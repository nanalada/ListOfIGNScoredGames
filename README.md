# ListOfIGNScoredGames

A JSON file containing games, their rating and date of release.
The list of games with acquired from Elbriga's [EveryVideoGameEver](https://github.com/Elbriga14/EveryVideoGameEver) database of games. Specifically a combination of PCGames.json, SteamGames.json and additional steam games acquired from the Steam API.

The ratings were then acquired by using regex to clean the names of games, and aiohttps + asyncio to scrape the reviews for the final review score.
