# Pong in Snap!

Students will implement a well-written and engineered version of the classic arcade game Pong.

## Overview

In 1972, when video games were still very new and relatively unknown, a new game took the world by storm.
A simple simulation of tennis using two-dimensional graphics, minimal sounds, and extremely basic controls,
Pong became the first arcade game to achieve widespread popularity and is credited as the genesis of the
modern video game industry. Today, the game has been played, remade, spun-off, and referenced
innumerable times and it remains, to many, the single most identifiable and recognizable game in the history
of video games.

## Details

1) **Behavior**
    1) **Gameplay**
       Pong is played by two players each controlling a paddle with the goal of defending their end of the "field." A ball begins play in the middle of the screen and, at the start of each round, moves in a random direction. The ball bounces off the upper and lower edges of the field and the players' paddles. Each time the ball bounces off a paddle, its speed increases by a small amount. When the ball bounces off a paddle, its direction is reversed with a small random variation to add unpredictability to the game.
       
    2) **Scoring**
        If the ball touches the left or right edge of the field, a point is scored for the opponent of the player who was defending that edge and the ball resets to the middle of the field. When one
player reaches 5 points, the game is over and that player is the winner. The winner is
announced on the screen and the players are given the opportunity to start a new game.

    3) **Player Control**
        Paddles are positioned a short distance away from the side they are defending, and can only move up and down, not side to side. Each player should have two keys to control the movement of their paddle: one for up, and one for down. Paddles move at a set speed that is the same for both players can cannot be controlled. The player on the left will control his/her paddle with the 'w' and 's' keys. The player on the right will use the up arrow and down arrow keys.
        
2) **Required Checkpoints**
    1) Players can control paddles; the ball starts in the middle, moves in a random direction, and bounces
    
    2) The ball speeds up when it hits a paddle, and resets to the middle when it hits the left or right
edge

    3) Final due date: A point is scored when the ball hits the edge on the opponent's side of the field; the game ends when one player reaches five points; players can start a new game after the game ends


## Grading Scheme/Rubric

|Requirement|Points|
|-----|-----|
|Players can control paddles with required keys| 2 points|
|Ball begins play at middle of field at start of game and after each point | 3 points|
|Ball bounces correctly off upper and lower edges and paddles |4 points|
|Ball increases in speed each time it bounces off a paddle |3 points|
|A point is scored for the opponent each time the ball touches the left or right edge |3 points|
|Game ends when one player reaches five points |2 points|
|Winning player is shown when game ends |2 points|
|Players can begin a new game |1 point|
|**Sub-Total 1** | **20 points**|
|Technical Correctness (Implementation)|
|Gameplay is smooth, polished, and intuitive |3 points|
|Program does not use a forever loop or stop/pause all block| 2 points|
|Program is well-documented and exhibits good style (Cleaned up with Comments)|2 points|
|Checkpoint 1 |4 points|
|Checkpoint 2 |4 points|
|**Sub-Total 2** |**15 points**|
|**Total** | **35 points**|


## Need Help Getting Started?
Helpful links / hints:
* [Game of Pong Description](https://bjc.edc.org/bjc-r/cur/programming/1-introduction/optional-projects/3-pong.html?topic=nyc_bjc%2F1-intro-loops.topic&course=bjc4nyc.html&novideo&noassignment)
* [Pong Hints](https://bjc.edc.org/bjc-r/cur/programming/1-introduction/optional-projects/3b-pong-hints.html)
* [Starter Code](https://snap.berkeley.edu/snap/snap.html#open:https://bjc.edc.org/bjc-r/prog/1-introduction/U1L5-pong-student.xml)

```
This work is licensed under a Creative Commons Attribution-
NonCommercial-ShareAlike 4.0 International License

Adapted from https://github.com/TEALSK12/introduction-to-computer-science/blob/master/Projects/Projects%20PDF/Project%202%20Pong.pdf
```