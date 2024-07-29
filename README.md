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


