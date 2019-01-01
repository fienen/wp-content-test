---
ID: 173
post_title: Edit Your Menus in Google My Business
author: fienen
post_excerpt: ""
layout: post
permalink: >
  https://drunkenux.com/2018/02/26/edit-your-menus-in-google-my-business/
published: true
post_date: 2018-02-26 07:00:49
---
In <a href="https://drunkenux.com/podcast/episode-4-scenes-from-a-crappy-restaurant-website/">Episode 4</a>, Aaron and I talked about restaurant websites, the things that frustrate us about them, and some steps developers can take to help restaurant owners to better serve their customers. At one point, we mentioned that Google was including menu listings in search quick results when they had the information available. This gets populated a number of ways, and at the time we mentioned several of them, including using schema and ensuring that your menu is up to date with third party services like AllMenus.

That brings us to today. We want to thank one of our listeners, Jonathan, for contacting us and pointing out that Google My Business very recently (like, just at the start of February) has <a href="https://searchengineland.com/restaurant-owners-can-now-edit-menu-listings-google-business-291007">started allowing native editing of menus through their portal</a>. This option isn't absolute, and won't be available if you are using menu schema on your website, or if they have pulled your data in from a third party (this is almost certainly to prevent data conflicts with what it assumes is your menu data of record outside Google). Nonetheless, it is a step to allowing first party control inside of Google to make sure people searching for your site can see it. As Search Engine Land noted:
<blockquote>Restaurant owners who are managing their own Google My Business (GMB) listings can now access a new editor to create and edit the menus that may display in their listings in Google mobile search results.

The editor is available in the Info tab in the Google My Business dashboard. This is also where owners have been able to edit links to their menus. With the editor, owners can add and edit titles, descriptions and prices of their menu items. Menus can also be broken out into sections for appetizers, entrees and desserts, for example.</blockquote>
We felt this new information was definitely worth bringing up to everyone for the sake of completeness. Jonathan also pointed us to a restaurant site he helped set up over at Shakespeare's Pizza. <a href="https://shakespeares.com/pizza/menu/">The menu on their site</a> includes the schema data that we mentioned you could include to define menu options, prices, etc. This was accomplished with a fairly straight forward pull and echo function in the site's WordPress theme. Use the previous link to check it out - just view the source on the page to see the schema information in the source code.

[caption id="attachment_174" align="aligncenter" width="850"]<a href="https://drunkenux.com/wp-content/uploads/2018/02/Search_Console_-_Structured_Data_-_https___shakespeares_com_.jpg"><img class="wp-image-174 size-large" src="https://drunkenux.com/wp-content/uploads/2018/02/Search_Console_-_Structured_Data_-_https___shakespeares_com_-1024x651.jpg" alt="Menu schema identified inside of Google Search Console under Structured Data" width="850" height="540" /></a> Menu schema identified inside of Google Search Console under Structured Data[/caption]

With the schema data, you can see Google reporting on the availability of the identified menu information inside of Google Search Console. This is the quick way to ensure your menu is being scraped properly by Google. They go into much more detail on this process over in <a href="https://deltasys.com/blog/add-restaurant-menu-google-search-results-knowledge-panel/">their post at Delta Systems</a>, so take a few minutes and swing by their site and get all the details.

We hope you found this followup information helpful! Special thanks to our listener Jonathan for drawing our attention to this recent change in Google-Land. If you've listened to an episode and feel like we've missed an important point, or there's been new information since we first aired, please don't hesitate to reach out so we can share that new information with our listeners as well. You can reach us either via social media, <a href="https://drunkenux.com/talk-to-us/">our contact page</a>, or <a href="/slack">our Slack channel</a>.