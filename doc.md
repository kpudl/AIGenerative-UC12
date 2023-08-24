# WatchFolderManager Class


## Definition
Class that represents watch folders files. It is responsible for finding,  adding, removing, updating folders in selected files that are on the computer. It implements IDisposable interface - it provides a mechanism for releasing unmanaged resources.

**Namespace:** <a href="e524df4e-c53b-2cd1-fc17-cf729d9631d2">ShareX</a>  
**Assembly:** ShareX (in ShareX.exe) Version: 15.0.1.0 (15.0.1)

**C#**
``` C#
public class WatchFolderManager : IDisposable
```

<table><tr><td><strong>Inheritance</strong></td><td><a href="https://learn.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>  →  WatchFolderManager</td></tr>
<tr><td><strong>Implements</strong></td><td><a href="https://learn.microsoft.com/dotnet/api/system.idisposable" target="_blank" rel="noopener noreferrer">IDisposable</a></td></tr>
</table>



## Constructors
<table>
<tr>
<td><a href="51cbd0f7-6303-fb06-e54a-fcbe3d4b90c4">WatchFolderManager</a></td>
<td>Initializes a new instance of the WatchFolderManager class</td></tr>
</table>

## Properties
<table>
<tr>
<td><a href="8515598d-1c1c-adad-ceba-317a63b5909a">WatchFolders</a></td>
<td>Gets list of watch folders to go through </td></tr>
</table>

## Methods
<table>
<tr>
<td><a href="AddWatchFolder">AddWatchFolder</a></td>
<td>Method to add new watch folder to the list </td></tr>
<tr>
<td><a href="94a59966-7849-2ba8-0577-7e234910b827">Dispose</a></td>
<td>Releases all resources used by the WatchFolderManager</td></tr>
<tr>
<td><a href="https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)" target="_blank" rel="noopener noreferrer">Equals</a></td>
<td>Determines whether the specified object is equal to the current object.<br />(Inherited from <a href="https://learn.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>)</td></tr>
<tr>
<td><a href="https://learn.microsoft.com/dotnet/api/system.object.finalize#system-object-finalize" target="_blank" rel="noopener noreferrer">Finalize</a></td>
<td>Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.<br />(Inherited from <a href="https://learn.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>)</td></tr>
<tr>
<td><a href="https://learn.microsoft.com/dotnet/api/system.object.gethashcode#system-object-gethashcode" target="_blank" rel="noopener noreferrer">GetHashCode</a></td>
<td>Serves as the default hash function.<br />(Inherited from <a href="https://learn.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>)</td></tr>
<tr>
<td><a href="https://learn.microsoft.com/dotnet/api/system.object.gettype#system-object-gettype" target="_blank" rel="noopener noreferrer">GetType</a></td>
<td>Gets the <a href="https://learn.microsoft.com/dotnet/api/system.type" target="_blank" rel="noopener noreferrer">Type</a> of the current instance.<br />(Inherited from <a href="https://learn.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>)</td></tr>
<tr>
<td><a href="https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone#system-object-memberwiseclone" target="_blank" rel="noopener noreferrer">MemberwiseClone</a></td>
<td>Creates a shallow copy of the current <a href="https://learn.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>.<br />(Inherited from <a href="https://learn.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>)</td></tr>
<tr>
<td><a href="RemoveWatchFolder">RemoveWatchFolder</a></td>
<td>Method to remove watch folder from the list </td></tr>
<tr>
<td><a href="https://learn.microsoft.com/dotnet/api/system.object.tostring#system-object-tostring" target="_blank" rel="noopener noreferrer">ToString</a></td>
<td>Returns a string that represents the current object.<br />(Inherited from <a href="https://learn.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>)</td></tr>
<tr>
<td><a href="UnregisterAllWatchFolders">UnregisterAllWatchFolders</a></td>
<td>Method to dispose of all atch folders from WatchFolders list. </td></tr>
<tr>
<td><a href="UpdateWatchFolders">UpdateWatchFolders</a></td>
<td>Method to update watch folder state - find existing folder and enable/disable it according to WatchFolderEnabled parameter. </td></tr>
<tr>
<td><a href="UpdateWatchFolderState">UpdateWatchFolderState</a></td>
<td>Method to get current version of folders on your computer. It unregisters WatchFolders. Then it adds from the start all folders (from existing files and and hotkeys) </td></tr>
</table>

## See Also


#### Reference
<a href="e524df4e-c53b-2cd1-fc17-cf729d9631d2">ShareX Namespace</a>  
