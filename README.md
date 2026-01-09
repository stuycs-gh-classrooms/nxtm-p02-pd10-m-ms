[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/jiVqpuMN)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=22153584)
# NeXtCS Final Project
### Name 0: NABIHA ISLAM
### Name 1: MAISHA ALAM
---

### Project Description
We are planning to do an m&m styled flappy bird game that spans of three levels. However, instead of the "camera" moving with the bird as it flies further, we will just display the entire level.
inspiration: https://flappyplay.com/

### Skill Usage
We will be using:
- vectors (control bird movement)
- 2d array (will store obstacle position)
- 1d array ()
- boolean values (determines status of if the game is playing or not)
- loops (game status)

### Controls
How will your program be controlled? List all keyboard commands and mouse interactions.

Keyboard Commands:
- SPACE: jump
- LEFT ARROW KEY: move left
- RIGHT ARROW KEY: move right

Mouse Control:
- Mouse movement: N/A
- Mouse pressed: pause


### Classes
What classes will you be creating for this project? Include the instance variables and methods that you believe you will need. You will be required to create at least 2 different classes. If you are going to use classes similar to those we've made for previous assignments, you will have to add new features to them.

Class 1: Bird
- instance variables: boolean hit, int Bx, int By (bird position)
- methods: BirdCollision(), movement(), KeyPressed();

Class 2: Level
- instance variables: boolean playing, int Coins, int Obstacles
- methods: points(); obstacles(); 
