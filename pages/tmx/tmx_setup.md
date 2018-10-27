---
title: CourtHive/TMX Setup
keywords: Installation, Setup
sidebar: ch_sidebar
permalink: tmx_setup.html
toc: true
---
## Configure Your Browser

CourtHive/TMX is implemented as a [Progressive Web App](https://en.wikipedia.org/wiki/Progressive_Web_Apps){:target="_ blank"}, which means that after it is opened in your browser for the first time, it can be launched even when the internet is disconnected... provided that your browser supports [Service Workers](https://caniuse.com/#feat=serviceworkers).  

{% include tip.html content="Create a bookmark to [CourtHive.com/tmx](https://CourtHive.com/tmx) to launch the application when you are offline." %}

Some browsers, such as Firefox, disable Service Workers when cookies are disabled.  To use all of the features of CourtHive/TMX you should allow cookies (even thought CourtHive/TMX doesn't make use of cookies).

{% include important.html content="For full offline support, allow cookies for Courthive.com" %}

## Check Your Default Settings

From the Home Screen, click on the settings icon to configure your preferences.  

{% include image.html file="ch_settings_icon.png" alt="Settings" caption="Settings" %}

{% include image.html file="ch_settings_tabs.png" alt="Tabs" caption="Settings Tabs" %}

If you have been given a [Configuration Key](tmx_configuration.html) some settings may have been configured for you and may be unavailable (such as Organization).

{% include image.html file="ch_settings_logos.png" alt="General" caption="Organization Settings" %}

__Logos:__ If you haven't entered an Organization Key then you have the opportunity to upload logos which will appear at the top of Player Lists, Draw Sheets and Schedules.  

{% include image.html file="ch_settings_general.png" alt="General" caption="General Settings" %}

__Week Starts Monday:__ Changes the behavior of pop-up calendars which enable date selection for tournaments and players
__Documentation Links:__ Enables context-sensitive documentation links throughout CourtHive/TMX

{% include image.html file="ch_settings_search.png" alt="Search" caption="Search Settings" %}

__Last Name, First Name:__ Reverse the default order when typing names
__Diacritics:__ Search using Diacritics (accents above/below characters)

{% include image.html file="ch_settings_draws1.png" alt="Draws" caption="Draws Settings" %}

__Compressed Draw Formats:__ Whether to allow 12, 24, 48 draw sizes
__Automatic Bye Placement:__ De-select if you want to place Byes manually
__Fixed Bye Order:__ Do not place byes strictly by seeding (configurable by keys)
__Auto Separate Players By Country:__ In automating draw creation
__Auto Separate Players By Club:__ In automating draw creation
__Auto Separate Players By School:__ In automating draw creation

{% include image.html file="ch_settings_draws2.png" alt="Draws" caption="Draws Settings" %}

__LL from All Qualifying Rounds:__ Include losers from all rounds on LL sign up sheet
__Qualifying Consolation:__ Enable consolation draws to be created directly from qualification draws
__Consolation Alternates:__ Enable players to be added into a consolation draw even if they didn't lose in a main draw
__Consolation Seeding:__ Seed players in Consolation Events (by GEM scores if configured by organization key)
__Restrict Seed Placement:__ Place seeds according to defaults or organization key settings.  Unchecking this option enables seeds to be placed freely throughout a draw (to support the replication of irregular draws).

__Country Flags Displayed:__ Display country flags alongside player names in online draws
__Match Times:__ Display match times to be displayed in online and PDF draws
__Match Dates:__ Display match dates to be displayed in online and PDF draws
__Court Details:__ Display scheduled court in online and PDF draws
__Matches Before Count:__ Display the number of incomplete matches on court prior to a given match

{% include image.html file="ch_settings_publishing.png" alt="Draws" caption="Publishing Settings" %}

__Require Confirmation:__ Do not publish without confirmation
__Publish when score entered:__ Immediate publishing to CourtHive/Live as scores are entered
__Publish as draw created:__ Publish a draw in real-time as players are placed

{% include image.html file="ch_settings_printing.png" alt="Draws" caption="Printing Settings" %}

__Save PDFs:__ Save PDFs immediately instead of opening in a new browser tab.  This is useful if your browser is blocking pop-ups and you don't know how to enable pop-ups.

{% include image.html file="ch_settings_schedule.png" alt="Draws" caption="Schedule Settings" %}

__Scores in Draw Order:__ As opposed to ___Winner Score First___
__Schedule Completed Matches:__ Show completed matches in ___Search___ when pulling matches into schedule cells

## Custom Settings

[Configuration Keys](tmx_configuration.html), which may include Organization Keys and Custom Keys are able to enable  aspects of CourtHive/TMX which are not available in the Settings dialogues.  If you have specific requirements please email <support@courthive.com> to see if the features you require are already available and can be enabled.
