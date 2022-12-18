---
layout: post
title:  "Minesweeper in Terminal"
date:   2022-12-17 20:45:00 -0700
# categories: Projects
published: true
---
Long time without posting. I started a new job and have been busy with it. 

Anyways, I've been learning python for some raspberry pi projects, and decided to make minesweeper in terminal for practice.
Initially I assumed it would be a fairly short and simple project, so I went at it with a mostly functional aproach only making a class to hold the grid and all the game functions.
This was a mistake. 
If I were to refactor I would make an inner class for the individual grid locations to move multiple functions into for things like getting the mine count and holding all the data. Functions like the game loop feel very out of place from within the Grid object. I may go back and fix this, but for now I'll leave it as is, it's not like I'm actually going to be playing the game outside of testing.
In case you want to check the project out you can find it at: https://github.com/FeelsRossMan/TerminalMinesweeper. All for now.