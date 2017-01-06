---
layout: single
title: "About our Resources"
excerpt: "How the Local Preservation School makes resources accessible and available to educators and learners."
permalink: /resources/about/
---

The Local Preservation School resource collection is a directory of websites, publications, and online tools for people interested in learning about or teaching historic preservation. The resources cover a broad range of topics.

They include both:

- online resources developed or adapted for publication by the Local Preservation School project;
- publications or websites we found useful and thought you would too.

We published some of our resources (e.g. the National Park Service brief on [architectural investigation](/resources/architectural-investigation/)) directly on this website. Other resources (e.g. the City Lore Toolkit on [advocacy for historic places](https://localpreservation.github.io/placematters/)) are published on stand-alone websites. Each resource is described with general criteria and using criteria that are especially useful for educators and learners.

## Resource information

Our directory describes each resource using these criteria:

- Publisher(s)
- Creator(s)
- License
- Publication date (earliest)
- Modification date (most recent)
- Resource state
- Resource repository (if available)
- Based on URL (if available)

### Resource state

We use badges to show the state of each project we're developing or including in the directory. These badges include:

- ![state: brainstorming](https://img.shields.io/badge/status-brainstorming-lightgrey.svg)
- ![state: needs work](https://img.shields.io/badge/status-needs%20work-red.svg)
- ![state: building/designing](https://img.shields.io/badge/status-building%2fdesigning-orange.svg)
- ![state: experimental](https://img.shields.io/badge/status-experimental-yellow.svg)
- ![state: ready](https://img.shields.io/badge/status-ready-brightgreen.svg)  

## Educational information

In addition to the general information, resources are also described with criteria useful for educators and learners. These descriptions are based in part on the [Learning Resource Metadata Initiative](http://lrmi.dublincore.net/lrmi-schema/) standards.

- Topics
- Difficulty
- Audience
- Educational Use
- Type of Interactivity
- Type of Resource

### Difficulty

We try to connect learners and educators with resources that are appropriate for their experience and background by noting the difficulty for each resource:

- Beginner
- Intermediate
- Advanced

### Topics

All of the resources are categorized by broad topics including:  

{% for topic in site.data.topics %}
- **{{ topic.name }}:** {{ topic.description }}
{% endfor %}

### Audience

The audience for a resource are the people for whom the resource was created or the people who we think are likely to find the resource useful. We've identified our key audiences by role – you may fit into one audience or more than one:

{% for audience in site.data.audiences %}
- **{{ audience.name }}:** {{ audience.description }}
{% endfor %}

 We do not break down audiences by age or grade level in detail. In general, our resources may be useful and accessible to high school students, college students, as well as adult learners. Only a few of our resources are designed for middle school or elementary school students.

### Educational Use

Potential educational uses for resource in this collection include:

- Self-guided learning
- Board and volunteer trainings
- Government and nonprofit staff trainings
- Community workshops
- High school and undergraduate college courses

Learn more about the potential educational uses of our resources with our [guide for educators](http://localpreservation.github.io/teach/).

### Type of Interactivity

The type of interactivity is the mode of learning supported by the educational resource including:

- active
- expositive
- mixed

Most of the resources in our collection are expositive. Some are mixed and we plan to add interactive elements to any resources we publish.

### Type of Resource

Many of our resources have been adapted from printed publications.
