## Finishing the Left Navigation
<center>
<video width="853" height="505" controls> <source src="https://bloc-books.s3.amazonaws.com/webflow/screencasts/BlocJams-19.mp4" type="video/mp4">
</video>
</center>
In this lesson, we'll complete the design and interactions for the left-hand navigation.


<center>
<video width="853" height="505" controls> <source src="https://bloc-books.s3.amazonaws.com/webflow/screencasts/BlocJams-15.mp4" type="video/mp4">
</video>
</center>

* Add in a link block, name it browseLogo
* center using left and right margin auto
* 10px padding on top and bottom
* width 100%
* position relative
* add in an image element, upload logo.png
* rename it blocJams
* center using left and right margin auto

<center>
<video width="853" height="505" controls> <source src="https://bloc-books.s3.amazonaws.com/webflow/screencasts/BlocJams-16.mp4" type="video/mp4">
</video>
</center>

* Add an unordered list with no bullets
* add in a link block to the first list item and rename to navItem
* add 20px padding to top and bottom
* center using left and right margin auto
* width 100%
* position relative
* text align center
* open sans normal #FFF 14px no underline
* add in image element
* upload search_active.png
* display inline-block
* position relative
* change the z-index to 1
* add in a text block below the image
* rename to navText
* add top padding of 10px
* change to position relative
* z-index 1
* Open sans white
* add in a new div block and call it navBg
* 100% width and 100% height
* position absolute
* position to be top left
* with a z-index of 0
* fill color of #313131

<center>
<video width="853" height="505" controls> <source src="https://bloc-books.s3.amazonaws.com/webflow/screencasts/BlocJams-17.mp4" type="video/mp4">
</video>
</center>

* Add in a div block called profileAvatar
* add top and bottom padding of 20px
* width 100%
* Position absolute
* bottom left 
* Add in an image, upload avatar.jpg
* rename it to avatar
* center using left and right margin auto
* width and height of 60px
* radius 50%
* add in a text block and name it avatarName
* add top padding of 10px
* open sans #fff 12px
* center align


<center>
<video width="853" height="505" controls> <source src="https://bloc-books.s3.amazonaws.com/webflow/screencasts/BlocJams-18.mp4" type="video/mp4">
</video>
</center>

* Select the Browse navItem
* Click Settings panel and change the link settings to link to a page and select Browse from the dropdown
* create a new interaction called leftNav Opacity
* set the initial appearance to 50%
* Add a trigger and select hover from the popup
* For the hover over, change the opacity to 100% and the timing to 200ms
* For the hover out, change the opacity to 50% and the timing to 200ms
* Add a second trigger and select hover
* Check the Affect different elements checkbox
* type in navBg
* And check the limit to nested elements checkbox
* For the hover over, change the opacity to 100% and the timing to 200ms
* For the hover out, change the opacity to 0% and the timing to 200ms.
* Select the Browse navItem and add a new class called navActive
* Change the fill color to #313131
* Select the navBg layer
* Create a new interaction called 0% opacity on load
* Change the initial appearance to 0% opacity
* Select the navItem layers in Search and Playlists and add the leftNav Opacity interactions
* Select the navBg layers in Search and Playlists and add the 0% opacity on load interactions