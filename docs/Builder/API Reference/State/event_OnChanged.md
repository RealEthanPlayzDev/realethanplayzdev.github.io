## Event information
```lua
State.OnChanged :: RESignal
```

This event fires each time [``State:Set()``](./func_Set.md) called, first argument will be the new value and the second argument will be the old value.

The signal object used is not a ``RBXScriptSignal``, but my custom signal library called [RESignal](../../../RESignal/About.md).