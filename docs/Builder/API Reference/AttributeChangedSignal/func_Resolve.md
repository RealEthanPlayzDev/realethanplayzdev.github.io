## Function information
```lua
function AttributeChangedSignal:Resolve(inst, value: (...any) -> (...any))
```

Resolves the ``AttributeChangedSignal`` by calling ``Instance:GetAttributeChangedSignal()`` with the attribute name as the first argument and then connects the event returned by the function using ``value``.

## Arguments
- ``inst`` - The target instance/class
- ``value: (...any) -> (...any)`` - The function to be connected handling attribute changes