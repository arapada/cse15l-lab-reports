# Lab Report 1
## How to Login to Course-Specific Account
Click on this link to access your [course-specific account](https://sdacs.ucsd.edu/~icc/index.php).
You should be directed to this page.

![Image](course-specific-account.png)

Input your student username that is from your UCSD email, for example, *arapada* is the username from *arapada*@ucsd.edu.
Along with your student ID.

After that, you should be directed to this page below

![Image](course-specific-account2.png)

Under **Addtional Accounts**, there should be a course-specific account that has the course name, number and term. For example, *cs15lsp23*.
You should be able to reset your password for that account teehee. **DON'T RESET YOUR ACTIVE DIRECTORY PASSWORD unless you actually forgot!!!**

## Installing VSCode
Click on this link to download [VSCode](https://code.visualstudio.com/). Make sure to download for Mac or Windows depending on OS. 

![Image](vscode1.png)

Then, click on the zip file in order to access the application. You should be able to double-click on the application to open it.

![Image](vscode2.png)

You should have the application open and look something like this. VSCode doesn't have to look exactly like this but something similar as seen below.

![Image](vscode3.png)

## Remotely Connecting
Connecting remotely to your course-specific account requires your terminal. You can access your terminal through VSCode or your built-in terminal on your device. 

To access your Terminal on VSCode, make sure to be on a new file (it can be any type of file) then click on Terminal -> New Terminal. This will pop out a new terminal that is shown to be connected to your User device.

![Image](remotely-connecting1.png)

After that, use the command `$ ssh cs15lsp23ir@ieng6.ucsd.edu` that should prompt you into entering your password. If the terminal asks for you to enter your password again, that means you didn't input the right password that you have reseted when accessing your course-specifc account. *Refer to How to Login to Course-Specific Account IF you need to reset your password again.*

![Image](remotely-connecting2.png)

Then, your terminal should be seen like this from the image below. This means you have successfully connected to the server **if that wasn't your first time**. If you prompted to show your fingerprint or a yes or no question, type in `yes`.

![Image](remotely-connecting3.png)

## Trying Some Commands
Lets try out some commands from your course-specific account! Try typing '$ ls`

![Image](some-cmds1.pmg)

This will give you a list of files and folders. Since the account is pretty new, you only see one file called `perl5` which I don't know what that means.
