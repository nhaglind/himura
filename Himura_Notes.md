## Himura (JavaScript/HTML5 Game)##

This game is being developed to work on utilizing and understand the DOM and building SVGs while also getting a deeper understanding of vanilla JS and programming patterns.

------

**Project Description**: You're flying around like some sort of crounching tiger hidden dragon type character, but you're a samurai. You progress through levels (randomly generated but with increasing difficulty). As you complete levels, you earn money and experience (scaling). While you gain levels this allows you to unlock certain skills (you must make a choice at different intervals, HotS/DotA style.  Example of advanced skills are "Can I slow time down or can I become invulnerable for a set period of time?" With money you buy equipment (your sword can cut through an n value of pipes before becoming dull).  The more you upgrade your blade the more pipes you can cut down or the more strong pipes you can cut down.



**Problems**:

- Controls
  - Keycodes
    - http://keycode.info/
  - up arrow (keycode 38) or spacebar (keycode 32)
  - mouse clicks for menu choices
  - q w e r d f (league style hotkeys for abilitys?) or clickable ability?
    - Need to consider ease of use while bouncing to use an ability or skill

- Put a sprite on the screen that takes up a specific amount of space and location. Should be reponsive. Calculate window width and apply a query function.

  - Could make the playing field a large array and append the array to increase size?

- Put a background that moves. Could also be static, change after x amount of levels. Later complexity could be weather effects that decrease speed or adjust the "up" values.

- Randomly generate "obstacles" and these would determine width between pipes for difficulty and frequency of appearence.

  - Also type of "obstacle" some can be cut with sword, some cannot. Some are rare and yield some benefit. Apply a floor to random().

- Tracking the 'Himura' object.

  - Experience value
  - Level value
  - Money value
  - Skills available for use
    - Done through switch case?
  - Movement values
    - Speed (intialize at a base value)
    - Bounce  (intialize at a base value)
  - Equipment
    - Append array in object with identifier.
  - Death
    - Lives

- Gameover instances (what causes a game over or is it a level reset or is it a reduction in lives? Likel you lose a life but continue at the beginning of the level)

  ​

- Saving? Might be difficult with pure js, but could pass value into some database that is simply storing all the different object parameters and assigning it an ID that can be loaded into a game. (Replacing of values of objects)





------

**Assets**:

- Sprites
  - Create or purchase (purchase might save a lot of time and make it look nice)
  - Initially start with using simple svg block(s) then later add in art
- Backgrounds
- Music (for each "group of levels")
- Sound effects
  - Level up
  - Completion of level
  - Death
  - Gameover
  - Movement
  - Crash
  - Swipe
  - Abilities


- Fonts
