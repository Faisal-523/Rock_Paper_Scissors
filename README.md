# Rock_Paper_Scissors
The Odin Project - Javascript assignment

1. Create a variable called computerSelection
2. Create a variable playerSelection
3. Create variable playerScore
4. Create variable computerScore
5. Write a function computerplay which returns either rock papaer or scissors randomly.Use math.random to return a random number between 0 and 2.Map these numbers to rock, paper and scissors strings. Copy the result to computerSelection.
6. Write a function playRound which accepts two arguments: computerSelection and PlayerSelection.
If computerSelection and PlayerSelection is Rock, return a string "Its a tie". Increment playerScore and computerScore. 
If computerSelection and PlayerSelection is Paper, return a string "Its a tie". Increment playerScore and computerScore. 
If computerSelection and PlayerSelection is Scissors, return a string "Its a tie". Increment playerScore and computerScore. 
If computerSelection is Rock and PlayerSelection is Paper, return a string "You Win. paper beats Rock". Increment playerScore. 
If computerSelection is Paper and PlayerSelection is Rock, return a string "Computer Wins. paper beats Rock". Increment computerScore
If computerSelection is Scissors and PlayerSelection is Paper, return a string "Computer wins. Scissors beat Paper". Increment computerScore.
If computerSelection is Paper and PlayerSelection is Scissors, return a string "You win. Scissors beat Paper". Increment playerScore.
If computerSelection is Scissors and PlayerSelection is Rock, return a string "You win. Rock beats Scissors". Increment playerScore.
If computerSelection is Rock and PlayerSelection is Scissors, return a string "Computer wins. Rock beats Scissors". Increment computer Score.
7. Write a function game which calls computerplay 5 times. After end of 5 times if computerScore is greater than playerScore, then computer wins.
Else Player wins. If computerScore and playerScore are equal, then its a tie.
