# Interaction Sequences

## Startup Sequence

-describe-how-your-modules-interact-to-start

GameMenu has PLAY and EXIT options.

When user selects PLAY option, game engine is triggered.

Game engine creates the instances of ball, paddle1, paddle2, scorekeeper1, scorekeeper2 and boundaries.

Ball and paddles are set to an initial position using SetBallPosition() and SetPaddleposition().

Initial velocity of velocity of the ball is updated to zero using SetBallVelocity().

Five second timer is displayed before the game starts.

PongGame module is created which performs lot of jobs.

## Movement Initiation

-describe-how-modules-interact-to-make-the-ball-move

## One score

-describe-how-the-modules-interact-to-record-scores
