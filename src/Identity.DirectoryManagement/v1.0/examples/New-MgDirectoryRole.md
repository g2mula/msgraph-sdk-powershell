### Example 1: Code snippet

```powershell

Import-Module Microsoft.Graph.Identity.DirectoryManagement

$params = @{
	roleTemplateId = "fe930be7-5e62-47db-91af-98c3a49a38b1"
}

New-MgDirectoryRole -BodyParameter $params

```
This example shows how to use the New-MgDirectoryRole Cmdlet.

