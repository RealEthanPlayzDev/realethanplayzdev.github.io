## Function information
```lua
function Method:Resolve(inst, value: {any})
```

Resolves the ``Method`` by calling the method on ``inst`` with the unpacked values of ``value`` passed as argument.

## Arguments
- ``inst`` - The instance/class where the method exists
- ``value: {any}`` - The arguments of the function, this table will be unpacked when resolved using ``table.unpack``