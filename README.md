# EggTimer2

### Installation

1. download zip of repo
2. unzip the folder
3. add folder to your `Alfred.alfredpreferences/workflows/` (you can find this folder by going to Alfred Preferences > "Advanced" tab > "Syncing" header > "Reveal in Finder" button )

### Basic Usage

The default keyword to use in Alfred is **timer**. In Alfred, set a timer with the following construction:

> **timer _MINUTES Your Reminder_**

For example:

> **timer 30 Game of Thrones time!**

And then, in 30 minutes time…

![](http://78.media.tumblr.com/d8a1b7a3e2a33d44ff78abdcfdb62d5a/tumblr_inline_mgjhkccWHa1qbs6wg.png)

…[Growl](http://t.umblr.com/redirect?z=http%3A%2F%2Fgrowl.info%2F&t=MGE5ZWM0NTU3ODk3YWZiYjM5ODFmM2ExNWE2NGM3ZjBjY2U4YWU2Nyw3azZSTUV2NA%3D%3D&b=t%3AQQrKy8i7VPCWevxKPiooBg&p=http%3A%2F%2Fgeekzone.philosophicalzombie.net%2Fpost%2F40086558091%2Feggtimer&m=1) pops up to tell you that it’s time for the [coolest-ever fictional dwarf](http://t.umblr.com/redirect?z=http%3A%2F%2Fgameofthrones.wikia.com%2Fwiki%2FTyrion_Lannister&t=NWI1ZThiZDMxNTk4M2FhZjljNTkxMzgwN2YzZjgyOWFmNDAzYjdkZSw3azZSTUV2NA%3D%3D&b=t%3AQQrKy8i7VPCWevxKPiooBg&p=http%3A%2F%2Fgeekzone.philosophicalzombie.net%2Fpost%2F40086558091%2Feggtimer&m=1) to start cutting people down to (his) size.

### Additional Features

Here is a very brief summary of some of the other things you can get EggTimer to do. For more detailed information, bring up the Help page by typing **timer help** into Alfred once it’s installed. (The Help page will load automatically the first time you run EggTimer.)

*   **timer** (with no additional parameters): Displays a list of currently running timers.
*   **timer every _MINUTES Your Reminder_**: Create an auto-repeating timer.
*   **timer kill**: Stop the last-completed auto-repeating timer.
*   **timer repeat _MINUTES_**: Repeat the last-completed timer. (Omit the **_MINUTES_** to use its previous duration.)
*   **timer snooze**: Repeat the last-completed timer for a preset duration. The default is 9 minutes.
*   **timer snooze _MINUTES_**: Set the snooze duration for future timers. (Omit the **_MINUTES_** to see the current value.)
*   **timer reset**: Cancel all running timers.
*   **timer about**: Shows basic info about EggTimer, including the version number.
