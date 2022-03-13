# RocksPaperScissorsGame
The main logic of the Pogramme is, it accepts a String and an integer.<br>
The String should contain only characters of 'p','r','s','P','R','S'. where P represents paper, R represents Rock and S represents Scissors.
Integer gives us no of matches. <br>
So, length of the string should be exactly equal to 2*n (As each match contains 2 characters). <br>
If length doesn't match or String contains any invalid characters other than p,r,s it throws an HTTP.BADRequest (400 status code). <br><br>

Let's come to the logic of the game:- It get 2 characters in each match and determines who is the winner whether player 1 or player 2.
And finally all the results of all matches are stored in the array and returend in JSON format.

<b> Some pics are attached for refernce purpose. (postman) <b>
