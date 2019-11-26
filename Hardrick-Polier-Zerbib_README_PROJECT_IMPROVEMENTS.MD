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
An undeterminate number of users input some controls.
After a few seconds, all the inputs are processed and the majority result is executed.  

We can see doing this with an input window next to the main window.
Users are connected, and will be simulated by a script maybe, and input their command.
After a few seconds, basically one in most cases, the game will process all the data and analyse it.
The most populare input wil win and the command will be executed accordingly.

One example of this implementation is [`Twitch plays pokemon`](https://www.youtube.com/watch?v=5Ec8zMxPVzk).

## Second Improvement description

We want to implement some gameplay powerups (bonus and malus): 

- Increase the frequency of the ship shooting.
- Stop all the asteroids for four seconds.
- Stop the ship for two second.
- Kill all the asteroids on the screen.
- Walls are lava
- Invert all the inputs
- etc.

This list is not exhaustive, and therefore, all the powerups above will not be implemented and some others might be.

