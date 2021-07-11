<h1 align="center">Project Keno</h1>

## Project Description
<p align="left">This project is a simple simulatated version of the the game Keno, a popular gambling game similar to a bingo. In this game, the player will place his bet and choose up to twenty numbers between 1 and 80, inclusive, while the game generates other twenty random numbers, also on that same gap. Once all the numbers are chosen by the player, the game will check how many of the chosen numbers match the randomly generated ones, and give a payoff to the player based on that.</p>

## How to play
<p align="left"> - To run this game, we will be needing a bet file, containing the information of the players initial credits, the number of rounds that he wishes to play, and the numbers he has chosen to bet on, consecutively, all three of them in their separeted lines.</p>

<p align="left"> - Once we have our bet file, we will need to go to the terminal and write down:</p>

```
cd bin/
cmake ../
cmake --build .
./keno path_to_datafile
./keno ../../data/bet_01.dat
```
<p align="left"> - So we can get inside the source directory, build everything inside the bin/ directory, create an executable named 'keno', and use './keno path_to_datafile' for playing. </p>
  
<p align="left"> - For example, if one'd like to play with the bet in the datafile >bet_01.dat , the command would be ./keno ../../data/bet_01.dat .</p>


