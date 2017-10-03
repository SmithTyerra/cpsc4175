# Assignment 6  
## October 2, 2017  

1.  **Two problem domains that I would use for Python are elevator control and online banking.** 
**Two problem domains that I would use for Swift are Minesweeper and Connect 4.** 
_Python would not be a great language choice to implement a MineSweeper game or a Connect 4 game_ 
_because Python is not fully obeject-oriented in that it does not support strong encapsulation._ 
_Swift is a more higher-level language than Python and would be overaccomadating to implement_ 
_elavator control or online banking and is therefore not a great language choice for these problem_ 
_domains._  

2. **Bad programming practices include:**  
	a) _Using vague, non-meaningful variable names._  
	b) _Showing inconsistencies in variable naming._  
	c) _Writing code that contain no comments._  
	d) _Testing all parts of the code at once._  
	
3. **Two versions of coding standards for sub procedures:**  
	a) _Subprocedures can define their own local variables and files and may be called recursively._  
	b) _Subprocedures can access files and variables found in the gloabal variables section may or may not return a value._ 

4.  **An example of the DRY principle:**  
_When I decided to implement an online shopping system, I found that after calling the addToCart method,_ 
_I would repeat a line of code that would add the price of the newly added item to the cart's total price._ 
_To apply the DRY principle, I created an updateCart method that updated the cart's total price instead._  

5. A **stub** is _an empty artifact and it should return the values corresponding to preplanned test cases._ A **driver** is _a code artifact that calls it one or more times,_
 _if possible checking the values returned by the artifact under test. I have used a driver and a stub in my previous programming experience. An example is..._ 

6. **Two strengths of top-down integration** are that _it supports fault isolation and ensures that logic artifacts are implemented ans integrated before operational artifacts._ 
**A weakness of top-down integration** is that _potentially reusable code artifacts may not be adequately tested._  

7. **Two strengths of bottom-up integration** are that _operational artifacts are throroughly tested and testing is done using defensively programmed artifacts or drivers which ensures fault isolation_. 
**A weakness of bottom up integration** is that _major design faults are detected late in the implementation workflow._  

8. **A DSL might promote sandwich integration because** _just as DSL acts as a  'glue' between higher level and lower level languages, it can be used to merge the result of the top-down integration and the bottom-up_ 
_integration that results in sandwich integration. The DSL will perform top-down intgration on logic artifacts and bottom-up integration on operational artifacts._

9. **The difference  in testing carried out by the implementation group and the testing carried out by the SQA group is that** _an SQA group thouroughly tests and analyzes the code with the greater good in mind while_ 
_the implementation group only analyzes and tests the code on a works or doesn't works basis. The SQA has more to lose if the integration tests are improperly performed and because of this they tend to pay more attention to detail._  

10. _After reading Dijkstra's letter, I began to analyze how I have completed previous programming assignments and compared them to Dijkstra's take on the process. During analyzation, I realized that I am inclined to agree with Dijkstra_ 
_on a few things. I think that I mostly agree with his gesture that even though the process of creating a product is the most important part of the product, once the product is created and functioning as it should the process of getting_ 
_there is pretty much forgotten. I have found this to be true because sadly after I have gotten a program to do what I want/need it to do, how I acheived the success is no longer important to me. I have started to try and leave this mindset_ 
_behind because in my future field of work, I will need to be able to expllain to  others how I achieved the finished product._ 