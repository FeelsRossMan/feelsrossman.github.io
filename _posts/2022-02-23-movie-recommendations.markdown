---
layout: post
title:  "Movie Recommendations"
date:   2022-02-23 17:45:00 -0700
# categories: Projects
published: true
---
I'm currently in the process of doing the computer science course on codecademy in order to get a better foundation for future projects.
Because of that I had to do a "recommendation" project to finish out the section on data structures. I decided to make a simple terminal program that takes a JSON containing a list of movies (taken from tmdb) and allow a user to type in a genre they like, and get back a list of movies of that genre. The program initially parses the JSON into a dictionary containing the genres as keys, and a list of movie dictionaries (each containing information about a movie of that genre) as values. The input can be part of the genre, or the whole thing, and it will try to infer what is meant. 
Later improvements would be: 
    - Interfacing with the actual API instead of using a prepulled JSON
    - Tabulating the returned movies instead of printing all at once
    - Allowing the user to enter multiple genres (i.e. searching for movies that fit both Sci-Fi and Horror)
In case you want to check the project out you can find it at: https://github.com/FeelsRossMan/MovieRecommendations. All for now.