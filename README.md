# GoldenChaos-BTT
A complete replacement for the stock Touch Bar interface wrapped up in a nice BetterTouchTool preset

![Photo](https://github.com/GoldenChaos/GoldenChaos-BTT/blob/master/cool-photo.jpg?raw=true)

# [Download the latest version](https://github.com/GoldenChaos/GoldenChaos-BTT/raw/master/goldenchaos-btt.bttpresetcompressed?raw=true) or [view the preset page on share.folivora.ai](https://share.folivora.ai/sharedPreset/97da12ef-3e78-4a6a-a831-87e707f5e043)
Make sure you're using the latest alpha version of BetterTouchTool before importing.

## Screenshot tour
<p align="center"><sub>The default set of keys if nothing is open; Fullscreen button doubles as escape key and always stays docked to the left</sub></p>

![](https://github.com/GoldenChaos/GoldenChaos-BTT/blob/master/screenshot-1.png?raw=true)

<p align="center"><sub>Contextual buttons and widgets populate the scrollable container as you open and close corresponding apps; Tap on any widget to open its parent app</sub></p>

![](https://github.com/GoldenChaos/GoldenChaos-BTT/blob/master/screenshot-2.png?raw=true)
![](https://github.com/GoldenChaos/GoldenChaos-BTT/blob/master/screenshot-4.png?raw=true)
![](https://github.com/GoldenChaos/GoldenChaos-BTT/blob/master/screenshot-3.png?raw=true)

<p align="center"><sub>Emoji and app switcher widgets take over the scrollable container</sub></p>

![](https://github.com/GoldenChaos/GoldenChaos-BTT/blob/master/screenshot-5.png?raw=true)
![](https://github.com/GoldenChaos/GoldenChaos-BTT/blob/master/screenshot-6.png?raw=true)

<p align="center"><sub>Hold down alt/option for an expanded control strip</sub></p>

![](https://github.com/GoldenChaos/GoldenChaos-BTT/blob/master/screenshot-7.png?raw=true)

## Currently supported apps

- Finder
- Safari
- Chrome
- Firefox
- iTunes
- Spotify
- YouTube (in Safari and as a Fluid app)
- Reminders
- Things 3
- Carrot Weather
- Calendar
- Fantastical 2

## Full list of features

- Designed to *completely* replace the stock Touch Bar interface
- Fullscreen button doubles as esc key, always docked to the left
- Two finger slide on the Touch Bar to change volume
- Three finger slide on the Touch Bar to change brightness
- Hold down Volume Down button to mute
- Hold Option/Alt to expand the function strip
- Emoji button toggles scrollable emoji widget
- App Switcher button toggles scrollable app switcher widget
- Date and Time widget toggles Fantastical 2 menu bar when pressed (uses Fantastical 2's default keyboard shortcut)
- Weather widget shows condition emoji + temperature in Fahrenheit, toggles Carrot menu bar when pressed (uses Carrot's default keyboard shortcut)
- Persistent Show Finder button for easy Finder access
- Persistent Maximize Left, Center Window, and Maximize Right controls for window management
- Refresh button appears next to Forward and Back buttons if Safari, Chrome, or Firefox is open
- Media controls and iTunes/Spotify widgets appear only when iTunes or Spotify is running
- Now Playing widgets show currently playing track info (with album art for iTunes!) or "Paused" if iTunes/Spotify are paused
- Due Today widget shows reminders from Reminders.app that are due today, overdue, or without a due date
- Reminders without a due date persist and automatically show the most recently added reminder
- Next Thing widget grabs your next reminder from Things 3
- Next Event widget uses [icalBuddy](http://hasseg.org/icalBuddy/) to get just today's upcoming calendar events (requires extra configuration)
- Tap on any widget to open its parent app

## Required helper apps

- [High Sierra Media Key Enabler](http://milgra.com/high-sierra-media-key-enabler.html) with "Pause if no player is running" enabled for media controls
- [Location Helper](http://www.mousedown.net/mouseware/LocationHelper.html) and [JSON Helper](http://www.mousedown.net/mouseware/JSONHelper.html) for the weather widget
- [icalBuddy](http://hasseg.org/icalBuddy/) for the calendar widget

## Media controls configuration

[High Sierra Media Key Enabler](http://milgra.com/high-sierra-media-key-enabler.html) with "Pause if no player is running" enabled is strongly recommended. Appropriate media controls are displayed conditionally based on the following hierarchy:

1. iTunes
2. Spotify
3. Safari (YouTube)

If no media player is running, and Safari is open to a YouTube video, only the Play/Pause button will be shown. In any other case, all media controls are available.

## Calendar widget configuration

For the Calendar widget to work properly, it must first be edited to include the names of calendars you wish to display. Replace my personal defaults with yours, and make sure you've installed [icalBuddy](http://hasseg.org/icalBuddy/). You can also configure the widget to display events for additional days, for example for up to a week, by changing "eventsToday" to "eventsToday+7".

### Uses modified versions of a bunch of widgets from https://github.com/vas3k/btt-touchbar-presets and https://community.folivora.ai/c/setup-preset-sharing. Inspired by [this blog post](http://vas3k.com/blog/touchbar/).
