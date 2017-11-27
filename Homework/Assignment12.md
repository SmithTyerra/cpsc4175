# Tyerra Smith  
## November 13, 2017  

1. Classes are blueprints of an object which includes variables and things that the 
objects will have (i.e. Class Student may have firstName, lastName, grade, GPA, etc.) 
while aspects are behaviors that are applicable multiple objects (i.e. monitoring/logging 
courses). If you used classes as in OOD, you would have to add a monitoring/logging method 
to each course but by using AOP you would make monitoring/logging an aspect and implement 
it at each pointcut or place in the code that aspect's code would run.  

2. It can be very inefficient to modify your code in the middle of a project. It is generally 
better to address issues and make changes as early on in the process as possible. With that being 
said, you will find it easier to change things in the analysis phase than in the design phase. When 
making changes in the analysis phase, the main concern is how you plan to solve a problem but when it 
comes to changing things in the design phase the concerns become how you approach the solution to the 
problem.  

3. The approach of the Universal Windows Platform is to target all APIs that are guaranteed to 
be present on the multiple devices that you plan to use the device on (desktop, mobile, etc.). 
That set of APIs is referred to as the Universal Device Family APIs. Additionally, device family 
specific APIs are also implemented. Altogether, these API's make up the Universal Windows Platform. 
You can target the universal set of APIs and still ue the additional set of APIs by adding a SDK 
reference. Once the reference has been added, you can use the API information class to so that the 
extension API is only called if the app is running on the devices that have it or you can target a 
specific device family and in this case you would not need an extension.  

4. The IDEs of today make building a project more achievable and simple because most of them are component 
based in that they have built-in functions that achieve functions that you will need. This prevents overthinking 
functions because they are already at your fingertips. This also prevents redundancy. It allows for more time to be 
spent on the more difficult parts of the project and less time on the error-detection of code since it is already given 
to you bug-free. A downfall is that when you program in a non component based language, you will have to learn to code 
the normally built -in functions from scratch.  

5. Infrastructure as a service (IaaS) is a form of cloud computing that provides virtualized computing 
resources via internet. Platform as a service (PaaS) is a cloud computing service in which a third-party 
provider delivers hardware and software tools to the users via internet. Software as a service (SaaS) is 
a software distribution model in which a third-party provider hosts applications and makes them available 
to customers via internet. Some of the similarities between the three are that all of them protect your 
API keys and are all forms of cloud computing.  

6.  

7. When building a project, I generally use input validation and sanitization. I use input validation to ensure that the 
user's input is legal and valid. I use input sanitization to detect common errors in the input and make the input valid and 
legal. For instance, if a user is supposed to input their name in a First Last format but they forget to capitalize the first 
letter of each, sanitization would detect the lower case letters at the first position and at the first position after the space 
and then change those to capital letters and resubmit it as input through which now the input validation test cases will be passed. 
Sanitization helps prevent having to retype the entire input if the error is as simple and common as a lowercase letter instead of an 
uppercase letter.  

8. 
