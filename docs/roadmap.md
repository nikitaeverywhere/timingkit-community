---
layout: page
title: Development Roadmap
permalink: /roadmap/
---

# [TimingKit](https://timingkit.tk){:target="_blank"} Development Roadmap

This document describes the current state of the [TimingKit service](https://timingkit.tk){:target="_blank"} development and the closest list of features to be implemented.
The most top-aligned items in the list below are the most prioritized to develop and are about to appear soon!
Want to change or propose something? Go to [describe your idea here](https://github.com/ZitRos/timingkit-community/issues){:target="_blank"}!

Development Roadmap
-------------------

+ Add ability to create/edit/delete calendars
+ Create a logical value for pivot table rows/columns (primarily for charts). Charts should draw on axes by logical value but not by index, which works only for some cases.
   + Some dimensions, like week number of the year may have, for example, Week 1 at the end of the year, which is correct, but leads to unexpected drawings while drawing charts due to Week 1 is being sorted to the beginning.
   + When many of the rows are empty and some groups are skipped due to no events appear in there, charts axes scales may be different and not consistent. This should also be an option.
+ Add ability to floor relative dates to month (also week, year) beginning
+ Add ability to sort values in the table by columns/rows
+ Add ability to format values in the table, introduce universal formatting language
+ Add a Bar Chart widget type

Development History
-------------------

+ [1/27/2017] Implement realtime event synchronization on the client (push synced events immediately)
+ [1/26/2017] Completely redesign Chronology page
+ [9/28/2017] Add a Line Chart widget type
+ [9/22/2017] Redefine the timeline in Chronology tab to always show the first column in -24 hours to the second one.
+ [8/29/2017] Parallel dashboard rendering, clustering.
+ [8/29/2017] Distinguish time zones for different users according to their browser setup. Add an option to fix the time zone for the specific dashboard.
+ [8/18/2017] Timeline page: a page for viewing, managing and recording time
    + [8/17/2017] Selecting and editing events
    + [8/15/2017] Scrollable timeline
    + [8/13/2017] Recording multiple events (basics)
+ [8/18/2017] Add Weekday dimension in addition to Day, Month and Year (by [Natalie](https://github.com/NatalieTr))
+ [8/16/2017] Add Week dimension in addition to Day, Month and Year (by [Natalie](https://github.com/NatalieTr))
+ [8/3/2017] Extend demo Work calendar with labels and add 2 more widgets to demonstrate them.
+ [8/2/2017] Set up Git pages on [community.timingkit.tk](http://community.timingkit.tk).
+ [8/2/2017] Add "overlapping events" option. Prioritize short events.
+ [8/2/2017] Ability to floor the relative dates to day beginning.
+ [8/1/2017] Apply new React Fiber.
+ [8/1/2017] Migrate to Zoho Mail.
+ [7/31/2017] Special calendar for unallocated time analysis.
+ [7/30/2017] Clarify what are the dimensions in widget editing mode for different widgets.
+ [7/30/2017] Enhance left menu with icons, design improvements.
+ [7/29/2017] Enhanced [TimingKit service demo](https://timingkit.tk/demo), now it has 3 dashboard with 13 widgets in total.
+ [7/28/2017] Created a Development Roadmap page.
