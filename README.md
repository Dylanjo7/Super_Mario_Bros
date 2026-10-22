# Super Mario Bros (MakeCode Arcade)

A three-world Super Mario Bros remake built in [Microsoft MakeCode Arcade](https://arcade.makecode.com/), with hand-drawn pixel sprites, power-ups and sound effects.

**Play it in your browser:** https://dylanjo7.github.io/super_mario_bros/

## Gameplay

- **Three worlds:** World 1, World 2 and an underground World 3. Reach the exit tile of each world to move on, then reach the goal in World 3 to win.
- **Goombas:** jump on them to stomp them. Touch one from the side and you lose.
- **Power-up block:** hit it from below to grow big. Big Mario survives one hit from a Goomba and shrinks back down.
- **Coins:** collect them for points. Your best score is saved as the high score.
- **Sprites:** separate animations for walking left and right, jumping and crouching.

## Controls

| Button | Action |
| --- | --- |
| ← / → | Move |
| A | Jump |
| ↓ | Crouch |
| B | Stand / face forward |

On a keyboard: arrow keys or WASD to move, **Space** or **Z** for A, **X** or **Enter** for B.

## Built with

- Microsoft MakeCode Arcade (blocks + TypeScript)
- Custom tilemaps for each world
- GitHub Pages for the playable web build

## Use as Extension

This repository can be added as an **extension** in MakeCode.

* open [https://arcade.makecode.com/](https://arcade.makecode.com/)
* click on **New Project**
* click on **Extensions** under the gearwheel menu
* search for **https://github.com/dylanjo7/super_mario_bros** and import

## Edit this project ![Build status badge](https://github.com/dylanjo7/super_mario_bros/workflows/MakeCode/badge.svg)

To edit this repository in MakeCode.

* open [https://arcade.makecode.com/](https://arcade.makecode.com/)
* click on **Import** then click on **Import URL**
* paste **https://github.com/dylanjo7/super_mario_bros** and click import

## Blocks preview

This image shows the blocks code from the last commit in master.
This image may take a few minutes to refresh.

![A rendered view of the blocks](https://github.com/dylanjo7/super_mario_bros/raw/master/.github/makecode/blocks.png)

#### Metadata (used for search, rendering)

* for PXT/arcade
<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>
