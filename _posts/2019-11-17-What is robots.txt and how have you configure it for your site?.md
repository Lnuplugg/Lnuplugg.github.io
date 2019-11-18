---
layout: post
title:  "What is robots.txt and how have you configure it for your site?"
date:   2019-11-17 20:58:58 +0100
categories: Blog
author: Mikael
permalink: /blog/what-is-robots-txt-and-how-have-you-configured-it-for-your-site
comments: true
---

## What is robots.txt and how have you configure it for your site?
The pupose of the robots.txt file is to tell the search engine crawlers and other webcrawlers
what files and folders they should avoid or follow. 
For example disallow crawling to login/admin pages to
avoid them being indexed in the search engines(might still happen). I have used "Disallow: /" which tells all crawlers
to avoid crawling the entire site.

## What is humans.txt and how have you configured it for your site?
I created it like with the robots.txt file, all lower case and in UTF-8.
Added the base template from humans.txt.org and added some parts and removed others that didn't the description of the project.
For example added the standards and software used in the creation process.

## How did you implement comments to blog posts?
I used Disqus and the code provided in their website. I created a seperate file in _includes and minima theme already had a "if block" to handle the code.

## What is Open Graph and how do you make use of it?
Using the The Open Graph protocol. I added a separate html file in the _includes folder with the code from the website specifically made for Jekyll.
Then checked the source code that everything was correct. I used type, image, description, site name, url.
