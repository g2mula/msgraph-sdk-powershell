### Example 1: Code snippet

```powershellImport-Module Microsoft.Graph.Users

# A UPN can also be used as -UserId.
Get-MgUserTodoListTask -UserId $userId -TodoTaskListId $todoTaskListId -TodoTaskId $todoTaskId
```
This example shows how to use the Get-MgUserTodoListTask Cmdlet.
To learn about permissions for this resource, see the [permissions reference](/graph/permissions-reference).

