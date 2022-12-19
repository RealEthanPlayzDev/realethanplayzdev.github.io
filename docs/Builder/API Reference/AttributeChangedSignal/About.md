``AttributeChangedSignal`` is a extended [``Resolvable``](../Resolvable/About.md) class that handles attribute changes by connecting the passed function handler using ``Instance:GetAttributeChangedSignal()``.

!!! bug "Throws error if not ``Instance``"
    If the description where this ``AttributeChangedSignal`` is put is not a Roblox ``Instance``, it will throw a error while resolving.

Using it in a [``Description``](../Types/type_Description.md):
```lua
{
    [Builder.AttributeChangedSignal("AttributeName")] = function() return end
}
```