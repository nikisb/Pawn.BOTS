Description:

This is the script for the pawnbots plugin. There is the possibility of installing an automatic hourly online.

Benefits:

Bots and players do not kick. Bots occupy slots. Bots have RP nicknames, random levels, color (cleist) and ping. Ability to add / remove bots from the game.

Installation:

Unzip Pawn.BOTS into your server folder, and edit server.cfg:

    Attach pawnbots to the end of all filterscripts.
    Plug pawnraknet.so and pawnbots.so at the end of all plugins.
    Make sure that the maxnpc value in server.cfg is not 0, you can simply set maxnpc 1. Connect #include immediately after #include <a_samp>, and compile the mod.

Setup:

The customization command from the .pbots game. Inside the scriptfiles / pawnbots folder there are 7 files:

    admin.inc - a list of nicknames that can use the settings from the game.
    color.inc - colors (cleats) for bots.
    lvl.inc - levels for bots.
    nick.inc - nicknames for bots.
    ping.inc - pings for bots.
    online.inc - setting up automatic hourly online bots (do not edit manually).
    setting.inc - settings (do not edit manually).

Notes:

The script uses the PawnRakNet plugin. There is no plugin for windows, and never will be. Hosts will either block you or require you to overpay for additional load, each bot creates a separate process.

Plugin author: urShadow
