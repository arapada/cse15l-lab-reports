# Lab Report 4
## Baseline
Step 4: Log into ieng6

![Image](step4.png)

On the terminal, I typed `ssh cs15lsp23ir@ieng6.ucsd.edu <enter>`. This allows me to access my account while also not having to input the password to save time.

***

Step 5: Clone your fork of the repository from your Github account

![Image](step5.png)

On the terminal, I typed `git clone https://github.com/arapada/lab7 <enter>`. WHich clones the repository under the account *arapada* .


***

Step 6: Run the tests, demonstrating that they fail

![Image](step6.png)

On the terminal, I typed `cd lab7` *that was the name of the directory from the repository that I have cloned from my github account.* ` <command> + <c>` to copy and paste the junit test command for java, which is `<ctrl> + <v> javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java <enter>`. `<command> + <c>` again to copy and paste the run command for java. `<ctrl> + <p>ava -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ...` but I messed up because i forgot to include the `j` in `java` so i tried again... `j <command> + <c>ava -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ...`. *Should demonstrate the tests failed.*

