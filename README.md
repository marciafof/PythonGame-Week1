<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Title of Your Project
*Battleship*

*Bulduk, Marcia and Clémence - Paris, 20/01/23*

## Content
- [Project Description](#project-description)
- [Rules](#rules)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

## Project Description
Our project is to code the game : Battleship. We choose to code a game for one player fighting against the computer. 

## Rules
The PC placed randomly 5 ships in a 10x10 array. Lenghts of ships are : 5 for the carrier; 4 for the battleship; 3 for the cruiser; 3 for the submarine and 2 for the destroyer. The ships must be placed without overlapping each other. 
The player needs to associate a Number and Letter to send a bomb and destroy PC’s ships under a maximum number of 60 guesses.If a ship a completly destroyed, it sinks. If all the ships are sunk, the player wins. 

## Workflow

GAME LOGIC FOR CODE 

1. Initiate game with empty matrix
2. For each type of ship the PC:
    Chooses RANDOMLY a first case (e.g. A3) 
    Orientation ( Vertical or Horizontal).
    Check if ship is not overlapping with previous placements
    Save final matrix hidden from player (in memory) : create a list for each boat 
3. The players has an amount of guesses
4. Ask player for placement of bomb: one letter + one number e.g. A3
    Verify for format of string : Ask again if not good
    Verify if case is already played: Ask again if True
    Check if bomb hits the ships:
    Return TOUCH if bomb hits ship 
    If TOUCH  verify if the ship is SUNK 
    If SUNK, return “SUNK”
    If not TOUCH return MISS
    Discount a guess
    Visualization
5. Check if all boats are sunk, if true return “YOU WON”, if not continue 
6. Check if amount of guess >0, if not return “GAME OVER”.  



## Organization
We planned our project on Jira, with kanban board. We detailed the game logic and edited a flowchart that was added to our repertory. 
On a google doc, we define functions that we will use for our code. We split the code work in free parts to work each on a part. After, we merge our codes, we fixed the bugs. And we improved our code working on visualization.  

Our repository contains : our readme, our flowchart, 3 files of codes for our individual work, and a main file which regroup our final code. 


## Links
Include links to your repository, slides and kanban board. Feel free to include any other links associated with your project.

[Repository](https://github.com/marciafof/PythonGame-Week1.git)  
[Slides](https://docs.google.com/presentation/d/1xpXu88ljJFCCIvD_R9ljVv4e5GNUjq8C/edit?usp=sharing&ouid=100045111133207559683&rtpof=true&sd=true)  
[Jira](https://clemencelegrand.atlassian.net/jira/software/projects/IR/boards/1)  
[Google doc](https://docs.google.com/document/d/1ya-vi_XDIL3RCmpBLD_Bx2GSfbMs4jfshOoxGUNK51o/edit)