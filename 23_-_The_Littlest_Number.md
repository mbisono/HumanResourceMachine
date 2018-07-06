# 23 - The Littlest Number

## Targets
Size: 13 / Speed: 75

## Size / Speed
```
-- HUMAN RESOURCE MACHINE PROGRAM --

    JUMP     b
a:
    COPYFROM 0
    OUTBOX  
b:
    INBOX   
c:
    COPYTO   0
d:
    INBOX   
    JUMPZ    a
    SUB      0
    JUMPN    e
    JUMP     d
e:
    ADD      0
    JUMP     c



```