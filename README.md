# LPU-1 (Little Processing Unit)
A super basic CPU designed using logisim.

# Instructions
LPU-1 has 11 instructions:

| Instuction         | Description                                                                                    | Op-Code (binary) |
| :----------------: | ---------------------------------------------------------------------------------------------- |------------------|
|  ADD               | Adds register A to register B and stores the result in the Accumulator                         | 0001             |
|  SUB               | Subtracts the contents of register B from register A and stores the result in the Accumulator  | 0010             |
|  PUT [REGISTER], X | Puts the value X in [REGISTER]                                                                 | 0011             |
|  JMP X             | Jumps to location X                                                                            | 0100             |
|  JEZ X             | Jumps to location X if register A's contents is equal to 0                                     | 0101             |
|  JNC X             | Jumps to location X if the carry register is not 1                                             | 0110             |
|  MOV [REGISTER], Y | Puts the value Y into [REGISTER]                                                               | 0111             |
|  LDA               | Loads the value from an address held in register A into the accumulator                        | 1000             |
|  STA               | Stores the value held in the accumulator into an address held in register A                    | 1001             |
|  AA                | Moves the value held in the accumulator to register A                                          | 1010             |
|  HLT               | Stops the clock                                                                                | 1111             |
