# 35 - Duplicate Removal	

## Targets
Size: 17 / Speed: 167

## Size
```
-- HUMAN RESOURCE MACHINE PROGRAM --

    INBOX   
    COPYTO   [14]
    JUMP     b
a:
    COPYFROM [14]
b:
    OUTBOX  
    BUMPUP   14
c:
    COPYFROM 14
    COPYTO   12
    INBOX   
    COPYTO   [14]
d:
    BUMPDN   12
    JUMPN    a
    COPYFROM [12]
    SUB      [14]
    JUMPZ    c
    JUMP     d


DEFINE LABEL 12
eJxTY2BgWOVWF9rqYZTyxGPL5P1eB+cAhRimOk32/emzwlU76KRbasj3gNSQNfFsIYLJH/2XFIDkv0Y+
L2ILudfMFnKy+0gIb19jaMxM+7D5s3eHz59dGC053Se2cCJX3OuezLi9TReinxeFRB0tBOl7lGOUcjZj
Z0Zd0obKX8mXqppztEpl8kVr4/IYWl9l8vZNTguYUJf0YyrDKBgFo4AuAAD+6kC6;

DEFINE LABEL 14
eJzTZmBgqHCMCTFzmh821enH1GiHNUuAQgwzTKust5rds3tvweCg5qHoGBN+zw4kvjmqv2JaZG65fVh/
xcugqob1Aakdk/ytZ5wJ7FqsHDp9TUz4zrUb0kNWnc04tzQvY0WXTfKSApA+v5I18WtLEvImFCu2TSh+
v0yk6M96kLhMvmyOZcGtzO8FgsmXitxjCuolg443sUS1Ngsmz60SrbWrutfcUXay+3tBwAQGEkBXb0T9
opaD4QX188OIUa88odCHrX+L3/I+ySBS7BkFo2CoAwB/MlFO;


```

## Speed
```
-- HUMAN RESOURCE MACHINE PROGRAM --

    INBOX   
    COPYTO   [14]
    OUTBOX  
    BUMPUP   14
    JUMP     c
a:
    COPYFROM [14]
    OUTBOX  
    BUMPUP   14
b:
    COPYFROM 14
c:
    COPYTO   12
    BUMPDN   12
    INBOX   
    COPYTO   [14]
d:
    COPYFROM [12]
    SUB      [14]
    JUMPZ    b
    BUMPDN   12
    JUMPN    a
    JUMP     d


DEFINE LABEL 12
eJxTY2BgWOVWF9rqYZTyxGPL5P1eB+cAhRimOk32/emzwlU76KRbasj3gNSQNfFsIYLJH/2XFIDkv0Y+
L2ILudfMFnKy+0gIb19jaMxM+7D5s3eHz59dGC053Se2cCJX3OuezLi9TReinxeFRB0tBOl7lGOUcjZj
Z0Zd0obKX8mXqppztEpl8kVr4/IYWl9l8vZNTguYUJf0YyrDKBgFo4AuAAD+6kC6;

DEFINE LABEL 14
eJzTZmBgqHCMCTFzmh821enH1GiHNUuAQgwzTKust5rds3tvweCg5qHoGBN+zw4kvjmqv2JaZG65fVh/
xcugqob1Aakdk/ytZ5wJ7FqsHDp9TUz4zrUb0kNWnc04tzQvY0WXTfKSApA+v5I18WtLEvImFCu2TSh+
v0yk6M96kLhMvmyOZcGtzO8FgsmXitxjCuolg443sUS1Ngsmz60SrbWrutfcUXay+3tBwAQGEkBXb0T9
opaD4QX188OIUa88odCHrX+L3/I+ySBS7BkFo2CoAwB/MlFO;


```