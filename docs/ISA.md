# Instruction Set for the VRT-64

### Keywords and their meanings
X - X register
Y - Y register
R - Result Register
A - Accumulator
PC - Program Counter
*addr* - User-specified address
*val* - User-specified value
ditto - Same as above

### List of Instructions

`ADD` - Adds X with Y, outputs to R

`SUB` - Subtracts X with Y, outputs to R

`AND` - ANDs X with Y, outputs to R

`NOT` - NOTs X, outputs to R

`OR` - ORs X with Y, outputs to R

`STA` *addr* - STores data from A into memory at *addr*

`STX` *addr* - ditto, but stores from X

`STY` *addr* - ditto, but stores from Y

`FDA` *addr* - Fetches Data from memory location *addr*, and stores it in A

`FDX` *addr* - ditto, but stores into X

`FDY` *addr* - ditto, but stores into Y
