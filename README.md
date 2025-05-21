# WacAzLocalhelp
Wac Azure Local Helper


## Help for collecting logs for Open Manage Integration for Windows Admin Center 3.3.2 ## 

## Help checking firewalls and other WAC and Azure Local Clean up for WAC ##


``` Powershell
echo WinClusArcHelper; [Net.ServicePointManager]::SecurityProtocol = [Net.SecurityProtocolType]::Tls12; $path=Join-Path $PWD 'RunHelp.ps1'; (New-Object Net.WebClient).DownloadFile('https://github.com/Louisjreeves/WacAzLocalhelp/raw/refs/heads/main/RunHelp.ps1', $path); & $path
```
