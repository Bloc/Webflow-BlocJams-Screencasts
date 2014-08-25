## A Heroic Home Page and Call-to-Action

Let's make our home page stand out with a "hero" image that represents our brand. Watch the video below to learn how we create a beautifully-styled and positioned hero section.

<center>
<video width="1024" height="576" controls> <source src="https://bloc-books.s3.amazonaws.com/webflow/screencasts/BlocJams-4.mp4" type="video/mp4">
</video>
</center>

Follow the steps in the video and make sure you accomplished the following:

* added a new `section` element named `hero`
* set the `hero` width to `100%` and the height to `800px`
* nested a `section` within `hero` named `heroImage`
* set the `heroImage` width to `100%` and height to `800px`
* created a background image and uploaded `heroImage.jpg`
* preset the `heroImage.jpg` position to the bottom edge of the `heroImage` section
* made sure the "X" button is pushed in the "Tile" section of the `heroImage.jpg` properties, so the image does not repeat
* changed the opacity of `heroImage` to `70%`

A hero image is often used on today's websites as a way to convey a message about what the product is. The image you select should portray that meaning, as in this case, we have a musician. We've declared a height of 800px so that the image will size nicely on our site. We've removed tiling, because we don't want it to show up more than one, and the opacity will help your text show up more clearly, which we'll go over in the next few sections. While our page already looks a lot better, it's not completely clear what Bloc Jams _is_.

In the next video we'll add some text and a call-to-action button.

<center>
<video width="1024" height="576" controls> <source src="https://bloc-books.s3.amazonaws.com/webflow/screencasts/BlocJams-5.mp4" type="video/mp4">
</video>
</center>

Review the video if you need to double check some of your settings. Here's a recap of what we did:

* updated the `heroImage` position to `absolute` and updated the positions for: top, left, right and z-index to be 0
* added a new container named `homeText`
* set the `homeText` position to `relative`
* set the `z-index` of `homeText` to 1, so it appears on top of `heroImage`
* created `h1` and `h2` headings in `homeText`
* created a `button` in `homeText`
* modified the `h1` font properties to open sans, light, center-aligned, 75px font and line height, and gave it a color of #ea3370
* modified the `h2` to open sans, normal, center-aligned, 24px font and line height, and gave it a color of white
* modified the button properties:
    * button font: uppercase, open sans, 16px, white
    * button background: #ea3370
    * button element: 10px padding on the top and bottom, 30px margin on the top, 250px width, center-aligned within container, border-radius of 20px
* added padding of `200px` to the `homeText` container

You're getting exposed to a lot of different properties for different elements. We've added some eye-catching text to our page that provides some additional context to what Bloc Jams is. Our main call-to-action should stand out, which is why we've chosen to replicate the color from the headline and the logo. The pink plays nicely with a black and white photo to grab the user's attention.

Now let's add some cool effects to our page:

<center>
<video width="1024" height="576" controls> <source src="https://bloc-books.s3.amazonaws.com/webflow/screencasts/BlocJams-6.mp4" type="video/mp4">
</video>
</center>

That was simple! To make the button color change on a hover event we:

* clicked on the button element and clicked on "states"
* selected `hover`
* changed the fill color to #bd3361

As a designer or developer, you should **always** remember to accommodate hover, active and focus states for your websites. So we made sure to add in a slight variation to the background color to let the user know that something's happened.

Now that we're able to take the whole page in, we'd like to make some adjustments. We've realized that 800px is just too tall for that hero image, so let's refactor a few things before moving on:

<center>
<video width="1024" height="576" controls> <source src="https://bloc-books.s3.amazonaws.com/webflow/screencasts/BlocJams-7.mp4" type="video/mp4">
</video>
</center>

* changed the `hero` height to `650px`
* changed the `heroImage` height to `650px`
* added a text shadow to `h2`
* changed the shadow angle to 180 degrees rgba(0,0,0,0.3)
* changed the shadow blur property to `2px`

And there we have it. Our home page is in good shape but it still needs a few things. Let's add a promotional section to explain our product a but better. We'll also need a footer to round the home page out. We'll do both of those things in the next chapter.
