---
title: "Big week for Parasitter!"
date: 2020-08-16T15:41:23+02:00
draft: false
layout: dnd
toc: false
images:
tags:
  - Parasitter
---

This week has been great for Parasitter! I have been working on a easy solution in order to protect user's privacy while using Parasitter.

I started relying on Invidious as a 'third-party' to stream the videos and get all the data, but since the announcement that we commented on the previous post
I had to change it. So I started a new Parasitter branch where I am working to break any dependency with Invidious.

A very useful tool for this is `youtube-dl` with it I can get the `GoogleVideo` link. It is curious that Youtube is embeding a video from GoogleVideo on its webpage.
So I can't use the Youtube url as I would be dealing with a request to the video html page and not the video itself. So I need this GoogleVideo link so I can stream
**just** the video.

This is interesting, and at the same time annoying. Youtube (or Google) doesn't have an easy translation to the GoogleVideo link. It is not like changing the `youtube.com`
for a `googlevideo.com`. GoogleVideo links are very complex and random, so I can't guess a video's link with just its id. There are plenty of methods for doing this, but
with `youtube-dl` it is **very** easy.

But Parasitter is a tool for protecting users privacy. So I can't make the client stream a video from GoogleVideo, as it would be awful. Parasitter's users should **never**
make any connection to Google. The only requests that a user should be doing are to Parasitter itself.

For doing so, I need to proxy a stream of video to the client through Parasitter. I started reading and trying to understand how Invidious did it. I also got in contact wiht
Invidious creator, Omar Roth, which he kindly answered my questions (Thanks!). I made my own research with the things I learned and finally I got it to work using Python and
Flask. So now when users connect to a (remote) Parasitter server, they will never connect to Google when wathcing videos!

## Next steps
Next steps are proxying the video thumbnails, as for now they are served from `ytimg` (a service that google uses for storing and serving youtube images). Also I need to start
working on the configuration page as it lacks most fundamental functions. Another good thing that I will be working on the future is on the ability to watch livestreams directly
from Parasitter. And lastly, but not less important, the ability for the user to see a channel page directly from Parasitter.

## Conclusions
So that's it! It's been a great development week for Parasitter and it looks very good! I hope I can start testing on a public instance before September.
