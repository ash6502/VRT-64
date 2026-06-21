# Instruction Set for the VRT-64

### Notes:

HEX codes for the instructions are all TBD, and will be added later.

The ISA is heavily inspired by the 6502's instruction set.

Unless specified, most instructions output to R.

### Keywords and their meanings
X - X register

Y - Y register

R - Result Register

A - Accumulator

PC - Program Counter

*addr* - User-specified address

*val* - User-specified value

*subr* - Subroutine

### List of Instructions

| Instruction | Inputs | Description |
| ----------- | ------ | ----------- |
| ADD | None | Adds X with Y |
| SUB | None | Subtracts X with Y |
| AND | None | ANDs X with Y |
| NOT | None | NOTs X |
| OR | None | ORs X with Y |
| STA | *addr* | STores data from A into memory location *addr* |
| STX | *addr* | ditto, but stores from X |
| STY | *addr* | ditto, but stores from Y |
| FDA | *addr* | Fetches Data from memory location *addr* into A |
| FDX | *addr* | ditto, but stores into X |
| FDY | *addr* | ditto, but stores into Y |
| NOP | None | No OPeration |
| HLT | None | HaLTs system |
| JSR | *subr* | Jumps to specified SubRoutine |
