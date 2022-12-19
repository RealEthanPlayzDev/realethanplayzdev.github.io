## Function information
```lua
function PropertyChangedSignal:Resolve(inst, value: (...any) -> (...any))
```

Resolves the ``PropertyChangedSignal`` by calling ``(Instance | Class):GetPropertyChangedSignal()`` with the property name as the first argument and then connects the event returned by the function using ``value``.

## Arguments
- ``inst`` - The target instance/class
- ``value: (...any) -> (...any)`` - The function to be connected handling property changes