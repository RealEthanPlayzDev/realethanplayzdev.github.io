## Event information
```lua
Cleaner.OnCleanup :: RESignal
```

This event will fire once before [``Cleaner:Clean()``](./func_Clean.md) starts destroying objects in the cleanup list.

The signal object used is not a ``RBXScriptSignal``, but my custom signal library called [RESignal](../../../RESignal/About.md).

## Passed arguments
| Number | Name    | Type    | Description                                                                           |
| ------ | ------- | ------- | ------------------------------------ |
| 1      | objects | {any}   | The array of objects to be destroyed |