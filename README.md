# Pixel Atlas

A neon geography game. Play at https://benrhamen.github.io/pixel-atlas/.

- World and USA states: Easy asks by name; Medium asks which country/state has a given capital.
- Capitals: find the capital city of a country, with a flag and city answers.
- Multiple choice, click the map, flag questions and a session-only visited-country map.
- Three lives and ten questions per round. Correct answers show a fact card until you choose Next.
- Actual flag SVGs, ten-color neighbor-safe maps, continent filters, zoom buttons, wheel zoom and pointer pan/pinch.
- Original collectible pixel sprites and a customizable explorer. Clickable skin, hair, clothing, shape, color and accessory choices; Random character picks features and a home country. Accessories unlock every two correct answers.
- Pixel Atlas's own device-local top-ten leaderboard. No shared score service, transmitted player data or connection to Neon Dragon. Current name, home, character and visited map are session-only.

## Data and licences

World boundaries: world-atlas/Natural Earth; USA states: us-atlas, US Census public-domain boundaries. Maps simplify geography and omit tiny countries. The UK is currently one country path. The visited total is the 172 playable entries, not a claim about sovereign-country counts.

Flags: flag-icons 7.5.0 (MIT), embedded as compressed SVGs. Afghanistan flag questions are excluded because of flag ambiguity.

Population: World Bank, 2024 estimates, https://data.worldbank.org/indicator/SP.POP.TOTL. Currency names: SIX ISO 4217 list, https://www.six-group.com/en/products-services/financial-information/data-standards.html. Missing population is omitted; selected fun facts carry individual source links.

Pixel characters and sprites are original game artwork. The character shapes and accessories also appear in Future Park; no account progress is carried over.

## Browser notes

Single self-contained `index.html`; no build step or score server. Flag decompression uses embedded fflate 0.8.2 (MIT), with no DecompressionStream dependency. Device storage is specific to this site's origin and can be cleared. Zoom buttons and continent controls are available; touch pinch is not verified on a physical iPad. Hard (currency/anthem), Space and UK constituent-country boundaries are a future sourced stage, not current features.

fflate copyright (c) 2023 Arjun Barrett, MIT licence embedded in index.html.
