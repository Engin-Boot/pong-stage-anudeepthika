# Interaction Sequences

## Startup Sequence

Game menu has PLAY and EXIT options.

When user selects PLAY option, game engine is triggered.

Game engine creates the instances of ball, paddle-one, paddle-two
Scorekeeper-one, scorekeeper-two and boundaries.

Ball and paddles are set to an initial position using Set-Ball-Position and Set-Paddle-Position.

Initial velocity of velocity of the ball is updated to zero using Set-Ball-Velocity.

Five second timer is displayed before the game starts.

Ball moves in a random direction.

Pong game module is created which performs lot of jobs.

## Movement Initiation

Pong game module keeps track of many operations

- It updates ball movement --> To get ball position call Get-Ball-Position.
And to update velocity call Set-Ball-Velocity

- checks for the collision of ball with paddles and boundaries

- updates the ball movement if collision occurs.

- Updates the score of player-one and player-two,
if collision occurs with boundaries behind the paddle

- Calls check-score module to check if it is the maximum score.
  This updates game-state to MENU state if score is equal to maximum score.
  And continues in IN-GAME state if score is not equal to maximum score.
  
- If game-state returns MENU state then it goes back to the Game Menu

## One score

Pong game module calls for the check-collision of ball with paddles
And boundaries

Update the score of the opposite player if there is collision with vertical boundary
