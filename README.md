#WSUS ID cleanup playbook
* This script removes the WSUS ID so it can be regenerated. ID should be unique for WSUS reporting to work correctly, but it can get duplicated when cloning or deploying VMs from a template. 
* Based on https://gallery.technet.microsoft.com/scriptcenter/Reset-WSUS-Authorization-2e26d1b0
* Tested on Windows Sever 2012R2 and 2016 but should be compatible with all currently supported versions of Windows Server
* Includes variables for WinRM over HTTP. Feel free to remove or modify them.
