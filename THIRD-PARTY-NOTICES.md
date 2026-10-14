# Third-party components

AniWatch uses the following. Their licences apply to those parts.

| Component | Licence | Used for |
|---|---|---|
| [.NET 8](https://github.com/dotnet/runtime) | MIT | the runtime |
| [LibVLC](https://www.videolan.org/vlc/libvlc.html) | LGPL 2.1 or later | playback |
| [LibVLCSharp](https://code.videolan.org/videolan/LibVLCSharp) | LGPL 2.1 or later | connecting the app to LibVLC |
| [SQLite](https://www.sqlite.org/) | Public domain | the library database (the copy built into Windows) |

LibVLC and LibVLCSharp are included unmodified, as separate libraries in the
`libvlc` folder and `LibVLCSharp*.dll`. Their source is available from
VideoLAN at the links above.

## Metadata

Details and artwork come from these services. None needs an account or a
key, and none endorses AniWatch.

- [AniList](https://anilist.co/) — through its public GraphQL API.
- [Jikan](https://jikan.moe/) — an unofficial API for
  [MyAnimeList](https://myanimelist.net/), used when AniList is unavailable and
  for episode titles.
- [ani.zip](https://ani.zip/) — episode titles, stills and synopses per
  season, with stills and episode data from [TheTVDB](https://thetvdb.com/).
- [Kitsu](https://kitsu.app/) — full-size posters and cover art.
