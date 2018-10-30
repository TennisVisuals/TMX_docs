---
title: Tournament Information Tab
keywords: tournament information
sidebar: ch_sidebar
permalink: tmx_tournament_information.html
toc: true
---

## Introduction

Tournament Information is used primarily when printing/saving PDF Sign-in Sheets, Event Draws, and Tournament Schedules.  

Tournament __Start__ and __End__ dates determine the days on which events may be scheduled.

{% include image.html file="ch_challenge_edit.png" alt="Add Player" caption="Tournament Editing Mode" %}

Much of the information on the Tournament Tab only applies when [Publishing](tmx_publishing_overview.html) is enabled.

## Tournament Notes

{% include image.html file="ch_tournament_notes_edit.png" alt="Notes" caption="Edit Notes" %}

TMX provides a WYSIWYG editor for formatting notes which appear when tournaments are published to [CourtHive.com/Live](https://CourtHive.com/live/active). These notes are typically information from tournament organizers which can include directions, contact information and special notices.

{% include image.html file="ch_tournament_notes.png" alt="Notes" caption="Tournament Notes" %}

## Tournament Registration

{% include image.html file="ch_register.png" alt="Registration Link" caption="Registration Link" %}

If online registration is available for a tournament the website address can be added to the tournament record which will result in a "Registration" button appearing when the tournament is published to [CourtHive.com/Live](https://CourtHive.com/live/active).

{% include image.html file="live_register_button.png" alt="Registration Button" %}

## Social Media Links

{% include image.html file="ch_social.png" alt="Social Media" caption="Social Media" %}

Social media links which are unique to a tournament may be entered as a list of URLs.

{% include image.html file="live_social_media_links.png" alt="Social Media Links" %}

Any recognized websites will appear as icons when the tournament is published to [CourtHive.com/Live](https://CourtHive.com/live/active).

{% include image.html file="live_social_media_icons.png" alt="Social Media Icons" %}

## Saving Tournament Data

Tournament data is automatically saved locally as changes are made.  There are two options for backing up tournament data and sharing tournaments with others.

{% include image.html file="ch_tournaments_save.png" alt="Save Tournament" caption="Save Options" %}

The __UP__ arrow pushes the __Tournament Record__ to the [CourtHive Cloud Server](tmx_cloud_server.html) from which it may be retrieved by any other user who has the tournament in their calendar.

The __DOWN__ arrow exports the __Tournament Record__ in JSON format to the local file system.  This file may be imported into any CourtHive/TMX client by drag/dropping it into the Import/Expoert target area.

{% include image.html file="ch_tournaments_save_state.png" alt="Save State" caption="Save State" %}

The "Push" and "Export" icons change color to indicate whether changes have been made to the the local copy of the tournament since the tournament was last pushed or exported.

__Yellow__ indicates "Out of Date" and __Green__ indicates "Up to Date".

{% include note.html content='When Tournament Events are completed, Tournament Records are automatically "pushed" to the server.' %}
