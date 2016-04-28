# About these cmdlets

## Requirements

* User signed on to an appropriate AD FS server as Administrator (or
  Administrator-level user).
* PowerShell v3 or later installed on the server.
* (Optional) A previously-created AD group to which the users
  authorized to use Silent Circle belong (or will belong).

## Before running the cmdlets

* Save the cmdlet to a local directory on the server.
* Start a PowerShell session.
* Ensure the current session's execution policy is set to
  `Unrestricted` as follows:

```
PS C:\Users\Administrator> Set-ExecutionPolicy Unrestricted

Execution Policy Change
The execution policy helps protect you from cmdlets that you do not trust. Changing the execution policy might expose
you to the security risks described in the about_Execution_Policies help topic at
http://go.microsoft.com/fwlink/?LinkID=135170. Do you want to change the execution policy?
[Y] Yes  [N] No  [S] Suspend  [?] Help (default is "Y"): Y
```

## Help Documentation

The cmdlets have detailed on-line help documentation that can be
seen by running the following commands:

```ps1
Get-Help .\Add-SilentCircleRelyingPartyTrust.ps1 -Full
Get-Help .\Remove-SilentCircleRelyingPartyTrust.ps1 -Full
```


