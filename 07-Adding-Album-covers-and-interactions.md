## Adding Album Covers and Interactions

<center>
<video width="1024" height="576" controls> <source src="https://bloc-books.s3.amazonaws.com/webflow/screencasts/BlocJams-24.mp4" type="video/mp4">
</video>
</center>

In this lesson we're going to make the album art pretty kick butt


<center>
<video width="1024" height="576" controls> <source src="https://bloc-books.s3.amazonaws.com/webflow/screencasts/BlocJams-20.mp4" type="video/mp4">
</video>
</center>

* added an image and uploaded `album1.jpg` 
* gave it a class of `albumCover`
* set the width of `albumCover` to 100%
* set the height of `albumCover` to 100%
* set the display to `inline-block`
* set the inner shadow to white and 90 degrees, with a distance of 0, a blur of 1px, and size of 0

<center>
<video width="1024" height="576" controls> <source src="https://bloc-books.s3.amazonaws.com/webflow/screencasts/BlocJams-21.mp4" type="video/mp4">
</video>
</center>

* added a div block and named it `albumDetails`
* set the width of `albumDetails` to 100%
* set the height of `albumDetails` to 100%
* positioned `albumDetails` absolute to the top and left
* set the background color to rgba(0,0,0,0.5)
* added a text block and gave it a class of `songTitle`
* set the left and right margin to auto
* added 20px of padding to the top, left and right sides of `songTitle`
* changed the text to Open Sans, with a color of white and at 22px
* added another text block called `artistName`
* set the left and right margins to auto
* added top and bottom margins of 5px to `artistName`
* changed the left and right padding to 20px for `artistName`
* included an image and uploaded `albumPlay.png`
* renamed it `albumPlay`
* positioned absolute
* left and bottom with 20px of space for `albumPlay`

<center>
<video width="1024" height="576" controls> <source src="https://bloc-books.s3.amazonaws.com/webflow/screencasts/BlocJams-22.mp4" type="video/mp4">
</video>
</center>

* Created a new interaction called `Hover Over - Album`
* added a trigger with a hover effect
* select to affect different elements, and typed in `albumDetails`
* checked limit to nested elements
* set the first Hover Over step to move the `albumDetails` down 300px at 0ms
* set the second Hover Over step to move to origin at 100% opacity and 350ms ease-in
* created a Hover Out to move down 300px at 350ms ease-in and opacity of 0%
* created a second step for Hover Out to move to origin
* Add the `0% opacity on load` interaction to the `albumDetails`

<center>
<video width="1024" height="576" controls> <source src="https://bloc-books.s3.amazonaws.com/webflow/screencasts/BlocJams-23.mp4" type="video/mp4">
</video>
</center>

* added a new interaction for the play button
* called it `Play Button Hover`
* added a trigger with a hover effect
* set the hover over to scale to 1.2x at 200ms
* set the hover out to scale back down to 1x at 200ms


<center>
<video width="1024" height="576" controls> <source src="https://bloc-books.s3.amazonaws.com/webflow/screencasts/BlocJams-25.mp4" type="video/mp4">
</video>
</center>

* Select `album`
* Copy and paste
* Change the album cover art
* Updated the name of the song and artist
* Replicated a total of 10 albums


