<h1> Misc - Gameboy Game</h1>

**Table of Contents**
- [Description](#description)
- [Solution](#solution)
  - [Used tools](#used-tools)

## Description
Who needs a defcon badge when you've got an emulator? Dodge some cones, have some fun.<br>
Translated to Japanese:<br>
エミュレーターがあればDEFCONバッジはいらないですよね？コーンを避けて、楽しみましょう。

## Solution
In this challenge, we are supposed to clear the game given by the organizer. 
The rule of the game are:
* Move towards the battery to score a point
* Cone moves randomly and reset the score if hit by it
* Score exactly 32767 to complete the level
<br>
![game_overview](https://github.com/apuitopui/writeup-automotive-ctf-2024/blob/main/Misc-Gameboy%20Game/img/game.gif)

### Used tools
* [mGBA](https://mgba.io/) : Gameboy Advanced emulator 
* [scanmem](https://github.com/scanmem/scanmem) : Memory scanner for Linux
