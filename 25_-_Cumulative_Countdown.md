# 25 - Cumulative Countdown

## Targets
Size: 12 / Speed: 82

## Size / Speed
```
-- HUMAN RESOURCE MACHINE PROGRAM --

    JUMP     c
a:
    COPYFROM 1
b:
    OUTBOX  
c:
    INBOX   
    JUMPZ    b
    COPYTO   0
d:
    COPYTO   1
    BUMPDN   0
    JUMPZ    a
    ADD      1
    JUMP     d



```