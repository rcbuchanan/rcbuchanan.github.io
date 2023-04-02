---
layout: default
title: Various School Projects
---

## Global Routing Solver (CAD)

For the uninitiated, the global routing problem is *very* similar to a game called [Flow Free](https://en.wikipedia.org/wiki/Flow_Free)---a game so simple you can probably figure it out by looking at the logo. The version of the "game" that our program solves is a bit more complex though. Instead of just two points, a path (called a "route") usually have to a set of many points (called a "net"); to make up for this, nets are allowed a to overlap a limited amount.

Compared to commercial solutions this one is very simple, but it was good enough to be the best in our class (which was made mostly of graduate students).

The general tactic of the program is called "rip-up and reroute." It works by first routing each net independently, ignoring possible collisions with other nets, then ripping-up the routes causing the most congestion so they can be snaked around the already busy sections. The program keeps on ripping-up and rerouting until it can't improve anymore (or is told to stop).

Below is a picture of one of the problems in the process of being solved, and here is the source [on github](https://github.com/rcbuchanan/ece556-router).

![congestion](/uploads/congestion.png)

## Compiler for a C-like Language

This compiles a C-like language into MIPS assembly language (our Computer Science department *really* likes MIPS). It's written in ANTLR/Java, so it was a nice friendly environment to experiment with---not too many sharp edges. Compared to other projects I've done this one wasn't very creative, but it was a good learning experience. In addition to implementing the whole grammar with ANTLR, we were required to use a parse tree skeleton that implemented the visitor pattern. This was my first exposure to design patterns in Java, and I've been much more conscientious of them since.

Here it is [on github](https://github.com/rcbuchanan/minicCompiler).

## RISC processor

## RTOS for senior design project
