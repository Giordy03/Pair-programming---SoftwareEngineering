# User use a random xalculator 

## Group assigment 2: pair programming

### Overview 
Using the random calculator previously developed, generate 10 question and ask the user for an answer. After the user has inputted an answer for all of the proposed expressions (the user can select `ENTER` to pass an answer 
and going directly to the next question print out the time it took the user to answer to all the questions. Then display how many times the user replied correctly to the questions (out of ten), and display all the incorrect
guessed expression reporting only yhe correct answer. Finally ask the user if he want to stop the execution `2. exit` or continue with an other set of ten operation `1. proceed`. The program runs until the user input 
`2. exit`.
Error such us the user enter a not allowed string as answer, a not recognised command to continue/abort the execution are all handled in the file. In case of a divizion by zero, the programm will automatically end the 
execution of the programm with error code `'-1'`.

### Output example
```markdown
<STUDENT ID1, STUDENT ID2>
Number 1 question: 13 + 17 - 1 =
-->Your answer: 29
Thanks!

...

Number 10 question: 11 * 15 - 5
-->Your answer: 100
Thanks!
Total time: 15 seconds
Total number of correct answers: 9
The followings are the right answer to the expressiong you get wrong:
11 * 15 - 5 = 160

Do you want the next set of expression (`'1. proceed'`) or to ecit the program (`'2. exi'`)?
--> `exit` 
```



#### University Information 
- **University**: TongJi University, Shanghai
- **Course**: Software engineering
- **Department**: Department of computer science and technology
- **Semester/Year**: Spring semester 2023-2024
