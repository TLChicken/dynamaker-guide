<frontmatter>
header: header.md
siteNav: main-nav.md
footer: footer.md
</frontmatter>

<link rel="stylesheet" href="../generalStyle.css">

# Basic Controls


## Navigation

<br>

**<kbd>A</kbd> / <kbd>D</kbd> / Scroll Wheel** : Move Forwards / Backwards in song by 1 second. (The chart scrolls up or down.)

**<kbd>Shift</kbd> + <kbd>A</kbd> / <kbd>Shift</kbd> + <kbd>D</kbd>** : Move Forwards / Backwards in song by 0.01 seconds.


**<kbd>Q</kbd> / <kbd>E</kbd>** : Sets speed at which notes come down (equivalent to slider in the actual game that comes up when starting a song that sets the note speed. However, Dynamaker uses a different speed scale than Dynamix. Use 1.4x speed if you want to have a similar speed as 1.0x in Dynamix.)

**<kbd>W</kbd> / <kbd>S</kbd>** : Sets speed of song. 
- Default speed is 1.0 Speed
- Set it slower to make it easier to set the song's offset or align notes to the rhythm more easily.

_BUG in dynaremixv3: Do not press S anymore when speed is 0.1 or it could become 0.0 and crash the chart maker._
_If you encounter the bug and want to recover your chart, follow the steps in the Troubleshooting section here: [Troubleshooting](Placing%20Notes.html#Troubleshooting)_

**<kbd>O</kbd> / <kbd>P</kbd>** : Adjusts the offset of the song. <kbd>O</kbd> causes notes to come down later than before, and vice versa for <kbd>P</kbd>.

**<kbd>Enter</kbd>** : Goes into Play Mode and the song is played from the start with auto-play on, with Scores and Combo displayed.

**<kbd>R</kbd> / <kbd>M</kbd>** : Go to the beginning of the chart and plays it. (No Scores and Combo displayed.)

**<kbd>Space</kbd>** : Play / Pauses the song.



## Charting

### Mouse:

**Left Click**: When in placing down notes mode (Press **<kbd>1</kbd> / <kbd>2</kbd> / <kbd>3</kbd>** on top of keyboard) it will place down a note when you release your left click after clicking down. While holding down left click you can move the mouse left and right to adjust the size of the note. (Left for smaller, Right for bigger note.)

**Right Click** : Opens the [~~Right Click Menu~~](https://www.youtube.com/watch?v=dQw4w9WgXcQ). (Right Click Menu Section To be Added.)

### Keyboard:

**<kbd>↓</kbd> / <kbd>←</kbd> / <kbd>→</kbd>** : Turns on/off the note guidelines for the respective sides. 
- Press once to have it 50% transparent.
- Press second time to make it opaque.
- Press third time to turn off.



<kbd>↑</kbd> : Switches the Active Side in the order of:

	Main Side (Down) → Left Side → Right Side
	
The Active side is the side that you are editing. You use it to choose what side your notes get placed down on when left-clicking. While a certain side is active, the other 2 inactive sides will not be affected by anything you do on the active side. (Eg: Deleting Notes)


**<kbd>1</kbd> / <kbd>2</kbd> / <kbd>3</kbd>** : Selects Type of Note

|Number|Note Type|
|---|-----|
|1| Tap |
|2| Slide|
|3| Hold|



**<kbd>4</kbd>** : Go into **Edit** Mode

<h1 id="edit_mode">EDIT Mode</h1>

When you mouse over or near a note there will be a **White Square** on the middle of the note. Double click to select it and place it somewhere else.

You can select several notes at once by dragging left click such that the box formed overlays the notes. 

(Only notes in the current side that you are editing (The **Active Side**) will be selected. i.e. When editing left side and you draw a box in a area with both left and main side notes you are actually only selecting the notes that are on the left side. When you press **<kbd>Del</kbd>** only the left side notes in the white box will be deleted.)
After selecting those notes you can right click to **Delete** or copy them. ( *You can only copy the notes. You can't paste them as there is no paste function. :thynk:* )

**<kbd>Del</kbd>** : You can press this in **Edit Mode** after dragging left click to select notes, to delete those notes.

**<kbd>H</kbd>** : Hold down to bring up some Help text which describes some controls available at the bottom of the screen.


## Next:

**[Placing Notes]({{ baseUrl }}/Contents/Placing%20Notes.html)**


<h1 id="random_stuff">Things around the Note you are holding:</h1>

**White Line** : Graphically shows the column that your note will be placed in if you left click. This can be used to help you align your notes.

**Blue/Red/Yellow Line** : Graphically shows the row (Timing) that your note will be placed in if you left click. This helps you to align your notes in terms of timing. For example, if you are placing down notes on the Right side, there would also be such a line on the opposite side for you to help you to compare the timing of the notes on the right and the left side.

**Purple Line** : The timing of your note if placed on other sides of the chart. Similar to the **Blue/Red/Yellow Line**.

- Use this to judge the timing of the current note you are placing to the other notes coming down on different sides.


**Confusing Numbers Around the Note** : See Niche Stuff Section in [Placing Notes](Placing%20Notes.html#niche).

**Multi-Colour Squares at the Centre of some Notes**: See Multi-Colour Squares Section in [Placing Notes](Placing%20Notes.html#multi-colour).

[Back to Main Page](../mainPg.html)
