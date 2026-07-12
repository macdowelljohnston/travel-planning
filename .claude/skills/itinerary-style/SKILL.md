---
name: itinerary-style
description: House writing style for trip itineraries in the travel-planning repo. Use when creating or editing any trip itinerary markdown (trips/*/itinerary.md). Applies the "Polished hype, Medium treatment" standard so every trip reads like a five-star travel brand and renders with styled callout cards on the site.
---

# Itinerary House Style

The standard for every itinerary in this repo. The goal: pages that are fun, enticing, and
unmistakably *ours*, not a transcript of times and venue names.

## Voice: "Polished hype"

Luxury-magazine meets insider friend. Evocative and atmospheric, but tight.

- **Second person, present tense.** "You climb the headland." "You finish on the cheesecake."
- **Every stop earns its place.** Never just name a venue. Give the one vivid reason it matters
  and the insider move: the *dish* to order, the *trick*, the *timing*.
- **Specificity over adjectives.** "Wild-mushroom sauté under a runny egg yolk" beats "amazing food."
- **Confident, refined, lightly romantic.** Atmosphere is welcome; slang and jokey filler are not.
- **No em dashes (—), ever.** Use colons, periods, or parentheses. En dashes (–) are fine in ranges
  (`17–20 Aug`, `$150–300`). Arrows (→) are fine for routes and sequences.
- **Lead with the hook, keep the logistics.** Vivid first, then the practical detail (time, cost,
  booking) stays in the same line or a callout. Never lose the useful information.

## Structure: "Medium treatment"

### Trip header
```
# {Destination} {emoji}

*{One-line tagline: the trip in a single evocative sentence.}*

**Dates:** … **Base:** … **Region/Vibe:** …
**The shape:** {One line describing the arc of the trip, day to day.}
```
Keep the **Fixed points** table (flights, trains, transfers with status).

### Each day
```
### Day N · {Wkd DD Mon} · {Functional label}
> {Day hook: one or two present-tense sentences setting the day's arc and energy.}

- **{HH:MM}** {icon} **{Venue}.** {The vivid why + the insider move, in a sentence or two.}
```
- Day labels stay **functional** (what/where), not cutesy themed names.
- The day hook is a plain blockquote (renders as an elegant serif dek).
- Times are optional where the plan is loose ("Late morning", "Afternoon").
- Bold every venue name. Sub-lists (e.g. a pintxos crawl) are numbered, each with icon + why.

### Callouts (use sparingly; they render as cards on the site)
Exactly **one ⭐ The Move per day** (the hero moment). The others only when they genuinely earn it.
```
> ⭐ **The Move:** {the single unmissable thing that day}
> 💡 **Local intel:** {the insider trick}
> ⚠️ **Heads up:** {the thing that will bite you}
> 🎯 **Book it:** {the reservation to lock now}
```
Each callout is its own blockquote and must **start with the emoji** so the renderer styles it.

## Icon legend (category markers)
☕ coffee · 🍴 eat · 🍸 drink / night · 🍺 beer / beer garden · 🏖️ beach · 🥾 hike / active ·
♨️ baths / spa · 👀 sights · 🛍️ shop · 🚢 boat · 🚲 activity · 🚕 transfer / taxi · 🚆 train ·
✈️ flight · 🛏️ stay

## Before → after (the bar to clear)

**Before (a transcript):**
```
- **La Viña** (Basque cheesecake)
```
**After (house style):**
```
- **20:00** 🍴 **La Viña.** You finish on the original burnt Basque cheesecake: torched top,
  molten centre, the dish a thousand menus now imitate. Order it without discussion.

> 💡 **Local intel:** start the crawl at 20:00 for first crack at the counters. Locals eat later,
> so the early window is yours.
```

## Checklist before saving an itinerary
- [ ] Tagline + "The shape" line in the header
- [ ] Every day has a hook and exactly one ⭐ The Move
- [ ] Every stop has a why-line and a category icon, not just a name
- [ ] Dishes / tricks / timing named where they matter
- [ ] Zero em dashes
- [ ] All original logistics (times, prices, bookings) preserved
