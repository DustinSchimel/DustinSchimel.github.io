---
layout: page
title:  "Minor Scale"
date:   2023-04-26 0:0:0
categories: ["complete"]
---
Minor Scale was my very first large-scale team game, which took place over the course of two semesters. It’s a simple rhythm game combined with tower defense features and a cute 2D/3D hybrid aesthetic.

<center><iframe width="642" height="362" src="https://www.youtube-nocookie.com/embed/gT3EOulVUow?si=XvPZxlDXvWLT-nsu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></center>

This was my first time using Unreal Engine and Perforce. My main tasks during the project were related to enemy types, enemy waves, rebindable controls and UI.

### Enemy types
All of the enemies are children of a parent class, with slight variations added to account for their stats or special abilities. These stats are taken from a data table that the enemy designers can easily change and adjust. The enemies follow a simple spline that can be created by the level designers. They have methods for things like taking damage, taking damage over time, being slowed, and more, which the tower creation team can utilize when designing their types of towers. Below is a picture of enemies moving down a simple spline.

<center><img src="{{ '/assets/img/EnemyPhoto.png' }}" id="enemy-img"></center>

### Enemy Waves
This is where the bulk of my time was spent during this project. I wanted to create a system similar to [Bloons TD 6][bloons-steam], where enemies appear in groups of the same type with breaks between spawns, and then it switches to different types of enemies. I developed a system that allowed designers to adjust values within a data table for the waves to see what worked best. Everything about the waves can be changed, including enemy types spawned, the number of enemies in each group, the time before each group spawns, the time between spawns within the same group, the cash reward for clearing each wave depending on difficulty, and which path the enemies take (if there are multiple paths). Below is a picture of part of the wave data table for level 1.

<center><img src="{{ '/assets/img/WavesPhoto.png' }}" id="waves-img"></center>

### Rebindable Controls
This was something we actually didn’t plan on adding to the game, but I had an opening in my tasks and decided to take it on. I was very happy that I did, as it allowed me to make our game more accessible to a wider range of people. All the controls within the game can be rebound, except for mouse controls. This even enables the game to be played on devices like the Steam Deck!

### UI
I created our main menu, pause menus, and the in-game UI. I aimed to make them as fluid and polished as possible. The in-game 3D UI updates dynamically depending on the incoming wave, the player's current amount of money, and their number of lives remaining. The first video above shows the 3D UI inside the level, while the video below displays the main menu and rebindable controls.

<center><iframe width="642" height="362" src="https://www.youtube-nocookie.com/embed/SOFNBFVjhWE?si=rQBwblIpLVV-NTpU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></center>

**Installation** 

You can play the game by following these links to [Steam][ms-steam] or [Itch][ms-itch]. You can also use the widgets below.

<center><iframe src="https://store.steampowered.com/widget/2376030/" frameborder="0" width="646" height="190"></iframe></center>
<div style="height:10px;font-size:1px;">&nbsp;</div>
<center><iframe frameborder="0" src="https://itch.io/embed/1948909?bg_color=dbdbeb&amp;fg_color=222222&amp;link_color=6d75f9&amp;border_color=00b58f" width="646" height="167"><a href="https://minor-scale-dev.itch.io/minor-scale">Minor Scale by Keyboard Critter Co, CosmicQuail, Dustin Schimel, mmorg00, wenylli, Viktor the Great</a></iframe></center>

**Team** 
- Ao Tan - 2D Artist
- Bryan Nguyen - Engineer
- Bryce Morrice - 3D Artist
- Cameron Lentz - Engineer
- Cat Worsey - Producer
- Christopher Chen - Engineer
- Craig Nash - Designer, Producer
- Darshan Jayamohan - 2D Artist
- Dustin Schimel - Engineer
- Dylan Habersetzer - 3D Artist
- Edward Tan - Designer
- Hayley Kocherhans - 3D Artist
- June Kaseda - Designer
- Justin Sundermeyer - Composer, Designer
- Katrina Makarewicz - Technical Artist
- Max Morgan - Engineer
- Qiaochu Wu - 2D Artist
- Tyler Jones - Technical Artist
- Viktor Hensen - Technical Artist
- Wendy Hoang - 2D Artist
- Will Loxley - Producer

[ms-steam]: https://store.steampowered.com/app/2376030/Minor_Scale/
[ms-itch]: https://minor-scale-dev.itch.io/minor-scale
[bloons-steam]: https://store.steampowered.com/app/960090/Bloons_TD_6/