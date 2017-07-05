# NumberToWordConversion_MVCWCFProblem overview: 
Develop a web application that performs the following functions:
 
•	Capture a person’s name and a number
•	Convert this number into words
•	Render this name and number (as words) as a web page.
 
This is similar in functionality to that of a cheque writing program, for example:
Input: John Smith
“123.45”
Output: John Smith
“ONE HUNDRED AND TWENTY-THREE DOLLARS AND FORTY-FIVE CENTS”


Solution:
Tech Stack:
1.	Visual studio 2015
2.	MVC- 5.2.3
3.	WCF [windows communication foundation]
4.	Dependency Injection- Unity container 
5.	JQuery 1.10.2 and for validation 1.16.0
6.	Rhino. Mock and NUnit for testing.

To address this requirement I have created MVC application to handle the user request and give back the required result. 
Created one WCF service which has the actual conversion logic and consumed by MVC application.


High Level solution design.

	

How to execute:
To execute this application just open the solution and click Debug - Start Debugging (or F5) from Visual Studio.

Note: To execute the test you need NUnit extension in visual studio.


