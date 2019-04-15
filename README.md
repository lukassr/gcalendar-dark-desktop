# GCalendar Dark: Google Calendar Destkop App with Dark Mode
[Google Calendar](https://calendar.google.com "Google Calendar") Desktop application for Windows, Mac and Linux with Dark Theme. Packaged with [Electron](https://electronjs.org/ "Electron").

***Last Update 15/04***

![GCalendar Dark](https://github.com/lukassr/gcalendar-dark-desktop/blob/master/media/screenshot.png)

***Observation:** The app is not finished yet. There are some assets with wrong colors, missing functionalities and improvements. I will accept PRs if you find an error and want to fix it* 

## Pre-release Downloads (v0.1.1)
[Download for macOS](https://github.com/lukassr/gcalendar-dark-desktop/releases/download/v0.1.1/GCalendar.Dark-0.1.1.dmg)

[Download for Windows](https://github.com/lukassr/gcalendar-dark-desktop/releases/download/v0.1.1/GCalendar.Dark.Setup.0.1.1.exe)

[Download for Linux](https://github.com/lukassr/gcalendar-dark-desktop/releases/download/v0.1.1/gcalendardark_0.1.1_amd64.deb)
## References
Special thanks to two developers who made almost all the effort. Honestly, I did a very little code here, except for some corrections of colors in the CSS.
- [Keep Desktop]( https://github.com/andrepolischuk/keep) by [andrepolischuck](https://github.com/andrepolischuk/)
- [CSS Style](https://github.com/pyxelr/Dark_Google_Calendar) by [pyxelr](https://github.com/pyxelr).

## Requirements
- npm

## Instructions
### Running the code for contributions:
```
npm install
npm start
```
### or if you want to build the app:
```
npm run dist:<OS>
```
Where `<OS>` can be `mac`, `win` or `linux`.


## Update log

### 15/04
- Remove bold style in month view
- Change min width window for better performance in shared fullscreen mode