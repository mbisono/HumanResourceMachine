# 28 - Three Sort	

## Targets
Size: 34 / Speed: 78

## Size
```
-- HUMAN RESOURCE MACHINE PROGRAM --

a:
    INBOX   
    COPYTO   0
    INBOX   
    COPYTO   1
    INBOX   
    COPYTO   2
b:
c:
    COPYFROM 0
    SUB      1
    JUMPN    d
    JUMP     e
d:
    COPYFROM 0
    COPYTO   5
    COPYFROM 1
    COPYTO   0
    COPYFROM 5
    COPYTO   1
    JUMP     c
e:
    COPYFROM 1
    SUB      2
    JUMPN    f
    COPYFROM 2
    OUTBOX  
    COPYFROM 1
    OUTBOX  
    COPYFROM 0
    OUTBOX  
    JUMP     a
f:
    COPYFROM 1
    COPYTO   5
    COPYFROM 2
    COPYTO   1
    COPYFROM 5
    COPYTO   2
    JUMP     b


DEFINE LABEL 0
eJwTYmBgWKAREKmkOy04WX+7j4qBu6eKgZNjsn6vc7I+o7+zXkAks75lwRH9z6UqBtzzgMoZ5FS4591T
CV3goFG9MFm/euHtmAOzGUbBKBgFQxIAAOsbFkM;

DEFINE LABEL 1
eJwTZmBgOKjZUXVQ833uIm3+9GfGr1Kfm/Gnn7Coz/K2de/gtiubudr21ZKVVvEbjhqt23VQU27fTWm5
fX+VLu9O0PyxR0nXeX+yvtKxDW65JxhGwSgYBUMOAACfYiJZ;

DEFINE LABEL 2
eJwTZGBgYDVycjxq9MNOy+aH3Rt7WQc/5+uuBe5s4RM9qpImesQVbnCzqzhumlyZbefc0O/KPe+9a9SK
d07v17yxF1l3RD9+A8MoGAWjYMgCAL4ZG5g;

DEFINE LABEL 5
eJzTZWBg6BSfPOmy8PzZosJqC0SFjVbmiMluPC22ZCtQiqGVN7VjpqBze4h8aoeNhmIbSGy2xuxjvzQ+
Hzig9nz7AbVb6+6qr1lSpnVrXbfe8+2PDDl2Vpsc3bbV7Na6CRYH50ywaOvMttoyWdM6ZNVz61vrkm2b
tlx37N8LMsfbTbGt1/V1T6/rtSmc7pmL9nsd3QYS3+TM0MrotbdJO4ih9WWQc/vLoJPdZwL1+o39AybM
8vkxlWEUjIJRQDUAAAQWTC4;


```

