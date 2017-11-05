---
id: 2046
title: Style the Genesis Author Box to Look Like Twitter Bio
date: 2014-03-23T01:04:13+00:00
author: Eli Overbey
layout: post
guid: http://elioverbey.net/?p=2046
permalink: /style-genesis-author-box-look-like-twitter-bio/
fsb_social_pinterest:
  - "0"
  - "0"
  - "0"
  - "0"
fsb_social_facebook:
  - "0"
  - "0"
  - "0"
  - "0"
fsb_social_google:
  - "1"
  - "1"
  - "1"
  - "1"
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
fsb_social_twitter:
  - "1"
  - "1"
  - "1"
  - "1"
dsq_thread_id:
  - "2693649608"
  - "2693649608"
ninja_forms_form:
  - "0"
categories:
  - SEO
  - Web Design
---
I&#8217;ve worked with Genesis for almost two years now, and I think the two weakest styled parts of any Genesis Child Themes are the comments and the author box. **The author box says a lot about you.** Might as well make it look nice.

Today, I want to go over how you can style your Genesis Author Box to look like your Twitter Bio. Below is a screenshot of what the end product will be.

<img class="aligncenter size-full wp-image-2047" alt="Genesis Author Box" src="/images/wp-uploads/2014/03/Screen-Shot-2014-03-22-at-10.52.48-PM.png" width="699" height="320" />

To make your author box look like your twitter profile, you&#8217;ll need to follow these three _simple_ steps:

  1. Set up your user profile in WordPress
  2. Add author box filters to functions.php
  3. Style

## Set Up Your User Profile in WordPress

_*If you have not set up your profile yet, s_tart off by going to Users &#8211;>Edit. _If you have set up your profile, proceed to step 2._

For this example, you don&#8217;t need to fill in all the data, just:

  * your email,
  * name,
  * display name, and
  * biography

When you are filling out your email, make sure it is the email with a linked gravatar (that is how you will get your picture). If you want it to be your exact Twitter profile photo, update your gravatar photo to match (visit [Gravatar.com](http://gravatar.com)).

After you enter your name, make sure you change the drop down for &#8220;Display name publicly as: to &#8221; &#8220;First Name Last Name&#8221;. Otherwise, your username will overwrite your full name.

Finally, enter your Twitter biography. _Do keep your biography under 160 characters._

## Next, Add Author Box to Functions.php

Add the code below to _functions.php: _



_*What are these functions doing? First, you are adding the author box to your theme (if you don&#8217;t have it already). Secondly, you are changing the author-box gravatar to 73 pixels (the official Twitter size). Finally, you are removing the word &#8220;About&#8221; from the title. Now, the title will only grab your name._

## Finally, Style The Author Box

Now, it&#8217;s time to style. You can copy and paste the gist below into your style.css file. Make sure you place it at the end to overwrite the existing styles.

Lastly, you&#8217;ll need the background image. I created this, and you can modify and use it in anyway. No attribution. Feel free to drag the photo to the desktop and save. *Just make sure you keep the name the same as in your css (twitter-background.jpg). **Upload the file to your images folder.**

<img class="aligncenter size-full wp-image-2055" alt="twitter-background" src="/images/wp-uploads/2014/03/twitter-background.jpg" width="520" height="260" />

There you have it. A Genesis Framework Author Box that looks like your twitter profile. If you have any questions, just add them in the comments. I respond quickly.