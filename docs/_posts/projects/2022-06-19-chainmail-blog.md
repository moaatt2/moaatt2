---
layout: post
title:  "Chainmail Blog"
categories: chainmail blog web-design
permalink: '/projects/chainmail_blog'
type: project
status: ongoing
---

Content Status: Ideation

### Origins and Inspiration

I maintain [this blog](https://moaatt2.github.io/test-blog/), from [this repository](https://github.com/moaatt2/test-blog), where every week I post about a different chaimail weave or other chainmail related topics. I first made the blog as I had heard that GitHub offered free webhosting using GitHub pages and I had always been interested in having a website of my own. I set up the website following the instructions in the GitHub pages documenation and made a single post. Unfortunately, I had no ideas for content that I could post on a regular basis so the website remained empty for quite some time. I was introduced to chainmail in august of that year and I learned about the wide variety of weaves that existed in December. After learning about the vast amount of weaves that existed I came up with the idea to make a post about a new weave every week as a source of content.

### Technical Overview

As this was the first website I had published using GitHub pages it is very simple. The blog is a static website generated from markdown files by Jekyll running via GitHub actions, using the Hacker theme. This design makes it quite easy to modify and add content to the blog, however since the repository only contains markdown files you cannot build the website locally and must take the changes live to view them rendered making it unrealistic to use branches in the workflow.

![tech stack diagram](/assets/images/projects/2022-06-19-chainmail-blog/tech_stack_diagram.png)

### Future Plans

In the future I plan to update the blog to allow for local building/viewing  and thus the use of branching in the repository to clean up my workflow. In fact I actually plan to base the updated blog on this website and implement what I have learned in customizing this website as well as to potentially take things further.
