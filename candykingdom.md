---
layout: inner
title: Candy Kingdom
permalink: /candykingdom
---

![](/img/posts/candy_main_menu.png)

<div style="text-align: justify">

<h2> Candy Kingdom: Tower Defense </h2>

<p style="font-size:1.3em">
    This is a project that I made in SHU (Sheffield Hallam University) with a team of 3 artists, 1 designer and 4 programmers. We made this game for PS4, in our engine that we developed during the year using PS4 SDKs. This game is a tower defense where the player needs to place turrets in a level, with one or more paths, and defend it from hordes of enemies. It has two game modes, one that follows a number of 5 designed levels which get harder when you progress, and another one that generates a new level each time you play.
</p>

<p style="font-size:1.3em">
    In this project I developed even more my communication skills inside a working group enviroment, and even I discovered some industry workflows like scrums, where we had meetings every week to know how was the work going. But apart from that, I focused on the audio, the collisions and a data-driven system for the resources.
</p>

<h3> Audio </h3>

<p style="font-size:1.3em">
    The first functionality of the audio system was focused on handling a high level audio library from the PS4 API, which required to control the initialization, update and termination of the system.
</p>

<p style="font-size:1.3em">
    The second functionality focused on managing the state of the different audio sources, so things like play, pause, stop or resume audio sources, and also setting their principal values, such as volume, pitch and toggle looping.
</p>

<p style="font-size:1.3em">
    And we also had a function to be able to load audio files in memory.
</p>

### Collisions

<p style="font-size:1.3em">
    The collision system in our game was a pretty simple approach of what is known as AABB collisions and Sphere collisions, so I just used some mathematical calculations with simple shapes to detect collisions between our game elements.
</p>

### Data-Driven Levels

<p style="font-size:1.3em">
    The last thing I took part of in this project was handling the designed levels inside and outside the engine. So I had to act as a "bridge" between the designer and the engine itself, so the task of testing this levels could be as easier as it could.
</p>

<p style="font-size:1.3em">
    That's why we have made use of <a href="https://www.mapeditor.org/">Tiled</a>, an external tool that is pretty useful for designing the levels' shape and layout. With this tool and a tileset, the designer could work on the levels by specifying a tile type for each tile in the level, and then export it into an xml, which I could read through code and load directly into the engine. The designers task was just to design the level, and then drop it in the correspondent directory, so the level could be seen in the engine.
</p>

<!-- [Tiled](https://www.mapeditor.org/) -->

</div>

![](/img/posts/candy_level1.png)
Example of the first level of the game.

