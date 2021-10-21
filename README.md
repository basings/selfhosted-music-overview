
# selfhosted-music-overview

selfhosted-music-overview intends to provide an overview of different self-hostable music streaming sites.

## Server Overview

| [Link](https://www.reddit.com/r/selfhosted/comments/pz9dpb/lets_make_a_definitive_guide_to_the_subtle/) | [Plex](https://github.com/plexinc/)                                  | [Emby](https://github.com/MediaBrowser/Emby)  | [Jellyfin](https://jellyfin.org/)                                                                                                      | [Navidrome](https://github.com/navidrome)                              | [Airsonic](https://airsonic.github.io/)      | [Subsonic](https://github.com/subsonic)      | [Funkwhale](https://funkwhale.audio/)     | [LMS](https://github.com/epoupon/lms)                                | [mStream](https://mstream.io/)                          | [Ampache](https://ampache.org/)                              | [Mopidy](https://docs.mopidy.com/) | [Koel](https://koel.dev/) | [MPD](https://www.musicpd.org/) | [Serviio](https://www.serviio.org/) | [Logitech Media Server](https://www.mysqueezebox.com/download)|
| ------------------------------------------------------------------------------------------------------- | ------------------------------------- | ----- | ------------------------------------------------------------------------------------------------------------- | -------------------------------------- | ------------- | ------------- | ------------- | ---------------------------------- | -------------------------------- | ------------------------------------ | ------ | ---- | --- | ------- | -------------------- |
| Open Source                                                                                             | No                                    | Sorta | Yes                                                                                                           | Yes                                    | Yes           | No            | Yes           | N/A                                | Yes                              | Yes                                  | N/A    | N/A  | N/A | N/A     | N/A                  |
| Internal Access                                                                                         | Yes, Paid                             | Yes   | Yes                                                                                                           | N/A                                    | N/A           | N/A           | N/A           | N/A                                | N/A                              | Yes                                  | N/A    | N/A  | N/A | N/A     | N/A                  |
| Scobble Plays                                                                                           | N/A                                   | N/A   | Yes, Plugin                                                                                                   | Yes                                    | N/A           | N/A           | N/A           | Yes                                | N/A                              | N/A                                  | N/A    | N/A  | N/A | N/A     | N/A                  |
| Can Read Tags                                                                                           | Yes                                   | N/A   | Yes                                                                                                           | Yes                                    | N/A           | N/A           | N/A           | Yes, Multi-Value                   | N/A                              | Yes                                  | N/A    | N/A  | N/A | N/A     | N/A                  |
| Can Write Tags                                                                                          | Yes                                   | N/A   | Yes                                                                                                           | No                                     | N/A           | N/A           | N/A           | Yes, Multi-Value                   | N/A                              | Yes, File or DB                      | N/A    | N/A  | N/A | N/A     | N/A                  |
| Subsonic API                                                                                            | No                                    | N/A   | No                                                                                                            | Yes                                    | N/A           | N/A           | Yes           | Yes                                | N/A                              | Yes                                  | N/A    | N/A  | N/A | N/A     | N/A                  |
| Can Share Music                                                                                         | Yes, Paid                             | N/A   | Yes                                                                                                           | Yes                                    | N/A           | N/A           | Yes           | N/A                                | Yes                              | N/A                                  | N/A    | N/A  | N/A | N/A     | N/A                  |
| Muli-User Support                                                                                       | Yes                                   | N/A   | Yes                                                                                                           | Yes                                    | N/A           | N/A           | N/A           | Yes                                | N/A                              | Yes                                  | N/A    | N/A  | N/A | N/A     | N/A                  |
| Muli-Library Support                                                                                    | Yes                                   | N/A   | Yes                                                                                                           | No, Future                             | N/A           | N/A           | N/A           | N/A                                | N/A                              | N/A                                  | N/A    | N/A  | N/A | N/A     | N/A                  |
| Smart Playlists                                                                                         | Yes                                   | N/A   | No                                                                                                            | No, Future                             | N/A           | N/A           | N/A           | Yes                                | No                               | Yes                                  | N/A    | N/A  | N/A | N/A     | N/A                  |
| Heart/Favorites                                                                                         | Yes                                   | N/A   | Yes                                                                                                           | Yes                                    | N/A           | N/A           | N/A           | Yes                                | N/A                              | Yes                                  | N/A    | N/A  | N/A | N/A     | N/A                  |
| 5 Star Rating                                                                                           | N/A                                   | N/A   | No                                                                                                            | Yes                                    | N/A           | N/A           | N/A           | N/A                                | Yes                              | Yes                                  | N/A    | N/A  | N/A | N/A     | N/A                  |
| Replay Gain                                                                                             | N/A                                   | N/A   | No                                                                                                            | Yes                                    | N/A           | N/A           | N/A           | N/A                                | Yes                              | N/A                                  | N/A    | N/A  | N/A | N/A     | N/A                  |
| Demo                                                                                                    | [Yes](https://app.plex.tv/desktop/#!/)| N/A   | [Yes](https://demo.jellyfin.org/stable/web/index.html#!/login.html?serverid=713dc3fe952b438fa70ed35e4ef0525a) | [Yes](https://www.navidrome.org/demo/) | N/A           | N/A           | N/A           | [Yes](https://lms.demo.poupon.io/) | [Yes](https://demo.mstream.io/?) | [Yes](https://ampache.org/demo.html) | N/A    | N/A  | N/A | N/A     | N/A                  |
| Transcode                                                                                               | N/A                                   | N/A   | Yes                                                                                                           | Yes                                    | N/A           | N/A           | N/A           | N/A                                | Yes                              | Yes                                  | N/A    | N/A  | N/A | N/A     | N/A                  |


## Client Overview

|                                 | Android | Android | Android                                                                                                                                                                              | Android    | Android                | Android   | Android | Android  | Android  | Web                                                                         |
| ------------------------------- | ------- | ------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | ---------------------- | --------- | ------- | -------- | -------- | --------------------------------------------------------------------------- |
|                                 | Gelli   | Finamp  | substreamer - Subsonic Client                                                                                                                                                        | Ultrasonic | Funkwhale for Android  | Subtracks | Dsub    | Audinaut | Subsonic | Navidrome                                                                   |
| Current Version                 |         |  0.5.1  |                                                                                                                                                                                      |   2.23.1   |                        |           | 5.5.2   |          |          | yes                                                                         |
| Album View                      |         |         | yes                                                                                                                                                                                  |   Yes      |                        |           |         |          |          | yes                                                                         |
| Song List                       |         |         | yes                                                                                                                                                                                  |   No       |                        |           |         |          |          | yes                                                                         |
| Folder View                     |         |         | yes                                                                                                                                                                                  |   No       |                        |           |         |          |          | no                                                                          |
| Artist View                     |         |         | yes                                                                                                                                                                                  |   Yes      |                        |           |         |          |          | yes                                                                         |
| Genre View                      |         |         |                                                                                                                                                                                      |   No       |                        |           |         |          |          | yes                                                                         |
| List by decade                  |         |         | yes                                                                                                                                                                                  |   No       |                        |           |         |          |          | no                                                                          |
| List by year                    |         |         | no                                                                                                                                                                                   |   Yes      |                        |           |         |          |          | yes                                                                         |
| Playlist Support                |         |         | yes                                                                                                                                                                                  |   Yes      |                        |           |         |          |          | yes                                                                         |
| Most Played Song                |         |         |                                                                                                                                                                                      |   No       |                        |           |         |          |          | yes                                                                         |
| Most Played Album               |         |         |                                                                                                                                                                                      |   Yes      |                        |           |         |          |          | yes                                                                         |
| Recently Played Song            |         |         |                                                                                                                                                                                      |   No       |                        |           |         |          |          | yes                                                                         |
| Recently Played Album           |         |         |                                                                                                                                                                                      |   Yes      |                        |           |         |          |          | yes                                                                         |
| Recently Added Song             |         |         |                                                                                                                                                                                      |   No       |                        |           |         |          |          | yes                                                                         |
| Recently Added Album            |         |         |                                                                                                                                                                                      |   Yes      |                        |           |         |          |          | yes                                                                         |
| Offline Mode                    |         |         | yes                                                                                                                                                                                  |    No      |                        |           |         |          |          | no                                                                          |
| Download Music                  |         |         | yes                                                                                                                                                                                  |   Yes      |                        |           |         |          |          | yes                                                                         |
| Podcasts                        |         |         | yes                                                                                                                                                                                  |            |                        |           |         |          |          | no                                                                          |
| Last.FM Scrobbling              |         |         | yes                                                                                                                                                                                  |     Yes    |                        |           |         |          |          | yes                                                                         |
| Similar Songs                   |         |         | yes                                                                                                                                                                                  |            |                        |           |         |          |          | no                                                                          |
| Show Top songs of an artist     |         |         | yes                                                                                                                                                                                  |            |                        |           |         |          |          | no                                                                          |
| Shuffle Play                    |         |         | yes                                                                                                                                                                                  |    Yes     |                        |           |         |          |          | yes                                                                         |
| Favourites / Starred / Bookmark |         |         | yes                                                                                                                                                                                  |    Yes     |                        |           |         |          |          | yes                                                                         |
| 5 Stars                         |         |         | no                                                                                                                                                                                   |    Yes     |                        |           |         |          |          | no                                                                          |
| Search function                 |         |         | yes                                                                                                                                                                                  |    Yes     |                        |           |         |          |          | yes                                                                         |
| Chromecast Support              |         |         |                                                                                                                                                                                      |    No      |                        |           |    Yes  |          |          |                                                                             |
| Android Auto                    |         |         |                                                                                                                                                                                      |    No      |                        |           |         |          |          |                                                                             |
| mp3                             |         |         | yes                                                                                                                                                                                  |     Yes    |                        |           |         |          |          | yes                                                                         |
| opus                            |         |         | yes                                                                                                                                                                                  |            |                        |           |         |          |          | yes                                                                         |
| flac                            |         |         | ?                                                                                                                                                                                    |     Yes    |                        |           |         |          |          | yes                                                                         |
| Dark Mode                       |         |         | yes                                                                                                                                                                                  |     Yes    |                        |           |         |          |          | yes                                                                         |
| Themeable                       |         |         | no                                                                                                                                                                                   |            |                        |           |         |          |          | yes                                                                         |
| License                         |         |         |                                                                                                                                                                                      |            |                        |           |         |          |          | GPL3                                                                        |
| Open Source                     |         |         | no                                                                                                                                                                                   |            |                        |           |         |          |          | yes                                                                         |
| Price Tag                       |         |         | free                                                                                                                                                                                 |            |                        |           |         |          |          | free                                                                        |
| Smart Recommendations           |         |         | yes                                                                                                                                                                                  |            |                        |           |         |          |          | no                                                                          |
| Link                            |         |         | [Substreamer](https://play.google.com/store/apps/details?id=com.ghenry22.substream2&hl=en&gl=US)                                                                                     |            |                        |           |         |          |          | [Navidrome](https://github.com/navidrome)                                   |


## How to Contribute

tba
