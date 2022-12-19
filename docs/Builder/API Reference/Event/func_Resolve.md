## Function information
```lua
function Event:Resolve(inst, value: (...any) -> (...any))
```

Resolves the ``Event`` by connecting to the target event on ``inst`` using ``value`` as the function handler.

## Arguments
- ``inst`` - The instance/class where the event exists
- ``value: (...any) -> (...any)`` - The event function handler