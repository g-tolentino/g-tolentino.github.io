---
layout: project
type: project
image: images/tama-icon.png
title: Tamagotchi
permalink: projects/tamagotchi
# All dates must be YYYY-MM-DD format!
date: 2017-04-15
labels:
  - C++
  - GitHub
summary: A text adventure game I developed for ICS 313.
---

<img class="ui image" src="{{ site.baseurl }}/images/cotton-header.png">

When I was young, I remember Tamagotchi being the hottest toy around. I never owned one, but my cousins did, so I would “tamagotchi sit” theirs. As soon as I found out that one of our final projects for EE205 was to recreate Tamagotchi, I started to brainstorm how to implement what we learned in class to the project. 

The first thing we did was to figure out the different types of actions you can do with the Tamagotchi. The user could feed, play a game, clean, give medicine, control the lights, and check the Tamagotchi’s health and information. For our feed function, we ask the user to choose between a meal or a snack. The game we programmed for the Tamagotchi was a guessing game. The user would guess which way the Tamagotchi was facing, either left or right. If the user won three or more times, it would increase the Tamagotchi’s happiness. The clean function would get rid of the poop that the Tamagotchi created. If the user does not clean it up in time, the Tamagotchi gets sick. To heal the Tamagotchi, the medicine function would determine how much medicines or injections the user would need to give to the Tamagotchi to make it all better. These actions turned out to be functions in our main Tamagotchi class. 

The next thing we did was create classes that were inherited from our main class. For the feed function, we decided that each Tamagotchi age group should have their own feed function. So, each age group would have a different meal and snack that the user could choose from. These meals and snacks would also affect the weight of the tamagotchi and maybe increase its happiness. We also added visuals to our Tamagotchi game. There is a main menu and each age group has a different Tamagotchi character. 

Although we have the main functions completed, we still need to test our random events function and  complete the main driver for our Tamagotchi game. Based on the age group, the random events function controls the Tamagotchi’s health levels,  how it feels, and what it does. For example, a baby Tamagotchi would eat, poop, and sleep more compared to an adult Tamagotchi. For the main driver, I am currently trying to figure out how to run the random events function while the user is making their decision on what to do with the Tamagotchi. We also need to go back into our code and double check that everything is working correctly and getting rid of any bugs. For example, the user should not be able to feed the Tamagotchi when it's sleeping. 

Overall, there is still many features that we still need to finish and test, but once we get them working, our Tamagotchi game will be ready for presentation. The one thing I like about this project is that each group is able to add their own creativity and features to their Tamagotchi game. It will be interesting to see what each group created. This also gives other groups ideas on new features they can add to their Tamagotchi games.


Source: <a href="https://github.com/jogarces/ics-313-text-game"><i class="large github icon "></i>jogarces/ics-313-text-game</a>

