---
layout: post
title: Why I stopped using Adblock Plus - the magic of the hosts file
share: y
disqus: y
---

### A few years of Adblock Plus

I've been using Adblock Plus since 2006, the year it was released for Firefox.  This was two years before the release of Google Chrome.  For anyone who was even slightly technologically savvy, Adblock Plus had a huge impact on browsing the internet.  It changed the playing field and gave people a huge reason to migrate to Firefox and away from Internet Explorer.  Between addons (specifically Adblock Plus), and tabbed browsing, Firefox was a big deal.

In 2011, I encountered an issue with Firefox where it simply refused to open on my Windows machine.  Even a reinstall wouldn't fix whatever problem I had at the time, so I migrated to Google Chrome.  I've been using Chrome ever since.  What came with me, however, was Adblock Plus.

A few months ago I read [an article](http://www.reddit.com/r/programming/comments/25j41u/adblock_pluss_effect_on_firefoxs_memory_usage/) about ad blocking extentions exactly like Adblock Plus which surprised me.  It turns out that blocking ads in the browser is a demanding process.  It uses a bit of CPU power but in particular, it uses a lot of RAM and slows down page load times.

This news came to me around a time where my browser usage was becoming more and more intensive.  With Google making Chrome more and more into its own self-sufficient ecosystem of applications and dynamic content, I had fewer reasons to have regular applications open and more reasons to have many tabs open.  It is not uncommon for me to have over 10 tabs open when I am browsing the internet.  Between Gmail, Google Music, sometimes Facebook, a few Reddit tabs, and maybe a YouTube tab, I found that I was frequently devoting over 2 gigaBytes of RAM to Google Chrome alone.  Google Chrome was sluggish, and not really the high speed it always claimed to be.

### The hosts file

~~Enter the hosts file.~~  Well, not quite.  **Reenter** the hosts file.  Originally imeplemented in the 1970s, the hosts file was used by operating systems to map hostnames (such as google.com) to IP addresses (such as 74.125.224.72).  In 1984, a system which replaced the need for a manually set hosts file was released.  This system was called the Domain Name System, which we refer to today as just DNS.

But the hosts file was here to stay, giving the computer user to locally map any hostname to any IP address.  Usually the only thing that the hosts file includes today is a line that looks like the following:

