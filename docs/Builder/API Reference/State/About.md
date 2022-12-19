``State`` is a object that stores a value, it's basically just like a variable.

You can use a ``State`` object directly in a [``Description``](../Types/type_Description.md), like below:
```lua
{
    ["PropertyName"] = State
}
```
It will also use [``State.OnChanged``](./event_OnChanged.md) for detecting changes via [``State:Set()``](./func_Set.md) and will automatically set the property with the new value.