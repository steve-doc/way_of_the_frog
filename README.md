# Way of the Frog Memory Game

Follow the order that the frogs are played.  When you get it right your score acrues and the sequence gets longer.  Keep going until you make a mistake and try to beat your high score.

Link to [Live site](https://steve-doc.github.io/way_of_the_frog/)

## Index - Table of Contents

- [Design](#design)
    - [Wireframes](#wireframes)
    - [Font and Colours](#font-and-colour-choices)

- [Features](#features)
    - [Existing Features](#existing-features)
    - [Future Features](#possible-future-features)

- [UX](#ux)
    - [Site Goals](#site-goals)
    - [User Stories](#user-stories)

- [Testing](#testing)
    - [Validator Testing](#validator-testing)
    - [Browser Testing](#browser-testing)
    - [Manual Testing](#manual-testing)
    - [Testing User Stories](#testing-user-stories)
    - [Fixed Bugs](#fixed-bugs)
    - [Unfixed Bugs](#unfixed-bugs)

- [Deployment](#deployment)

- [Credits](#credits)
    - [Media](#media)
    - [Code](#code)
    - [Content](#content)

## Design



1. Strategy
Build a fun and challenging memory game that will engage the player.  The game theme will be a lilly pond with different coloured frogs on it.    
2. Scope
The frogs will ribbet in a random order and the player will have to play back the same order by clicking on the frogs.  Each level will last for a set amount of time, possibly 30 secs. 
 The game will get harder by the addition of more frogs as the levels progress. The player will have 3 lives which will decrement as player makes mistake, when they run out of lives the game will be over.  Possibly reset the player lives at the start of each level.  There will also be a scoring system that will increase based on the length of the sequence that the player succefully remembers.  When the game is over the player's score will be added to the high score table.
3. Structure
4. Skeleton
5. Surface

Credit
Pond background image - https://www.vecteezy.com/vector-art/521836-a-pond-with-many-plants 
frog sounds - https://quicksounds.com/search/filter/tracks/frog and edited with Vector 2 Exress

bugs

1. Intermittent on click audio bug not playing audio
2. When playing audio sequence if there are repeats of the same audio it will only play the audio once.
3. Score incrementing by multiples after first game.  Event listeners getting added again.