# Anime Mappings
A simple API created by Quack.si

This public repository will be updated as frequently as new anime are fetched from Quack.si partners. Use of the Quack.si API may trigger for anime mappings to be updated. The quack.si is used across various Discord Bots and different projects, which we've heard is used to fetch new anime on the go.

This repository will link the following:
- AnimeSchedule.net
- AniList
- MyAnimeList
- 9Anime

The only content linked are only IDs/links that directly identifies the content. For 9Anime it'd be the link as 9Anime doesn't publicly allow a publicly accessible API. AnimeSchedule.net will use slugs (as use of IDs isn't shown in most endpoints), AniList & MAL will use anime IDs respectfully from their platform.
The repostitory will get updated as frequently as API requests are made. 

The anime mappings API is available directly at https://am.api.quack.si. The API is publicly available for everyone to access.
```json
{'animeName': 'name of anime',
'animeRomaji': 'name of anime but instead romaji title',
'malID': 1,
'anilistID': 1,
'9animeslug': '/nameofanime-ec3'
}
```
The format so far is nothing complex. Beware this may change as this API is in BETA stage.
