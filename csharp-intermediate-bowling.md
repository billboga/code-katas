A Bowling We Will Go
=======

### Language
*C#*

### Difficulty
*Intermediate*
  - this is due to the expectation of having multiple projects within the solution and knowledge of ASP.NET MVC and writing tests.

### Abstract
We have been requisitioned to build an app. for scoring a game of bowling for one-player. The player is not expected to know the various rules for scoring between frames - they just want to knock-down pins! The app. should be web-driven and allow for entering number of pins knocked-down per frame. Additionally, the player's overall tally should be easily-visible at all times. Once the game is over, the player's total should be visible and the player should be given the option to start a new game.

### Goals
  - Learn how to score one-game of bowling.
  - Learn how to keep state in a stateless environment (HTTP).
  - Learn how to write tests against the app.'s logic.

### Base Requirements
  - App. is written in C#.
  - Uses ASP.NET MVC5 for UI.
  - Valid tests for scoring are necessary.
    - if the player's first throw is three and the second is five, then the test should confirm the current score is eight.
    - complete test-coverage is not the goal.
  - UI needs to maintain game-tally for all frames.
  - UI needs to allow a way to enter pins knocked-down per throw.

### Possible Enhancements
  - Add API-driven back-end for logic
    - this could mean having a dynamic client making AJAX requests or just calling the API-endpoints from the MVC-endpoints.
  - Aim for eighty-five percent or higher test-coverage.
  - Add graphics to represent spares, strikes, and turkeys.
  - Provide styling for print-out of game scorecard.
