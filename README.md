# Spotify <-> YouTube Playlist Converter
A simple python script to convert playlists from spotify to youtube (TODO: and vice versa) using the [Youtube Data API v3](https://developers.google.com/youtube/v3/) and the [Spotify Web API](https://developer.spotify.com/documentation/web-api/).
Inspired by [SpotifyGeneratePlaylist](https://github.com/TheComeUpCode/SpotifyGeneratePlaylist).

## Usage
### Spotify to Youtube
- Generate Spotify OAuth Token and paste into a file called `secrets.py` 
- Enable Oauth For Youtube and download the `client_secret.json`
- Get a Spotify Playlist's URI (*Share* > *Copy Spotify URI*)
- Run `python convert_playlist.py spotify:playlist:<uri>`
- Click on displayed link to get authorization code

### Youtube to Spotify
TODO
