# Installation

0. setup userContent.css
1. `git clone git@github.com:FrndlyFox/userContent.git` somewhere
2. import styles in userContent.css
3. toggle features in about:config

### Example

##### directory structure

```
chrome
├ userContent
│ ├ global.css
│ └ youtube.css
├ userChrome.css
└ userContent.css
```

##### userContent.css

```
@import url("userContent/global.css");
@import url("userContent/youtube.css");
```

# Switches

## youtube

- `youtube.unpink`
- `youtube.shorts.hide`
- `youtube.sidemenu.cleanup`
- `youtube.feed.cleanup`
- `youtube.thumbnail.cleanup`
- `youtube.player.cleanup`
- `youtube.player.theater.cleanup`
- `youtube.header.cleanup`
- `youtube.gay`
