🌍[English](README.md) ∙ [Deutsch](README.de-DE.md) ∙ [Svenska](README.sv-SE.md)

# WeekNumber
Windows 11/10 system tray area application that displays the current week number

<img src="https://user-images.githubusercontent.com/2292809/120221521-d6a79580-c23e-11eb-99d1-be6210b43fcf.png" data-canonical-src="https://user-images.githubusercontent.com/2292809/120221521-d6a79580-c23e-11eb-99d1-be6210b43fcf.png" alt="WeekNumber" width="150" height="150" /> ![image](https://user-images.githubusercontent.com/2292809/120940539-0f071200-c71e-11eb-8b03-8f24b9fb36ad.png)


[![Latest release ZIP](https://img.shields.io/github/v/release/voltura/WeekNumber?label=download%20latest%20release&style=for-the-badge)](https://github.com/voltura/weeknumber/releases/latest/download/WeekNumber_v1.6.6.9.zip)

[![Github All Releases](https://img.shields.io/github/downloads/voltura/WeekNumber/total.svg)]()
[![License](https://img.shields.io/badge/licence-MIT-green)]()

## Features
Always see the current week number in the system tray area in Windows taskbar and lookup the week number for any other date via double-click on the application icon.

Options to start with Windows, customize icon colors, language, notifications, calendar rules and more. For details see _**Help section**_ below.

### Supported Languages
- English
- Deutsch
- Swedish

<sub>_If you want to contribute with another language, please create an Issue on Github and I'll contact you!_<sub>

## Screenshots
#### System tray area icon with default colors
![Taskbar icon](https://user-images.githubusercontent.com/2292809/120904782-473f1f80-c64e-11eb-9256-c3d0ddab2124.png)
#### Context menu - accessible via right-click on icon - with language selection
![Context menu](https://github.com/user-attachments/assets/53a8908f-0674-4563-b458-a13b93da5248)
#### Find out week number for any date
![Weeknumber form](https://github.com/user-attachments/assets/918860bb-9926-44c0-8363-84d3ecfed81f)

#### System tray area icon with customized colors
![Custom colors #1](https://user-images.githubusercontent.com/2292809/118048718-f4d74f80-b37c-11eb-8b36-211250ff25c5.png) ![Custom colors #2](https://user-images.githubusercontent.com/2292809/120920791-e997eb00-c6c0-11eb-889e-9a3e67787033.png) ![Custom colors #3](https://user-images.githubusercontent.com/2292809/120921288-498f9100-c6c3-11eb-8451-d2c3e19fba30.png)
#### Icon color picker, possible to define and use custom colors; both icon text and background can be customized
![Color picker](https://user-images.githubusercontent.com/2292809/118050315-4e407e00-b37f-11eb-8ac9-17cc1a08aa08.png)

## Installation
After download of WeekNumber_v1.6.6.9.zip via [*Download latest release*](https://github.com/voltura/weeknumber/releases/latest/download/WeekNumber_v1.6.6.9.zip) first unzip the archive, then run WeekNumber.exe.
To remove the application just delete the executable and other files extracted from the zip archive and the generated application configuration file WeekNumber.exe.config.

### Download notes
Choose to keep the file downloaded if prompted - it will look similar to this (depends on your web browser and settings)

![Keep file if prompted #1](https://user-images.githubusercontent.com/2292809/120716901-fa7d0c80-c4c6-11eb-9232-f279f959f0a6.png)


### Security notes / alternative lightweight version
Microsoft Defender / Windows Security could identify application as a virus, trojan and/or malware which is *not* the case.
I have created a lightweight version that does not trigger any false alarm, this version only can display the current week number in the task area, nothing else.
Not autostart with Windows (it can manually be made to start with Windows - google how).
Nor do the lightweight version have options to change icon colors or anything else that the full version of WeekNumber can do.

See more [here](https://voltura.github.io/WeekNumberLite2/) if interested.

## Help section
All application features are accessible via right-click on the application icon residing in the system tray area in Windows taskbar.
If the application icon is not visible then press the ^ symbol on the system tray area, click and hold on the application icon and then drag it to the visible system tray area to pin it there.

### Context menu options:
- **About WeekNumber** - _Displays version information_
- **Settings**
   - **Start with Windows** - _If ticked, the application starts automatically with Windows_
   - **Language** - _Change language used by the application_
     - **English**
     - **Deutsch**
     - **Svenska** - _Swedish_
   - **Application log**
      - **Use application log** - _Application writes to a log file if ticked_
      - **Show application log** - _If above is ticked, opens the application log file in a text editor; quite technical_
   - **Notifications** - _Control the application notification messages in sub-menus_
      - **Display startup notification** - _If ticked, the application will show a notification when started_

      <img src="https://user-images.githubusercontent.com/2292809/120921660-0b936c80-c6c5-11eb-974b-653954fca5ed.png" width="400">

      - **Display new week notification** - _If ticked, a notification will be shown when the week changes_

      <img src="https://user-images.githubusercontent.com/2292809/120921898-6da0a180-c6c6-11eb-82f0-4827dfbc2f4c.png" width="400">

      - **Use silent notifications** - _If ticked, any notifications for this application will not trigger system sounds to be played_
   - **Use small / large taskbar buttons** - _Toogles Windows taskbar size and also adjusts the application icon resolution to match. Having trouble seeing the week number? Try using large taskbar buttons_
   - **Export settings...** - _Option to export / backup the current application settings_
   - **Import settings...** - _Option to import previously exported / backed up application settings_
   - **Calendar** - _Calendar rules used by the application; per default the application uses the systems regional settings to figure this out, but it can be manually overridden here_
     - **First Day Of Week** - _Calendar rule, select what day a week starts on_
     - **Calendar week rule** - _Additional calendar rule that tells what rule is used for the first week of a year_
   - **Icon** - _Application icon settings_
     - **Icon colors** - _Allows user to change icon background and foreground color or reset colors used back to default in sub-menus_
     - **Icon resolution** - _Possibility to tweak the WeekNumber icon resolution, if the icon is fuzzy setting a higher or lower resolution can help with apperance_
     - **Graphics settings** - _Possibility to tweak icon graphics settings used by the application when drawing the week number icon_
       - **Smoothing mode**
       - **Compositing Quality**
       - **Interpolation Mode**
       - **Text Contrast**
     - **Save icon...** - _Saves the current WeekNumber icon displayed to a .ico file_
- **Get week number for date...** - _Get week number for specified date_

  <img src="https://user-images.githubusercontent.com/2292809/120942749-3a442e00-c72b-11eb-8b16-88fcbfe756f1.png" width="400">
- **Exit WeekNumber** - _Closes the application. Start it again from the Windows Start Menu_

## Donations
*- WeekNumber is completely free and open source. Donations are very much appreciated!*

[![Donate](https://img.shields.io/badge/donate_via-paypal_or_card-blue)](https://www.paypal.com/donate?hosted_button_id=7PN65YXN64DBG) __⟵__ _**Press here to donate!**_

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/G2G74W5F8) __⟵__ _**Press here to buy me a coffee!**_

## Statistics
[![Open issues](https://img.shields.io/github/issues/voltura/WeekNumber)](https://github.com/voltura/WeekNumber/issues)
[![Code Quality](https://img.shields.io/github/workflow/status/voltura/WeekNumber/CodeQL)]()
[![Website Status](https://img.shields.io/website?url=https%3A%2F%2Fvoltura.github.io%2FWeekNumber%2F)]()

[![Number of programming langauges](https://img.shields.io/github/languages/count/voltura/WeekNumber)]()
[![Top programming language](https://img.shields.io/github/languages/top/voltura/WeekNumber)]()
[![Code size](https://img.shields.io/github/languages/code-size/voltura/WeekNumber)]()
[![Number of repo forks](https://img.shields.io/github/forks/voltura/WeekNumber)]()
[![Number of repo stars](https://img.shields.io/github/stars/voltura/WeekNumber)]()
[![goto counter](https://img.shields.io/github/search/voltura/WeekNumber/goto)]()
[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fvoltura%2FWeekNumber%2Fhit-counter&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)]()
![GitHub last commit](https://img.shields.io/github/last-commit/voltura/WeekNumber?color=red)

![Visitors](https://estruyf-github.azurewebsites.net/api/VisitorHit?user=volturaf&repo=WeekNumber&countColorcountColor&countColor=%235690f2)
