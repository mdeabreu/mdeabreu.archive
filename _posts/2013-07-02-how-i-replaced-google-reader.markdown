---
layout: post
title:  "How I Replaced Google Reader"
date:   2013-07-02 21:52:00
category: "Tutorial"
---

As I'm [sure](http://lifehacker.com/google-reader-is-shutting-down-here-are-the-best-alter-5990456) [you](http://mashable.com/2013/07/01/google-reader-final-countdown/) [know](http://www.huffingtonpost.com/2013/07/01/google-reader-shut-down_n_3518733.html) Google Reader is about to bite the dust, so I thought I would write about how I replaced it with something just as good, if not better. Some of the main reasons I loved Google Reader was because it put all of my feeds in one synced location; I could wake up in the morning and read on my desktop, continue where I left off using my phone while transiting to school and then read on my laptop between classes. There were so many apps for iOS, Android, Windows and Mac that it didn't matter what device I had, I could still sync with Google Reader not to mention if I didn't have an app installed I could just visit the web app. Soon, however, Google Reader will disappear forever and I needed something to replace it.

I tried several different tools that were supposed to be "perfect" replacements but they were always missing one feature or another, or they didn't work in quite the same way. One majour deal breaker for a lot of these Reader replacement was the lack of offline reading and then syncing any changes when a connection reappears. This is very important for me since I don't have a data plan and spend a lot of time on public transit, I need to be able to pull down all my unread articles and then push my changes once I get reconnected to wifi. Luckily I managed to find the perfect replacement; it has a web app, and has an API so that any app on any platform can access the feeds, and the app I'm using supports offline caching so I can continue to read during transit rides. It's a perfect replacement for Google Reader and it might be just what you're looking for.

Meet [Tiny Tiny RSS](http://tt-rss.org), a [plugin](http://tt-rss.org/forum/viewtopic.php?f=22&t=1981) to emulate the [Fever API](http://www.feedafever.com/api), and [Reeder](http://reederapp.com/).

<!--more-->

[Tiny Tiny RSS](http://tt-rss.org) is a self hosted RSS web app very similar to Google Reader, installation is very simple: just unzip the latest version into your webserver's public directory, visit the install page with your browser, follow the onscreen instructions, and voila! You end up with a portal you can visit to read your feeds, a wide variety of options to sort through articles, preferences to alter just about every aspect of your reading experience, and the ability to install and enable plugins to enhance the base installation. For quite a while I just used tt-rss and a few plugins such as adding a checkbox to mark an article unread or not, adding embedded video support, a mobile page, and a minimalistic theme. While this worked well for a while I found a way to make it even better.

One day while feeling a little curious I went to the tt-rss forums and found a [plugin](http://tt-rss.org/forum/viewtopic.php?f=22&t=1981) that emulated the [Fever API](http://www.feedafever.com/api) and showed how to use this with the iPhone app by the name of [Reeder](http://reederapp.com/). After a bit of research into what the Fever API is and if the app would suit my needs I determined that this was exactly what I wanted. I installed the plugin (which was just unzipping an archive, enabling it, and then setting a password) and downloaded the app. The whole process took less than 2 minutes! Now I'm able to read my feeds using the web app or I can sync the feeds to my phone using Reeder which will even cache the articles and sync the changes once I get an Internet connection again.

Overall I am extremely happy with my new setup, my only complaint so far is that after reading offline syncing is a bit slower than with Google Reader; but all in all I could not ask for a better replacement.
