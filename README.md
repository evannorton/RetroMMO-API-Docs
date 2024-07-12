# RetroMMO Public API Documentation
Documentation for RetroMMO public API

## Routes
Base URL is https://play.retro-mmo.com

### /constants.json
Returns various constant values that are used in the game.

### /game-data.json
Returns game data that is used in the game client.

### /leaderboards.json
Returns a list of players' usernames and lifetime experience. Optionally paginated with a query string parameter (e.g. `/leaderboards.json?page=2`).

### /players.json
Returns a list of online players' usernames.

### /registered-users.json
Returns the total amount of registered users.

### /usernamess/:username.json
Returns info about a username.

### /users/:username.json
Returns a user's leaderboards ranking and lifetime experience.

### /version.json
Returns the current version of the game.
