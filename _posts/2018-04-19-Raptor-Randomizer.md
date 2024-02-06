---
layout: page
title:  "Raptor Randomizer"
date:   2018-04-19 0:0:0
categories: ["complete"]
---
Raptor Randomizer is a Java Applet that randomizes League of Legends champions, item builds, runes, and summoner spells. It was inspired by a website called Ultimate Bravery, which does mostly the same thing but in a web format. This was made for an AP CS class and was my final project. There are no plans on updating this, and it's basically unusable for current League of Legends since it was made for season 8. There is no downloadable build available, but there is a video included below of it working, and if you really want to build it the code is available on [GitHub][raptor-git].

<center> <iframe width="511" height="315" src="https://www.youtube.com/embed/MLMRyT-8hxw?si=sm9AwkH32ncWjm_V" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe> </center>

Due to this being one of my first projects, there is a lot of redundant code and things I would change. Despite that though, there are some cool things going on here. In League of Legends certain items cannot be used with certain items, certain runes cannot be used with other runes, and other things like that. Because of this, there are many conditional statements that make sure only usable builds, runes, and summoner spell combos are provided to the user. This was also one of my first uses of a MVC structure and exploration of the uses of inheritance.

[raptor-git]: https://github.com/DustinSchimel/Raptor-Randomizer
