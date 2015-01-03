Shazify
=====================

Chrome extension used to sync your Shazam tags to a Spotify playlist.

[![ScreenShot](https://raw.githubusercontent.com/leeroybrun/chrome-shazify/master/promo_1400x560.png)](http://youtu.be/Zi1VRJqEI0Q)

## How it works

<p align="center"><a href="https://www.youtube.com/watch?v=Zi1VRJqEI0Q"><img src="https://raw.githubusercontent.com/leeroybrun/chrome-shazify/master/video_screenshot.png" alt=""/></a></p>

## Install

To install the extention, just go to the Chrome Webstore : https://chrome.google.com/webstore/detail/shazify/clhbpnpnaneankhiagfnjcegpccjkbib

## How to use

It will only works if you use the Shazam app for iOS or Android AND you are logged in with Facebook in the app.

If these conditions are met, Shazam will sync your tags with their MyShazam service (www.shazam.com/myshazam).

This extension will then parse the MyShazam website, get your tags, and add them to a new playlist created on your Spotify account.

How it works :

1. Install the extension
2. Click on the new icon appeared on your Chrome toolbar
3. You will be asked to login on MyShazam and Spotify
4. A new playlist ("My Shazam Tags") will be created on your Spotify account
5. Your Shazam tags will be listed and automatically added to this playlist

If a Shazam tag cannot be found on Spotify, you will have the possibility to change the search query for this track.

When you want to update your Spotify playlist with new tags, simply click on the Shazify icon on Chrome toolbar. It will then search for new tags on Shazam and add them to Spotify.

## Developers

### How to build

```
grunt build
```

### How to bundle

```
grunt bundle
```

## Roadmap for v0.2.5

- Custom update scripts, handle versions like 0.2.10

## Disclaimer

Shazify is not affiliated with Shazam Entertainment Limited.
"Shazam" and its logo are trademarks and registered trademarks of Shazam Entertainment Limited.
All other companies and product names are trademarks or registered trademarks of their respective companies.