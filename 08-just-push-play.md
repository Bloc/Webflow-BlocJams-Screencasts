## Just Push Play

In this chapter we'll add a universal play bar to easily control the currently-playing album. Let's create the section for it first:

<center>
<video width="1024" height="576" controls> <source src="https://bloc-books.s3.amazonaws.com/webflow/screencasts/BlocJams-26.mp4" type="video/mp4">
</video>
</center>

This is pretty standard stuff by now. Here are the steps from the video:

* added a new section named `playBar`
* changed the left margin to 100px
* added padding to top and bottom of 20px
* set the width to 100% and the height to 90px
* fix the position to the bottom left
* updated the z-index to 1
* filled the background with the rgba(44,44,44,0.9)

Our play bar should remain static throughout Bloc Jams. So that if you start a new song and then go search for the next on the list, the music never stops. This is why we've placed it at the bottom.

Next we'll add controls to our play bar:

<center>
<video width="1024" height="576" controls> <source src="https://bloc-books.s3.amazonaws.com/webflow/screencasts/BlocJams-27.mp4" type="video/mp4">
</video>
</center>

Here's what we did:

* added 20px padding to the left and right of `playBar`
* created a new section named `playerControls`
* changed the width to `auto`
* floated the `playBar` left
* displayed inline-block
* created a link block named `playControls`
* displayed inline-block
* added an image and uploaded `prev.png`'
* replicated the link blocks and replaced the images
* added 10px of margin to the right side of `playControls`
* added a new class to the last `playControls`, which is the volume icon
* updated the right margin to 40px

Most music apps share similar qualities, but all have to have controls. We've made sure to add in the main ones: previous, play, next and volume.

Finally, let's design how the album information will be displayed on the play bar:

<center>
<video width="1024" height="576" controls> <source src="https://bloc-books.s3.amazonaws.com/webflow/screencasts/BlocJams-28.mp4" type="video/mp4">
</video>
</center>

That was a bit of work. Let's review:

* floated `playerControls` to the left
* displayed inline block
* positioned `playerControls` relative
* added a section named `songInfo`
* set width to 64%
* displayed inline block
* positioned `songInfo` relative
* floated `songInfo` to the left
* added a text block named `playbarSong`
* changed the font style to 16px and open sans
* added a div block named `songBar`
* set the width to 100%
* added a new text block called `songTime`
* changed the width to auto
* floated `songTime` to the left
* displayed inline-block
* positioned `songTime` relative
* changed the font style to open sans, 10px and white
* added a new div block named `timeBar`
* updated the margin to be 10 on top, left and right and 0 on bottom
* changed the width to 91%
* height 3px
* floated `timeBar` to the left
* displayed `timeBar` inline-block
* positioned `timeBar` relative
* changed the fill color to #555
* added another class named `timeActive`
* set the width to 125px
* displayed inline-block
* positioned absolute and to the top left
* updated the z-index to 1
* changed the fill color to #ea3370
* removed the 10px of margin on the top and left sides
* duplicated the start time for `songTime`
* added another class named `last`
* click and dragged `last` below the `timeBar`

We want to display the name of the song and artist prominently on the play bar so it's always visible even if you switch pages. The time bar itself will display the current progression of the song, and we've used the same pink to keep with the consistency in color.

Our play bar is now complete and looking fly. Just a few more chapters and Bloc Jams will be complete.
