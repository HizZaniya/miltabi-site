---
title: Miltabi Privacy Policy
---

[日本語](../) | **English**

# Miltabi Privacy Policy

Effective date: November 2, 2026

This policy describes how Miltabi, a trip planning application for Windows ("the app"), handles your information.

## Information We Collect

The developer does not collect any personal information. The app does not send your information to the developer.

The app has no account registration, usage measurement (telemetry or analytics), advertising, automatic crash reporting, or automatic update checks.

## Network Communication

The app connects to the internet only in the two cases below. In both cases, as with any internet connection, the other party learns your IP address.

### The Concierge (Anthropic's Claude)

The concierge that plans your itinerary runs on Anthropic's Claude. When you ask it to plan an itinerary, the app gives Claude the following trip details:

- Trip conditions: origin, return point, dates, departure and return times, party size (the number of adults, children, and infants), budget, and whether to favor cost or time
- Places to go and things to do: name, kind, priority, place, souvenir items, and the date and time of events
- What was researched before, and discounts
- When replanning, the items you pinned, added, or edited, and the items you marked as fully booked (name, place, duration, cost, whether a reservation is needed, pitfalls, and so on)

The app does not give Claude the trip name, the memos, addresses, or official website URLs you wrote on items, reservation numbers, the packing list, or the booklet's cover photo.

You choose how to connect to Claude on the settings screen.

- API key: the app sends the trip details and your API key to Anthropic's API (<https://api.anthropic.com>). When you check the connection on the settings screen, it sends only the API key.
- Claude Code CLI: the app starts the Claude Code that you installed on this PC and signed in to, and passes it the trip details. Claude Code sends them to Anthropic. The app never reads or stores Claude Code's credentials. It starts Claude Code with the conversation set not to be saved.

The app does not connect to any other website for the concierge's research.

Information sent to Anthropic is governed by Anthropic's privacy policy and by your own agreement with Anthropic (the API terms or your subscription terms). You pay for Claude under that agreement. The developer does not receive what is sent to Anthropic.

### Maps (OpenFreeMap)

When the app shows a map, it fetches map data and font glyphs from OpenFreeMap (<https://tiles.openfreemap.org>). From the range of map data requested, OpenFreeMap can tell which area the map shows.

When you save an offline map, the app fetches the map data around the places in your itinerary from OpenFreeMap in one download. It sends the app's name and version with this download. It does not send the trip details or place names.

Information handled by OpenFreeMap is governed by OpenFreeMap's privacy policy.

## Data Stored on Your PC

The app stores the following on your PC. Apart from what is described under "Network Communication" above, none of it is sent anywhere.

- Trip data: the trip name, trip conditions, places to go and things to do, the itinerary, reservation states and reservation numbers, the packing list, and which pitfalls you confirmed
- The booklet's cover photo: the photo you chose, stored as is. If the photo file contains when or where it was taken, that is kept too
- Offline maps: the map data you saved
- Research results: opening hours, prices, how to reserve, and so on, as researched by the concierge, with their sources
- Settings: how to connect to Claude
- Screen state: the tab you last opened. WebView2, which displays the app's screen, may also temporarily keep data it used for display

When trip data is moved to a newer format, the file from before the move is kept in the same folder.

These are kept in the app's own folder inside your per-user application data folder in Windows. Deleting that folder deletes what the app has stored.

The API key is not written to any file; it is stored in Windows Credential Manager. You can delete it from the settings screen at any time.

The app does not create log files.

When you export the booklet as HTML or PDF, the app writes the file to the location you choose. The app never sends that file anywhere.

## Information the App Does Not Hold

The app has no fields for your or your companions' names or for family contacts. The booklet prints only blank fields for writing them in by hand. They are therefore never in the saved files, in what is given to Claude, or in exported booklets.

## Microsoft Components and the Store

The app uses Microsoft Edge WebView2 to display its window. If you got the app from the Microsoft Store, the Microsoft Store handles installation and updates. Information handled by WebView2 and the Microsoft Store is governed by the Microsoft Privacy Statement.

## Children's Information

The app gives Claude the number of children and infants as part of the party size. It does not collect children's names or other personal information.

## Changes to This Policy

If the app's behavior changes so that this policy no longer matches it, this page will be updated and the effective date revised.

## Contact

Questions about this policy can be sent to the following email address:

<hizzaniya@proton.me>
