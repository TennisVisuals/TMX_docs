---
title: Using Google Sheets
keywords: data management
sidebar: ch_sidebar
permalink: tmx_google_sheets.html
toc: true
---

## How it works...

Google provides a [Sheets API](https://developers.google.com/sheets/api/){:target="_ blank"} which enables applications to access and manipulate Google Sheets.  Given a valid URL (website link) and appropriate privileges, the CourtHive Cloud Server uses this API to pull data out of sheets and return data to TMX clients.  Data being returned to TMX is organized by [___Column Names___](tmx_google_sheets.html#accepted-column-names), which means that in order for data to be useable within TMX it must be recognized and mapped to appropriate attributes.

{% include important.html content="In order to use a google sheet as a source/repository for data you must first have a GMAIL account." %}

## Enabling Access

By default Google Sheets may only be viewed and edited by their creator or owner.  In order for the CourtHive Cloud Server to access the data in a Google Sheet, you must ___Share___ the sheet.

The first step to share a google sheet is to press the blue __Share__ button in the upper right hand corner of a sheet:

{% include image.html file="ch_sheet_share.png" alt="Share" caption="Share Button" %}

The easiest way to share a google sheet is to click __Generate Shareable Link__ in the dialogue that appears:

{% include image.html file="ch_sheet_link.png" alt="Generate Shareable Link" caption="" %}

{% include important.html content="By default Google will restrict sharing a link to other members of your G Suite (if you are a member of a G Suite)... It is important that before you copy the generated link you change the setting to 'Anyone with the link __can view__'" %}

{% include image.html file="ch_sheet_anyone.png" alt="Anyone can view" caption="" %}

{% include note.html content="Generating a link does not mean that your google sheet is public.  It cannot be found via search and can only be accessed by those who have the link. If you are uncomfortable with this method of sharing, it is possible to share the sheet _directly_ with the CourtHive server using a unique email address.  Contact <support@courthive.com> if you are interested in this option." %}

{% include image.html file="ch_sheet_sharing.png" alt="Sheet Sharing" caption="" %}

{% include tip.html content="Copy the sheet link and paste it into CourtHive/TMX wherever you see the link icon.  Sheets can be used for tournament players or for each team within a team tournament." %}

{% include image.html file="ch_tmx_edit_link.png" alt="Edit Link" caption="Edit Link" %}

## Accepted Column Names

Spreadsheet data can only be recognized by TMX if columns have appropriate headings.  The table below outlines accepted column names which enable data to be appropriately mapped as player attributes.

| Attribute  | Accepted Columns  | Description                  |
------------ | ----------------- | ---------------------------- |
| ID         | ID, UUID, Unique ID, Unique Identifier | Player Unique Identifier |
| Name       | Name              | Parsed into First/Last Names |
| Last Name  | Last, Last Name   | Player Last Name             |
| First Name | First, First Name | Player First Name            |
| Gender     | Gender, Sex       | Player Gender                |
| Profile    | Profile, UTR Profile, UTR Player Profile Link | Link to player on MyUTR.com |
| Email      | Email, E-Mail     | Player E-mail                |
| Phone      | Phone, Phone Number | Player Phone Number        |
| Location   | Location          | City and State               |
| Rank       | Rank, Ranking     | Player Ranking               |
| Rating     | Rating            | Player Rating                |
| Birthdate  | Birth, Birthdate, Birth Date, Date of Birth | Player's Birthdate |
| Country    | Country           | Full Country Name            |
| School     | School            | Player School Name           |
| School Abbreviation | School Code, School Abbr, School Abbreviation | Abbreviation for School |

{% include note.html content="Valid values for the __Gender__ column are 'Male, Female, M, W, Man, Woman'" %}
{% include note.html content="TMX recognizes column headers included in XLSX files that are generated by MyUTR.com" %}

## JotForm Example

[JotForm](https://www.jotform.com){:target="_ blank"} is a great way to automate the creation of Google Sheets which can serve as data stores for tournament registrations.

See the [JotForm Example](tmx_jotform.html) for step-by-step instructions.
