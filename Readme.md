### Football API by Futmetrics

Over 900+ leagues and cups. Deep field statistics, player profiles, and gameplay metrics. Livescores, live news feed, predictions, lineups and much more! The only football API you’ll ever need.

#### Features:

1. In-field statistics of players in real time
2. Complete player profiles (Market fee, attributes, trophies, clubs, transfer history)
3. Complete club profiles (history, trophies, squads)
4. Complete coach profiles
5. League gameplay statistics
7. Club/Team gameplay statistics
8. Probable lineups of each match
9. Gameplay statistics of each match
10. Club/League/Player related news and much more!


Please refer to our documentation here - https://rapidapi.com/shanjohridev/api/football-api-by-futmetrics

Plans and pricing - https://rapidapi.com/shanjohridev/api/football-api-by-futmetrics/pricing

If you have any questions or need support. Please email us at   `support@futmetrics.com`



#### Sample request [Get shotmap of match - Arsenal vs Liverpool]

```python

import requests

url = "https://football-api-by-futmetrics.p.rapidapi.com/api/data/get_match_shotmap"

payload = {"match_id": 3901022}
headers = {
	"content-type": "application/json",
	"X-RapidAPI-Key": "4c62d63354msh6a96ded3bb7cea5p13f8a8jsnb1ed659d1c42",
	"X-RapidAPI-Host": "football-api-by-futmetrics.p.rapidapi.com"
}

response = requests.request("POST", url, json=payload, headers=headers)

print(response.text)
```

#### Sample response

