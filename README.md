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
   
 3) **place_marker**
    
    
