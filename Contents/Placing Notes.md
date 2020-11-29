
# Placing Down Some Notes!

Press **1** to select *Tap Notes*, then **Left Click** to place down the note at where your mouse is at. 

While placing notes down, hold down **Left Click** to adjust the size of the note.
To delete notes, press **4** to go into **Edit Mode**, then drag **Left Click** over the notes that you want to delete to select them, then press **Del** or use the **Right Click** menu to delete them.
Note that only notes in the side that yo are editing (the **Active Side**) will be selected and deleted.


Press **2** to place down *Slide notes*, the same way as *Tap Notes*.


Press **3** to place down *Hold Notes*. 
You will place down the start of the hold note first, then scroll to the part of the song you want to hold note to end, then **Left Click** again to place down the end of the hold note.

Press **Up Arrow** to change the **Active Side**, which is the side that you are placing notes on. The **Active Side** changes in a clockwise direction, from Main to Left to Right and then back.

Press **4** to go into **EDIT Mode** if you need to select and move or delete notes that are already placed. (More in Navigation Controls)


Be sure to see the [Navigation Controls](Controls%20Nav) Section so you know how to move around the song.




# Niche Stuff Section


## Confusing Numbers around the Notes

This is a sample representation of a note:

        *Bar No. + x/y*
                <=============>
        *Horizontal Value*   *Note Size*

**ATTENTION QUITE CONFUSING AT FIRST, DONT REALLY HAVE TO KNOW:**

**Bar No. + x/y**: Bar No. is the bar of the song that you are about to place the note in. Exact timing depends on BPM of the song. (Music Theory)
y is the number of sub intervals of the bar that the note can be snapped to (adjusted by **C/V**, recommend 4 or 8, use 12 to place at 1/3 intervals in bars)
x is the sub interval that the note is being snapped onto.

The more intervals allowed to be snapped to means the shorter amount of time between each sub interval.

For a song with 4/4 time signature you can set y=4 then place down notes on 1/4, 2/4, 3/4, 4/4(not shown in editor) to have all 4 Beats in the bar to have notes on them. Or you can set y=16 and place notes at 4/16, 8/16, 12/16, 16/16 and achieve the same result. But having y at 16 means you can place more notes in between the timings of the 4 Beats in the bar

x/y is like which sub interval of the bar are u placing the note in, it represents the timing of the song that you are placing the note


**Horizontal Value** : The x coordinate on the axis (or the column) that the note is being placed on.



## Multi-color Squares at middle of notes and what it represents:
Will update again in the future.

**White Square**:
Shows up in EDIT Mode (When you press **4**) when your mouse is near a note. This note will be selected if you double click.

![Pic Showing Blue and Purple Square on Note](Images/Blue%20Square%20Pic%202.jpg?raw=true "Blue and Purple Square")

**Blue Square**:
This square means that the current size you have selected (Size of the next note you place down if you do not change its size) is the same as the notes that have the blue square on them. When you see blue squares on multiple notes, note that they all have the same size.

**Purple Square**:
This square means that this note is the same size and in the same column as the note that you are about to place down. (Blue + Red = Purple)

![Pic Showing Red Square on Note](Images/Red%20Purple%20Blue%20Square%20on%20Note.jpg?raw=true "Red Square")

**Red Square**:
If a note has a red square it means that this note is in the same column as the note that you are about to place down. Very useful for aligning your notes.

### Unknown Squares:

![Pic Showing Yellow Square on Note](Images/Yellow%20Square%20on%20Note.jpg?raw=true "Yellow Square")

**Yellow Square**: Rarely shows up, I do not know why it appears, seems like it does for no reason.

![Pic Showing Grey Square on Note](Images/Grey%20Square%20on%20Note.jpg?raw=true "Grey Square")

**Grey Square**: This seems to show up even less than the Yellow Square and I have no idea why it does.



## HYINTS: 
Save your chart regularly using the right click menu so as to not lose progress




# Troubleshooting

If you encounter any bug while charting and your screen turns black, do the following steps to recover your chart and not waste the past few hours of work you put into it!
_(For example: When you press **S** too many times until Song Speed becomes 0 in the dynaremixv3 chart maker.)_

#### Steps:
1. Press "F12"
2. In the Dev Window that pops up, press the "Console" tab at the top
3. In the console type save();

Then you can choose where to save your map xml file in the pop up window even though the screen is black, after that just reload dynaremix and then reopen your newly downloaded map xml file and breathe a sigh of relief.



[Back to Main Page](https://github.com/TLChicken/dynamaker-guide)

