# Off-by-One Error in Assembly Stack Pointer Arithmetic
This repository demonstrates a common off-by-one error in assembly code involving stack pointer manipulation. The error leads to incorrect calculations because of an improper adjustment to the stack pointer.

## Bug Description
The assembly code attempts to increment a value located on the stack. However, due to an off-by-one error in the calculation of the stack pointer offset, it results in an incorrect increment.