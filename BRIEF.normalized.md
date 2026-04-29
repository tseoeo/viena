# Vienna Trip 2026-04

## Topic
- Vienna trip planning for 30 April to 3 May 2026 with elderly parents, centered on imperial sights, gardens, and a fixed Musikverein concert.

## Research Goal
- Determine the most practical, high-value 4-day Vienna itinerary for this group.
- Resolve whether Belvedere alone is enough or whether Schonbrunn and Hofburg should also be included given mobility, holiday timing, and hotel location.

## Audience and Deliverable
- Primary audience: the user planning the trip.
- Desired final output: an opinionated synthesis that can be turned into a paced day-by-day itinerary plus ranked site and restaurant options.
- Useful result: specific recommendations with source-backed opening info, accessibility/logistics notes, and realistic transport/walking tradeoffs.

## Known Context
- Travelers: Ivan plus both parents; father does not attend the Thursday concert.
- Dates: Thursday 30 April 2026 to Sunday 3 May 2026.
- Hotel: Blutengasse 14-16, 1030 Vienna.
- Fixed event: Thursday 30 April 2026 at 19:30, Wiener Symphoniker at the Grosser Musikvereinssaal.
- Mobility: slow but steady; stairs okay in small doses; frequent sit-down breaks; target about 30-60 total walking minutes per day.
- Interests prioritize palaces/imperial sights, then gardens/parks.
- Belvedere is very close to the hotel and should be weighted heavily.
- Friday 1 May 2026 is a public holiday in Austria and may affect openings, transport flow, and demonstrations.

## Open Questions
- Should the trip include both Belvedere and Schonbrunn, or is Belvedere plus Hofburg the better imperial pairing?
- Which Hofburg components give the highest value in about 90 minutes?
- What is open or closed on Friday 1 May 2026, especially Belvedere, Schonbrunn, Hofburg/Sisi Museum, gardens, restaurants, and coffeehouses?
- What transport and station-elevator details matter most from the hotel, especially for Musikverein night, Hofburg, and Schonbrunn?
- Which restaurants and coffeehouses best fit the routes, pacing, and seating needs?
- Is a hop-on-hop-off bus useful for this exact trip or not?
- What is the best calm Sunday morning activity near the hotel before departure?

## Constraints
- Work within `/Users/ivandimitrov/Projects/research-station/research station/vienna-trip-2026-04`.
- Use existing cmux workers `codex1`, `codex2`, and `codex3`.
- Prefer primary and official sources wherever possible.
- Keep worker scopes independent and avoid overlapping output files.
- Main answer must stay practical and mobility-aware rather than generic sightseeing.

## Non-Goals
- Exhaustive city guide coverage.
- Restaurant hunting beyond a few strong route-based recommendations.
- Re-checking facts the brief explicitly says to treat as fixed unless needed for logistics framing.

## Suggested Angles
- Day-by-day itinerary design anchored to hotel, holiday, and concert.
- Palace/garden ranking with accessibility and time-budget reality checks.
- Transport, closure, and route verification, including a devil's-advocate pass on assumptions that may fail in practice.

## Assumptions Made During Intake
- Final deliverable will be a research synthesis first, with enough detail to support a later itinerary draft.
- Round 1 should use three workers because the topic is multi-faceted but bounded.

## Intake Output
- Problem statement: Build a source-backed, mobility-aware Vienna plan for four days that favors imperial sights and gardens, uses the hotel near Belvedere as the operational center, protects energy for a Thursday concert, and avoids bad assumptions around May 1 operations and cross-city transfers.
- Core sub-questions:
  1. Which major imperial sights are worth the energy budget, in what order, and with what accessibility tradeoffs?
  2. What openings, transport routes, elevator access, and concert-night logistics materially affect the plan?
  3. Which assumptions break under scrutiny, especially around May 1, Hofburg sprawl, Schonbrunn effort, and supposed convenience of tourist transport options?
- Recommended rounds: 2 substantive rounds plus 1 verification pass, unless Round 1 materially changes the thesis.
- Round 1 worker split:
  - Worker A: Palace/garden ranking with accessibility and booking strategy.
  - Worker B: Transport, May 1 operations, Musikverein logistics, and route-based food stops.
  - Worker C: Devil's advocate on feasibility, closures, crowding, walking burden, and whether common recommendations are wrong for this party.
  - Devil's advocate: Worker C.
