---
layout: post
title:  "Creating a Portfolio Website"
categories: programming blog-post web-design
permalink: '/blog/creating_a_blog'
type: blog
---

Status: Drafting

#### Content - In Progress

A friend of mine recently made a blog using Jekyll and github pages and sent me the tutorials ([Jekyll - Static Site Generator | Tutorial](https://www.youtube.com/playlist?list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB) by [Giraffe Academy](https://www.giraffeacademy.com/)) he used. When reviewing the tutorials I found that they differed from my chainmail blog in that this workflow started with downloading ruby and jekyll so you can build and host the website locally so you can see the changes as you make them. This would fix one of the largest issues I had with my blog and allow me to use branching logic. However I wanted to try it out and learn how it workd before I implemented it into the blog. Rather than making a small test website I decided to create this portfiolio website so that I would be making something I needed while learning how to use Jekyll.

Following the tutorials had me start with installing Ruby and Gem then the Jekyll framework. From there I ran a setup command to create the boilerplate for a Jekyll project, then modified the `_config.yml` file to set a title, footer information, and set the theme to minima dark. In order to ensure that the website worked when pushed to GitHub I also created a separate part in the `_config.yml` file to denote GitHub specific settings, in this case a different baseurl.

p2 - TODO

p3 - TODO

p4 - TODO

Overall I found making this portfoilio website to be a and fun and iluminating project. It has caused me to install Ruby which I might try programming in later, given me much more exposure to the Jekyll framework, increased my knowledge of web development and provided me a platform to showcase my skills to others. Creating a portfolio website is a project that I highly recomend to any programmer. GitHub makes it very easy to create an host a website for free and a large part of learning programming is making things, a portfolio website is the perfect place to show off what you have made.

#### Structure plans

* Opening paragraph:
    * Motivations and decsion to make website
* Paragraph 1:
    * How I made the base website
* Paragraph 2:
    * How I created the resume page
* Paragraph 3:
    * How I created the blog and and posts pages.
* Paragraph 4:
    * Various customizations
* Concluding Paragraph:
    * You should make your own stuff and make your own portfolio website


#### Content Snippets

After working on my [chainmail blog]() for a while I decided that I wanted to try making a website with Jekyll that could be built and previewed locally and use GitHub for hosting.

My friend had recently done the same thing and suggested this [series of tutorials](https://www.youtube.com/playlist?list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB) by [Giraffe Academy](https://www.giraffeacademy.com/), This is actually what prompted me to start working on this.

When thinking about what kind of website to make I decided that I should make a portfolio website with my resume, and showcasing projects I have done. With the experience I had gained working on my chainmail blog making me feel confident enough that I could work on this.

The tutorial got me to the point where I had a working locally hosted static website built in jekyll.

However when I went to push the website to github pages I noticed that it did't work. After debugging it I found that I needed to update the `baseurl` field in the jekyll config file.

Additionaly, I also created blog and project layouts for use on different pages to let me create a blog page with blog posts separate from my projects page to funciton as a portfolio.

Finally, I created a resume layout page that is built dynamically from a `resume.yml` data file and used it to create the Resume page.
