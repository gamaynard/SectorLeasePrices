# Creating a new connection to an AWS server

This process may seem a little intimidating, but you only need to do it once to set up a connection between a windows machine and the server. 

1. Download the PuTTY terminal emulator program [here](https://the.earth.li/~sgtatham/putty/latest/w64/putty-64bit-0.74-installer.msi) and install it on your Windows machine. *NOTE: If the linked installer for Windows 10 64-bit systems doesn't work on your PC, you can select the appropriate installer from the list [here](https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html)*
2. Log in to the AWS Management Console with the CCCFA credentials and select the EC2 option.
![aws_homescreen.PNG](/SupportingFiles/aws1.PNG)
3. On the left-hand side of the EC2 screen, under **NETWORK & SECURITY** select the **Key Pairs** option.
![aws_EC2screen.PNG](/SupportingFiles/aws2.PNG)
4. Click on the orange **CREATE KEY PAIR** button in the top right corner of the screen and you should see the options below. Enter a name that describes the computer being used. For example, you could use the computer's name on the CCCFA network (`"HOOK-##"`) or something along those lines. Be sure that you've selected the correct key type for use with PuTTY (.ppk) and press the orange **CREATE KEY PAIR** button to create the keys. You will be prompted to save the private key in a safe place. 
```diff
- WARNING: THIS IS YOUR ONLY CHANCE TO DOWNLOAD AND SAVE THE PRIVATE KEY SO DO NOT IGNORE IT OR LOSE THE FILE
```
![aws_createKeyPair.PNG](/SupportingFiles/aws3.PNG)
5. Launch the puttygen.exe program from your start menu. The easiest way to do this is just to type `puttygen.exe` into the Windows start menu search. You should see a screen that looks like this. 
![puttygen1.PNG](/SupportingFiles/puttygen1.PNG)