# Checks score

## Feature

Checks whether score is equal to maximum score.
And updates the game-state.

## Acceptance Criteria

### Scenario: Check player score

  Given the game is active
  And the ball is moving away from the player

  When player score increases

  Then compare the current score with the maximum score.

### Scenario: Update game-state to MENU
  
  Given the game is active
  And the score of a player is increased
  
  When score equals to maximum score
  
  Then update game-state to MENU.

### Scenario: Update game-state to IN-GAME
  
  Given the game is active
  And the score of a player is not increased
  
  When score not equals to maximum score
  
  Then update game-state to IN-GAME.
