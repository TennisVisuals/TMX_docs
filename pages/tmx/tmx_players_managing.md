---
title: Local Player Database
keywords: Tournament Players Database
sidebar: ch_sidebar
permalink: tmx_players_managing.html
toc: true
---

In normal use by organizations which have configured TMX to connect with existing tournament registration systems, the local player database exists primarily to facilitate the addition of players who sign in on site.

For individuals or clubs to construct tournaments independent of external tournament registration systems, using the local player database means that player information only needs to be entered once.

At present there is no ability to edit players which are imported, the assumption being that player data is maintained externally and imported/synchronized only to facilitate tournament creation.  

Administrators who have been granted access to [Data Storage Configuration](tmx_data_storage.html) have the option of maintaining a master player database in [Google Sheets](tmx_google_sheets.html).  This master database can be configured to synchronize with the Local Data for any organization Referee or Administrator.

### Remote Database Sync

If CourtHive/TMX is has been configured by an [Organization Key](tmx_configuration.html), the player database may be imported/synchronized by hovering the mouse over the __Player Count__ icon in the upper right corner and clicking on the Refresh icon that appears.

{% include image.html file="ch_players_refresh.png" alt="Players" caption="Refresh Players" %}

After synchronizing, the __Player Count__ will change to reflect the number of players in the database.

### Import from Tournament

Tournament Players may be added to the local database by clicking on the header to the __Player__ column in the [Players Tab](tmx_tournament_players.html)...

{% include image.html file="ch_player_column_header.png" alt="Player Column Header" caption="" %}

Which will present the following dialogue:

{% include image.html file="ch_add_tournament_players.png" alt="Add Tournament Players" caption="" %}

### Drag/Drop Import

For bulk loading of players when there is no remotely accessible player database, a __Spreadsheet Template__ has been provided.

This template, once populated, can be loaded from the file system, or dragged and "dropped" on the import target area, which is accessible by clicking on the __Import/Export__ icon from the Home Page.

The __Spreadsheet Template__ can be downloaded from the __Import/Export__ screen by clicking on the Spreadsheet Icon.

<div style='display: flex; flex-wrap: wrap;'>
<div style='padding-right: 1em;'>{% include image.html file="ch_import_export.png" alt="Import" caption="Import/Export" %}</div>
{% include image.html file="ch_import_template.png" alt="Import Template" caption="Template" %}
</div>

There are four tabs in the  __Spreadsheet Template.__  The "CourtHive" tab is blank, but must be present for the system to recognize the spreadsheet.  The other three tabs are optional and can be deleted depending on what type of data is being imported. For players it is important that Player IDs are unique.

### Manual Entry

A local player database can be constructed by entering players one at a time.

The __Add Player__ icon is accessible from the Home Page by clicking on the __Players Icon.__

<div style='display: flex; flex-wrap: wrap;'>
   <div style='padding-right: 1em;'> {% include image.html file="ch_players_icon.png" alt="Players" caption="Players Icon" %}</div>
   {% include image.html file="ch_players_add_icon.png" alt="Add Player" caption="Add Player" %}
</div>

Only the fields in __Yellow__ are required.

{% include image.html file="ch_players_add_form.png" alt="Player Information" caption="Basic Player Information" %}
