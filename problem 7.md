# Problem 7
## Create a shell script 
### Questions
- create a shell script named /root/delvex.sh 
- make sure it will run /bin/sh shell 
- a user will be running this script my using a command name opensource
- when a user  run like  "opensource  time" it must give current time only
- when it runs like "opensource user"  it will give list of interactive shell users only
- when run like "opensource 100"  it must print "Hello Delvex" 100 times in interval of 1 sec
- if runs like  "opensource windows"  then it must shutdown OS
- if run opensource command without any parameter  then it must show out --
-            i)   name of kernel 
-            ii)   version of kernel 
-            iii)  current date in the format of  /DD/MM/YY
-            iv)  name of OS 
-            v)   last reboot time 
 
-  Note:    each output for last option must be in a separate line.
### Solutions
- Open terminal and type following commands.
- `vim /root/delvex.sh`

![7(3)](https://user-images.githubusercontent.com/63852645/86645234-da657480-bffb-11ea-94d9-ec8d9169b05f.PNG)

- `chmod +x /root/delvex.sh`
- `vim /usr/bin/opensource`

![7(4)](https://user-images.githubusercontent.com/63852645/86646181-ab033780-bffc-11ea-871e-06288fb026fc.PNG)

- `chmod +x /usr/bin/opensource`
- Now run following commands:

![7(2)](https://user-images.githubusercontent.com/63852645/86644949-9a05f680-bffb-11ea-811c-94867d803ac0.PNG)
