# Checks score

## Feature

Checks whether score is equal to maximum score.

## Acceptance Criteria

### Scenario: Check player score

  Given the game is active
  And the ball is moving away from the player

  When player score increases

  Then compare the current score with the maximum score.
