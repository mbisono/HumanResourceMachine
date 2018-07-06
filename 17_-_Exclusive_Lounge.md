# 17 - Exclusive Lounge

```
-- HUMAN RESOURCE MACHINE PROGRAM --

    JUMP     f
a:
    INBOX   
    JUMPN    d
b:
    COPYFROM 4
    JUMP     e
c:
    INBOX   
    JUMPN    b
d:
    COPYFROM 5
e:
    OUTBOX  
f:
    INBOX   
    JUMPN    c
    JUMP     a



```