---
title: Reflection on past projects
description: Thoughts on projects completed or no longer being worked on
slug: doneproj
weight: 1
categories:
#    - Pinned
tags:
#    - Pinned

---
### Josephloporto.com
```yaml
    Context: 
    This Website

    Well executed:
        -Nginx combined with Hugo make a powerful duo, which can easily 
         run forever on super light hardware with minimal hassle
        -This hosting service will be able to run for free likely indefinitely, 
         as long as I do not abandon it

    Missed value:
        -Utilizing Hugo templating more in depth along with a more robust 
         deployment system for posts would smooth the editing process
        -Diving deeper into tagging and posts themselves might allow
         me to create a better UX

    Lessons Learned:
        -Nginx and SElinux create a lot of headaches
        -For simple websites like this one, a lot can be done with Hugo
        -Learning more about yaml/toml will be a benefit in the future

    Notes:
        This website will continue to be developed as time goes on, this
        list may be edited as such to reflect the sum of the experience
```

### Discord Economy Bot (2021)
```yaml
    Context: 
    https://github.com/csjoey/DiscordEconBot
    While bored during the peak of covid in a discord server with equally bored
    students, I had the idea to create an interactive discord bot. As time
    went on this bot grew in complexity and demands.
    Well executed:
        -Creation of a fun discord bot with features such as auto generated
         word games to earn currency, math puzzles, and currency drops.
        -By testing this bot in a server full of CS students, I was able
         to learn by avoiding many accidental vulerabilities, and I got to
         see how an end user might try and break something like this

    Missed value:
        -Due to lacking knowledge of the eventual scope of this project,
         A robust databasing system was never implemented. Instead it relied
         heavily on json parsing libraries, and had little redundancy
        -The rapidly evolving state of this bot lead to a generally 
         un-functionalized program, which could use some breaking up

    Lessons Learned:
        -If you'll be storing data, go with a robust DB from the beginning
        -Especially when interacting with large services such as discord,
         it is important to have fallback mechanisms and completion checks
        -Planning for future development requires limiting your design ideas
         in the beginning

    Notes:
        This was a great fun hobby project I'd love to continue working on, 
        however I don't use discord much these days. Instead i'll look to 
        other bots to make
```
### Arcade Dungeon Crawler (2020)
```yaml
    Context: 
    https://github.com/csjoey/Dungeon_game_client
    For my first college computer science class I had the oppurtunity thanks
    to an amazing teacher, to make a game as a final project. I ended up 
    working with a classmate of mine who had a similar programming backgroung
    before the class started, and though mistakes were made, I learned alot
    Well executed:
        -Proceedural generation of a dungeon crawler using the Arcade library
         for python. This used a sha-256 based seed to compute general room
         layout and enemies.
        -Worked together successfully with my teammate, and gained valuable
         experience in co-programming and mutually designing software

    Missed value:
        -A big minus on this one due to my inexperience in python at the time,
         I ended up completely misusing the idea of classes in python. This is
         somewhat embarrasing looking back, but I'm proud to be able to see my
         mistakes now, and hey, at least I had the right idea
        -As part of the challenge of mutual design between ametuers, some of 
         the code for screen drawing and hit registration is uglier than i'd 
         like. A lot uglier; but not bad for two college freshmen since it
         does work.

    Lessons Learned:
        -Drawing out functionality of complex system helps communication
        -Co-programming is a valuabe tool for fast productivity in teams
        -When designing software, looking to open source analogous projects
         can be a valuable source for a community that has refined best 
         practices for a particlar language.

    Notes:
        I was very proud at the time that I was a freshman that this got done,
        and my partner was very enjoyable to work with. Looking back on this
        I see it as a reminder to always search for ways to be better, I hope
        I look back on my work I do now the way I look at this project
```
