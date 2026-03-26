# UX Journal Entry I
## Minesweeper
Minesweeper is a puzzle video game where the goal is to click on every tile that is not a mine. In the game flags can be used to indicate where the player thinks a mine is located. 

Minesweeper has historically been made for computers, however there have been numerous attempts of translating the game to a mobile friendly version. One limitation that arises while trying to port the game from computer to mobile is changing how the player can reveal a tile and how to place a flag to indicate a mine. On computer versions, revealing a tile is done with left clicking and placing a flag is done with a right click. This of course can not be replicated on mobile as there is only input available to the player, which is tapping on the screen. 

I am a minesweeper enthusiast and wanted to find a version that I could play on my phone that was as easily playable on a computer with a mouse. After trying many different mobile versions of minesweeper I came across Minesweeper Go, which solved the flagging vs revealing the tile issue very elegantly. Minesweeper Go's solution was to have two different modes available to the player which changed what tapping on a tile would do. In digging mode, indicated by a shovel icon, the player would reveal the tile, and in flagging mode the player would place a flag on the tile. To change the mode the player just has to tap the icon at the bottom of the screen, which immediately switches to the other mode. 

<video src="./assets/videos/demo.mov" controls width="600" height="400">
</video>

This solution demonstrates a very important heuristic in UX design known as **Visibility of System Status**. This heuristic states that the design of the product should always give information as to what is happening by giving feedback in a reasonable time. Minesweeper Go's solution demonstrates this principle perfectly because it always informs the player on what their current action will do, and when the player wants to switch the mode it immediately updates.

Another reason this solution works well is that the icon to change the mode offers a very important **Affordance** to indicate to the player that it is able to be interacted with. Affordances are characteristics of a technology that indicate what the technology does. One affordance that makes it clear to the player that the icon to switch the mode is able to be interacted with is that it looks similar to the tiles that the player is trying to clear. If the mode icon had been a flat texture then the player might think that it is just a logo.

[[Insert picture of mode icon]] [[Insert picture of tile icon]]
