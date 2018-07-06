#24 - Mod Module

```
-- HUMAN RESOURCE MACHINE PROGRAM --

    JUMP     b
a:
    ADD      1
    OUTBOX  
b:
    INBOX   
    COPYTO   0
    INBOX   
    COPYTO   1
    COPYFROM 0
c:
    SUB      1
    JUMPN    a
    JUMP     c



```