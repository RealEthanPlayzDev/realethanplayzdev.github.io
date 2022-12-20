## Event information
```lua
State.OnChanged :: RESignal
```

This event fires each time [``State:Set()``](./func_Set.md) called.

The signal object used is not a ``RBXScriptSignal``, but my custom signal library called [RESignal](../../../RESignal/About.md).

## Passed arguments
| Number | Name   | Type | Description   |
| ------ | ------ | ---- | ------------- |
| 1      | newval | any  | The new value |
| 2      | oldval | any  | The old value |