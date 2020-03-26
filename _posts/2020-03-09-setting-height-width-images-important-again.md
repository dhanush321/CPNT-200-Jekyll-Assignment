---
layout: post
title:  "Setting Height And Width On Images Is Important Again"
date:   2020-03-09 00:00:00 -0600
categories: post
---
Web performance advocates have often advised to add dimensions to your images for best performance to allow the page to be laid out with the appropriate space for the image, before the image itself has been downloaded. This avoids a layout shift as the image is downloaded — something Chrome has recently started measuring in the new Cumulative Layout Shift metric.

Well, a dirty, little, secret — not that well-known outside the hard-core web performance advocates — is that, until recently, this actually didn’t make a difference in a lot of cases, as we’ll see below. However, adding width and height attributes to your img markup have become useful again after some recent changes in the CSS world, and the quick adoption of these changes by the most popular web browsers

[-Barry Pollard](https://www.smashingmagazine.com/2020/03/setting-height-width-images-important-again/ "https://www.smashingmagazine.com/2020/03/setting-height-width-images-important-again/")