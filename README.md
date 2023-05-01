---
Shell Scripting in Bash

Here is an example of printing numbers from 1 - 10 :
```
#!/bin/bash
x=1
while [ $x -le 10 ]
do
  echo "$x"
  x=$(( $x + 1 ))
done
```


TEST output :

![image](https://user-images.githubusercontent.com/124895858/220117042-3f8d678a-3a82-406d-85c0-2cf2ec374836.png)
