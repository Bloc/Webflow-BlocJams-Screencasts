## Designing the Home Page and Top Navigation Bar

> Webflow has made slight changes to its interface since this tutorial was created. However, the controls are the same — just the placement of a few items has changed. We'll keep this tutorial updated with new changes, as this is quite common with software as a service products.

<center>
<video width="1024" height="576" controls> <source src="https://bloc-books.s3.amazonaws.com/webflow/screencasts/BlocJams-1.mp4" type="video/mp4">
</video>
</center>

Building the page shown in the video above would require a lot of custom HTML and CSS code. As you'll see from these short videos, we can accomplish the same results much more efficiently with Webflow. Before you begin, download [this zip file](https://bloc-books.s3.amazonaws.com/webflow/assets/BlocJams_Assets.zip) of images we'll be using throughout this tutorial.

Let's jump to it and change the background color on our site:

<center>
<video width="1024" height="576" controls> <source src="https://bloc-books.s3.amazonaws.com/webflow/screencasts/BlocJams-2.mp4" type="video/mp4">
</video>
</center>

Follow the steps in the video and update the background color property on the body element to `#4d4d4d`.

That was too easy. Let's explore some new elements and properties as we build the navigation area:

<center>
<video width="1024" height="576" controls> <source src="https://bloc-books.s3.amazonaws.com/webflow/screencasts/BlocJams-3.mp4" type="video/mp4">
</video>
</center>

In the video we accomplished the following:

* added a new section named `topNav`
* changed the background color to `rgba(43,43,43,0.9)`
* changed the opacity to `90%`
* nested a `container` element within the `topNav` element
* added a link block inside the `container` element and named it "logo"
* added an image within the `logo` link block and uploaded `logo.png`
* added `10px` of padding to the top and bottom of the `logo` link block

In the next chapter we'll work on the main section of our home page, and make it stand out with a sweet-looking image and call-to-action.
