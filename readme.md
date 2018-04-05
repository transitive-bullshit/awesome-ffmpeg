# Awesome FFmpeg [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome [ffmpeg](http://ffmpeg.org) resources with a focus on JavaScript.

<p align="center">
  <img width="400" src="https://cdn.rawgit.com/transitive-bullshit/awesome-ffmpeg/master/ffmpeg-logo.svg">
</p>


## Contents

- [Docs](#docs)
- [JavaScript](#javascript)
- [Mobile](#mobile)
- [Tutorials](#tutorials)


## Docs

FFmpeg's official docs are notoriously difficult for beginners to understand due to the scope and complexity of ffmpeg's capabilities. With that being said, they're still very useful as a reference.

- [FFmpeg.org](http://ffmpeg.org/) - Where it all starts.
- [Filters](https://ffmpeg.org/ffmpeg-filters.html) - Docs for ffmpeg's powerful filter chains (scaling, cropping, concatenating, merging, etc.). This is one of my most visited links when working with ffmpeg.
- [Man page](https://man.cx/ffmpeg) - Official ffmpeg man page.
- [Wiki & Bug Tracker](https://trac.ffmpeg.org/) - Lots of great info on here.
- [CLI flags](https://github.com/transitive-bullshit/ffmpeg-cli-flags/blob/master/readme.md) - A comprehensive list of all ffmpeg commandline flags. Really useful for searching random flags that you come across in the wild.


## JavaScript

- [fluent-ffmpeg](https://github.com/fluent-ffmpeg/node-fluent-ffmpeg) - A fluent API to [FFmpeg](http://www.ffmpeg.org). If you only use one tool from this list, it should be this one.
- [ffmpeg-probe](https://github.com/transitive-bullshit/ffmpeg-probe) - Wrapper around ffprobe for getting info about media files.
- [ffmpeg-concat](https://github.com/transitive-bullshit/ffmpeg-concat) - Concats a list of videos together using ffmpeg with sexy OpenGL transitions.
- [ffmpeg-generate-video-preview](https://github.com/transitive-bullshit/ffmpeg-generate-video-preview) - Generates an attractive image strip or GIF preview from a video.
- [ffmpeg-extract-frame](https://github.com/transitive-bullshit/ffmpeg-extract-frame) - Extracts a single frame from a video.
- [ffmpeg-extract-frames](https://github.com/transitive-bullshit/ffmpeg-extract-frames) - Extracts screenshots from a video using ffmpeg.
- [ffmpeg-extract-audio](https://github.com/transitive-bullshit/ffmpeg-extract-audio) - Extracts an audio stream from a media file.
- [ffmpeg-on-progress](https://github.com/transitive-bullshit/ffmpeg-on-progress) - Utility for robustly reporting progress with fluent-ffmpeg.
- [ffmpeg.js](https://github.com/Kagami/ffmpeg.js) - Port of FFmpeg to JavaScript via Emscripten. Allows for limited ffmpeg use on the client-side.
- [ffmpeg-static](https://github.com/eugeneware/ffmpeg-static) - Provides static ffmpeg binaries for Mac OSX, Linux, and Windows. Extremely useful for CI testing.


## Mobile

- [simplest ffmpeg mobile](https://github.com/leixiaohua1020/simplest_ffmpeg_mobile) - FFmpeg examples for Android and iOS.
- [ijkplayer](https://github.com/Bilibili/ijkplayer) - Android / iOS video player based on FFmpeg


## Tutorials

- [How to Write a Video Player in Less Than 1k Lines](http://dranger.com/ffmpeg/)
- [Learn FFmpeg libav the Hard Way](https://github.com/leandromoreira/ffmpeg-libav-tutorial)
- [Applying OpenGL Shaders with FFmpeg](https://nervous.io/ffmpeg/opengl/2017/01/31/ffmpeg-opengl/) and [follow-up](https://nervous.io/ffmpeg/opengl/2017/05/15/ffmpeg-pbo-yuv/)


## Contribute

Contributions welcome! Please read the [contributing guideline](contributing.md) first.


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0) @ [Travis Fischer](https://github.com/transitive-bullshit)
