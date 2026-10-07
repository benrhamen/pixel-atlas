# Pixel Atlas

A neon retro geography quiz in a single static `index.html` (no build, no dependencies).

Play: https://benrhamen.github.io/pixel-atlas/

## Modes
- **World**: multiple choice (country from capital and continent, capital, flags) or click the country on the map ("find X" or "country whose capital is X"). Region buttons filter and zoom.
- **USA states**: multiple choice (state from capital, capital from state) or click the state on a US map.
- 3 lives. Answer 10 questions to clear a level.
- A short fun fact appears after a correct answer for some countries and all 50 states.
- 35 original pixel-art sprites (monuments, foods, animals) unlock on the world map when you answer their country correctly.

## Limits
- Small islands and micro-states are hard to tap (110m map).
- 172 countries are quizzed. Kosovo, Somaliland and Northern Cyprus are drawn but not quizzed. Antarctica is excluded.
- Capitals come from a public dataset and are not individually hand-checked. Some are disputed.
- Fun facts are written from well-known facts and are not individually source-checked.
- Flags are bundled SVG images, not emoji. Afghanistan is omitted from flag questions because its flag usage is contested. Syria uses the green-white-black flag with three red stars. Best score is not saved. Modern browsers with DecompressionStream support are required.

## Data credits
- World map: Natural Earth 110m via [world-atlas](https://github.com/topojson/world-atlas) (Natural Earth is public domain, world-atlas is ISC).
- Country data: [datasets/country-codes](https://github.com/datasets/country-codes) (PDDL).
- USA map: [us-atlas](https://github.com/topojson/us-atlas) (US Census Bureau cartographic boundaries, public domain), Albers projection.
- US state capitals cross-checked against three public datasets.
- Pixel art: original.
- Flags: [flag-icons 7.5.0](https://github.com/lipis/flag-icons) by Panayiotis Lipiridis, MIT. Full licence is included in the HTML.
- Map: 10 colors, assigned by DSATUR graph coloring on the rendered boundary geometry. Point contacts and gaps under 0.15 map units count as touching. Zero same-color pairs across 315 world and 107 USA contacts. This is a simplified map, not a statement about disputed borders.
- New collectible pairings checked against Britannica. Their placement is decorative within the country, not an exact landmark coordinate.

## Run locally
Open `index.html` in a browser.

## Player and facts

Create a pixel explorer with a made-up name and skin tone. Name is kept only in memory in this browser session. No account, upload or tracking. Costumes are neutral city/mountain/trail/forest/rainforest/ocean/road-trip gear, selected by region.

Controls are ordered: World or USA, continent (World only), Multiple choice or Map, By name or By capital. Flags remains an extra World multiple-choice option. Clues is removed.

Every correct World answer shows a fact card, kept visible until Next question. Approximate population is from the [World Bank Population total](https://data.worldbank.org/indicator/SP.POP.TOTL), 2024 observations (downloaded 7 October 2026). Population is available for 169 of 172 quiz entries; missing values are omitted. Currency is cross-checked against the [SIX ISO 4217 current currency list](https://www.six-group.com/en/products-services/financial-information/data-standards.html), published 17 September 2026. Currency available for all quiz entries; Palestine is marked no universal currency per ISO. Additional source-linked fun facts appear for 15 countries. Other countries show only verified population/currency. Previous unsourced World fun facts were removed. The USA facts remain from the earlier build and were not re-audited here.

35 original collectible sprites, unlocked by answering the corresponding country correctly. Names/locations checked against Britannica. Decorative sprite positions are not exact landmark coordinates.

Home country is optional and shown as a small flag badge. Visited countries mode toggles selected countries in gold and shows count, percent of the 172 playable map entries, and continent coverage. These are not all sovereign countries: the simplified map includes dependencies and omits tiny countries. All selections are session-only. Maps support 50%-400% zoom, buttons, pinch or Ctrl+wheel, and native scroll/touch pan.
