## Album Covers and Interactions

We can't have our users browse music without albums, so let's add some. In this chapter we'll add some awesome album art. Check out what we'll be doing:

<center>
<video width="1024" height="576" controls> <source src="https://bloc-books.s3.amazonaws.com/webflow/screencasts/BlocJams-24.mp4" type="video/mp4">
</video>
</center>

Let's start with the album covers:

<center>
<video width="1024" height="576" controls> <source src="https://bloc-books.s3.amazonaws.com/webflow/screencasts/BlocJams-20.mp4" type="video/mp4">
</video>
</center>

It's so satisfying to see pretty pictures after a few changes. Let's recap:

* added an image and uploaded `album1.jpg` with a class of `albumCover`
* set the width of `albumCover` to 100%
* set the height of `albumCover` to 100%
* set the display to `inline-block`
* set the inner shadow to white and 90 degrees, with a distance of 0, a blur of 1px, and size of 0

Let's fill out the album covers with a song title, artist name and play button:

<center>
<video width="1024" height="576" controls> <source src="https://bloc-books.s3.amazonaws.com/webflow/screencasts/BlocJams-21.mp4" type="video/mp4">
</video>
</center>

To review:

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

Our albums are looking good, but they're oh-so static. Let's add some hover interactions:

<center>
<video width="1024" height="576" controls> <source src="https://bloc-books.s3.amazonaws.com/webflow/screencasts/BlocJams-22.mp4" type="video/mp4">
</video>
</center>

If you've ever coded interactions by hand, hopefully you're starting to appreciate the efficiency of a visual tool. Let's review the steps in the last video:

* created a new interaction called `Hover Over - Album`
* added a trigger with a hover effect
* selected to affect different elements, and typed in `albumDetails`
* checked limit to nested elements
* set the first hover-over step to move the `albumDetails` down 300px at 0ms
* set the second hover-over step to move to origin at 100% opacity and 350ms ease-in
* created a hover-out to move down 300px at 350ms ease-in and opacity of 0%
* created a second step for hover-out to move to origin
* added the `0% opacity on load` interaction to the `albumDetails`

Let's create another hover effect for our play button:

<center>
<video width="1024" height="576" controls> <source src="https://bloc-books.s3.amazonaws.com/webflow/screencasts/BlocJams-23.mp4" type="video/mp4">
</video>
</center>

This is getting too easy, but let's review anyhow:

* added a new interaction for the play button named `Play Button Hover`
* added a trigger with a hover effect
* set the hover-over to scale to 1.2x at 200ms
* set the hover-out to scale back down to 1x at 200ms

For the last part of this chapter, we'll replicate our album cover and interactions, and just replace the images. This will make our browse page look complete:

<center>
<video width="1024" height="576" controls> <source src="https://bloc-books.s3.amazonaws.com/webflow/screencasts/BlocJams-25.mp4" type="video/mp4">
</video>
</center>

That was fun. Here's a recap:

* selected `album`
* copy and pasted `album` 9 times
* changed the album cover art for each album
* updated the name of the song and artist for each album

We now have 10 albums, great effects and a side bar to navigate our inventory. Time to move on!
