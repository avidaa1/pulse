# AVIDAA Pulse

Live machines and people on one map. Open https://avidaa1.github.io/pulse/

Sources (all read straight from the browser, nothing stored on a server):
- CelesTrak GP elements, propagated with SGP4 (satellite.js, MIT): satellites
- USGS earthquake feed: earthquakes M2.5+
- NASA EONET: open natural events
- IODA (Georgia Tech): internet outages by country (listed, not placed on the map)
- Launch Library 2 (The Space Devs): upcoming launches and launch pads (cached, rate limit respected)
- OpenSky and KiwiSDR: shown as "source down" because browsers cannot read them from this site (checked 2026-11-25)
Reference layers (marked "reference", not real time): undersea cables (TeleGeography Submarine Cable Map, CC BY-NC-SA 3.0, snapshot in data/cables.json), tech power nodes (curated, UNVERIFIED), launch sites and pads (Launch Library 2).
Build: pulse_build/build_pulse.py in the AVIDAA work folder makes the modern copy and the legacy ES5 copy and the CSP hashes.
