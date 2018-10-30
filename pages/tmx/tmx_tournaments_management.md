---
title: Managing Tournaments
keywords: Tournament Calendar Management
sidebar: ch_sidebar
permalink: tmx_tournaments_management.html
toc: true
---

## Synchronizing Tournaments

When the [Search Box](tmx_searchbox.html) is in Tournaments Mode, the number of tournaments in the calendar is displayed on the far right of the navigation bar. (See [Using the Search Box](tmx_fundamentals.html) to learn how to change the Search Box Mode).

Hovering over the Tournament Count displays a __Refresh Icon__.  If CourtHive/TMX is configured to synchronize with an organization database, tournaments may be loaded from a remote server.

{% include image.html file="ch_tournaments_count.png" alt="Tournament Search" caption="Tournament Search Mode" %}

Clicking the refresh icon requests new tournaments which occur *after* the last entry in the local calendar.

["Context Clicking"](tmx_fundamentals.html) the refresh icon reloads the entire calendar from the server and adds any tournaments which may be missing from the local calendar.

## Manually Adding Tournaments

To the right of the Tournament Category Filter is an Add Tournament Icon.

{% include image.html file="ch_add_tournament_icon.png" alt="Add Tournament" caption="Add Tournament" %}

Clicking the Add Tournament Icon presents several options:

{% include image.html file="tmx_tournament_add_menu.png" alt="Add Tournament" caption="Add Tournament Options" %}

### New Tournament

Clicking the "New Tournament" option presents a dialogue for entering information that is required by the calendar.

Fields in __Yellow__ are required before a new tournament can be added.

__Tournament Type__ may be either *Standard* or *Dual Matches*.  For "Team Tournaments" select *Dual Matches*.  

{% include note.html content='Different options appear when editing tournaments depending on the tournament type.' %}

<div style='display: flex; flex-wrap: wrap;'>
   {% include image.html file="ch_add_tournament.png" alt="Add Tournament" %}
   {% include image.html file="ch_challenge.png" alt="Add Tournament" %}
</div>

Once new tournament information has been submitted the tournament appears in the calendar view (unless the tournament dates fall outside of the __Date Range__ defined by the __From:__ and __To:__ date selectors).

{% include image.html file="ch_challenge_calendar.png" alt="Tournament Added" %}

### Load by ID

Some organization keys allow tournaments to be pulled into TMX from a remote calendar.

{% include image.html file="tmx_tournament_id.png" alt="Tournament Added" %}

If your organization/federation maintains a database of tournaments on an existing server and this option is enabled, enter the tournament ID at the prompt.

{% include tip.html content="Tournaments retrieved by ID may fall out of the currently defined calendar date range.  If you don't see the tournament appear, check the __From:__ and __To:__ dates." %}

### Import Record

To import a JSON formatted tournament record that was previously exported, see [Importing Local Data](tmx_data_local.html#tournaments-and-players).

## Deleting and Editing Tournaments

Tournament information (such as a tournament name) may edited and tournaments may be deleted by ["Context Clicking"](tmx_fundamentals.html) on any tournament.  Clicking on the Date, Category, or Rank columns is the same as context clicking and allows these options to be accessed on __Touch Devices__.

{% include image.html file="ch_tournament_delete.png" alt="Delete Tournament" caption="Edit or Delete a Tournament" %}

Choosing to edit a tournament launches the same dialogue used to Add a New Tournament, with all of the values filled in.

{% include note.html content='In some configurations there is the option to "Merge" tournaments, which has the effect of combining lists of registered players.  This situation occurs because some organizations have different tournament IDs for Male/Female events.' %}
