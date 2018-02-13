## Rock, Paper, Scissors
A pretty self-explanatory Rock, Paper, Scissors game in `C`. The player plays a "Best of 5" series with the computer whose responses are (pseudo)randomly generated. I created this program as an assignment for the University of Pittsburgh's Introduction to System Software course (COE 0449).

Compile: `gcc -o rps rps.c`  
Execute: `./rps`

Example:  
```
$ gcc -o rps rps.c
$ ./rps
Welcome to Rock, Paper, Scissors.
The rules are simple:
1)Rock smashes Scissors
2)Scissors cut Paper
3)Paper covers Rock.

Good Luck.
Would you like to play? yes
Round 1. What is your choice? rock
he computer picked Paper! You lose this game!
he score is now You: 0 Computer: 1


Round 2. What is your choice? paper
The computer picked Paper! This game was a tie!
The score is now You: 0 Computer: 1


Round 3. What is your choice? scissors
The computer picked Scissors! This game was a tie!
The score is now You: 0 Computer: 1
```
