<frontmatter>
header: header.md
siteNav: main-nav.md
footer: footer.md
</frontmatter>

<link rel="stylesheet" href="../generalStyle.css">

{{ three_star }}
# Getting Started 

Website Link: https://dynamaker.tunergames.com/

##### Welcome to the unofficial Dynamaker Guide!
This tool grants you the power to create a Dynamix chart for any song you envision a chart being made for, which is amazing! It is made by omegaPi some time ago.

## Step 1: Getting the Editor to fit your screen. 

Use *Google Chrome* to visit the website.
Press <kbd>F</kbd> to go into Full-Screen mode. (Might have to press <kbd>F11</kbd> as well so that everything is aligned.)


<panel header="**If the website does not fit your screen:**" alt="Click here if you have window sizing issues." type="danger" minimized>
	<p>Set the <b>Zoom</b> of the website to 100%.</p>
	<p>(Setting is in the Chrome Dropdown menu at the top right, below the X close window button.)
	If it still does not fit, try other zoom values like 80%. </p>
</panel>

<br>
<br>


## Step 2: Load your music (and map) files

<panel header="If you are creating a new map, only load the music file, then press **New Map**." minimized>
    <tip-box type="warning">
        <p>Press <i>Audio/Video Browse</i> to load, when the button is moused over, it will turn green, if it stays blue it means you are clicking nothing even if your mouse pointer appears to be pointing at the button. </p>
    </tip-box>	    
    <panel header="If you still cannot click the button... (See here if the button always stays blue.)" type="danger" minimized>
        <p>Click slightly below the buttons. If it still does not work, please use the EXE version of Dynamaker 
<a href="https://github.com/jmakxd/dynamaker-modified/releases">found here</a>  
instead as this bug as been fixed there.</p>
    </panel>
</panel>
<br>
If you are editing an existing map, load both the map file and audio file.


## Step 3: New Map Setup

Find the BPM of the song from other sources (eg Osu!), then enter it in the Beat Per Minute or Bar Per Minute box. Then enter the offset if you know what offset it has, else leave it as 0. You can set the offset again later while editing the chart using the **<kbd>O</kbd>** and **<kbd>P</kbd>** keys.

<box type="info">
<p>Entering the BPM of the song: <b>(Please check which box is present in your version of Dynamaker and enter accordingly.)</b></p>
<li>Beat Per Minute is the BPM of the song. </li>
<li>Bars Per Minute is the BPM divided by the Time signature of the song (Number of Beats in 1 Bar)</li>
<li>Numbers entered can contain a decimal point.</li>
</box>


<panel header="Additional Information about the Create Map Menu" alt="Create Map Menu - Additional Information" type="info" minimized>
    <box><h5 style="font-family: Dynamix">Music Name</h5>
        Enter the name of the song. It will display at the bottom left hand corner of the screen when playing the map.
    </box>	
    <box><h5 style="font-family: Dynamix">Difficulty</h5>
        Choose the appropriate difficulty that you intend to chart using the dropdown menu.
        <div>
            Available Difficulties:
<h3>
            {{ casual_badge }}
            {{ normal_badge }}
            {{ hard_badge }}
            {{ mega_badge }}
            {{ giga_badge }}
</h3>
        </div>
        <panel header="Additional Difficulties" minimized>
            <box type="info"><p style="font-family: Dynamix">Custom / None</p>
                There will be no difficulty graphic shown at the bottom left corner of the screen if this is chosen.
            </box>
            <box type="warning"><p style="font-family: Dynamix">HORNEEE - Only available in EXE Version</p>
                <h3> {{ horneee_badge }} </h3>
                This difficulty is used for meme/insane/funny charts, as a reference to Homeee, Dynamix's Official Charter.
            </box>
        </panel>
    </box>
    <box><h5 style="font-family: Dynamix">Left Side and Right Side</h5>
      <li> <span class="DynamixTxtContainer">MIXER:</span> Side has Sliding Bar and can only contain Chain Notes </li>
      <li> <span class="DynamixTxtContainer">PAD:</span> Side can only contain Tap and Hold Notes </li>
      <li> <span class="DynamixTxtContainer">MULTI:</span> Side can contain all 3 types of notes. (This type of side cannot be found in Dynamix) </li>
    </box>
    <box><h5 style="font-family: Dynamix">Offset</h5>
        <li> Use either <span class="DynamixTxtContainer">OFFSET [sec]</span> or <span class="DynamixTxtContainer">OFFSET [bar]</span> and not both, if both are available.</li>
        <li>You can change the offset again later while editing using <kbd>O</kbd> or <kbd>P</kbd>.</li>
    </box>
</panel>

<br>

## Step 4: Create Map

Press the Start button.
Change the offset of your song by using the **<kbd>O</kbd>** and **<kbd>P</kbd>** buttons.
**<kbd>O</kbd>** makes notes come later.
**<kbd>P</kbd>** makes notes come earlier. 


## Next:

**[Controls - Navigation and Charting]({{ baseUrl }}/Contents/Controls%20Nav.html)** {{ two_star }}

**[Placing Notes]({{ baseUrl }}/Contents/Placing%20Notes.html)** {{ three_star }}


## TO SAVE YOUR CHART
1. Right Click
2. Click Save as XML to only save the chart file. 
3. Next time when opening DynaMaker, load both the XML map file and the song file.

<panel header="About .DY files and what they do. " alt="About .DY Files" minimized> {{ hint_badge }}

Alternatively you can click Save as .DY to save as a format which contains both the map and the song. (File Size is bigger!!) 
When you save it in this form, the next time you open DynaMaker you only need to load the .dy file as it contains both the map and song. However if you save too many .dy files it will take up a lot of space.

.dy files can also be loaded into the DynaMaker website on your phone to play the chart using DynaMaker's in-built touchscreen interactive chart player. (Personally I couldn't get it to load on some of my devices as the screen and webpage are misaligned. I tried a few devices but I could get it to work consistently only on a iPhone 7 running iOS 10 though.) This is an alternative way to test your chart if you do not want to upload your chart on to Dynamite.

</panel>

<br><br>



**[Back to Main Page](../mainPg.html)**


