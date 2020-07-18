# TASK 4
## Play with Scripts.
### Question.
- Write a Script and run it.
- If it successfully works,convert that shell script into binary code.
- then put the binary file under /usr/bin/
### Solution.
- For converting into binary, we need to install required packages for SHC compiler.
- `sudo yum install glibc-devel` - for fedora based os.
- Now, Download and install SHC
- `cd /usr/src`
- `wget http://www.datsi.fi.upm.es/~frosal/sources/shc-3.8.9.tgz`
- `sudo tar xzf shc-3.8.9.tgz`
- Now compile the SHC source code on your system and install it using following command.
- `cd shc-3.8.9`
- `make install`
- Now Create a Shell script
- `vim script.sh`

![1](https://user-images.githubusercontent.com/63852645/87862129-64053280-c96a-11ea-87bb-84dda516ed22.PNG)

- Now lets Create Binary of the script.
- `shc -f script.sh`
- The above command will create two files in current directory. One will be script.sh.x.c which is in C language format of your script. Second one will be script.sh.x which will be in binary format.
- If you do  `cat script.sh.x`, it will be in binary format.

![2](https://user-images.githubusercontent.com/63852645/87862130-65cef600-c96a-11ea-9e15-c38bc3ae7646.PNG)

- Now move that binary format file under /usr/bin.
- `mv script.sh.x /usr/bin/script`
- Give permissions to the file. `chmod +x /usr/bin/script`
- Now if you type command `script`, it will run as the same.
