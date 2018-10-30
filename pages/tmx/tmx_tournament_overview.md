---
title: Getting Started with Tournaments
keywords: tournament overview
sidebar: ch_sidebar
permalink: tmx_tournament_overview.html
toc: true
---

## Editing Tournaments

Before a tournament may be edited it must be present in the [Tournaments Calendar.](tmx_tournaments_navigation.html) Refer to the section on [Adding Tournaments](tmx_tournaments_management.html#manually-adding-tournaments) if there are no tournaments in the calendar.

{% include image.html file="ch_challenge_calendar.png" alt="Tournament Calendar" caption="Select a tournament from the calendar" %}

When a tournament is selected from the calendar a modal window displays the tournament information in read-only mode.

To edit a tournament you must be part of the same organization that created the tournament.  If this is the case, a __Pencil Icon__ appears in the upper right-hand corner.

{% include image.html file="ch_challenge_view.png" alt="Add Player" caption="Tournament Information" %}

Once in __Editing Mode__ other tabs and options become available, and the tournament information fields become editable.

{% include note.html content="Some functionality is not available until an __Organization Key__ has been entered." %}

{% include image.html file="ch_challenge_edit.png" alt="Add Player" caption="Tournament Editing Mode" %}

To exit __Editing Mode__, click on the __Check Mark__ in the upper right hand corner.

## Authorization

If TMX is enabled for publishing to CourtHive.com/Live then a small set of keys will appear top-center.  

<div style='display: flex; flex-wrap: wrap;'>
<div style='padding-right: 1em;'>{% include image.html file="ch_keys_unauth.png" alt="Unauthorized" caption="Unauthorized" %}
</div>
{% include image.html file="ch_keys_auth.png" alt="Authorized" caption="Authorized" %}
</div>

The color of the keys indicates whether the TMX is authorized for publishing.

If the an [Administrator Key](tmx_configuration.html) has been entered, clicking the keys icon will generate an authorization code which can be sent to a referee or tournament organizer.

Authorization keys can also be used by administrators to pre-publish [tournament notes](/tmx_tournament_information.html#tournament-notes), [registration information](tmx_tournament_information.html#tournament-registration), [social media links](tmx_tournament_information.html#social-media-links), and even event and draws in advance of passing on control to staff who will manage tournaments on-site.

When an authorization key is entered the corresponding tournament is automatically "pulled" from the CourtHive Cloud Server into the local TMX database.

## Cloud Fetch

If a tournament record has been "pushed to the [CourtHive Cloud Server.](tmx_cloud_server.html), clicking the "Cloud Fetch" icon will offer the option of "pulling" the tournament record into TMX, or "merging" any published events with the local tournament record.

{% include image.html file="ch_cloud_fetch.png" alt="Cloud Fetch" caption="Cloud Fetch" %}

"Cloud Fetch" capabilities make it possible to pass versions of a tournament between referees/organizers who may be present at different tournament venues.  The same capabilities underlie the ability of TMX to delegate entire tournaments to mobile devices so that referees can spent more time courtside.

### Download Tournament Record

When downloading a tournament record from the [CourtHive Cloud Server.](tmx_cloud_server.html) you are presented with a dialogue which includes a ___timestamp___ for when the record was pushed to the server.  

{% include image.html file="ch_cloudfetch_replace_tournament.png" alt="Replace Tournament" caption="Replace Tournament" %}

If no version of the current tournament has been pushed to the server, an error message is shown.

{% include image.html file="ch_cloudfetch_notfound.png" alt="Not Found" caption="Not Found" %}

The [Tournament Information](tmx_tournament_information.html) section describes how to push copies of a tournament to the  [CourtHive Cloud Server.](tmx_cloud_server.html)

### Merge Events

Tournament events are published independently.  In other words, tournament events may be published without a tournament record ever having been "pushed" to the [CourtHive Cloud Server.](tmx_cloud_server.html).  The ability to fetch published events means that the latest published version of events may be merged into a local copy of a tournament  which exists on an administrator computer, for instance.

{% include image.html file="tmx_merge_events.png" alt="Merge Events" %}

## Tournament Web Link

{% include image.html file="ch_web_link.png" alt="Tournament Link" caption="Tournament Link" %}

Click this icon to generate a QR Code which can be included with marketing materials related to a tournament.  The Tournament Web Link icon also copies a web address which can be included with emails or other social media.
