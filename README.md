# Pixel Atlas

A neon geography and Space learning game. Play at https://benrhamen.github.io/pixel-atlas/.

- Geography: Easy by capital, Medium by flag, Hard by currency plus anthem title. Hard covers 156 places with clear anthem/currency pairs; ambiguous and territorial cases are omitted. No lyrics or audio.
- Answer by multiple choice, type it yourself, or click the country/state map. Capitals mode asks for the capital city. Map mode uses capital clues.
- UK has four playable paths: England, Scotland, Wales and Northern Ireland. Northern Ireland uses a neutral label and is excluded from flag questions pending a flag choice. Afghanistan is also excluded from flag questions.
- 175 playable places, including territories: not a count of sovereign countries. 50 USA states. All places have a sourced short geography/language fact. Richer trivia and landmarks cover 174/175; Western Sahara has no verified landmark in this release.
- Three lives; 10/20/30/50/100 questions per geography level. Three-second feedback, then automatic advance. Changing level length starts a fresh level.
- Personal Countries I have visited tab beside Avatar, independent of quiz scores. Visits persist only in this browser on the standalone site; if storage is blocked, the list is session-only. No sharing/upload. Public File anonymous visits are session-only; signed-in local state support is separate.
- Original category-symbol landmark sprites, not exact portraits. Unlock landmark names, locations and source links. Ten-color maps, continent filters, zoom buttons, wheel zoom and pointer pan/pinch. Asia's yellow and Europe's blue rings are requested design colors, not an official Olympic continent mapping.
- One Avatar panel: name, home, preview, skin, hair, clothing, shape, color and accessories. Random character picks features and a home. Accessories unlock every two correct geography answers. Avatar session only.
- Device-local top-ten geography leaderboard. No shared score service or connection to Neon Dragon.
- Space starter: eight planets in Sun-outward order plus Orion, Cassiopeia, Crux/Southern Cross and Big Dipper. Big Dipper is identified as an asterism in Ursa Major, not a constellation. Multiple-choice/manual answers, level-length controls, three-second feedback and restart. Space scoring is separate, with no lives or geography collectibles. Drawings are original learning schematics, not to scale, a sky chart or all 88 constellations.

## Data and licences

World boundaries: world-atlas/Natural Earth; UK constituent paths from simplified Natural Earth 10m map subunits. Natural Earth is public domain: https://www.naturalearthdata.com/about/terms-of-use/ . USA states: us-atlas, US Census public-domain boundaries. Maps simplify geography, omit tiny countries and are not statements of political recognition.

Flags: flag-icons 7.5.0 (MIT), embedded compressed SVGs. https://github.com/lipis/flag-icons . Flag ambiguity exclusions noted above.

Short geography/language facts adapted from mledoze/countries (ODbL 1.0), https://github.com/mledoze/countries/blob/master/LICENSE . Derived data/attribution in the source panel. Richer UNESCO fact paraphrases adapted from UNESCO World Heritage Centre property descriptions under CC BY-SA 3.0 IGO: https://whc.unesco.org/en/disclaimer/ . Individual source links accompany facts. Kuwait Towers uses Wikipedia under CC BY-SA 4.0. Original category-symbol artwork is separate from the source texts.

Anthem titles: Wikipedia individual articles (CC BY-SA 4.0), titles only. Currency names/codes: SIX ISO 4217 list, https://www.six-group.com/en/products-services/financial-information/data-standards.html . Earlier map population/currency fields are not a newly audited country dataset. Kazakhstan capital is Astana; North Macedonia display retains aliases for older names.

Space sources: https://science.nasa.gov/solar-system/planets/ ; https://spaceplace.nasa.gov/constellations/ ; https://apod.nasa.gov/apod/ap160318.html ; https://www.nasa.gov/image-article/dark-reflections-southern-cross/ ; https://science.nasa.gov/solar-system/what-are-asterisms/ . Facts checked October 7, 2026. No NASA photographs copied.

## Browser notes

Single self-contained `index.html`; no build step or score server. Flag decompression uses embedded fflate 0.8.2 (MIT, copyright 2023 Arjun Barrett); no DecompressionStream or optional-chaining dependency. Licences are embedded. Device storage is specific to this origin and can be cleared. Tested in mobile-sized cloud Chrome, not a physical iPad or Ben's actual workstation. Zoom buttons and continent controls remain available.
