**SENG 438 - Software Testing, Reliability, and Quality**

**Lab. Report #3 – Code Coverage, Adequacy Criteria and Test Case Correlation**

| Group \#: 29      |     |
| -------------- | --- |
| Student Names: |     |
| Evan                |   
| Abdullah            |   
| Jack                |   
| Max                 |  

(Note that some labs require individual reports while others require one report
for each group. Please see each lab document for details.)

# 1 Introduction
In this assignment we will be demonstrating our skills with code coverage white box testing, now that we have access to 
the code inside we can now develop CFG diagrams and actually calculate what the coverage metrics are on our code pertaining to c-use and p-use and do calculations on how many of these we hit. We can also use code coverage tools to test other coverage metrics such as branch, statement, and condition coverage. 

# 2 Manual data-flow coverage calculations for X and Y methods
Please see attached pictures and pdf of our calculations for both the calculateColumnTotal method and getLowerBounds method

# 3 A detailed description of the testing strategy for the new unit test
Because we found all of our tests to have 100% coverage for statement, branch and condition coverage we did not develop any additional test cases as there is no way we could find to improve on our current testing strategy without adding tests that did the exact same thing as we already had done.

# 4 A high level description of five selected test cases you have designed using coverage information, and how they have increased code coverage

Because all of our metrics were 100% there was no way to increase the coverage of our code here is a layour of five of our tests that were conducted for the calculateColumnnotal method

testInvalidColumn this tested the ability for the system to give an error when trying to access a column that was larger than the possible columns

testInvalidParameter this was to test if the code would reach an invalidParameter exception when given a null data set

testNegativeColumn this was a test to see if the code would reach an error given a column that was smaller than the available columns

testIncorrectValue this was a test to see if the system would correctly evaluate a data object with null values as it should output a 0 as said

testShouldWork this was a test to run through all of the code without errors this runs through almost all of the method and hits most of the coverage 

# 5 A detailed report of the coverage achieved of each class and method (a screen shot from the code cover results in green and red color would suffice)

DataUtilities class hit 100% on statement, branch and condition coverage and all methods that were tested

calculateColumnTotal 100% on statement, branch and condition coverage

calculateRowTotal 100% on statement, branch and condition coverage

getCumulative percentage 100% on statement, branch and condition coverage

createNumberArray2D 100% on statement, branch and condition coverage

createNumberArray 100% on statement, branch and condition coverage

Range class hit 100% on statement, branch and condition coverage and all methods that were tested

getLowerBound 100% on statement, branch and condition coverage

getUpperBound 100% on statement, branch and condition coverage

toString 100% on statement, branch and condition coverage

getLength 100% on statement, branch and condition coverage 

getCentralValue 100% on statement, branch and condition coverage

# 6 Pros and Cons of coverage tools used and Metrics you report

The pros of coverage tools is they are a good way to get an initial look at some of the metrics of unit testing code and they provide great insight into the branch, statement, condition and many other coverage metrics

The cons of using coverage tools is that some do not know the difference between unused lines of code and used lines of code and they take into account infeasable and unreachable lines of code so manual calculations are needed to actually define whether you are hitting 100% coverage

# 7 A comparison on the advantages and disadvantages of requirements-based test generation and coverage-based test generation.

The advantages to requirements based testing or black box testing is that you get an initial look at whether the code is running properly based on the documentation of methods developed but the disadvantage is that you don't actually know what is going on inside of the code and whether you are actually testing the full functionality of the code, obviously this isn't always a disadvantage as in our case we had built code in our black box testing that once we moved to coverage testing we found 100% coverage

The advantages to coverage based testing is that you get a look at what is actually going on in the inside of the code and you are able to  adesign CFG's and DFG's to actually tell whether you are testing all of the code that has been made, the disadvantages to this method is that it can take alot of effort to make DFG's and CFG's to make sure that your coverage tools are providing accurate information

# 8 A discussion on how the team work/effort was divided and managed

After we had figured out together that we had hit 100% coverage on all of the metrics that we needed to test for we decided to move right on to manual calculations to make sure that the results of our code coverage tool was correct and we split into two teams to accomplish this, team 1 Jack and Max worked on the manual coverage results for the getLowerBounds method and team 2 Evan and Abdullah worked on the manual coverage results for the calculateColumnTotal method we then agreed to meet at a later time to look over and compare each others work and finish the lab report

# 9 Any difficulties encountered, challenges overcome, and lessons learned from performing the lab

We encountered the difficulty of hitting 100% coverage and not knowing what tests to develop from here to increase our results from 100%, we decided that a professional programmer would not develop any additional tedious tests that would not increase coverage but we did not know if this was the right solution to our problem

# 10 Comments/feedback on the lab itself

Amazing lab, we learned alot about different code coverage tools that can help speed up the process of doing coverage based testing and we got to put our skills of manual testing to practice as we had learned from class
