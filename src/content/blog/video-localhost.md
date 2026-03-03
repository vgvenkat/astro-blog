---
title: 'Youtube video localhost'
description: 'A quick note about using video tags with YouTube and Vimeo URLs in web projects.'
pubDate: 'Aug 28 2017'
---

Currently working on a redux project and came across an issue where `video` tag does not take youtube or vimeo src urls. Aparently they are not in the right format, so use a local mp4 video. To embed the url source video better use iframe.

> Note for myself: For blogpost frontmatter date, use `new Date().toISOString()` in chrome console to get date. Needs updating for automation. Good for now
