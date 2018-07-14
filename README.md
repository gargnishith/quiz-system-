# quiz-system-
basic structure of a quiz system : build in c language .

In this project we will develop a module where the user will appear in a test where 10 questions  , one at a time.
These questions will picked up from a file containing 30 questions. Each question will have 4 answers.
User has to choose the correct one.  When he submits his answer, the program will evaluate it against stored answer for the specific questions.
All the 10 questions will be evaluated in the similar manner and marks will be assigned to the correctly chosen answers. 
At the end it will display the marks that the user has secured.


quiz rules 
1. no question to be repeated in a session .
2.every time question sequence is different.

starts : opening screen :user enters the number of questions : display of questions :get the answers :and finally display results .

Main function calls menu controller 
displays opening screen 
and start the quiz .

at this stage the questionbank file is read and questions selected and stored in a array structure .

function : run quiz called , every time a user answers , his answer be evaluated and marks alloted .
result displayed .

