# CricketScore-API


# API Usage
- features
    - All live matches
    - scores
    - wickets
    - overs
    - short commentry
    

### Request Format

#### GET: `https://cricket-score-api.herokuapp.com/`

```json
{
    "data": [
        {
            "match_type": "T20",
            "series_name": "Indian Premier League, 2018",
            "teams": "CSK vs KKR",
            "ground_name": "MA Chidambaram Stadium",
            "city": "Chennai",
            "country": "India",
            "match_state": "complete",
            "current_state": "Chennai won by 5 wkts",
            "toss_win_team": "Chennai",
            "decision": "Fielding",
            "start_date": "Apr 10 2018",
            "end_date": "Apr 10 2018",
            "KKR": {
                "runs": "202",
                "overs": "20",
                "wickets": "6"
            },
            "CSK": {
                "runs": "205",
                "overs": "19.5",
                "wickets": "5"
            }
        },
        {
            "match_type": "T20",
            "series_name": "Indian Premier League, 2018",
            "teams": "SRH vs RR",
            "ground_name": "Rajiv Gandhi International Stadium",
            "city": "Hyderabad",
            "country": "India",
            "match_state": "complete",
            "current_state": "Hyderabad won by 9 wkts",
            "toss_win_team": "Hyderabad",
            "decision": "Fielding",
            "start_date": "Apr 09 2018",
            "end_date": "Apr 09 2018",
            "RR": {
                "runs": "125",
                "overs": "20",
                "wickets": "9"
            },
            "SRH": {
                "runs": "127",
                "overs": "15.5",
                "wickets": "1"
            }
        }
    ]
}
```


# Contributing

- Data Fetch From [Cricbuzz](http://www.cricbuzz.com/) unofficialy.

- If the API is not working properly, please open a issue.
