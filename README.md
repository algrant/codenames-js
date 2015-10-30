# codenames-js
Play codenames game with cellphones!


-----------

At least 2 devices.

User Experience

1. go to codenam.es
    - new room
        + go to page codename.es/random-set-of-words
    - join room
        + type in words
        + or select words ---> first word (if there's more than 10 games going on at once this will be hard...);
    - about
        + displays some stuff...
2. go to codenam.es/random-set-of-words
    - if room exists:
        + try to join room
    - else:
        + create this room
3. join a room:
    - set option dialogue
        + first device
            * number of teams
            * input clues
        + all devices
            * spymaster or player
            * team colour (optional)
            * room open for new connections / closed

4. once in room:
    - menu stuff:
    - options button:
        + view as spymaster/player
        + number of teams
        + team colour (optional)
        + room open for new connections / closed
        + input clues (?)
        + show text in both directions (?)
    - info button:
        + devices & player/style
        + boot connection (?)
        + multi-display
        + game rules
        + about
    - new game button:
        + pop-up (are you sure!) [yes, no, change settings]
    - current game board
        + 5x5 with words (or section if multi-display)
            * word unchecked (empty if user -- colours/assasin if spy-master)
            * word checked - show who it belongs to
    - stats
        + agents left for each team colour
        + team winning streaks
        + who's turn is it ( requires spymaster to input number )
        + inputs left ( requires spymaster to input clue )
    - timer:
