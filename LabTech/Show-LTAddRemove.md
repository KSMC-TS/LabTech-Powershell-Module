# Show-LTAddRemove
## SYNOPSIS
This function shows the LabTech install in the add/remove programs list.
## SYNTAX
```powershell
Show-LTAddRemove [-WhatIf] [-Confirm] [<CommonParameters>]
```
## DESCRIPTION
This function will rename the HiddenDisplayName registry key to show it in the add/remove programs list.
If there is not HiddenDisplayName key the function will import a new entry.
## PARAMETERS
### -WhatIf &lt;SwitchParameter&gt;

```
Required                    false
Position                    named
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -Confirm &lt;SwitchParameter&gt;

```
Required                    false
Position                    named
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
## NOTES
Version:        1.2

Author:         Chris Taylor

Website:        labtechconsulting.com

Creation Date:  3/14/2016

Purpose/Change: Initial script development



Update Date: 6/1/2017

Purpose/Change: Updates for better overall compatibility, including better support for PowerShell V2



Update Date: 3/12/2018

Purpose/Change: Support for ShouldProcess. Added Registry Paths to be checked. 

Modified hiding method to be compatible with standard software controls. 
