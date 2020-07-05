# Problem 6
##  Run command without any output 
### Question
- open terminal and type any command.
- once you press enter your output of given command must not  print.
- you are not allowed to redirect output anywhere .
### Solution
- As we are not allowed to redirect, but we can redirect the output by `exec > /dev/null` .
- this command will redirect your output to `/dev/null` .

![6(1)](https://user-images.githubusercontent.com/63852645/86542588-7035cc80-bf34-11ea-838d-88e071c4e096.PNG)

- So, we can use some cool bash commands to prevent output. 
- `bash -n` will check for the command but doesn't gives you output back.
- `-n` means non exectution.

![6(2)](https://user-images.githubusercontent.com/63852645/86542590-72982680-bf34-11ea-98d4-3181f7f055a7.PNG)

-  We can also use `bash -D` , as this command will also prevent the output.
- But when we use double-quoted strings prefixed by $ then it will shows the message.

![6(3)](https://user-images.githubusercontent.com/63852645/86542592-74fa8080-bf34-11ea-965f-395f57adca49.PNG)
