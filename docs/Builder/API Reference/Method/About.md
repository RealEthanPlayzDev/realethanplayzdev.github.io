``Method`` is a extended [``Resolvable``](../Resolvable/About.md) class that handles calling a method when building instances.

Using it in a [``Description``](../Types/type_Description.md):
```lua
{
    [Builder.Method("MethodName")] = {"Arg1", "Arg2"}
}
```