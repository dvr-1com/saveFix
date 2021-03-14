# saveFix
Workaround for freecol bug https://github.com/FreeCol/freecol/issues/63
Works for Linux.

Steps:
1. Save saveFix to your pc.
2. Make it executable
3. Run freecol with your save.fsg to get error
4. Take name of the user and name of the king from error
5. Run saveFix 
6. You will get save_fixed.fsg
7. Use save_fixed.fsg to start game

Example
./saveFix previousGame.fsg "user1" "Louis XIV"