```json
{
  "status": "success",
  "data": {
    "shots": [
      {
        "id": 2469795803,
        "eventType": "Goal",
        "teamId": 9825,
        "playerId": 1021586,
        "playerName": "Gabriel Martinelli",
        "x": 96.60526021232141,
        "y": 39.376905404232446,
        "min": 1,
        "minAdded": null,
        "isBlocked": false,
        "isOnTarget": true,
        "blockedX": null,
        "blockedY": null,
        "goalCrossedY": 32.39875,
        "goalCrossedZ": 0.6099999970000001,
        "expectedGoals": 0.450450599193573,
        "expectedGoalsOnTarget": 0.6301,
        "shotType": "RightFoot",
        "situation": "RegularPlay",
        "period": "FirstHalf",
        "isOwnGoal": false,
        "onGoalShot": {
          "x": 1.4236111111111112,
          "y": 0.16137566058201058,
          "zoomRatio": 1
        },
        "firstName": "Gabriel",
        "lastName": "Martinelli",
        "teamColor": "#bd0510"
      },
      {
        "id": 2469799941,
        "eventType": "AttemptSaved",
        "teamId": 8650,
        "playerId": 950561,
        "playerName": "Darwin Nunez",
        "x": 85.81617647,
        "y": 21.196688168771782,
        "min": 6,
        "minAdded": null,
        "isBlocked": true,
        "isOnTarget": true,
        "blockedX": 89.5,
        "blockedY": 23.438726119099996,
        "goalCrossedY": 33.8475,
        "goalCrossedZ": 1.2199999940000001,
        "expectedGoals": 0.10151240229606628,
        "expectedGoalsOnTarget": null,
        "shotType": "RightFoot",
        "situation": "RegularPlay",
        "period": "FirstHalf",
        "isOwnGoal": false,
        "onGoalShot": {
          "x": 1.0403439153439162,
          "y": 0.32275132116402117,
          "zoomRatio": 1
        },
        "firstName": "Darwin",
        "lastName": "Nunez",
        "teamColor": "#d3171e"
      },
      {
        "id": 2469807029,
        "eventType": "Miss",
        "teamId": 8650,
        "playerId": 209405,
        "playerName": "Virgil van Dijk",
        "x": 92.4000015258789,
        "y": 36.2875,
        "min": 12,
        "minAdded": null,
        "isBlocked": false,
        "isOnTarget": false,
        "blockedX": null,
        "blockedY": null,
        "goalCrossedY": 30.72125,
        "goalCrossedZ": 5.305931043199999,
        "expectedGoals": 0.014045178890228271,
        "expectedGoalsOnTarget": null,
        "shotType": "Header",
        "situation": "FromCorner",
        "period": "FirstHalf",
        "isOwnGoal": false,
        "onGoalShot": {
          "x": 1.4184994268583453,
          "y": 0.6772486772486772,
          "zoomRatio": 0.48247894274480957
        },
        "firstName": "Virgil",
        "lastName": "van Dijk",
        "teamColor": "#d3171e"
      },
      {
        "id": 2469819453,
        "eventType": "AttemptSaved",
        "teamId": 8650,
        "playerId": 950561,
        "playerName": "Darwin Nunez",
        "x": 95.3508786640393,
        "y": 18.464204358343565,
        "min": 26,
        "minAdded": null,
        "isBlocked": false,
        "isOnTarget": true,
        "blockedX": 103.103448276,
        "blockedY": 30.291999999999998,
        "goalCrossedY": 33.5425,
        "goalCrossedZ": 0.8925263114,
        "expectedGoals": 0.02872854471206665,
        "expectedGoalsOnTarget": 0.0201,
        "shotType": "RightFoot",
        "situation": "RegularPlay",
        "period": "FirstHalf",
        "isOwnGoal": false,
        "onGoalShot": {
          "x": 1.121031746031747,
          "y": 0.2361180717989418,
          "zoomRatio": 1
        },
        "firstName": "Darwin",
        "lastName": "Nunez",
        "teamColor": "#d3171e"
      },
      {
        "id": 2469821035,
        "eventType": "AttemptSaved",
        "teamId": 9825,
        "playerId": 576165,
        "playerName": "Gabriel Jesus",
        "x": 100.44827296849174,
        "y": 47.71413798622574,
        "min": 28,
        "minAdded": null,
        "isBlocked": false,
        "isOnTarget": true,
        "blockedX": 104.4310344828,
        "blockedY": 37.732,
        "goalCrossedY": 37.355000000000004,
        "goalCrossedZ": 0.0385263156,
        "expectedGoals": 0.044982582330703735,
        "expectedGoalsOnTarget": 0.234,
        "shotType": "RightFoot",
        "situation": "RegularPlay",
        "period": "FirstHalf",
        "isOwnGoal": false,
        "onGoalShot": {
          "x": 0.11243386243386144,
          "y": 0.010192146984126984,
          "zoomRatio": 1
        },
        "firstName": "Gabriel",
        "lastName": "Jesus",
        "teamColor": "#bd0510"
      },
      {
        "id": 2469823521,
        "eventType": "Miss",
        "teamId": 8650,
        "playerId": 292462,
        "playerName": "Mohamed Salah",
        "x": 93.0999984741211,
        "y": 17.6234394922,
        "min": 32,
        "minAdded": null,
        "isBlocked": false,
        "isOnTarget": false,
        "blockedX": null,
        "blockedY": null,
        "goalCrossedY": 28.959285713000003,
        "goalCrossedZ": 0.5329473658000001,
        "expectedGoals": 0.05841514468193054,
        "expectedGoalsOnTarget": null,
        "shotType": "LeftFoot",
        "situation": "RegularPlay",
        "period": "FirstHalf",
        "isOwnGoal": false,
        "onGoalShot": {
          "x": 2,
          "y": 0.10572854072972776,
          "zoomRatio": 0.7498937223537185
        },
        "firstName": "Mohamed",
        "lastName": "Salah",
        "teamColor": "#d3171e"
      },
      {
        "id": 2469825747,
        "eventType": "Goal",
        "teamId": 8650,
        "playerId": 950561,
        "playerName": "Darwin Nunez",
        "x": 97.47368273756071,
        "y": 31.7125,
        "min": 34,
        "minAdded": null,
        "isBlocked": false,
        "isOnTarget": true,
        "blockedX": null,
        "blockedY": null,
        "goalCrossedY": 33.466249999999995,
        "goalCrossedZ": 1.0145263108,
        "expectedGoals": 0.46570301055908203,
        "expectedGoalsOnTarget": 0.3026,
        "shotType": "RightFoot",
        "situation": "RegularPlay",
        "period": "FirstHalf",
        "isOwnGoal": false,
        "onGoalShot": {
          "x": 1.141203703703705,
          "y": 0.2683932039153439,
          "zoomRatio": 1
        },
        "firstName": "Darwin",
        "lastName": "Nunez",
        "teamColor": "#d3171e"
      },
      {
        "id": 2469842731,
        "eventType": "Goal",
        "teamId": 9825,
        "playerId": 961995,
        "playerName": "Bukayo Saka",
        "x": 102.43965806650827,
        "y": 30.95,
        "min": 45,
        "minAdded": 5,
        "isBlocked": false,
        "isOnTarget": true,
        "blockedX": null,
        "blockedY": null,
        "goalCrossedY": 33.00875,
        "goalCrossedZ": 0.0385263156,
        "expectedGoals": 0.8906897306442261,
        "expectedGoalsOnTarget": 0.9529,
        "shotType": "RightFoot",
        "situation": "FastBreak",
        "period": "FirstHalf",
        "isOwnGoal": false,
        "onGoalShot": {
          "x": 1.26223544973545,
          "y": 0.010192146984126984,
          "zoomRatio": 1
        },
        "firstName": "Bukayo",
        "lastName": "Saka",
        "teamColor": "#bd0510"
      },
      {
        "id": 2469858445,
        "eventType": "AttemptSaved",
        "teamId": 9825,
        "playerId": 961995,
        "playerName": "Bukayo Saka",
        "x": 94.4824561388,
        "y": 30.316,
        "min": 48,
        "minAdded": null,
        "isBlocked": true,
        "isOnTarget": true,
        "blockedX": 95.15789473550001,
        "blockedY": 30.416249999999994,
        "goalCrossedY": 34,
        "goalCrossedZ": 1.2199999940000001,
        "expectedGoals": 0.15563863515853882,
        "expectedGoalsOnTarget": null,
        "shotType": "RightFoot",
        "situation": "RegularPlay",
        "period": "SecondHalf",
        "isOwnGoal": false,
        "onGoalShot": {
          "x": 1,
          "y": 0.32275132116402117,
          "zoomRatio": 1
        },
        "firstName": "Bukayo",
        "lastName": "Saka",
        "teamColor": "#bd0510"
      },
      {
        "id": 2469858459,
        "eventType": "AttemptSaved",
        "teamId": 9825,
        "playerId": 534670,
        "playerName": "Martin Ødegaard",
        "x": 91.5,
        "y": 30.256,
        "min": 48,
        "minAdded": null,
        "isBlocked": true,
        "isOnTarget": true,
        "blockedX": 93,
        "blockedY": 30.328,
        "goalCrossedY": 34.38125,
        "goalCrossedZ": 1.2199999940000001,
        "expectedGoals": 0.08665627241134644,
        "expectedGoalsOnTarget": null,
        "shotType": "LeftFoot",
        "situation": "RegularPlay",
        "period": "SecondHalf",
        "isOwnGoal": false,
        "onGoalShot": {
          "x": 0.8991402116402113,
          "y": 0.32275132116402117,
          "zoomRatio": 1
        },
        "firstName": "Martin",
        "lastName": "Ødegaard",
        "teamColor": "#bd0510"
      },
      {
        "id": 2469860513,
        "eventType": "AttemptSaved",
        "teamId": 9825,
        "playerId": 534670,
        "playerName": "Martin Ødegaard",
        "x": 90.30000305175781,
        "y": 37.659999418258664,
        "min": 50,
        "minAdded": null,
        "isBlocked": false,
        "isOnTarget": true,
        "blockedX": 101.3965517244,
        "blockedY": 34.68625,
        "goalCrossedY": 34,
        "goalCrossedZ": 0.160526315,
        "expectedGoals": 0.1746305525302887,
        "expectedGoalsOnTarget": 0.0247,
        "shotType": "LeftFoot",
        "situation": "RegularPlay",
        "period": "SecondHalf",
        "isOwnGoal": false,
        "onGoalShot": {
          "x": 1,
          "y": 0.042467279100529096,
          "zoomRatio": 1
        },
        "firstName": "Martin",
        "lastName": "Ødegaard",
        "teamColor": "#bd0510"
      },
      {
        "id": 2469863493,
        "eventType": "Goal",
        "teamId": 8650,
        "playerId": 242709,
        "playerName": "Roberto Firmino",
        "x": 93.30000305175781,
        "y": 43.44025370301287,
        "min": 53,
        "minAdded": null,
        "isBlocked": false,
        "isOnTarget": true,
        "blockedX": null,
        "blockedY": null,
        "goalCrossedY": 30.95,
        "goalCrossedZ": 0.1219999994,
        "expectedGoals": 0.3437691032886505,
        "expectedGoalsOnTarget": 0.6219,
        "shotType": "LeftFoot",
        "situation": "RegularPlay",
        "period": "SecondHalf",
        "isOwnGoal": false,
        "onGoalShot": {
          "x": 1.806878306878306,
          "y": 0.032275132116402115,
          "zoomRatio": 1
        },
        "firstName": "Roberto",
        "lastName": "Firmino",
        "teamColor": "#d3171e"
      },
      {
        "id": 2469870751,
        "eventType": "Miss",
        "teamId": 9825,
        "playerId": 207236,
        "playerName": "Granit Xhaka",
        "x": 95.3508786640393,
        "y": 47.5740127358,
        "min": 62,
        "minAdded": null,
        "isBlocked": false,
        "isOnTarget": false,
        "blockedX": null,
        "blockedY": null,
        "goalCrossedY": 37.50750000000001,
        "goalCrossedZ": 4.940965524800001,
        "expectedGoals": 0.07590201497077942,
        "expectedGoalsOnTarget": null,
        "shotType": "LeftFoot",
        "situation": "RegularPlay",
        "period": "SecondHalf",
        "isOwnGoal": false,
        "onGoalShot": {
          "x": 0.5192336956154144,
          "y": 0.6772486772486772,
          "zoomRatio": 0.518117357255518
        },
        "firstName": "Granit",
        "lastName": "Xhaka",
        "teamColor": "#bd0510"
      },
      {
        "id": 2469877825,
        "eventType": "AttemptSaved",
        "teamId": 9825,
        "playerId": 961995,
        "playerName": "Bukayo Saka",
        "x": 95.83333480453929,
        "y": 26.69,
        "min": 73,
        "minAdded": null,
        "isBlocked": false,
        "isOnTarget": true,
        "blockedX": 101.0172413796,
        "blockedY": 30.568749999999998,
        "goalCrossedY": 32.779999999999994,
        "goalCrossedZ": 0.0834736838,
        "expectedGoals": 0.20655393600463867,
        "expectedGoalsOnTarget": 0.087,
        "shotType": "RightFoot",
        "situation": "RegularPlay",
        "period": "SecondHalf",
        "isOwnGoal": false,
        "onGoalShot": {
          "x": 1.3227513227513243,
          "y": 0.02208298513227513,
          "zoomRatio": 1
        },
        "firstName": "Bukayo",
        "lastName": "Saka",
        "teamColor": "#bd0510"
      },
      {
        "id": 2469877879,
        "eventType": "AttemptSaved",
        "teamId": 9825,
        "playerId": 576165,
        "playerName": "Gabriel Jesus",
        "x": 99.3070175438,
        "y": 32.322499418258666,
        "min": 73,
        "minAdded": null,
        "isBlocked": false,
        "isOnTarget": true,
        "blockedX": 100.6379310348,
        "blockedY": 32.6275,
        "goalCrossedY": 34,
        "goalCrossedZ": 0.1219999994,
        "expectedGoals": 0.24015659093856812,
        "expectedGoalsOnTarget": 0.0781,
        "shotType": "RightFoot",
        "situation": "RegularPlay",
        "period": "SecondHalf",
        "isOwnGoal": false,
        "onGoalShot": {
          "x": 1,
          "y": 0.032275132116402115,
          "zoomRatio": 1
        },
        "firstName": "Gabriel",
        "lastName": "Jesus",
        "teamColor": "#bd0510"
      },
      {
        "id": 2469877907,
        "eventType": "AttemptSaved",
        "teamId": 9825,
        "playerId": 1021586,
        "playerName": "Gabriel Martinelli",
        "x": 81.80922502006557,
        "y": 43.230063154656435,
        "min": 73,
        "minAdded": null,
        "isBlocked": true,
        "isOnTarget": true,
        "blockedX": 88.1779411764,
        "blockedY": 41.3678125,
        "goalCrossedY": 34.38125,
        "goalCrossedZ": 1.2199999940000001,
        "expectedGoals": 0.0468883216381073,
        "expectedGoalsOnTarget": null,
        "shotType": "RightFoot",
        "situation": "RegularPlay",
        "period": "SecondHalf",
        "isOwnGoal": false,
        "onGoalShot": {
          "x": 0.8991402116402113,
          "y": 0.32275132116402117,
          "zoomRatio": 1
        },
        "firstName": "Gabriel",
        "lastName": "Martinelli",
        "teamColor": "#bd0510"
      },
      {
        "id": 2469880495,
        "eventType": "Goal",
        "teamId": 9825,
        "playerId": 961995,
        "playerName": "Bukayo Saka",
        "x": 94,
        "y": 34,
        "min": 76,
        "minAdded": null,
        "isBlocked": false,
        "isOnTarget": true,
        "blockedX": null,
        "blockedY": null,
        "goalCrossedY": 36.8975,
        "goalCrossedZ": 0.0834736838,
        "expectedGoals": 0.7884,
        "expectedGoalsOnTarget": 0.9941,
        "shotType": "LeftFoot",
        "situation": "Penalty",
        "period": "SecondHalf",
        "isOwnGoal": false,
        "onGoalShot": {
          "x": 0.23346560846560827,
          "y": 0.02208298513227513,
          "zoomRatio": 1
        },
        "firstName": "Bukayo",
        "lastName": "Saka",
        "teamColor": "#bd0510"
      },
      {
        "id": 2469897937,
        "eventType": "AttemptSaved",
        "teamId": 8650,
        "playerId": 156008,
        "playerName": "Jordan Henderson",
        "x": 87.21176798175176,
        "y": 43.10218661785126,
        "min": 90,
        "minAdded": 8,
        "isBlocked": true,
        "isOnTarget": true,
        "blockedX": 92.3,
        "blockedY": 39.881190477,
        "goalCrossedY": 30.72125,
        "goalCrossedZ": 1.2199999940000001,
        "expectedGoals": 0.07181116938591003,
        "expectedGoalsOnTarget": null,
        "shotType": "RightFoot",
        "situation": "RegularPlay",
        "period": "SecondHalf",
        "isOwnGoal": false,
        "onGoalShot": {
          "x": 1.8673941798941804,
          "y": 0.32275132116402117,
          "zoomRatio": 1
        },
        "firstName": "Jordan",
        "lastName": "Henderson",
        "teamColor": "#d3171e"
      },
      {
        "id": 2469897963,
        "eventType": "AttemptSaved",
        "teamId": 8650,
        "playerId": 963964,
        "playerName": "Harvey Elliott",
        "x": 81.24611822406555,
        "y": 40.80571556846489,
        "min": 90,
        "minAdded": 8,
        "isBlocked": true,
        "isOnTarget": true,
        "blockedX": 92.7,
        "blockedY": 37.732,
        "goalCrossedY": 34.533750000000005,
        "goalCrossedZ": 1.2199999940000001,
        "expectedGoals": 0.045770078897476196,
        "expectedGoalsOnTarget": null,
        "shotType": "LeftFoot",
        "situation": "RegularPlay",
        "period": "SecondHalf",
        "isOwnGoal": false,
        "onGoalShot": {
          "x": 0.8587962962962951,
          "y": 0.32275132116402117,
          "zoomRatio": 1
        },
        "firstName": "Harvey",
        "lastName": "Elliott",
        "teamColor": "#d3171e"
      }
    ]
  }
}
```

