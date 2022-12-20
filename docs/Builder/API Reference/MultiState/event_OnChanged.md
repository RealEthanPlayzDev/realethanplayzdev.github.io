## Event information
```lua
MultiState.OnChanged :: RESignal
```

This event fires each time [``MultiState:Set()``](./func_Set.md) called.

The signal object used is not a ``RBXScriptSignal``, but my custom signal library called [RESignal](../../../RESignal/About.md).

## Passed arguments
| Number | Name      | Type | Description    |
| ------ | --------- | ---- | -------------- |
| 1      | statename | any  | The state name |
| 2      | newval    | any  | The new value  |
| 3      | oldval    | any  | The old value  |