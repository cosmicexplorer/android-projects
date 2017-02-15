android-lectures-spring-2016
============================

# project ideas

- ideas have tentative names, summaries of functionality, expected major challenges, lists of people doing them, and links to their repos (after they're created)

## Friend Finder

### summary
- register other users as friends
- get locations of each user
- list friend locations
- register areas to send notifications to you when friends leave or enter that area

### devs
- arnav

### challenges
- to send notifs, need to obtain user's location in background
    - need backend to store locations
        - need to be able to query whether user is within some specified location / range to send notifs
    - need to use android location api, which is annoying to use
    - need to send notifs
- have mutual friend registration system
    - username?
    - qr code?
    - ensure people can unregister as friends whenever they want!

## Emoji Composer

### summary
- create images
- use created images as custom keyboard

### devs
- emily

### challenges
- need to create custom keyboard using images from app
- creating images with custom ui
    - mix-and-match with image resources in the app

## D&D DM Helper

### summary
- bunch of tools for d&d dms
    - support multiple games at once
- name generator for npcs
    - generates name based on race,gender,etc
    - searchable dictionary of npc names / traits / notes
- keep track of player characters' names / traits / notes
- searchable reference of d&d book
    - has magic items, races, etc
- tools for turn-by-turn actions (e.g. rolls)

### devs
- payton

### challenges
- keep lots of information in coherent ui
    - should be understandable
    - not so huge/complex as to be easy to forget
    - dictionaries for all characters / items / plot points introduced
    - support multiple games
- d&d book is copyrighted!
    - not a problem if we don't put on app store yet
    - is there an api for it?
