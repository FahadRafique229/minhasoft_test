
Code Feedback:
1) In Booking repository Controller, Curl request is called directly within the function. It should be in a generic function with set of required parameters; 
	such as url and data etc. so that it can be used in other functions as well. 
2) Exceptional Handling missing: Always put code especially an API call within try catch block because it usually cause errors such as CORS which results in crashing the application.
3) A method's line of code should be atmost it covers the entire screen without scrolling. Splitting the code makes it more understandable and beautiful.
4) Removing unnecessary comments inside the script.
5) Booking Controller code is written as functions are more readable.









*****##########*************#############*********##########*********##########*************############*************#########***********
Choose ONE of the following tasks.
Please do not invest more than 1-2 hours on this.
Upload your results to a Github repo, for easier sharing and reviewing.

Thank you and good luck!



Code to refactor
=================
1) app/Http/Controllers/BookingController.php
2) app/Repository/BookingRepository.php

Code to write tests
=====================
3) App/Helpers/TeHelper.php method willExpireAt
4) App/Repository/UserRepository.php, method createOrUpdate


----------------------------

What I expect in your repo.

1, A readme with:   Your thoughts about the code. What makes it amazing code. Or what makes it ok code. Or what makes it terrible code. How would you have done it. Thoughts on formatting. Logic.. 

2.  Refactor it if you feel it needs refactoring. The more love you put into it. The easier for us to asses.  

Make two commits. First commit with original code. Second with your refactor so we can easily trace changes. 

NB: you do not need to set up the code on local and make the web app run. It will not run as its not a complete web app. This is purely to assess you thoughts about code, formatting, logic etc














