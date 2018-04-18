# GoldenChaos-BTT
A full-featured BetterTouchTool preset that makes the MacBoo Pro Touch Bar not suck

![Photo](https://github.com/GoldenChaos/GoldenChaos-BTT/blob/master/cool-photo.jpg?raw=true)

![Screenshot](https://github.com/GoldenChaos/GoldenChaos-BTT/blob/master/screenshot-1.png?raw=true)
![Screenshot](https://github.com/GoldenChaos/GoldenChaos-BTT/blob/master/screenshot-2.png?raw=true)
![Screenshot](https://github.com/GoldenChaos/GoldenChaos-BTT/blob/master/screenshot-3.png?raw=true)
![Screenshot](https://github.com/GoldenChaos/GoldenChaos-BTT/blob/master/screenshot-4.png?raw=true)
![Screenshot](https://github.com/GoldenChaos/GoldenChaos-BTT/blob/master/screenshot-5.png?raw=true)

# [Download latest version (right click -> save as)](https://raw.githubusercontent.com/GoldenChaos/GoldenChaos-BTT/master/goldenchaos-btt.json)

### Supported apps:

- Finder
- Safari
- Chrome
- Firefox
- iTunes
- Spotify
- Reminders
- Things 3
- Carrot Weather
- Calendar
- Fantastical 2
- More to come...

### Nifty features:

- Fullscreen button also acts as esc key, stays docked to the left
- Emoji button toggles a scrollable emoji widget
- Date and Time widget toggles Fantastical 2 menu bar when pressed (uses Fantastical 2's default keyboard shortcut)
- Weather widget shows condition emoji + temperature in Fahrenheit, toggles Carrot menu bar when pressed (uses Carrot's default keyboard shortcut)
- Persistent Show Finder widget provides easy finder access
- Persistent Maximize Left, Center Window, and Maximize Right controls (with custom glyphs!) for window management
- Refresh button appears next to Forward and Back buttons if Safari, Chrome, or Firefox is open
- Media controls and iTunes/Spotify widgets appear only when iTunes or Spotify is running
- Now Playing widgets show currently playing song or "Paused" if iTunes/Spotify are not playing anything
- Due Today widget shows reminders from Reminders.app that are due today, overdue, or without a due date
- Reminders without a due date persist and automatically show the most recently added reminder
- Next Thing widget grabs your next reminder from Things 3
- Next Event widget uses icalBuddy to get just today's upcoming calendar events (requires extra configuration)
- Tap on any widget to open its parent app

Requires Location Helper, JSON Helper, and icalBuddy for the weather and calendar widgets to work properly.

### Calendar Widget Configuration

For the Calendar widget to work properly, it must first be edited to include the names of calendars you wish to display. Replace my personal defaults with yours, and make sure you've installed [icalBuddy](http://hasseg.org/icalBuddy/). You can also configure the widget to display events for additional days, for example for up to a week, by changing "eventsToday" to "eventsToday+7".

#### Uses modified versions of a bunch of widgets from https://github.com/vas3k/btt-touchbar-presets and inspired by [this blog post](http://vas3k.com/blog/touchbar/).
