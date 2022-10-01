![Image](1.png)
Install Visual Studio Code: We need to go to the official website of Visual Studio Code https://code.visualstudio.com/ to download the app. There are 3 options for different operating systems, select one that fits your laptop.
![Image](2.png)
Remotely Connecting: We need to type $ssh cs15lfa22jj@ieng6.ucsd.edu to connect the remote server. If you are first time connecting to the server, there might be soe messages.
Just say yes to these messages and give your password to connect the server.
[Image](new%203.png)
Trying Some Commands: Try running different commands both on your computer and on the remote sever. For example: ls, pwd, and cat. For example, I  printed out the working directory by typing “pwd”.

![Image](4.png)
Moving Files with scp:  In order to move files from local computer and remote server, we can use command scp transfer files back and forth. As you can see, I created a file called WhereAmI.java on my laptop, then I copy and paste it with the command “scp ”in the remote server and ran the file. If you move the file successfully, you will get different information about the name of operating system, user, and directory.

![Image](5.png)
Setting an SSH Key: The reason we set an SSH Key is every time we log in and run scp, we have to type password. By setting an SSH key, we will save a lot of time. Type $ ssh-keygen to generate public/rsa key pair. After that, you don’t need to password to login remote server.

![Image](6.png)
Optimizing Remote Running: Type ssh cs15lfa22@ieng6.ucsd.edu "ls",then type 
cp WhereAmI.java OtherMain.java; javac OtherMain.java; java WhereAmI. Press enter key to complete.

