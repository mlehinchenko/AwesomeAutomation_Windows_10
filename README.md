Please enter here command neededs for Windows 10 setup to start Automation
start Powershell ISE as administrator copy the commands below and press start button for now java, maven and rest of application are installed in default path and do not write nothing to PATH variables. For future I planned to fix it.

#          ---install chocolatey -------

Get-PackageProvider -Name chocolatey -Force
Set-PackageSource -Name chocolatey -trusted -Force
Set-ExecutionPolicy RemoteSigned -Force

install-package -name jdk8 -Force
install-package -name maven -Force

install-package -name skype  -Force
install-package -name slack -Force

install-package -name GoogleChrome -Force
install-package -name chromedriver -Force
install-package -name Firefox -Force
install-package -name selenium-gecko-driver -Force
