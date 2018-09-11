---
title: TMX Quick Start
keywords: Example Tutorial Quick Start
sidebar: ch_sidebar
permalink: tmx_quick_start.html
toc: true
---
## Overview

The purpose of this tutorial is to help you use TMX to build your first tournament draws as quickly as possible.

This tutorial includes the following:
- entering a configuration key to enable the retrieval of ranked players
- creating a tournament
- adding players to the tournament
- signing players into the tournament
- creating a tournament event
- approving players for a tournament event
- creating a draw for a tournament event

{% include important.html content="Your Browser __must__ cache the latest version of TMX for this Quickstart tutorial to function properly.  If you have previously loaded CourtHive/TMX you will need to refresh your browser!" %}

## Demonstration Video

This Screen recording captures all of the steps outlined in this Quick Start Tutorial.

{% unless site.output == "pdf" %}
   <iframe width="560" height="315" src="https://www.youtube.com/embed/6wkHX5HzVSk" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
{% endunless %}

## Enter a Configuration Key

CourtHive can be configured to import ranked ATP/WTA/ITF players directly into a Tournament.  

From the Home Page navigate to Key Entry by clicking on the Keys Icon

{% include image.html file="ch_keys.png" alt="Keys" caption="Keys" %}

Enter "players" in the [Configuration Key](tmx_configuration.html) dialogue and press the __Submit__ button.

{% include image.html file="ch_key_players.png" alt="ATP/WTA" caption="Configuration Key" %}

Nothing visible will happen when this key is entered, but the system will be configured with the appropriate parameters for retrieving rank lists for several player categories.

## Create a Tournament

From the Home Page navigate to the Tournaments Calendar by clicking on the Tournaments Icon

{% include image.html file="ch_tournaments.png" alt="Tournaments" caption="Tournaments" %}

The __Tournaments Calendar__ page displays tournaments within a date range, optionally filtered by category.  

To the right of the Category Filter is an __Add Tournament Icon__.

{% include image.html file="ch_add_tournament_icon.png" alt="Tournament Filters" caption="Tournament Filters" %}

Clicking the __Add Tournament Icon__ launches an Add Tournament dialogue.  

Fields in ___Yellow___ are required before a new tournament can be added.

<div style='display: flex; flex-wrap: wrap;'>
   {% include image.html file="ch_add_tournament.png" alt="Add Tournament" %}
   {% include image.html file="ch_challenge.png" alt="Add Tournament" %}
</div>

{% include important.html content="For this example we will be adding players ___without birthdates___, so select the Category __ALL__" %}

{% include image.html file="ch_challenge_calendar.png" alt="Tournament Added" %}

## Edit Tournament

Clicking on a tournament in the Tournaments Calendar will open a window which will initially display a Tournament Overview.  Notice in the upper right-hand corner there is a __Pencil Icon__.  

{% include image.html file="ch_challenge_modal.png" alt="Tournament" caption="Tournament Overview" %}

Click the __Pencil Icon__ to enter ___Editing Mode___.

{% include image.html file="ch_editing_mode.png" alt="Edit Mode" caption="Additional Tabs appear in Editing Mode" %}

## Add Players

The __Players Tab__ is where players can be added to a tournament and then signed-in to a tournament when they arrive on-site on the day when the tournament begins.

{% include image.html file="ch_players_tab.png" alt="Players Tab" caption="Tournament Players Tab" %}

Since we have configured TMX to retrieve _Ranked Players_ from a variety of sources, clicking the __Refresh__ icon on the far right will present the options available for player import.

{% include image.html file="ch_player_import.png" alt="Player Import" caption="Select Players to Import" %}

The ATP, WTA, and ITF buttons import players from current ranking lists published by the respective organizations.  The "Load Players" button allows you to import a spreadsheet of players using an __Excel XLSX__ file.  You can use the [TMX template](tmx_players_managing.html#dragdrop-import) or UTR Ratings Lists which can be generated [here... if you have an account](https://app.myutr.com/players/ratingslist){:target="_ blank"}.

For this tutorial, click on the __ATP__ option.

{% include image.html file="ch_atp_players.png" alt="ATP Players" caption="Ranked ATP Players" %}

## Sign-In Players

Before players can be added to Tournament Events, they must be Signed In.  Players can be signed in two ways: Using the Search Box at the top of the screen, or by __Clicking__ on a player's name.  

For the purposes of this tutorial, simply click on the first 8 players to sign them in to the tournament.

{% include note.html content="Signed-In Players appear at the __bottom__ of the page." %}

{% include image.html file="ch_atp_players_signed_in.png" alt="Signed In" caption="Signed In Players" %}

## Add an Event

Now you can switch to the __Events Tab__ by clicking the tab.

Add your first event by clicking the __Add Event__ button.  You will see the 8 players who are signed in as ___Eligible___ for the event, as long as they meet the criteria set by the _Gender_ and _Category_ filters.

{% include image.html file="ch_quick_start_event.png" alt="Tournament Event" caption="Adding a New Event to the tournament" %}

Players can be __approved__ for the event in _four_ ways:
- Clicking on a player's name
- Context Clicking on a players' name to approve as a wildcard
- Clicking the __+__ icon on the right side of the __Eligible__ area (adds all players)
- Searching for a player in the Searchbox (___only after the tournament has been saved___)

Once you have approved all 8 players, press __Save Event__ and then the __Automated Draw__ icon.

<div style='display: flex; flex-wrap: wrap;'>
   <div style='padding-right: 1em;'>
        {% include image.html file="ch_events_auto_play.png" alt="Play" %}
   </div>
   <div style='padding-bottom: 1em;'>
        {% include image.html file="ch_events_auto_pause.png" alt="Pause" %}
   </div>
</div>

Once the event is saved a __Draws Tab__ will appear.

If you have pressed the __Automated Draw__ icon, then a __Matches Tab__ will also appear.

{% include image.html file="ch_quick_start_auto_event.png" alt="Tournament Event" caption="Event Saved, Automated Draw" %}

## Viewing the Draw

Now you can switch to the __Draws Tab__ by clicking the tab.

{% include image.html file="ch_quick_start_draw.png" alt="Event Draw" caption="Elimination Event Draw" %}

You are now ready to [Add Scores](tmx_tournament_scoring.html) and Print PDFs.

You can create as many events as you wish: round robins, compass draws, staggered entry draws, doubles draws.  

You can also link qualification draws to main draws and consolation draws to main draws to see how players progress from event to event.  

You can also add WTA or ITF players to this tournament to create Female and Mixed Gender events.

___Have Fun!___
