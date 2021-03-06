﻿---
uid: configure-sitemap
locale: en
title: Configure Your Sitemap
dnnversion: 09.02.00
related-topics: module-sitemap
---

# Configure Your Sitemap

## Steps

1.  Go to **Persona Bar \> Settings \> SEO**.
    
    ![Persona Bar > Settings > SEO](/images/scr-pbar-host-Settings-E91.png)
    
2.  Go to the **Sitemap Settings** tab.
    
      
    
    ![SEO Sitemap settings](/images/scr-SEO-SiteMapSettings-TitleGeneral-E90.png)
    
      
    
3.  Update the **General Sitemap Settings**.
    
      
    
    ![SEO Sitemap general settings](/images/scr-SEO-SiteMapSettings-General-E90.png)
    
      
    
    |**Field**|**Description**|
    |---|---|
    |<strong>Sitemap URL</strong>|The location of the sitemap.|
    |<strong>Exclude URLs With a Priority Lower Than</strong>|The lowest priority to include in the sitemap.|
    |<strong>Include Hidden Pages</strong>|If enabled (On), pages that are not visible in the menu are also included in the sitemap.|
    |<strong>Days to Cache Sitemap For</strong>|The number of days before the sitemap is regenerated. If set to Disable Caching, the sitemap is regenerated, only when requested.|
    |<strong>Clear Cache</strong>|Click/Tap to delete all cached sitemaps. A new sitemap is generated at the next request.|
    |<strong>Minimum Priority for Pages</strong>|If Use page level based priorities? is checked, the lowest priority to assign to pages. Example, if the minimum priority is 0.7,<ul><li>Root/Level 1 gets a priority of 1.0.</li><li>Level 2 gets a priority of 0.9.</li><li>Level 3 gets a priority of 0.8.</li><li>Level 4 and all lower levels get a priority of 0.7.</li></ul>|
    |<strong>Use Page Level Based Priorities</strong>|If enabled (On), the priority for each page is computed based on its hierarchy level. Top level pages are assigned a priority of 1.0, and lower levels are 0.1 less than the next higher level (i.e., the second level pages are assigned a priority of 0.9; the third level, 0.8).|

    > [!Tip]
    > If you have a large site (i.e., at least 50,000 URLs), cache the sitemap for at least one day to help improve your site's performance.
    
4.  Enable and configure the sitemap providers you want to use.
    
      
    
    ![SEO Sitemap Provider settings](/images/scr-SEO-SiteMapSettings-Providers-E90.png)
    
      
    
    Click/Tap the pencil icon in the first column of the table for the appropriate provider.
    
    |**Field**|**Description**|
    |---|---|
    |<strong>Enable Sitemap Provider</strong>|The order in which the providers would be used, if more than one provider is enabled.|
    |<strong>Override Priority</strong>|The priority of the provider, if more than one provider is enabled. The sitemap generated by a provider with a higher priority is preferred over the sitemap generated by a provider with a lower priority.|
    
5.  Click/Tap **Save**.

  

![SEO Site Submission settings](/images/scr-SEO-SiteMapSettings-Submission-E90.png)

  

6.  (Optional) [Submit your site to Google Search for indexing](xref:submit-site-google-search)
7.  (Optional) Submit your site to Bing for indexing.
    
    1.  Choose Bing from the Search Engine dropdown.
    2.  Click/Tap Submit.
    
    You will be directed to Bing's site for webmasters.
    
8.  (Optional) Submit your site to Yahoo! for indexing.
    
    1.  Choose Yahoo! from the Search Engine dropdown.
    2.  Click/Tap Submit.
    
    You will be directed to Yahoo!'s site for webmasters.
