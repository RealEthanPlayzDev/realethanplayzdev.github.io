## Event information
```lua
Cleaner.OnObjectRemoving :: RESignal
```

This event will fire each time an object is removed using [``Cleaner:Remove()``](./func_Remove.md).

The signal object used is not a ``RBXScriptSignal``, but my custom signal library called [RESignal](../../../RESignal/About.md).

## Passed arguments
| Number | Name | Type | Description                                                                |
| ------ | ---- | ---- | -------------------------------------------------------------------------- |
| 1      | obj  | any  | The object that was removed using [``Cleaner:Remove()``](./func_Remove.md) |