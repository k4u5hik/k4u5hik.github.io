---
title: Download audio from Youtube videos on Mac
layout: post
date: '2022-03-01 10:19:00 +1100'
categories: Terminal
---

This post is for Mac users who want to download audio from youtube videos

1. Open Mac Terminal
2. [Install Homebrew](https://brew.sh/) `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
3. Install yt-dlp `brew install yt-dlp`
4. Replace Youtube URL `yt-dlp -f 140 'https://www.youtube.com/watch?v=-44VdVFU9pY'`

Check [yt-dlp](https://github.com/yt-dlp/yt-dlp) documentation for more options and information.
