---
layout: post
title:  "How I'd Help Wistia Improve Their SEO: An In-Depth Audit"
date:   2011-11-10 10:18:00
permalink: improve-wistia-inbound-audit
---


<p>I love SEO and inbound marketing, which means I spend too much time looking at marketing sites: Inbound.org, Hubspot, Moz, etc… A few days ago, I was reading up on Video Optimization on Wistia, and after looking through their site, I wanted to offer a few thoughts.</p>

<p>I’m sure Wistia’s people have already analyzed this design from a funnel and business perspective, but maybe no one has analyzed the SEO ramifications?</p>

<p><a href="http://wistia.com/shirts" target="_blank"><em>Perhaps, I’ll get a free T-shirt.</em></a></p>

<p>Wistia certainly has thought about SEO from a product perspective; their video embeds for SEO are top notch (seriously, I could not be more of an advocate for Wistia Video Hosting after spending weeks auditing – I’d never host my videos anywhere else – and that’s saying a lot – so <a href="http://wistia.com/free/new" target="_blank">Get Started Here</a> [not an affiliate link] or <a href="https://www.distilled.net/blog/video/getting-video-results-in-google/" target="_blank">check out this great article via Phil Nottingham at Distilled</a>).</p>

<p>But what about using SEO to market their own website? They currently rank #1 for “video hosting,” but given the right tools, could they increase their organic traffic and CRO? As I looked through their employees, I didn’t see an SEO Analyst or Inbound Manager who is specifically devoted to this issue, so I thought I could offer some fresh perspective.</p>

<p>The last major redesign for Wistia happened during the first week of April in 2013. Since a year old website is ancient in web standards, and a redesign may be in the future, I thought now would be a great time to chime in.</p>

<p><img class="aligncenter size-large wp-image-2193" src="/images/wp-uploads/2014/05/Wistia-Team-1024x523.jpg" alt="Wistia Team" width="1024" height="523" /></p>

<p>In this post, I’ve put together a detailed,<strong> technical SEO Audit</strong> for Wistia. My audit is widespread and comprehensive, covering a wide range of SEO topics (e.g., article listings, structured data, duplicate content, backlink analysis, etc.). But before the audit, let’s cover the basics…</p>

<h2 id="who-is-wistia">Who is Wistia?</h2>

<p><a href="http://wistia.com/">Wistia Inc</a>. is an internet video hosting and analytics company that was founded in April 2006 by Brown University graduates Chris Savage and Brendan Schwartz.</p>

<p><a href="http://wistia.com"><img class="aligncenter size-large wp-image-2191" src="/images/wp-uploads/2014/05/Video-Hosting-for-Business-2014-05-04-14-27-33-1024x495.png" alt="Video Hosting for Business 2014-05-04 14-27-33" width="1024" height="495" /></a></p>

<h4 id="disclaimer">Disclaimer</h4>

<p>Before I jump into the technical details of the audit, it’s important to note that I have no affiliation with Wistia. As a result, I don’t have access to any of the site’s analytics or webmaster tools accounts, and I don’t have access to the site’s content management system (CMS).</p>

<p>I also did not want to hammer their site’s bandwidth using multiple crawlers, thus if my data is inaccurate, I blame my sincerity. If this were a typical audit, I’d run through their analytics and start the assessment from there, but for this audit, I am relying exclusively on third-party data.</p>

<p>So… if I make completely inaccurate observations, I blame the third party, ie (Searchmetrics, Ahrefs, SEMrush, Moz, etc…). You may have noticed similar audits on <a href="http://www.webgnomes.org/blog/grantland-seo-audit-example/" target="_blank">Webgnomes</a>, <a href="http://moz.com/blog/how-to-perform-the-worlds-greatest-seo-audit" target="_blank">Moz</a>, and <a href="http://www.quicksprout.com/2013/02/04/how-to-perform-a-seo-audit-free-5000-template-included/" target="_blank">Quicksprout</a>. I have no problem admitting I used their layouts as a template and even linking to them, but of course, all of the data here is relevant to Wistia. With that disclaimer out of the way, let’s roll.</p>

<h2 id="table-of-contents">Table of Contents</h2>

<p>Since this post will be extremely long – here is a detailed navigation to help you understand where you are throughout this audit.</p>

<ul>
  <li><a href="#organic">Organic Search Visibility</a></li>
  <li><a href="#index">Index-ability</a>
    <ul>
      <li><a href="#robots">Robots</a></li>
      <li><a href="#metatag">Robots Meta Tag</a></li>
      <li><a href="#sitemaps">XML Sitemap</a></li>
    </ul>
  </li>
  <li><a href="#accessibility">Accessibility</a>
    <ul>
      <li><a href="#performance">Performance</a></li>
      <li><a href="#architecture">Site Architecture</a></li>
      <li><a href="#usability">Usability</a>
        <ul>
          <li><a href="#clickdepth">Click Depth</a></li>
        </ul>
      </li>
    </ul>
  </li>
  <li><a href="#onpage">On Page Factors</a>
    <ul>
      <li><a href="#markup">HTML Markup</a>
        <ul>
          <li><a href="#schema">Structured Data</a></li>
          <li><a href="#descriptions">Meta Descriptions</a></li>
          <li><a href="#headtags">Head Tags</a>
            <ul>
              <li><a href="#opengraph">Open Graph</a></li>
              <li><a href="#twittercards">Twitter Cards</a></li>
            </ul>
          </li>
        </ul>
      </li>
      <li><a href="#titles">Titles</a></li>
      <li><a href="#urls">URLs</a></li>
      <li><a href="#images">Images</a></li>
      <li><a href="#transcripts">Transcripts</a></li>
      <li><a href="#duplication">Content Duplication</a></li>
    </ul>
  </li>
  <li><a href="#offsite">Off Page Factors</a>
    <ul>
      <li><a href="#backlinks">Backlinks</a>
        <ul>
          <li><a href="#subdomains">Subdomain Backlinks</a></li>
          <li><a href="#backlinkdistribution">Backlink Distribution</a></li>
          <li><a href="#backlinksource">Backlink Source</a></li>
          <li><a href="#anchor">Anchor Link Analysis</a></li>
        </ul>
      </li>
      <li><a href="#socialengagement">Social Engagement</a></li>
    </ul>
  </li>
  <li><a href="#50grove">50 Grove</a></li>
  <li><a href="#inbound">Inbound Marketing</a></li>
  <li><a href="#summary">Summary</a></li>
</ul>

<h2 id="organic">Organic Search</h2>

<p>In order to set the framework for the entire audit, it’s important to analyze the site’s organic performance. When looking at Wistia’s organic traffic, there are 3 important questions:</p>

<ol>
  <li>Is the organic traffic growing?</li>
  <li>Has the site been penalized?</li>
  <li>What is the percentage of organic traffic?</li>
</ol>

<p>To determine Wistia’s SEO performance, I used two tools: <a href="http://suite.searchmetrics.com/en/research/domains/organic?url=wistia.com" target="_blank">Searchmetrics Suit</a>, and one of my new favorites, <a href="http://new.similarweb.com/website/wistia.com" target="_blank">Similar Web</a>. Again, finding accurate third party data is incredibly difficult, but after using Google Analytics on a network of sites, I’ve found that these two programs provide the most accuracy in capturing data.</p>

<p><a href="http://new.similarweb.com/website/wistia.com" target="_blank"><img class="aligncenter size-large wp-image-2343" src="/images/wp-uploads/2014/05/Screen-Shot-2014-05-18-at-9.01.07-PM-1024x281.png" alt="Organic Search" width="1024" height="281" /></a>As this graph shows, Wisita’s traffic is growing. It is estimated that the monthly traffic to Wistia.com is 4.8 million, with a high time-on-site average and an extremely low bounce rate. Things are looking pretty good for Wistia, but let’s take a closer look.</p>

<p>Based on the data above, we are looking at all traffic (referrals, organic, paid, etc…) but we are really interested in <em>organic</em> for this audit. To get a better picture, we need to run some numbers and exclusions.</p>

<p><strong>First Exclusion:</strong> Wistia’s users accounts (user.wistia.com) are each included in total sessions (more on that in the analysis below). This explains why the bounce rate is extremely low and the time on site is extremely high. When you sign up for an account at Wistia.com, you receive an account on a subdomain of wistia (elioverbey.wistia.com). Thus, users are repeating visits to their subdomain to login (lowering bounce) and upload videos (increasing time on site). This first exclusion removes over 51% of all visits. (As you can tell by the graph below, I am being generous by not excluding fast.wistia and secure.wistia).</p>

<p><a href="http://new.similarweb.com/website/wistia.com" target="_blank"><img class="aligncenter size-full wp-image-2344" src="/images/wp-uploads/2014/05/Screen-Shot-2014-05-18-at-9.04.30-PM.png" alt="Subdomains" width="694" height="534" /></a></p>

