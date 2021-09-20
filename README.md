# Queries DB to fetch a single game

- Method: Get
- Description: Uses the id of a created game to get its details



##### REQUEST BODY SCHEMA: application/json

##### Response header

```sh
{
  "message": string"
  "data": null,
  "success": boolean
}
```


##### Required parameters;
| Name | Data type |
| ------ | ------ |
| game_ID | string |





### Responses with description
``` sh

200:
Description: A successful response

404:   
Description: Game does not exist

500:
Description: An error occurred
```
##### Url link [https://chess.zuri.chat/api/v1/game/{gameId}]







# Queries DB to fetch games by user id

- Method: Get
- Description: Uses the id of a user to get all games a user has been involved in



##### REQUEST BODY SCHEMA: application/json

##### Response header

```sh
{
  "message": string"
  "data": null,
  "success": boolean
}
```


##### Required parameters;
| Name | Data type |
| ------ | ------ |
| user_ID | integer |





### Responses with description
``` sh

200:
Description: A successful response

404:   
Description: user id does not exist

500:
Description: An error occurred
```
##### Url link [https://chess.zuri.chat//api/v1/game/all/:userId]

