---
id: 2438
title: An In-Depth Inbound Marketing Audit of Buffer
date: 2014-06-12T00:00:24+00:00
author: Eli Overbey
layout: post
guid: http://elioverbey.net/?p=2438
permalink: /inbound-marketing-audit-buffer/
dsq_thread_id:
  - 2719778253
  - 2719778253
ninja_forms_form:
  - 0
categories:
  - Inbound Marketing
  - SEO
---
Buffer’s people have spent hours creating a quality product and interacting with their customers. If you’ve ever replied to a comment on one of their posts or reached out to them personally, you know that Buffer is built on transparency and intentionality.

And if you&#8217;ve ever been as busy as Buffer &#8211; shipping great apps, creating quality content, and engaging with customers 24/7 &#8211; you know that monitoring your _own_ website for optimization and conversion can get put on the bottom of the list. In Buffer&#8217;s case &#8211; their content marketer, Courtney, has done a great job of preventing that, but this audit will provide a third party look into Buffer&#8217;s inbound strategy.

In this post, I’ve put together a detailed, technical Inbound Marketing Audit for Buffer. This audit is widespread and comprehensive, covering a wide range of Inbound Marketing Tactics (e.g., optimization, calls-to-action, landing pages, forms, contacts, emails, etc&#8230;). Please feel free to use this as a template or example when conducting inbound / seo audits of  your own. But before the inbound marketing audit, let’s cover the basics…

### Why Conduct an Inbound Marketing Audit of Buffer?

**First**, Buffer does not have an inbound marketer / SEO person on their staff. They do have a content marketer, but content marketers normally focus on one thing: content. <a href="http://blog.bufferapp.com/author/courtney" target="_blank">Courtney Seiter</a> heads up Buffer&#8217;s content marketing, and does an excellent job &#8211; but in this audit, I hope to cover content marketing and then go _beyond_ it to the technical implementation.

With inbound marketing being fairly new (around 2006) and SEO with a blemished name, I hope this audit validates those fields. Even more, in the future, I&#8217;d love to see Buffer create room for inbound marketing due to its impact on their business.

I also hope this audit helps Buffer succeed in their inbound marketing. Buffer&#8217;s company culture, product, and practice sets a model _worth_ growing.

**Second,** I have never seen a complete inbound marketing audit (probably because of the relative newness of inbound marketing.) I&#8217;ve read countless pieces on SEO, Social Media, Landing Pages, etc&#8230; but I&#8217;ve never read an audit that ties all the pieces together. I hope that by stringing all the pieces of inbound marketing together, this audit could be useful for others as a template on which to conduct their businesses.

## Who is Buffer?

<a href="https://bufferapp.com" target="_blank"><img class="alignnone size-large wp-image-2460" src="/images/wp-uploads/2014/06/Buffer-A-better-way-to-share-on-social-media-2014-05-31-19-23-07-1024x589.png" alt="Buffer - A better way to share on social media 2014-05-31 19-23-07" width="1024" height="589" /></a>

Founded by <a href="http://joel.is" target="_blank">Joel Gascoigne </a>and <a href="http://leostartsup.com/" target="_blank">Leo Widrich</a>, Buffer’s goal is to make it easy for individuals and companies to manage multiple social media accounts at once. Buffer allows you to post and maintain content – articles, photos, links, etc. – on different profiles and platforms; you can even set up a specific time and date for them to release your content.

Their employees work from all over the world – Buffer believes that you should live in the place that makes you happiest and allows you to do your best work. Their goal is satisfaction for the customer and the employee.

#### Disclaimer

Before the audit, it’s important to point out that I am not affiliated with Buffer in _any way_, which means that I lack direct access to their site’s analytics, webmaster tools, and content management system (CMS). In a typical audit, I would begin by sifting through the data and then narrowing in on problem issues.

In this inbound audit, I will be relying heavily on third-party data. I hope you’ll forgive any inaccurate observations based on the information from the third parties – Searchmetrics, Ahrefs, SEMrush, Moz, etc (they are awesome tools, don’t get me wrong – they are just being used in a third party scenario).

I will also be using research and stats from Buffer themselves. Buffer publishes many of their stats and website numbers online at <a href="http://open.bufferapp.com" target="_blank">open.bufferapp.com</a>. With those disclaimers out of the way, let’s get down to business…

_*If you have any questions, just tweet me @elioverbey._

## Table of Contents

Since this post will be extremely long &#8211; here is a detailed navigation to help you understand where you are throughout this audit. As you will see, this audit will spend a majority of time on optimization (top of funnel), but lower areas of the funnel will be covered as well. The audit will work through four main areas as seen below: Optimization (Attract), Conversion, Customers, and Delight.

  * **[Inbound Marketing](#inboundmarketing)**
  * **[Optimization / Attract](#attract)** 
      * [Search Visibility](#searchvisibility)
      * [Index-ability / Buffer Web Structure](#indexability) 
          * [Robots](#robots)
          * [Robots Meta Tag](#robotsmeta)
          * [XML Sitemap](#sitemap)
      * <a href="#access" target="_blank">Accessibility</a> 
          * [Performance](#performance)
          * [Site Architecture](#architecture)
          * [Usability](#usability) 
              * [Click Depth](#clickdepth)
      * [On Page Factors](#onpage) 
          * [HTML Markup](#markup) 
              * [Structured Data](#schema)
              * [Meta Descriptions](#metadescription)
              * [Head Tags](#headtags) 
                  * [Open Graph](#opengraph)
                  * [Twitter Cards](#twittercards)
          * [Titles](#titles)
          * [URLs](#urls)
          * [Keywords](#keywords)
          * [Images](#images)
          * [Content Duplication](#duplicate)
      * [Off Page Factors](#offpage) 
          * [Backlinks](#backlinks) 
              * [302 Redirects](#302)
              * [Backlink Distribution](#backlinkd)
              * [Backlink Source](#backlinksource)
              * [Anchor Link Analysis](#anchortext)
              * [No Follow Links](#nofollow)
              * [Image Links](#imagelinks)
  * **[Conversion / Leads](#conversion)** 
      * [Calls to Action](#cta)
      * [Landing Pages](#landingpages)
      * [Forms](#forms)
  * [**Close / Customers**](#close) 
      * [Contacts](#Contacts)
      * [Email](#Contacts)
  * [**Delight**](#delight) 
      * [Social Media](#SM)
      * [Engaging Content](#engaging)
  * [**Summary**](#summary)

## Inbound Marketing {#inboundmarketing}

In its most basic form:

> Inbound marketing focuses on earning, not buying, a person&#8217;s attention &#8211; <a href="http://www.hubspot.com/company/management/brian-halligan" target="_blank">Brian Halligan</a>

The principle of inbound marketing has been around for years, but the term has been coined by <a href="http://hubspot.com" target="_blank">HubSpot</a> (<a href="http://www.hubspot.com/company/management/dharmesh-shah" target="_blank">Dharmesh</a> has brilliantly positioned his company with this money keyword). Inbound Marketing focuses on creating interesting and relevant content that naturally pulls people into your company and your product. By aligning yourself with your customers&#8217; interests, you will attract traffic that will eventually turn into paying customers (<a href="http://www.hubspot.com/rachelgoodman" target="_blank">HubSpot &#8211; Rachel Goodman</a>).

As the graph below depicts (<a href="http://www.hubspot.com/inbound-marketing" target="_blank">via HubSpot</a>), inbound marketing exist in stages (or a funnel). As this audit continues on, you&#8217;ll notice how the funnel naturally works.
  
<a href="http://www.hubspot.com/inbound-marketing" target="_blank"><img class="alignnone size-large wp-image-2447" src="/images/wp-uploads/2014/06/HubSpot-What-is-Inbound-Marketing-2014-05-29-21-51-37-1024x419.png" alt="HubSpot | What is Inbound Marketing? 2014-05-29 21-51-37" width="1024" height="419" /></a>

## Optimization / Attract {#attract}

The first step in inbound marketing / SEO is attracting the right audience. Content is the single best way to attract new visitors to your website. In order to be found by the right prospective customers, _Buffer must not only create optimized content, but foster an environment in which content can thrive. _

### Search Visibility {#searchvisibility}

In order to set the framework for the entire audit, it’s important to <a href="https://www.distilled.net/blog/seo/4-signs-you-should-invest-in-seo-now/" target="_blank">analyze the site’s performance</a>. When looking at Buffer’s traffic, there are 3 important questions:

  * Is the traffic growing?
  * Has the site been penalized?
  * What is the percentage of organic traffic?

Finding accurate third party data is incredibly difficult, but <a href="http://open.bufferapp.com" target="_blank">Buffer posts Google Analytics traffic data monthly</a>. They do not post traffic to bufferapp.com (just the subdomain blogs). Technically, that is all we will need for this audit &#8211; as you can see below, Buffer&#8217;s traffic declined this past month:

<a href="http://open.bufferapp.com/may-buffer-content-marketing-report/" target="_blank"><img class="alignnone size-full wp-image-2680" src="/images/wp-uploads/2014/06/Screen-Shot-2014-06-02-at-5.19.27-PM.png" alt="Buffer Traffic" width="907" height="237" /></a>This is not too alarming, as Memorial Day is known to lower traffic. Overall, blog.bufferapp experienced:

  * 679,021 unique visitors (-6.9% from last month)
  * 908,658 total visits (-5.5%)
  * 1,154,690 pageviews (-3.2%)

Additionally, the organic referral traffic was down as well (down from 33.9% to 33.25%):

<a href="http://open.bufferapp.com/may-buffer-content-marketing-report/" target="_blank"><img class="alignnone size-full wp-image-2682" src="/images/wp-uploads/2014/06/Referrals-for-May1.png" alt="Referrals-for-May1" width="799" height="417" /></a>

The open blog experienced a growth, but as you can see from the graph below, the articles were not growing traffic at the end of the month (perhaps due to the engineering content).

<a href="http://open.bufferapp.com/may-buffer-content-marketing-report/" target="_blank"><img class="alignnone size-full wp-image-2685" src="/images/wp-uploads/2014/06/Screen-Shot-2014-06-05-at-6.11.09-PM.png" alt="Open Blog Traffic" width="740" height="217" /></a>

In any regard, Buffer&#8217;s organic traffic looks excellent. One very positive thing to note: in the last 6 months, Buffer does not seem to have been hurt by any penalties from Google. Again, you cannot trust the graph above because it contains all traffic and not just organic, but other graphs from <a href="http://suite.searchmetrics.com/en/research/domains/organic/?url=bufferapp.com&cc=US" target="_blank">Search Metrics show a similar pattern.</a>

I&#8217;d highly suggest Buffer monitor their organic traffic. <a href="http://open.bufferapp.com/may-buffer-content-marketing-report/" target="_blank">In a recent post, they stated</a>:

> Is traffic the best way to measure whether we’re effectively reaching out goal? We don’t believe it is, so we’ll be emphasizing it less as a metric and focusing more on growing email subscribers as our main metric.

I do agree with Buffer in this aspect; however, traffic will be one of their most important components in increasing email signups. Buffer should keep a close eye on their organic and referral traffic. During the audit, there has been a strong correlation between traffic growth and email signups.

### Indexability / Buffer Web Structure {#indexability}

In order to understand this audit, you need to understand how Buffer is set up. At first glance, you&#8217;ll notice that Buffer website is constructed in silos.

The page count was derived using two tools: Xenu Link Sleuth and a propriety tool. I compared the two findings, removed duplicates, and was left with the total below.

  * bufferapp.com &#8211; <span style="color: #339966;">27 pages </span> 
      * bufferapp.com/add &#8211; <span style="color: #339966;">61 Pages</span>
      * bufferapp.com/developers &#8211; <span style="color: #339966;">14 pages</span>
      * bufferapp.com/faq &#8211; <span style="color: #339966;">3 pages</span>
      * bufferapp.com/guides &#8211; <span style="color: #339966;">8 pages</span>
      * bufferapp.com/oauth &#8211; <span style="color: #339966;">7 pages</span>
      * bufferapp.com/weeklydigest <span style="color: #339966;">4 pages</span>
  * *api.bufferapp.com &#8211; <span style="color: #339966;">3 pages</span>
  * status.bufferapp.com &#8211; <span style="color: #339966;">1 page</span> 
      * status.bufferapp.com/history &#8211; <span style="color: #339966;">1 page</span>
      * status.bufferapp.com/incidents &#8211; <span style="color: #339966;">3 pages</span>
  * jobs.bufferapp.com &#8211; <span style="color: #339966;">17 pages</span>
  * dev.bufferapp.com &#8211; <span style="color: #339966;">40 pages</span>
  * blog.bufferapp.com &#8211; <span style="color: #339966;">468 posts </span> 
      * blog.bufferapp.com/author &#8211; <span style="color: #339966;">61 pages</span>
      * blog.bufferapp.com/tag &#8211; <span style="color: #339966;">438 pages</span>
      * blog.bufferapp.com/category &#8211; <span style="color: #339966;">48 pages</span>
  * open.bufferapp.com &#8211; <span style="color: #339966;">94 posts </span> 
      * open.bufferapp.com/author &#8211; <span style="color: #339966;">16 pages</span>
      * open.bufferapp.com/tag &#8211; 2<span style="color: #339966;"> pages</span>
      * open.bufferapp.com/category &#8211; <span style="color: #339966;">19 pages</span>
  * happiness.bufferapp.com/ &#8211; <span style="color: #339966;">0 pages</span> at the root level 
      * happiness.bufferapp.com/ reports &#8211; <span style="color: #339966;">104 pages</span>
  * webinars.bufferapp.com &#8211; <span style="color: #339966;">3 pages</span> 
      * webinars.bufferapp.com/ gettingtoknowbuffer &#8211; <span style="color: #339966;">2 pages</span>
  * *email.bufferapp.com &#8211; <span style="color: #339966;">5 pages</span>

_An * (asterisk) indicates that the subdomain is blocked by the robots.txt._

As this audit was being written, Buffer created yet another subdomain &#8211; overflow.bufferapp.com. Overflow is a place for their engineers to blog.

  * *overflow.bufferapp.com &#8211; 12<span style="color: #339966;"> pages</span>

**For a total of 1,461 pages across all subdomains. **

As you glance at the site structure of Buffer, you begin to notice that their content is heavily separated and the only way to navigate from subdomain to subdomain (with the exception of a few in-text links) is the footer [Buffer does not have a top navigation].

<a href="http://blog.bufferapp.com/" target="_blank"><img class="alignnone size-large wp-image-2477" src="/images/wp-uploads/2014/06/Screen-Shot-2014-05-31-at-10.13.38-PM-1024x239.png" alt="Buffer Footer" width="1024" height="239" /></a>

#### The Case for Subdirectories (versus Subdomains)

A lot has been said about subdomains and subdirectories. Some companies, such as Hubspot, have placed their blog in a subdomain, ie, blog.hubspot.com. HubSpot&#8217;s reasoning for having the blog in a subdomain is:

> Many companies have their blog on a subdomain, and it seems to be starting to be somewhat of a standard. The search engines are treating subdomains more and more as just portions of the main website, so the SEO value for your blog is going to add to your main website domain. If you want your blog to be seen as part of your company, you should it this way (or the next way) &#8211; <a href="http://www.mikevolpe.com/" target="_blank">Mike Volpe</a>

Even <a href="http://www.youtube.com/watch?v=_MswMYk05tk" target="_blank">Matt Cutts</a> has said:

> [Subdomains and Subdirectories] are roughly equivalent. I would basically go with whichever one is easier for you in terms of configuration, your CMSs, [and] all that sort of stuff.

Although it seems like subdomains and subdirectories can be treated equally, Cutts uses very vague language; &#8220;roughly equivalent&#8221; is still not equivalent.

_Personally, based on research and countless other stories, I&#8217;d encourage Buffer to think about subdirectories._ Just because using a subdomain is becoming a standard, does not mean it the _best_ way. I&#8217;d highly suggest Buffer consider testing out _subdirectories_ over subdomains for 2 main reasons:

**First,** there is a correlation between pages on the root domain and higher rankings. According to Rand at Moz:

> I would still strongly urge folks to keep all content on a single subdomain. We recently were able to test this using a subdomain on Moz itself (when moving our beginner&#8217;s guide to SEO from guides.moz.com to the current URL http://moz.com/beginners-guide-to-seo). The results were astounding &#8211; rankings rose dramatically across the board for every keyword we tracked to the pages.

I&#8217;ve also had the opportunity to see other sites do the same &#8211; with a positive result. It may benefit Buffer to _consider_ moving some of their subdomains to subdirectories. I would not suggest they move the blog subdomain right away; instead, they could test their results with other, smaller subdomains, such as jobs, status, etc&#8230;

**Second,** _fewer _subdirectories tend to create a better user experience and flow.

As it stands, Buffer exist in silos. Although the subdirectories are clean, they do not make for the best of navigation.

For example, if you are a stranger to Buffer who clicks on a blog article from the search engines, you may _then_ navigate to the career section, and you may _then_ decide to sign up with Buffer. But, you will have technically visited 3_ different sites_. As a user, it&#8217;s easy to get lost in subdomains. Why not simplify the process?

##### There is an opportunity for Buffer to consolidate some of their subdomains.

If Buffer does indeed stick with subdomains, they should consider consolidating a few of them. Since no one is really sure how links pass among subdomains, having as few subdomains is advisable. A few of the blogs, such as open, webinars, and blog, could be consolidated into one subdomain.

I&#8217;d also suggest that Buffer test out how their links pass and how their content ranks by moving the job subdomain to bufferapp.com/jobs. Since most of the job traffic comes from referrals, it would be a harmless test.

##### Subdomain Links

Links will be mentioned in-depth below, but Buffer should consider how their links pass from root domain to subdomain. Since their root domain has over 12M links, and the other subdomains (such as the blog) only have 7k, Buffer should consider link equity.

Although it may be an &#8220;SEO myth&#8221; that links do not pass from root to subdomain, it still should weigh heavily on Buffer. Until Buffer has the opportunity to test link juice passing, they should take a path of least resistance.

If the root domain has over 12M links, they should take advantage of that. With only 27 pages on the root domain &#8211; and a lot of that content being less viewed, weaker content  &#8211; they should _at least_ think about the potential of combining the subdomain and root (with 301 &#8211; of course)_. Every time Buffer creates a new subdomain, they are potentially starting from scratch (or at least less). _A few months ago, Buffer moved its transparency articles (reports, revenue) off of blog.bufferapp.com to open.bufferapp.com.

__Wonder what the open.bufferapp blog would have done on the root domain (bufferapp.com)? _Open Blog has roughly 1,100 unique domains, as opposed to 50,000 unique domains on Bufferapp &#8211; or even 8,600 uniques on blog.bufferapp._

As far as we know, links may not pass through to subdomains._** Thus, now is an optimal time for Buffer to consider moving subdomains.**_

Even more, as this audit was being conducted, Buffer created another subdomain: overflow.bufferapp.com. This new subdomain gives a perfect case study of what happens when you create a subdomain. When Buffer created overflow.bufferapp.com &#8211; the blog for everything development related &#8211; they took the posts and moved them from open.bufferapp to overflow.bufferapp. As you can see below, the traction for the new subdomain is slow (the search query is from their most recent article on overflow.bufferapp):

<img class="alignnone size-large wp-image-2606" src="/images/wp-uploads/2014/06/overflow-bufferapp-1024x723.png" alt="overflow-bufferapp" width="1024" height="723" />As you can see from the chart above, the previous subdomain is ranking higher than the new subdomain (in fact, the new subdomain isn&#8217;t even ranking). This will eventually cause duplicate content issues as well. Buffer is essentially starting from scratch with this new subdomain. As evidenced in the chart below, the new domain has only 2 links.

<a href="https://ahrefs.com/site-explorer/overview/subdomains/?target=overflow.bufferapp.com%2F" target="_blank"><img class="alignnone size-large wp-image-2607" src="/images/wp-uploads/2014/06/ahrefs-buffer-1024x138.png" alt="ahrefs buffer" width="1024" height="138" /></a>In creating this new subdomain, Buffer left over 1,1o0 unique domains on open.bufferapp.com. Once again, Buffer is potentially starting from scratch with 2 unique referring domains. In this case, it would be prudent for Buffer to weigh the cost of creating a subdomain before they segment their articles.

#### The Case for Subdomains (versus Subdirectories)

##### Buffer&#8217;s Traffic is Growing on Subdomains

Buffer has always built their blogs on subdomains &#8211; and why mess with a good thing? In March &#8211; April of 2014, Buffer moved their transparency documents (open salaries, analytics, revenue, etc&#8230;) from blog.bufferapp to open.bufferapp. <a href="http://open.bufferapp.com/april-content-marketing-report/" target="_blank">According to analytics</a>:

<a href="http://open.bufferapp.com/april-content-marketing-report/" target="_blank"><img class="alignnone size-full wp-image-2549" src="/images/wp-uploads/2014/06/Screen-Shot-2014-05-01-at-2.16.17-PM.png" alt="Open Blog Analytics" width="908" height="484" /></a>

  * **March: **14,694 unique visitors &#8211; **April: **43,209 unique visitors (+203%)
  * **March: **20,158 total visits &#8211; **April: **56,399 total visits (+188% )
  * **March: **31,198 pageviews &#8211; **April: **79,929 pageviews (+157% )

By all means, the traffic seems to be growing, and as such, Buffer should not change a thing.

##### Buffer Can&#8217;t Build On Their Root Domain

**It is possible that **Buffer _can&#8217;t _build on the root domain in order to be &#8220;white hat&#8221; with their links. Have you ever clicked on the Buffer icon button when sharing an article and noticed what URL is in the pop up?

It&#8217;s https://bufferapp.com/add. This means that every website that has a Buffer icon is technically hosting a Buffer link (making their root domain backlink profile massive). Check out the image below (this website &#8220;openid.net&#8221; was picked because it was listed as a backlink from an analysis on <a href="http://majesticseo.com" target="_blank">Majestic</a>):

<a href="http://openid.net/2014/03/19/last-call-on-the-launch-and-the-move-to-mobile/" target="_blank"><img class="alignnone size-large wp-image-2547" src="/images/wp-uploads/2014/06/Buffer-Button-Link-1024x516.png" alt="Buffer Button Link" width="1024" height="516" /></a>I highlighted two things of note on this chart. First, you&#8217;ll notice the Buffer button on the left side of the screen. On the right side of the screen is the code behind that button. As you can see:

  * The Buffer Social Button is hyperlinked to http://bufferapp.com/add
  * The Hyperlink does _not _include a &#8220;nofollow&#8221;

Based on what&#8217;s happening here, since the Buffer social links are not naturally earned, but are rather accumulated from the growth of a social product, Buffer does not host their blogs on the root domain in order to avoid link penalties.

Again, that is speculation, but based on the culture of Buffer, this theory fits in line with their philosophy of openness and transparency.

Whether Buffer chooses to stay with subdomains or test subdirectories, they should always be aware of the data.

#### Robots {#robots}

A robots.txt file is used to restrict search engines from accessing specific sections of a site. Here is a copy of Buffer’s root domain Robots.txt file:

On their blogs, Buffer uses the another robots.txt file:

The records in the robots file politely ask all bots (bots used by all search engines are identified with the aterisk) to not crawl specific directories.

There are a few improvements that Buffer could make in the construction of their robots.txt.

**First**, Buffer should add sitemaps to the robots.txt. This will help the robots to index their pages.
  
**Second**, Buffer should consider blocking &#8216;/wp-content/plugins/&#8217;. Sometimes developers put links in their plugins.
  
**Third**, Buffer should rethink blocking /wp-includes/&#8217; in robots. There are better solutions for blocking robots than in the robots.txt file (ie, NOINDEX &#8211; discussed below).
  
**Fourth**, Buffer should remove the disallow of all directories on their new blog overflow.bufferapp.com:

In its current condition, the site cannot be indexed.

#### Robots Meta Tag {#robotsmeta}

Each page on a site can use a robots meta tag to tell search engine crawlers if they are allowed to index that page and follow its links. Very few of Buffer&#8217;s pages have a meta robots tag – which is fine &#8211; they are unnecessary unless they are trying to specify a hidden page. In the case mentioned above (wp-includes), it would benefit Buffer to include a “noindex” robots meta tag on a per page basis, rather than blocking an entire directory. WordPress is a great open source platform &#8211; one that Buffer blogs are built on &#8211; but duplicate content is one thing you have to be very mindful of. Using the robots meta tag will help prevent duplicate content. Content duplication issues include /tag, /category, and /author. <a style="color: #185bac;" target="_blank"><img src="/images/wp-uploads/2014/06/siteblog.bufferapp.comtagtwitter-chat-Google-Search-2014-06-01-13-57-04.png" alt="" /></a> As you can see above, the tags are indexed. Since these tags take up crawl bandwidth, but don’t have unique content, and historically have a low CTR, Buffer should “NOINDEX, FOLLOW” these archive based pages. Buffer has successfully implemented this change on subpages and should consider adding the same meta robots to the other archive based structure. The “NOINDEX, FOLLOW” will remove the tags, categories, and authors from the index, but will still allow links to pass.

#### XML Sitemaps {#sitemap}

What are sitemaps?

> Sitemaps are an easy way for webmasters to inform search engines about pages on their sites that are available for crawling. In its simplest form, a Sitemap is an XML file that lists URLs for a site along with additional metadata about each URL… Sitemaps.org 

I identified two Sitemap listings in Buffer’s robots.txt file:

The first listing points to blog.bufferapp Web Sitemap, which should include URLs for every page the site wants search engines to crawl and index. The second listing points to the open.bufferapp Sitemap. You can see one of Buffer&#8217;s sitemaps below (they are identical):

<a href="http://blog.bufferapp.com/sitemap_index.xml" target="_blank"><img class="alignnone size-large wp-image-2693" src="/images/wp-uploads/2014/06/sitemaps-1024x581.png" alt="sitemaps" width="1024" height="581" /></a>

In both sitemaps, I&#8217;d remove the page section &#8211; <a href="http://blog.bufferapp.com/sample-page" target="_blank">as it links to a blank &#8220;sample page&#8221;</a>. If Buffer does choose to NOINDEX tags and categories, they should remove them from the sitemap.

Since Buffer uses quite a bit of video, it may also help to compile a comprehensive list of the site’s indexable pages with videos on the page (i.e., pages that are substantive enough to warrant video inclusion) and creating a video sitemap using that list (they can use [Yoast&#8217;s extension for that as well](https://yoast.com/help-scout-review/)).

### Accessibility {#access}

This section covers best practices for both search engines and users. Many of the search engines’ accessibility issues were mentioned above in index-ability, and now we’ll cover accessibility as it mainly relates to personas with the benefits of robots in mind.

##### Performance {#performance}

According to Google Webmaster tools:

> You may have heard that here at Google we’re obsessed with speed, in our products and on the web. As part of that effort, today we’re including a new signal in our search ranking algorithms: site speed. Site speed reflects how quickly a website responds to web requests… While site speed is a new signal, it doesn’t carry as much weight as the relevance of a page.

Though it’s tempting to dismiss site speed as an important SEO ranking factor, if Google says it matters (even a small percentage), it matters.

Buffer’s site speed is decent, but Buffer could make a few tweaks to make their site much more efficient:

<a href="http://gtmetrix.com/reports/bufferapp.com/jPBQCu4c" target="_blank"><img class="alignnone size-large wp-image-2673" src="/images/wp-uploads/2014/06/performance-1024x707.png" alt="performance" width="1024" height="707" /></a>

Reducing the number of files needed to load the site, and thereby reducing the number of HTTP requests, will make Buffer&#8217;s site load more quickly.

**There are usually three parts to fixing this:**

  * Reduce the number of JavaScript files
  * Reduce the number of CSS files
  * Reduce the number of images

The Time to First Byte is extremely quick, but the page load is somewhat slow – anywhere from 2.66 seconds to 3.15 seconds (Pingdom). They received a 55/100 on Page Speed Insights via Google, and 80/100 on Pingdom. Buffer’s homepage has room for improvement. Another concern is that_ their blogs have over 100+ requests with a page speed of 3 seconds._

**The site could be improved with the following:**

  * Eliminate render-blocking JavaScript and CSS
  * Minimize HTTP requests – Buffer’s pages will load more quickly with fewer requests. Minimizing these requests involves reducing the number of files that have to be loaded, such as Javascript, CSS, and images.
  * Combine Javascript and CSS into external files with links from the header. This allows the external page to be cached so that it will load faster.
  * Implement server side / browser caching – This creates a static html page for a URL so that the dynamic sites don’t have to reload / be recreated each time the URL is requested.
  * Load Javascript asynchronously.
  * Finally, use 301′s only when necessary. A 301 forces a new URL, which takes a longer time to load.

##### Site Architecture {#architecture}

Currently, Buffer’s average page level is 3.7 (0 being the homepage). At this point, Buffer should:

  * Examine and prune their content that doesn’t produce results
  * Reduce the number of content silos on their pages by creating a flatter, better connected architecture

**First**, content is like a grapevine: In order to produce the best fruit possible, you really need to prune. I’d suggest that Buffer sit down with Google Analytics, Backink profiles, etc. and decide which pages are brining in traffic, shares, etc, and which articles are not. Based on the results, Buffer can create better content that engages and prevents keyword cannibalization.

On the other hand, there are posts that have aged poorly. If they are not driving traffic, increasing shares, ranking, or converting, Buffer should consider removing them. In removing content, Buffer should 301 duplicate content and let the rest of the content 404.

**Secondly**, Buffer should create a flatter site architecture. Right now, Buffer exists in 4 main silos: home, blog, open, and overflow. The Buffer homepage links to a silo (ie. blog), and silos link to posts. This creates lots of information, but links are flowing down, not around.

In reworking their site architecture, these vertical silos will disappear.

##### Usability {#usability}

Buffer has a few layout issues that reduce the website’s usability and effectiveness.

First, noticeably missing from the Buffer&#8217;s website is a navigation menu.

<img class="alignnone size-large wp-image-2675" src="/images/wp-uploads/2014/06/Screen-Shot-2014-06-11-at-10.49.25-AM-1024x128.png" alt="Navigation" width="1024" height="128" />

The only way to find something on Buffer&#8217;s website is to go down to the footer. While Buffer should consider adding a NAV, they may also want to add a search functionality to help users, and to figure out what exactly the user is searching for in their site page analytics.

Next, Buffer’s site is mobile responsive. But, on mobile, all of Buffer&#8217;s call-to-actions on the homepage (hello bar, pop up, etc&#8230;) fall off:

<img class="alignnone size-large wp-image-2676" src="/images/wp-uploads/2014/06/photo-576x1024.png" alt="photo" width="576" height="1024" />

It would be beneficial for Buffer to add a relevant call to action on the homepage for mobile devices. Finally, at some breakpoints, Buffer&#8217;s site could use a little adjusting:

<img class="alignnone size-full wp-image-2677" src="/images/wp-uploads/2014/06/Buffer-Open-Insights-into-Buffers-culture-numbers-experiments-and-improvements-2014-06-11-10-54-56.png" alt="Buffer Open Insights into Buffer's culture, numbers, experiments, and improvements 2014-06-11 10-54-56" width="1012" height="677" />Overall, Buffer&#8217;s site is usable on both mobile and desktop. Apart from a few minor tweaks, Buffer is doing well for usability (as it relates to inbound).

##### Click Depth {#clickdepth}

Click Depth (or crawl depth) is the number of times a website visitor must click on a link from the root domain in order to get to the desired page. The root domain will have a link depth of zero – since it takes zero clicks to get to the root domain on a webpage.

Search Engines are like humans – they do not want to waste time trying to find pages hidden deep in a site’s architecture. Pages that are available in one click – thus one page from the homepage – are deemed more important by search engines than those that are several clicks removed.

As the graph below shows, Buffer is doing a good job of keeping the required clicks minimal &#8211; the subdomains help keep the URL paths minimal.

<img class="alignnone size-large wp-image-2553" src="/images/wp-uploads/2014/06/Click-Depth-1024x655.png" alt="Click Depth" width="1024" height="655" />

### On Page Factors {#onpage}

In this section, I will investigate the characteristics of Buffer&#8217;s pages (e.g., URLs, schema, duplicate content, etc.) that influence the site’s search engine rankings. On Page search factors are those that are entirely within Buffer’s own control.

#### HTML Markup {#markup}

A site’s HTML is important because it contains some of the most vital on-page ranking factors.

HTML markup is a machine readable language that is used to tell the browser how to display the text or graphics in the document. Search engines crawl over your pages and semantic markup can identify your pages’ most important information. Semantic HTML markup is a way of indicating the meaning of web content to the search engine.

When examining Buffer&#8217;s pages, I found multiple pages with 20-40 errors per page. Many of the issues are easy fixes: open tags, stray elements, attribute errors, etc&#8230; Although these aren’t extremely critical issues, it&#8217;s best to clean up as many errors as possible (empty headings, duplicate IDs, attributes, etc).

<a href="http://validator.w3.org/check?uri=http%3A%2F%2Fblog.bufferapp.com%2Fthe-10-most-important-marketing-lessons-i-learned-working-at-facebook-mint-and-appsumo&charset=%28detect+automatically%29&doctype=Inline&group=0&user-agent=W3C_Validator%2F1.3+http%3A%2F%2Fvalidator.w3.org%2Fservices" target="_blank"><img class="alignnone size-large wp-image-2515" src="/images/wp-uploads/2014/05/Markup-Validation-of-httpblog.bufferapp.comthe-10-most-important-marketing-lessons-i-learned-working-at-facebook-mint-and-appsumo-W3C-Markup-Validator-2014-06-01-21-17-29-1024x177.png" alt="Markup Validation of http:::blog.bufferapp.com:the-10-most-important-marketing-lessons-i-learned-working-at-facebook-mint-and-appsumo - W3C Markup Validator 2014-06-01 21-17-29" width="1024" height="177" /></a>

##### Structured Data {#schema}

Schema.org microdata is an extra set of HTML tags that you can add to your HTML elements to let the search engines know specifically what you are talking about.

Fortunately, Buffer does define structured data, but fails to add authorship to most of its writers. Though a few of Buffer&#8217;s articles include authorship, such as the one below, including authorship in _all_ articles would be greatly beneficial:

<img class="aligncenter size-full wp-image-2281" src="/images/wp-uploads/2014/06/Authorship.png" alt="Authorship" />

Sadly, many others do not have authorship enabled, and even Kevan &#8211; by far one of their best writers- does not have authorship enabled for the open blog (pictured above is Main blog).

In order to add authorship, here&#8217;s what you can do: create a Google+ profile for each of the site’s authors. Then, link from their Google + profile back to the blog, and vice versa.

<span style="color: #ff0000;"><strong>Be Careful with Schema.org</strong></span>

One caution: Be wary of schema.org for all HTML elements.

Google uses micro markup (schema) to scrape content and place it on Search Result Pages &#8211; this could potentially hurt click through rates (CTR). The more information you tell Google &#8211; the more you risk Google scraping your content and your site losing sessions.

##### Meta Descriptions {#metadescription}

Meta descriptions are HTML attributes that provide concise explanations of the contents of web pages. Meta descriptions are commonly used on search engine result pages (SERPs) to display preview snippets for a given page (Moz).

Meta Descriptions do not influence the ranking factor of a site’s page, but they do influence the CTR (click-through-rate).

These short paragraphs (normally 155 words) are a website’s opportunity to advertise content to searchers and to let them know whether the given page contains the information they’re looking for.

Out of 1,449 unique HTML/Text URLs, 893 do not include a meta description, and 92 of those descriptions are duplicates. What this means is that in almost all of the searches, the meta descriptions are automatically generated by the search engine. Many of the duplicated meta descriptions are on the root domain (bufferapp.com). As you can see below, the home page has the same meta description as the about page, and as the &#8220;awesome&#8221; page:

<img class="alignnone size-large wp-image-2524" src="/images/wp-uploads/2014/06/Buffer-Duplicate-Meta-Description-1024x263.jpg" alt="Buffer Duplicate Meta Description" width="1024" height="263" />

**2 Options to Fix**

**The first answer** would be adding a unique meta description for each of the page’s content.

**The second answer** is a bit more complex. If a page is only targeting between one and three search terms, then by all means, write a meta description that targets those key words. But if the page is targeting long-tail searches, it may be easier to let the search engines pull in the meta descriptions themselves.

The reason the second answer is more feasible is because when the search engines pull content, they pull content and display keywords surrounding the user’s query. If you force a meta description, it can detract from the relevance of long tail search.

In some cases, search engines will overrule your meta description anyways, but you cannot always rely on that. In that regard, it would be advantageous for Buffer to add meta descriptions for pages that target only a few keywords and leave the other long-tail pages open for variance.

_One last issue to be aware of when thinking about meta descriptions:_

Social sharing sites will commonly pull the meta description when sharing &#8211; unless open graph is enabled (more on that in a moment). Without the meta description, social sharing sites will just use the first text they can find (sometimes Google will as well &#8211; see below).

![meta description](/images/wp-uploads/2014/06/Screen-Shot-2014-06-01-at-5.25.29-PM.png)

Not using a meta description may create a bad user experience for social sharing. In Buffer&#8217;s case, they are using open graph tags with &#8220;descriptions&#8221;, thus I&#8217;d encourage them to add meta descriptions as well.

##### Head Tags {#headtags}

_rel=publisher_

Buffer has a great looking Google+ page, so they ought to take advantage of rel=publisher. This tag has seen a much smaller adoption rate compared to Rel=author, and its name may cause the confusion. The publisher tag can be used by any business or brand website that has a corresponding Google+ page.

Publisher connects your Google + page to your website, and that results in your Google + page being displayed in search results whenever anyone is searching for your brand name.

Buffer has no rel=publisher markup code on their home page. In fact, if you analyze the page with the structured data tool, you will notice there is no publisher schema on the page at all. However, if you look at Buffer&#8217;s Google+ profile page, you will notice they have a verified website listing &#8211; which is why they are currently receiving the rich markup:

![publisher](/images/wp-uploads/2014/06/bufferapp-Google-Search-2014-06-01-22-25-20.png)

Rel=publisher markup is not required for the logo to show up. All that is required is for the company to have a Google+ page that has their website verified in their Google+ profile. But, it wouldn&#8217;t hurt for Buffer to add the publisher markup, just to make sure their rich snippet stays in place.

_rel=canonical_

Buffer is using [Yoast&#8217;s SEO plugin](https://yoast.com/help-scout-review/) &#8211; a great choice. Buffer has the plugin set up well, but there are a few conditions Buffer should be aware of with WordPress.

**First**, Yoast and rel canonical for paginated WordPress URLs are technically correctly implemented. Yoast&#8217;s plugin applies a rel-canonical meta tag to itself. _Depending on your source_, this could be a slight misuse of the rel-canonical tag (per <a href="http://googlewebmastercentral.blogspot.ca/2013/04/5-common-mistakes-with-relcanonical.html" target="_blank">Google&#8217;s Webmaster Blog</a>, which says rel-canonical should be replaced with rel-prev and rel-next for page 2, 3, etc.). On the other hand, millions of blogs use this setup of the canonical with no problem.

The current set up canonicalizes the subpage to itself. Not a crisis (or even a big deal), but it is something to monitor as Google updates its documentation.

According to webmaster tools, Google actually recommends that you rel=canonical to a “View All” page. The current set up (based on the plugin) is technically incorrect because the subpage is canonicalized to itself &#8211; not a view all pages. Buffer could fix this problem with one of 2 solutions.

  1. Buffer should use a canonical tag that points to a view all page.
  2. Or use Rel=prev/next.

      Excluding subpages, each Buffer page also uses a rel=”canonical” link; however, all of these links are self-referential and shouldn’t be a problem. _rel=prev / next_ Google asks that Webmasters add rel=”next” and rel=”prev” to paginated archives, so that Google can distinguish them as a series and send users to the most relevant pages. As far as I can tell, Buffer has not implemented this throughout their site.

###### Open Graph {#opengraph}

The Open Graph protocol enables any web page on Buffers’s site – or all sites – to become a rich object. For instance, the Open Graph is used by Facebook to allow any web page to have the same functionality as any other object on Facebook. Currently, Buffer does implement Open Graph protocol on their sites (with the exception of happiness.bufferapp.com). This is the open graph information in their root domain (bufferapp.com) markup:

_Which translates into:_

![](/images/wp-uploads/2014/06/Screen-Shot-2014-06-01-at-5.21.30-PM.png)

It may be best, however, that on bufferapp.com, Buffer include these basic og: tags at the very minimal:

Currently, on the homepage (and job.bufferapp.com) they are omitting type and URL. I&#8217;d suggest adding those tags. On their blogs (open.bufferapp and blog.bufferapp), they are correctly implementing open graph (using Yoast&#8217;s plugin to automatically generate og: markup).

###### Twitter Cards {#twittercards}

Twitter cards are another micro markup – essentially rich snippets for Tweets. Twitter will actually fall back on the Open Graph tags used for FB, but the Open Graph tags aren’t comprehensive. All of Buffer’s blog pages include Twitter Card tags, which attach additional information to the Tweets associated with those pages. However, the root domain should also include (in addition to the og: tags):

#### Titles {#titles}

According to <a href="http://cyrusshepard.com/" target="_blank">Cyrus Shepard at Moz</a>:

> Title tags—technically called title elements—define the title of a document. Title tags are often used on search engine results pages (SERPs) to display preview snippets for a given page, and are important both for SEO and social sharing.

Each page that is indexed should have unique content and a unique title that effectively summarizes the content for users and search engines. Out of the 1400+ pages on Buffer&#8217;s website, only 90 pages do not have unique titles.

Most of the pages that do not have a unique title derive from happiness.bufferapp.com. As you can see below, in the way that the happiness site is set up, the &#8220;title&#8221; tag is left empty.

<a href="view-source:https://happiness.bufferapp.com/reports/tags/helpscout/today" target="_blank"><img src="/images/wp-uploads/2014/06/httpshappiness.bufferapp.comreportstagshelpscouttoday-2014-06-01-16-04-38.png" alt="" /></a>

On these pages, Buffer should add a unique title that describes the pages.

Buffer does have a duplicate title issue with their development site. They should consider &#8220;noindexing&#8221; their dev site to prevent that error (more on that below). Additionally, many of the pages on the root domain have duplicate, non descriptive titles. Every page inside of bufferapp.com/developers holds the same title &#8220;Buffer &#8211; Developers&#8221;.

Once again, adding a unique title that describes the pages would be enormously beneficial.

Google will show as many characters that a 512 pixel display can show – thus, around 50-60 characters. As you can see below, most of Buffers titles are at an average of 69 characters long, and very few of them reach 80-90 characters in the title.

![Buffer Title Length](/images/wp-uploads/2014/06/Screen-Shot-2014-06-01-at-4.51.40-PM.png)

Shortening some of these titles would help Buffer to avoid truncation. For example, Buffer&#8217;s most recent title on the blog:

&#8220;10 Marketing Lessons From Billion-Dollar Businesses: Inside the Strategies of Facebook, Mint, and AppSumo&#8221;

is 105 characters long and looks like this in the SERPs:

![SERPs](/images/wp-uploads/2014/06/New-Title-Tag-Guidelines-Preview-Tool-Moz-2014-06-01-16-58-39.png)

In some cases, when Buffer&#8217;s title tag is too long, Google no longer truncates the title and adds an ellipsis to the end; instead, Google tries to algorithmically determine a better title for the post.

Titles matter so much that when Google wants to return a result, it changes the title to better match the query. The reason for this is simple: users scan for and assign higher relevance to titles that include their query.

**In this case, keeping titles within 50-60 characters is the wisest option.**

Along the same lines, many of the site’s pages in the root domain (bufferapp.com) use titles that are not sufficiently descriptive (e.g., &#8220;Buffer &#8211; Android FAQ&#8221;, &#8220;Buffer &#8211; FAQ&#8221;, etc.).

These titles need to provide more information about the contents of their corresponding pages. Users may be less likely to click through to those pages, and search engines will be less likely to rank those pages at the top of their search results.

Most of the site’s titles incorporate the brand name at the end to help promote brand awareness, but not all of them do.

The older blog posts incorporate branding:

_4 Little Known And Underused Twitter Tips For Bloggers &#8211; The Buffer Blog_

but the new blog post do not incorporate branding at the end:

_The Research and Science Behind a Perfect Blog Post_

Buffer can easily fix this issue on their blogs by setting up a template (with Yoast&#8217;s plugin they currently use) that automatically appends the title with the brand at the end. To help promote brand awareness, I recommend appending the brand name to the end of the site’s titles.

#### URLs {#urls}

Buffer has done a great job crafting their URLs. Their URLs are at an average length of 50 characters (including bufferapp.com/ or subdomain.bufferapp.com).

![](/images/wp-uploads/2014/06/Buffer-URL-Analysis.png)

Ignoring the subdomain structure (as opposed to subdirectory), the site’s URL structure is organized and clean. Each URL also contains at least one keyword.

Buffer keeps their root URLs short (averaging 26 characters), ie:
  
bufferapp.com/about
  
bufferapp.com/business

And their blog URLs lengthier (averaging 65 characters), ie:

blog.bufferapp.com/science-of-storytelling-why-telling-a-story-is-the-most-powerful-way-to-activate-our-brains
  
blog.bufferapp.com/people-dont-buy-products-they-buy-better-versions-of-themselves

The URLs work seemingly well. The root domains are short for memory and the blog URLs are a little lengthier for search indexing.

Unfortunately, while crawling the site, I found URLs on 738 pages that returned a 403 or 404 HTTP status codes (i.e., those URLs are no longer accessible). If possible, those links should be redirected and updated.

Another important URL-related consideration is the domain name. Buffer&#8217;s domain (bufferapp.com) is obviously appropriate for the brand; however, Joel (the domain’s registrant) hasn’t extended the domain’s registration, and now, it’s set to expire in October, 2014 (i.e., four months from now).

At some point in the near future, it would be great to see Buffer buy the domain Buffer.com. Bufferapp.com works, but it can be confusing (especially since Buffer changed Twitter names from @bufferapp to @buffer).

One last point: Buffer&#8217;s new blog overflow.bufferapp.com should remove the date from the link structure:

<img class="alignnone size-large wp-image-2652" src="/images/wp-uploads/2014/06/Screen-Shot-2014-06-11-at-8.57.30-AM-1024x185.png" alt="Screen Shot 2014-06-11 at 8.57.30 AM" width="1024" height="185" />

#### Keywords {#keywords}

The Meta keywords tag is no longer a valid tag employed by the search engines, as it was a method abused by spammers in the past.

For now, Buffer won&#8217;t be penalized by _Google_ for their existing use of keywords, but on the other hand, Bing still takes keyword tags into account as a signal for spam. In either situation, it would be advantageous for Buffer to remove the keywords tag.

Another reason for Buffer to remove the Meta Keywords tag is that it provides an easy way for their competition to see the words they are trying to rank for.

![keywords](/images/wp-uploads/2014/06/Keywords.jpg)

What&#8217;s most disconcerting of all is that if these keywords are truly the words Buffer is trying to rank for, then they need to conduct more keyword research. Some of the keywords make sense, but even attempting to rank for &#8220;Twitter&#8221;, &#8220;Linked In&#8221;, etc&#8230; would be difficult and would probably garner a low CTR. Buffer should consider doing more research around &#8220;Social Media Management Dashboard,&#8221; &#8220;Hootsuite alternative&#8221;, etc&#8230; These types of phrases would be more beneficial to their audience.

#### Images {#images}

For the benefit of search engines, compliance (HTML), and the visually impaired – all images on Bufferapp should have an ALT tag. The ALT tag should accurately describe the image, and if possible, contain a keyword relevant to Buffer (but only if the keyword is relevant to the image).

Additionally, image file names should be descriptive – not containing random numbers or queries. The file name should describe the image and, once again, use a keyword if possible.

If Buffer ensures that images follow these two rules, they will increase the likelihood of referral traffic from image searches. Buffer has hundreds of images, and around 81% of the images take advantage of the alt text.

One area that Buffer can improve in is the descriptiveness of the file naming. As you can see below, quite a few of the images are just random strings.

There are hundreds of images like the ones above on Buffer&#8217;s blog. I’d suggest adding descriptive title tags to the images to increase organic image search, and also to be HTML compliant. If you&#8217;ve ever read a blog by Buffer, you will notice they rely heavily on Screenshots. In fact, 29% (817) of all their images are screenshots. In order to avoid file naming structures such as &#8220;Screen-Shot-2014-01-15-at-1.30.44-PM.png&#8221; Buffer should consider using Awesome Screenshot Addon for Firefox. When taking a screenshot with the addon, the file is automatically named with &#8220;Title | Description&#8221;. It will save Buffer time and will automatically create files that are semantically named.

#### Content Duplication {#duplicate}

Buffer is doing a excellent job keeping their content unique and fresh (much thanks to Belle and Courtney). Buffer does, however, need to be careful with duplicate content and canonicalization. **Duplicate Content issues with the Development Site** Buffer uses a development site &#8211; dev.bufferapp.com &#8211; to test before pushing to production. As you can tell from the screenshot below, the dev site is a mirror of the production site: <a href="https://dev.bufferapp.com/about/team" target="_blank"><img src="/images/wp-uploads/2014/06/Team-Buffer-2014-06-01-13-20-16.png" alt="" /></a> This is normal practice to test changes on a UA, Dev, and staging server before pushing changes to production, but in this case, I&#8217;d suggest that Buffer do one of the following:

  1. Bring dev.bufferapp.com internally (which may not be easy due to a distributed work force).
  2. Add a robots file that Disallows the dev subdomain.
  3. Add a meta robots tag that &#8220;NOINDEX, NOFOLLOW&#8221; every page on the site.

      This is not a major issue right now because there are only 40 pages on the development site, but the last thing Buffer would want is duplicate content &#8211; or even worse &#8211; people linking to the development site. **Duplicate Content Issues with Overflow** Overflow is a new blog that Buffer just created. They took content from the open blog and moved it to overflow. During this process, they did not redirect the old content to the new location, leaving duplicate content. As you can see below, Buffer has content living in two blogs:  <img class="alignnone size-large wp-image-2609" src="/images/wp-uploads/2014/06/How-to-Stop-Procrastinating-on-Your-Goals_-The-Story-of-Fighting-Alligators-and-Building-Bikesheds-Google-Search-2014-06-10-10-14-19-1024x727.jpg" alt="How-to-Stop-Procrastinating-on-Your-Goals_-The-Story-of-Fighting-Alligators-and-Building-Bikesheds---Google-Search-2014-06-10-10-14-19" width="1024" height="727" />Right now, there isn&#8217;t a huge urgency to fix this matter because the overflow blog is being Disallowed by robots.txt. However, Buffer should 301 redirect the content from open to overflow fairly quickly to avoid duplicate content issues. I didn&#8217;t want to wait until the audit was published to contact Buffer, so I went ahead and sent this information over. The robots disallow could harm organic. Buffer replied with:

<blockquote class="twitter-tweet" lang="en">
  <p>
    <a href="https://twitter.com/elioverbey">@elioverbey</a> Thanks Eli, will pass along to double check! -Mary — Buffer (@buffer) <a href="https://twitter.com/buffer/statuses/476423041505701888">June 10, 2014</a>
  </p>
</blockquote>

**Duplicate Content Issues with https** Since Buffer&#8217;s site has secure pages (designated by the “https:” protocol), Buffer should be careful of both secure and non-secure versions getting indexed. Ideally, these problems will be solved by the site-architecture itself. In many cases, it’s best to Noindex these pages.

### Off Page Ranking Factors {#offpage}

This section will cover some of the most influential factors in ranking: backlinks.

#### Backlinks {#backlinks}

Links are not everything when it comes to SEO, but search professionals and companies attribute a large portion of the search engines’ algorithms to backlinks (Larry Page based Google off of the Educational Citation Method – ie. A professor who was cited by other authors was considered more credible – Read his dissertation for more information). When analyzing backlinks, you should consider: Total number of links, link quality, number of unique domains, fresh/incoming links, and anchor text usage. To start, I first recorded how many backlinks Buffer had received over the past few months. The charts below show the growth of Buffer’s backlink profile over the course of one year. <a href="https://ahrefs.com/site-explorer/overview/subdomains/?target=bufferapp.com" target="_blank"><img class="alignnone size-large wp-image-2645" src="/images/wp-uploads/2014/06/Overview-bufferapp.com-on-Ahrefs-2014-06-11-08-32-59-1024x722.png" alt="Overview bufferapp.com on Ahrefs 2014-06-11 08-32-59" width="1024" height="722" /></a> After comparing the backlink analysis above to both Majestic SEO and Moz, there was not much of a difference. Buffer was consistently growing their unique domain backlinks until April, and has started a recent growth. The reason Buffer&#8217;s backlink profile is massive is due to the Buffer social links pointing back to their root domain. To get a clearer view of what a natural link profile (and by natural, I mean not placed), here is a look at Buffer&#8217;s blogs (open and blog &#8211; at the time of writing the audit, overflow did not have any links&#8230;). [The first graph is blog.bufferapp &#8211; the second is open.bufferapp]: <a href="https://www.majesticseo.com/reports/compare-domain-backlink-history?IndexDataSource=F&d0=blog.bufferapp.com&d1=&d2=&d3=&d4=&type=1&ctype=1" target="_blank"><img class="alignnone size-large wp-image-2646" src="/images/wp-uploads/2014/06/Screen-Shot-2014-06-11-at-8.42.52-AM-1024x277.png" alt="Majestic SEO" width="1024" height="277" /></a> <a href="https://www.majesticseo.com/reports/compare-domain-backlink-history?IndexDataSource=F&d0=open.bufferapp.com&d1=&d2=&d3=&d4=&type=1&ctype=1" target="_blank"><img class="alignnone size-large wp-image-2647" src="/images/wp-uploads/2014/06/Screen-Shot-2014-06-11-at-8.43.05-AM-1024x269.png" alt="Screen Shot 2014-06-11 at 8.43.05 AM" width="1024" height="269" /></a>As you can see from the data above, their backlinks are growing, but the Bufferapp root domain is outpacing the blog, which is outpacing open. If Buffer continues to open subdomains (which is great for segregating content, bad for links) they need to keep a close eye on their links. This past month, the open blog traffic dropped: [<img class="alignnone size-full wp-image-2648" src="/images/wp-uploads/2014/06/Open-Traffic.png" alt="Open Traffic" width="740" height="217" />](http://open.bufferapp.com/may-buffer-content-marketing-report/) This graph includes all traffic (not just organic), but since the subdomain had been moved a month before, it could be a drop due to the lack of backlinks. The articles went from a subdomain with 10,000 backlinks to a subdomain with 1,100. Even though it was a month later, sometimes the changes are delayed in Google. To see how Buffer’s backlink growth matches up with their competition, I compared Buffer’s growth with one of their competitors over the past 5 years: Hootsuite. <a href="https://www.majesticseo.com/reports/compare-domain-backlink-history?IndexDataSource=H&d0=bufferapp.com&d1=hootsuite.com&d2=&d3=&d4=&type=1&ctype=1" target="_blank"><img class="alignnone size-large wp-image-2649" src="/images/wp-uploads/2014/06/Screen-Shot-2014-06-11-at-8.49.45-AM-1024x286.png" alt="Hootsuite and Buffer" width="1024" height="286" /></a> This charts shows 2 things:

  1. Buffer’s backlinks _are_ growing.
  2.  They have fierce competition.

      The reason Buffer has been able to make up so much ground against Hootsuite is due to the quick adaption of the Buffer button. Without the Buffer button, their links do not come close to Hootsuite&#8217;s. Almost every month, Hootsuite is acquiring more links from more unique referring domains. The backlink analysis shows the competitiveness of  backlinks: <a href="https://ahrefs.com/labs/domain-comparison/bufferapp.com/hootsuite.com" target="_blank"><img class="alignnone size-large wp-image-2653" src="/images/wp-uploads/2014/06/Domain-Comparison-Ahrefs-2014-06-11-08-55-19-563x1024.png" alt="Domain Comparison - Ahrefs 2014-06-11 08-55-19" width="563" height="1024" /></a>

##### 302 Redirects {#302}

Buffer implements redirects correctly throughout, but there is cause for some concern on the homepage. There are technical reasons for implementing a 302 redirect to https, but since this redirect will stay around, I&#8217;d suggest Buffer change the redirect to a 301. As you can see below, http://bufferapp 302 redirects to https://bufferapp:  <img class="alignnone size-large wp-image-2657" src="/images/wp-uploads/2014/06/Screen-Shot-2014-06-11-at-9.02.33-AM-1024x262.png" alt="Buffer Redirect" width="1024" height="262" />Unless there is a technical reason for this, I&#8217;d suggest Buffer consider adding a 301.

##### Backlink Distribution {#backlinkd}

To monitor Buffer’s backlink distribution – the links dispersed among all of their pages – I used Moz’s Pro Tools to analyze the backlinks for each page on Buffer’s site. <img class="alignnone size-large wp-image-2663" src="/images/wp-uploads/2014/06/distribution-of-links-1024x673.png" alt="distribution of links" width="1024" height="673" />Buffer has – according to Moz, Majestic and Ahrefs – around 42,000 referring domains. But, upon closer inspection, many of those links are pointing to root (via social links). According to the data, 76% of all Buffer’s pages have no backlinks. Of the 24% that do have links, the homepage accounts for almost 23% of those links (the data is skewed here because of the massive amount of backlinks to the root domain via the Buffer social sharing icon).

##### Backlink Source {#backlinksource}

To analyze Buffer’s backlinks, I used Majestic SEO. Here is a plotting of their backlinks: <a href="https://www.majesticseo.com/reports/site-explorer/link-profile?folder=&q=bufferapp.com&oq=bufferapp.com&IndexDataSource=F" target="_blank"><img class="alignnone size-large wp-image-2668" src="/images/wp-uploads/2014/06/Buffer-Backlink-Source-1024x542.jpg" alt="Buffer-Backlink-Source" width="1024" height="542" /></a> The site has quite a few quality backlinks. When analyzing Majestic, you are hoping to see the links fall to the top right. Citation Flow is link juice and the Trust Flow is how close those links are to trustworthy, authoritative sources. Correlating with the data above, a handful of Buffer&#8217;s links that I checked appeared spammy, and a few of the links over-optimized anchor text. With a trust ratio of .842 on bufferapp and .660 on blog.bufferapp, Buffer really needs to examine their backlink profile. (It would be nice to see the ratio greater than 1.) <span style="font-weight: bold;">One last caution:</span> Buffer should be careful of websites using links in headers and footers that repeat across the site. These sitewide links are heavily scrutinized by Google’s Penguin update… Buffer&#8217;s entire sharing model is based on multiple pages having the same backlink. Buffer should monitor webmaster tools closely to make sure they stay in line with Google&#8217;s regulations.

##### Anchor Text Distribution {#anchortext}

After Penguin, Panda, etc – it’s important for Buffer to conduct an anchor text analysis. Over the years, there were many ways to manipulate rankings on Google, and links were one of them. Google has always been aware of this, and they are finally cracking down (in fact, anchor text misuse will trigger the Penguin filter quickly). This is a great rule of thumb to follow:

  * 70% brand, URL, brand+keyword, and non-targeted anchor texts (Branded Links, White Noise, Naked URL, Titles, and Image)
  * 25% partial, phrase, and broad match keyword anchor texts (Compound)
  * 5% exact match anchor texts (Exact Match)

      Below is the Anchor Text chart for Buffer…  <img class="alignnone size-full wp-image-2557" src="/images/wp-uploads/2014/06/blog.bufferapp-anchor-text.png" alt="blog.bufferapp anchor text" width="938" height="778" />Buffer does very well. If you examine the chart closely:

  * 2% of Buffer links come from “Buffer,” which is a branded identity.
  * 4% of searches include a partial match, etc…
  * 94% include the other types of links: Naked, URL, etc..

      Buffer has done a great job of keeping their links diverse. The other blog &#8211; open.bufferapp &#8211; appears natural as well. As the company grows, the branded terms should grow as well, but again, that would be a natural progression. The only cause for concern is bufferapp.com &#8211; as you can see below, the Anchor text distribution is unnatural:  <img class="alignnone size-full wp-image-2558" src="/images/wp-uploads/2014/06/bufferapp-anchor-text.png" alt="bufferapp anchor text" width="970" height="780" />The  main reason for this is because Buffer uses bufferapp.com as the link location for all sharing functionality produced by Buffer. If you&#8217;ve ever created a Buffer share button, you would have seen:

If you look closely in the code above, you can see the anchor text is &#8220;Buffer&#8221; &#8211; which is why 34% of their anchor text on bufferapp.com is &#8220;Buffer&#8221;. In this case, since those links are technically placed links, Buffer should keep a close eye on it&#8217;s backlink profile, webmaster updates, and potential penalties. A future penalty on the root domain could hurt all domains.

##### No Follow Links {#nofollow}

With any link that you place on your site, NoFollow or not, know that these links act as a gateway into other sites that introduce your audience to others&#8217; content. So before you place a well-positioned link, think of what that link could to your site traffic and your content reach. As you can see below, the Hello Bar that Buffer uses places a follow link on every page (over 1,000).

<img class="alignnone size-large wp-image-2583" src="/images/wp-uploads/2014/06/Hello-Bar-No-Follow-Links-1024x551.jpg" alt="Hello Bar No Follow Links" width="1024" height="551" />

If I were Buffer, I&#8217;d reconsider the implementation of the HelloBar for 2 reasons:

**First**, the HelloBar will inevitably take users away from Buffer&#8217;s page. Since the link is at the very top of the page, some of Buffer&#8217;s quality, top-of-the-funnel users will be lost to Hello Bar.

**Second,** since the links are placed &#8211; and one day may be considered a link scheme &#8211; Buffer should consider upgrading the Hello Bar to remove the links. Upgrading HelloBar is a low fee that will remove both issues (users navigating away and multiple links). <a href="https://support.google.com/webmasters/answer/66356?hl=en&rd=1" target="_blank">According to Webmaster tools</a>:

> Widely distributed links in the footers or templates of various sites are unnatural and potentially violate guidelines.

In fact, Buffer should consider talking to Hello Bar about adding a nofollow (in fact, HelloBar could be considering adding a no follow in the future). One other consideration with no follows: Buffer should moderate their personal placement of Buffer links via the social share icons. With Google changing its stance on allowable links frequently, that is an important topic to remember.

##### Images {#imagelinks}

Lastly, Buffer should consider removing all links that open the same image in a new tab. For example-

(or just click the image below to see the action I am talking about):

[<img class="alignnone size-large wp-image-2603" src="/images/wp-uploads/2014/06/Email-List-Building-From-the-Experts_-How-to-Grow-a-Massive-Email-List-2014-06-09-22-40-14-1024x525.jpg" alt="Email-List-Building-From-the-Experts_-How-to-Grow-a-Massive-Email-List-2014-06-09-22-40-14" width="1024" height="525" />](/images/wp-uploads/2014/06/Email-List-Building-From-the-Experts_-How-to-Grow-a-Massive-Email-List-2014-06-09-22-40-14.jpg)

Buffer should consider removing that extra link. These extra links are an innate WP function that can easily be changed in functions.php:



This removes one extra link on the page (saving inbound and external links) and helps with UX and CRO by keeping the user on the page.

## Conversion / Leads {#conversion}

Once Buffer has visitors on their site (mainly from SEO), the next step is to convert those visitors into leads by gathering their contact information (in Buffer&#8217;s case, their email addresses). This leads us into the second stage, conversion and lead generation. This section will examine calls to action, landing pages, forms, and contacts.

### Call to Action {#cta}

A call-to-action (CTA) is an image or text that encourages users to take action, by subscribing to a newsletter or requesting a product demo. In most cases, CTAs _should direct people to landing pages_, where collection of information can be made. In that sense, an effective CTA results in more leads and conversions for your website (<a href="http://www.hubspot.com/" target="_blank">via Hubspot</a>).

Let&#8217;s start at the very beginning. Buffer should have calls to action on the homepage. It’s probably the most frequently visited page on Buffer and presents an opportunity to drive traffic for lead generation. In fact, some say the homepage should have at least three calls-to-action.

<img class="alignnone size-large wp-image-2590" src="/images/wp-uploads/2014/06/Buffer-A-better-way-to-share-on-social-media-2014-06-09-21-46-03-1024x525.png" alt="Buffer - A better way to share on social media 2014-06-09 21-46-03" width="1024" height="525" />

Buffer has an offer and at least three calls to action &#8211; asking people to log in with Twitter, Facebook, and Linkedin. The only shortcoming on this page is the CTA&#8217;s don&#8217;t lead to a landing page. This leaves two potential gaps.

**First,** a user could complete the login process and never come back. If a user logs in with Twitter or Linkedin &#8211; via the CTA &#8211; and there is no landing page to collect more information, the user could be one and done. As you can see below, if a user logins with Twitter or Linkedin, Buffer does not get their email information:

<img class="alignnone size-full wp-image-2591" src="/images/wp-uploads/2014/06/Authorize-LinkedIn-2014-06-09-21-57-40.jpg" alt="Authorize | LinkedIn 2014-06-09 21-57-40" width="800" height="528" />

The other forms of login (Facebook and Email) do allow for the collection of email, but perhaps Buffer could improve gathering more information.

**Secondly,** without email capture, lower funnel lead generation will become extremely difficult for Buffer. In a January post, Buffer detailed how they redesigned the CTAs on the homepage. In the article, they recount that the new homepage led to a 16% increase in overall new user conversions. This is great, but conversion in this case is top of the funnel &#8211; not paying users. Thus, 16% of those &#8220;new users&#8221; may have been one and done. If Buffer can create a landing page that collects email addresses on every signup for marketing automation and lead nurturing, they may increase their paying customers.

On the blog pages, Buffer also includes CTA&#8217;s, but the offers do not change and can be a little overwhelming: <img class="alignnone size-large wp-image-2594" src="/images/wp-uploads/2014/06/6-Research-Backed-Ways-to-Get-More-Followers-on-Twitter-and-Facebook-2014-06-09-22-11-56-1024x525.jpg" alt="6-Research-Backed-Ways-to-Get-More-Followers-on-Twitter-and-Facebook-2014-06-09-22-11-56" width="1024" height="525" />At the bottom of every blog page (open blog included), Buffer clusters its CTA&#8217;s, so much so that the sidebar CTA is hidden by the pop up footer CTA. In this case, it would be beneficial for Buffer to remove some of their CTA&#8217;s at certain scroll depths. It&#8217;s great that their CTA&#8217;s are above the fold, but when they all merge, the user is overwhelmed with 4 places to click.

#### 2 Quick Suggestions:

  1. With the exclusion of the footer popup (#4 on the screenshot above), every CTA is hyperlinked back to the homepage. Buffer should attempt to direct each CTA to its own dedicated landing page that restates the offer and copy from the CTA. At this point, the homepage seems to function as a dumping ground for all miscellaneous traffic. CTAs give Buffer the opportunity to increase conversions, reducing the amount of miscellaneous / anonymous traffic, but to take advantage of the CTAs, separate landing pages would be more effective.
  2. Buffer should attempt to use a different call to action in the footer (#2) and sidebar (#3) on each post. Creating different CTAs for different personas and audiences increases the effectiveness of their CTAs. If Buffer only uses one CTA for all blog posts, then they only hit one persona. Implementing different CTA&#8217;s increases the chances of targeting missed audiences.

Finally, Buffer needs to make sure their CTA&#8217;s are honest. Although this is accidental, notice the discretion between the number of email sign-ups at the top of the page and the sidebar:

<img class="alignnone size-large wp-image-2596" src="/images/wp-uploads/2014/06/Screen-Shot-2014-06-08-at-8.15.26-PM-1024x593.png" alt="Buffer Numbers" width="1024" height="593" />Again, this was a complete accident &#8211; or perhaps &#8211; even a lack of updating information (20,000+ users vs. 19,638), but I&#8217;d highly encourage that Buffer verify their numbers.

### Landing Pages {#landingpages}

A landing page is a web page that allows you to capture a visitor’s information. On your landing page, your visitors will find a form that they can fill out to receive an offer (<a href="http://www.hubspot.com/chrislodolce" target="_blank">Chris LoDolce at HubSpot</a>).

On Buffer&#8217;s site, however, the only landing page (either through CTA, Social Media, etc&#8230;) is the home page. Mainly, Buffer&#8217;s referral traffic lands on a blog page &#8211; which contains a CTA &#8211; which directs them back to the homepage:

<img class="alignnone size-large wp-image-2590" src="/images/wp-uploads/2014/06/Buffer-A-better-way-to-share-on-social-media-2014-06-09-21-46-03-1024x525.png" alt="Buffer - A better way to share on social media 2014-06-09 21-46-03" width="1024" height="525" />
  
In this case, Buffer is directing all of their traffic back to the home page, thinking that their visitors will “figure out” where they want to go. But with so many opportunities and the limited attention of the user, the home page is almost too broad and generic, rather than being narrowly focused to one particular topic to one particular persona.

For example, what if a user was solely interested in using Buffer to schedule tweets? Perhaps creating a landing page for that specific purpose and persona would drive up conversions (according to <a href="http://searchengineland.com/think-beyond-the-click-how-to-build-landing-pages-that-convert-12939" target="_blank">Interactive Marketing Inc.</a>, keeping relevant, focused, important information on a single page can increase conversion by 55%.).

Buffer should examine the possibility of creating custom landing pages for each type of content that could trigger a conversion. Creating landing pages will also allow Buffer to closely target their audience using different content that may appeal to different segments of their audience (perhaps segments Buffer did not know about). These different landing pages will offer Buffer a baseline conversion path that they can build upon.

### Forms {#forms}

Buffer does not use many forms &#8211; and perhaps, it&#8217;s because they don&#8217;t want the forms to come across as a hard sell. Nevertheless, it would be advantageous for Buffer to use a few more detailed forms to collect information. No matter how you spin it, Buffer does have name squeeze forms (an internet marketing tactic that presents users with a choice: enter your name and email to get a freebie, or go elsewhere). So, Buffer might as well see if they can at least ascertain more of the users&#8217; information.

<img class="alignnone size-full wp-image-2613" src="/images/wp-uploads/2014/06/Screen-Shot-2014-06-10-at-6.46.28-PM.png" alt="Forms" width="640" height="636" />

Buffer could create a few CTA&#8217;s that lead to unique landing pages with forms that collect name and email. Perhaps these forms could increase conversion. As it stands, a user could complete the form process and never come back. If a user logs in with Twitter or Linkedin &#8211; via the CTA &#8211; Buffer does not collect emails, and the user could be one and done. Or even worse, the user could log in, love the software, then get distracted &#8211; go to another site &#8211; and then, Buffer has no way of contacting them.

## Close / Customers {#close}

Closing refers to transforming leads into customers. This generally includes a wide array of options (lead scoring, email, marketing automation, CRM, etc [<a href="http://www.hubspot.com/nicksalvatoriello" target="_blank">via Nick at HubSpot</a>]) but since Buffer doesn&#8217;t have a sales team, this section will focus on contacts and email. <a href="http://open.bufferapp.com/hiring-at-buffer-in-february-2024-applicants-3-offers-made/" target="_blank">According to Leo</a>:

> For now, we decided that we wouldn’t go and build a sales team. The reason for this is that we’d rather try and go the Customer Success route for now. Sales teams come with a lot of interesting challenges and some of them don’t quite seem to be aligned with the type of culture and company we want to build at this point.

### Contacts / Email {#Contacts}

Buffer can accomplish their start up goals &#8211; without a sales team &#8211; if they continue to use best practices of inbound marketing. At some point, however, they will probably have to create a sales team to focus on leads.

In any manner, Buffer could improve their email communication / marketing automation. As previously mentioned, if a user logs in with Twitter or Linkedin &#8211; via the CTA &#8211; Buffer does not collect emails, and the user could be one and done (it is also not clear if Buffer can use the emails from FB login). During the month that this audit was being created, Buffer was collecting more email addresses than before (23,629 total email subscribers (+6%)).

**But as emails grow, so should Buffer&#8217;s outreach.** When a user signs up for Buffer&#8217;s email (through Hellobar or the popup), the visitor then must complete the double opt in (which is great in the prevention of SPAM). I signed up and you can see the **first** email I received:

<img class="alignnone size-full wp-image-2627" src="/images/wp-uploads/2014/06/Buffer-Email.png" alt="Buffer Email" width="834" height="518" />

Immediately, three problems arise that are compounded by other issues:

1. **Due to the lack of forms**, the email is not personalized. Buffer has no way to distinguish who I am,  what my name is, or where I am at on my buyer&#8217;s journey.
  
2. **Due to the lack of relevant CTA&#8217;s and landing pages**, the email is not targeted. The first email I receive is the generic email that gets sent to everyone else. Because Buffer does not use landing pages, they cannot segment my email into a list &#8211; and provide me with the related information I found interesting.
  
3. Finally, **the emails do not use marketing automation**. It would be great to feel included, or even welcomed, and although Buffer does an outstanding job with customer service, the emails aren&#8217;t personal. Even a generic email welcoming me to the Buffer list would be better than the blog roll.

Buffer may want to personalize their email marketing. Although they are growing their lists, their information should be targeted &#8211; and since they are using MailChimp, they should consider using the various email marketing communication tools they offer.

## Delight {#delight}

Buffer has some of the most engaging customers and fans in the internet marketing industry. Buffer provides remarkable content to all users &#8211; visitors, leads, or existing customers. This next stage of inbound marketing is all about engaging with and (hopefully) keeping their future and current customers happy.

Social Media also exists in optimization and attraction, thus this section will examine attraction and engagement.

### Social Media {#SM}

Bar none, Buffer is one of the best companies on social media. The responded to most tweets within 20 minutes, and during the week of monitoring, out of 1,798 inquiries, they responded to 90% in less than 6 hours.

<a href="https://happiness.bufferapp.com/reports/response-times/helpscout/last-week" target="_blank"><img class="alignnone size-large wp-image-2632" src="/images/wp-uploads/2014/06/Screen-Shot-2014-06-10-at-10.15.15-PM-1024x604.png" alt="Response Times" width="1024" height="604" /></a>

Besides using social media as a customer service tool, we cannot ignore the fact that social media is a search engine of sorts. People on social media are researching, searching, interacting, and engaging – and at very high engagement rates. According to Statisticbrain, the number of Twitter search engine queries every day is over 2.1 billion. In any regard, a site’s success is largely dependent on social success and social engagement.

The chart below provides a visual of how Buffer’s shares are split concerning a search engine’s point of view. The center represents the first page, and each segment beyond it are pages linked from that page (in this case &#8211; the blog roll page). Segments beyond that are linked to their parent. Pages with no shares are not included or shown (click on the image to zoom in and to read the text).

[<img class="alignnone size-large wp-image-2635" src="/images/wp-uploads/2014/06/Screen-Shot-2014-06-10-at-10.34.20-PM-1024x944.png" alt="Buffer Starburst" width="1024" height="944" />](https://socialcrawlytics.com/account/report/SC5397d9c7c6f281504/large_tree/4000/4000)

As you can tell from the starburst, Buffer&#8217;s top 10 posts in organic traffic are highly represented in social media engagement:

  1. *[53+ Free Image Sources For Your Blog and Social Media Posts](http://blog.bufferapp.com/free-image-sources-list)
  2. *[The Big List of The 61 Best Social Media Tools for Small Business](http://blog.bufferapp.com/best-social-media-tools-for-small-business)
  3. [10 Simple Things You Can Do Today That Will Make You Happier, Backed By Science](http://blog.bufferapp.com/10-scientifically-proven-ways-to-make-yourself-happier)
  4. *[The Busy Person’s Guide to Content Curation: A 3-Step Process for Your Blog, Newsletter, or Timeline](http://blog.bufferapp.com/guide-to-content-curation)
  5. [8 Surprising New Instagram Statistics to Get the Most out of the Picture Social Network](http://blog.bufferapp.com/instagram-stats-instagram-tips)
  6. [The Social Media Frequency Guide: How Often to Post to Facebook, Twitter, LinkedIn And More](http://blog.bufferapp.com/social-media-frequency-guide)
  7. *[The Big List of IFTTT Recipes: 34 Hacks for Hardcore Social Media Productivity](http://blog.bufferapp.com/the-big-list-of-ifttt-recipes-for-social-media)
  8. [8 Surprising Ways Music Benefits and Affects Our Brains](http://blog.bufferapp.com/music-and-the-brain)
  9.  [Why Most Olympic Records Are Broken in the Afternoon: Your Body’s Best Time For Everything](http://blog.bufferapp.com/your-bodys-best-time-for-everything-how-to-eat-sleep-and-work-more-efficiently)
 10.  [The Ideal Length of Everything Online, According to Science](http://blog.bufferapp.com/the-ideal-length-of-everything-online-according-to-science)

_*Written during Audit_

As you can see from the graph above, the center represents the blog homepage, and all articles off of the homepage. The graph below breaks down that same content by social network:

<a href="https://socialcrawlytics.com/account/report/SC5397d9c7c6f281504" target="_blank"><img class="alignnone size-large wp-image-2636" src="/images/wp-uploads/2014/06/Screen-Shot-2014-06-10-at-10.27.44-PM-952x1024.png" alt="Social Shares" width="952" height="1024" /></a>This data strongly correlates with the data that Buffer produces each month on the open blog. <a href="http://open.bufferapp.com/may-buffer-content-marketing-report/" target="_blank">According to Buffer</a><span style="text-decoration: underline;">:</span>

[<img class="alignnone size-large wp-image-2638" src="/images/wp-uploads/2014/06/Social-Media-Interaction-1024x217.png" alt="Social Media Interaction" width="1024" height="217" />](http://open.bufferapp.com/may-buffer-content-marketing-report/)

As the data shows, followers grew on all social networks this month, but their interactions were down for every network except Facebook. Even though Facebook grew this month, Buffer&#8217;s Facebook engagement still needs some help – their engagement rate is hovering around 2%.

The articles on Buffer that are most widely read are ones that ask for engagement:

<img class="alignnone size-full wp-image-2641" src="/images/wp-uploads/2014/06/Screen-Shot-2014-06-10-at-10.49.48-PM.png" alt="Facebook gone" width="850" height="372" />

In this case, I&#8217;d encourage Buffer to examine their posts, and they are likely to find that the posts with larger images / posts asking for involvement did better than others.

Overall, Buffer does extremely well with social media. One minor suggestion, though: Buffer should consider adding social icons to the top of articles on the blog as well.

### Engaging Content {#engaging}

Besides social shares and traffic (which have already been measured), the next best tell for engaging content is commenting. On average, Buffer receives 35 comments for each post.

As you can see from the graph below, Buffer receives quite a few comments for each post (40 in sample):
  
<img class="alignnone size-large wp-image-2643" src="/images/wp-uploads/2014/06/Screen-Shot-2014-06-10-at-11.07.19-PM-1024x597.png" alt="Buffer Comments" width="1024" height="597" />

The only recommendation I&#8217;d have for Buffer is to add a comment counter to the blog page. With such high interaction levels, a user may just click the comment count to join the discussion.

## Summary {#summary}

If you read everything in this audit example, I am truly impressed. If you cheated and jumped straight down to this section, I’ll forgive you. Either way, this section contains a summary of my most important observations and recommendations for Buffer&#8217;s Inbound Marketing Audit.

### Optimization / Attract

  * Buffer&#8217;s site is built with 11 subdomains for a total of 1,461 pages across all subdomains. Personally, based on research and countless other stories, I’d encourage Buffer to think about subdirectories. [[More information]](#indexability)
  * It is possible that Buffer can’t build on the root domain in order to be “white hat” with their links. Have you ever clicked on the Buffer icon button when sharing an article and noticed what URL is in the pop up? [[More information]](#indexability)
  * Buffer should remove the disallow of all directories on their new blog overflow.bufferapp.com. In its current condition, the site cannot be indexed. [[More information]](#robots)
  * Since Buffer uses quite a bit of video, it may help to compile a comprehensive list of the site’s indexable pages with videos on the page (i.e., pages that are substantive enough to warrant video inclusion) and create a video sitemap using that list. [[More information]](#sitemap)
  * Buffer received a 55/100 on Page Speed Insights via Google, and 80/100 on Pingdom. Buffer’s homepage has room for improvement. Another concern is that their blogs have over 100+ requests with a page speed of 3 seconds. [[More information]](#performance)
  * When examining Buffer’s pages, I found multiple pages with 20-40 errors per page. Many of the issues are easy fixes: open tags, stray elements, attribute errors, etc… [[More information]](#markup)
  * Out of 1,449 unique HTML/Text URLs, 893 do not include a meta description, and 92 of those descriptions are duplicates. [[More information]](#metadescription)
  * Yoast and rel canonical for paginated WordPress URLs are technically incorrectly implemented. Yoast’s plugin applies a rel-canonical meta tag to itself. This is a known misuse of the rel-canonical tag. [[More information]](#headtags)
  * Each page that is indexed should have unique content and a unique title that effectively summarizes the content for users and search engines. Out of the 1400+ pages on Buffer’s website, only 90 pages do not have unique titles. [[More information]](#titles)
  * Buffer has done a great job crafting their URLs. Their URLs are at an average length of 50 characters (including bufferapp.com/ or subdomain.bufferapp.com). [[More information]](#urls)
  * Buffer has hundreds of images, and around 81% of the images take advantage of the alt text. [[More information]](#images)
  * Buffer implements redirects correctly throughout, but there is cause for some concern on the homepage. There are technical reasons for implementing a 302 redirect to https, but since this redirect will stay around, I’d suggest Buffer change the redirect to a 301. [[More information]](#302)
  * 76% of all Buffer’s pages have no backlinks. Of the 24% that do have links, the homepage accounts for almost 23% of those links. [[More information]](#backlinkd)
  * With a trust ratio of .842 on bufferapp and .660 on blog.bufferapp, Buffer really needs to examine their backlink profile. (It would be nice to see the ratio greater than 1.) [[More information]](#backlinksource)

### Conversion / Leads

  * Buffer has an offer and at least three calls to action on the homepage – asking people to log in with Twitter, Facebook, and Linkedin. The only shortcoming on this page is the CTA’s don’t lead to a landing page. [[More information]](#cta)
  * At the bottom of every blog page (open blog included), Buffer clusters its CTA’s, so much so that the sidebar CTA is hidden by the pop up footer CTA. [[More information]](#cta)
  * On Buffer’s site, the only landing page (either through CTA, Social Media, etc…) is the home page. Buffer’s referral traffic lands on a blog page – which contains a CTA – which directs them back to the homepage [[More information]](#cta)

### Close / Customers

  * Due to the lack of forms, the email is not personalized. Buffer has no way to distinguish who I am, what my name is, or where I am at on my buyer’s journey. [[More information]](#Contacts)

### Delight

  * Buffer responded to most tweets within 20 minutes, and during the week of monitoring, out of 1,798 inquiries, they responded to 90% in less than 6 hours. [[More information]](#SM)
  * Besides social shares and traffic (which have already been measured), the next best tell for engaging content is commenting. On average, Buffer receives 35 comments for each post. [[More information]](#SM)

### Final Thought

As important as SEO is, it doesn’t exist in a silo. I hope this audit integrates SEO and inbound marketing to create a cohesive strategy and plan for Buffer in the future.

After the entire audit, I plan to solely use Buffer as a way to publish on social media. You won&#8217;t find a better company. I hope this helps them succeed.

This audit has proven two things:

  1. No company is perfect. Even the best companies have to constantly monitor their internet marketing. This should be an encouragement for all &#8211; we all miss things in our inbound / SEO.
  2. Buffer comes pretty close to being perfect&#8230;

Best of luck, Buffer.

## What Do You Think?

I would love to hear your thoughts, suggestions, and questions in the comments below. Do you have any audit-related tips you’d like to share? How would you help Buffer with inbound?