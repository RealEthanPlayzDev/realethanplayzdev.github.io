## Function info
```lua
function LuauInLuau.Compile(src: string): (success: boolean, bytecode: string, bytecodelength: number)
```

Compiles ``src`` into Luau bytecode if there are no syntax/compile errors

## Arguments
- ``src: string`` - The source

## Returns
- ``success: boolean`` - Indicates whether the compiler successfully compiled ``src`` into bytecode or not
- ``bytecode: string`` - The bytecode
- ``bytecodelength: number`` - The bytecode length