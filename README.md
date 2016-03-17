# TheOGL
API Documentation for TheOGL.com

## Overview

TheOGL.com provides an API so that game developers can show our data within their game. The API is not intended for web use. If you wish to use this API on your website, please email us at api@theogl.com and let us know what your plans are.

By using the TheOGL.com API you agree to the following [API Terms of Service]{:target="_blank"}(http://www.theogl.com/p/api-terms-of-service) and the [Terms of Service](http://www.theogl.com/p/terms-of-service){:target="_blank"} for TheOGL.com.

#### Example Requests

GET JSON > https://api.theogl.com/games/?dev_id=&key=

### Games

| Example | Description |
| ---- | --------------- |
| GET /games/ | Get All Games |
| GET /games/game_info/?game_id=&dev_id=&key= | Get Specific Game |

### Leagues

| Example | Description |
| ---- | --------------- |
| GET /leagues/ | Get All Leagues |
| GET /leagues/league_info/?league_id=&dev_id=&key= | Get Specific League |

### Tournaments

| Example | Description |
| ---- | --------------- |
| GET /tournaments/ | Get All Tournaments |
| GET /tournaments/tournament_info/?tournament_id=&dev_id=&key= | Get Specific Tournament |

### Teams

| Example | Description |
| ---- | --------------- |
| GET /teams/ | Get All Teams |
| GET /teams/team_info/?team_id=&dev_id=&key= | Get Specific Team |

### Players

| Example | Description |
| ---- | --------------- |
| GET /players/ | Get All Players |
| GET /player/player_info/?player_id=&dev_id=&key= | Get Specific Player |
