## Superfly Search

Our Browse page is linked, but our Search panel is still without functionality. We want to display search results and images when a user is searching for an album, but we don't have much room to do it. Since we're low on real estate, we'll utilize a sliding search panel that will display results when a query is submitted. Let's get started:

<center>
<video width="1024" height="576" controls> <source src="https://bloc-books.s3.amazonaws.com/webflow/screencasts/BlocJams-29.mp4" type="video/mp4">
</video>
</center>

Just a few minor things to note here, but it's mostly review for you at this point:

* added a section named `search`
* set the width to 300px
* set the height to 100%
* added 100px of margin on the left side
* changed top and bottom padding to 10px
* set the position to fixed
* updated z-index to 2
* set the fill color to #313131
* added a container element inside the `search` called `searchBox`
* removed the top margin and update to -10px
* added in 20px to the top, left and right sides
* set the position as relative

Let's move on and create our search form:

<center>
<video width="1024" height="576" controls> <source src="https://bloc-books.s3.amazonaws.com/webflow/screencasts/BlocJams-30.mp4" type="video/mp4">
</video>
</center>

Here's a recap of our steps, which includes some minor refactorings:

* added a form block element
* removed text label, the second text input field and the submit button
* renamed the form to `searchPanel`
* renamed the text field to `searchField`
* changed left padding to 10px
* added bottom margin of 10px
* changed the width to 220px
* set the position as relative
* positioned top left and then 41px from the left side
* filled the background color to #565656
* added a 1px solid transparent line around the `searchField`
* clicked on the right-top and right-bottom radius and set to 4px
* changed the typeface to open sans
* set the text color to #FFF and 12px
* added a new div called `searchIcon`
* set the width and height to be 38px
* added 8px of padding up top
* set position to absolute
* positioned 20px from the top and 20px from the left
* added an image and uploaded the `small_search.png` file

Our search form is decent, but we want to mock some search results too. Let's add some artists links and images for sample search results:

<center>
<video width="1024" height="576" controls> <source src="https://bloc-books.s3.amazonaws.com/webflow/screencasts/BlocJams-31.mp4" type="video/mp4">
</video>
</center>

There were a lot of steps, so make sure you understand the following:

* added a new section
* added an h4 header
* set the top and bottom padding to 10px
* change to Open Sans Semi-Bold
* sized the font to 14px and set to uppercase
* changed the color of the type to #fcfcfc
* added a new section below the header called `artistList`
* added a bottom margin of 15px
* created an image named `avatar` with a class of `artist`, and uploaded `artist1.jpg`
* updated the right margin to 15px
* checked to see if it's being displayed inline-block and floated left
* added a link block named `artistSearch`
* added a top margin of 18px and floated left
* changed the font style to open sans, light, and 16px
* added a new link block and a text block named `trackSearch`
* created a 5px margin on the bottom of `trackSearch`, floated left, and cleared
* set the font style to 16px, open sans
* added another link block and text block inside of `trackSearch` and renamed it to `trackSearchName`
* set the font style to 12px uppercase #cfcfcf
* floated left and displayed block

Now it's time for fun with animation! We want the search panel to fly-out when it's clicked:

<center>
<video width="1024" height="576" controls> <source src="https://bloc-books.s3.amazonaws.com/webflow/screencasts/BlocJams-32.mp4" type="video/mp4">
</video>
</center>

To recap, we:

* added a new interaction named "Search Slide"
* moved it left 300px from the initial position
* duplicated the interaction and named it "nav opacity 2"
* added a new click trigger
* checked the **Affect Different Elements** checkbox
* set the first click to move to the origin position at a rate of 350ms
* set the second click to move 300px to the left from the origin position at a rate of 350ms

Our search design is now complete. Let's add a couple more links to make navigating Bloc Jams easier:

<center>
<video width="1024" height="576" controls> <source src="https://bloc-books.s3.amazonaws.com/webflow/screencasts/BlocJams-33.mp4" type="video/mp4">
</video>
</center>

That was easy, we only needed to do a couple of things:

* linked the logo on the browse page to the home page
* linked the button on the home page to the browse page

***

Congratulations on designing a beautiful, responsive web site without writing a line of code! At Bloc, we actually love writing code, and writing your own HTML, CSS and JavaScript is a big part of our [UX and Design course](https://www.bloc.io/design). That being said, if you want to design rapid prototypes, learn how to use new CSS tricks, or merely want to visualize how CSS properties affect HTML elements, Webflow is a great tool to use. Beginners and professionals can find distinct use cases for Webflow, so if you're serious about web design you may want to consider it.

We hope you enjoyed yourself and don't hesitate to reach out if you have any questions about this tutorial. You may be interested in trying our other courses, like [Building an iOS Tetris app in Swift](https://www.bloc.io/tutorials/swiftris-build-your-first-ios-game-with-swift) and [Building a landing page with the Skeleton CSS framework](https://www.bloc.io/tutorials/jottly-a-beginner-s-guide-to-html-css-skeleton-and-animate-css). Come back soon!
