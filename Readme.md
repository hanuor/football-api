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



#### Sample request

```python

import requests

url = "https://football-api-by-futmetrics.p.rapidapi.com/api/data/get_match_stats"

payload = {"match_id": 3901022}
headers = {
	"content-type": "application/json",
	"X-RapidAPI-Key": "4c62d63354msh6a96ded3bb7cea5p13f8a8jsnb1ed659d1cb3",
	"X-RapidAPI-Host": "football-api-by-futmetrics.p.rapidapi.com"
}

response = requests.request("POST", url, json=payload, headers=headers)

print(response.text)
```


