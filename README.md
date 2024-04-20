# Angry Birds - CS50 Version

Welcome to my Angry Birds game remake, inspired by the iconic mobile game developed by Rovio Entertainment.

![angry](https://github.com/najlae01/angry-birds/assets/88176530/bc5b2e60-ed53-4e99-8fa5-3b594e28f727)


## Introduction

Angry Birds is a physics-based puzzle game where players use a slingshot to launch birds at structures containing pigs. The goal is to eliminate all the pigs on the playing field using as few birds as possible.

## Features

- Classic Angry Birds gameplay experience with a slingshot mechanism and destructible structures
- Splitting Aliens feature: launching an Alien splits it into three Aliens, each behaving like the original Alien
- Implementation of collision detection to trigger splitting only before the launched Alien hits any obstacles
- Launch marker reset only after all flung Aliens slow down to nearly still, ensuring smooth gameplay transition
- Realistic physics simulation for the trajectory and behavior of flung Aliens

## Controls

- **Mouse Click and Drag**: Aim and launch the slingshot

## Installation

To run the game, ensure you have Love2D framework installed on your system. You can download Love2D from [the official website](https://love2d.org/).

Clone this repository to your local machine:

```
git clone https://github.com/najlae01/angry-birds
```

## Usage

Navigate to the project directory and run the game with Love2D:

```
cd angry-birds
```
```
love .
```

## Credits

Developed with Love2D (Lua) as part of the CS50 Introduction to Game Development course.
