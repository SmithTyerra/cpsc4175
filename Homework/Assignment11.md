# Tyerra Smith  
## November 8, 2017  

1. Stepwise refinement entails beginning with a general idea and breaking it down to a 
more specific and precise idea. It's like when you decide to buy a car. You generally 
decide the make first, then you work out the details to determine which model is the 
best fit for you.  

2. OOAD focuses on the smaller pieces of the project first (bottom-up) while stepwise 
refinement focuses on the project as a whole first (top-down). OOAD reduces the size of 
the program by encouraging careful design of data types and planning beforehand while 
stepwise refinement is kind of an 'as you go' type process.  

3. The article entitled _Program Development by Stepwise Refinement_ gave a great 
explanation of what stepwise refinement is. It described it a a series of steps wherein 
each step the grand problem at hand is broken down to form smaller subproblems that are 
more easily solved. The article also explained how 'practice makes perfect' in regards 
to programming and also how teachers/professors often give students the false perception 
that as long as they are able to learn and master programming languages, they will have 
no problems in the computer science field. The fact is that it is actually the applications 
of the techniques that are more valuable in the field.  

4. A non-technical example of the exercise of due diligence would be if Columbus State 
University decided to remove the parking decal fees. They would have to analyze the current 
cost with the parking decal and the cost if parking decal fees were removed. They would then 
have to weigh the benefits against the costs to make the appropriate decision.  

5. Since object A contains an invocation of a method in object B, anytime object A is 
used or reused, object B must/will be used or reused as well. This is a problem because 
object B is not needed everytime object A is needed. A solution to this problem is to either 
allow object A to inherit the methods of object B (if applicable) or to place the method into 
an interface that the objescts can implement. 

6. **INCOMPLETE**  

7. ```c  
# 
#target entry to build program executable from program and mylib 
#object files  
#
program: program.o mylib.o
gcc -o program program.o mylib.o
```
