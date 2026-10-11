# Willow Flats

A city-building game in your browser. Lay out streets, run power, water and waste out to the land,
zone it for homes, shops and factories, and grow a settlement into a metropolis while keeping the
treasury in the black and your residents happy. Plain HTML, CSS and JavaScript in a single file,
no build step.

## Play

**[▶ Play in your browser](https://cubicobelus.github.io/willow-flats/city_planner.html)**: nothing to download or install.
Press **Walk me through it** on the intro screen (or the **Tutorial** button any time) for a short guided start.

To run it offline, download `city_planner.html` and open it. (Fonts load from Google Fonts, so
it looks best with an internet connection.)

## How it works

You don't place houses. You build the streets and utilities, mark land as residential, commercial
or industrial, and people arrive along the highway and build on any lot they can reach. Homes need
jobs, shops need customers and factories need both, so growth only comes from keeping the three in
balance. Land value decides how tall a lot grows: parks lift it, while smog, landfills, gridlock and
crime pull it down.

## Features

- **Zones driven by live demand:** homes, shops and factories, with demand meters that show what the city wants
- **Utilities and services:** coal and wind power, water towers and aquifers, landfills and sanitation, plus fire, police, clinics, schools and bus stops, each with a coverage radius
- **Roads that matter:** streets, avenues and boulevards, with traffic, gridlock and bridges over water
- **Map overlays:** services (per type), land value, traffic, crime and pollution
- **Four map types:** river valley, coastal, lakes and mountains. Click the map tag at the top to copy a link that opens the same map and difficulty for anyone
- **Difficulty:** four presets and sliders for starting funds, tax revenue, running costs, land prices, hazards and growth speed
- **Money:** tax rates that unlock as you grow (one rate at 500 residents, separate rates for homes, shops and factories at 1,000), bonds, land parcels to buy, and a bulldoze tool that refunds part of the cost
- **Policies:** from 800 residents, switch on city-wide rules (recycling, clean air, free buses, a safety campaign, a tourism campaign). Each costs money every month and has a trade-off, and you get one slot at first, two from 2,000 residents and three from 4,000
- **Goals:** a charter to complete, ten commendations that earn permanent discounts, and a score when you finish
- **Your city:** give it a name, and save into two slots of your own plus an automatic one, all kept in your browser, with Continue and New game on the start screen
- **Quality of life:** undo, a minimap, a history graph, day and night, sound effects, zoom and pan, a fullscreen button, and short hover tips

## Controls

| Action | Keys |
|---|---|
| Pick a tool | the letter or number on its button (R street, 1 homes, 2 shops, 3 factories, X bulldoze, ...) |
| Play / pause | Space |
| Undo | Ctrl+Z |
| Show all the keys | ? |
| Pan | arrow keys or middle-drag |
| Zoom | scroll wheel |
| Clear the current tool | Esc |

## Privacy

Everything runs in your browser. Saves and your best score live in your browser's local storage and
nothing is sent anywhere. The only outside request is the font from Google Fonts.

## License

MIT
