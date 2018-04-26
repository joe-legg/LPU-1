# LPU-1 (Little Processing Unit)
A super basic CPU designed using logisim.

# Instructions
LPU-1 has 11 instructions:

| Instuction         | Description                                                                                    |
| :----------------: | ---------------------------------------------------------------------------------------------- |
|  ADD               | Adds register A to register B and stores the result in the Accumulator                         |
|  SUB               | Subtracts the contents of register B from register A and stores the result in the Accumulator  |
|  PUT [REGISTER], X | Puts the value X in [REGISTER]                                                                 |
|  JMP X             | Jumps to location X                                                                            |
|  JEZ X             | Jumps to location X if register A's contents is equal to 0                                     |
|  JNC X             | Jumps to location X if the carry register is not 1                                             |
|  MOV [REGISTER], Y | Puts the value Y into [REGISTER]                                                               |
|  LDA               | Loads the value from an address held in register A into the accumulator                        |
|  STA               | Stores the value held in the accumulator into an address held in register A                    |
|  AA                | Moves the value held in the accumulator to register A                                          |
|  HLT               | Stops the clock                                                                                |
