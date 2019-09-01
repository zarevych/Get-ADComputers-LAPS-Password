# Get-ADComputers-LAPS-Password


Get LAPS Passwords information from Active Directory.

Generates a CSV file with computer names and LAPS Passwords.



## Requirement of the script:
- Active Directory PowerShell Module
- Needed rights to view AD LAPS Attributes: ms-Mcs-AdmPwd, ms-Mcs-AdmPwdExpirationTime



## Usage
```powershell
.\Get-ADComputers-LAPS-Password.ps1
```
or 
```powershell
.\Get-ADComputers-LAPS-Password.ps1 -OU "OU=Computers,OU=IT Department,DC=myDomain,DC=com"
```
