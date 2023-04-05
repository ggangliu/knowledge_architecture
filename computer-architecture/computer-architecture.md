# Computer Architecture

## Datapath

### Datapath without control signal

![CPU datapath overview](../images/datapath.png)

### Datapath with control signal

![CPU datapath overview](../images/datapath_with_control.png)

## Instruction Set

### Format

- R-type
![R-type](../images/r-type.png)
  - add rd, rs, rt
  - sub rd, rs, rt
  - and rd, rs, rt
  - or  rd, rs, rt
  - slt rd, rs, rt
- I-type
![I-type](../images/i-type.png)
  - lw   rt, rs, imm16
  - st   rt, rs, imm16
  - addi rt, rs, imm16
  - beq  rt, rs, imm16
- J-type
![J-type](../images/j-type.png)
  - j target

## Pipelining

### Single cycle datapath

- IF(Instruction Fetch)
- ID(Instruction Decode and register file read)
- EX(Execution or address calculation)
- MEM(Data memory access)
- WB(Write back)
