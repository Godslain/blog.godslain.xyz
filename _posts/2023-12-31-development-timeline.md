---
layout: post
title:  "The Team & Timeline Going Forward"
date:   2023-12-31 00:00:00 +0100
author: Demecate
type:   devblog
excerpt: "For a whole year, we've been working heavily on terrain, in-game buildings, and the general design."
---

# 2022's Progress

For a whole year, we've been working heavily on terrain, in-game buildings, and the general design. [TLDR](#what-the-future-holds)

This project started almost exactly a year ago when we were brainstorming with `Deniz` [Deniz's ArtStation](https://www.artstation.com/denizgur). We worked together for two months, with him making the 3D assets and me writing the code. Being smarter than myself, he decided to pursue other projects when we realized we were in over our heads. I, on the other hand, continued to develop a basic version of the game. At this point, we had a top-down camera, enemy AI, enemy patrols, and character levels. The playable character was a free asset from the Unity store, and for the buildings, I've used Deniz's previous work. You can find his assets for `Red City` here:

[City Prototype](https://www.artstation.com/artwork/XgPgqy)

## Getting The Team Together

I'm horrible at visual arts, so I needed a new partner in crime. After three months, I started a search for a 3D artist. By the end of my fifth month of development (May 2023), I hired `Astrid` to work on all our assets, including characters, buildings, props, and the Unity terrain. She has done a great job so far!

I hadn't really written C# before working on `Red City` nor used Unity, so it had been quite a learning process. For me, learning the engine was the harder part. Being a C and assembly geek myself, I found that I really like writing C# despite my prejudices. "This is easy!" I thought. I soon found out that it's only easy until you stumble into Unity animator hell. A considerable proportion of my time was spent on writing animation controllers.

Soon, I figured we needed another developer, hopefully someone who knows the Unity internals better than I do (you don't really find that stuff in tutorials). I had been warned by my friends in the industry that game development is a very hard business. It's harder if you have a full-time job. During my two-month-long search, I've done countless interviews and worked with 4 different developers briefly. During this time period, we've experimented with many ideas. We ended up implementing and later on scrapping the following:

- A top-down camera version of the base game with a click-2-move controller
- A hack-and-slash version of the base game using a third-person controller
- A first-person `Elder Scrolls-like` version of the base game
- An RTS version of the base game where the player controls ally units
- A behavior tree for the enemy AI
- Three completed character models
- A set of character animations

I have also tried different character control assets off the Unity store; I didn't find them to be versatile enough, and the code quality and/or design choices would have been a major issue in the future.

Now, my friends have also told me that my first game should definitely not be a full-fledged RPG. I know that most people aim for something simple. I don't see the fun in that. I also know it's much easier to push a game out if you make all the choices regarding game mechanics beforehand; things will move much faster. But to make anything that you can call art, I strongly believe one shouldn't settle at the first thought that comes to one's mind. That being said, on month 6 (June), I was done experimenting and set out to redefine the GDD for a final time. I will be sharing more details about skills and progression in a later post.

It was evident that we needed a top-down camera because it is hard to see what your troops are up to when you're closer. However, our hand-painted assets look very good close up, and it's a more immersive experience to walk around with your character. The final decision for the controller is to default it to a top-down view while allowing the user to switch to 3rd person. The game is a real-time RPG and isn't turn-based. So we need to be able to stop time for the player to think about what actions to take every once in a while. All this aside, we would use a targeted combat mechanic; otherwise, it gets too hectic during a 40v40 army fight. Currently, we're aiming for a controller like the one in `Dragon Age Origins`.

Towards our 8th month, I stumbled across `relik`, who is an excellent programmer with good knowledge of Unity internals & HLSL. He started working on the project immediately and has been with us since. He has developed quite a lot on top of the base game.

## What The Future Holds

Currently, we have a working quest system, skills, stats, inventory management, a leveling system, a saving system, an army controller which easily supports 80 mobs (e.g. 40 vs. 40), an open world terrain, and a city for shops & quest, and our first dungeon. We have [3 unique music tracks](https://redcity.ink/music/), extensive lore, a [conlang](https://redcity.ink/lore/) with a [runic alphabet](https://runes.redcity.ink) & a [custom font](https://runes.redcity.ink/S1-Regular.ttf), made specifically for `Red City`.

In the following 2 months, we'll be adding quests and content to the game, re-doing the city terrain, adding creatures and NPCs. `Astrid` and `relik` will be sharing their previous progress on the game in a time-travel sort of manner. This blog will remain a safe space where we talk about experiments, failures, and whatever else we'd like to share.

## The Team

We have `Astrid` working on assets & animations, `relik` working on development & level design, Me, working on development & everything else.