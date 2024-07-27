---
layout: page
title:  "Raptor Randomizer"
date:   2018-04-19 0:0:0
categories: ["complete"]
---
Raptor Randomizer is a Java applet that randomizes League of Legends champions, item builds, runes, and summoner spells. It was inspired by a website called Ultimate Bravery, which offers similar functionality in a web format. There are no plans to update this, and it is essentially unusable for the current version of League of Legends, as it was designed for season 8.

<center><iframe width="587" height="362" src="https://www.youtube-nocookie.com/embed/MLMRyT-8hxw?si=JhnKYpu5PY173rlN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></center>

Due to this being one of my first projects, there is a lot of redundant code and aspects I would change. Despite that, there are some interesting features here. In League of Legends, certain items cannot be used with others, certain runes cannot be used together, and other similar constraints exist. Because of this, there are many conditional statements to ensure that only valid builds, runes, and summoner spell combos are provided to the user. This was also one of my first experiences creating an MVC structure and exploring inheritance.

**Installation** 

There is no downloadable build available, but a video of it being used is included above. If you really want to build it, the code is available on [GitHub][raptor-git].

[raptor-git]: https://github.com/DustinSchimel/Raptor-Randomizer