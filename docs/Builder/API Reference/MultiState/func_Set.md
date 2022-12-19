## Function information
```lua
function MultiState:Set(name: any, value: any)
```

Sets the value in the ``MultiState`` using ``name`` as the key and ``value`` as the new value, and then fires all callbacks connected to [``MultiState.OnChanged``](./event_OnChanged.md).