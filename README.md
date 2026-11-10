# Pit Wall F1

**Live demo:** https://azziromulo.github.io/pit-wall-f1/

An interactive analytics dashboard covering every Formula 1 season from 1950 to 2024: 861 drivers, 77 circuits and 75 seasons in one page. It combines classic BI views with a race simulator and game features that make the data engaging.

The interface is in Brazilian Portuguese.

## Sections

- **Overview (Visão geral):** season KPIs, champions, and championship progression for any year
- **Races (Corridas):** every Grand Prix with podium, results and, from 1996 onward, a lap-by-lap position chart
- **Drivers (Pilotos):** sortable, searchable table with filters (champions, 2024 grid, Brazilians) and a career profile for each driver
- **Circuits (Circuitos):** track maps and history for all 77 layouts
- **Simulator (Simulador):** pick a driver from any era, a track and the rivals. Driver ratings come from real history (race pace, qualifying, wins, reliability) and each track's overtaking difficulty is derived from real data. A repeated-simulation run estimates the chosen driver's chances
- **Arena:** gamification with XP, levels and badges across three challenges (driver Top Trumps, "guess the circuit" quiz, and podium prediction)

## Data and credits

- Race data: Ergast / Kaggle Formula 1 dataset (1950–2024): races, results, standings, laps and pit stops
- Driver photos: lead image of each driver's English Wikipedia article (Wikimedia Commons, each under its own license), auto-cropped to the face
- Team logos (2014–2024): from the apex-f1-intelligence project. Trademarks belong to their teams and are used only to identify each team in this non-commercial analytics project
- Track maps: simplified reference layouts from bacinger/f1-circuits (MIT) and f1db (CC BY 4.0)

Unofficial project, not affiliated with Formula 1.

## Tech

- Single static HTML file, no build step and no framework
- Charts drawn as inline SVG with vanilla JavaScript
- Game progress (XP, badges) saved in the browser's localStorage

## Run locally

Open `index.html` in any modern browser.
