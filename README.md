# sim-philly-2000
# SimPhilly 2000

A climate equity city builder for Philadelphia. You're the mayor — allocate budget, weather crises, and find out what kind of leader you are. Every department is powered by a real civic tech tool built for Philly.

## Why This Exists

Philadelphia ranks last among the 50 largest U.S. metros for enabling low-income residents to achieve economic mobility. The city's tree canopy is smallest where heat hits hardest. Over 300,000 residents live in poverty. SEPTA faces recurring funding crises. More than 250,000 Philadelphians have a disability and are routinely left out of emergency planning.

These aren't just statistics — they're governance failures. SimPhilly 2000 turns the tradeoffs behind those failures into a game you can play in five minutes, grounded in real Philadelphia data and powered by real civic tech tools.

## How to Play

1. **You're the Climate Equity Mayor.** You have 4 years (rounds) and 12 investment points per year.
2. **Allocate your budget** across 6 departments: Parks & Canopy, Transit, Flood Resilience, Climate Refuge, Community Power, and Policy & Plain Language.
3. **Face a crisis each year** — heat waves, flooding, SEPTA cuts, air quality emergencies, federal grants, and more. Your investments determine whether the city is protected or unprepared.
4. **Get your Governance Report** — your letter grade, governance style, disability equity assessment, score evolution chart, and links to every real tool.

**Civic Trust Mechanic:** Invest 2+ points in Policy & Plain Language and all other departments get a 15% effectiveness boost. Transparent governance multiplies everything.

**High Contrast Mode:** Toggle accessible high-contrast display from any screen.

## The Real Tools

Every department in the game is powered by a real, open-source civic tech tool built for Philadelphia:

| Department | Tool | What It Does |
|---|---|---|
| 🌳 Parks & Canopy | [CanopyWatch](https://meyeringn.github.io/canopy-watch/index) | Maps tree canopy gaps and heat equity by neighborhood |
| 🚇 Transit | [Transit Carbon Calculator](https://meyeringn.github.io/transit-carbon-calculator) | Quantifies CO₂ savings from transit use across 11 PA agencies |
| 🌊 Flood Resilience | [FloodRisk Philly](https://meyeringn.github.io/floodrisk-philly/) | FEMA flood risk lookup for Philadelphia renters |
| 🏠 Climate Refuge | [ClimateRefuge Philly](https://meyeringn.github.io/climate-refuge-philly/) | Cooling center and climate shelter finder |
| 👥 Community Power | [Frontline Philly](https://meyeringn.github.io/frontline-philly) | Climate burden explorer for frontline communities |
| 📋 Policy & Plain Language | [PlainSpeak Policy Explainer](https://meyeringn.github.io/plainspeak-policy-explainer/) | Plain-language policy translator with readability scoring |

## Data Sources

Game events, community voices, and governance insights draw from:

- Pew Charitable Trusts, *Philadelphia 2026: State of the City* (April 2026)
- Brookings Institution, *Southeastern Pennsylvania Market Assessment for Growing Opportunity Industries and Economic Mobility* (July 2025)
- Pew Charitable Trusts, *Gen Z Likes Philadelphia but Feels Frustrated by Low Pay, Limited Jobs* (August 2026)
- Pew Charitable Trusts, *Philadelphia's Guiding Document at 75* (March 2026)
- Opportunity Insights, economic mobility data (Harvard University)

Neighborhood income data (Hunting Park, Eastwick, Nicetown, North Philadelphia) comes from U.S. Census Bureau American Community Survey 2020–2024 estimates via Pew.

## Tech Stack

- Vanilla HTML/CSS/JS — single `index.html`, no build step
- React 18 + Babel (CDN) for component architecture
- Hand-built SVG chart (no charting library dependency)
- Hosted on GitHub Pages

## Contributing

Ideas, bug reports, and pull requests are welcome. If you're a Philadelphian with lived experience in any of the areas this game covers — heat, flooding, transit, disability access, housing — your perspective matters more than your code. Open an issue or reach out.

## License

MIT

## Built By

**Nico Meyering, MPA**
Chairman, Philadelphia Mayor's Commission on People with Disabilities
VP, Net Impact Philadelphia · Board, Disability Pride PA
Steering Committee, Transit Forward Philadelphia

Part of the [Vibe Coding for Climate Justice](https://github.com/meyeringn) portfolio.
