---
id: 1005
title: 'Add Slider to the Home Page of Minimum Pro Theme v.3.0 &#8211; Updated!'
date: 2013-10-05T19:13:38+00:00
author: Eli Overbey
layout: post
guid: http://elioverbey.net/?p=1005
permalink: /add-slider-home-page-minimum-pro-theme-v-3-0/
ratings_average:
  - "5"
  - "5"
  - "5"
  - "5"
ratings_score:
  - "5"
  - "5"
  - "5"
  - "5"
ratings_users:
  - "1"
  - "1"
  - "1"
  - "1"
fsb_social_twitter:
  - "0"
  - "0"
  - "0"
  - "0"
fsb_social_google:
  - "0"
  - "0"
  - "0"
  - "0"
fsb_social_facebook:
  - "0"
  - "0"
  - "0"
  - "0"
fsb_social_pinterest:
  - "0"
  - "0"
  - "0"
  - "0"
fsb_social_linkedin:
  - "0"
  - "0"
  - "0"
  - "0"
dsq_thread_id:
  - "2692423721"
  - "2692423721"
categories:
  - Web Design
---
StudioPress just released Minimum Pro Theme to Genesis Framework users.

I recently wanted to substitute a slider on the homepage instead of a static featured image. I’ll post the solution here in case you’d like to try it yourself. (btw &#8211; just giving a thanks &#8211; [Ted](http://www.studiopress.com/forums/users/tedvieira/) helped me out a ton!)

![Thriveworks](/images/wp-uploads/2013/08/Thrivewors-e1377803909306.jpg)

**CREATE A NEW WIDGET AREA**

The featured image used in the Minimum Pro Theme demo is hard-coded into funtions.php. We’re going to change this by creating a new widget area for our home page slider.

To register a new widget area, drop the following into your functions.php (between header and tagline widgets on homepage).



After adding this code to your theme and saving it, you can go to Appearance > Widgets and see your new widget area. You can drop widgets in there and add content all you like, but it won’t show up on your home page until we tell it to do so.

**ADD THE NEW WIDGET AREA TO THE HOME PAGE**

Add this to functions.php:



**Then REMOVE (on functions.php):**

Removed:



And on front-page.php, remove or comment out:



Done!