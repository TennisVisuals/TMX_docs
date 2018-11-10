---
title: Tournament Courts
keywords: tournament courts
sidebar: ch_sidebar
permalink: tmx_tournament_courts.html
toc: true
---

## Court Locations
Before any [Scheduling](tmx_tournament_schedule.html) can occur, __Court Locations__ must be defined.

Fields in __Yellow__ are required.

{% include image.html file="ch_courts_tab.png" alt="Add Location" caption="Add Court Location" %}

### Abbreviation
The __Abbreviation__ is used at the top of __Schedule__ columns to differentiate locations.

If only one court location is used, then __"Court"__ is appropriate.

### Court IDs

An (Optional) comma separated list of court identifiers.

By default courts are numbers sequentially: 1, 2, 3, 4...

Enter any comma or space delimited string to give each court a unique identifier: CC, A, B, 3, 7, 8

{% include tip.html content="Court IDs can be used to change the order of courts on the Schedule." %}

{% include note.html content="The [Schedule Tab](tmx_tournament_schedule.html) will appear after at least one court location is added and one tournament event has been created." %}

### Latitude / Longitude

In the future, Geolocation Services will be used in a number of ways by TMX.  

* Providing online maps to court locations for tournament participants
* Geofencing for Crowdsourced Live Scoring

Geo position may be defined by manually entering Latitude and Longitude coordinates, by pasting a link (website address) to a Google Map location, or by clicking the __Geo Location__ icon

{% include image.html file="tmx_geo_location.png" alt="Location" caption="Geo Location" %}
