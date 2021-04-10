# Tic-Tac-Toe
## Table of contents
1)[Introduction](#Introduction)

2)[Language and enviornment](#Language-and-enviornment)

2)[What is the game?](#what-is-the-game?)

3)[Functions in program](#Functions-in-program)

4)[Variables in program](#variables-in-program)

5)[Summary](#Summary)

6)[Acknowledgement](#acknowledgement)

## Introduction

This project is all about creating a tic tac toe using python.it is intresting to use functions in python for this project.

To explore more and learn it all you need is knowledge of programming language python then the next story is all below ..

## Language and enviornment

Language : **Python**
 You can have installed python IDE in your computer.
 You can also have jupyter notebook from anaconda navigator.
 Set up your enviornment and start coding.
 
 ## What is the game?
 
 Tic tac toe is a small game we played in childhood.the thing is to make it computerized.
 
 This game will be played by two players P1 and P2.
 
 You will be given a checked board of 3*3 boxes.
 

7 | 8 | 9                                 |      |

------------          ____________________

4 | 5 | 6        ==                       |      |    

------------          __________________

1 | 2 | 3                                 |       |                       
   
   P1 and P2 will get alternate chances.
   each one have to choose one notation X or O. The first chance to choose their id will be given on basis of random number appears.
   case 1: if P1 gets chance first to choose and he chooses X then p2 will be O.
   This viceversa occurs.
   
   P1 and P2 will have chance to put X and O in desired box alternatively.
   if any one player got winning condition before other gets then he will be the winner.
   
   
   **Winning Conditions**
   
   1)if elements at this positions are same.
     
     * 7=8=9
     
     * 4=5=6
     
     * 1=2=3
     
     * 7=4=1
     
     * 8=5=2
     
     * 9=6=3
     
     * 9=5=1
     
     * 1=5=9
     
   If any of this conditions satisfies at any turn then thee player is winner.
   
   ## Functions in program
   
   1) The first function in program is **display_board(board)**
   
       This function is made to print format of the game board and assign the values 
       of places to the index values .
       this function takes one parameter the name of board.
       
                                      7 8 9
       
                                      4 5 6
                                      
                                      1 2 3
                                      
   2)**player_input**
      The function is player input.this function is meant to take input from player as the marker of their choice "X" OR "Y".
      and return the P1 nad P2 markers.
   
   3)**place_marker**
      Place marker is the function to place the marker of the of the player position to ine position on the board and update the board.
       It takes three parameters board,marker and position.
    
    
   4)**win_check**
        Win_check is the function to check is there winner in game after every move of the player.
        this functions checks all the winning conditions of the game.
        it returns true if any condition is satisfied or false if not.
     
   5)**choose_first**
        The program imports the library random.
        it randomly chooses any integer from 0 or 1.
        if random returns 0 then player 2 gets chance first to choose marker and if it returns 1 then player 1 gets chance.
    
    
  6)**space_check**
    this function checks if the spce in the board selected by player is empty or not.
    if space in the board is empty the function returns true.
   
   
  7)**full_board check**
      This function takes 1 parameter that is "the board".it calls our previously defined function space check to check the empty space.
      it checks all boxes from  1 to 9 and if found any block free it returns true else false.This function is called after every individual turn to check draw.
      
      
  8) **player_choice**
      This function takes one parameter that is the board and as variable position = 0.
      it asks player for his next position and checks whether the index is between 1 to 9 and if the that space is empty.
      if both conditions are satisfied it assigns the marker on that position.
     
     
   9) **replay**
     The last function for the game is replay .
     it asks to restart the game or quit it.

      
  The game will start by printing welcome to tic tac toe and will assemble all tthe functions we created inside a while loop.
  The gameon is the variable which returns boolean value for the game to start is true and stop as gameon turns false.
  
  
  
 ## Variables in program
 
 1)**theBoard** is the variable which created the board.we can say it as our game board.it is passed in display every time we want to show the board.

 2)**player1_marker and player2_marker** are the two variables which stores the values returned from our function called player input().
   we can call it as x or o is assigned to players according to rules.
   
 3)**Turn** is the variable which stores value returning from fnction choose first.it returns a string player 1 or player two on the basis of random toss between  1 and  0.

 4)**play_game** is the variable which stores the value from user called y or no ...y for yes and n for no.
   if play game is yes than gameon variable turns true else it is false.
   game goes on if game on is true.
   
 5)**position** is the variable inside while loop.it is  used to store value retuned from thr function players choice.
   this function as we seen ask player for index on the board and returns the index or say position.
   this value returned from players choice is stored inside variable position.
   then this position is passed to place marker function to place the marker of respective player on respective index and the board is displayed.
   
   
