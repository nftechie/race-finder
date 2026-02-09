# Race Finder Skill

Find upcoming races — running, trail, triathlon, cycling, swimming, and obstacle courses. Powered by [RaceFinder](https://racefinder.net).

## Quick Start

```bash
curl "https://api.racefinder.net/api/v1/races?city=Austin&state=TX"
```

No authentication required.

## Install as Claude Code Skill

```bash
claude skill add --url https://github.com/nftechie/race-finder-skill
```

## What It Does

- Search by location (city/state, zipcode + radius)
- Filter by sport (running, trail, triathlon, cycling, swimming, obstacle)
- Filter by distance (5K, 10K, half-marathon, marathon, ultra)
- Filter by date range
- Returns race details, distances, pricing, and registration links

See [SKILL.md](SKILL.md) for full API documentation.
