---
layout: default
title: Game Dev Experiments
---

# Game Dev Experiments

These are a few projects I started that I had hoped would turn out more complete and polished than they actually did. I might pick them back up later, but they've already served their purpose by being entertaining and giving me a chance to play around with different software packages.

Some of this code is gets a little hacky; I wouldn't say it's necessarily reflective of the way I develop code professionally.

## Staredust
*uses Haxe flixel*

This is a clone of an old mac puzzle game I really liked. I extracted the original's assets/puzzles and cloned the mechanics, but I'm hoping to make my own assets and puzzles at some point.

Below is an example of gameplay (using a level and graphics from the original). [Source](https://github.com/rcbuchanan/staredust).

<video controls>
  <source src="/uploads/staredust_example.webm" type="video/webm">
  An webm video should be here instead of this text.
</video>


## Parachute

*uses javascript and SVG animation*

This is almost more of a javascript experiment than a game. Originally, I made a clone of the LCD game-and-watch "parachute" game, but then I decided I wanted to do my own artwork with a different theme.

The software adaptation isn't quite finished though, and neither is the art. I'm pretty happy with how the snakes/mice/hands turned out, but I just couldn't get the trees to look right. I'll probably finish them someday when I'm better at art.

[This version](/uploads/parachute.svg) runs in the browser using Right/Left keys. [Source](https://github.com/rcbuchanan/parachute).

## I. S. O.
*uses Irrlicht/C++*

The object of this game is to move a rubix snake type structure towards the goal while always having at least one segment touching an anchor point.

It was an interesting idea, but it turns out it's really obtuse. [Source](https://github.com/rcbuchanan/iso).

<video controls>
  <source src="/uploads/iso.webm" type="video/webm">
  An webm video should be here instead of this text.
</video>

## snakes

*uses Irrlicht/C++/lua*

Generates a 3D chutes-and-ladders maze via an external lua script. It doesn't do much more than look cool now, though it's possible to pan around the world and interact with a lua console. [Source](https://github.com/rcbuchanan/snakes).

![snakes screenshot](/uploads/snakes.png)
