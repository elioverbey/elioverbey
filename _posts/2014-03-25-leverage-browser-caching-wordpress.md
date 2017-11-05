---
id: 2054
title: Leverage Browser Caching in WordPress
date: 2014-03-25T04:27:05+00:00
author: Eli Overbey
layout: post
guid: http://elioverbey.net/?p=2054
permalink: /leverage-browser-caching-wordpress/
fsb_social_google:
  - "2"
  - "2"
  - "2"
  - "2"
fsb_social_twitter:
  - "0"
  - "0"
  - "0"
  - "0"
fsb_show_social:
  - "0"
  - "0"
  - "0"
  - "0"
fsb_social_linkedin:
  - "0"
  - "0"
  - "0"
  - "0"
fsb_social_facebook:
  - "0"
  - "0"
  - "0"
  - "0"
dsq_thread_id:
  - "2690857290"
  - "2690857290"
ninja_forms_form:
  - "0"
categories:
  - SEO
---
Have you ever gone to Pingdom Tools and received a near zero score on &#8220;leveraging browser caching&#8221;? This is really an easy fix that you can implement on your own blog.

## What is Browser Caching?

Every time a browser loads a webpage it has to download all the web files to properly display the page. This includes all the HTML, CSS, javascript and images.

Leveraging browser caching will help decrease your page load time. It stores some of the files locally in the user&#8217;s browser. Thus, the first visit nothing changes &#8211; same load speed, however when that user **_revisits_** your website, refreshes the page, or goes to a new page on your site, they already have some of the files they need locally &#8211; **reducing page load tome**.

The Great News? Decreased page load times.

## Edit the .htaccess file

Find your .htaccess file in the root of your domain. By default, this file is a hidden but should show up in FTP. If you are using Coda or a similar text editor, click View &#8211;> Show Invisible Files.

Paste this in your .htaccess file:



Now, head over to Pingdom and check out your leverage browser caching score.