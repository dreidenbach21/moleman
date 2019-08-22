# moleman

2D 100% random world generator based on probability functions. User has control over a mole which can burrow, creating new rooms and hallways as they search for the exit while avoiding various enemies based on the chosen difficulty. Enemy movement is based of A Star search algorithm. User may also save and load their game, resuming the game at the exact moment of the saved state.

For academic reasons I am unable to post the code for this project since it was started as a class project and later expanded upon. Thank you Professor Hug for designing the tile renderer to help me save time with displaying the work.

The goal of the game is to take your character the @ and reach the golden door digging into it to open and win freedom.

Please Email me @dreidenbach@berkeley.edu if you have any questions or would like me to securely share the code.

When starting the game you are prompted and can choose N(New Game), L(Load Game), or Q(Quit)

![start](https://i.postimg.cc/XqMGmyRV/Screen-Shot-2019-08-21-at-10-46-16-PM.png)

After selecting the user is prompted to enter a seed value. This is a number that sets all the random choices for every aspect of world creation. I designed a creation process to randomly build rooms and hallways unitl a certain percentage of the world is filled. To submit the seed press 's'

![mid user selection](https://i.postimg.cc/PJmpj5H1/Screen-Shot-2019-08-21-at-10-46-26-PM.png)

After the seed is submitted the user is prompted to enter their name. enter your name(there is no delete for now) and press';' to submit

![game example 1](https://i.postimg.cc/CMDfDm8d/Screen-Shot-2019-08-21-at-10-51-23-PM.png)

After the name is entered press E, M, or H to select the difficulty. The difficulty determines the number of enemies that will appear in the world

![game example 2](https://i.postimg.cc/YqzGD0bH/Screen-Shot-2019-08-21-at-10-51-37-PM.png)

The game controls are  W A S D for movement I J K L for direction digging Z to display the A Star algorithim path that all enemies are locked on to you. X to display your A Star path to the golden door. Your mouse also displays information about what block you are hovering over in the top left corner.


To Quit the game press :(shift ;) then q. This autosaves the exact point in teh game writing the history into a text file. If you want to resume rerun the program and select L for load game. Since all the game's choices are based of the initally entered random seed rerunning the entire program from that seed will result i nthe exact same outputs thus resuming the game.



The rest of the images are different stages of the game showing different seeds and difficulties. 


![start](https://i.postimg.cc/jS8WK1p3/Screen-Shot-2019-08-21-at-10-52-06-PM.png)

![mid user selection](https://i.postimg.cc/cJ2rtn4Q/Screen-Shot-2019-08-21-at-10-52-21-PM.png)

![game example 1](https://i.postimg.cc/j5fCHSLB/Screen-Shot-2019-08-21-at-10-52-35-PM.png)

![game example 2](https://i.postimg.cc/3NHNnQGN/Screen-Shot-2019-08-21-at-10-52-46-PM.png)

![start](https://i.postimg.cc/FK7YKZmr/Screen-Shot-2019-08-21-at-10-53-04-PM.png)

![mid user selection](https://i.postimg.cc/2j4V33pZ/Screen-Shot-2019-08-21-at-10-53-25-PM.png)

![game example 1](https://i.postimg.cc/sx9XLHPc/Screen-Shot-2019-08-21-at-10-54-05-PM.png)

![game example 2](https://i.postimg.cc/L84qcSbZ/Screen-Shot-2019-08-21-at-10-54-30-PM.png)

![game example 2](https://i.postimg.cc/BQ4tFssw/Screen-Shot-2019-08-21-at-10-54-57-PM.png)
![start](https://i.postimg.cc/pdhdvLYy/Screen-Shot-2019-08-21-at-10-55-22-PM.png)

![mid user selection](https://i.postimg.cc/m2jkNqgZ/Screen-Shot-2019-08-21-at-10-56-16-PM.png)

![game example 1](https://i.postimg.cc/vZSmCVnp/Screen-Shot-2019-08-21-at-10-56-44-PM.png)

![game example 2](https://i.postimg.cc/k50ggPfs/Screen-Shot-2019-08-21-at-10-57-25-PM.png)






