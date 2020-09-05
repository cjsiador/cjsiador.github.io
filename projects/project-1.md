---
layout: project
type: project
image: images/Project1-3.PNG
title: Pokemon GO Java
permalink: projects/pokemon-go-java
# All dates must be YYYY-MM-DD format!
date: 2019-12-07
labels:
  - Java
  - Game
  - Group Project
  
summary: My team developed a simple Pokemon GO game with Java's GUI function that allows either capture or escape from nine random Pokemon,
---


<div class="ui small rounded images">
  <img class="ui image" src="../images/Project1-2.PNG">
  <img class="ui image" src="../images/Project1.PNG">
  <img class="ui image" src="../images/Project1-3.PNG">
  
</div>


  Pokemon GO Java is a game to demonstrate Java GUI, polymorphism (Pokemon’s Evolution), and a game feature that allows players a chance to either catch a random generated Pokemon or the Pokemon will escape. Java GUI was used to display the game’s function. Whenever the player clicks the hunt button, a notification window pops up with a random Pokemon. Players have an option of either catch it or run away. However, trying to catch it isn’t guaranteed and it’ll escape. The polymorphism allows the second and third evolution Pokemon (for example, Charmander’s 2nd evolution is Charmeleon and Charzard is the 3rd evolution) to inherit attributes and methods down to the first evolution. 	

  For this program, I was responsible for designing the GUI and Charmander’s evolution class. I started programming the parent class (Charmander) with stats based on Pokemon GO wiki stats. While designing the GUI, I program a function where the player clicks the “hunt” button, a random Pokemon would appear in a popup window. This was coded using a random generator between 1 - 9 and each Pokemon are designated by their Pokedex Number through a switch case in a addActionListener() function. If the Pokemon were to be caught, it’ll be stored in an array and will display its stats, type, and the name of that Pokemon. 

  Throughout this project, I learned more about working with a group. I found that it’s important that people should be given roles and responsibilities so that way it’ll become organized and straightforward. Additionally, I was able to understand other coding styles from my peers and because of this, it’ll help me implement different coding styles for future projects. Lastly, I learned more about how hierarchy and polymorphism work in Java and new fundamentals for writing Java GUI.


You can learn more at the [GitHub Repositories Website](https://github.com/cjsiador/final-project-pokemon-gui-f19-final-project-group-5-developChristian).



