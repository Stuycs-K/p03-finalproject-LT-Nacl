# Final Project Proposal

## Group Members:

Leo Titievsky
       
# Intentions:
I want to develop a tournemant/dual style simple FPS game, with support for local multiplayer and basic bots.
    
# Intended usage:

The users will interact through a menu with the keyboard, which will then place them into a keyboard and mouse controlled FPS game.
  
# Technical Details:

A server will host map events, even in local mode (the server will be run locally for singleplayer), necessitate ipc for singleplayer and sockets/networking for multiplayer.
Intercepting signals will be critical for proper control and closing. 
Memory allocation is key to the graphics system, underlying frame buffering. 

I'm doing all of it.
  
    
# Intended pacing:
FPS game core with command line GFX done prior to starting.
By 1/8/26, add menus and either SDL or a lightweight 'proper' frame buffer library for graphics.
By 1/10/26, Move 'backend' non graphical/input logic to a serverside process
By 1/12/26, revamp bots with A* and (potentially) modular behaviours
By 1/14/26, Setup a tournemant system and menu (with fewer players then needed, additional slots are filled with bots)
By 1/16/26, Polish, make maps, playtest
