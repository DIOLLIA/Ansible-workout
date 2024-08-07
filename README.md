# Ansible-workout
Project describes how to for windows


## Preparation

Install:
* Python
* WSL2 + Ububtu


### WSL2
Use commands in PowerShell (hereinafter - PSh), from the admin, to enable wsl2:

`Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux`

`Enable-WindowsOptionalFeature -Online -FeatureName VirtualMachinePlatform`

Download wsl core from https://wslstorestorage.blob.core.windows.net/wslblob/wsl_update_x64.msi

set the default version for Windows `wsl --set-default-version 2` from PSh

use `wsl --install -d ubuntu-24.04` to download and install 

