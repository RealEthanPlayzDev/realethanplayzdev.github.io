``DynamicState`` is similar to a ``State``, with the difference is that ``DynamicState:Get()`` returns from a function set for it.

Just like ``State``, you can use a ``DynamicState`` object directly in a [``Description``](../Types/type_Description.md), like below:
```lua
{
    ["PropertyName"] = DynamicState
}
```
However, keep in mind that ``DynamicState``s do not have a changed signal, they will not be automatically updated.