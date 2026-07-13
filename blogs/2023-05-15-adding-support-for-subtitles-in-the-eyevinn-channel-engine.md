---
title: "Adding support for subtitles in The Eyevinn Channel Engine"
url: "https://dev.to/video/adding-support-for-subtitles-in-the-eyevinn-channel-engine-3ec6"
date: "2023-05-15"
author: "Johan Lautakoski"
feed_url: "https://dev.to/feed/video"
---
In this blog post, I'll describe how I added support for subtitles in the Channel Engine so it could play subtitle tracks. I will also assume that the reader is somewhat familiar with the HLS streaming format and Channel Engine or has at least read the documentation in the Channel Engine git repo , or this article link beforehand. Introduction The Eyevinn Channel Engine is an Open-Source service that works well with VODs, But before we get into it, I need to clarify what I mean when I say "subtitle tracks" and "subtitle groups", as I will be using these words throughout this post.
