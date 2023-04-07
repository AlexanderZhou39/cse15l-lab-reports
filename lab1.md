# Lab Report 1 (4/6/23)

## Summary
Following are the steps to setup and login to your cse15L user via ssh on the remote server.  <br><br>

### 1. Installing VSCode
Go to [https://code.visualstudio.com/](https://code.visualstudio.com/) and install VSCode for your OS. I've already installed it previously, but you should see something like this once opened:
![Image](assets/lab1/vscode.png)
<br><br>
### 2. Find your account username
First you want to find the username for your cse15L account so you can reset its password. Go to [https://sdacs.ucsd.edu/~icc/index.php](https://sdacs.ucsd.edu/~icc/index.php) and enter in your UCSD credentials. 
![Image](assets/lab1/search_acc.png)
<br><br>
### 3. Select the CSE15L account
Under "Additional Accounts," click the one that starts with the class code and follow the instructions to reset the account's password.
![Image](assets/lab1/reset_pass.png)
<br><br>
### 4. SSH using the account
After the account's password has been successfully reset (it may take up to 30 minutes), you can now attempt to login to it on the remote server via ssh. First open a new terminal session (in vscode: `terminal` -> `new terminal`), then enter in
```bash
ssh <username>@ieng6.ucsd.edu
```
Where `<username>` refers to your account's username. 
<br><br>
### 5. Enter in your password
It'll prompt you to enter in your account's password. 
![Image](assets/lab1/shell.png)
<br><br>
### 6. Login
If the login succeeded, then you should see something like this:
![Image](assets/lab1/server.png)
<br><br>
### 7. Try different commands
You can now try different commands to explore the directory structure and other things. 
![Image](assets/lab1/commands.png)