# Lab Report 3 by Shresth Hooda

## Streamlining SSH Configuration
---


<img src="https://github.com/Shresthhooda/cse15l-lab-reports/blob/main/LabReport3Images/1.1.PNG?raw=true" alt="Image" />

> Showing `.ssh/config` file edited in VS Code.

<img src="https://github.com/Shresthhooda/cse15l-lab-reports/blob/main/LabReport3Images/1.2.PNG?raw=true" alt="Image" />

>Showing ssh command with alias hooda

<img src="https://github.com/Shresthhooda/cse15l-lab-reports/blob/main/LabReport3Images/1.3.PNG?raw=true" alt="Image" />

> showing scp command moving hello.txt.

> I created the shortcut for logging into the remote machine by changing the code in .ssh/config to recognize the username "hooda" when logging in. I then made a file hello.txt and moved into my virtual machine using scp.

---
## Copy whole directories with scp
--

<img src="https://github.com/Shresthhooda/cse15l-lab-reports/blob/main/LabReport3Images/3.1.PNG?raw=true" alt="Image" />

> Copying markdown parse directory to remote computer

<img src="https://github.com/Shresthhooda/cse15l-lab-reports/blob/main/LabReport3Images/3.2.PNG?raw=true" alt="Image" />

> Running succesful tests on remote computer

> I was able to copy multiple files with scp by using scp along with the dot which copied the whole directory. I then chose my target destination on the remote computer. Finally I ran my tests an they succeeded on the remote computer.
