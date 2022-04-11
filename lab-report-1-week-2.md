# Remote Access

## Step 1: Installing VSCode
<img src="https://github.com/Shresthhooda/cse15l-lab-reports/blob/main/visual%20studio%20screenshot%201.PNG?raw=true" alt="Image" />



>The first step is to download visual studio from the visual studio code website and getting the right version for your computer. Then use the setup wizard to get it setup on your pc. Finally launch the application to the home screen.

## Step 2: Remotely Connecting
<img src="https://github.com/Shresthhooda/cse15l-lab-reports/blob/main/login%202.PNG?raw=true" alt="Image" />

>If you're on windows you should download open ssh and then open up a terminal. Type in the command ` $ ssh cs15lsp22zz@ieng6.ucsd.edu ` and replace the zz with the letters for your course specific account. If you get a "authenticity can't be established" prompt, type in yes then enter your password.

## Step 3: Trying Some Commands
<img src="https://github.com/Shresthhooda/cse15l-lab-reports/blob/main/command%20try%203.PNG?raw=true" alt="Image" />

>Once you are logged into the servers, you can run a number of commands. These commands do things like returning directories, files, and hidden files. If you try the command ` ls -lat `, it wil give you all of the files in the specific directory on the remote machine.

## Step 4: Moving Files with scp
<img src="https://github.com/Shresthhooda/cse15l-lab-reports/blob/main/scp%20ssh%204.PNG?raw=true" alt="Image" />

>Scp is a command that lets you copy files to a remote computer using the command ` scp "FileName" cs15lsp22zz@ieng6.ucsd.edu:~/ `. First create a java file and then type in this command with the file name and fill in your course specific letters. Then the file will be copied to the remote computer and you can see it by typing in the command ` ls `.

## Step 5: Setting an SSH Key
<img src="https://github.com/Shresthhooda/cse15l-lab-reports/blob/main/no%20password%205.PNG?raw=true" alt="Image" />

>To setup an ssh key you need to type in the command `$ ssh-keygen ` and then you need to type in the file path for the file where the key will be stored. Then enter a passphrase and then log back into the remote machine and type the command ` $ mkdir .ssh `. We then need to copy the public key to the ssh directory on the remote machine with the command 
` $ scp /Users/<user-name>/.ssh/id_rsa.pub cs15lsp22zz@ieng6.ucsd.edu:~/.ssh/authorized_keys ` and the ssh key should be setup.

