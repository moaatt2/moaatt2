---
layout: post
title:  "Updating a Blog"
categories: programming blog-post web-design
permalink: '/blog/updating_a_blog'
type: blog
---

Helpful tutorial: https://www.youtube.com/playlist?list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB

Filtering Posts: https://stackoverflow.com/questions/42843187/filter-posts-by-category-in-jekyll
* Segregated Blog and Project Posts

Themes Used: 
* Minima - Base theme
* jekflix - contact form styling
* minimajake - footer (https://github.com/JakeSteam/minimaJake)

Removing Style Changes on Chrome Auto Complete: https://css-tricks.com/snippets/css/change-autocomplete-styles-webkit-browsers/

Resume commas in list except for last
https://talk.jekyllrb.com/t/separate-items-in-array-with-commas-except-last/4041/2

Using Grids for layout

Gallery
* Wanted a gallery of images that would be dynamically created for each item and function nicely.
* Wanted boostrap like behaviour however, installing bootstrap was not feasible due to conflicts with existing css.

RSS
* Needed to create custom RSS feed as basic one from plugin didn't work very well:
    * No icon/logo support
    * No support for setting image size
    * No support for manually setting url

3d model:
* Decided on using threejs since it had an easy
* Started following youtube tutorials which were not helpful.
* Ended up following tutorials from the threejs website, these were very helpful.
    * Start with just getting cubes on screen.
    * Figure out how to import a
    * Figured out how to switch from orbit controls to trackball controls. I didn't like how orbit controls couldn't move past the poles.
* I had trouble working out the lighting as ambient lighting doesn't work on metallic materials. I ended up deciding that the best way to sort it out for the time being was to modify the models to be rougher non-metalic material and add some point lights to make it easier to see.
* Modifed the tutorial code to be used in an include so it can be reuseable.
* Updated the include to allow for:
    * Specifying the canvas name, so multiple models can go in the same post.
    * Not including its own canvas so you can target another canvas,
    * Not including the imports/style tag to avoid duplicates with multiple uses.
* Realize that the styling should go with the css for the posts.

About Page:

* The years dynamically update each time the page reloads.
* Help Docs:
    * [Calculate Date differences](https://stackoverflow.com/questions/7763327/how-to-calculate-date-difference-in-javascript)
    * [Round years](https://www.geeksforgeeks.org/how-to-round-a-number-to-a-certain-number-of-decimal-places-in-javascript/)
