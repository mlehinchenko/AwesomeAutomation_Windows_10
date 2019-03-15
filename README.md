Please enter here command neededs for Windows 10 setup to start Automation
start Powershell ISE as administrator copy the commands below and press start button for now java, maven and rest of application are installed in default path and do not write nothing to PATH variables for maven. For future I planned to fix it.

# Scoop and Chocolatey are pretty the same.

## Install chocolatey
```
Get-PackageProvider -Name chocolatey -Force
Set-PackageSource -Name chocolatey -trusted -Force
Set-ExecutionPolicy RemoteSigned -Force
Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
```

## Install scoop
Make sure Powershell 3 (or later) and .NET Framework 4.5 (or later) are installed. Then run:
```
Set-ExecutionPolicy RemoteSigned -scope CurrentUser
iex (new-object net.webclient).downloadstring('https://get.scoop.sh')
```
### You can find any package by using:
```
scoop search 'packagename'     ---for scoop
Find-Package 'packagename'     ---for chocolatey
```

## Git
```
install-package -name git -Force
```


## Browsers
```
install-package -name GoogleChrome -Force
install-package -name Firefox -Force
```

## Skype,Slack,Viber,WhatApp
```
install-package -name skype  -Force
install-package -name slack -Force
```

## Editors
```
install-package -name notepadplusplus -Force
```

## Java
```
install-package -name jdk8 -Force
```


## Maven
```
install-package -name maven -Force
```


## IDE
```
install-package -name eclipse -Force
scoop install extras/idea
```



## Automation Drivers
```
install-package -name selenium-gecko-driver -Force
install-package -name chromedriver -Force
scoop install windows-application-driver
```

