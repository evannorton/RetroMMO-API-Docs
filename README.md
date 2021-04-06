# RetroMMO Public API Documentation
Documentation for RetroMMO public API

## Routes
Base URL is https://play.retro-mmo.com

### /leaderboards.json
Returns a list of players' usernames and lifetime experience. Optionally paginated with a query string parameter (e.g. /leaderboards.json?page=2). 100 players per page.

### /players.json
Returns a list of online players' usernames.

### /users/:username.json
Returns a user's leaderboards ranking and lifetime experience.