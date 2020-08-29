# Checks for collision

## Feature

Keeps track of ball co-ordinates and checks for the collision.

## Acceptance Criteria

### Scenario: Check for collision with paddle

  Given the game is active.
  The ball position and paddle position are obtained

  When the co-ordinates of the ball equals to paddle co-ordinates

  Then update a flag that indicate collision with paddle.
  
### Scenario: Check for collision with horizontal boundary

  Given the game is active.
  The ball position is obtained

  When the co-ordinates of the ball equals to horizontal boundary co-ordinates

  Then update a flag that indicate collision with horizontal boundary.
  
### Scenario: Check for collision with vertical boundary

  Given the game is active.
  The ball position is obtained

  When the co-ordinates of the ball equals to vertical boundary co-ordinates

  Then update a flag that indicate collision with vertical boundary.
