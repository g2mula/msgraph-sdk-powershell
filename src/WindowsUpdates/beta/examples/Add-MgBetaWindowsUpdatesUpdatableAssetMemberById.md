### Example 1: Code snippet

```powershell

Import-Module Microsoft.Graph.Beta.WindowsUpdates

$params = @{
	ids = @(
	"String"
"String"
"String"
)
memberEntityType = "#microsoft.graph.windowsUpdates.azureADDevice"
}

Add-MgBetaWindowsUpdatesUpdatableAssetMemberById -UpdatableAssetId $updatableAssetId -BodyParameter $params

```
This example shows how to use the Add-MgBetaWindowsUpdatesUpdatableAssetMemberById Cmdlet.

