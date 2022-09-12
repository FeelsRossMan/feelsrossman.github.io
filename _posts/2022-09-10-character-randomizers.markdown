---
layout: post
title:  "Character Randomizers"
date:   2022-09-10 14:50:00 -0700
# categories: Projects
published: true
---
Main goal this week was to make a simple app that would give me a random character for the video game Apex Legends (and maybe random guns or something as well). The initial app was fine, I mean after all its just a number generator with pictures, but I wanted to use it as an opportunity to work on my Jetpack Compose skills, and to work on organizing my apps better. 

While working on that I found that Philipp Lackner has a whole tutorial Pokedex app in Jetpack Compose ([**link to the first video**](https://youtu.be/v0of23TxIKc)) which had a lot of info on Dagger/Hilt dependency injections, using Retrofit for APIs, and just general practice for Jetpack Compose, so I decided to follow through the tutorial from start to finish. Definitely worth it. 

In addition to that, I also found that League of Legends (another game I play) has a [**pretty solid open API**](https://developer.riotgames.com/docs/lol) with tons of options, so I think that'll be the next quick project. I'll start with another randomizer, just like [**ultimate bravery**](https://www.ultimate-bravery.net/), then maybe try something more involved. Not sure yet but my first thought is to do some kind of character builder app, where you can pick your champion, your load-out, which skills you level up, what your build path is, and even share it with friends. 

For now I'm going to add some more functionality to the Apex Randomizer and pretty it up so it's not so plain. I'm not going to publish it to the app store since I just copied all the image assets straight from EA's website, but here's a link to the GitHub repo for it: [**Apex Randomizer**](https://github.com/FeelsRossMan/RandomApex)

I've attached a couple photos of what the app is right now below. The improvements I'd like to make are:  
1. Add an option to remove characters from the options pool before rolling.
2. Add a re-roll button on the Character Screen. I'll also inject the current instance of the Character data class into the associated ViewModel
3. Make the color scheme of the Character Screen reflect the rolled character
4. Add animations for revealing the rolled character 
5. Add gun load-outs with all the previously listed ideas (options pool, coloring, animations)

I might think of a few more things but that'll probably be it on this app for now. Hopefully by next post it's finished and I've started work on a League of Legends app. All for now.

![HomeScreen](/assets/images/2022-09-10-HomeScreen.png) ![ApexCharacterScreen](/assets/images/2022-09-10-CharacterScreen.png)