## Function info
```lua
function LuauInLuau.Compile(src: string, optimizationlevel: number?, debuglevel: number?): (success: boolean, bytecode: string, bytecodelength: number)
```

Compiles ``src`` into Luau bytecode if there are no syntax/compile errors

## Arguments
- ``src: string`` - The source
- ``optimizationlevel: number?`` - The optimization level for the resulting bytecode
- ``debuglevel: number?`` - The debug level for the resulting bytecode

!!! bug "Important note regarding the optimization and debug level arguments"
    The ``optimizationlevel`` and ``debuglevel`` argument is only available starting with LuauInLuau v0.579

## Returns
- ``success: boolean`` - Indicates whether the compiler successfully compiled ``src`` into bytecode or not
- ``bytecode: string`` - The bytecode
- ``bytecodelength: number`` - The bytecode length