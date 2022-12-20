## Event information
```lua
Cleaner.OnObjectAdded :: RESignal
```

This event will fire each time an object is added using [``Cleaner:Add()``](./func_Add.md).

The signal object used is not a ``RBXScriptSignal``, but my custom signal library called [RESignal](../../../RESignal/About.md).

## Passed arguments
| Number | Name | Type | Description                                                        |
| ------ | ---- | ---- | ------------------------------------------------------------------ |
| 1      | obj  | any  | The object that was added using [``Cleaner:Add()``](./func_Add.md) |