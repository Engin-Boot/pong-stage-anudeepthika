# Edit player details

## Feature

Player can make changes in photo or username or password.

## Acceptance Criteria

### Scenario: Change player photo

  Given the game is open on its home screen
  And there is option to edit player details

  When player updates different photo from current photo
  Or removes the current photo

  Then change the photo of the player to new photo.

### Scenario: Change player username

  Given the game is open on its home screen
  And there is option to edit player details

  When player enters different username from current username
  And the username field is not left empty

  Then change the username of the player to new username.
  
### Scenario: Change player password

  Given the game is open on its home screen
  And there is option to edit player details

  When player enters different password from current password
  And the password entered satisfies all the specifications

  Then change the password of the player to new password.
