# Kiwi IRC Media Search

This plugin allows users to search different media providers directly from [Kiwi IRC]!

![Example](https://github.com/LouisT/KiwiIRC-MediaSearch/blob/master/assets/KiwiIRC-MediaSearch.gif)

#### Providers:
* 500px            - https://500px.com/settings/applications
* Coub             - https://coub.com/dev/docs/Coub+API/Overview
* DeviantArt       - https://www.deviantart.com/developers/
* Giphy            - https://github.com/Giphy/GiphyAPI
* Gfycat           - https://gfycat.com/api
* Imgur            - https://api.imgur.com/
* Instagram        - https://www.instagram.com/developer/
* Jamendo          - https://developer.jamendo.com/v3.0
* Last.fm          - http://www.last.fm/api
* Mixcloud         - https://www.mixcloud.com/developers/
* Pixabay          - https://pixabay.com/api/docs/
* SoundCloud       - http://soundcloud.com/you/apps
* Spotify          - https://developer.spotify.com/web-api/
* Stack Overflow   - https://api.stackexchange.com/docs
* Twitch           - https://github.com/justintv/Twitch-API
* Vimeo            - https://developer.vimeo.com/apps
* YouTube          - https://developers.google.com/youtube/v3/getting-started


Usage
-
Edit [MediaSearch/plugin.html](MediaSearch/plugin.html) and add the required API keys.
Place `MediaSearch` in `/client/assets/plugins/` and edit `config.js` to include it in your plugins list.

```javascript
conf.client_plugins = [
    // "http://server.com/kiwi/plugins/myplugin.html",
    "/kiwi/assets/plugins/MediaSearch/plugin.html",
    "/kiwi/assets/plugins/textstyle.html"
];
```

Note:
-
In order for all of the provider icons to display, we must use a custom font called 'MediaSearch'.

License
-
Copyright 2016 [Louis T.]

Code licensed under the MIT License: http://opensource.org/licenses/MIT / [LICENSE](LICENSE)

CSS licensed under the MIT License: http://opensource.org/licenses/MIT / [LICENSE](LICENSE)

Font licensed under the SIL OFL 1.1 License: https://scripts.sil.org/OFL / [FONT-LICENSE](FONT-LICENSE)

[Kiwi IRC]: https://kiwiirc.com/
[Louis T.]: https://ltdev.im/
