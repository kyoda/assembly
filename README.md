
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

### jump

| jump | mean |
|:--:|:--:|
| ja | a < b |
| jae | a <= b |
| jb | a > b |
| jbe | a >= b |
| je | a = b |
| jne | a != b |
| jc | CF = 1 |
| jz | ZF = 1 |


### Linux System Calls

| %eax | name | %ebx | %ecx | %edx | %esx | %edi |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| 1 | exit | int | - | - | - | - |
| 2 | fork | struct pt_regs | - | - | - | - |
| 3 | read | unsigned int | char * | size_t | - | - |
| 4 | write | unsigned int | const char * | size_t | - | - |
| 5 | open | const char * | int | int | - | - |






