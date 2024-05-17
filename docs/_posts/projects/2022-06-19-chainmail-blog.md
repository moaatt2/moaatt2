---
layout: post
title:  "Chainmail Blog"
categories: chainmail blog web-design
permalink: '/projects/chainmail_blog'
type: project
status: ongoing
---

Content Status: Refinement

### Origins and Inspiration

In [this repository](https://github.com/moaatt2/test-blog), I maintain [a chainmail blog](https://moaatt2.github.io/test-blog/)(pictured below), where every week I post about a different chainmail weave or other chainmail related topics. I first made the blog as I had heard that GitHub offered free web hosting using GitHub Pages, and I had always been interested in having a website of my own. After following the instructions in the GitHub Pages documentation, I successfully set up the website and published my first post. Unfortunately, the blog sat idle for a while because I couldn't find a steady stream of content to write about. I later learned my first chainmail weave in August of that year. Then, in December, I was first exposed to the wide variety of existing weaves. After observing the vast multitude of weaves, I realized I could feature a new weave each week, providing a steady stream of content and a path to honing my chainmail skills. 

![tech stack diagram](/assets/images/projects/2022-06-19-chainmail-blog/blog_screenshot.png)

### Technical Overview

As this was the first website I had published using GitHub pages it is very simple. The blog is a static website generated from markdown files by Jekyll running via GitHub actions, using one of the offered basic themes(Hacker). This design makes it quite easy to modify and add content to the blog, however since the repository only contains markdown files you cannot build the website locally and must take the changes live to view them rendered making it unrealistic to use branches in the workflow. Below is a diagram showing the tech stack for the blog:

![tech stack diagram](/assets/images/projects/2022-06-19-chainmail-blog/tech_stack_diagram.png)

### Future Plans

In the future I plan to update the blog to allow for local building/viewing  and thus the use of branching in the repository to clean up my workflow. In fact I actually plan to base the updated blog on this website and implement what I have learned in customizing this website as well as to potentially take things further.
