# Assignment 5  
## Tyerra M. Smith  

1. The two basic ways of designing a product are _operation-oriented design and data-oriented design._ **Operation-oriented design** _places emphasis on the operations._ 
**Data-oriented design** _considers the data first._ **Data-oriented design and operation-oriented design are different because** _in data-oriented design, operations are of_ 
_secondary importance and in operation-oriented design, data are of secondary importance._  

2. The input to the design workflow is _the specification document and the output is the design document._  

3. **Variables for a student's graduation requirements-**   
_Input variables:_ studentFirstName: String, studentLastName: String, studentMI: String, studentIDNumber: String, studentMajor: String  
_Output variables:_ studentStanding: Integer, creditsLeftToGraduate: Float, coursesLeftToGraduate: [String], majorRequirementsFulfilled: Boolean, studentExpectedGraduationDate: Date  
_Processing variables:_ studentCompletedCourses: [String], studentCompletedCredits: Float, majorRequiredCourses: [String], majorRequiredCredits: Float, studentGPA: Float  
I would design the program so that the input variables are used to search a Student database in order to and retrieve the student's transcript. Once the transcript is loaded,
the completed courses and credits would be compared to the required courses and credits for the student's major. This comparison will be used to ouput whether or not the 
required courses and credits have been completed and if not, will output the courses and credits left until the student is eligible for graduation as well as the expected 
graduation date of the student and the student's standing.  

4. a) Input the  student's ID number, last name, first name, middle initial, and major.  
   b) Search the student database to access the student's transcript information.  
   c) Search the degree database to access the requirements for the student's major.  
   d) Copy the array of required courses into the array of courses left to graduate.
   e) Set the amount of credits left to graduate equal to the amount of required credits for the student's major.  
   f) Compare the student's completed courses to the required courses.  
   g) For each required course completed, delete that course from the array of courses left to graduate.  
   h) For each required course completed, subtract the number of credits that the course is worth from the credits left to graduate.  
   i) Return the array of courses left to graduate, the number of credits left to graduate, the student's current standing based on the number of credits completed, whether or 
   not the student has fulfilled the graduation requirements, and the student's expected graduation date.  
   
5. **Student Class-**  
	_Attributes-_ studentFirstName: String, studentLastName: String, studentMI: String, studentIDNumber: String, studentMajor: String, studentStanding: Integer, studentGPA : Float,
		studentCompletedCourses: [String], studentCompletedCredits: Float, studentExpectedGraduationDate: Date  
	_Methods-_ setFirstName, setMI, setLastName, setIDNumber, setMajor, addCourses, deleteCourse, addCredits, setStanding, calculateGPA, setExpectedGraduationDate  
	
6. In the case of our project, _I think that the best approach would be to for the design workflow to be an iterative, spiral process in itself. These seems to be best because_ 
_so far the design process has been the stage of the process that has changed the most for us. We began with the idea of an ATM machine but once we ran into a problem of how we_ 
_execute a particular part of the ATM machine, we decided that our design resembled online banking instead and so that is what we chose to execute for our project instead._ 
_I look at the design phase as the make or break of a product. If you can't design it, you can't implement it._ 

7. _To test a design you coompare the specification document with the code that you have to make sure that each of the requirements have been met. To test an implementation, you_ 
_test your code to ensure that the output is what you expected and that each of the classes interact as expected._  
**To test the design for the student's graduation requirements system ensure that:**  
	a) The student's transcript can be found by typing in the student's unique information.  
	b) The courses for the degree and the amount of credits required for the degree are able to be retrieved.  
	c) The student's GPA can be correctly calculated.  
	d) The expected graduation date can be calculated correctly.  
**Procedure for Transaction Analysis Design:**  
	a) Enter a student's unique identifying information.  
	b) Ensure that the correct student's transcript has been retrieved.  
	c) Ensure that the correct degree information for that student's degree has been retrieved.  
	d) Compare the completed criteria to the requirement criteria.  
	e) Ensure that the courses left to graduate reflects the required courses minus the completed courses.  
	f) Ensure that the credits left to graduate reflects required credits minus completed credits.  
	g) Ensure that the requirements fulfilled variable is false unless the courses left to graduate is empty and the credits left to graduate equals 0.  
	
8. _The cyclomatic complexity of a design is used to determine the complexity of a given flowchart. Cyclomatic complexity can be calculated using the equation E - N + 2P, where E_ 
_is the number of edges, N is the number of nodes, and P is the number of exit points. In Figure 1, E = 11, N = 10, and P = 1, therefore the cyclomatic complexity = 11 - 10 + 2(1)_ 
_= 3._  

9. _Previously, I have used LucidChart to create my diagrams. I find this program helpful because you can make almost any type of diagram needed, especially in software engineering._ 
_This program is easy to navigate and doesn't require much to use. I would recommend this program to anyone looking to make quality diagrams. You are able to position the objects_ 
_in the position of your choice unlike some other programs such as Dia._  

10. _This article was almost unbelievable. The programmers and software engineers that created and executed this product are awesome. I aspire to right code nearly as perfect_ 
_as the code produce for the shuttles. They almost had an error free product which is expected for a product in which an error in the product could be detrimental. This article_ 
_explains how the software is more important than the hardware in most cases because the software controls the hardware in most all cases._ 