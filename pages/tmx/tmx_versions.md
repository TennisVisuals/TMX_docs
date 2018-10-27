---
title: Versions
keywords: Versions
sidebar: ch_sidebar
permalink: tmx_versions.html
toc: true
---
## Release cycle
* CourtHive/TMX is in continuous development with frequent releases.  
* The current "stable" version can always be found at [https://CourtHive.com/tmx](https://CourtHive.com/tmx).  
* If your organization hosts a version of CourtHive/TMX, the release cycle may be defined by the organization.

## Understanding the Version Number
The version number follows this pattern:  _Major.minor.added.changed.fixed_

* Every time a __minor__ release is made, _changed_ and _fixed_ are reset to zero.
* Every time a __major__ release is made, _added_, _changed_, and _fixed_ are reset to zero.
* There will be only 9 minor releases within each major release.

## Updating to the latest version
If your browser supports [Service Workers](https://caniuse.com/#feat=serviceworkers){:target="_ blank"}, then a version of CourtHive/TMX is cached locally.  When a new version is available, the Service Worker begins updating your cache after you refresh your browser. The Home and Menu icons turn __yellow__ to indicate that a new version is available.  

<div style='display: flex; flex-wrap: wrap;'>
<div style='padding-right: 1em;'>{% include image.html file="ch_home_update.png" alt="Update" caption="Update" %}
</div>
{% include image.html file="ch_menu_update.png" alt="Update" caption="Available" %}
</div>

Click on the Home/Menu icon and select __Messages__ from the menu.

{% include image.html file="ch_new_version.png" alt="Update" caption="" %}

{% include note.html content="To ___Force___ a version update: refresh your browser, wait a few minutes, then refresh again.  If you never refresh your browser after you load TMX then the Service Worker will not begin to cache the new version." %}

{% include note.html content="If your browser __does not__ support Service Workers then refreshing your browser will always load the current version, but you will not be able to load CourtHive/TMX when you are not connected to the internet." %}

{% include tip.html content="You can click on the Menu Icon at any time to check your version." %}

## Old and New Versions
* The __previous__ version of CourHive/TMX is available on: [https://CourtHive.com/tmx-](https://CourtHive.com/tmx-)
* The __next__ release candidate is available on [https://CourtHive.com/tmx+](https://CourtHive.com/tmx+)
* __Bleeding edge__ releases and urgent bug fixes are available on [https://CourtHive.com/tmx++](https://CourtHive.com/tmx++)
