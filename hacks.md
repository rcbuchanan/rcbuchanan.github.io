---
layout: default
title: Hacks
---

## Haxagon

This is an AI I wrote to play the game [Super Hexagon](http://superhexagon.com/).

Instead of bothering with all that screen scraping and image processing stuff like most game AIs, I'm using the `LD_PRELOAD` trick as a wiretap between the Super Hexagon binary and the OpenGL shared library in order to access triangle data straight from the source. If I was entering a Super Hexagon AI programming competition this would probably be considered cheating---but I'm not, so it isn't.

For now, I'm declaring this project complete. It isn't perfect, but it can beat five of the six stages, including the final stage that triggers the game's "true" ending. By contrast, I can clear two stages---almost three--and I consider myself to be not-too-bad at the game.

Below is a somewhat over-compressed video of clearing the last stage, and here is [the program](http://github.com/rcbuchanan/haxagon) that did it.

<video controls>
  <source src="/uploads/win.webm" type="video/webm">
  An webm video should be here instead of this text.
</video>
