# Fernweh 1.4 · Roadtrip 100

Version 1.4 adds rounded country-road bends with 28-metre radii, three mandatory side routes and three signed diversions around road closures. Fuel signs are moved clear of the roadway; barriers leave access gaps. Navigation defaults to the final destination instead of requesting a turn into every next stop.

Seven discovery locations add short on-foot activities: an old mill, farm, lookout tower, quarry, lakeside village, castle ruin and creekside picnic camp. **J** opens the shared journal and selects destinations; **K** reads the information board and interacts at the activity marker. Each new shared stamp gives every traveller €6.50. At the fishing dock, cast with K, wait for the bite, then press K within three seconds. Some buildings and both elevated viewpoints are accessible.

Fields, farms, rocks and waterside scenery extend the surroundings. The standard seed has 42 named stops. Closures appear red in the atlas. All players need **1.4**; previous versions are incompatible. The four cities, two cloverleaf interchanges and sound layers from 1.2 remain.

These are fixed road incidents and simple activities, not a dynamic mission simulation. Water is shallow scenery without swimming. Progress lasts for the current trip.

# Fernweh · Landstraße 100

An early Windows roadtrip prototype made with Unity. Drive a procedural 100-kilometre route in an old pickup, alone or with two friends, stopping at fuel stations, rest areas and villages.

[Deutsch](README.md) · [Asset credits](CREDITS.md)

## Getting started

Extract the entire download and launch `Fernweh.exe`. Keep the data folder and bundled Unity files beside the application. Choose a name and character, then select **Allein aufbrechen** for solo play or create a room. The current in-game interface is German.

## Playing together

- **Internet:** The host selects **Raum erstellen** and shares the room code. Friends enter it and select **Beitreten**. This experimental mode uses Unity Relay and requires an internet connection and an available Relay service.
- **LAN:** On the same local network, the host selects **LAN Host**. Friends enter the host computer's local IP address and select **LAN Beitreten**. Default port: UDP 7777. `127.0.0.1` only works on the same computer.
- A room has **three places: the host drives and two friends ride as passengers**. Everyone can get out when the pickup is stopped.
- **F1** opens the room menu. The shared session ends when the host leaves. Host migration and built-in voice chat are not included.

## Controls

| Key | Action |
|---|---|
| WASD / arrows | Drive; S brakes, then reverses |
| Mouse / C | Look around / centre the driver's view |
| Space | Handbrake; jump while walking |
| F | Get out when stopped / enter beside the pickup |
| WASD / Shift | Walk / run |
| E | Talk or shop; hold near a fuel pump to refuel |
| Q / G | Pick up or use an item / put it down |
| P | Open your bag |
| I / B / L | Engine / cabin light / headlights or flashlight |
| H | Pick up an available hitchhiker or drop them at their destination |
| T / V | Mark the next stop / sound the horn |
| Tab / M | Expand the navigation map / open the full atlas |
| J / K | Shared travel journal / interact at discovery boards and activities |
| Z / X | Left / right indicator |
| N | Cycle through time-of-day previews |
| R | Roadside recovery: return the pickup to the road |
| Esc / F1 | Pause or close a dialogue / room and main menu |
| F8 | Host: skip the current crew contract without a reward |

## Using provisions together

Walk to the counter of an open shop, press **E**, and buy an item. Each traveller starts with a separate €75 wallet. Purchases appear at the collection point. Look at the item and press **Q** once to hold it; press **Q** again to use or consume it. **G** puts it down, allowing another traveller to pick it up. You can hold one item at a time, with a room limit of 24 unconsumed items. **P** opens your bag, but physical items still need to be within reach. The driver must stop to handle items; passengers can use them while travelling.

## Six crew contracts

Shared tasks begin automatically when at least two people are in the room. Progress and rewards are synchronized. The host can press **F8** to skip a task without a reward.

| Contract shown in game | What to do |
|---|---|
| Kaffeepause zu zweit | Park. Two different travellers must each hold a purchased coffee for two seconds. Press Q to pick it up, but do not drink it yet. |
| Alle mal die Beine vertreten | Drive to the indicated stop. Everyone gets out and stays together there for three seconds. |
| Der Beifahrer weiß den Weg | A passenger marks the next stop with T. Travel there together and remain parked for two seconds. |
| Das schlechteste Hupkonzert | Park. Everyone presses V within the same eight-second window; anyone outside must stay within 18 metres of the pickup. |
| Der rollende Kiosk | Carry three different types from coffee, water, sandwiches and nuts, either in people's hands or in the pickup bed. Drive more than 100 metres to the indicated next stop and park. |
| Fahrer hat Pause | A passenger gets out at a fuel station and holds E to add five litres. The task is skipped if the tank is already too full. |

Everyone receives a reward on completion. Repeating the same contract at the same location does not pay again within that room.

## Current content

42 named stops, walk-in fuel-station shops, provisions, short text conversations, four traveller models, traffic and hitchhikers. Plains, wooded foothills and mountain passes connect along the route, including two drivable tunnels. Lighting and roadside activity change through the day and night.

Hessen, Bayern and Thüringen label chapters of a **fictional** route. The villages and road layout do not recreate a real map of Germany.

## Prototype status

This is a work in progress. More realistic lighting, photographic textures and detailed characters sit alongside procedural vehicles, buildings and terrain. It is not a finished photorealistic production. Multiplayer, physics and visuals may still have bugs.

Progress belongs to the current session; a complete save-and-resume system is not included. Walking is limited to roughly 210 metres from the pickup. Buses are background traffic rather than a boarding service. Dialogue is not voiced, the radio is decorative, and the temperature display is atmospheric.

For bug reports, include the location or kilometre, play mode and a short description. This build writes Unity's log to `%USERPROFILE%\AppData\LocalLow\Luis Studios\Fernweh\Player.log`.

See [CREDITS.md](CREDITS.md) and [THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md) for asset sources and bundled notices.
