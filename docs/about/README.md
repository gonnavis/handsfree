---
prev: /community/
next: false
---
# About Handsfree.js.org

## Master Plan

1. Create a library that makes face, hand, eye, and pose tracking and voice and mind control easy to use 
2. Use the library to build a repository of custom handsfree plugins, components, and gestures
3. Use the repository to seed a "user script manager" to power a handsfree browser extension
4. Grow a community of handsfree users and developers around the library and repository
5. Start "The Handsfree Foundation" to promote creative expression

## Special Thanks

This project couldn't have been possible without:

- Invitations to residencies at [The STUDIO for Creative Inquiry]() (Spring 2019, 2021)
- Grant from [Glitch.com](https://glitch.com) (Winter 2019)
- Grant from the School of AI Grant (Fall 2018)
- Grant from [Google PAIR](https://pair.withgoogle.com/) (Spring 2018)

## Support Handsfree.js.org

Please consider supporting this project 💜 There are several ways to help:

- [Sponsor the project on GitHub](https://github.com/sponsors/midiblocks)
- [Make a Pull Request](https://github.com/midiblocks)



<blockquote>
  <div class="text-center">
    <p>Thanks to all of <a href="https://github.com/midiblocks/handsfree#thanks-to-the-handsfreejsorg-github-sponsors">our GitHub Sponsors</a>, including:</p>
  </div>
  <hr style="margin: 20px auto">
  <div class="text-center">
    <a href="https://github.com/nsthorat"><img src="https://avatars3.githubusercontent.com/u/1100749?s=460&u=99b5107179ac8a00bff093bd4b67b5898301119b&v=4" height=48></a>
  </div>
</blockquote>

## Changelog

<div class="next-element-is-changelog"></div>

| Date | Version | Description |
| ---- | ------- | ----------- |
| 2020-01-18 | 8.2.2 | Adds new [palmPointers plugin](/ref/plugin/palmPointers/) and updates the [pinchScroll plugin](/ref/plugin/pinchScroll/) to support all hands. Also adds a new `/boilerplate/cdn/pinch-scrolling.html`
| 2020-01-13 | 8.2.1 | Adds new [normalized helper](/ref/model/handpose/#data): `handsfree.data.handpose.normalized`. These `[x, y, z]` are similar to `.handpose.landmarks` but normalized between [0, 1]
| 2020-01-06 | 8.2.0 | Adds [TensorFlow Handpose](/ref/model/handpose/) including a basic THREE boilerplate remixed from [@LingDong-'s handpose-facemesh-demos](https://github.com/LingDong-/handpose-facemesh-demos), and a fingertip raycaster
| 2020-01-01 | 8.1.2 | Fixes [Face Pointer](/ref/plugin/facePointer/) offsets, which was causing the pointer to assume you were facing straight up 😆
| 2020-12-31 | 8.1.1 | Adds [pinchers Plugin](/ref/plugin/pinchers/) for easily working with finger pinches through events, new properties, and styles
| 2020-12-30 | 8.1.0 | Adds [.showDebugger()](/ref/method/showDebugger/), [.hideDebugger()](/ref/method/hideDebugger/), and helper classes. Renames `feedback` to `debugger`
| 2020-12-29 | 8.0.10 | Fixes a bug where `handsfree.debug.$video` had 0 width and height; Fixed issue where the webcam feed was not showing behind model wireframes when `handsfree.config.showDebug === true`
| 2020-12-28 | 8.0.9 | Adds [isClient Mode](/ref/prop/config#isclient) for remote inference. [.runPlugins()](/ref/method/runPlugins/) [.TweenMax()](/ref/method/TweenMax/), [.throttle()](/ref/method/throttle/), reduced filesize by 80kb+
| 2020-12-22 | 8.0.7 | Adds [handsfree.model.weboji.isDetected](/ref/model/weboji/)