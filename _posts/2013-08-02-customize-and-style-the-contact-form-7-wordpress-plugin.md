---
id: 819
title: Customize and Style the Contact Form 7 WordPress Plugin
date: 2013-08-02T03:24:36+00:00
author: Eli Overbey
layout: post
guid: http://elioverbey.net/?p=819
permalink: /customize-and-style-the-contact-form-7-wordpress-plugin/
fsb_social_twitter:
  - "0"
  - "0"
  - "0"
  - "0"
  - "0"
  - "0"
fsb_social_google:
  - "0"
  - "0"
  - "0"
  - "0"
  - "0"
  - "0"
fsb_social_facebook:
  - "0"
  - "0"
  - "0"
  - "0"
  - "0"
  - "0"
fsb_social_pinterest:
  - "1"
  - "1"
  - "1"
  - "1"
  - "1"
  - "1"
fsb_social_linkedin:
  - "0"
  - "0"
  - "0"
  - "0"
  - "0"
  - "0"
dsq_thread_id:
  - "2690243676"
  - "2690243676"
  - "2690243676"
ninja_forms_form:
  - "0"
categories:
  - Web Design
---
Contact 7 form is one of my favorite plugins for WP &#8211; in fact &#8211; I use it on all the sites I run. Gravity forms is an awesome alternative, but since it is free, and runs on WP Multisite, I stick with contact form 7. The only problem: Contact Form 7 needs customization and style. This tutorial will teach you how to create a contact form that goes from (the default css):

[<img class="alignnone  wp-image-820" src="/images/wp-uploads/2013/08/Screen-Shot-2013-08-01-at-11.18.05-PM.png" alt="Contact Form 7 Customize and Style" width="577" height="500" />](/images/wp-uploads/2013/08/Screen-Shot-2013-08-01-at-11.18.05-PM.png)

To something a little more eye catching. This tutorial will add a bit of style and color to Contact Form 7. Feel free to change the colors in the process:

[<img class="alignnone size-full wp-image-881" src="/images/wp-uploads/2013/08/Screen-Shot-2013-08-09-at-2.22.50-PM.png" alt="Contact Form 7 Customized" width="623" height="536" />](/images/wp-uploads/2013/08/Screen-Shot-2013-08-09-at-2.22.50-PM.png)

Let&#8217;s begin! First, you need to download the Contact Form 7 plugin.

### Installing Contact Form 7

Installing the WordPress plugin could not be easier. Always make sure you have a recent backup of your database before you install or update anything on your site (I say this, but hardly every do it). After you backup you site, here’s how to install Contact Form 7.

  1. Log-in to Your WordPress website.
  2. Under “Plugins” click on “Add New”.
  3. Under ”Search” enter “Contact Form 7” .
  4. After the page reloads Click on “Install Now” under Contact Form 7.
  5. Click “OK” when you get the “Are You Sure” alert.
  6. After the plugin downloads click “Activate Plugin”.
  7. You’ll now have a “Contact” tab in the menu on the left side of the screen.
  8. Click the “Contact” tab.

We are going to be working with the default contact form. If you need to add fields, that is fine &#8212; just make sure they are in the same class.

### Customizing the Contact Form 7 Plugin

Here’s the code to get it looking good.

There are a few things you need to keep in mind.

  1. You may need to adjust the width of the input and textarea. Every theme is different.
  2. Make sure you change the border color of the input, textarea, and .text to match your site.

### The HTML

The default HTML for Contact Form 7 is below:



**We want to change that too:** Below, are we are doing is removing the Titles. We removed &#8220;Your Name (required)&#8221;, &#8220;Your Email (required)&#8221;, &#8220;Subject&#8221;, and &#8220;Message&#8221;. It is okay to remove those. We are going to add text inside the input boxes. Contact Form 7 calls this &#8220;placeholder text&#8221; &#8211; but we will get to that shortly.



Now, if you are following along, your form should look something like this:

[<img class="alignnone  wp-image-843" src="/images/wp-uploads/2013/08/Screen-Shot-2013-08-02-at-12.11.34-AM.png" alt="Contact Form 7 Styled" width="570" height="420" />](/images/wp-uploads/2013/08/Screen-Shot-2013-08-02-at-12.11.34-AM.png)

You will notice that all of the titles have been removed. We did this to streamline everything. When working with customers, the shorter the CTA (the form), the better. If there are unneeded breakspaces and text, remove them.

Next up: Add the placeholders. The placeholders are the text that go inside the input boxes. They are &#8220;suggestions&#8221;. If you are confused, just look down below and it will make more sense.



You will notice in this step all we did was add placeholder text. Placeholder text goes inside the input areas and give hints or suggestions. These placeholders replace the need for &#8220;Titles&#8221;.

[<img class="alignnone  wp-image-846" src="/images/wp-uploads/2013/08/Screen-Shot-2013-08-02-at-12.19.41-AM.png" alt="Contact Form 7" width="573" height="425" />](/images/wp-uploads/2013/08/Screen-Shot-2013-08-02-at-12.19.41-AM.png)

At this point, we are ready to start styling the form. Don&#8217;t worry if your form doesn&#8217;t look just like mine (each theme has different default stylings)! We will get to that in the next step. The important part is that we have the structure down.

### The CSS

Just add the following: