# Lab Report 3 by Shresth Hooda

## Streamlining SSH Configuration
---


<img src="https://github.com/Shresthhooda/Lab_Report2/blob/main/DiffOne.PNG?raw=trueg" alt="Image" />

> Showing `.ssh/config` file edited in VS Code.

<img src="https://github.com/Shresthhooda/Lab_Report2/blob/main/Error%201%20Space.PNG?raw=true" alt="Image" />

>Showing ssh command with alias hooda

<img src="https://github.com/Shresthhooda/Lab_Report2/blob/main/Error%201%20Space.PNG?raw=true" alt="Image" />

> showing scp command moving hello.txt.

> I created the shortcut for logging into the remote machine by changing the code in .ssh/config to recognize the username "hooda" when logging in. I then made a file hello.txt and moved into my virtual machine using scp.

---
## Setup Github Access from ieng6.
--

<img src="https://github.com/Shresthhooda/Lab_Report2/blob/main/DiffTwo.PNG?raw=true" alt="Image" />

<img src="https://github.com/Shresthhooda/Lab_Report2/blob/main/Error%202%20Parenthesis.PNG?raw=true" alt="Image" />

> The link to the test file for the failure-inducing input is [here](https://github.com/Shresthhooda/markdown-parser/blob/main/test-file3.md?plain=1).

> The symptom in the second test case is that an extra parenthesis is included in the output of all of the links. The failure inducing output contains an extra open parenthesis in one of the links and the program is unable to ignore the extra parenthesis. The bug is that the program only checks for the first open parenthesis and doesn't check for more after that, which leads to the extra parenthesis being included in this symptom.

---
## Code Change 3
---
<img src="https://github.com/Shresthhooda/Lab_Report2/blob/main/DiffThree.PNG?raw=true" alt="Image" />

<img src="https://github.com/Shresthhooda/Lab_Report2/blob/main/Error%203%20bracket.PNG?raw=true" alt="Image" />

> The link to the test file for the failure-inducing input is [here](https://github.com/Shresthhooda/markdown-parser/blob/main/test-file4.md?plain=1).

> The symptom in the third test case is that there is an infinite loop because of the failure inducing input. The failure-inducing input includes an extra closed bracket, which makes the link lose functionality. The bug was that the extra bracket removed the link's functionality so we had to skip over it in our solution by writing an if statement that checked for the second bracket and skipped to the next link if it existed.





