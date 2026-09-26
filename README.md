# Simple-Turing-Interpreter

Interprets a basic turing machine instruction set and runs it on a single two-way infinite tape using a hexadecimal alphabet Σ!

## Goals

- [ ] Design simple context-free language grammar that allows the definition of ifs with the ability to either shift left/right, halt or jump to another named instruction card
- [ ] Implement an interpreter able to lex, parse and then execute the instructions from the start while storing the infinite tape in memory using 8-bit typed arrays
- [ ] Implement reflection API returning callbacks that allow each operation to be caught and visualised on a front-end
- [ ] Visually represent the turing machine on a simple web front-end where code can be written and sent to the machine for execution. Show the current finite length of the written band (even though it's in theory infinite, almost all cells will be empty) after each operation
- [ ] Maybe some other interesting stuff?
