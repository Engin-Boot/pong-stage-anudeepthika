# Updates score

## Feature

Increases the score of the player when there is collision between ball
And opposite vertical boundary

## Acceptance Criteria

### Scenario: Check player score

  Given the game is active
  And the paddle misses the ball hit

  When there is a collision between ball and vertical boundary

  Then score of the opposite paddle or player by one.
