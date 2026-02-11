# map-rings
Display city aerial distances in rings around a configurable center.

## Features
- Single html file - just open in browser of choice.
- Based on leaflet world map & features.
- Preconfigured with cities in israel based on 2024 gov data, approximated to latitude/longitude coords (ITM -> WGS84, thanks to Zvika Ben-Haim's website), categorised as major / medium / small by pop (30k / 100k).
Data about cities with >10k pop seems to be freely available on the world cities database.
- Every city name is displayed and coloured according to the innermost ring it is within (or black if outside all rings).
- Cities can be filtered by population number, ring sizes can be adjusted both in colour and radius.
- Drag the marker or long press or "C" to change center position. Long pressing C repeats  every 0.1 seconds for a cursor tracking feature.
- Press "R" to reset configuration, spacebar to reset zoom on center.
- Tooltips for cities contain population and distance (hover), and anywhere within a ring the coord + distance from center + general information about the ring.
- Partial support for mobile - menus adjust with screen size, changing center (with long tap, ignoring multiple taps) updates all slider values.

<img width="1680" height="847" alt="RadiusCirclesExample1" src="https://github.com/user-attachments/assets/41154b3b-64e9-4ad1-b386-181d770d9839" />

<img width="583" height="846" alt="RadiusCirclesExample2" src="https://github.com/user-attachments/assets/bc7e9ece-a9dc-40fa-8cd2-19d56f49b1b9" />
