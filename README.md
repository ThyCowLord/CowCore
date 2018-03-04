# CowCore

## What is it?
It's basically a small, lightweight, and versatile way to get your text-based RPG on the road. 

## Setup

> git clone https://git.io/vAHET

> cd CowCore

> sudo python3 setup.py install

## Usage

### Required after each sequence


### Recommended after each sequence
To check HP, Level, and all that, after each sequence run:

> cowcore.all()

### Changing player stats:

> cowcore.player.[stat] = [newstat]

Available stats: hp, xp, lv, dmg, arm, money

### Animated text

> cowcore.delay_print("Hello world!")

### Saving

> cowcore.save()

This is auto-activated by the all() sequence.

### Loading

> cowcore.load()

### Dying

> cowcore.die()

This is auto-activated by the all() sequence if the HP is 0 or below.

### Leveling up
Normally, you need 10 XP to level up. To bypass that (e.g Cheat Codes) you can do

> cowcore.player.lv = [level]





