# Notes
Technical notes

md c:\\HWID
Set-Location c:\\HWID
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Unrestricted
Install-Script -Name Get-WindowsAutoPilotInfo
Get-WindowsAutoPilotInfo.ps1 -Grouptag MDContractor -OutputFile "$env:COMPUTERNAME.csv"
