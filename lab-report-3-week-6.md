# Lab Report 3
## Streamlining ssh Configuration
To streamline logging into the account, you have to first edit the config file in the .ssh folder to create an alias for the login, which is ieng6 in the following example.
<br>
![image](3-1-1.png)
<br>
From this point, the alias (ieng6) will be able to be used in place of the HostName, logging into the User specified in the config. <br> <br>
![image](3-1-2.png)
<br><br>
This process makes it easier to process code across the local and server computers, as can be seen in the following example, copying a file from the local computer to the server computer, using the alias instead of the full address.<br><br>
![image](3-1-3.png)
<br>
<br>

## Setup Github Access from ieng6
A set of keys can also be created on the server side computer to be able to push changes to Github. Below, the set of keys can be seen, on both github and the server computer.
<br> <br>
![image](3-2-1.png)
![image](3-2-2.png)
<br> <br>

## Copy whole directories with scp -r
Using the -r flag of the scp command, whole directories can be copied to a server, as seen below.
<br> <br>
![image](3-3-1.png)
<br> <br>
The following is the results of compiling and running the copied files.
![image](3-3-2.png)
Below is the single line command that can be used to copy a whole directory to the server, compile a file in the directory, and run the file.
![image](3-3-3.png)