## Browse Controls

<center>
<video width="1024" height="576" controls> <source src="https://bloc-books.s3.amazonaws.com/webflow/screencasts/BlocJams-19.mp4" type="video/mp4">
</video>
</center>

Let's complete the design and interactions for the side bar navigation. Watch the following video and learn how we create cool-looking controls for browsing music:

<center>
<video width="1024" height="576" controls> <source src="https://bloc-books.s3.amazonaws.com/webflow/screencasts/BlocJams-15.mp4" type="video/mp4">
</video>
</center>

The first step of building our side bar is complete, now that we've added our logo. To recap, here's what we did:

* added a link block named `browseLogo`
* centered `browseLogo` using left and right margin-auto
* added 10px padding on the top and bottom of `browseLogo`
* added a width 100% to `browseLogo`
* added a relative position for `browseLogo`
* added an image element named `blocJams`
* uploaded `logo.png`
* centered `blocJams` using left and right margin-auto

Let's fill out the side bar with search, browse and playlists panels:

<center>
<video width="1024" height="576" controls> <source src="https://bloc-books.s3.amazonaws.com/webflow/screencasts/BlocJams-16.mp4" type="video/mp4">
</video>
</center>

Let's review our steps, since we did some tricky stuff with overlays:

* added an unordered list with no bullets
* added a link block for the first list item named to `navItem`
* added 20px padding to the top and bottom of `navItem`
* centered `navItem` using left and right margin-auto
* changed the width to 100%
* changed the position to relative
* updated the text to align-center
* updated the font style to open sans, normal, #FFF, 14px, and no underline
* added an image element
* uploaded `search_active.png`
* changed the image display to inline-block
* changed the image position to relative
* changed the z-index to 1
* added a text block below the image named `navText`
* added top padding of 10px to `navText`
* changed the `navItem` to position relative
* updated the z-index to 1
* updated the font style to open sans with a white color
* added a new div block named `navBg`
* updated the width of `navBg` to 100% and height to 100%
* changed the position to absolute
* positioned `navBg` to be top left with a z-index of 0
* changed the fill color to #313131

Let's personalize our page with a custom avator image:

<center>
<video width="1024" height="576" controls> <source src="https://bloc-books.s3.amazonaws.com/webflow/screencasts/BlocJams-17.mp4" type="video/mp4">
</video>
</center>

That wasn't too bad. Let's review what we did:

* added a div block named `profileAvatar`
* added top and bottom padding of 20px
* added a width of 100%
* added a position absolute
* aligned to the bottom left
* added an image and uploaded `avatar.jpg` with a class of `avatar`
* centered using left and right margin-auto
* adjusted the width and height to 60px
* added a border-radius 50% to make it a circle
* added a text block and named it `avatarName`
* added top padding of 10px
* changed the font style to open sans, #fff, and 12px
* center aligned the text

Now it's time to make the side bar sizzle with interactions. Check out how we do it:

<center>
<video width="1024" height="576" controls> <source src="https://bloc-books.s3.amazonaws.com/webflow/screencasts/BlocJams-18.mp4" type="video/mp4">
</video>
</center>

We used some new settings for our interactions, so let's recap:

* selected the "Browse" `navItem`
* clicked the **Settings** panel and changed the link settings to link to a page and selected "Browse" from the drop down
* created a new interaction named `leftNav Opacity`
* set the initial opacity to 50%
* added a trigger and selected hover from the pop-up
* for the hover-over, changed the opacity to 100% and the timing to 200ms
* for the hover-out, changed the opacity to 50% and the timing to 200ms
* added a second trigger and selected hover
* checked the **Affect different elements** checkbox
* checked the **Limit to nested elements** checkbox
* for the hover-over, changed the opacity to 100% and the timing to 200ms
* for the hover out, changed the opacity to 0% and the timing to 200ms
* selected the "Browse" `navItem` and added a new class named `navActive`
* changed the fill color to #313131
* selected the `navBg` layer
* created a new interaction named `0% opacity on load`
* changed the initial appearance to 0% opacity
* selected the `navItem` layers in "Search" and "Playlists" and added the `leftNav Opacity` interaction
* selected the `navBg` layers in "Search" and "Playlists" and added the `0% opacity on load` interaction

Our side bar is now complete. Let's move on and add some album covers to our page.
