# first ISA

- R-type
|0-5   |6-8    |9-13 |14-18 |19-23  |
|:---  |:---   |:--- |:---  |:---   |
|Opcode|d_type |ra   |rb    |rd     |

- I-type
|0-5   |6-8    |9-13 |14-18 |19-31  |
|:---  |:---   |:--- |:---  |:---   |
|Opcode|d_type |ra   |rd    |imm    |

d_type: i8, i16, i32, f8, f16, f32

``` #!/bin/sh
add.i32 ra, rb, rd
addi.i32 ra, imm, rd
madd.i32 ra, rb, rd
ld.i32 ra, rd
st.i32 ra, rd
beq ra, rb, rd
jr rd
```
