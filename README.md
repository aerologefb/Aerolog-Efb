# Aerolog EFB

**Electronic Flight Bag for line pilots.** Import your OFP, read your sector before you fly it, get live weather and NOTAMs, decode D-ATIS worldwide, run aviation calculators, and keep an EASA-compliant logbook — all in one professional iOS app.

---

## Built for the line

Aerolog EFB is built by a pilot, for pilots flying schedule. It does the briefing-room work in your bag: drop in your OFP, see the track you actually filed, get the weather your dispatcher saw, and check your NOTAMs without juggling six tabs.

Every figure it shows you comes from your flight plan or a named source. Where a number cannot be derived, Aerolog says so instead of estimating one.

## What's inside

### OFP & briefing
- LIDO, Jeppesen, NavBlue, and Sabre OFP import, with format auto-detection
- Auto-extracts route, fuel, weights, NOTAMs, weather, ETAs
- Cost index, dispatcher, OFP revision, filed ATC route, reclearance plan, MEL/CDL items
- Re-import a revised OFP and every changed figure rolls old → new with delta chips
- Fuel waterfall: block fuel decomposed bar by bar down to planned fuel over destination
- Winds OFP ⇄ forecast: planned cruise winds morphed into live forecasts, with the headwind delta called out

### Reading the sector
- Threats read as a ranked list ordered by when you meet them, each carrying the fuel your plan states at that point
- The plan view draws the ground track you filed, with waypoints and hazards, against a scale in nautical miles — and states when the flight plan authored no coordinates rather than drawing a line anyway
- Vertical profile against grid MORA, with fuel over destination and final reserve marked
- A mission ruler that is live at rest: milestones, a now-marker, a second pin for comparing two points, and ETA / fuel-over-destination / worst-threat-ahead always on screen

### Live weather
- METAR, TAF, decoded flight rules (VFR / MVFR / IFR / LIFR)
- Per-airport briefings with sunrise/sunset and magnetic variation
- **D-ATIS worldwide** — runway in use, transition level, approach and arrival/departure runway decode for airports outside the FAA feed, across five national phrasings
- Reports from outside the US are overheard from ACARS, so each one shows where it came from and how old it is
- Where an ATIS and a METAR disagree on pressure, the METAR is named as the current figure
- Airport weather flips between the dispatch-issued OFP snapshot (fully offline) and live conditions

### NOTAMs & hazards
- Multi-airport parallel fetch
- Company-NOTAM decoding
- Map plotting with point / circle / polygon geometry
- Enroute SIGMET/AIRMET and G-AIRMET areas, plus pilot reports, filtered to your route corridor

### An outage says so
When a weather, NOTAM, pilot-report or wind source cannot be reached, Aerolog reports the source as unavailable rather than showing an empty result. A feed that is down never reads as clear skies or no NOTAMs.

### Calculators
- Great-circle distance and time
- Fuel planning with PTC reserves
- Crosswind, altimetry, cold-temperature correction
- EASA crew rest schedule planner

### Digital logbook
- Flight logging with takeoff/landing recency tracking
- CSV import from ForeFlight, LogTen Pro, MCC Pilot Log, eCrew
- EASA PDF export
- Aircraft fleet with type-currency tracking

### All-weather operations
- ICAO Annex 15 SNOWTAM and ASHTAM decoders
- LVO RVR assessment
- Runway data with TORA / LDA declared distances

### Made to read in a cockpit
- Light, Dark and red-safe Night share one accent language
- Your device text-size setting scales Aerolog's own type, not just system controls
- The command dock retracts while you read and returns when you scroll back

### Tools
- Countdown timer with operational presets
- Precision stopwatch with laps and alert pulses
- Backup and restore to `.aerolog` format
- Widget and Apple Watch: trip fuel, EFOB at destination, ETOPS entry countdown, ride band

## Subscription

Aerolog EFB Premium — **$9.99/month USD** with a **7-day free trial**.

- Cancel anytime in iOS Settings → Apple ID → Subscriptions
- Auto-renews monthly until cancelled
- Renewal occurs within 24 hours before the period ends
- Payment is charged to your Apple ID at confirmation of purchase

## Privacy

Aerolog EFB does not collect, store, or transmit any personal data, and has no account system. Your logbook, OFPs, and settings stay on your device.

Aviation data is fetched from public providers, and the optional AI briefing, voice assistant and spoken-briefing features send operational flight-plan text to third-party services. No personal information is sent to any of them.

[Read the full Privacy Policy](./PRIVACY_POLICY.md)

## Support

- Email: [NAV-INT-llc@pm.me](mailto:NAV-INT-llc@pm.me)
- Bug reports & feature requests: [GitHub Issues](https://github.com/aerologefb/Aerolog-Efb/issues)
- Support page: [SUPPORT.md](./SUPPORT.md)

## Disclaimer

Aerolog EFB is a **reference and planning tool**. It is **NOT certified for primary navigation, dispatch, or operational use**. Always cross-check all data against your company's official OFP, dispatch documentation, and authoritative aviation sources (FAA, EASA, NOTAM offices, METAR/TAF providers, airline operations).
