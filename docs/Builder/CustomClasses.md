Builder supports custom classes, custom classes must be inside a ModuleScript within the search range of the descriptor, and must return a field called ``new`` acting as the constructor.

By default, the module finds custom classes under a folder called ``CustomClasses`` parented to the root of the Builder ModuleScript.

[``Descriptor``](./API%20Reference/Descriptor/About.md) has a field, [``Descriptor.CustomClassesLocation``](./API%20Reference/Descriptor/publicvar_CustomClassesLocation.md) that can be set as a alternative custom class search path, it overrides the default search path.