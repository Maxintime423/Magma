# Matur Bytecode
- Before making anything, I thought of making a road map.
- I have started building the bytecode .
- For making the bytecode easier to write . I will use compiler which converts MaturAssembly to actual MaturBytecode.
- This Matur Bytecode will run in Matur Virtual Machine.

## Instructions in MaturBytecode
- There will be a total of ***255*** instructions (headers only, excluding parameters). So a instruction is exactly one byte .
- Every Instruction is followed by some parameters or array of data. 

- Example: 
''' TerminalWrite "Hello Man" -> 01 AA .... -> Prints to the Terminal '''

## The 00 instruction is excluded as it will be used as C style null terminator instead of pascal like thing .

### -by Mallikarjun.S.Matur 