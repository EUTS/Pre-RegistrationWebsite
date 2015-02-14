Pre-RegistrationWebsite
=======================

Project under [Dr Wadee](https://github.com/wadeehalabi) 

This system has to do the following: 

1) Check the four year plan and the student transcript <br>
2) Recommend a schedule for the next semester <br>
3) Assume all the courses are available  <br>
4) Keep track of how many students are registered in each course <br>
5) Keep track of how many sections there are for each course <br>

First Task:

1) Download the four year plan 

2) Download your own transcript

3) Write down a set by step process to how YOU would create your proposed schedule for next semester using only the four year plan and your transcript. 

Ex. 

	 Compare each course in the four year plan with the courses in the transcript 
	 If they are equal, consider that course as "Completed"


Etc. 

Try to come up with the solution with as little steps as possible. 

4) Do this at a larger scale with maybe ten students (Dr Wadee will give out multiple transcripts for this)

5) Upload your solution onto this project and discuss each other's solutions 

Some things to consider: 

1) A lower limit for each section/course. Ex. 10 <br>
2) A higher limit for each section. Ex. 20 <br>
3) Maximum number of credits the student has to take <br>
4) Minimum number of credits the student has to take <br>
5) The previous courses the student has taken (from the transcript) <br>
6) The grade for each course on trasnscript

Some algorithms for the system:

1) If grade ==  fail
	remove the course from transcript (i.e consider it not taken)
2) Label each course High, Low, Middle priority based how many courses it is the pre-requisite for (ex. programming languages is a low priority because it isn't a pre-requisite for any course)
3)If a section in two different course has the same students registered, make sure the sections do not clash. 

Coding Stuff:

To work on this project, you need to know HTML, CSS, Javascript and PHP. To get started with learning these languages, check out the post on the EUTS website [Getting Started With PHP](http://euts.github.io/web/development/resources/2014/12/03/Getting-Started-With-PHP.html)
