# Pixel Atlas

A neon retro geography quiz in a single static `index.html` (no build, no dependencies).

Play: https://benrhamen.github.io/pixel-atlas/

## Modes
- **World**: multiple choice (country from capital and continent, capital, flags, progressive clues) or click the country on the map ("find X" or "country whose capital is X"). Region buttons filter and zoom.
- **USA states**: multiple choice (state from capital, capital from state) or click the state on a US map.
- 3 lives. Answer 10 questions to clear a level.
- A short fun fact appears after a correct answer for some countries and all 50 states.
- 18 original pixel-art sprites (monuments, foods, animals) unlock on the world map when you answer their country correctly.

## Limits
- Small islands and micro-states are hard to tap (110m map).
- 172 countries are quizzed. Kosovo, Somaliland and Northern Cyprus are drawn but not quizzed. Antarctica is excluded.
- Capitals come from a public dataset and are not individually hand-checked. Some are disputed.
- Fun facts are written from well-known facts and are not individually source-checked.
- Flag emoji look different per device. Best score is not saved.

## Data credits
- World map: Natural Earth 110m via [world-atlas](https://github.com/topojson/world-atlas) (Natural Earth is public domain, world-atlas is ISC).
- Country data: [datasets/country-codes](https://github.com/datasets/country-codes) (PDDL).
- USA map: [us-atlas](https://github.com/topojson/us-atlas) (US Census Bureau cartographic boundaries, public domain), Albers projection.
- US state capitals cross-checked against three public datasets.
- Pixel art: original.

## Run locally
Open `index.html` in a browser.
