Please enter here command neededs for Windows 10 setup to start Automation
start Powershell ISE as administrator copy the commands below and press start button for now java, maven and rest of application are installed in default path and do not write nothing to PATH variables for maven. For future I planned to fix it.

# Install chocolatey
```
Get-PackageProvider -Name chocolatey -Force
Set-PackageSource -Name chocolatey -trusted -Force
Set-ExecutionPolicy RemoteSigned -Force
```

# Install scoop
```
Get-PackageProvider -Name chocolatey -Force
Set-PackageSource -Name chocolatey -trusted -Force
Set-ExecutionPolicy RemoteSigned -Force
```


# Git
```
install-package -name git -Force
```


# Browsers
```
install-package -name GoogleChrome -Force
install-package -name Firefox -Force
```

# Skype,Slack,Viber,WhatApp
```
install-package -name skype  -Force
install-package -name slack -Force
```

# Editors
```
install-package -name notepadplusplus -Force
```

# Java
```
install-package -name jdk8 -Force
```


# Maven
```
install-package -name maven -Force
```


# IDE
```
install-package -name eclipse -Force
```



# Automation Drivers
```
install-package -name selenium-gecko-driver -Force
install-package -name chromedriver -Force
```

