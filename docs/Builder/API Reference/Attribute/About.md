``Attribute`` is a extended [``Resolvable``](../Resolvable/About.md) class that sets a attribute when building instances.

!!! bug "Throws error if not ``Instance``"
    If the description where this ``Attribute`` is put is not a Roblox ``Instance``, it will throw a error while resolving.

Using it in a [``Description``](../Types/type_Description.md):
```lua
{
    [Builder.Attribute("AttributeName")] = AttributeValue
}
```