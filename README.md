
## Study Assembly


### compile

> gcc hello.s

### register

| 32 | 16 | 8 | mean |
|:--:|:--:|:--:|:--:|
| EAX | AX | AH, AL | accumulater |
| EBX | BX | BH, BL | base register |
| ECX | CX | CH, CL | counter register |
| EDX | DX | DH, DL | |
| ESI | SI || source |
| EDI | DI || destination |
| EBP | BP || base pointer |
| EIP | IP || instruction pointer |
| ESP | SP || stack pointer |

### mnemonic

> movb $0x01 %al

opecode: movb
operand: $0x01, %al


### opecode

| bit | mean | e.g. | | register |
|:--:|:--:|:--:|:--:|:--:|
| 8 | byte | movb | | |
| 16 | words | movw | eXtend | %ax |
| 32 | long | movl | Extend | %eax |
| 32 | doublewords | movd | | |
| 64 | quadword | movq | | |


number > $  
register > % 



