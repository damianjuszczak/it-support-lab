# Active Directory and Windows Server

Scripts and configuration notes for managing Active Directory, Group Policy, and user accounts.

## Files

- `new-ad-users.ps1` - PowerShell script that reads `new-users.csv`, checks if each account already exists, and creates new AD users with a temporary password and forced password reset at next logon.
- `new-users.csv` - Sample CSV input file with test employee details (`FirstName`, `LastName`, `Username`, `Department`).
- `gpo-setup.md` - Notes on configuring a mapped network drive (`S:`) and idle screen lock policy via Group Policy.