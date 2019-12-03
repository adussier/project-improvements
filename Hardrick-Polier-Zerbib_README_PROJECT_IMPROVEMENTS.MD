# TWEB Project : Asteroïd Game Improvements


## Membres du groupe

- Baptiste Hardrick
- Florian Polier
- Jeremy Zerbib


## Introduction

Those two features are independent but can be combined.
We want to give the opportunity for a user to access a *normal* game with all the powerups, only the multi-user polling session or both.  

This strategy is implemented in order to test more easily all the phases and the later compatibility with some plugins.

## First Improvement description 

Multi-user control polling : 
In real time, multiple users can vote on input for the ship. 
Each second or so, all the inputs are processed and the most requested one is executed. 

We want to implement it as an input window on the side of the page.
For the demo, we can ask the classroom to play it OR we can simulate inputs when some scripting.

One example of this implementation is [`Twitch plays pokemon`](https://fr.wikipedia.org/wiki/Twitch_Plays_Pok%C3%A9mon).
This concept was very popular and has been watched (played) by more than 15 millions player across the world.

Such an implementation can be used to demonstrate "The Wisdom of Crowds" thesis. 

## Second Improvement description

We want to implement some gameplay powerups (bonus and malus). 
These are some examples that we can change if the game feedback requires it: 

- Increase the frequency of the ship shooting.
- Stop all the asteroids for four seconds.
- Wipe all the asteroids on the screen.
- Walls are lava
- Invert all the inputs for a given time
- New weapons
- etc


