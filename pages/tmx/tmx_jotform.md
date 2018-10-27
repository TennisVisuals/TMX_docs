---
title: JotForm Registration Page
keywords: data management registration
sidebar: ch_sidebar
permalink: tmx_jotform.html
toc: true
---

## Step 1: Create A Form

[JotForm](https://www.jotform.com){:target="_ blank"} accounts are free and registration data is seamlessly exported to [Google Sheets](tmx_google_sheets.html), which makes it easy to synchronize with CourtHive/TMX.

{% include image.html file="jotform_create_form.png" alt="Create" %}

Creating a form is a three part process: Building the form, Configuring Settings, and Publishing.

{% include image.html file="jotform_build.png" alt="Create" caption="" %}

Building a form is a simple process of _Dragging_ and _Dropping_ elements onto a canvas.

The examples below are a __Name__ and __Date__ elements; in this case the date element is used to capture a birth date.

<div style='display: flex; flex-wrap: wrap;'>
   <div style='padding-right: 1em;'>
   {% include image.html file="jotform_name_element.png" alt="Create" %}
   </div>
   {% include image.html file="jotform_date_element.png" alt="Create" %}
</div>

{% include tip.html content="Use a Date Picker element for birthdates to insure a consistent format." %}

{% include image.html file="jotform_datepicker.png" alt="Create" caption="" %}

When linked to a [Google Sheet](tmx_google_sheets.html) the title of each element becomes a column header. Please review the list of [Valid Column Headers](tmx_google_sheets.html#accepted-column-names) for pulling data into CourtHive/TMX.

An example tournament registration form can be found [here](https://form.jotformeu.com/CourtHive/tournament-registration){:target="_ blank"}

## Step 2: Share to Google Sheets

Once a form has been completed, click on the __Settings__ tab.

{% include image.html file="jotform_settings.png" alt="Create" caption="" %}

A menu will appear on the left.  Select __Integrations__ and then click on __Google Sheets__.

{% include image.html file="jotform_integrations_google.png" alt="Create" caption="" %}

### __Authenticate__  with GMAIL

{% include image.html file="jotform_authenticate.png" alt="Create" caption="" %}

### Ready to go!

{% include image.html file="jotform_integration_ready.png" alt="Create" caption="" %}

### ___Optional:___ Customize Form URL

{% include image.html file="jotform_direct_link.png" alt="Create" caption="" %}

## Step 3: Share sheet with TMX

Now you're just a few clicks away from being able to sync registered players with your tournament.  

Copy the link to the google sheet, open it in a new tab or window, and review the steps to [__Enable Access__](tmx_google_sheets.html#enabling-access).

## Step 4: Add Registration Link to your Tournament Page

{% include image.html file="jotform_publish.png" alt="Create" caption="" %}

Once you publish your form you will see a __Direct Link__ to your form.

{% include image.html file="jotform_copy_link.png" alt="Create" caption="" %}

### Return to TMX

In the __Tournament Tab__ you will see an icon for adding a registration link.

{% include image.html file="tmx_add_registration_link.png" alt="Create" caption="" %}

### Paste URL

Use Command-V (Mac) or Control-V (Windows) to paste the URL.

{% include image.html file="tmx_registration_link.png" alt="Create" caption="" %}

### View in Live

Next time you publish your tournament, the __Register__ button will appear beneath the tournament header.

{% include image.html file="tmx_live_register_button.png" alt="Create" caption="" %}
