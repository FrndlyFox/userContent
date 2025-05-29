# Installation

0. setup userContent.css
1. `git clone git@github.com:FrndlyFox/userContent.git` somewhere
2. import needed styles in userContent.css
3. toggle features in about:config

## Example

### directory structure

```
chrome
├ userContent
│ ├ global.css
│ └ youtube.css
├ userChrome.css
└ userContent.css
```

### userContent.css

```
@import url("userContent/global.css");
@import url("userContent/youtube.css");
```

# Features

## global

hides google login popup everywhere

## youtube

- `youtube.unpink` replace many pink gradients like in header icon, progressbars etc with pure red
- `youtube.shorts.hide` completely hide any shorts in feeds, search, channels + shorts buttons in the side menu
- `youtube.sidemenu.cleanup` hide "Explore" and "More from YouTube" sections and footer from the the side menu
- `youtube.feed.cleanup` hide minigames, surveys, "latest posts" from feed
- `youtube.thumbnail.cleanup` hide live avatar and paid content popup on video thumbnails
- `youtube.player.cleanup` hide paid content popup and "Clip" and "Thanks" buttons in the video player
- `youtube.player.theater.pretty` add round corners and margins to the theater player
- `youtube.header.cleanup` hide voice search button in the header
- `youtube.gay` gay
