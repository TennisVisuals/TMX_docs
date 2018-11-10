---
title: Tournament Teams Tab
keywords: tournament overview
sidebar: ch_sidebar
permalink: tmx_tournament_teams.html
toc: true
---

## Introduction

The Teams Tab appears when editing a __Team Tournament__ (Dual Matches).

{% include image.html file="tmx_teams_tab.png" alt="Teams" caption="Teams Tab" %}

There are several ways to Add a new team:
* __Create New__ by entering only a team name
* __Load Players__ using a [Player Spreadsheet](http://courthive.com/tmx/assets/CourtHiveImportTemplate.xlsx) from the local file system
* __Submit Key__ to retrieve a team list from the CourtHive Cloud Server

{% include image.html file="tmx_add_team.png" alt="Add Team" caption="Add Team" %}

If no name is supplied then a new team is created with a default name of __"New Team"__.

__"Load Players"__ is similar to [Adding Players to the tournament from spreadsheet files](tmx_tournament_players.html#adding-players-from-spreadsheet-files), except that players in a spreadsheet are added to the current team as well as to the tournament.

__"Submit Key"__ will load a team record which was previously shared to the CourtHive Cloud Server

{% include image.html file="tmx_team_detail.png" alt="Team Details" caption="Team Details" %}

## Editing Team Name

To edit a __Team Name__, click on the team name in the detail panel.  

When clicked the team name becomes editable (see above).  Modifying the name and pressing __Enter/Return__ accepts the change.

## Adding Team Players

### Using the Search Box

When editing a team, the [Search Box](tmx_searchbox.html) recognizes the context and changes mode to __"Add Team Player"__ so that searching for players adds them to the team.

{% include image.html file="tmx_add_team_player.png" alt="Add Team Player" caption="Add Team Player" %}

### Synchronizing Team Rosters

<div style='display: flex; flex-wrap: wrap;'>
<div style='padding-right: 1em;'>
{% include image.html file="tmx_url.png" alt="Link" caption="Link" %}
</div>
{% include image.html file="tmx_refresh.png" alt="Refresh" caption="Refresh" %}
</div>

Team Rosters may be managed using [Google Sheets](tmx_google_sheets.html), which makes it easy for team captains to make modifications from any device (laptops/mobiles).  

The __Refresh__ icon appears only after a link has been entered.

When a link is provided to a [Google Sheets](tmx_google_sheets.html), team players ___cannot___ be added any other way.

## Managing Team Players

### Changing Player Order

{% include image.html file="ch_rankings_icon.png" alt="Modify Rankings" caption="Toggle Edit Mode" %}

To change the order of players in a Team Roster, click the __"Modify Rankings"__ icon.  Once you are satisfied with the order, click the icon again and the players will be re-ordered.

{% include image.html file="tmx_team_player_order.png" alt="Player Order" caption="Edit Player Order" %}

Team order is used to determine the selection order when constructing matches in __Dual Events__.

{% include note.html content="The names of players who have not yet been signed appear faded." %}

### Deleting Players

Players may be deleted from a team by [Context Clicking](tmx_fundamentals.html) on their name.
