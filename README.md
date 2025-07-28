# Windows-Event-Log-Monitoring

This lab outlines the basics of using Sysmon, Windows Event Viewer, and PowerShell scripts to monitor and analyze Windows Event Logs for security incidents.

## Tools
- **Sysmon** for detailed logging of system activities.
- **Windows Event Viewer** for visualizing and analyzing event logs.
- **PowerShell scripts** for querying and processing event logs.

### Monitoring with Sysmon

Sysmon (System Monitor) is a Windows system service and device driver that logs system activity of Windows operating systems to the Windows Event Log. The following goes over some basic Sysmon queries in PowerShell with the Get-WinEvent commandlet that 
can be used to monitor and analyze activities on Windows systems configured with Sysmon. 




