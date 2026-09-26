# Fernweh 1.5 · Europe & Somewhere in Europe

A Windows roadtrip prototype by Luis Studios, made with Unity. Drive an old pickup, explore, and shop alone or with up to three players. [German guide and controls](README.md).

## Somewhere in Europe

Select the mode, host a room, and share its code. Each player starts at an unknown, separated location with their **own pickup**. No navigation, maps, location labels, or teammate markers. A compass shows the direction you are looking. Describe road signs and landmarks using your own voice chat; the game does not include voice communication.

Park all connected players' pickups within 35 metres of each other for four seconds to win. At least two players are required. Keep exploring or let the host select **F1 → Neue Suchrunde** while everyone is seated and stationary.

The original shared-pickup mode remains available: one host driver and two passengers. All players must use version 1.5. Online rooms use Unity Relay; LAN play is available. The host must stay connected. Host migration and persistent multiplayer saves are not included.

## Europe

80 places and 101 connections span Europe, islands, microstates, and selected transcontinental areas (51 country/territory codes, not a political definition of Europe). Press **M** outside search mode to choose a start and destination or random trip. Zoom and drag the map.

Distances come from OpenStreetMap/OSRM, retrieved September 26, 2026; reverse-direction distances are approximated. Vehicles remain life-sized but intercity travel is compressed. Road geometry follows generalized source-road bearings with widened bends. **The driving world is not a geographically exact reconstruction.** Most terrain, buildings, and urban streets are procedural.

Frankfurt-Nordend and Luxembourg-Gare use imported road geometry and building footprints; facades and heights are simplified. Dashed connections are fictional vehicle transfers with approximate straight-line distances, not measured roads or real-world services. Stop at a terminal and press **E**. No ferry simulation is included. Journeys range from about 3.8 to 157 game kilometres; search mode normally uses shorter routes without transfers.

New two-way signs, water towers, silos, and radio masts provide orientation. Windshield glare no longer creates an opaque sun hotspot. Day/night cycles, shops, physical items, and route-dependent exploration activities remain available.

![Europe map](docs/v15-europe.png)

## Download

Extract the entire ZIP and run **Fernweh.exe**. Keep its data directory and runtime files together. Pick a name and character, then host, enter a room code, or drive alone. This is a prototype with simplified scenery and mechanics.

Map data © [OpenStreetMap contributors](https://www.openstreetmap.org/copyright), [ODbL 1.0](https://opendatacommons.org/licenses/odbl/1-0/). Boundaries: [Natural Earth](https://www.naturalearthdata.com/about/terms-of-use/), public domain. The derived database is included as [data/Fernweh-Europe-ODbL.json](data/Fernweh-Europe-ODbL.json). Its license does not license the entire game. Other sources: [CREDITS.md](CREDITS.md), [THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md).
