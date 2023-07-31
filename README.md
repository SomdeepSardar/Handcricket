# Handcricket
Handcricket game using Python language with Playsound library
The game of hand-cricket is like normal cricket. In this program, you are playing against the computer. The steps are being simplified for easy understanding -

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
