---
title: "SEO Audit of the Kissmetrics Blog: Google Panda Recovery"
meta_description: Have you ever noticed how much advice about SEO and Social Sharing is completely wasted? It's amazing to me how many people can write about strategies, best practices, and go on preaching without showing exactly how it's done.
permalink: a-complete-audit-of-kissmetrics-seo-and-inbound-marketing/
layout: post
---

Have you ever noticed how much advice about SEO and Social Sharing is completely wasted? It's amazing to me how many people can write about strategies, best practices, and go on preaching without showing exactly how it's done.

[Eli Overbey](http://elioverbey.net/) has provided an incredible post about the website KISSmetrics. In fact, if you've ever wondered how to do an audit, detailed analysis, or strategy document...wonder no more.

It's all in the nearly 9,000 word document below.

 {% highlight html %}
This post was original written for OkDork (Noah Kagan). You can find it here: https://okdork.com/a-complete-audit-of-kissmetrics-seo-and-inbound-marketing/
{% endhighlight %}


In this post, I will provide a comprehensive technical Inbound audit for KISSmetrics. This example is extremely detailed, and it covers a wide range of inbound topics. But before the inbound marketing audit, let's cover the basics...

### **Who is KISSmetrics? **

[KISSmetrics](https://www.kissmetrics.com/) is a web analytics solution that helps companies make smarter business decisions, and boosting ROI.

Headquartered in San Francisco, KISSmetrics is backed by a syndicate of angels and early stage funds.

### **Why Audit KISSmetrics?**

Like everyone working in SEO and Inbound Marketing, we all overlook or miss things (even basic things). The goal of this post is to help KISSmetrics, to help others learn from their inbound successes (they've done remarkable things in this arena), and to give a third-party perspective on a great example.

To be fair, "audit" seems like a terrible word, but in this case, think of "audit" as "being helpful." The purpose of this audit is to give an outsider's view to a great company. All in all, I hope this helps KISSmetrics. Neil and team are outstanding.

### **Disclaimer**

Before I jump into the technical details of the inbound audit, it's important to note that* I have no affiliation with KISSmetrics* (I am also not currently a user of their product - so you don't have to worry about affiliate links). KISSmetrics also did not ask me to complete this audit. As a result, I don't have access to any of the site's analytics or webmaster tools accounts, and I don't have access to the site's content management system (CMS).

In a typical audit, I would begin by sifting through the data and then narrowing in on problem issues. So... if I make completely inaccurate observations, I blame my data from the third party tools, ie (Searchmetrics, Ahrefs, SEMrush, Moz, etc...). Don't get me wrong - these tools are awesome, but they generally work better from the inside of the company.

The goal of this audit is to help KISSmetrics. The aim is never to critique in a negative, harmful way, but to help promote KISSmetrics through inbound marketing by giving them the perspective of an objective third party. With those disclaimers out of the way, let's begin.

*If you have any questions: [@elioverbey](https://twitter.com/elioverbey)


**Indexability / KISSmetrics Web Structure**
--------------------------------------------

In order to understand this audit, you need to understand how KISSmetrics is set up. At first glance, you'll notice that KISSmetrics is constructed using quite a few subdomains:

-   kissmetrics.com/ - 18 pages

○      *tweets.kissmetrics.com - 2587 Pages

○      blog.kissmetrics.com - 1,038 pages

○      *status.kissmetrics.com - 70 pages

○      grow.kissmetrics.com - 7 pages

○      focus.kissmetrics.com - 10 pages

○      support.kissmetrics.com - 347 pages

○      middleman.kissmetrics.com - 1 pages

○      styleguide.kissmetrics.com - 7 pages

○      uptime.kissmetrics.com - Redirects to status.kissmetrics.com

○      demo.kissmetrics.com - 100 pages

*An * (asterisk) indicates that the subdomain is blocked by the robots.txt.*

**In total, KISSmetrics has 4,185 pages across 11 domains and subdomains.** 

As you glance at the site structure of KISSmetrics, you notice that their content is divided up into subdomains. Due to the structure of KISSmetrics, this inbound audit will focus solely on two areas of their site: the root domain (kissmetrics.com) and their blog (blog.kissmetrics.com). The other subdomains do not contain information pertaining to this inbound audit (ie. styleguide) and will not be included in the analysis.

**Inbound Marketing**

In its most basic form:

"Inbound marketing focuses on earning, not buying, a person's attention."-- [Brian Halligan](http://www.hubspot.com/inbound-marketing)

The principle of inbound marketing has been around for years, but the term has been coined by HubSpot (well done Dharmesh and Brian). Inbound Marketing is all about creating great content that pulls people in.

Since [HubSpot](http://www.hubspot.com/inbound-marketing) is the go-to on inbound, this audit will use their structure as a model. As this audit continues, you'll notice how the funnel naturally works.

![Inbound Marketing Funnel](/assets/images/kissmetrics/Inbound-Marketing-Funnel.png)

**Optimization / Attract**
--------------------------

The first step in inbound marketing / SEO is attracting the right audience. Content is the single best way to attract new visitors to your website. In order to be found by the right prospective customers, KISSmetrics must not only create optimized content, but foster an environment in which content can thrive.

### **Search Visibility**

In order to set the framework for the entire audit, it's important to [analyze the site's performance](https://www.distilled.net/blog/seo/4-signs-you-should-invest-in-seo-now/). When looking at KISSmetrics's traffic, there are 3 important questions:

-   Is the traffic growing?
-   Has the site been penalized?
-   What is the percentage of organic traffic?

To determine KISSmetrics's traffic performance, I used two tools:

[Searchmetrics Suit](http://suite.searchmetrics.com/en/research/domains/organic?url=kissmetrics.com), and one of my new favorites, [Similar Web](http://www.similarweb.com/website/kissmetrics.com). Finding accurate third party data is incredibly difficult, but after using Google Analytics on a network of sites, I've found that these two programs provide the most accuracy in capturing third-party data.

As you can see [from the graph below](http://suite.searchmetrics.com/en/research/domains/organic?url=kissmetrics.com), there are some red flags for KISSmetrics (the tools join all traffic from all subdomains together):

![KISSmetrics SEO Visibility](/assets/images/kissmetrics/KISSmetrics-SEO-Visibility-1024x622.png)

As the graph above shows, the site's visibility decreased dramatically after May 18, 2014. This date is important because it also corresponds to when [Google updated Panda 4.0](http://www.searchenginejournal.com/everything-need-know-panda-4-0/109345/).

**Immediately, **there is cause for concern on KISSmetrics's site. As you begin to look over the third-party data, there is a strong correlation between the data (although third party) and Google's Panda update...

**There are three possible solutions to this drop in traffic:** 

1.  **The data is inaccurate**
2.  **The site was algorithmically penalized due to duplicate content**
3.  **The site was algorithmically penalized due to guest bloggers  ** 

**The first possibility: **The data from the third party is inaccurate. In fact, it seems highly improbable that KISSmetrics was hit with an algorithmic penalty, right? [Neil Patel](http://www.quicksprout.com/) (co-founder of KISSmetrics and SEO expert) wrote an article for [Search Engine Journal about the Panda 4.0 update](http://www.searchenginejournal.com/everything-need-know-panda-4-0/109345/) the day after Panda 4.0 was released.

In the post, Neil describes the update, who was affected, and how to fix it. Does it not seem like KISSmetrics (his company) would be prepared for Panda? Since he knew so much about Panda, he would have protected his assets.

Besides that, KISSmetrics writes lengthy (2,000+ word average), unique content that is well received (only 12 of their articles don't have any comments - meaning, the other 1,000+ have engagement via comments).

That is one possibility. But the other possibilities do cause for more concern:

**The second possibility**: KISSmetrics was hit by Panda 4.0 and here is the probable reason:

For some odd reason, the KISSmetrics blog exist on two protocols: http and https. Meaning, the same content (although unique and engaging) can technically be seen as duplicate.

Let's look at an example. As of today, the most recent post from KISSmetrics is: [Website Testing Mistakes That Can Damage Your Business](http://blog.kissmetrics.com/website-testing-mistakes/) (this post was chosen due to recency, but this same problem exists throughout). You can find this article in two places:

-   **http:**//blog.kissmetrics.com/website-testing-mistakes/
-   **https:**//blog.kissmetrics.com/website-testing-mistakes/

As you can see from the image below, the same page exists in two places (unfortunately, this is duplicate content and cause for concern):

![KISSmetrics Dual URLs](/assets/images/kissmetrics/KISSmetrics-Dual-URLs-1024x577.png)

You'll notice that in the image above, on the left is the normal protocol (http://), and on the right is the secure protocol (https://). *Google drops the http:// protocol in the browser on the left by default.*

I also checked out the source code on this same page to find three problems that could have led to this drop in traffic on May 19th (Panda 4.0), I highlighted 3 key problems in the diagram below:

![Panda 4.0 3 Key Problems KISSmetrics](/assets/images/kissmetrics/Panda-4.0-3-Key-Problems-KISSmetrics-1024x577.jpg)

1.  Once again, I highlighted the protocol so you can see the two exact pages in two locations.
2.  Both of these pages are INDEX, FOLLOW. If one of these pages was NOINDEX, there wouldn't be a huge problem, but KISSmetrics is telling the search engines to index both of these pages. This is another red flag.
3.  The third red flag is the canonical. The canonical tag tells the search engines that a given page should be treated as though it were a copy of the URL. In this case, each page canonicals itself. One page says the content should canonical to http:// and the other page says the content should canonical to https://. Basically, each page is claiming original.

Finally, Google has noticed that the blog exists in two locations. As you can see below, a query for the blog brings back both protocols (http and https).

![KISSmetrics Both Protocols Appear](/assets/images/kissmetrics/KISSmetrics-Both-Protocols-Appear-1024x1010.png)

**This means that the KISSmetrics blog was probably hit by an algorithmic penalty on May 19th. ** 

Even if the third party data is wrong (and KISSmetrics was not hit by a penalty) they should fix these problems *immediately*. KISSmetrics should decide which URL is primary, and then 301 or canonical.

Even more, as it currently stands, the site is dispersing its links among https and http. If they fix this problem, the could see a rise in rankings due to the migration of their links.

**The third possibility**: KISSmetrics was hit by Panda 4.0 because of guest bloggers.

I am **not **implying that KISSmetrics was penalized because "[they didn't stick a fork in their guest bloggers"](http://www.mattcutts.com/blog/guest-blogging/). But, KISSmetrics could have been penalized by duplicate content from their guest bloggers (quite a few of KISSmetrics posts are written by guest bloggers). Guest writers could have written for KISSmetrics and then re-published that content on their own blog.

Based on the [KISSmetrics publishing guidelines](http://blog.kissmetrics.com/guest-blogging-for-kissmetrics/)**, **there are no guidelines stating that the writer cannot re-publish his or her own content. Although the duplicate content issue could be covered in other forms of communication to the writers (contract, etc), it is a possibility.

### **Penalty Conclusion**

Although I am hoping for the first possibility, (I wouldn't wish a penalty upon anyone) these are issues that KISSmetrics should thoughtfully consider. Again, I cannot stress the unreliability of third party data, but in any manner, these are issues that should be addressed immediately. Hopefully, Neil can chime in on this issue. I'd really love to know if these have been issues for KISSmetrics (plus, Neil is extremely transparent in order to be helpful).

### **Robots**

A robots.txt file is used to restrict search engines from accessing specific sections of a site. Here is a copy of KISSmetric's root domain Robots.txt file:

![KISSmetrics Robots File](/assets/images/kissmetrics/KISSmetrics-Robots-File.png)

On their blog, KISSmetrics uses another robots.txt file:

![KISSmetrics Blog Robots File](/assets/images/kissmetrics/KISSmetrics-Blog-Robots-File.png)

There are a few improvements that KISSmetrics could make in the construction of their robots.txt.

**First**, on the blog, KISSmetrics should consider blocking '/wp-content/plugins/'. Sometimes developers put links in their plugins.

**Second**, on the blog, KISSmetrics should rethink blocking /wp-includes/' in robots. There are better solutions for blocking robots than in the robots.txt file (ie, NOINDEX).

**Finally**, KISSmetrics should add a working sitemap to their blog. The current sitemap (Sitemap: http://blog.kissmetrics.com/sitemap.xml.gz) does not work.

![KISSmetrics Site Map Does Not Work](/assets/images/kissmetrics/KISSmetrics-Site-Map-Does-Not-Work.png)

Fixing this will help the robots to index their pages.

### **Robots Meta Tag**

Each page on a site can use a robots meta tag to tell search engine crawlers if they are allowed to index that page and follow its links.

WordPress is a great open source platform -- one that KISSmetrics built their blog on -- but duplicate content is one thing you have to be very mindful of. Using the robots meta tag will help prevent duplicate content. Content duplication issues include tags, categories, and archives.

Quite a few of KISSmetrics's pages have a meta robots tag. In the case mentioned above (wp-includes), it would benefit KISSmetrics to include a "noindex" robots meta tag on a per page basis, rather than blocking an entire directory.

One thing KISSmetrics should consider 'NOINDEX' is blog subpages. As you can see below, the sub-pages are indexed:

![Subpages Indexed](/assets/images/kissmetrics/Subpages-Indexed-1024x274.png)

Since these page take up crawl bandwidth, but don't have unique content, and historically have a low CTR, KISSmetrics (based on their analytics) should consider "NOINDEX, FOLLOW" on these archive based pages.

KISSmetrics has successfully implemented this change on subpages of categories, topics, and topic sub-pages, and should consider adding the same meta robots tag to the other archive based structures. The "NOINDEX, FOLLOW" will remove the subpages from the index, but will still allow links to pass.

**Accessibility**
-----------------

This section covers best practices for both search engines and users. Many of the search engines' accessibility issues were mentioned above in index-ability, and now we'll cover accessibility as it mainly relates to personas with the benefits of robots in mind.

### **Performance**

[According to Google Webmaster tools](http://googlewebmastercentral.blogspot.com/2010/04/using-site-speed-in-web-search-ranking.html):

You may have heard that here at Google we're obsessed with speed, in our products and on the web. As part of that effort, today we're including a new signal in our search ranking algorithms: site speed. Site speed reflects how quickly a website responds to web requests... While site speed is a new signal, it doesn't carry as much weight as the relevance of a page.

It's tempting to dismiss site speed as an important SEO ranking factor, but if Google says it matters (even a small percentage), then it matters. Even if you dismiss speed as an optimization factor, it is also an inbound factor that can't be ignored. Who likes a slow site?

KISSmetrics's site speed is fairly slow, and KISSmetrics could easily make a few tweaks to make their site much more efficient. As you can see below, the site speed for the root domain is:

![Performance Report for KISSmetrics](/assets/images/kissmetrics/Performance-Report-for-KISSmetrics-1024x577.png)

The problems on the root domain above are quick fixes. The blog (blog.kissmetrics.com) did much better, scoring an 88% and a 79%.

Reducing the number of files needed to load the site, and thereby reducing the number of HTTP requests, will make KISSmetrics's site load more quickly. Currently, the root domain makes 64 request when loading the page (which is somewhat surprising, considering the homepage is only a few images and includes less than 70 words.)

**There are usually three parts to fixing this:**

-   Reduce the number of JavaScript files
-   Reduce the number of CSS files
-   Reduce the number of images

On the homepage, the Time to First Byte is efficient (300ms), but the page load is somewhat slow -- anywhere from 2.95 seconds on GTMetrix to 1.95 seconds on a tool like Pingdom. They received a 55/100 on Page Speed Insights via Google (42 on Mobile), and 75/100 on Pingdom. KISSmetrics's homepage has room for improvement.

Another concern is that their blogs have over 100+ https requests, but surprisingly, even with all the requests, the page speed was excellent: 933kb.

**The site could be improved with the following:**

-   Eliminate render-blocking JavaScript and CSS
-   Minimize HTTP requests -- KISSmetrics's pages will load more quickly with fewer requests. Minimizing these requests involves reducing the number of files that have to be loaded, such as Javascript, CSS, and images.
-   Combine Javascript and CSS into external files with links from the header. This allows the external page to be cached so that it will load faster (there are 10 CSS files and 4 JS files loaded separately on the blog).
-   Implement server side / browser caching -- This creates a static html page for a URL so that the dynamic sites don't have to reload / be recreated each time the URL is requested.
-   Load Javascript asynchronously.
-   Use a CDN -- such as Amazon. The CDN will allow users to download information more quickly (as far as I can tell, they are not using a CDN).
-   Finally, use 301′s only when necessary. A 301 forces a new URL, which takes a longer time to load (93 of their pages use 301).

### **Site Architecture**

The site architecture defines the overall structure of a site, and it has a number of important SEO implications. For example, when a page receives external authority, the site architecture defines how that authority flows through the rest of the site.

Additionally, since search engine crawlers have a finite crawl budget for every site, the site architecture ultimately dictates how frequently pages are crawled (or if they're crawled at all).

### **Authority Flow**

To understand how authority flows through the site, I performed an analysis on the site's internal links.

Based on that analysis, here is the distribution of the site's links (these values have been rounded to the nearest percentage):

![Inernal Authority Flow](/assets/images/kissmetrics/Inernal-Authority-Flow-1024x661.png)

As you can see above, 96% of the pages have a value less than 0.1 (pages with authority values closer to 0 have the least authority and pages closer to 1 have highest authority), relative to the other pages. Most of the site's internal authority is held by 3.8% of the pages.

The root cause for this authority is the site's navigation. All of the pages that have large amounts of internal links (1800+), are found in the footer or header:

/infographics (1834)

/marketing-guides (1830)

/webinars (1822)

/topics (1820)

Since these links appear sitewide (i.e., on every page), these page receive multiple internal links, while the other pages receive very few internal links.

Even though the Article Categories on the site break down the articles into substantial sections, the internal links do not seem to pass through to individual articles (which is the case with almost every navigation).

The related post section on each article works well to accomplish this purpose (an example is below), but not every post includes the related post widget.

![KISSmetrics Related Posts](/assets/images/kissmetrics/KISSmetrics-Related-Posts-1024x287.png)

Since KISSmetrics related posts seem to be manually picked, often times, the most recent posts are picked (leaving the older post with fewer internal links). KISSmetrics should continue cross-page linking so that the internal links distribute across other pages.

### **Click Depth**

Click Depth (or crawl depth) is the number of times a website visitor must click on a link from the root domain in order to get to the desired page. The root domain will have a link depth of zero -- since it takes zero clicks to get to the root domain on a webpage.

Search Engines are like humans -- they do not want to waste time trying to find pages hidden deep in a site's architecture. Pages that are available in one click -- thus one page from the homepage -- are deemed more important by search engines than those that are several clicks removed.

It doesn't matter if the URL is KISSmetrics.com/name if it takes Googlebot (and users) 8 clicks to get there.

As the graph below shows, 44% of the site's pages have a click depth of 5 or greater (i.e., they are 5 or more clicks away from the homepage):

![Depth Stats](/assets/images/kissmetrics/Depth-Stats-1024x409.png)

To reduce the click depth, KISSmetrics can create new ways to interlink the site's pages. To accomplish this, KISSmetrics could:

-   Increase the blogroll count to reduce the number of paginated pages (currently, they have 90+) [Revealing more results by scrolling (or swiping) is an established convention ([Kohn](http://www.blindfiveyearold.com/crawl-optimization)).]
-   Link back to the top results from each of the paginated URLs

A flat architecture decreases the distance between high authority pages and all other pages, increasing the chance that low PR pages will be crawled on a more frequent basis.

**On Page Factors**
-------------------

In this section, I will investigate the characteristics of KISSmetrics's pages (e.g., URLs, schema, duplicate content, etc.) that influence the site's search engine rankings. On Page search factors are those that are entirely within KISSmetrics's own control.

### **HTML Markup**

A site's HTML is important because it contains some of the most vital on-page ranking factors.

HTML markup is a machine readable language that is used to tell the browser how to display the text or graphics in the document. Search engines crawl over your pages and semantic markup can identify your pages' most important information. Semantic HTML markup is a way of indicating the meaning of web content to the search engine.

When examining KISSmetrics's pages, I found multiple pages with 5-15 errors per page.

![KISSmetrics errors per page](/assets/images/kissmetrics/KISSmetrics-errors-per-page-1024x161.png)

Many of the issues are easy fixes: open tags, stray elements, attribute errors, etc... Although these aren't extremely critical issues, it's best to clean up as many errors as possible (empty headings, duplicate IDs, attributes, etc). To be fair, most of the errors are output from the plugins that are installed on the blog.

### **Structured Data**

Schema.org mircodata is an extra set of HTML tags that you can add to your HTML elements to let the search engines know specifically what you are talking about. For example, for the KISSmetric blog, they would tag the title as a "headline," the author as an "author" (with authorship), and the date the blog post was published as the "publishedDate."

Now when Google indexes KISSmetrics's blog, it knows specifically what the title of an article is, who the author is, and when the post was published.

Fortunately, KISSmetrics does define structured data on most of their posts (authorship included):

![Structured Data](/assets/images/kissmetrics/Structured-Data.png)

As of late June 2014, [Google's John Mueller announced that Google was making a major change with authorship](http://searchengineland.com/google-plays-authorship-search-results-dropping-profile-image-google-circle-count-195163) - Specifically - dropping the profile photo and circle count from the search listings (supposedly "click-through behavior on this new less-cluttered design is similar to the previous one"). For some reason, I highly doubt this, but KISSmetrics can be the judge.

To make the remaining articles more readable for search engines, I'd recommend adding authorship for guest bloggers.

![Structured Data Testing Tool](/assets/images/kissmetrics/Structured-Data-Testing-Tool-1024x373.png)

**Be Careful with Schema.org**

One caution: I do not recommend schema.org for all HTML elements. For example, consider the search term "how do you boil eggs":

![how do you boil eggs -schema](/assets/images/kissmetrics/how-do-you-boil-eggs-schema-1024x694.png)

Here, you can see that Google is using micro markup (schema) [to scrape the content and place it on Google](https://www.google.com/search?sourceid=chrome-psyapi2&ion=1&espv=&ie=UTF-8&q=how%20do%20you%20boil%20eggs) -- this could potentially hurt click through rates (CTR). The more information you tell Google -- the more you risk Google scraping your content and your site losing sessions.

### **Head Tags**

**rel=publisher**

KISSmetrics has a Google+ page, and they are taking advantage of rel=publisher. Publisher connects the Google+ page to the website, and that results in your Google+ page being displayed in search results whenever anyone is searching for your brand name.

KISSmetrics has rel=publisher markup code on their homepage. If you look at KISSmetrics's results in the SERPs, you will notice they are receiving the markup:

![SERPs Markup](/assets/images/kissmetrics/SERPs-Markup-1024x492.png)

KISSmetrics could, however, update their Google+ profile more often. They currently only update their profile a few times a month. Updating the post more regularly could result in a posts being shown in the results.

***rel=prev / next***

As previously mentioned, KISSmetrics could potentially have a duplicate content issue. In addition to addressing the issues above, these tags are influential in indexing and preventing duplicate content.

Google asks that Webmasters add rel="next" and rel="prev" to paginated archives, so that Google can distinguish them as a series and send users to the most relevant pages. KISSmetrics is doing a great job of using prev/next on individual pages, but they are not currently using prev/next on subpages of archives (page/1/ or sub-pages of /topics/).

They do, however, seem to have an issue using nofollow on pagination. [According to Rand](http://moz.com/blog/pagination-best-practices-for-seo-user-experience), whatever you do, do NOT:

Add nofollow to the paginated links on the results pages. This tells the engines not to flow link juice/votes/authority down into the results pages that desperately need those votes to help them get indexed and pass value to the deeper pages.

Unless KISSmetrics has a valid reason unbeknownst to a third-party, they should consider removing the nofollow links on the blog pagination.

*rel=canonical*

Each KISSmetric post uses a rel="canonical" link; however, all of these links are self-referential and normally are not a problem. The problem arises, however, when both the https and http version are self-referential.

On subpages (/page/2/, etc...), KISSmetrics does not use canonical tags, but on many pages, KISSmetrics uses rel=prev, rel=next, which is actually a common substitute for canonical (according to webmaster tools). Since not all subpages include canonical or rel="prev/next", I'd suggest adding those tags to help the search engines distinguish the paginated series. Since KISSmetrics has 'NOINDEX' on topic subpages, this isn't a problem, but they should consider addressing canonical (or prev/next) on the blogroll, as it is 'INDEX,FOLLOW'.

*NOINDEX*

The last tag KISSmetrics should think about implementing (after checking analytics) is NOINDEX,FOLLOW. They've successfully implemented NOINDEX on the /topics/ but have not used it on subpages on the blog roll. Unless their data says otherwise, they should consider NOINDEX,FOLLOW on these pages.

### **Open Graph**

The Open Graph protocol enables any web page on KISSmetrics's site -- or all sites -- to become a rich object. For instance, the Open Graph is used by Facebook to allow any web page to have the same functionality as any other object on Facebook.

This is the open graph information in their blog (blog.kissmetrics.com) markup [the root domain does not include open graph information]:

![KISSmetrics Opengraph](/assets/images/kissmetrics/KISSmetrics-Opengraph.png)

The above markup translates to:

![Open Graph Translate](/assets/images/kissmetrics/Open-Graph-Translate-1024x266.jpg)

On their blog, they are correctly implementing open graph and might want to include the tag below:

![Correctly Implementing Open Graph](/assets/images/kissmetrics/Open-Graph-2.png)

KISSmetrics may also want to consider adding publisher to the blog as well (and not just the root domain) and verify they have authorship implemented throughout (these tags can also display on open graph - and they currently do not).

### **Twitter Cards**

Twitter cards are another micro markup -- essentially rich snippets for Tweets. Twitter will actually fall back on the Open Graph tags used for FB, but the Open Graph tags aren't comprehensive.

All of KISSmetrics's blog pages include og: tags, which attach additional information to the Tweets associated with those pages by default. However, they should also include (in addition to the og: tags):

![Twitter Cards Meta](/assets/images/kissmetrics/Open-Graph-3.png)

### **Titles**

Each page that is indexed should have unique content and a unique title that effectively summarizes the content for users and search engines.

For titles, Google will show as many characters that a 512 pixel display can show -- thus, around 50-60 characters. The reason the number varies is because some characters are bigger than others (ie, you could fit a lot more "i"s than you could "w"s).

Out of the 1000+ pages on KISSmetrics's website, 393 pages have a width greater than 512 pixels. As you can see below, most of KISSmetrics title's fall in and around the 512 mark, but about ⅓ exceed:

![Page Title Pixels](/assets/images/kissmetrics/Page-Title-Pixels.png)

KISSmetrics's titles average 51 characters, but since the pixels of various characters can exceed 512 pixels, some of the title's are truncated in the SERPs:

![Truncated Titles](/assets/images/kissmetrics/Truncated-Titles.png)

*In some cases, Google no longer truncates the title and adds an ellipsis to the end; instead, Google tries to algorithmically determine a better title for the post (Google changes the title to better match the query. The reason for this is simple: users scan for and assign higher relevance to titles that include their query).

Just out of curiosity, though, let's look at the overall distribution of title lengths that were not cut off: (pre-cut-off):

![Title Character Count](/assets/images/kissmetrics/Title-Character-Count.png)

The good news is that this distribution is roughly normal, peaking at about 54-58 characters. Post-cut-off title tags ranged in length from 55 to 68+ characters. Here's a title cut off at 55 characters (measured at 514 pixels):

![Title Cut Off](/assets/images/kissmetrics/Title-Cut-Off-1024x181.png)

The example above is the only title less than 58 characters that was truncated. In this case, keeping titles within 50-58 characters is the wisest option. It's not worth going back and revising every title based on this new data. KISSmetrics should look at their key pages, view the SERPs, and make sure the snippets show correctly.

KISSmetrics should keep these guidelines in mind for future SEO efforts, but not worry too much.

Lastly, less than 5% of KISSmetrics's titles contain their brand name. To help promote brand awareness, I'd add suggest adding KISSmetrics at the end of each title (| KISSmetrics). Because KISSmetrics is well recognized, including the brand name in the title element could increase search engine clicks.

### **Meta Descriptions**

Meta descriptions are HTML attributes that provide concise explanations of the contents of web pages. Meta descriptions are commonly used on search engine result pages (SERPs) to display preview snippets for a given page (Moz).

Meta Descriptions do not influence the ranking factor of a site's page, but they do influence the CTR (click-through-rate).

It's speculated that Meta descriptions are calculated by pixel width, rather than characters. This pixel width is less than simply 512 pixels multiplied by two (1,024px) which you might expect, and actually the CSS truncation appears to be around 920 pixels. Google uses 13px Arial for meta description text and chop off at word boundaries.

Out of 1,056 unique HTML/Text URLs on the root domain and blog, 97% include a meta description. Over 51% of the meta descriptions are over 920 pixels. As you can see below, the meta description is being truncated:

![Meta Description Truncated](/assets/images/kissmetrics/Meta-Description-Truncated-1024x149.png)

For every page on the site, the meta description is an excerpt of the first sentence. KISSmetrics should consider writing a succinct, unique meta description (no more than 155 characters) in order to help CTR.  Because their meta descriptions are excerpts, many of them are cut off:

![Meta Description Length](/assets/images/kissmetrics/Meta-Description-Length-1024x696.png)

If KISSmetrics does not decide to write a unique meta description for each page, they should consider removing the automatic excerpt on the long-tail articles. If the page is targeting long-tail searches, it may be easier to let the search engines pull in the meta descriptions themselves.

The reason this is more feasible than automatically outputting an excerpt is because when the search engines pull content, they pull content and display keywords surrounding the user's query. If you force a meta description, it can detract from the relevance of long tail search.

In some cases, search engines will overrule your meta description anyways, but you cannot always rely on that. In that regard, it would be advantageous for KISSmetrics to consider adding unique meta descriptions for pages that target only a few keywords (to see if they can increase CTR) and leave the other long-tail pages open for variance.

Since KISSmetrics posts average 2,400 words, they should consider A) writing unique descriptions for the posts, or B) allowing the SERPs to automatically create the description based on the user's query.

### **Images**

For optimization purposes, the two most important image attributes are the image's filename and the image's alt text. Both of these attributes should effectively describe the image's content to provide additional context for search engines and visually impaired users.

Image file names should be descriptive -- not containing random numbers or queries. The file name should describe the image. The file name is information you give directly to the search engines and to other technologies to identify what the information is about.

For the benefit of search engines, compliance (HTML), and the visually impaired, all images on KISSmetrics should also have an ALT tag (Alternative text is text you provide for an image in case it can't be displayed - perhaps the image is broken or the program cannot display the image). The ALT tag should accurately describe the image, and if possible, contain a keyword relevant to KISSmetrics (but only if the keyword is relevant to the image).

One other form of optimization that is not usually included is the text around an image. The text around an image tells a lot about the image itself. This is just another signal telling the search engine what the image is.

If KISSmetrics ensures that images follow these rules, they will increase the likelihood of referral traffic from image searches. KISSmetrics has hundreds of images, and around 81.26% of the images take advantage of the alt text (there are 2,089 images without alt text).

One area that KISSmetrics can improve in is the descriptiveness of the file naming. As you can see below, quite a few of the images are just random strings.

![Random Strings for Images](/assets/images/kissmetrics/Random-Strings-for-Images-1024x249.png)

There are hundreds of images like the ones above on KISSmetrics's blog. I'd suggest adding descriptive title tags to the images to increase organic image search, and also to be HTML compliant.

### **URLs**

The site's URL structure is streamlined, and  KISSmetrics has done a great job crafting their URLs. Their URLs are at an average length of 50 characters (including http://www.kissmetrics).

![KISSmetrics URL Length](/assets/images/kissmetrics/KISSmetrics-URL-Length-1024x710.png)

KISSmetrics could, however, improve some of their URL structures by making them slightly more descriptive. Take these URLs, for example

> [6 Mistakes That Will Kill Your Product Launch](https://blog.kissmetrics.com/6-mistakes/)

> [9 Metrics to Help You Make Wise Decisions About Your Start-Up](https://blog.kissmetrics.com/9-metrics/)

> [How to Make a Landing Page That C.O.N.V.E.R.T.S.](https://blog.kissmetrics.com/c-o-n-v-e-r-t-s/)

KISSmetrics could add one or two more words to the URL to describe what the page is about. The keywords in the URLs above are very vague, and KISSmetrics could potentially help ranking and click through by describing the URL better. For example, an article titled, "Truth Will Out -- Why Authenticity is the Key to Growing Your Business" is found here:

http://blog.kissmetrics.com/truth-will-out/ (the only descriptive keyword is "truth").

Updating these URLs to make them more descriptive (and more closely aligned with their corresponding content) may help in their organic search.

Overall, the site's URL structure is organized and clean. Unfortunately, while crawling the site, I found URLs on 738 pages that returned a 403 or 404 HTTP status codes (i.e., those URLs are no longer accessible). In one post, [50 Resources for Facebook Application Developers](http://blog.kissmetrics.com/50-resources-for-facebook-application-developers/), KISSmetrics states, "Note this post is from 2008 so many of the links are broken." If possible, those links should be redirected and updated.

Another important URL-related consideration is the domain name. Although the domain is not expiring anytime soon, KISSmetrics should keep a watch on the domain's expiration: September of 2015.

### **External Links**

One last item for KISSmetrics to consider is the amount of links they place on each page. [According to Matt Cutts (on the topic of links per page):](http://www.mattcutts.com/blog/how-many-links-per-page/)

> So how might Google treat pages with well over a hundred links? If you end up with hundreds of links on a page, Google might choose not to follow or to index all those links. At any rate, you're dividing the PageRank of that page between hundreds of links, so each link is only going to pass along a minuscule amount of PageRank anyway. Users often dislike link-heavy pages too, so before you go overboard putting a ton of links on a page, ask yourself what the purpose of the page is and whether it works well for the user experience.

KISSmetrics has 61 pages on their blog that exceed 100 links and 4 with 200 external links or more ("[28 Things You Need To Know About The New Facebook Pages](http://blog.kissmetrics.com/new-facebook-pages/)" ranks the highest with 372 outlinks). You can see an example of that post below:

![Lots of External Links](/assets/images/kissmetrics/Lots-of-External-Links-1024x738.png)

Simply put, more links equals less PR for those links. The actual math of PR gets fuzzy fast, but for best measures, KISSmetrics should consider keeping their links under 100 per page (even if for user as experience).

**Off - Page Factors**
----------------------

This section will cover some of the most influential factors in ranking: backlinks and social engagement.

### **Backlinks**

Links are not everything when it comes to SEO, but search professionals and companies attribute a large portion of the search engines' algorithms to backlinks (Larry Page based Google off of the Educational Citation Method -- ie. A professor who was cited by other authors was considered more credible -- Read his dissertation for more information).

When analyzing backlinks, you should consider: Total number of links, link quality, number of unique domains, fresh/incoming links, and anchor text usage.

To start, I first recorded how many backlinks KISSmetrics had received over the past few months. The charts below show the growth of KISSmetrics's backlink profile over the course of one year. Below is a chart of blog.kissmetrics.com:

![Growth of KISSmetrics backlink profile](/assets/images/kissmetrics/Growth-of-KISSmetrics-backlink-profile.jpg)

After comparing the backlink analysis above to both [Majestic SEO](http://www.majesticseo.com/reports/site-explorer?q=kissmetrics.com&oq=kissmetrics.com&IndexDataSource=F) and Moz, there was not much of a difference. KISSmetrics was consistently growing their unique domain backlinks until a steep drop in March, and has started a recent growth once more.

Both the root domain and the blog subdomain have the same drop, and combined they have around 16,000 unique domain backlinks.

To see how KISSmetrics's backlink growth matches up over the years,[ I compared their root domain growth with their blog domain growth](http://www.majesticseo.com/reports/site-explorer?q=kissmetrics.com&oq=kissmetrics.com&IndexDataSource=F):

![Root Domain vs Blog Domain Growth](/assets/images/kissmetrics/Root-Domain-vs-Blog-Domain-Growth-1024x263.png)

As you can see above, the blog backlinks are growing at a much faster pace than the root domain backlinks (and they should be, since new content is created daily on the blog).

Since KISSmetrics's blog is outpacing the root domain in backlinks, should they move the blog to a subdirectory?

**The Case for Subdirectories (versus Subdomains)**

[Matt Cutts has said](http://www.mattcutts.com/blog/subdomains-and-subdirectories/):

> [Subdomains and Subdirectories] are roughly equivalent. I would basically go with whichever one is easier for you in terms of configuration, your CMSs, [and] all that sort of stuff.

Although it seems like subdomains and subdirectories can be treated equally, Cutts uses very vague language; "roughly equivalent" is still not equivalent.

**KISSmetrics should consider testing out subdirectories over subdomains for 2 main reasons:**

**First**, there is a correlation between pages on the root domain and higher rankings. [According to Rand at Moz](http://moz.com/community/q/moz-s-official-stance-on-subdomain-vs-subfolder-does-it-need-updating):

> I would still strongly urge folks to keep all content on a single subdomain. We recently were able to test this using a subdomain on Moz itself (when moving our beginner's guide to SEO from guides.moz.com to the current URL http://moz.com/beginners-guide-to-seo). The results were astounding -- rankings rose dramatically across the board for every keyword we tracked to the pages.

**Second**, fewer subdirectories tend to create a better user experience and flow. As it stands, KISSmetrics exist in silos. Although the subdomains are clean, they do not make for the best of navigation.

KISSmetrics should also consider how their links pass from root domain to subdomain. Since their root domain has over 3K links, and the other subdomain (the blog) has over 13k, KISSmetrics should consider link equity. With only 16 pages on the root domain -- and a lot of that being less viewed, weaker content  - they should at least think about the potential of combining the subdomain and root (with 301, of course).

**The Case for Subdomains (versus Subdirectories)**

There is also the stance that subdomains work equally as well. Some of the benefits of using a subdomain are:

-   Links from the root domain (since subdomains are treated as a separate site)
-   Get links "from another website" (subdomains are treated pretty much as such). Ability to link back to priority pages on the root domain.
-   Piggyback on the authority of the root domain.
-   Can be hosted anywhere. Since KISSmetrics has a https root domain (and they use Amazon), putting the blog on a subdomain makes for easier hosting - such as WP Engine.

And yet again, Cutts has said "[Subdomains and Subdirectories] are roughly equivalent". In any manner, it's a possibility worth testing.

### **Backlink Distribution**

To monitor KISSmetrics's backlink distribution -- the links dispersed among all of their pages -- I used Moz's Pro Tools to analyze the backlinks for each page on KISSmetrics's site.

![Backlink Disctribution](/assets/images/kissmetrics/Backlink-Discribution.png)

KISSmetrics has -- according to Moz, Majestic and Ahrefs -- around 16,000 referring domains. According to the data, 75% of all KISSmetrics's pages have backlinks. Many of their pages with multiple links are the embeddable infographics.

### **Backlink Source**

To analyze KISSmetrics's backlinks, I used [Majestic SEO](http://www.majesticseo.com/reports/site-explorer?q=kissmetrics.com&oq=kissmetrics.com&IndexDataSource=F). Here is a plotting of their backlinks:

![Plotting of Back Links](/assets/images/kissmetrics/Plotting-of-Back-Links-1024x524.jpg)

The site has quite a few quality backlinks. [When analyzing Majestic](http://blog.majesticseo.com/development/flow-metrics/), you are hoping to see the links fall to the top right. Citation Flow is link juice and the Trust Flow is how close those links are to trustworthy, authoritative sources.

Correlating with the data above, only a handful of KISSmetrics's links that I checked appeared spammy, and a few of the links over-optimized anchor text. Currently, there is a trust ratio of .672 on KISSmetrics and .660 on blog.KISSmetrics, so it would be worthwhile for KISSmetrics to examine their backlink profile. (It would be encouraging to see the ratio greater than 1).

One last caution: KISSmetrics should be careful of websites using links in headers and footers that repeat across the site. These sitewide links are heavily scrutinized by Google's Penguin update.

### **Anchor Text Distribution**

After Penguin, Panda, etc -- it's important for KISSmetrics to conduct an anchor text analysis. Over the years, there were many ways to manipulate rankings on Google, and links were one of them. Google has always been aware of this, and they are finally cracking down (in fact, anchor text misuse will trigger the Penguin filter quickly).

This is a great rule of thumb to follow:

70% (or higher!) brand, URL, brand+keyword, and non-targeted anchor texts (Branded Links, White Noise, Naked URL, Titles, and Image)

25% partial, phrase, and broad match keyword anchor texts (Compound)

5% exact match anchor texts (Exact Match)

On the blog, the anchor text distribution follows the above guidelines. [The root domain is displayed below](http://www.majesticseo.com/reports/site-explorer-search?folder=&q=kissmetrics.com&IndexDataSource=F):

![Anchor Text Distribution](/assets/images/kissmetrics/Anchor-Text-Distribution.png)

85% of KISSmetrics backlinks include a branded identity - this anchor text appears natural. You generally expect to see many branded links, and 85% is rather high. It's not a bad thing - with Google's preference for branded terms, it's much better than exact match anchor text.

One of the reasons the links feature the brand is because the root domain doesn't have a blog - thus very little to link back to via anchor text.

### **Image Links**

KISSmetrics should consider removing all links that open the same image in a new tab. For example - if you click some of the blog images on KISSmetrics - they open the images in a new tab (creating an extra link):

KISSmetrics should consider removing that extra link. These extra links are an innate WP function that can easily be changed in functions.php:

update_option('image_default_link_type','none');

This removes one extra link on the page (saving inbound and external links) and helps with UX and CRO by keeping the user on the page. They've done a great job removing most of these, but a few posts have images that target new tabs.

**Conversion / Leads**
----------------------

Once KISSmetrics has visitors on their site (mainly from SEO), the next step is to convert those visitors into leads by gathering their contact information (in KISSmetric's case, their email addresses). This leads us into the second stage of inbound marketing, conversion and lead generation. This section will examine calls to action, landing pages, forms, and contacts.

### **Calls-to-Action**

A call-to-action (CTA) is an image or text that encourages users to take action, by subscribing to a newsletter or requesting a product demo. In most cases, CTAs should direct people to landing pages, where collection of information can be made. In that sense, an effective CTA results in more leads and conversions for your website (via Hubspot).

Let's start at the very beginning. KISSmetrics should have calls to action on the homepage. It's probably the most frequently visited page on KISSmetrics and presents an opportunity to drive traffic for lead generation. In fact, some say the homepage should have at least three calls-to-action.

![KISSmetrics Calls to Action](/assets/images/kissmetrics/KISSmetrics-Calls-to-Action-1024x484.png)

KISSmetrics has an offer and at least three calls to action -- asking people to log in with Google Analytics, get a three minute overview, or sign in. This page is doing exactly what it is supposed to: narrowing the focus and removing clutter that could distract visitors.

On the blog, there are multiple calls to actions on the page: 3 in the sidebar, 1 in the footer, and one after the post entry. The three calls to actions in the sidebar (as you can see below), do not change:

![Consistent Calls to Action](/assets/images/kissmetrics/Consistent-Calls-to-Action-1024x484.png)

In a perfect world, it would be nice if these offers changed (mainly the webinar) based on content, but limited personnel and resources normally restrict.

The last CTA to address is the after post CTA. During the audit, there were only two live CTA's after the posts:

![After Post Live CTAs](/assets/images/kissmetrics/After-Post-Live-CTAs.png)

If the content was filed under the topics "Twitter" or "Social Media," the visitor received the Linkedin CTA (the one on the right). If the user was on a page about any other topic, he or she received the CTA about marketing funnels.

As compelling as the offers can be, in some cases, they were not applicable. If a user read a post about "6 Ways to Make Customers Fall in Love With Your Brand," they received the Marketing Funnel CTA. The CTA does connect in a way, but there could be a more compelling offer.

Or, if a user was reading "How Typography Affects Conversions," they were greeted with the same marketing funnel offer. Again, relatable, but not the best offer. A better offer for Typography might have been a free download of:

![Color Pyschology Marketing Guide CTA](/assets/images/kissmetrics/Color-Pyschology-Marketing-Guide-CTA.png)

This is a free marketing guide that KISSmetrics has already created that would make a suitable offer. I understand that creating free materials for downloads can be time consuming. But, KISSmetrics already has done all the work. They have multiple free ebooks that would make for compelling CTAs:

![Multiple Free EBooks](/assets/images/kissmetrics/Multople-Free-EBooks.png)

To improve their CTA's, I'd suggest KISSmetrics use more than two after post CTAs and create more compelling offers by using the free material they already have. Their free ebooks are outstanding.

### **Landing Pages**

A landing page is a web page that allows you to capture a visitor's information. On your landing page, your visitors will find a form that they can fill out to receive an offer ([HubSpot](http://www.hubspot.com/)).

If you were to click on any of the after entry CTA's mentioned above ([Linkedin](http://grow.kissmetrics.com/guide-to-linkedin) or [Leaky Marketing Funnels](http://grow.kissmetrics.com/leaky-funnels)), you would have been brought to one of these landing pages:

![Landing Pages by KISSmetrics](/assets/images/kissmetrics/Landing-Pages-by-KISSmetrics-1024x417.jpg)

And honestly, there isn't much to say about these pages.

These pages are to the point, use contrasting colors, gain ethos from the logo, are well designed, and are consistent.

### **Forms**

Without knowing the sales and marketing goals behind the forms, it is hard to make an accurate analysis of the forms. Although [short forms normally do better](http://www.quicksprout.com/2012/06/25/5-ways-to-improve-your-contact-form-conversion-rate/), KISSmetrics's longer forms are warranted because they are seeking more qualified leads. They could, however, use auto generated forms.

### **Thank You Page**

Every landing page should be followed by a thank you page. Here is what KISSmetrics's [Thank you pages look like:](http://grow.kissmetrics.com/thank-you)

![Followed by a Thank You Page](/assets/images/kissmetrics/Followed-by-a-Thank-You-Page-1024x387.jpg)

I tried multiple options on the forms to generate different thank you pages. The only difference in the pages is the left page is because I asked for a demo (I'm interested) and the right is because I declined a demo.

With these thank you pages, the user is trapped with no navigation and no truly compelling next step to take.

Kissmetrics should consider bringing back the navigation, adding social sharing icons (the user did just download an offer), direct the user to other relevant content, or reconvert by asking if a user is interested in another product.

As it stands, the user will close the page and leave.

**Close / Customers** 
----------------------

Closing refers to transforming leads into customers. This generally includes a wide array of options (lead scoring, email, marketing automation, CRM, etc [HubSpot]) but since this audit didn't engage with KISSmetrics sales team, this section will focus on contacts and email.

### **Contacts / Email**

After I finished the form and closed out the thank you pages, I received my free downloads via email:

![Free Downloads via Email Picture](/assets/images/kissmetrics/Free-Downloads-via-Email-Picture-1024x654.jpg)

The download worked. The only problem with the email (and this is being picky) is that Lars Lofgren's signature was on the landing page, but Magi and Dan sent the email. It is a small detail, but since the email is automated, it should be an easy change.

Overall, the email hit the main 6 points:

-   A clear subject line.
-   An actual person sent the email (although not my friend Lars).
-   Branding
-   Personalized
-   Focused CTA
-   Unsubscribe Link

*Suggestion: there is no sharing or forwarding built into the email.*

**Delight**
-----------

Inbound marketing is all about converting leads into customers. Just because someone has signed up does not mean the process is over. Inbound should continue by engaging with, delighting, and creating brand advocates.

This next stage of inbound marketing is all about engaging with and (hopefully) keeping their future and current customers happy.

### **Social Media**

Besides using social media as a customer service tool, we cannot ignore the fact that social media is a search engine of sorts. People on social media are researching, searching, interacting, and engaging -- and at very high engagement rates. [According to Statisticbrain](http://www.statisticbrain.com/twitter-statistics/), the number of Twitter search engine queries every day is over 2.1 billion. In any regard, a site's success is largely dependent on social success and social engagement.

The chart below ( via Social Crawlytics ) provides a visual of how KISSmetrics's shares are split concerning a search engine's point of view. The center represents the first page, and each segment beyond it are pages linked from that page (in this case -- the blog roll page). Segments beyond that are linked to their parent. Pages with no shares are not included or shown (click on the image to zoom in and to read the text).

![Circle Graph](/assets/images/kissmetrics/Circle-Graph-1024x933.jpg)

As you can see from the graph above, the center represents the blog homepage, and all articles off of the homepage. The graph below breaks down that same content by social network:

![Social Media Shares Breakdown for KISSmetrics](/assets/images/kissmetrics/Social-Media-Shares-Breakdown-for-KISSmetrics-1024x933.png)

Not surprisingly, KISSmetrics does really well on Pinterest. As you can tell from the graph below, many of their most shared posts come from infographics:

![Shares of Infographics](/assets/images/kissmetrics/Shares-of-Infographics-1024x281.png)

**Engaging Content**
--------------------

Besides social shares and traffic (which have already been measured), the next best tell for engaging content is commenting. On average, KISSmetrics receives 22 comments for each post.

As you can see from the graph below, KISSmetrics actually receives quite a few comments for each post:

![Comment Count](/assets/images/kissmetrics/Comment-Count-1024x682.png)

There are no recommendations for KISSmetrics on this (they average 22 comments per post). Their engagement level is great, and even Shah and Patel comment regularly (a great place for users to learn).

**Summary**
-----------

If you read everything in this audit example, I am truly impressed. If you cheated and jumped straight down to this section, I'll forgive you. Either way, this section contains a summary of my most important observations for KISSmetrics and tips for you as you audit your site:

**Check for Duplicate content**

1.  Always check your canonical tag (Click view source, push Command + F (Mac), and type "canonical"). It's that easy - you don't need a specialized tool. In this audit, there is cause for concern on KISSmetrics's site with duplicate content and the canonical tag. As you begin to look over their third-party data, there is a strong correlation between the data (although third party) and Google's Panda update.
2.  Use Google's site operators to check for duplicate content (site:domain.com). On the last Search Engine Results page, if you see the dreaded "In order to show you the most relevant results, we have omitted some entries very similar to the # already displayed.", you need to check your content. There is cause for concern with KISSmetrics and duplicate content as this appears with their search.

**Check for Indexability**

1.  Check your robots file. Make sure that you are allowing robots by visiting yourdomain.com/robots.txt. If you do not have a robots file, consider creating one. KISSmetrics doesn't have a problem with robots.txt, but they do have a broken sitemap in the robots.txt.
2.  Check your meta robots tags. These are page level tags that have the ability to de-index your content. KISSmetrics uses these tags well, but KISSmetrics should consider adding "NOINDEX" to subpages of their blog to prevent duplicate content.

**Check for On Page Errors**

1.  Check your site for broken links (especially if you have an older blog where links may have changed). Broken links kill your UX and end your link credibility. You can use a free tool called "Integrity" to check your backlinks. KISSmetrics has quite a few hundred broken links they should update.
2.  Measure your click depth (you can do it manually using Excel or with tools like Screaming Frog). Click Depth (or crawl depth) is the number of times a website visitor must click on a link from the root domain in order to get to the desired page (It doesn't matter if the URL is KISSmetrics.com/name if it takes Googlebot (and users) 8 clicks to get there.). 44% of KISSmetric's pages have a click depth of 5 or greater.
3.  Check your site speed on Google, Pingdom, or GTMetrix (all free).KISSmetrics's site speed is fairly slow, and KISSmetrics could easily make a few tweaks to make their site much more efficient.

**Check Backlinks**

1.  Check the number of backlinks (you should mainly be concerned with referring domains). You can use limited free tools like Majestic, Ahrefs, or Moz. KISSmetrics is consistently growing their unique domain backlinks until a steep drop in March, and has started a recent growth once more.
2.  Check your backlink anchor text. After Penguin, Panda, etc -- it's important for you to conduct an anchor text analysis. This is a great rule of thumb to follow: (70% (or higher!) brand, 25% partial, phrase, and broad match keyword, 5% exact match anchor texts. KISSmetrics anchor text is excellent - with 85% of the anchor text branded.
3.  Check your backlink source with [Majestic](http://www.majesticseo.com/). When analyzing Majestic, you are hoping to see the links fall to the top right. Currently, KISSmetrics has a trust ratio of .660 on blog.KISSmetrics, so it would be worthwhile for KISSmetrics to examine their backlink profile (we were aiming for a 1).

**Final Thought**

As important as SEO is, it doesn't exist in a silo. I hope this audit integrates SEO and inbound marketing to create a cohesive strategy and plan for KISSmetrics in the future. After the entire audit, I leave with a lot of respect for KISSmetrics, and I hope you do as well. I hope this helps them succeed.

This audit has proven three things:

1.  No company is perfect. Even the best companies have to constantly monitor their internet marketing. This should be an encouragement for all -- we all miss things in our inbound / SEO.
2.  If there is a company that is putting their best foot forward in inbound, it's KISSmetrics.
3.  You won't meet better guys than Hiten Shah or Neil Patel.

Best of luck, KISSmetrics.

[**What Do You Think?** ](https://okdork.com/a-complete-audit-of-kissmetrics-seo-and-inbound-marketing/#commentform)