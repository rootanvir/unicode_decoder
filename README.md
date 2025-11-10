```py
flags ="灩捯䍔䙻ㄶ形楴獟楮獴㌴摟潦弸弰摤捤㤷慽"
decode = ""
for flag in flags:
    decode += chr(ord(flag) >> 8)
    decode += chr(ord(flag) & 0xFF)
print(decode)
```
