## Type information
```lua
export type Description = {[string | number | Event | Method | PropertyChangedSignal | Attribute | AttributeChangedSignal]: any}
```

A description is a dictionary-array mix. The key of the array is either a property name (string) or a resolvable object. The value is usually another Instance, [``Descriptor``](../Descriptor/About.md), a [``State``](../State/About.md), or the value for the resolvable/property.

## Example
```lua
local Builder = require(path.to.builder)
local Descriptor = Builder.Descriptor

local NameState = Builder.State("Hello")
NameState:Set("Hello World")

local MultiStateObj = Builder.Multistate({Anchored = false})
MultiStateObj:Set("Anchored", true)

local AInstance = Instance.new("SurfaceGui")

local PLDescriptor = Descriptor("PointLight", { Name = "Yes" })

local FinalPartDescriptor = Descriptor("Part", {
    Name = NameState;
    Anchored = Builder.MultiStateResolvable(MultiStateObj, "Anchored");
    CanCollide = true;
    Transparency = 0.5;
    Material = Enum.Material.Glass;
    [Builder.Attribute("TestsEnabled")] = true;
    [Builder.AttributeChangedSignal("TestsEnabled")] = print;
    [Builder.PropertyChangedSignal("Anchored")] = warn;
    [Builder.Event("DescendantAdded")] = print;
    [Builder.Method("GetPivot")] = print;
    AInstance;
    PLDescriptor;
})

FinalPartDescriptor:Build().Parent = workspace
```