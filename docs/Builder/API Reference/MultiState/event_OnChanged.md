## Event information
```lua
MultiState.OnChanged :: RESignal
```

This event fires each time [``MultiState:Set()``](./func_Set.md) called, first argument will be the state name, second argument will be the new value, and third argument will be the old value.

The signal object used is not a ``RBXScriptSignal``, but my custom signal library called [RESignal](../../../RESignal/About.md).