<p>This exclusion removes 2,457,600 visits, and we are left with only 48.98% of visitors actually visiting a Wistia front-facing site (http://wistia.com, secure.wistia.com, embed.wistia.com, etc…).</p>

<p><strong>Second Exclusion: </strong>According to the third party data, only 10.56% of all visits are organic.</p>

<p><a href="http://new.similarweb.com/website/wistia.com" target="_blank"><img class="aligncenter size-large wp-image-2345" src="/images/wp-uploads/2014/05/Screen-Shot-2014-05-18-at-9.02.17-PM-1024x513.png" alt="Organic Traffic" width="1024" height="513" /></a></p>

<p>If you do the math, we are left with roughly 248,269 organic visitors per month to Wistia.com.</p>

<p><strong>Why exclude subomain / user accounts?</strong></p>

<p>In this scenario, if I would have just taken 10% (organic) of 4.8M (all visits), I’d have inaccurate data. Since organic only applies to those coming from search, I know that users’ subdomains should not be included in organic data because their robots.txt makes it difficult for them to appear in search (more on that below).</p>

<p><em>Thus, user subdomains were excluded – leaving us with an average of 250,000 organic visitors per month.</em></p>

<p>In any regard, Wistia should always be looking to improve their 10% organic search. It could be said that most of Wistia’s traffic is branded, and so, much of their traffic is direct. But, with Wistia only being 8 years old, the branded traffic is young as well – thus it’d be nice to see organic hovering around 25%.</p>

<p>One very positive thing to note: in the last 6 months, Wistia does not seem to have been hurt by any penalties from Google. Again, you cannot trust the graph above because it contains all traffic and not just organic, but other graphs from Search Metrics show a similar pattern:</p>

<p><a href="http://suite.searchmetrics.com/en/research/domains/organic?url=wistia.com" target="_blank"><img class="aligncenter size-large wp-image-2348" src="/images/wp-uploads/2014/05/Screen-Shot-2014-05-18-at-9.56.10-PM-1024x327.png" alt="Screen Shot 2014-05-18 at 9.56.10 PM" width="1024" height="327" /></a>There does seem to be a drop in keyword rankings from January to end of March, but luckily, there were no major updates released in that time period (just anonymous soft Panda updates). The cause could be that one of their major keywords “video hosting” seems to fluctuate quite a bit.</p>

<h2 id="index">Index-ability</h2>

<p>To find how many of Wistia’s pages are actually out there, I crawled their entire site using Screaming Frog’s SEO Spider and Xenu Link Slueth. The crawlers found thousands of URLs, and after multiple crawls, I successfully crawled 5,685 unique pages. Of that, 2,325 URLs were on the Wistia root domain [http://wisita.com/].</p>

<p>Finally, there were 1,243 of those pages that were html/text. It gets complicated with Wistia because they host their customers’ videos on subdomains, so that a user who uses Wistia gets a url similar to: user.wisita.com. Those subdomain URLs were not included in the crawl.</p>

<p>Based on my two previous site crawls, I was able to successfully crawl 5,685 unique pages. But, according to the search operator “site:”, Google has indexed quite a bit more. 31,400 to be exact.</p>

<p><a href="https://www.google.com/search?q=site%3Awistia.com&amp;oq=site%3A&amp;aqs=chrome.0.69i59l3j69i57j69i58.2278j0j1&amp;sourceid=chrome&amp;es_sm=91&amp;ie=UTF-8" target="_blank"><img class="aligncenter size-large wp-image-2237" src="/images/wp-uploads/2014/05/Screen-Shot-2014-05-13-at-9.56.34-PM-1024x225.png" alt="Indexability" width="1024" height="225" /></a></p>

<p>According to this, Google has been able to crawl 6 times more than what I was able to crawl. But we need to keep in mind that the high result number is known to be inaccurate. On the other hand, it shows that Wistia needs to start “no-indexing” some of their content because when you navigate to page 54 on Google, you are greeted with this warning:</p>

<p><a href="https://www.google.com/search?q=site%3Awistia.com&amp;oq=site%3A&amp;aqs=chrome.0.69i59l3j69i57j69i58.2278j0j1&amp;sourceid=chrome&amp;es_sm=91&amp;ie=UTF-8#q=site:wistia.com&amp;start=530" target="_blank"><img class="aligncenter size-large wp-image-2238" src="/images/wp-uploads/2014/05/Screen-Shot-2014-05-13-at-10.03.08-PM-1024x400.png" alt="Duplicate Content" width="1024" height="400" /></a></p>

<p>This warning suggests duplicate content issues. If you repeat the search with omitted results, you will notice 4 things:</p>

<p><img class="aligncenter size-large wp-image-2239" src="/images/wp-uploads/2014/05/Screen-Shot-2014-05-13-at-9.56.20-PM-1024x235.png" alt="Repeat Search" width="1024" height="235" /></p>

<p><strong>First,</strong> If you navigate to the last page, there are only around 6,000 pages indexed – which is much closer to my crawl estimate.</p>

<p><strong>Second, </strong>There are broken links that should be absolved. There are not many (only 119) links that should be cleaned up.</p>

<p><strong>Third, </strong>There are duplicates that should be de-indexed. Wistia has hundreds of pages that are indexed that are basically copies of each other. Take for example: <span style="color: #006621;">wistia.com/blog?page=38</span> (Below).</p>

<p><a href="http://wistia.com/blog?page=38%20" target="_blank"><img class="aligncenter size-full wp-image-2240" src="/images/wp-uploads/2014/05/Wistia-at-Work-2014-05-13-22-19-20.png" alt="Wistia at Work 2014-05-13 22-19-20" width="979" height="677" /></a></p>

<p>These blog roll pages should be noindex, follow. <a href="http://googlewebmastercentral.blogspot.com/2011/09/pagination-with-relnext-and-relprev.html" target="_blank">Wistia has done a great job of implementing rel=prev/next</a>, and according to the Official Google Webmaster Blog, they are meeting the standards:</p>

<blockquote>
  <p>When you implement rel=”next” and rel=”prev” on component pages of a series, we’ll then consolidate the indexing properties from the component pages and attempt to direct users to the most relevant page/URL. This is typically the first page. There’s no need to mark page 2 to n of the series with noindex unless you’re sure that you don’t want those pages to appear in search results.</p>
</blockquote>

<p>Based on that information, Wistia has marked up their information correctly, but in this scenario, they “are sure” they do not want these pages crawled. Using a robots meta tag here to “noindex, follow” the pages would be encouraged since the rel/prev is still being indexed. In this case, rel/prev is preventing a duplication issue, but it is not solving the indexing issue.</p>

<p><strong>Fourth,</strong> Wistia’s product is built on a subdomain model. The reason for so many URLs is because each new user of Wistia gets a subdomain on the URL. I tried out the sign-up process:</p>

<p><img class="aligncenter size-large wp-image-2241" src="/images/wp-uploads/2014/05/Screen-Shot-2014-05-13-at-10.15.22-PM-1024x628.png" alt="Wistia Subdomain" width="1024" height="628" /></p>

<p>They have correctly added a disallow in the robots.txt to each user’s profile (more on that in a moment), but to better enforce the issue, Wistia should consider adding a robots meta tag that noindexes all subdomains at the page level. They could keep the “follow” aspect, and could benefit from links back to the subdomains. Here is the current setup:</p>

<p><img class="aligncenter size-full wp-image-2242" src="/images/wp-uploads/2014/05/sitewistia.com-Google-Search-2014-05-13-22-32-06.png" alt="site:wistia.com - Google Search 2014-05-13 22-32-06" width="979" height="677" /></p>

<p>The subdomains are being indexed, but Wistia is not receiving any credit for them. Another concern is that the crawl budget is being affected. While it’s good that most of Wistia’s content is being crawled, the subdomains are taking away from the bots crawling Wistia’s main pages. They are giving a lot of room away to subdomainers who are disallowed anyways.</p>

<h3 id="robots">Robots.txt</h3>

<p>A <span class="s1">robots.txt file</span> is used to restrict search engines from accessing specific sections of a site. <a href="http://wistia.com/robots.txt" target="_blank">Here is a copy of Wistia’s root domain Robots.txt file</a>:</p>

<p>The first record in robots.txt file explains how to write and use the robots file. The next entry is telling the webmaster how to use the file. The third record politely asks all bots (bots used by all search engines are identified with the aterisk) to not crawl the old blog /oldblog/.</p>

<p>Finally, the remaining records simply specify the locations for Wistia’s XML Sitemaps and are technically accurate. In any case, I would recommend moving the sitemaps entries to the top of the robots.txt</p>

<p><strong>There are a few improvements that Wistia could make in the construction of their robots.txt.</strong></p>

<p>Robots.txt is ONLY a way in which to tell a search engine bot which pages it’s allowed to spider, to “see”, and which pages it cannot “see.”</p>

<p>This is not telling search engines if they can include them in their index or not. There is a huge difference. For example, Google will sometimes list URLs that it’s not allowed to spider, because it’s blocked by robots.txt, yet it still shows up in their index.</p>

<p>Wistia should update their robots file because the /oldblog/ contains links. The problem is, right now, the links towards that blog don’t count towards the credibility of Wistia because they’re blocked, but Google displays the page anyway in the search results; It looks something like this:</p>

<p><img class="aligncenter size-large wp-image-2200" src="/images/wp-uploads/2014/05/Wistia-Old-URLs.jpg" alt="Wistia-Old-URLs" width="889" height="426" /></p>

<p>In order to avoid “A description for this result is not available because of this site’s robots.txt – learn more,” <strong>There are two possible solutions for this problem:</strong></p>

<p><strong>First</strong>, Wistia could add a <em>&lt;meta name=”robots” content=”noindex, follow”&gt;</em> tag to those /oldblog/ pages, as it would prevent the pages from being indexed and would allow the link “juice” to flow through to the returned posts and pages.</p>

<p><strong>Second</strong>, Wistia could 301 redirect all of the /oldblog/ pages to their corresponding new pages. Thus, an article like “<a href="http://wistia.com/oldblog/stats-export-updates/" target="_blank">Improved Stats Exports In Wistia</a>” on the old blog “http://wistia.com/oldblog/stats-export-updates/” would 301 redirect to the new location at http://wistia.com/blog/stats-export-updates.</p>

<p>These solutions will pass links and will help Wistia from creating duplicate content. A quick reminder: telling Google that it cannot see something in the robots.txt file does not mean that they cannot index it; it tells the engines not to crawl the given URL, but that they may keep the page in the index and display it in the results. There are better solutions for blocking robots than in the robots.txt file.</p>

<p><strong>With the page level solutions mentioned above, the new robots.txt file for the Wisita root domain would look like:</strong></p>

<p>As you can see, I’ve removed the comments and the /oldblog/ from the original.</p>

<h4 id="robotstxt-for-wistia-users">Robots.txt for Wistia Users</h4>

<p>Each Wistia user receives a setup similar to the following: company.wistia.com. Wistia uses the subdomain to build out the users’ hosting space. They’ve equipped each subdomain with the following robots.txt:</p>

<p>This setup is technically correct, and I would need a deeper understanding of the Wistia platform before suggesting prudent changes. However, here is what I can tell with my limited access:</p>

<p><img class="aligncenter size-full wp-image-2226" src="/images/wp-uploads/2014/05/sitewistia.com-Google-Search-2014-05-12-21-23-23.png" alt="site:wistia.com - Google Search 2014-05-12 21-23-23" width="989" height="991" /></p>

<p>The subdomains are being indexed, which is not technically healthy for Wistia’s site. Again, blocking the robots.txt file doesn’t keep Google from indexing the content, it just keeps the search engines from showing what’s inside.</p>

<p>A solution would be to add a <em>&lt;meta name=”robots” content=”noindex, follow”&gt;</em> tag to all user subdomains.</p>

<p>If Wistia switched from blocking pages at the robots.txt pages to blocking pages at the page level, they could benefit from embedded links pointing at their subdomains. But once again, I would need a fuller understanding of the platform and limitations before suggesting any changes.</p>

<h3 id="metatag">Robots Meta Tag</h3>

<p>Each page on a site can use a robots meta tag to tell search engine crawlers if they are allowed to index that page and follow its links.</p>

<p>Very few of Wistia’s pages have a meta robots tag – which is fine – they are unnecessary unless they are trying to specify a hidden page. In the case mentioned above, it would benefit Wistia to include a “noindex” robots meta tag on a per page basis, rather than blocking an entire directory.</p>

<p>Finally, Wistia’s SEO could benefit by adding a “noindex,follow” (perhaps nofollow) tag to their users’ profiles. The image below shows what Google does with users’ profiles.</p>

<p><img class="aligncenter size-large wp-image-2227" src="/images/wp-uploads/2014/05/sitewistia.comcommunityusers-Google-Search-2014-05-12-21-36-53-721x1024.png" alt="site:wistia.com:community:users - Google Search 2014-05-12 21-36-53" width="721" height="1024" /></p>

<p>The problem here is that because users’ profiles are displayed, they take up Wistia’s crawl budget. Wistia’s main content <em>should</em> be what consumes the crawl budget, <em>not</em> individual user profiles.  So, it would be beneficial to “noindex,follow” all user profiles.</p>

<h3 id="sitemaps">XML Sitemaps</h3>

<p>What are sitemaps?</p>

<blockquote>
  <p>Sitemaps are an easy way for webmasters to inform search engines about pages on their sites that are available for crawling. In its simplest form, a Sitemap is an XML file that lists URLs for a site along with additional metadata about each URL… <a href="http://www.sitemaps.org" target="_blank">Sitemaps.org</a></p>
</blockquote>

<p>I identified two Sitemap listings in Wistia’s robots.txt file:</p>

<p>The first listing points to the site’s Web Sitemap, which should include URLs for every page the site wants search engines to crawl and index.</p>

<p>The second listing points to the site’s Video Sitemap, which should include URLs for pages that include video listings. The video sitemap may also earn Wistia a click through boost by giving them a picture in the SERPs. Here are the <a href="http://app.wistia.com/sitemaps/4721.xml" target="_blank">contents to Wistia’s first sitemap:</a></p>

<p><img class="aligncenter size-large wp-image-2211" src="/images/wp-uploads/2014/05/4721-1024x626.png" alt="4721" width="1024" height="626" /></p>

<p>The video sitemap is implemented correctly:</p>

<ul>
  <li>It makes it clear to Google what their content is.</li>
  <li>They have the opportunity to provide a range of details through schema.</li>
  <li>Additional presence on video.google.com search.</li>
  <li>A picture thumbnail, which is a pretty great call to action in the SERPs.</li>
</ul>

<p><img class="aligncenter size-large wp-image-2212" src="/images/wp-uploads/2014/05/Announcing-the-Wistia-Community-1024x399.png" alt="Announcing the Wistia Community" width="1024" height="399" /></p>

<p>It is interesting to note that Wistia does not include all posts with videos in their sitemap. However, since most of their videos earn a picture thumbnail, it may be beneficial for Wistia to add more videos to their sitemap.</p>

<p>I would recommend compiling a comprehensive list of the site’s indexable pages with videos on the page (i.e., pages that are substantive enough to warrant video inclusion) and creating the video sitemap using that list.</p>

<p>Wistia’s other sitemap is a little more disappointing.</p>

<p><img class="aligncenter size-large wp-image-2213" src="/images/wp-uploads/2014/05/Screen-Shot-2014-05-05-at-12.34.31-PM-1024x188.png" alt="Wistia Sitemap" width="1024" height="188" /></p>

<p>This sitemap is not populated – and it’s another video sitemap – <em>meaning Wistia does not have a sitemap for text posts</em>. I would recommend compiling a comprehensive list of the site’s indexable posts and pages and creating the sitemap using that list.</p>

<p>One last issue with the sitemaps: they are located on a subdomain of wistia.com. Moving the sitemaps from app.wistia.com to wistia.com/sitemaps/ may help with indexing, since all the articles inside the sitemap are hosted on the root domain.</p>

<h2 id="accessibility">Accessibility</h2>

<p>This section covers best practices for both search engines and users. Many of the search engines’ accessibility issues were mentioned above in index-ability, and now we’ll cover accessibility as it mainly relates to humans with the benefits of robots in mind.</p>

<h3 id="performance">Performance</h3>

<p><a href="http://googlewebmastercentral.blogspot.com/2010/04/using-site-speed-in-web-search-ranking.html" target="_blank">According to Google Webmaster tools</a>:</p>

<blockquote>
  <p>You may have heard that here at Google we’re obsessed with speed, in our products and on the web. As part of that effort, today we’re including a new signal in our search ranking algorithms: site speed. Site speed reflects how quickly a website responds to web requests… While site speed is a new signal, it doesn’t carry as much weight as the relevance of a page.</p>
</blockquote>

<p>Though it’s tempting to dismiss site speed as an important SEO ranking factor, if Google says it matters (even a small percentage), it matters.</p>

<p>Wistia’s site speed is decent, but Wistia could make a few tweaks to make their site much more efficient:</p>

<p><a href="http://gtmetrix.com/reports/wistia.com/9C9phTHA" target="_blank"><img class="aligncenter size-large wp-image-2309" src="/images/wp-uploads/2014/05/Screen-Shot-2014-05-16-at-10.31.46-AM-1024x584.png" alt="Screen Shot 2014-05-16 at 10.31.46 AM" width="1024" height="584" /></a></p>

<p>One of the things you’ll notice is that the site is loading too many external files. Reducing the number of files needed to load the site, thereby reducing the number of HTTP requests, will make the site load more quickly. Currently, Wistia is making 94 HTTP requests – far too many requests.</p>

<p>There’s usually three parts to fixing this:</p>

<ul>
  <li>Reduce the number of JavaScript files</li>
  <li>Reduce the number of CSS files</li>
  <li>Reduce the number of images</li>
</ul>

<p>The Time to First Byte is extremely quick, but the page load is somewhat slow – anywhere from 2.88 seconds to 3.93 seconds (<a href="http://tools.pingdom.com/fpt/#!/bOoIP6/wistia.com" target="_blank">Pingdom</a>). They received a <span style="color: #800000;">63/100</span> on Page Speed Insights via Google, and 72/100 on Pingdom.  Wistia’ site has room for improvement.</p>

<p><strong>The site could be improved with the following:</strong></p>

<ul>
  <li>Eliminate render-blocking JavaScript and CSS</li>
  <li>Minimize HTTP request – Wistia’s pages will load more quickly with fewer requests. Minimizing these requests involves reducing the number of files that have to be loaded, such as javascript, css, and images.</li>
  <li>Combine Javascript and CSS into external files with links from the header. This allows the external page to be cached so that it’ll load faster.</li>
  <li>Optimize images for the web.</li>
  <li>Implement server side caching – This creates a static html page for a URL so that the dynamic sites don’t have to reload / be recreated each time the URL is requested.</li>
  <li>Use a CDN – such as Amazon. The CDN will allow users to download information more quickly.</li>
  <li>Load Javascript asynchronously.</li>
  <li>Finally, use 301’s only when necessary. A 301 forces a new URL, which takes a longer time to load.</li>
</ul>

<p>Wistia also has around 200 broken links – which is not a lot – but fixing those would cut down on 404s and unnecessary HTTP requests.</p>

<p>Finally, <a href="view-source:http://wistia.com/blog" target="_blank">Wistia loads some of their CSS in the header</a>  – over 500 lines of CSS on each page. This occurs on the homepage and other pages throughout the site. In order to increase page speed and be more semantic, Wistia should move their styles to the main CSS style sheet. Right now, Wistia’s website suffers from 120+ CSS errors.</p>

<h3 id="architecture">Site Architecture</h3>

<p>Currently, Wistia’s average page level is 5.4 (0 being the homepage). At this point, Wistia should:</p>

<ol>
  <li>Start to trim back their content that doesn’t produce results</li>
  <li>Reduce the number of content silos on their pages by creating a flatter, better connected architecture</li>
</ol>

<p><strong>First,</strong> some SEOs are under the impression that all content is good, meaning that content should never be deleted. In fact, even HubSpot has an article entitled <a href="http://blog.hubspot.com/blog/tabid/6307/bid/16241/5-Reasons-Why-Deleting-Your-Blog-Posts-Is-Stupid.aspx" target="_blank">5 Reasons Why Deleting Your Blog Posts Is Stupid</a> (perhaps the article is outdated – and should be deleted). I tend to lean the other way.</p>

<p>Content is like a grapevine: In order to produce the best fruit possible, you really need to prune. I’d suggest that Wistia sit down with Google Analytics, Backink profiles, etc. and decide which pages are brining in traffic, shares, etc, and which articles are not. Based on the results, Wistia can create better content that engages and prevents keyword cannibalization.</p>

<p>Wistia can cut back on content in two ways: meta robots “noindex” or they can delete the content. Content that is necessary for a positive user experience but should not be included in the SERPs should be deindexed. _For example, _one of the first places Wistia should consider deindexing is /community/. This section of the site does not contain any CTAs – the rankings are low – and the architecture is deep. Wistia should not cut this content because it is useful for the user, but not for the search engine. Deindexing the content takes care of the problem.</p>

<p>On the other hand, there are posts that have aged poorly. If they are not driving traffic, increasing shares, ranking, or converting, Wistia should delete them. In_ deleting content, Wistia should 301 duplicate content and let the rest of the content 404. _</p>

<p><strong>Secondly, </strong>Wistia should create a flatter site architecture. If Wisita can contain most of their content within 3 levels http://wistia.com/blog/category/article (root counts as 0), they will be able to increase indexation and increase long tail results. This will also prevent vertical silos (<a href="http://moz.com/rand/" target="_blank">Rand has a great article on content silos</a>).</p>

<p>Right now, Wistia exists in 4 main silos: /blog, /learning, /community and /doc. The Wistia homepage links to a silo (ie. blog), and silos link to posts. This creates lots of information, but links are flowing down, not around.</p>

<p>In reworking their site architecture, these vertical silos will disappear.</p>

<h3 id="usability">Usability</h3>

<p>Wistia has a few layout issues that reduce the website’s usability and effectiveness.</p>

<p>First, noticeably missing from the Wistia website is a search form. The only way to find something on the Wistia website (outside of the navigation) is to head over to Google and search “Wistia + “. Adding this search functionality will help users, and it will also help Wistia know what the user is searching for in their site page analytics.</p>

<p><img class="aligncenter size-large wp-image-2382" src="/images/wp-uploads/2014/05/Wistia-1024x94.png" alt="Wistia" width="1024" height="94" /></p>

<p>Next, Wistia’s site is not mobile responsive. Based on the analytics, Wistia has 50% of their users visiting the site on mobile. On iOS, sometimes Wistia’s entire site loads, but at other times, users will see this:</p>

<p><img class="aligncenter size-full wp-image-2383" src="/images/wp-uploads/2014/05/Screen-Shot-2014-05-20-at-10.13.00-PM.png" alt="Wistia iPhone" width="492" height="824" /></p>

<p>At some breakpoints, Wistia’s site seems to be in the middle of transition between “almost mobile ready” and fixed width:</p>

<p><img class="aligncenter size-large wp-image-2384" src="/images/wp-uploads/2014/05/Video-Hosting-for-Business-2014-05-20-22-16-52-212x1024.png" alt="Video Hosting for Business 2014-05-20 22-16-52" width="212" height="1024" /></p>

<p>Usability needs improvement on mobile, and according to Matt Cutts, “There is NO SEO disadvantage to using responsive design, only advantages.” I’m sure this usability problem will be fixed in the next iteration of Wistia’s website.</p>

<h4 id="clickdepth">Click Depth</h4>

<p>Click Depth or crawl depth is the number of times a website visitor must click on a link from the root domain in order to get to the desired page. The root domain will have a link depth of zero – since it takes zero clicks to get to the root domain on a webpage.</p>

<p>Search Engines are like humans – they do not want to waste time trying to find pages hidden deep into a site’s architecture. Pages that are available in one click – thus one page from the homepage –  are deemed more important by search engines than those that are nearly hidden.</p>

<p>As the graph below shows, Wistia is doing a good job of keeping the required clicks minimal. What will decrease click depth even more, though, would be to remove silos.</p>

<p><img class="aligncenter size-large wp-image-2233" src="/images/wp-uploads/2014/05/Screen-Shot-2014-05-13-at-10.43.54-AM-1024x607.png" alt="Crawl Depth" width="1024" height="607" /></p>

<p>####</p>

<h2 id="onpage">On Page Ranking Factors</h2>

<p><span style="color: #555555;">In this section, I’ll examine Wistia’s on-page ranking factors (e.g., Titles,URLs, markup, images, content, etc.) that influence the site’s search engine rankings.</span></p>

<h3 id="markup">HTML Markup</h3>

<p>Semantic HTML markup, in its most basic elements, is a machine readable language that is used to tell the browser how to display the text or graphics in the document. Search engines crawl over your pages and semantic markup can identify your pages’ most important information. Semantic HTML markup is a way of indicating the meaning of web content to the search engine.</p>

<p>When examining Wistia’s pages, I found multiple pages with 10-30 errors per page. The most concerning was the empty heading tags littered throughout the pages. Although these aren’t extremely critical issues, I’d recommend cleaning up as many errors as possible (empty headings, duplicate IDs, attributes, etc).</p>

<h4 id="schema">Structured Data</h4>

<p>Schema.org mircodata is an extra set of HTML tags that you can add to your HTML elements to let the search engines know specifically what you are talking about. For example, for the Wistia blog post, they would tag the title as a “headline,” the author as an “author” (with authorship), and the date the blog post was published as the “publishedDate.” Now when Google indexes Wistia’s blog, it knows specifically what the title of an article is, who the author is, and when the post was published.</p>

<p>Unfortunately, Wistia does not define structured data. To make these articles more readable for search engines, I’d recommend adding the article markup. Wistia is already doing a great job with Video Markups, and the posts should be an easy next step.</p>

<p>Wistia fails to add authorship to most of its articles. Though a few of Wistia’s articles include authorship, such as the one below, including authorship in <em>all</em> articles would be greatly beneficial.</p>

<p><img class="aligncenter size-full wp-image-2281" src="/images/wp-uploads/2014/05/Welcome-Jonathan-to-the-Engineering-Team-2014-05-15-13-41-02.png" alt="Welcome Jonathan to the Engineering Team 2014-05-15 13-41-02" width="938" height="363" /></p>

<p><img class="aligncenter size-full wp-image-2282" src="/images/wp-uploads/2014/05/Google-Structured-Data-Testing-Tool-2014-05-15-13-41-52.png" alt="Google Structured Data Testing Tool 2014-05-15 13-41-52" width="813" height="560" /></p>

<p>In order to add authorship, here’s what you can do: create a Google+ profile for each of the site’s authors. Then, link from Google + profile back to the blog, and vice versa.</p>

<p><span style="color: #ff0000;"><strong>Be Careful with Schema.org</strong></span></p>

<p>One caution: I do not recommend schema.org for all HTML elements. For example, consider the search term “OneRepublic”:</p>

<p><img class="aligncenter size-large wp-image-2283" src="/images/wp-uploads/2014/05/one-republic-Google-Search-2014-05-15-13-47-35-1024x698.png" alt="one republic - Google Search 2014-05-15 13-47-35" width="1024" height="698" /></p>

<p>Here, you can see that Google is using micro markup (schema) to scrape the content and place it on Google – this could potentially hurt click through rates (CTR). The more information you tell Google – the more you risk Google scraping your content and your site losing sessions.</p>

<h4 id="descriptions">Meta Descriptions</h4>

<p>Meta descriptions are HTML attributes that provide concise explanations of the contents of web pages. Meta descriptions are commonly used on search engine result pages (SERPs) to display preview snippets for a given page (<a href="http://moz.com" target="_blank">Moz</a>).</p>

<p>Meta Descriptions do not influence the ranking factor of a site’s page, but they do influence the CTR (click-through-rate).</p>

<p><img class="aligncenter size-full wp-image-2231" src="/images/wp-uploads/2014/05/meta-description.png" alt="meta-description" width="542" height="79" /></p>

<p>These short paragraphs (normally 155 words) are a website’s opportunity to advertise content to searchers and to let them know whether the given page contains the information they’re looking for.</p>

<p>Out of 1,243 unique HTML/Text URLs on Wisita’s root domain (more on that in a minute) only 76 of Wistia’s pages use a meta description, and 19 of those descriptions are duplicates. What this means is that in almost all of the searches, the meta descriptions are automatically generated.</p>

<p><strong>2 Options to Fix</strong></p>

<p>There is no single answer for this problem.</p>

<p>The <strong>first </strong>answer would be adding a unique meta description for each of the page’s content.</p>

<p>The <strong>second </strong>answer is a bit more complex. If a page is only targeting between one and three search terms, then by all means, write a meta description that targets those key words. But if the page is targeting long-tail searches, it may be easier to let the search engines pull in the meta descriptions themselves.</p>

<p>The reason the second answer is more feasible is because when the search engines pull content, they pull content and display keywords surrounding the user’s query. If you force a meta description, it can detract from the relevance of long tail search.</p>

<p>In some cases, search engines will overrule your meta description anyways, but you cannot always rely on that. In that regard, it would be advantageous for Wistia to add meta descriptions for pages that target only a few keywords and leave the other long-tail pages open for variance.</p>

<h5 id="one-last-issue-to-be-aware-of-when-thinking-about-meta-descriptions">One last issue to be aware of when thinking about meta descriptions:</h5>

<p>Social sharing sites will commonly pull the meta description when sharing.</p>

<p><img class="aligncenter size-large wp-image-2219" src="/images/wp-uploads/2014/05/meta-description-share-1024x632.jpg" alt="meta-description-share" width="1024" height="632" /></p>

<p>Without the meta description, social sharing sites will just use the first text they can find. As you can see above, the social share pulled the title twice, the date, and then the first words from the opening paragraph. Not using a meta description may create a bad user experience for social sharing.</p>

<h4 id="headtags">Head Tags</h4>

<p><em>rel=publisher</em></p>

<p>Wistia has a great looking Google+ page, and they need to take advantage of rel=publisher. This tag has seen a much smaller adoption rate compared to Rel=Author, and its name may cause the confusion.  The publisher tag can be used by any business or brand website that has a corresponding Google+ page.</p>

<p>Publisher connects your Google + page to your website, and that results in your Google + page being displayed in search results whenever anyone is searching for your brand name. For example:</p>

<p><a href="https://www.google.com/search?q=moz&amp;oq=moz&amp;aqs=chrome..69i57j69i60l3j0j69i35.1071j1j4&amp;sourceid=chrome&amp;es_sm=91&amp;ie=UTF-8" target="_blank"><img class="aligncenter size-large wp-image-2356" src="/images/wp-uploads/2014/05/Screen-Shot-2014-05-18-at-10.28.57-PM-1024x313.png" alt="Publisher URL" width="1024" height="313" /></a>See the rich snippet on the right? This is what Wistia is missing. Currently, a search for Wistia leaves room to be desired:</p>

<p><a href="https://www.google.com/search?q=moz&amp;oq=moz&amp;aqs=chrome..69i57j69i60l3j0j69i35.1071j1j4&amp;sourceid=chrome&amp;es_sm=91&amp;ie=UTF-8#q=wistia" target="_blank"><img class="aligncenter size-large wp-image-2357" src="/images/wp-uploads/2014/05/wistia-Google-Search-2014-05-18-22-30-46-1024x652.png" alt="wistia - Google Search 2014-05-18 22-30-46" width="1024" height="652" /></a></p>

<p>The red box here indicates where Wistia’s publisher mark-up could go. Wistia simply needs to link from their home page to their Google Plus page using rel=”publisher”.</p>

<p><em>rel=canonical</em></p>

<p>Wistia does a fine job of inputting rel=canonical in most cases. On many subpages, blog rolls, etc… Wistia uses rel=prev, rel=next, which is actually a common substitute for canonical (according to webmaster tools). On <a href="view-source:http://wistia.com/community?page=3#results" target="_blank">http://wistia.com/community</a> there does seem to be a small error in rel=canonical. In the markup, Wistia has the canonical page as the first page. According to <a href="http://googlewebmastercentral.blogspot.com/2013/04/5-common-mistakes-with-relcanonical.html" target="_blank">Google Webmaster Tools</a>:</p>

<blockquote>
  <p>Specifying a rel=canonical from page 2 (or any later page) to page 1 is not correct use of rel=canonical, as these are not duplicate pages.</p>
</blockquote>

<p>Based on this information, Wistia has the rel=canonical set up incorrectly. All community subpages point back to /community. According to webmaster tools, Google actually recommends that you rel=canonical to a “View All” page. The current set up is technically incorrect because page 2 is not a duplicated of /community.</p>

<p>In order to fix this, I’d recommend that Wistia implement rel=prev / rel=next like they do in other subpages (and remove rel=canonical), or that they create a “view all” page and rel=canonical the pages that include all discussions from community. This may help decrease the indexing of the community pages.</p>

<p>Lastly, not all subpages include canonical or rel=”prev/next”. I’d suggest adding those tags to help the search engines distinguish the paginated series.</p>

<p><em>rel=prev / next</em></p>

<p>Google asks that webmasters add rel=”next” and rel=”prev” to paginated archives, so that Google can distinguish them as a series and send users to the most relevant pages.</p>

<p>As far as I can tell, Wistia implements this correctly (ie, the blog).</p>

<h5 id="opengraph">Open Graph</h5>

<p>The Open Graph protocol enables any web page on Wistia’s site – or all sites – to become a rich object. For instance, the Open Graph is used by Facebook to allow any web page to have the same functionality as any other object on Facebook. Currently, Wistia does not implement Open Graph protocol on their site.</p>

<p><img class="aligncenter size-large wp-image-2365" src="/images/wp-uploads/2014/05/Screen-Shot-2014-05-19-at-10.01.37-PM-1024x442.png" alt="Facebook Open Graph" width="1024" height="442" /></p>

<p>If you look closely, you can easily notice that Wistia is not using the open graph – due to how the description is automatically generated by Facebook. At the very minimum, Wistia should include the following open graph tags:</p>

<p>Even if Wistia does not have the time to implement all forms of open graph, at the bare minimum, I’d recommend they include Open Graph (all social platforms can use it as a baseline, including Twitter). Adding Open Graph tags to their website won’t directly affect the on-page SEO, but it will influence the performance of Wistia’s links in social media.</p>

<h5 id="twittercards">Twitter Cards</h5>

<p>Currently, Wistia is not implementing Twitter cards on their site:</p>

<p><img class="aligncenter size-large wp-image-2367" src="/images/wp-uploads/2014/05/Screen-Shot-2014-05-19-at-10.21.47-PM-1024x394.png" alt="Wistia Twitter Cards" width="1024" height="394" /></p>

<p>Twitter cards are another micro markup – essentially rich snippets for Tweets. Now, as mentioned above, Twitter will actually fall back on the Open Graph tags used for FB if Wistia would implement them, but the Open Graph tags aren’t comprehensive.</p>

<p>There may be a reason that Wistia opted not to use Twitter cards, because they could easily implement them if they wanted to. Since they’ve seamlessly implemented video on Twitter, the other card formats would be easy to implement.</p>

<p><img class="aligncenter size-large wp-image-2368" src="/images/wp-uploads/2014/05/Screen-Shot-2014-05-19-at-10.23.01-PM-1024x803.png" alt="Wistia Video " width="1024" height="803" /></p>

<p>It is an easy fix. At the very minimum, Wistia could add:</p>

<p>I’d recommend Wistia looking into adding open graph to all of their pages to help with social engagement and sharing.</p>

<h3 id="titles">Titles</h3>

<p>According to <a href="http://cyrusshepard.com/" target="_blank">Cyrus Shepard at Moz</a>:</p>

<blockquote>
  <p>Title tags—technically called title elements—define the title of a document. Title tags are often used on search engine results pages (SERPs) to display preview snippets for a given page, and are important both for SEO and social sharing.</p>
</blockquote>

<p>Each page that is indexed should have unique content and a unique title that effectively summarizes the content for users and search engines. Out of the 1200+ pages on Wistia’s website, only 512 pages have unique titles.</p>

<p><strong>On these pages, there are two options:</strong></p>

<p><strong>First</strong>, add a unique title that describes the pages.</p>

<p><strong>Second</strong>, and probably most preferred, “noindex, follow” the pages that are not necessarily important (See the example below of titles and pages that are not necessary). This will remove them from the search engines but links will still pass equity.</p>

<p><a href="/images/wp-uploads/2014/05/sitewistia.comcommunity-Google-Search-2014-05-18-11-58-51.png"><img class="aligncenter size-large wp-image-2316" src="/images/wp-uploads/2014/05/sitewistia.comcommunity-Google-Search-2014-05-18-11-58-51-633x1024.png" alt="site:wistia.com:community - Google Search 2014-05-18 11-58-51" width="633" height="1024" /></a></p>

<p>Many of the site’s pages use titles that are not descriptive enough (Ie. “Sent from my iPhone,” “Lighting for a Webcam,” etc). These titles do not provide enough information about Wistia or their products , which results in a lower ranking and lower CTR for Wistia. Here is a sampling of the titles from Wistia:</p>

<blockquote>
  <p>Shooting for the Edit</p>
</blockquote>

<blockquote>
  <p>Choosing a Microphone</p>
</blockquote>

<blockquote>
  <p>Choosing Music for Your Video</p>
</blockquote>

<blockquote>
  <p>Sent from my iPhone</p>
</blockquote>

<blockquote>
  <p>Shooting with a Ring Light</p>
</blockquote>

<blockquote>
  <p>Lighting for a Webcam</p>
</blockquote>

<blockquote>
  <p>Making Better Help Videos</p>
</blockquote>

<p>Based on the titles above, it seems as if Wistia is more of a video creation company rather than a video <em>hosting</em> company. I’d suggest researching the CTR and the company’s business needs and crafting articles and titles that are focused on those needs with the audience in mind.</p>

<p>For example, let’s look closely at this title: “<a href="http://wistia.com/blog/does-length-matter-it-does-for-video-2k12-edition">Does Length Matter?</a>“<span style="color: #000000;">. Of course, if you know Wistia, you know that they are referring to video length. But let’s say you don’t know Wistia. What would you think? Wistia isn’t trying to be explicit or inappropriate, but you can see how a more descriptive title, such as, “Does Length Matter in Online Videos: Video Analytics Say Yes” makes much more sense.  That title is a little long, 61 characters, but it would show up in Google as: </span></p>

<p><a href="/images/wp-uploads/2014/05/Screen-Shot-2014-05-18-at-2.30.36-PM.png"><img class="aligncenter size-large wp-image-2321" src="/images/wp-uploads/2014/05/Screen-Shot-2014-05-18-at-2.30.36-PM-1024x195.png" alt="Screen Shot 2014-05-18 at 2.30.36 PM" width="1024" height="195" /></a></p>

<p>It cut the title off, but it does leave the viewer wondering what the analytics say. This title is much more descriptive and removes any click anxiety a user would face when coming upon the title “Does Length Matter.”</p>

<p>As you noticed above, Google will show as many characters that a 512 pixel display can show – thus, around 50-60 characters. The reason the number varies is because some characters are bigger than others (ie, you could fit a lot more “i”s than you could “w”s). _Wistia is not taking advantage of this character count. _Most of Wistia’s titles are at an average of 22 characters long, and very few of them reach 50 characters in the title. If Google gives you the opportunity to create a longer, more descriptive title, do it.</p>

<p><img class="aligncenter size-large wp-image-2319" src="/images/wp-uploads/2014/05/Screen-Shot-2014-05-18-at-2.15.44-PM-1024x607.png" alt="Title Length" width="1024" height="607" /></p>

<p>I’d suggest that Wistia go back and rewrite many of their titles. A longer, more specific title could result in higher click through rates, and ultimately, better rankings. Even if Wistia does not want to rewrite many of their titles, adding the branding would increase character count and would, at the very least, take back the length real estate they have lost up until this point.</p>

<table>
  <tbody>
    <tr>
      <td>Less than 50% of the site’s titles actually incorporate the brand name. To help promote brand awareness, I’d add Wistia at the end of each title (“Shooting for the Edit</td>
      <td>Wistia”). Because Wistia is well recognized, including the brand name in the title element can increase search engine clicks.</td>
    </tr>
  </tbody>
</table>

<h3 id="urls">URLs</h3>

<p>Wistia has done a great job crafting their URLs. Their URLs are at an average length of 50 characters (including http://wistia).</p>

<p><img class="aligncenter size-large wp-image-2326" src="/images/wp-uploads/2014/05/Screen-Shot-2014-05-18-at-2.46.38-PM-1024x792.png" alt="Wistia URL Analysis" width="1024" height="792" /></p>

<p>The site’s URL structure is organized and clean. The blog section is under /blog/. The Documentation lives under /doc/, and community lives under /community/. Each URL also contains at least one keyword.</p>

<p>Wistia could, however, improve their URL structure by making it slightly more descriptive. Take this URL, for example:</p>

<p><a href="http://wistia.com/blog/screenr/" target="_blank">http://wistia.com/blog/screenr/</a></p>

<p>Wistia could add one or two more words to the URL to describe what the page is about. The keyword Screenr is very vague, and Wistia could potentially help ranking and click through by describing the URL better.</p>

<h3 id="images">Images</h3>

<p>For the benefit of search engines, compliance (HTML), and the visually impaired – all images should have an ALT tag.</p>

<p>The ALT tag should accurately describe the image, and if possible, contain a keyword relevant to Wistia’s site (but only if the keyword is relevant to the image).</p>

<p>Additionally, image file names should be descriptive – not containing random numbers or queries. The file name should describe the image and, once again, use a keyword if possible.</p>

<p>If Wistia ensures that images follow these two rules, they will increase the likelihood of referral traffic from image searches. Wistia has hundreds of images, but only about 8% of the images take advantage of the alt text. Wistia also has many images that are labeled with random numbers and strings:</p>

<p>There are hundreds of images like this on Wistia’s blog, and the ones above were taken from the most recent articles posted. I’d suggest adding alt tags and descriptive title tags to the images to increase organic image search, but to also be HTML compliant (<a href="http://validator.w3.org/check?uri=wisita.com&amp;charset=%28detect+automatically%29&amp;doctype=Inline&amp;group=0" target="_blank">they currently aren’t</a>) and to help the visually impaired.</p>

<h3 id="transcripts">Transcripts</h3>

<p>According to Wistia:</p>

<blockquote>
  <p>When a search engine is indexing your page, instead of seeing a video element with a few tags, transcripts allow the search engines to index every single word of your video.</p>
</blockquote>

<p>Transcripts are an opportunity to tell Google what a video is about. Transcripts also generates a closed caption for the video, which allows hearing impaired users to watch the video and read the dialogue.</p>

<p>Unfortunately, some of Wistia’s videos do not appear to utilize transcripts, and what’s more, those that do have transcripts do not accurately match the video. I would recommend adding transcripts to improve the searchability and usability of Wistia’s videos.</p>

<h3 id="duplication">Content Duplication</h3>

<p>Wistia is doing a great job keeping their content unique and fresh. They do, however, need to be careful with canonicalization (only point back to a view all page in archives) and prev/next.</p>

<p>For example, Wistia does need to do something about their users’ profiles, ie.  http://wistia.com/community/users/. Their users’ profiles should be deindexed. They risk spammy content and content duplication, as seen below:</p>

<p><img class="aligncenter size-large wp-image-2393" src="/images/wp-uploads/2014/05/Screen-Shot-2014-05-20-at-10.49.37-PM-1024x477.png" alt="Users" width="1024" height="477" /></p>

<p>Wistia also doesn’t have a major issue yet, but they might want to remove the old WordPress /oldblog (or bring it in house since it might be a test sight):</p>

<p><img class="aligncenter size-large wp-image-2388" src="/images/wp-uploads/2014/05/Wistia-at-Work-2014-05-20-22-35-28-1024x509.png" alt="Wistia at Work 2014-05-20 22-35-28" width="1024" height="509" /></p>

<h2 id="offsite">Off-Site Ranking Factors</h2>

<p>This section will cover some of the most influential factors in ranking: backlinks and social engagement.</p>

<h3 id="backlinks">Backlinks</h3>

<p>Links are not everything when it comes to SEO, but search professionals and companies attribute a large portion of the search engines’ algorithms to backlinks (Larry Page based Google off of the Educational Citation Method – ie. A professor who was cited by other authors was considered more credible – Read his dissertation for more information).</p>

<p>When analyzing backlinks, you should consider: Total number of links, link quality, number of unique domains, fresh/incoming links, and anchor text usage.</p>

<p>To start, I first recorded how many backlinks Wistia had received over the past few months (this is not including 500 unique domains that point to www.wistia.com). The charts below show the growth of Wistia’s backlink profile over the course of one year.</p>

<p><img class="alignnone size-full wp-image-2275" src="/images/wp-uploads/2014/05/Overview-wistia.com-on-Ahrefs-2014-05-14-22-32-32.png" alt="Overview wistia.com on Ahrefs 2014-05-14 22-32-32" width="863" height="725" /></p>

<p>After comparing the backlink analysis above to Majestic SEO and Moz, there was not much of a difference. Wistia was consistently growing their unique domain backlinks until April, and has started a recent growth.</p>

<p>To see how Wistia’s backlink growth matches up with their competition, I compared Wistia’s growth with 4 of their competitors over the past 5 years: Vzaar, Viddler, Viewbix, and Sproutvideo (notable, Vimeo was not included. Vimeo is on a much larger scale than Wistia at this point). *Wistia is a startup, but they’ve been around the past years.</p>

<p><img class="alignnone size-large wp-image-2273" src="/images/wp-uploads/2014/05/Backlink-History-Majestic-SEO-2014-05-14-22-24-24-1024x443.png" alt="Backlink History - Majestic SEO 2014-05-14 22-24-24" width="1024" height="443" /></p>

<p>One would hope that Wistia would be the yellow line, but they are not. Currently, Wistia is being outpaced by Viddler (Viddler provides online video hosting and custom solutions for businesses along with industry leading support and professional services). Viddler is only one year older than Wistia – Viddler was founded in 2005 and Wistia was founded in 2006 – which means that there should not be such a significant difference in the two companies’ backlink growth.</p>

<p>So that you can actually see Wistia’s cumulative backlink growth, I removed Viddler and focused on only the last 2 years (cumulative):</p>

<p><img class="alignnone size-large wp-image-2274" src="/images/wp-uploads/2014/05/Backlink-History-Majestic-SEO-2014-05-14-22-28-54-1024x496.png" alt="Backlink History - Majestic SEO 2014-05-14 22-28-54" width="1024" height="496" /></p>

<p>These charts shows 2 things:</p>

<ol>
  <li>Wistia’s backlinks <em>are</em> growing.</li>
  <li> They have fierce competition.</li>
</ol>

<p>If Wistia is not careful, they could potentially lose their #1 ranking for “video hosting” to Viddler. Almost every month, the competitors are acquiring more links from more unique referring domains. The backlink analysis shows the competitiveness of  backlinks:</p>

<p><img class="alignnone size-full wp-image-2271" src="/images/wp-uploads/2014/05/Open-Site-Explorer-2014-05-14-22-19-52.png" alt="Open Site Explorer 2014-05-14 22-19-52" width="957" height="626" /></p>

<h3 id="subdomains">Subdomain Backlinks</h3>

<p>As previously mentioned, Wistia sets their users up with a subdomain on their on site to host videos.</p>

<p><img class="aligncenter size-full wp-image-2329" src="/images/wp-uploads/2014/05/Screen-Shot-2014-05-18-at-2.57.41-PM.png" alt="Wistia Subdomains" width="948" height="362" /></p>

<p>Thus, when anyone signs up, they can host their videos on their own subdomain hosted at Wistia.</p>

<p><strong>What does this mean for Wistia?</strong></p>

<p>They receive a lot of subdomain links from their users. In fact, out of the 17,000 backlinks, 13,000 of them point at subdomains of Wistia. There are three ways to look at this situation, but they all come with one major caution:</p>

<ol>
  <li><strong>Pro:</strong> The backlinks on the subdomains are actually helping Wistia. Many companies have started to place their blog on a subdomain, and it seems to be a standard. Supposedly, the search engines are treating subdomains more and more as just portions of the main website, and in a way, links are passing credibility.</li>
  <li><strong>Neutral:</strong> Since the backlinks are not in a subdirectory and are in a subdomain, Google does not pass link credibility. They see the subdomains as a separate site, and thus, the subdomain does not help the main site.</li>
  <li><strong>Con: </strong>Currently, all of Wistia’s subdomains are disallowed from their robots.txt. It would be better for Wistia to set up meta robots tags with “noindex,follow” (to keep link credibility) than to disallow in the robots.</li>
</ol>

<p><strong>Caution:</strong> Whether Wistia changes their robots disallow to meta robots or not, Wistia needs to be mindful of their backlink profile. Even though Wistia currently disallows their users’ subdomains, the users’ links are still tracked. If users have spammy content, the fact that they are hosted at wistia.com means that Wistia could be penalized.</p>

<h4 id="backlinkdistribution">Backlink Distribution</h4>

<p>To monitor Wistia’s backlink distribution – the links dispersed among all of their pages – I used Moz’s Pro Tools to analyze the backlinks for each page on Wistia’s site.</p>

<p><img class="alignnone size-large wp-image-2407" src="/images/wp-uploads/2014/05/Screen-Shot-2014-05-21-at-4.34.27-PM-1024x564.png" alt="Wistia Backlink Distribution" width="1024" height="564" /></p>

<p>Wistia has – according to Moz, Majestic and Ahrefs – around 17,000 referring domains. But, upon closer inspection – many of those links are pointing to subdomains of Wisita. There are only around 1,250 domains pointing to the root folder (http://wistia.com).</p>

<p>According to the data, 72% of all Wistia’s pages have no backlinks. Of the 28% (359 pages) that do have links, the homepage accounts for almost 55% of those links. If you remove the homepage, here is what happens:</p>

<p><img class="alignnone size-large wp-image-2408" src="/images/wp-uploads/2014/05/Screen-Shot-2014-05-21-at-4.46.55-PM-1024x564.png" alt="backlinks" width="1024" height="564" /></p>

<p>The articles with the most links (excluding the homepage) are:</p>

<p>The rest of the pages contain less than 1% of all referring links. Moving forward, I recommend spending more time on in-depth / well researched articles, ie. <a href="http://wistia.com/blog/does-length-matter-it-does-for-video-2k12-edition" target="_blank">Does Video Length Matter</a>. Additionally, it would not hurt to conduct outreach on the articles to increase page shares.</p>

<h4 id="backlinksource">Backlink Source Analysis</h4>

<p>To analyze Wistia’s backlinks, I used Majestic SEO. Here is a plotting of their backlinks:</p>

<p><a href="https://www.majesticseo.com/reports/site-explorer/link-profile?folder=&amp;q=wistia.com&amp;oq=wistia.com&amp;IndexDataSource=F" target="_blank"><img class="aligncenter size-full wp-image-2402" src="/images/wp-uploads/2014/05/Wistia-Backlinks.png" alt="Wistia Backlinks" width="964" height="912" /></a>The site has quite a few quality backlinks. When analyzing Majestic, you are hoping to see the links fall to the top right. Citation Flow is link juice and the Trust Flow is how close those links are to trustworthy, authoritative sources.</p>

<p>Correlating with the data above, only a handful of Wistia’s links that I checked out appeared spammy, and very few of the links over-optimized anchor text. With a trust ratio of .918, Wistia has links from mostly trustworthy sources. It would be nice, however, to see the ratio greater than 1.</p>

<p><strong>One last caution:</strong> Wistia should be careful of others websites using links in headers and footers that repeat across the site, ie, <a href="http://www.alyce.io/" target="_blank">this site</a>. These sitewide links are heavily scrutinized by Google’s Penguin update, but they should be okay with just a few…</p>

<h4 id="anchor">Anchor Text Distribution</h4>

<p><em>After Penguin, Panda, etc – it’s important for Wistia to conduct an anchor text analysis. </em> Over the years, there were many ways to manipulate rankings on Google, and links were one of them. Google has always been aware of this, and they are finally cracking down (in fact, anchor text misuse will trigger the Penguin filter quickly).</p>

<h5 id="what-links-dotheyneed-to-examine">What Links Do They Need to Examine?</h5>

<h6 id="branded-links">Branded Links</h6>

<p>Branded anchor text includes any link that is a brand name (Wistia), URL, or domain (wistia.com). Google wants to see these brand referrals. If you notice that your link profiles has higher branded links, that is okay. It is natural.</p>

<h6 id="partial-match-money">Partial Match (Money)</h6>

<p>Compound, also commonly known as ‘partial match anchor text,’ is used when the link contains the brand or targeted term, in addition to other words that you aren’t targeting. For example, Wistia may target ‘Wistia Production’ as a partial match…</p>

<h6 id="exact-match-money">Exact Match (Money)</h6>

<p>Exact match anchor text can be considered over optimization. This refers to the words in the links (anchor text, ie… <a href="http://wistia.com" target="_blank">Video Hosting</a>), exactly matching the keywords that you are trying to rank for.</p>

<h6 id="generic">Generic</h6>

<p>‘Zero match anchor text’ or white noise / generic uses calls to action to drive users to targeted pages. Example: <a href="http://elioverbey.net">click here</a>, learn more, follow, read more, etc…</p>

<h6 id="naked-urls">Naked URLs</h6>

<p>A naked URL is simply the domain name or page you are linking to. For example: <a href="http://wistia.com" target="_blank">http://wistia.com</a></p>

<h6 id="image-links">Image Links</h6>

<p>Often overlooked, but are still powerful links, are links on images, which have keywords in the alternate text of the image.</p>

<p><strong>This is a great rule of thumb to follow:</strong></p>

<ul>
  <li>70% brand, URL, brand+keyword, and non-targeted anchor texts (Branded Links, White Noise, Naked URL, Titles, and Image)</li>
  <li>25% partial, phrase, and broad match keyword anchor texts (Compound)</li>
  <li>5% exact match anchor texts (Exact Match)</li>
</ul>

<p>Below is the Anchor Text chart for Wistia…</p>

<p><a href="http://www.majesticseo.com/reports/site-explorer?folder=&amp;q=wistia.com&amp;oq=wistia.com&amp;IndexDataSource=F" target="_blank"><img class="aligncenter size-full wp-image-2262" src="/images/wp-uploads/2014/05/Screen-Shot-2014-05-14-at-8.49.58-PM.png" alt="Wistia's Anchor Text" width="447" height="366" /></a></p>

<p>Wistia does very well. If you examine the chart closely:</p>

<ul>
  <li>6% of Wistia links come from “Wistia,” which is a branded identity.</li>
  <li>10% of searches include a partial match, etc…</li>
  <li>84% include the other types of links: Naked, URL, etc..</li>
</ul>

<p>Wistia has done a great job of keeping their links diverse. One of the best things Wistia did was leaving their video backlinks, from their embeds, empty. <em>This is the reason for the massive amounts of empty anchor text links</em>.</p>

<p>As a result, Wistia’s anchor text appears to be natural. As the company grows, the branded terms should grow as well, but again, that would be a natural progression.</p>

<h3 id="socialengagement">Social Engagement</h3>

<p>In May 2010, Google’s SEO Genius, Cutts, stated that the algorithm does not use social signals as a factor in search results. In December 2010, Cutts said social signals are a factor. More recently, in January of 2014, Cutts went back and said social media is not a signal in the algorithm.</p>

<p>Either way, we cannot ignore the fact that social media is a search engine of sorts. People on social media are researching, searching, interacting, and engaging – and at very high engagement rates. According to <a href="http://www.statisticbrain.com/twitter-statistics/" target="_blank">Statisticbrain</a>, the number of Twitter search engine queries every day is over 2.1 billion. In any regard, a site’s success is largely dependent on social success and social engagement.</p>

<p>The chart below gives you a great visual of how Wistia’s shares are split concerning a search engine’s point of view. The center represents the first page, and each segment beyond it are pages linked from that page. Segments beyond that are linked to their parent. Pages with no shares are not included or shown.</p>

<p><a href="/images/wp-uploads/2014/05/Starburst-Sharing-Graph.png"><img class="aligncenter size-large wp-image-2373" src="/images/wp-uploads/2014/05/Starburst-Sharing-Graph-1022x1024.jpg" alt="Starburst-Sharing-Graph" width="1022" height="1024" /></a>As you can see from the graph above, the center represents the homepage, and all directories off of the homepage (/blog, /docs, /learning, etc). It’s great to see that the /blog (large orange portion) takes up a large portion of the shares. The graph below breaks down that same content by social network:</p>

<p><a href="https://socialcrawlytics.com" target="_blank"><img class="aligncenter size-large wp-image-2395" src="/images/wp-uploads/2014/05/Screen-Shot-2014-05-21-at-1.08.04-PM-1024x888.png" alt="Wistia Shares by Social" width="1024" height="888" /></a>As you can tell, Wistia is putting their best foot forward on Twitter, but Facebook still needs some help. On Twitter, they’ve got hashtags (#wisitafest), embed videos, pictures, and links – and the best part – most of their links are to endorse content that is not always their own. In fact, most of the time, the links go to varying sources.</p>

<p>On Facebook, though, Wistia needs a little work:</p>

<p><a href="http://likealyzer.com/wistia" target="_blank"><img class="aligncenter size-large wp-image-2398" src="/images/wp-uploads/2014/05/Wistia-Facebook-1024x980.jpg" alt="Wistia-Facebook" width="1024" height="980" /></a></p>

<p>The Wistia Facebook page is updated on a daily basis, but those updates have various characteristics that need improvement:</p>

<ul>
  <li>Wistia’s content is likable, but it’s not sharable. As a third party analyst, most of their content looks interesting. In the example above, their work space looks cool, but is it worth sharing? A better approach in the specific example above would be to encourage input, such as, “Practicing for the Wistiafest workshops: what are some things you want to see taught?” Very basic, but it’s _at least _asking for interaction.</li>
  <li>Wistia doesn’t create interaction on the posts – their engagement rate is hovering around 2%.</li>
</ul>

<p>Most disconcerting of all: 76% of all content has no FB engagement, and the lack of engagement is true for 51% of Tweets. Even worse, Google+ is non-existent. Here’s why: Wistia only promotes Facebook and Twitter sharing on their blogs – AND they are not very visible. (The red box below highlights this.)</p>

<p><img class="aligncenter size-large wp-image-2399" src="/images/wp-uploads/2014/05/Video-Cheat-Codes-Creating-an-Office-Documentary-in-Under-24-Hours-2014-05-21-13-37-13-1024x509.png" alt="Video Cheat Codes: Creating an Office Documentary in Under 24 Hours 2014-05-21 13-37-13" width="1024" height="509" /></p>

<p>To improve Wistia’s engagement on Facebook, Twitter, and Google+, I would :</p>

<ul>
  <li>Start using more prominent social sharing buttons. I would also add Google+ (since their network seems to have high link authority).</li>
  <li>Use the data above to delete old content that receives no engagement.</li>
</ul>

<h2 id="50-grove-50grove">50 Grove {#50grove}</h2>

<p>50 Grove is a subdomain of Wistia – 50grove.wistia.com – that was created a few years back to help connect videos producers with clients. This site doesn’t appear to have been updated since early 2013, and accounts for quite a bit of <a href="https://www.google.com/search?q=site%3Awistia.com&amp;oq=site%3Aw&amp;aqs=chrome.4.69i57j69i58j69i59l3.3878j0j7&amp;sourceid=chrome&amp;es_sm=91&amp;ie=UTF-8#q=site:wistia.com&amp;start=0" target="_blank">Wistia’s search real-estate</a>. With the uncertainty of how exactly Google sees subdomains, it might be in the best interest of Wistia to cut this subdomain.</p>

<p>Again – this is from the outside looking in, but with only 40 referring domains, and a lack of updating – it seems as if Wistia has moved on from 50 Grove. Even <a href="http://savagethoughts.com/" target="_blank">Wistia’s CEO</a> had <a href="http://simplifilm.com/50grove/" target="_blank">this to say about 50 grove</a>:</p>

<blockquote>
  <p>We take no commission from 50 Grove and we aren’t a video production company. Our interests are solely in making it easier to connect businesses with producers.</p>
</blockquote>

<p>I do think 50grove is a great idea, and I do understand how it relates to the business model, but with so many other products that Wistia offers, it may be a subdomain that is consuming more resources than it’s worth.</p>

<h2 id="inbound">Inbound Marketing</h2>

<p>After analyzing their site – over 1,200+ pages, I noticed that Wistia could also improve on their inbound marketing. With HubSpot right down the street from Wistia’s headquarters, Wistia may want to lean on their neighbor’s expertise (I’m sure <a href="http://onstartups.com/about-dharmesh-shah" target="_blank">Dharmesh</a> has tickets to <a href="http://www.inbound.com/" target="_blank">Inbound 2014</a>).</p>

<p>As Wistia’s website currently stands, they are lacking lead generation tools. Right now, Wistia excels in blogging and social media content, but they are lacking in many conversion channels: calls-to actions, landing pages, forms, marketing automation, etc.</p>

<p>If Wistia does follow the practices above, their organic traffic will grow, but since only 2% of website visitors return, they’ve got to implement lead generation tools where they can build relationships, lead nurture, and then hopefully convert those visitors to customers. This audit will help attract users to the website, but it is only a stepping stone in creating customers.</p>

<p>Wistia should be adding compelling calls-to-action at the bottom of each posts, with helpful tools such as: ebooks, videos, freebies, etc. that will funnel a visitor to a landing page where Wistia can collect information.</p>

<h2 id="summary">Summary</h2>

<p>As important as SEO is, it doesn’t exist in a silo. Right now, Wistia is doing well, but if they could make these tweaks and incorporate SEO into their business’s best practices and online marketing objectives, their gross revenue could soar.</p>

<p>Best of luck, Wistia.</p>


