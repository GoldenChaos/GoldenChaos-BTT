# GoldenChaos-BTT
A feature-rich BetterTouchTool preset that makes the MacBook Pro Touch Bar not suck

![Photo](https://github.com/GoldenChaos/GoldenChaos-BTT/blob/master/cool-photo.jpg?raw=true)

# [Download the latest version](https://github.com/GoldenChaos/GoldenChaos-BTT/raw/master/goldenchaos-btt.bttpresetcompressed)

## Screenshots
![Screenshot](https://github.com/GoldenChaos/GoldenChaos-BTT/blob/master/screenshot-1.png?raw=true)
<p align="center">Default set of keys</p>

![Screenshot](https://github.com/GoldenChaos/GoldenChaos-BTT/blob/master/screenshot-2.png?raw=true)
^Contextual buttons appear and disappear as you open/close corresponding apps</p>

![Screenshot](https://github.com/GoldenChaos/GoldenChaos-BTT/blob/master/screenshot-4.png?raw=true)
<p align="center">Critically, the esc/fullscreen key stays docked to the left at all times</p>

![Screenshot](https://github.com/GoldenChaos/GoldenChaos-BTT/blob/master/screenshot-3.png?raw=true)
<p align="center">Widgets for Reminders, Fantastical, Things 3, and more apps added on a regular basis</p>

![Screenshot](https://github.com/GoldenChaos/GoldenChaos-BTT/blob/master/screenshot-5.png?raw=true)
![Screenshot](https://github.com/GoldenChaos/GoldenChaos-BTT/blob/master/screenshot-6.png?raw=true)
<p align="center">Emoji and app switcher widgets take over the scrollable container</p>

![Screenshot](https://github.com/GoldenChaos/GoldenChaos-BTT/blob/master/screenshot-7.png?raw=true)
<p align="center">Hold down alt/option to expand the control strip</p>

## Supported apps:

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
- More to come...

## Features:

- Designed to *completely* replace the stock Touch Bar interface
- Fullscreen button doubles as esc key, *always* stays docked to the left
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

## Required Plugins:

- [High Sierra Media Key Enabler](http://milgra.com/high-sierra-media-key-enabler.html) with "Pause if no player is running" enabled for media controls
- [Location Helper](http://www.mousedown.net/mouseware/LocationHelper.html) and [JSON Helper](http://www.mousedown.net/mouseware/JSONHelper.html) for the weather widget
- [icalBuddy](http://hasseg.org/icalBuddy/) for the calendar widget

## Media Controls Configuration

[High Sierra Media Key Enabler](http://milgra.com/high-sierra-media-key-enabler.html) with "Pause if no player is running" enabled is strongly recommended. Appropriate media controls are displayed conditionally based on the following hierarchy:

1. iTunes
2. Spotify
3. Safari (YouTube)

If no media player is running, and Safari is open to a YouTube video, only the Play/Pause button will be shown. In any other case, all media controls are available.

## Calendar Widget Configuration

For the Calendar widget to work properly, it must first be edited to include the names of calendars you wish to display. Replace my personal defaults with yours, and make sure you've installed [icalBuddy](http://hasseg.org/icalBuddy/). You can also configure the widget to display events for additional days, for example for up to a week, by changing "eventsToday" to "eventsToday+7".

## Uses modified versions of a bunch of widgets from https://github.com/vas3k/btt-touchbar-presets and inspired by [this blog post](http://vas3k.com/blog/touchbar/). Make sure you're using the latest alpha version of BetterTouchTool before importing!
