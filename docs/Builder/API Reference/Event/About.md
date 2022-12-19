``Event`` is a extended [``Resolvable``](../Resolvable/About.md) class that handles connecting a event with a function when building instances.

Using it in a [``Description``](../Types/type_Description.md):
```lua
{
    [Builder.Event("EventName")] = function(...) return end
}
```