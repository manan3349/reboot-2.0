# Problem 5
## Play with files and directories
### Question
- create  3 files named   abc.txt  ok  fine  g.txt  /tmp directory 
- create  4  directories   aa aaa aaaa  under  /tmp directory 
- give ls command to  list the content of  /tmp directory 
-  make sure it will only list the content (file|directory)  having 2 char in their name.
  
 ### Solution
- Open Terminal and type following commands:
-   `cd /tmp`
-   `ls`
-   `touch abc.txt "ok fine" g.txt`
-   `ls`
  
      ![ok](https://user-images.githubusercontent.com/63852645/86514359-8443d600-be2f-11ea-98f9-222896e71594.PNG)
 
-   `mkdir aa aaa aaaa`
-   `ls`

      ![a](https://user-images.githubusercontent.com/63852645/86514463-f87e7980-be2f-11ea-8889-abf1f58878f3.PNG)
      
 -   `ls -d ??`
 - Here `ls` will list all files and  `-d` flag will prevent `ls` to display the content of file.
  - `??` will list only the (directories|file) having 2 char.
 
 
      ![5(3)](https://user-images.githubusercontent.com/63852645/86514466-03390e80-be30-11ea-81f2-4c0019d7915c.PNG)


 -> Source: https://unix.stackexchange.com/questions/207504/find-files-whose-name-is-4-characters-long/207507
