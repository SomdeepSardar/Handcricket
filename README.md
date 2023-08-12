# Handcricket 
Handcricket game using Python language with Playsound library.
The game is being played against the computer..
To play the game:-
1) Download the code as Zip by clicking on CODE and then DOWNLOAD ZIP.
2) Next, unzip the file in your folder and inside the Handcricket folder, run the Handcricket.exe file.
3) The Handcricket.txt file contains the records of the games being played.

Functionalities:-
1) The game uses the traditional Handcricket method of toss.
2) The game has proper errorhandling in place to handle all the edge cases properly.
3) The program plays aesthetic music in the background while the game is running that adds to the intense environment
4) If one manages to take a hat-trick, then the game applauds for the same in a proper manner.
5) At the end of the play, the game prints a summary of whatever happened in the game including the runs scored, Fall Of Wickets , the winner and by what margin, and even the date and time of the occurence of the game. 
6) The game also records the summary in a file named "Handcricket.txt" which can be found inside the Handcricket folder.

The game of hand-cricket is like normal cricket. The steps are being simplified for easy understanding -
1) You need to select the no of wickets you want to have for the game. It can range from 1 to 10.
2)  (a)Then comes the toss. Now, for the toss you need to choose from either Odd or Even.

    (b)Now, no matter what you choose the next step is that you as well as the computer will have to choose something between 1 and 6. Let the computer choose x and you choose y. Now, the sum of x and y will determine who wins the toss. 
    As an instance, let you have chosen Even. Now, perhaps the computer has chosen 1 and you have chosen 3. The sum is 1+3= 4, which is an even no. Hence you win the toss.
3) Now, the winner of the toss gets the chance to choose if he wants to bat or bowl first. Based on his decision we will proceed.
    BATTING:- Now the aim of the batsman is to choose a number x from 1 to 6 such that it is different from the y that the bowler chooses in the same range. If x ≠ y then the batsman scores x + his previous score. But if x = y, then he loses wickets. The batsman can lose as many wickets as he began his game with. 

    BOWLING:- During bowling, the aim is to pick up all the wickets. The aim of the bowlers is to pick up wickets. To pickup wickets, he will need to choose the same number that the batsman chooses.

    TARGET:- The target can be defined as the score of the 1st innings +1
    
    TO WIN:- To win the match when you're batting first, you'll need to score and then restrict your opponent to a score that is lesser than the target.
      To win the match when you're batting second, the aim is to chase down the target before you lose all your wickets.

HOPE YOU WILL ENJOY THE GAME!!