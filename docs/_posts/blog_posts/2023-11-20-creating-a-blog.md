---
layout: post
title:  "Creating a Portfolio Website"
categories: programming blog-post web-design
permalink: '/blog/creating_a_blog'
type: blog
---

Status: Refining

#### Content - In Progress

A friend of mine recently made a blog using Jekyll and GitHub pages and sent me the tutorials ([Jekyll - Static Site Generator | Tutorial](https://www.youtube.com/playlist?list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB) by [Giraffe Academy](https://www.giraffeacademy.com/)) he used. When reviewing them, I found that they differed from my chainmail blog in that they used Ruby and Jekyll locally, which allows for building and viewing the rendered website locally. Implementing those changes would allow me to use Git branching and pull requests with my chainmail blog, fixing one of its most pressing issues. However, I wanted to try using it to learn how to use it before implementing it into my blog. Rather than making a dummy test website, I decided to create this portfolio website so I could make something I needed and learn more about Jekyll at the same time.

Following the tutorials had me start with installing Ruby and Gem then the Jekyll framework. From there I ran a setup command to create the boilerplate for a Jekyll project, then modified the `_config.yml` file to set a title, footer information, and set the theme to minima dark. In order to ensure that the website worked when pushed to GitHub I also created a separate part in the `_config.yml` file to denote GitHub specific settings, in this case a different baseurl.

As this was intended to be a portfolio website I needed to include a resume, and I wanted the resume to be easy to update so I couldn't hardcode the page. When I found out about data files I realized that they would provide the perfect opportunity to make that possible. I then created the `resume.yml` data file to contain all of the resume content and sections I needed and filled it out. Then I created the `resume.html` layout using jinja formatting reading from the data file so the page would respond to the content of the data file and I could easily update the data file to update the resume. Lastly, I created the `resume.md` page and had it use the resume layout so that I would have a nice clear Resume option at the top of the page available from any page.

Since this is a portfolio blog I wanted somewhere to display my projects as well and also to have somewhere to write blog posts on more technical topics should I feel like it. I liked how the homepage displayed posts and decided to base both the blog and projects pages on it. To do that I added a `type` value to the front matter and created two layout varants (`blog.html` and `projects.html`) of the basic homepage that itterated over all posts and filtered based on the post type, then created two new pages `blog.md` and `projects.md` to use those layouts and add the `Blog` and `Projects` headings to my website.

In addition to those larger changes I also modifed the footer to handle more diverse external links as well as updating the theme's CSS. The updates I made to the footer were focused on adding support for other social links, primarily GitHub, to get them to work I had to locate svg images that matched the website's theme and updating the `_config.yml` file to contain the new data. I modified the CSS to change the background and text colors as well as to remove the highlights on form fields when they are filled in via autocomplete to keep the visual consistency of the website.

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
