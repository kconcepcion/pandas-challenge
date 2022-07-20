pandas-challenge
module 4 challenge

#Description of repository
This repository has the file that breaks down school data information into readable data to allow its reader to draw conclusions. My written analysis and conclusions are in the following section and the description of each section of the code is under that.

##Written Analysis for Module 4 Challenge
There are a couple important things to do here after coming up with some charts.

One thing to note is that the five best performing schools were charter schools while the 5 lowest performing schools were district schools. There are a couple factors that can be attributed to these results. One factor might be that charter schools, in general, have less kids to worry about. Perhaps smaller classes can allow teachers to spend more one on one time with students compared to that of a bigger class.

Another thing I noticed is that more highschool kids appear to pass reading more than they do math. This is applicable to both charter and district schools. This might lead to the conclusion that more time needs to be spent in the math section to see a rise in the percentage of kids passing.

One last thing that might be important to note is when looking at the "Scores by School Spending" you can see that schools with a higher budget per each student perform worse overall in acedemics than schools wtih lower budgets. Maybe some of the money that the higher budget schools have can do towards higering more tutors/instructors.

##Instructions
Using Pandas and Jupyter Notebook, create a report that includes the following data. Your report must include a written description of at least two observable trends based on the data.

###District Summary
The goal is to create a high-level snapshot of the district's key metrics in a DataFrame, including the following: Total schools, Total students, Total budget, Average math score, Average reading score, % passing math (the percentage of students who passed math), % passing reading (the percentage of students who passed reading), % overall passing (the percentage of students who passed math AND reading)

###School Summary
Create a DataFrame that summarizes key metrics about each school, including the following: School name, School type, Total students, Total school budget, Per student budget, Average math score, Average reading score, % passing math (the percentage of students who passed math), % passing reading (the percentage of students who passed reading), % overall passing (the percentage of students who passed math AND reading)

###Highest-Performing Schools (by % Overall Passing)
Create a DataFrame that highlights the top-5 performing schools based on % Overall Passing. Include the following metrics: School name,School type, Total students, Total school budget, Per student budget, Average math score, Average reading score, % passing math (the percentage of students who passed math), % passing reading (the percentage of students who passed reading), % overall passing (the percentage of students who passed math AND reading)

###Lowest-Performing Schools (by % Overall Passing)
Create a DataFrame that highlights the bottom-5 performing schools based on % Overall Passing. Include the following metrics: School name, School type, Total students, Total school budget, Per student budget, Average math score, Average reading score, % passing math (the percentage of students who passed math), % passing reading (the percentage of students who passed reading), % overall passing (the percentage of students who passed math AND reading)

###Math Scores by Grade
Create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

###Reading Scores by Grade
Create a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

###Scores by School Spending
Create a table that breaks down school performance based on average spending ranges (per student). Use your judgment to create four bins with reasonable cutoff values to group school spending. Include the following metrics in the table: Average math score, Average reading score, % passing math (the percentage of students who passed math), % passing reading (the percentage of students who passed reading), % overall passing (the percentage of students who passed math AND reading)

###Scores by School Size
Create a table that breaks down school performance based on school size (small, medium, or large).

###Scores by School Type
Create a table that breaks down school performance based on school type (district or charter).



