# Windows-Event-Log-Monitoring

This lab outlines some basics on using Sysmon, Windows Event Viewer, and PowerShell to monitor and analyze Windows Event Logs for security incidents. 

## Tools
- **Sysmon** for detailed logging of system activities.
- **Windows Event Viewer** for visualizing and analyzing event logs.
- **PowerShell** for querying and processing event logs.

### Monitoring with Sysmon

Sysmon (System Monitor) is a Windows system service and device driver that logs system activity to the Windows Event Log. The following goes over some basic Sysmon queries in PowerShell with the Get-WinEvent commandlet that 
can be used to monitor and analyze activities on Windows systems configured with Sysmon. 


#### List All Sysmon Events
![List All Sysmon Events.PNG](Images/List%20All%20Sysmon%20Events.PNG)

#### List All Network Connection Events

![List all network connection events.PNG](Images/List%20all%20network%20connection%20events.PNG)

#### List All Process Creation Events

![List all process creation events.PNG](Images/List%20all%20process%20creation%20events.PNG)

#### List Events for New Files Created

![List new files created.PNG](Images/List%20new%20files%20created.PNG)

#### List Events for File Modifications

![List events for file modifications.PNG](Images/List%20events%20for%20file%20modifications.PNG)

#### Monitor for Remote Thread Creation

![Monitor for Remote Thread Creation.PNG](Images/Monitor%20for%20Remote%20Thread%20Creation.PNG)

#### Monitor for Changes to the Registry

![Monitor for changes to the registry.PNG](Images/Monitor%20for%20changes%20to%20the%20registry.PNG)

#### List Failed Logon Attempts

![Retrieve Failed Logon Attempts.PNG](Images/Retrieve%20Failed%20Logon%20Attempts.PNG)

#### List Successful Login Events

![Retrieve Successful Login Events.PNG](Images/Retrieve%20Successful%20Login%20Events.PNG)


