``MultiStateResolvable`` is a extended [``Resolvable``](../Resolvable/About.md) class that handles setting a property using a state from a [``MultiState``](../MultiState/About.md).

It works the same as if putting a state on a description, it will also detect state changes and changes the property if the state that was changed was the target state used in this resolvable.

Using it in a [``Description``](../Types/type_Description.md):
```lua
{
    ["PropertyName"] = Builder.MultiStateResolvable(MultiState, "StateName")
}
```