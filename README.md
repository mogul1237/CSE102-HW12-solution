# CSE102-HW12-solution

Download Here: [CSE102#HW12 solution](https://jarviscodinghub.com/assignment/cse102hw12-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

In this homework, you will write a program that reads score information of players from a text file and
writes these information to a binary file. In the text file, each player represented as a line. Text file format is
given below.
Text file format:
NAME1 GAME_1 GAME_2 GAME_3 GAME_4 GAME_5
NAME2 GAME_1 GAME_2 GAME_3
NAME3 GAME_1 GAME_2 GAME_3 GAME_4
NAME4 GAME_1 GAME_2
NAME5 GAME_1 GAME_2 GAME_3 GAME_4
NAME6 GAME_1 GAME_2 GAME_3 GAME_4 GAME_5 GAME_6 GAME_7
Example
Ahmet 1.15 1.26 1.72 0.85 1.64
Fatma 1.32 1.18 1.51
Mehmet 1.24 1.11 2.07 1.55
Each player can have different number of game scores. You must read these scores until to the end of line to
construct a struct given below. This struct holds information for every player.
name: player name
scores: score array (must be dynamic)
size: score array size
average: average score
typedef struct player_scores{
char * name;
double * scores;
int size;
double average;
} PlayerScores;
You should use linked list to keep structs of the players. Each node of the linked list must store one
PlayerScores element. You should read players from a text file then you should calculate average score for
every player. You should write players in descending order to the binary file.
#notes
– This homework will NOT be graded.
– You should submit all your code including main function.
