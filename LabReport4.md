# Lab Report 4 by Shresth Hooda

## Links
---


> Our markdown-parser [link](https://github.com/Shresthhooda/markdown-parser) embedded

>There markdown-parser [link](https://github.com/alixintong/markdown-parser) embedded

## Expected Output
---
>The expected output for snippet 1 is all of the url's will be produced except for url.com.

>The expected output for snippet 2 is a.com should be produced twice and then example.com once.

>The expected output for snippet 3 is the twitter link should work and the schedule link should also work. The link to the ucsd site should also work.
## Our implementation
---
>My code for running the tests

<img src="https://github.com/Shresthhooda/cse15l-lab-reports/blob/main/LabReport4Images/myimplementationtests.PNG?raw=true" alt="Image" />

>My output from running the tests

<img src="https://github.com/Shresthhooda/cse15l-lab-reports/blob/main/LabReport4Images/myimplementationfailures.PNG?raw=true" alt="Image" />

> None of these tests passed.


## Other group's implementation
---
>Their code for running the tests

<img src="https://github.com/Shresthhooda/cse15l-lab-reports/blob/main/LabReport4Images/theirimplementationtests.PNG?raw=true" alt="Image" />

>Their output from running the tests

<img src="https://github.com/Shresthhooda/cse15l-lab-reports/blob/main/LabReport4Images/theirimplementationfailuresOne.PNG?raw=true" alt="Image" />

<img src="https://github.com/Shresthhooda/cse15l-lab-reports/blob/main/LabReport4Images/theirimplementationfailuresTwo.PNG?raw=true" alt="Image" />

>None of these tests passed

## Code Changes
---
**Snippet 1**
>The error resulted from our code not checking if the first and second bracket are present to determine if the link should be included. Our code included the link because of the inline back tick but it shouldn't have done that. We need to implement a small change that will check for the first and second bracket being present in our code.

**Snippet 2**
>Our code didn't register the url for "example.com" because there was an extra second bracket, which ruined its functionality. We need to implement a small change in our code that can ignore an extra bracket so that those url's will be included in our output.

**Snippet 3**
>Our code produced an error because of extra test at the end of the test file. We would be able to fix this issue by implementing something in our code to ignore any extra text after the last parenthesis. This can be done with a small change that will involve an if statement that checks for extra code at the end of the test file. 
