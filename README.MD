# Bundling

## Problem 

    - Code gets hard to manage as projects get more complex. 
    -  It gets easier if we split code into smaller files
    - Browsers dont like using imports ('require' or 'import')
    - We coudl link each file seprately but it gets messy

## Solution (bundlers)

    - Massively hacky
    - Write the code in seperate files, using imports.
    - Get a tool (bundlers)
    - Use the tool to package up all teh files into a single file.
    - he single file contains all the code required, in the right order. 


## Transpilation

- Compilation: translate in one language down to another machine-focussed language
- Transpilation: translate in one language across to another at the same level of abstraction 

'console.log(3)' --> 'OUT 3' 
'console.log(3)' --> 'print(3)

- there are **so many** version of JS in use.

