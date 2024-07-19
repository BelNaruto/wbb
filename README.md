# Women's College Basketball (WBB) API Documentation

The **Women's College Basketball API** provides comprehensive access to real-time and historical data from the world of women's college basketball. Designed for developers, sports analysts, and basketball enthusiasts, this API delivers detailed statistics, game information, player data, and more, allowing for in-depth insights and seamless integration into various applications.
This API can be found [here](https://rapidapi.com/belchiorarkad-FqvHs2EDOtP/api/womens-college-basketball-wbb)

## Key Features

- **Live Game Data**: Access real-time updates during women's college basketball games, including scores, plays, and player stats.
- **Player and Team Information**: Retrieve detailed profiles and statistics for players and teams, including standings and performance metrics.
- **Game Schedule**: Get information on upcoming games, including dates, locations, and matchups.
- **Historical Data**: Access past game results, player statistics, and historical records for comprehensive analysis.

## Getting Started

1. **Sign Up**: Create an account on RapidAPI.
2. **Subscribe**: Choose a subscription plan that suits your needs.
3. **API Key**: Obtain your unique API key to begin making requests.
4. **Documentation**: For detailed usage instructions, visit the [Women's College Basketball API Documentation](https://rapidapi.com/belchiorarkad-FqvHs2EDOtP/api/womens-college-basketball-wbb).

## Retrieve Play by Play Data

GET /pbp/{gameId}

Retrieve Play by Play data for a specific game.

### Parameters

| Name    | Type   | Description             |
|---------|--------|-------------------------|
| `gameId`| string | ID of the game          |

### Response

- Status: `200 OK`
- Content: JSON object representing the Play by Play data



## Retrieve Box Score Data

GET /boxscore/{gameId}

Retrieve Box Score data for a specific game.

### Parameters

| Name    | Type   | Description             |
|---------|--------|-------------------------|
| `gameId`| string | ID of the game          |

### Response

- Status: `200 OK`
- Content: JSON object representing the Box Score data
\```


## Retrieve Summary Data

GET /summary/{gameId}

Retrieve Summary data for a specific game.

### Parameters

| Name    | Type   | Description             |
|---------|--------|-------------------------|
| `gameId`| string | ID of the game          |

### Response

- Status: `200 OK`
- Content: JSON object representing the Summary data



## Retrieve Rankings

GET /rankings

Retrieve rankings data for a specific year and week.

### Parameters

| Name    | Type   | Description             |
|---------|--------|-------------------------|
| `year`  | number | Year                    |
| `week`  | number | Week (default: 1)       |

### Response

- Status: `200 OK`
- Content: JSON object representing the rankings data



## Retrieve Schedule Data

GET /schedule

Retrieve schedule data for a specific year, month, and day.

### Parameters

| Name        | Type   | Description                   |
|-------------|--------|-------------------------------|
| `year`      | number | Year                          |
| `month`     | number | Month                         |
| `day`       | number | Day                           |
| `group`     | number | Group (default: 50)           |
| `seasontype`| number | Season type (default: 2)      |

### Response

- Status: `200 OK`
- Content: JSON object representing the schedule data

## Retrieve Scoreboard Data

GET /scoreboard

Retrieve scoreboard data for a specific year, month, and day.

### Parameters

| Name         | Type   | Description                              |
|--------------|--------|------------------------------------------|
| `year`       | number | Year                                     |
| `month`      | number | Month                                    |
| `day`        | number | Day                                      |
| `group`      | number | Group (default: 50)                      |
| `seasontype` | number | Season type (default: 1)                 |
| `limit`      | number | Limit on the number of results (default: 200) |

### Response

- Status: `200 OK`
- Content: JSON object representing the scoreboard data

## Retrieve Conferences Data

GET /conferences

Retrieve conferences data for a specific year.

### Parameters

| Name    | Type   | Description             |
|---------|--------|-------------------------|
| `year`  | number | Year                    |
| `group` | number | Group (default: 50)     |

### Response

- Status: `200 OK`
- Content: JSON object representing the conferences data


## Retrieve Standings Data

GET /standings

Retrieve standings data for a specific year.

### Parameters

| Name    | Type   | Description             |
|---------|--------|-------------------------|
| `year`  | number | Year                    |
| `group` | number | Group (default: 50)     |

### Response

- Status: `200 OK`
- Content: JSON object representing the standings data

## Retrieve Team List Data

GET /team-list

Retrieve list of teams.

### Parameters

| Name    | Type   | Description             |
|---------|--------|-------------------------|
| `group` | number | Group (default: 50)     |

### Response

- Status: `200 OK`
- Content: JSON object representing the team list data


## Retrieve Team Info Data

GET /team-info/:teamId

Retrieve information for a specific team.

### Parameters

| Name     | Type   | Description             |
|----------|--------|-------------------------|
| `teamId` | string | ID of the team          |

### Response

- Status: `200 OK`
- Content: JSON object representing the team info data

## Retrieve Team Players Data

GET /team-players/:teamId

Retrieve players for a specific team.

### Parameters

| Name     | Type   | Description             |
|----------|--------|-------------------------|
| `teamId` | string | ID of the team          |

### Response

- Status: `200 OK`
- Content: JSON object representing the team players data


## Retrieve News Data

GET /news

Retrieve latest news data.

### Response

- Status: `200 OK`
- Content: JSON object representing the news data

## Retrieve Player Statistics Data

GET /player-statistic

Retrieve statistics for a specific player.

### Parameters

| Name       | Type   | Description             |
|------------|--------|-------------------------|
| `playerId` | string | ID of the player        |

### Response

- Status: `200 OK`
- Content: JSON object representing the player statistics data

## Retrieve Team Statistics Data

GET /team-statistic

Retrieve statistics for a specific team.

### Parameters

| Name     | Type   | Description             |
|----------|--------|-------------------------|
| `teamId` | string | ID of the team          |

### Response

- Status: `200 OK`
- Content: JSON object representing the team statistics data

## Retrieve Injuries Data

GET /injuries

Retrieve injury data for the current season.

### Response

- Status: `200 OK`
- Content: JSON object representing the injuries data


## Retrieve Team Roster Data

GET /team-roster

Retrieve roster for a specific team and season.

### Parameters

| Name     | Type   | Description             |
|----------|--------|-------------------------|
| `teamId` | string | ID of the team          |
| `season` | number | Season                   |

### Response

- Status: `200 OK`
- Content: JSON object representing the team roster data
## Retrieve Schedule by Team Data

GET /schedule-team

Retrieve schedule data for a specific team and season.

### Parameters

| Name     | Type   | Description             |
|----------|--------|-------------------------|
| `teamId` | string | ID of the team          |
| `season` | number | Season                   |

### Response

- Status: `200 OK`
- Content: JSON object representing the team schedule data

If you have any question, feel free to send us a private message. Have a nice day!


