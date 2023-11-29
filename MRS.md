# MRS  Instruction

## full form: Move to Register from Special Register

ARM uses a load-store model for memory access which means that only load/store (LDR and STR) instructions can access memory.
so we need Instruction for Special Registers.
MRS comes in handy to load special registers in to generel purpose registers.

for Example:

MRS x0, CPSR
