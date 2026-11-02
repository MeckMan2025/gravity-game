# Gravity Flip

A one-button neon runner. Your cube races along the floor; press Space (or tap the screen) to flip gravity and fall to the ceiling, press again to fall back. Dodge spikes and walls, grab coins for +50, and see how far you get as the speed climbs.

Play at [gravity-game.meckman.org](https://gravity-game.meckman.org).

## Controls

- **Space** (or **tap** anywhere on a phone or tablet): start, flip gravity, retry

That's the whole list. On a phone, turn it sideways for the biggest view; on iPhone, turn off silent mode to hear the sound.

## Tech

One HTML file: canvas graphics and Web Audio sound effects. The world is a fixed size scaled to fit the screen, so a phone sees as much track ahead as a laptop. The game runs at a fixed 60 Hz, so it plays at the same speed on 60, 120 and 240 Hz screens. Your best score is saved in the browser. No frameworks, no assets, no build step.

## Deploy

Static site served as a Cloudflare Worker assets bundle.

```
wrangler deploy
```
