---
id: 1957
title: Remove Shrinking Header in Genesis Centric Pro
date: 2014-03-24T10:24:54+00:00
author: Eli Overbey
layout: post
guid: http://elioverbey.net/?p=1957
permalink: /remove-shrinking-header-in-genesis-centric-pro/
fsb_social_facebook:
  - "0"
  - "0"
  - "0"
  - "0"
fsb_social_google:
  - "2"
  - "2"
  - "2"
  - "2"
fsb_social_linkedin:
  - "0"
  - "0"
  - "0"
  - "0"
fsb_social_twitter:
  - "0"
  - "0"
  - "0"
  - "0"
dsq_thread_id:
  - "2692749220"
  - "2692749220"
categories:
  - SEO
  - Web Design
---
This is a hack but it worked for me. Just replace the code below with the code in /js/global.js. The only difference is that I remove the “shrink” class in line 7.

Editing the code below will remove the shrinking header on the Centric Pro theme.



Then, it’s just simple css:



I tried this and it works as well. It just removes the shrinking action completely.