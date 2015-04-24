---
layout: post
title:  "Video, photos and more..."
date:   2014-08-01
categories: doarama
tags:
- technical
- social
---


[]()One of our most common support requests is to be able to add synchronised photos and video to the 3D map visualization provided by Doarama&trade;.
We are excited to announce that we have just rolled out a range of changes to support this functionality via the YouTube and Instagram APIs.
In our testing synchronised video works best in Google Chrome browser, and even surprisingly well on Nexus 4 & 5 (you may need to press play/pause a couple of times for the video to work on Nexus).
Let's start with a couple of examples (click to view).

First up is Don Vella mountain biking on the Oaks Fire Trail single track in the Blue Mountains west of Sydney, Australia.

[![Mountain Biking]({{ site.url }}/assets/2014-08-01-mtb.jpg)](http://www.doarama.com/view/8135)

Next is Simon Wilks with a Wing Wing Z-84 autonomous flight in the Swiss Alps.  More detail on this flight can be found [here](https://www.youtube.com/watch?v=RK6j2pEe-xM)

[![Autonomous Flight]({{ site.url }}/assets/2014-08-01-autonomous.jpg)](http://www.doarama.com/view/8138)

Finally, here is a bike ride by Chris Cooper in north western Sydney showing some photos and comments along the way.

[![Bike Ride]({{ site.url }}/assets/2014-08-01-bike.jpg)](http://www.doarama.com/view/8140)

Many thanks to Don, Simon and Chris for providing these examples which have been extremely helpful during development.

There are a number of changes included in this rollout, and we'll continue to work hard to improve these features over time.

* New picture-in-picture control for displaying video and photos.  Click/touch to swap displays.
* Revised text comment feature with improved support for long comments.
* New edit UI (shown below) with synchronisation controls for media elements and trim controls.
* New time slider which shows when media is present.  It also has improved usability on touch devices.
* Automatic playback rate change when video is present.  e.g. Play at 32x then drop back to 1x during video.
* Updated 3D map display allowing you to jump in time e.g. to the start of a video or text comment by clicking on the dot, icon or text.
* Using [STK World Terrain](http://cesiumjs.org/data-and-assets/terrain/stk-world-terrain.html) which has more detailed terrain data, particularly in Australia, Europe and USA.

There have also been some updates to the [Doarama Terms of Use](http://www.doarama.com/terms) to support the use of photos and videos.
The Doarama API will also be updated to support the new photo, video and text comment functionality in due course.

![Edit UI]({{ site.url }}/assets/2014-08-01-edit-ui.jpg)
