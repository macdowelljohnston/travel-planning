# Travel Planning ✈️

A personal repo for planning trips, building itineraries, and keeping travel notes all in one place.

## Structure

```
travel-planning/
├── trips/          # One folder per trip (e.g. trips/2026-japan/)
├── templates/      # Reusable templates for itineraries, packing lists, budgets
└── resources/      # General reference: airlines, loyalty programs, tips
```

## How to plan a new trip

1. Copy the itinerary template into a new folder under `trips/`:
   ```
   trips/YYYY-destination/
   ```
   (e.g. `trips/2026-japan/`)
2. Rename and fill out the copied `itinerary.md`.
3. Add supporting files as needed — bookings, maps, budget, packing list.

## Naming convention

- Trip folders: `YYYY-destination` (e.g. `2026-italy`, `2027-patagonia`)
- Keep confirmation numbers, passport scans, and other sensitive info **out** of the repo (see `.gitignore`).

## Templates available

- [`templates/itinerary.md`](templates/itinerary.md) — day-by-day itinerary
- [`templates/packing-list.md`](templates/packing-list.md) — packing checklist
- [`templates/budget.md`](templates/budget.md) — trip budget tracker
