# Kiwi IRC Media Search

This plugin allows users to search different media providers directly from [Kiwi IRC]!

![Example](https://github.com/LouisT/KiwiIRC-MediaSearch/blob/master/assets/KiwiIRC-MediaSearch.gif)

#### Providers:
* 500px            - https://500px.com/settings/applications
* Instagram        - https://www.instagram.com/developer/
* Last.fm          - http://www.last.fm/api
* Mixcloud         - https://www.mixcloud.com/developers/
* SoundCloud       - http://soundcloud.com/you/apps
* Spotify          - https://developer.spotify.com/web-api/
* Stack Overflow   - https://api.stackexchange.com/docs
* Twitch           - https://github.com/justintv/Twitch-API
* Vimeo            - https://developer.vimeo.com/apps
* YouTube          - https://developers.google.com/youtube/v3/getting-started


Usage
-
Edit [mediasearch.html](mediasearch.html) and add the required API keys.
Place `mediasearch.html` in `/client/assets/plugins/` and edit `config.js` to include it in your plugins list.

```javascript
conf.client_plugins = [
    // "http://server.com/kiwi/plugins/myplugin.html",
    "/kiwi/assets/plugins/mediasearch.html",
    "/kiwi/assets/plugins/textstyle.html"
];
```

Note:
-
In order for all of the provider icons to display, we must use the latest version of [Font Awesome].
To do this, the plugin adds the [BootstrapCDN] version (provided by [MaxCDN]) with the following at the top of `mediasearch.html`.
```html
<!-- Use the latest version of Font Awesome! -->
<link rel="stylesheet" href="//maxcdn.bootstrapcdn.com/font-awesome/latest/css/font-awesome.min.css">
```

License
-
Copyright 2016 [Louis T.]

Code licensed under the MIT License: http://opensource.org/licenses/MIT

[Kiwi IRC]: https://kiwiirc.com/
[Font Awesome]: https://fortawesome.github.io/Font-Awesome/
[BootstrapCDN]: http://www.bootstrapcdn.com/#fontawesome_tab
[MaxCDN]: https://www.maxcdn.com/
[Louis T.]: https://ltdev.im/
