---
layout: post
title: How to create open educational resources with Jekyll and GitHub Pages
---

Over the past few months, we have been learning how to a use a handful of new tools to create open educational resources and publish them online. GitHub, Jekyll and GitHub pages are three of those tools and we used them to create the website you are reading right now.

[Jekyll](http://jekyllrb.com) is a  static site generator for turning plain text files into websites or blogs. [GitHub](https://github.com/) is a popular service for sharing and collaborating on open-source projects. [GitHub Pages](https://pages.github.com/) is an feature that allows users to host simple websites using a GitHub repository. I did not know much about how these tools worked when we started the project so I wanted to share some background on how they work, how we are using them and how you can too.

## How did we get started?

We started to get curious about Jekyll, GitHub and GitHub pages after finding the Peer 2 Peer University [Course-in-a-Box Jekyll template](http://howto.p2pu.org) while developing our project proposal back in the spring. After gaining some experience using Jekyll for another Baltimore Heritage project ([our ongoing research on the history of Baltimore's Civil Rights movement](http://baltimoreheritage.github.io/baltimore-civil-rights-heritage/about/), we feel ready to use these tools and an open-source approach for the Local Preservation School project. We just started work on our first Jekyll-based site for the Local Preservation School—an online course we are creating to teach volunteers and local historians how to research and write about historic places. It is rough around the edges but you can take a look at [Explore Baltimore Heritage 101](http://baltimoreheritage.github.io/explore-101/) right now.

These tools are exciting for a many reasons. They are **free**, **open-source** and **easy to learn** (thanks to a wealth of free online resources). Jekyll has many [attractive and user friendly themes](http://jekyllthemes.org/) that we can use to build a good looking website without being an expert in HTML or CSS. Finally, GitHub makes it easy to collaborate and it has a community of users that includes historians, educators and cultural institutions including:

- [Cooper Hewitt, Smithsonian Design Museum](https://github.com/cooperhewitt)
- [Indianapolis Museum of Art](https://github.com/IMAmuseum)
- [National Park Service](https://github.com/nationalparkservice)
- [Center for Public History and Digital Humanities, Cleveland State University](https://github.com/CPHDH/)

## What is GitHub?

Wikipedia is almost always a good place to begin:

>**GitHub** is a Web-based [Git](https://en.wikipedia.org/wiki/Git_(software) "Git (software)") repository hosting service. It offers all of the [distributed revision control](https://en.wikipedia.org/wiki/Distributed_revision_control "Distributed revision control") and [source code management](https://en.wikipedia.org/wiki/Source_code_management "Source code management") (SCM) functionality of [Git](https://en.wikipedia.org/wiki/Git_(software) "Git (software)") as well as adding its own features. Unlike Git, which is strictly a [command-line](https://en.wikipedia.org/wiki/Command-line "Command-line") tool, GitHub provides a [Web-based graphical interface](https://en.wikipedia.org/wiki/Web_application "Web application") and desktop as well as mobile integration. It also provides [access control](https://en.wikipedia.org/wiki/Access_control "Access control") and several collaboration features such as [bug tracking](https://en.wikipedia.org/wiki/Bug_tracking_system "Bug tracking system"), [feature requests](https://en.wikipedia.org/wiki/Software_feature "Software feature"), [task management](https://en.wikipedia.org/wiki/Task_management "Task management"), and [wikis](https://en.wikipedia.org/wiki/Wiki "Wiki") for every project.

In the past few years, GitHub has grown to become the most popular host for source code in the world with a reported 9 million users. Wired Magazine wrote [a long profile on GitHub in 2013](http://www.wired.com/2013/09/github-for-anything/) that noted how a tool originally developed for software engineers started finding a broader audience:

>The folks at GitHub think this style of cooperative tinkering represents the future: a world where anyone can suggest improvements to almost any project, and all fixes can be discussed like Facebook posts. “The open, collaborative workflow we have created for software development is so appealing that it’s gaining traction for non-software projects that require significant collaboration,” says GitHub cofounder and CEO Tom Preston-Werner.

Here are some tutorials and resources we used to get started working with GitHub:

- [How to use GitHub and the terminal: a guide](https://18f.gsa.gov/2015/03/03/how-to-use-github-and-the-terminal-a-guide/) by Melody Kramer, 18F
- [GitHub For Beginners: Don't Get Scared, Get Started - Part 1](http://readwrite.com/2013/09/30/understanding-github-a-journey-for-beginners-part-1), [Part 2](http://readwrite.com/2013/10/02/github-for-beginners-part-2) by Lauren Orsini, readwrite
- [Getting Started With a GitHub Repository](http://chronicle.com/blogs/profhacker/getting-started-with-a-github-repository/47393) by Konrad M. Lawson, ProfHacker
- [Hello World](https://guides.github.com/activities/hello-world/) - GitHub Guide
- [Getting Started with GitHub Desktop](https://help.github.com/desktop/guides/getting-started/) - GitHub Guide
- [Got 15 minutes and want to learn Git?](https://try.github.io/levels/1/challenges/1) - a command-line tutorial from GitHub

## What is Jekyll?

For the answer to this question, we went [right to the source](http://jekyllrb.com/docs/home/):

>Jekyll is a simple, blog-aware, static site generator. It takes a template directory containing raw text files in various formats, runs it through a converter (like Markdown) and our Liquid renderer, and spits out a complete, ready-to-publish static website suitable for serving with your favorite web server. Jekyll also happens to be the engine behind GitHub Pages, which means you can use Jekyll to host your project’s page, blog, or website from GitHub’s servers for free.

Jekyll is well-documented but a bit intimidating for anyone who is more accustomed to editing a website through a content management system (CMS) like WordPress or a website builder like SquareSpace. Here are some tutorials and resources we found helpful:

- [Build A Blog With Jekyll And GitHub Pages](http://www.smashingmagazine.com/2014/08/build-blog-jekyll-github-pages/) by Barry Clark, Smashing Magazine
- [Yes We Jekyll](http://yeswejekyll.com/)
- [Run Jekyll on Windows](http://jekyll-windows.juthilo.com/): A step-by-step guide to setting up Jekyll on Windows by [@juthilo](https://twitter.com/juthilo).

## What is GitHub pages?

GitHub explains Pages [this way](https://help.github.com/articles/what-are-github-pages/):

>GitHub Pages are public webpages hosted and published through our site. You can create and publish GitHub Pages online using the Automatic Page Generator. If you prefer to work locally, you can use the GitHub Desktop or the command line.

GitHub Pages works well with another tool—[Prose.io](http://prose.io/#about)—that makes editing Jekyll-based websites easy to do in your web browser:

>Prose provides a beatifully simple content authoring environment for CMS-free websites. It's a web-based interface for managing content on GitHub. Use it to create, edit, and delete files, and save your changes directly to GitHub.

Using GitHub pages also makes it easy to use an existing Jekyll site as a template for your own site. By forking the original code and making a few small tweaks, you can have a site up and running in minutes. This is exactly the idea behind the P2PU Course-in-a-box template. Here is how we can use GitHub pages and the Jekyll template to [create a course](http://howto.p2pu.org/modules/start/create-your-course/):

>You're going to be building your course in GitHub. GitHub is web-based repository hosting service, which allows you to manage your code, and see revisions you've made via a good-looking, easy-to-use web interface. It's newbie-friendly, and a great collaboration tool, which is why we're using it for Course in a Box.
>The flagship functionality of GitHub is “forking” – copying a repository from one users account to another. This is what we will do with this repository of content. By forking repository you will copy the Course in a Box content from our repository, and modify it under your own account and then publish with your own link to it.
>Your course will live on GitHub (so you don't need to worry about hosting) and you'll do all the building work there, but you'll be able to view it as a web page.

We're putting together a list of all of the changes we are making to the template as we build our [Explore Baltimore Heritage 101 course](http://baltimoreheritage.github.io/explore-101/) as a reference for anyone else who wants to use the template in the future. These changes include customizing the footer and header menus, as well as swapping out the existing course modules and lessons for our new modules and lessons.

## A few more tools we are excited about

Jekyll is great for publishing simple websites but there are many other helpful tools available that work well for open-source projects. Here are a few more tools we are learning how to use and that you'll probably see us mention in future updates:

**[Tik Tok](http://datanews.github.io/tik-tok/)**

>Tik Tok is a Javascript tool to easily create beautiful, simple, mobile-friendly, vertical timelines.

**[geojson.io](http://geojson.io)**

> geojson.io is a quick, simple tool for creating, viewing, and sharing maps. geojson.io is named after GeoJSON, an open source data format, and it supports GeoJSON in all ways - but also accepts KML, GPX, CSV, TopoJSON, and other formats.

**[editdata.org](http://editdata.org)**

>editdata.org is a simple version of flatsheet, a tool for curating data as editorial content.

Do you have suggestions for other tools or resources we should look at? [Please share your ideas!](http://localpreservation.github.io/contact/) If you use this guide to get started with GitHub, Jekyll or GitHub Pages, we'd love to hear about your experience. Share your feedback on Twitter with the hastag [#localpast](https://twitter.com/search?q=%23localpast) or say hello to me – [@elipousson](http://twitter.com/elipousson).

_P.S. We didn't really discuss open educational resources in this post but we'll make sure to post again with more information soon. Check out our new background page on [open education]({{ site.url}}/open-education/) for a preview of what we are working on._
