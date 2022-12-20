## Event information
```lua
Cleaner.OnObjectCleaning :: RESignal
```

This event will fire each time before an object is destroyed using [``Cleaner:Clean()``](./func_Clean.md).

The signal object used is not a ``RBXScriptSignal``, but my custom signal library called [RESignal](../../../RESignal/About.md).

## Passed arguments
| Number | Name             | Type    | Description                                                                           |
| ------ | ---------------- | ------- | ------------------------------------------------------------------------------------- |
| 1      | obj              | any     | The object that is about to be destroyed using [``Cleaner:Clean()``](./func_Clean.md) |
| 2      | destroyfuncname  | string  | The destroyer function method name used to destroy the object                         |