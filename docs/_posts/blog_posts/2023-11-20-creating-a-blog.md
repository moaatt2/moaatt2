---
layout: post
title:  "Creating a Portfolio Website"
categories: programming blog-post web-design
permalink: '/blog/creating_a_blog'
type: blog
---

Status: Ideation

After working on my [chainmail blog]() for a while I decided that I wanted to try making a website with Jekyll that could be built and previewed locally and use GitHub for hosting.

My friend had recently done the same thing and suggested this [series of tutorials](https://www.youtube.com/playlist?list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB) by [Giraffe Academy](https://www.giraffeacademy.com/), This is actually what prompted me to start working on this.

When thinking about what kind of website to make I decided that I should make a portfolio website with my resume, and showcasing projects I have done. With the experience I had gained working on my chainmail blog making me feel confident enough that I could work on this.

The tutorial got me to the point where I had a working locally hosted static website built in jekyll.

However when I went to push the website to github pages I noticed that it did't work. After debugging it I found that I needed to update the `baseurl` field in the jekyll config file.

Additionaly, I also created blog and project layouts for use on different pages to let me create a blog page with blog posts separate from my projects page to funciton as a portfolio.

Finally, I created a resume layout page that is built dynamically from a `resume.yml` data file and used it to create the Resume page.
