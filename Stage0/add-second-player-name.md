# Add second player name

## Feature

Opens a text box to add name of second player and updates the player name

## Acceptance Criteria

### Scenario: Open a text box to add name

  Given the game is in progress
  And the player chose to play game

  When player selects to play the game in two player mode

  Then pop a text box with default name to update the name.

### Scenario: Update the name

  Given the game is in progress
  And the player chose to play game in two player mode.

  When player changes the default name in text box
  Or leaves the default name unchanged
  And press continue

  Then update the name of the second player.
