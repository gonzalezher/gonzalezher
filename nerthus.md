---
layout: inner
title: Nerthus
permalink: /nerthus
published: true
---

![](/img/posts/nerthus_title_splash.jpg)
## Nerthus: Einar's Fate

<div style="text-align: justify">

<p style="font-size:1.3em">
    This is one of my last projects in ESAT (in spanish, Escuela Superior de Arte y Tecnología) that I made with a team of 4 artists, 1 designer and 6 programmers, and also with 2 musicians from Berklee, and we used Unreal Engine 4 as our game engine. Nerthus: Einar's Fate is a frenetic third person shooter where you play as a Guardian in his mission to return the heart of Nerthus to its sacred place. You will need to face hordes of different types of enemies, and defeat them while completing missions that appear throughout 4 levels and maps, and to do so, you will make use of elemental magics and spells.
</p>

<p style="font-size:1.3em">
    In this project, I focused on developing the AI, more specifically in creating the behaviour of 3 of the 4 enemies that the game has. This led to the realisation of everything related to behaviour trees, tasks and also blackboard keys. These enemies are:
</p>

<ul style="font-size:1.3em">
    <li>The werewolf is a melee pawn that chases the player and tries to make an attack when he is close enough.</li>
    <li>The elf is a ranged pawn that chases the player but tries to attack him from a far distance with a bow, so the arrow makes an arc and tries to predict where the player is going to move.</li>
    <li>And finally the golem, wich has two versions and is the bigger one. The first one is the "jumper" and attacks the player jumping into him. The second one is the "rock-launcher", wich throws a boulder with the same logic of the elf attack, but can also knock down the player if it hits him.</li>
</ul>

<!-- * <font size="4">The werewolf is a melee pawn that chases the player and tries to make an attack when he is close enough. </font>
* <font size="4">The elf is a ranged pawn that chases the player but tries to attack him from a far distance with a bow, so the arrow makes an arc and tries to predict where the player is going to move. </font>
* <font size="4">And finally the golem, wich has two versions and is the bigger one. The first one is the "jumper" and attacks the player jumping into him. The second one is the "rock-launcher", wich throws a boulder with the same logic of the elf attack, but can also knock down the player if it hits him. </font> -->

<p style="font-size:1.3em">
    Apart from this, I also took care of setting up the nav mesh provided by UE4 for all levels, as well as making custom nav links to give enemies the ability to jump between the different height levels on the maps.
</p>

</div>

You can also check the game in Steam [here](https://store.steampowered.com/app/1662670/Nerthus_Einars_Fate).