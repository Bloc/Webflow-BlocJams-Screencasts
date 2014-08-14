## Browsing Music

Our home page is looking sweet, and we're bound to get users. Let's give them a page to browse our awesome music library. Take a look at the page we're about to build:

<center>
<video width="1024" height="576" controls> <source src="https://bloc-books.s3.amazonaws.com/webflow/screencasts/BlocJams-10.mp4" type="video/mp4">
</video>
</center>

Let's get to it and create a new page for browsing:

<center>
<video width="1024" height="576" controls> <source src="https://bloc-books.s3.amazonaws.com/webflow/screencasts/BlocJams-11.mp4" type="video/mp4">
</video>
</center>

In addition to creating a new page, we added a side bar that will store our browsing options. Here's a recap of what we did:

* created a new "Browse" page
* added a section named `leftNav`
* set the width of `leftNav` to 100px
* set the height of `leftNav` to 100%
* fixed the position of `leftNav` to the top 0px and left 0px
* filled the color of `leftNav` with #3d3d3d
* set the border property of `leftNav` to right 1px, solid, and rgba(0,0,0,0.8)
* created a drop shadow of rgba(255, 255, 255, 0.08)
* set the shadow to 90 degrees, with a distance of 1px, a blur of 0, and size of 0

Let's take a break from our side bar and focus on the main section of the page:

<center>
<video width="1024" height="576" controls> <source src="https://bloc-books.s3.amazonaws.com/webflow/screencasts/BlocJams-12.mp4" type="video/mp4">
</video>
</center>

That's a good start. Let's recap:

* created a new section named `main`
* set the margin top to 50px
* set the margin right to 60px
* set the margin bottom to 100px
* set the margin left to 160px
* created an `h1` with a class named `browseHeadline`
* set the `browseHeadline` margin top to 20px, and margin botton to 40px
* set the `browseHeadline` font to open sans, light, left-aligned, 45px size and line height
* set the drop shadow properties to rgba(0,0,0, 0.2), 180 degrees, 2px distance and 1px blur

Let's add some tabs to the main section of our page:

<center>
<video width="1024" height="576" controls> <source src="https://bloc-books.s3.amazonaws.com/webflow/screencasts/BlocJams-13.mp4" type="video/mp4">
</video>
</center>

We just created a few tabs, but touched a few styles and multiple properties. Let's review:

* added a list element named to `browseLinks`
* added 20px of margin to the bottom of `browseLinks`
* added a 3px solid border to the bottom of `browseLinks`, with a fill color of #333
* gave the first list item a class named `browseLink`
* added 10px of bottom padding to `browseLink`
* added 40px right margin to `browseLink`
* added -3 bottom margin to `browseLink`
* displayed `browseLink` as inline-block
* changed the font style of `browseLink` to: open sans, semi-bold, 14px size, 20px line height, and uppercase
* added the `browseLink` class to the other two links
* added a `browseActive` class to the first link
* added a bottom border of 3px, solid, #ea3370, and bottom margin of -3px to `browseActive`
* created a hover state for `browseLink`
* added a bottom border on `browseLink` of 3px, solid, #ea3370, and a bottom margin of -3px

To complete the main section of our browse page we'll need albums. But first, let's create a template to add albums to:

<center>
<video width="1024" height="576" controls> <source src="https://bloc-books.s3.amazonaws.com/webflow/screencasts/BlocJams-14.mp4" type="video/mp4">
</video>
</center>

Now we have a good place to add albums, which we'll do soon. Before moving on, be sure you followed the video and did steps listed below.

* added a section named `albums`
* added a link block named `album`
* added 20px of top margin to `album`
* added 2% of right margin to `album`
* added 10px of bottom margin to `album`
* added 18% width to `album`
* added auto height to `album`
* changed the display of `album` to inline-block
* changed the overflow of `album` to hidden
* changed the position of `album` to relative
* added a drop shadow to `album` with the properties of: color #333, 180 degrees, distance of 1px, blur of 5px, and size of 0

In the next chapter we'll complete the side bar navigation on the left of the page.
