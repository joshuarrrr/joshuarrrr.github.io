---
title: Portfolio Sites for Non-coding Journalists
layout: post
tags: Digital publishing
---

Creating personal or portfolio websites shouldn't really be that hard. And for people who work with web technology daily, it isn't, because we're surrounded by a proliferation of tools that make it easy to create and launch simple sites. After all, most personal sites are not that complex: A list of clips, a brief description of the person, a resume or CV, and maybe a blog. Just pick your favorite static site generator (jekyll [js], hexo [js], hugo [go], or pelican [python] are all fine, depending on your language of choice) and choose a place to host the site (GitHub Pages or Amazon S3 are good free options), and you can have your own digital space up and running in no time.

But as good as these tools are, they're built for developers, and generally assume a good deal of implicit technical knowledge that can seem mysterious and daunting for anyone who doesn't already do development work. So journalists, designers, and academics often turn to easier options like Wordpress, Squarespace, or Weebly, instead. All of these require no technical experience to get started, and provide lots of themes that seem to work well out of the box.

The problem is that these user-friendly content management systems are wildly bloated for the purpose of simply updating and maintaining a couple of web pages. While it's possible to set up a very simple personal site, these products are built to support more complicated corporate sites, e-commerce sites, or high-volume blogs. Further bloat comes from installing numerous plugins and themes, which also must support a variety of use. The result is often a slow, expensive site that requires constant updates.

Some of the digital journalists that I highly respect and look up to ([Tyler Fisher](https://medium.com/learning-journalism-tech/github-makes-portfolio-sites-for-journalists-cheap-and-kinda-easy-bd53d882185f#.a8wzcafdc), [Lena Groeger](http://lenagroeger.s3.amazonaws.com/makeawebsite/makeawebsite.html), and [Dan Nguyen](https://dannguyen.github.io/github-for-portfolios/), for instance) have tried to bridge the gap by writing detailed tutorials about setting up personal sites using GitHub Pages. But I think it's important to acknowledge and separate the two very different goals that may go into building a personal site. The first is the practical goal of just getting a site up and the ability to easily edit and change its content. The second goal, with more long-term benefits, is to learn: about digital publishing, web technologies, version control, etc. Most of these tutorials assume an audience that is interested in both goals. But in reality, launching a static site, especially for a novice, puts the focus much more heavily on the learning objective.

The list of topics to be learned by the unitiated is substantial:

* Plain text files and plain text editor
* Bash and the command line
* Markdown syntax
* Git, GitHub, how they're different, and the concept of version control
* Plain text config files
* HTML basics
* CSS syntax
* Manual image editing and management
* Jekyll and Ruby

This semester I'm auditing [Introduction to Digital Humanities](http://fredgibbs.net/courses/digital-methods/index.html), and over the last two weeks of classes, I saw my classmates tackle all of these challenges. There was a good deal of confusion, but also a lot of learning. As frustrating as it may have been, we still managed to cover a lot of ground in the class, much faster than when I was learning all of this stuff on my own a few years ago. And my classmates will soon have an array of tools at their disposal that will come in handy for other more complicated projects.

But what about for people who care more about the portfolio than the learning objectives? I'd like to be able to recommend a static site solution for journalists who aren't looking to pick up developer skills. Something where they can focus on Markdown/HTML/CSS, with a publishing workflow that doesn't require knowledge of git. How personal sites look is also very important, and I  don't think it's reasonable to expect journalists to design a site from scratch. Lena's tutorial helpfully includes the idea of working with a template, and I think basic themes or templates are a major requirement for getting people off to a productive start. 

Obviously I'm not the first person to identify this need, and there are now many content management systems built for publishing static sites. In fact, the large number of choices only further complicates the question. In the next few weeks I plan to try out a few, and ideally find a solution that I can recommend as a viable Wordpress alternative. Here's the list of tools I'm considering:

- [Prose.io](http://prose.io/#about)
- [HubPress.io](http://hubpress.io/)
- [Statamic](https://statamic.com/)
- [Forestry.io](https://forestry.io/)
- [Kirby](https://getkirby.com/)
- [Grav](https://getgrav.org/)
- [DatoCMS](https://www.datocms.com/)
- [Roots](http://roots.cx/)