---
layout: post
title: Warlock Core Features
tags: warlock design
---

It seems worthwhile to break out the core features of the Warlock app ahead of actually coding it together. The features listed below are all “integral” or 1.0 features that really demonstrate the usefulness of the tool— I can think of additional features over time, but the ones below capture how I envision using Warlock in a day-to-day environment.

##Core Concept
A hexcrawl roleplaying game generator and manager that removes the overhead placed on a Dungeon Master.

The success of generalized web-apps like [Roll20](https://roll20.net/) in this space demonstrates the value of making this an easy-to-access, online-only web application over a native app.

##Features

###Region Generator
Generates a hex map of a region seeded with adventure locations, plots and inter-connected variables.

###Seed-Saving
Seeds can be loaded into the generator, allowing one to create specific instances of hex crawls with certain hard-saved variables. This allows modularity and the sharing of “good seeds.”

###Hex Navigation
In-App, the DM is able to navigate a token or “view” through each hex, receiving information about what is contained in each hex and how it interacts with the overall plots and surrounding hexes. DMs can also enter in their own notes and X out or edit the variables in the hexes.

###Timeline/Plots Navigation
In a second tab, the DM receives a web-type/timeline-type view of the ongoing plots randomly generated through the generator. The DM can advance certain plots (or the timeline as a whole), which will provide visual tracking of where the parties are in the story. DMs can also edit the points on the timeline to change plots to their liking.

###Accounts System
DMs will be able to create accounts, allowing them to save their seeds and the progress/edits made to those seeds.
