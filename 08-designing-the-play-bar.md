## Designing the play bar

<center>
<video width="1024" height="576" controls> <source src="https://bloc-books.s3.amazonaws.com/webflow/screencasts/BlocJams-26.mp4" type="video/mp4">
</video>
</center>

* Add a new section and call it `playBar`
* change left margin to 100px
* add padding to top and bottom of 20px
* set the width to 100% and the height to 90px
* fix the position to the bottom left
* update the z-index to 1
* fill the background with the rgba(44,44,44,0.9)

<center>
<video width="1024" height="576" controls> <source src="https://bloc-books.s3.amazonaws.com/webflow/screencasts/BlocJams-27.mp4" type="video/mp4">
</video>
</center>

* add padding to left and right of `playBar` that is 20px
* create a new section called `playerControls`
* change the width to `auto`
* float left
* display inline-block
* create a link block and name it `playControls` 
* display inline-block
* add an image and upload `prev.png`'
* copy and paste three more times
* change out the images
* add in 10px of margin to the right side of `playControls`
* add a new class to the last `playControls` - the volume icon
* update the right margin to 40px

<center>
<video width="1024" height="576" controls> <source src="https://bloc-books.s3.amazonaws.com/webflow/screencasts/BlocJams-28.mp4" type="video/mp4">
</video>
</center>

* float left `playerControls`
* display inline block
* position relative
* add a new section called `songInfo`
* set width to 64%
* display inline block
* position relative
* float left
* add in a text block called `playbarSong`
* change to 16px open sans 
* add in a div block and call it songBar
* set the width to 100%
* add in a new text block called songTime
* change the width to auto
* float left
* display inline-block
* position relative
* open sans 10px white 
* add in a new div block and name it timeBar
* update the margin to be 10 on top, left and right and 0 on bottom.
* change the width to 91%
* height 3px
* float left
* display inline-block
* position relative
* change the fill color to #555
* copy and paste
* add a second class called `timeActive`
* set the width to 125px
* display inline-block
* and position absolute top left
* update the z-index to 1
* change the fill color to #ea3370
* remove the 10px of margin to the top and left sides
* duplicate the start time for `songTime`
* add a second class to the new one and call it `last`
* click and drag it below the timeBar