## Speed
```
-- HUMAN RESOURCE MACHINE PROGRAM --

a:
b:
c:
d:
e:
    INBOX   
    COPYTO   0
    INBOX   
    COPYTO   1
    INBOX   
    COPYTO   2
    SUB      1
    JUMPN    h
    COMMENT  1
    COPYFROM 1
    SUB      0
    JUMPN    f
    COMMENT  4
    COPYFROM 0
    OUTBOX  
    COPYFROM 1
    OUTBOX  
    COPYFROM 2
    OUTBOX  
    JUMP     c
f:
    COMMENT  5
    COPYFROM 1
    OUTBOX  
    COPYFROM 2
    SUB      0
    JUMPN    g
    COPYFROM 0
    OUTBOX  
    COPYFROM 2
    OUTBOX  
    JUMP     a
g:
    COPYFROM 2
    OUTBOX  
    COPYFROM 0
    OUTBOX  
    JUMP     b
h:
    COMMENT  0
    COPYFROM 1
    SUB      0
    JUMPN    k
    COMMENT  3
    COPYFROM 0
    SUB      2
    JUMPN    i
    COPYFROM 2
    OUTBOX  
    COPYFROM 0
    OUTBOX  
    JUMP     j
i:
    COPYFROM 0
    OUTBOX  
    COPYFROM 2
    OUTBOX  
j:
    COPYFROM 1
    OUTBOX  
    JUMP     d
k:
    COMMENT  2
    COPYFROM 2
    OUTBOX  
    COPYFROM 1
    OUTBOX  
    COPYFROM 0
    OUTBOX  
    JUMP     e


DEFINE COMMENT 0
eJzTZ2BgUDV29/Qw/+uW6/jXTd/VJ9DIuz7LyHtSl6EH27T3rmUzOSxCF5x34Z4X4Ba64JP3gkVhQQsW
VYRFrQBqZZiffMc3PsUn0CmTLZynhjtep9Yggbf+VSpvfVSmd/XlGq7KGy0vSu70PCv0mcCUVTgRpKd8
4iaXiMm9zrtnbnL5M/uvW+3c7T775vsEyi8IiKydezRl9gyR/Nkz7Cpk525qll+g3p+waM/khUuezVm4
pHphw+Kji2tmRa2onGK6nGEUjIJRQDEAACiRUNA;

DEFINE COMMENT 1
eJyzYmBg4HORsBBwl7AQ9DpnujPis9nuaDvLObE/7GTjJ3nLxj8MjYkLiLQIN0i4GmCQcNn3aEpY0JLs
qkjLgjmxHVV34/+2/kswXS4bL7Jud3T8hh2hVuuvBkStmOR9dPE659AF75y45wGtYDhTk+N1rn67z8e2
gMhp/Qdids98lXp/QUvR/QWfS+fMdm64NX1S147JTH0mPWUzJ3eGLhDqiFpR2Pp+zfpGkXUg/Rwb7/hq
bHL3PLllk4vPzk0uevuUPAoP+wROOvIwdNPRqqRNR1cWFx7OaHy/704P93a2aS83sU2bflZ7+s1LgTN2
XTkwm2EUjIJRgBUAAJ4Bbdk;

DEFINE COMMENT 2
eJzzZWBgkJSeHd2otTtksV5AZKqRaUaq0eWaxXqFE3fJLlh0Q+LVEgvJ+pWS0qdWV8udWp1qdG5zl826
XUBtDN8Cj6bsCLUs+BneUiQb31I0N6Gj6l/Cpuba+MKJNrHc8yQjl66SjIzfsCP08u5i382HQHpYCz6X
Hit4n7u8aEn2itIl2a/KW4pWVSRXviqf1JVZxtSXXuwzoaMkcEZn+YJFqyrqV3ZXnVrNU9OykadGclt3
1Y89XhUZB1JyPY4rZ3scB5mXsyuu0H//umr+A39b1+8vnMi3N3SB7m7T5Vpb36/p3yey7sPBlo1GR1o2
Ch/7sgWkXu52fdadGyuLKy9lNEpemtQ167L2dKmrs2fduXFg9ssPz+ZwfQpdAFL35ptpRu6PqMz833GF
+n/sKvT/FE7s//NwiuH/Z3MYRsEoGEYAAH8RlOg;

DEFINE COMMENT 3
eJwLZGBgmMB13fUDV4bTRR4nxxIhWYfvYk6O28U3uVhI/nWLkLrjO0vmVeosmVM5PyRl68tEcztDBJn6
BHl8JlRKF06Ukps2abZ84AygMQz71ZQ8DmoqebgYMvp7mDP6e9v6BPbYPww9Y3cgpssmNHGl1ZLsDIu4
wicGl2tA6qf4/bDbGeHk+Ctqk4tN7B3fP7Fs4X9iZ0dXxxgk7Iw4mmIV1VFVFencUBac2ykakNsJ0rO5
yydQpPuO79eeHK+ZU909Z8/Y7nNnlkHCnVmfS2fPUGq/PvHAbJOeBYtE+0IXWE41mG8949mc+wsWLGpa
dnRx+/qlq0BmrNrmE3h6O1t4/74DMdfOhCbOuMCfHnFRJL/8/Mribac3NX868nDKpyOBMy4enj0LpF71
1YEYtjdRmcffrCw+/ka2/tmraZPaXnHPO/6mfqX6W6v1DKNgFAxhAABuCI/q;

DEFINE COMMENT 4
eJyLZGBg2CK4O+SaaGHQTqnCoJvSu0NiFCwL9ihIlu9RkK3/Lb+p+ZfM31ZLmUlds2TU+6vltKfPUxVY
9l/VbrucyuXd10Qv7xbm79wJNIaBWb8wqMtmXTWv449aXaeMxrOO0yZl2wXOaDczmN9mvHITq9GXLSB1
hh5s4aIBs6O/BXLH7wg1zagIaymSCDsw+3qw6fIvfi0bN/t82WLk/WXLZp/kHTfCknfsjv6xZ3+K3D6Q
3ik9p3Km9PCnT+sPTTSfxB1/c4pBgvUM/vTfM07l/Jl9rqR27t/WvXMeTrkzK3TB7BlRKyqnvF9j0hO/
YcYkq/Wxc+I3zF9ot71lpeQ2kFnr9rzPNTi4rvrTkYzGkpN/W2dc+Nt6+2pu5+9rd3qkrk6bFH6Oe961
M0cXm56qXzn5eP3Ky8daNgYd/bLl4mG77RsPQfzy/O373ONvJMvbXv2oVX3V26T6Sr3/2Su2aW6vBZa5
vZbb1/Zq8yGGUTAKBjEAAAWPrq8;

DEFINE COMMENT 5
eJwLZGBgKOY/V/JVWCS/TFQk/4ZEXKGUXFzhX6XPpfNUMxrj1aZNqlN5NidcnHveVpHQBWWiAssqpeM3
zJK5vHuWzOZDldIex8slJp28KjTp5CRepWP+HD/2AI1kcNQ+lZOk01LErL+yWMXgc2m72aSuExZMfZ5W
D6f4OBxdvNZh6aq1DiLreuxXbnIzubxbxaD3oLPe9lOLtJnOgvTfipStr43/USuXtL27LmnlJtsE5/3V
MUrHQHJWUbknpGP+HomJ+3tkf8rd040ZTGdfld89DZJzWv631Wn5tEnKK0XWKa903t+65txmkHjgodzO
qycfTtl1JXSB1NWji2ddjlpheurLlsnHf+xZv//vEZCa1597m7i/9jad+Zrbef737Fnv/4QueP9HZJ3+
H7vtvD8yDmS87z347NXfI54ft5/y/sJ2Vedb4PX//2tuMIyCUTCEAQDmoZxZ;

DEFINE LABEL 0
eJwTYmBgWKAREKmkOy04WX+7j4qBu6eKgZNjsn6vc7I+o7+zXkAks75lwRH9z6UqBtzzgMoZ5FS4591T
CV3goFG9MFm/euHtmAOzGUbBKBgFQxIAAOsbFkM;

DEFINE LABEL 1
eJwTZmBgOKjZUXVQ833uIm3+9GfGr1Kfm/Gnn7Coz/K2de/gtiubudr21ZKVVvEbjhqt23VQU27fTWm5
fX+VLu9O0PyxR0nXeX+yvtKxDW65JxhGwSgYBUMOAACfYiJZ;

DEFINE LABEL 2
eJwTZGBgYDVycjxq9MNOy+aH3Rt7WQc/5+uuBe5s4RM9qpImesQVbnCzqzhumlyZbefc0O/KPe+9a9SK
d07v17yxF1l3RD9+A8MoGAWjYMgCAL4ZG5g;


```