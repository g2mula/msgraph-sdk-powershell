### Example 1: Code snippet

```powershellImport-Module Microsoft.Graph.PersonalContacts

# A UPN can also be used as -UserId.
Remove-MgUserContact -UserId $userId -ContactId $contactId
```
This example shows how to use the Remove-MgUserContact Cmdlet.
To learn about permissions for this resource, see the [permissions reference](/graph/permissions-reference).

