# IFR Procedures Guide

A comprehensive guide to Instrument Flight Rules procedures in Microsoft Flight Simulator 2024.

---

## Table of Contents

1. [IFR Fundamentals](#ifr-fundamentals)
2. [Flight Planning](#flight-planning)
3. [Departure Procedures](#departure-procedures)
4. [En Route Navigation](#en-route-navigation)
5. [Arrival Procedures](#arrival-procedures)
6. [Instrument Approaches](#instrument-approaches)
7. [Holding Patterns](#holding-patterns)
8. [ATC Communications](#atc-communications)
9. [Emergency Procedures](#emergency-procedures)

---

## IFR Fundamentals

### IFR vs VFR

| Aspect | VFR | IFR |
|--------|-----|-----|
| Weather Minimums | 3 SM visibility, clear of clouds | Can fly in IMC |
| Navigation | Visual references | Instruments only |
| Flight Plan | Optional | Required |
| ATC Contact | Optional (Class E, G) | Mandatory |
| Altitude | Flexible | Assigned |

### Minimum Equipment (IFR)

Remember: **GRABCARD**

- **G**enerator/Alternator
- **R**adios (nav & com)
- **A**ltimeter (sensitive)
- **B**all (slip/skid indicator)
- **C**lock (seconds)
- **A**ttitude indicator
- **R**ate of turn indicator
- **D**irectional gyro (heading indicator)

### Instrument Scan

**Primary Instruments:**
- Attitude Indicator (pitch & bank)
- Altimeter (altitude)
- Heading Indicator (direction)
- Airspeed Indicator (speed)
- Vertical Speed Indicator (climb/descent rate)
- Turn Coordinator (rate of turn)

**Scan Technique:**
1. Start at attitude indicator
2. Scan to supporting instruments
3. Return to attitude indicator
4. Repeat in radial pattern

---

## Flight Planning

### IFR Altitudes

**Eastbound (0°-179°):** Odd thousands + 500
- FL190, FL210, FL230, FL250...

**Westbound (180°-359°):** Even thousands + 500
- FL180, FL200, FL220, FL240...

*Note: Add 500 ft above FL290 for RVSM airspace*

### Route Planning

1. **Check weather** (METAR, TAF, winds aloft)
2. **File flight plan** with route:
   - Departure airport (ICAO)
   - SID (Standard Instrument Departure)
   - Airways (J-routes high, V-routes low)
   - Waypoints
   - STAR (Standard Terminal Arrival Route)
   - Approach
   - Destination (ICAO)
   - Alternate (if required)

### Alternate Airport Requirements

**1-2-3 Rule:** Need alternate if:
- **1** hour before to **1** hour after ETA
- Ceiling less than **2000** ft
- Visibility less than **3** SM

### Fuel Requirements

- Fuel to destination
- Fuel to alternate (if required)
- 45 minutes reserve (day)

---

## Departure Procedures

### Types of Departures

#### 1. SID (Standard Instrument Departure)

Pre-planned departure routes from busy airports.

**Reading a SID:**
- Runway-specific
- Initial heading/course
- Altitude restrictions
- Transition to en route

**Example:**
```
BIKKR2.ALOBE (KSEA)
- Runway 16L/16C: Climb heading 156°
- At 400ft, turn right heading 210°
- Cross BIKKR at or above 3000
- Transition ALOBE: Direct ALOBE, maintain FL230
```

#### 2. ODP (Obstacle Departure Procedure)

Used when no SID exists or terrain requires specific routing.

**Standard Takeoff Minimums:**
- 1 SM visibility
- Climb 200 ft/nm to 400 ft AGL

#### 3. Radar Vectors

ATC provides headings after takeoff.

---

## En Route Navigation

### Airway Structure

**Low Altitude (Below FL180):**
- Victor Airways (V-routes)
- MEA: Minimum En Route Altitude
- MOCA: Minimum Obstruction Clearance Altitude

**High Altitude (FL180-FL450):**
- Jet Routes (J-routes)
- RVSM airspace (FL290-FL410)

### Navigation Fixes

| Type | Description |
|------|-------------|
| VOR | VHF Omnidirectional Range |
| NDB | Non-Directional Beacon |
| Waypoint | GPS coordinate fix |
| Intersection | Radial crossings |

### GPS/FMS Navigation

Modern aircraft use RNAV (Area Navigation):
- Direct routing between waypoints
- More efficient than airway routing
- Required for many approaches

---

## Arrival Procedures

### STAR (Standard Terminal Arrival Route)

Transition from en route to approach.

**Reading a STAR:**
- Entry points from en route
- Altitude restrictions (at/above, at/below)
- Speed restrictions
- Transition to approach

**Example Restriction Notation:**
```
WAYPOINT
10000A  = At or Above 10,000
8000B   = At or Below 8,000
6000    = Cross AT 6,000
250K    = 250 knots max
```

### Descent Planning

**Top of Descent (TOD) Formula:**
```
Distance = (Cruise Alt - Field Elev) ÷ 300

Example: FL350 → 1000 ft field
(35,000 - 1000) ÷ 300 = 113 nm
```

**3° Descent Profile:**
- Approximately 300 ft per nm
- Or: Groundspeed × 5 = ft/min descent rate

---

## Instrument Approaches

### Approach Categories

| Category | Speed (Vref) |
|----------|--------------|
| A | < 91 knots |
| B | 91-120 knots |
| C | 121-140 knots |
| D | 141-165 knots |
| E | > 166 knots |

### Types of Approaches

#### ILS (Instrument Landing System)

Most precise approach type.

**Components:**
- Localizer (LOC): Lateral guidance
- Glideslope (GS): Vertical guidance (typically 3°)
- Marker beacons: OM, MM, IM

**Minimums:** As low as 200 ft / ½ SM (CAT I)

**Flying the ILS:**
1. Intercept localizer (heading to intercept)
2. Track localizer inbound
3. Intercept glideslope from below
4. Follow both needles to minimums
5. Look for runway environment
6. Land or go missed

#### VOR Approach

Non-precision approach using VOR.

**Flying VOR Approach:**
1. Identify VOR
2. Set inbound course
3. Intercept final approach course
4. Descend per procedure
5. Time from FAF to MAP
6. At minimums: runway or missed

#### RNAV (GPS) Approaches

**LPV (Localizer Performance with Vertical):**
- Precision-like minimums
- Requires WAAS GPS
- Similar to ILS

**LNAV/VNAV:**
- Lower minimums than LNAV only
- Requires baro-VNAV or WAAS

**LNAV:**
- Lateral guidance only
- Step-down fixes
- Higher minimums

#### Circling Approaches

- Maneuver visually to land on different runway
- Higher minimums
- Protected airspace varies by category

---

## Holding Patterns

### Standard Holding Pattern

- Right turns
- 1 minute legs (below 14,000)
- 1.5 minute legs (above 14,000)

### Holding Entries

Determine entry based on aircraft heading relative to hold:

```
         Direct
           ↑
    _____ | _____
   /      |      \
  /  Parallel     \
 /    Entry   Teardrop
/                   \
←─────── FIX ───────→
         Holding Course
```

**Direct Entry (Sector A - ~70%):**
- Fly directly to fix, turn outbound

**Teardrop Entry (Sector B):**
- Fly to fix, turn 30° offset, fly 1 min
- Turn inbound, intercept holding course

**Parallel Entry (Sector C):**
- Fly to fix, turn parallel to outbound leg
- After 1 min, turn back to fix

### Holding Speeds

| Altitude | Max Speed |
|----------|-----------|
| Up to 6000 MSL | 200 KIAS |
| 6001-14000 MSL | 230 KIAS |
| Above 14000 MSL | 265 KIAS |

---

## ATC Communications

### Standard Phraseology

**Clearance:**
```
"[Callsign] is cleared to [destination] airport,
[departure procedure], then as filed,
maintain [altitude], expect [cruise alt] [time],
departure frequency [freq], squawk [code]"
```

**Readback:** Repeat all clearances

**Contact Sequence:**
1. Ground (taxi)
2. Tower (takeoff/landing)
3. Departure (climb)
4. Center (en route)
5. Approach (descent)
6. Tower (landing)
7. Ground (taxi in)

### Altitude Assignments

- "Climb and maintain FL350"
- "Descend and maintain 10,000"
- "Cross WAYPOINT at FL240"
- "Cross WAYPOINT at or above 6000"

### MSFS ATC Tips

1. Use ATC menu (default: scroll wheel)
2. Listen for your callsign
3. Follow assigned headings/altitudes
4. Request approach when prompted
5. ATC will sequence you with traffic

---

## Emergency Procedures

### Lost Communications (NORDO)

**Route:** AVE-F
- **A**ssigned (last assigned route)
- **V**ectored (direct to fix)
- **E**xpected (route told to expect)
- **F**iled (flight plan route)

**Altitude:** Highest of:
- Last assigned altitude
- Minimum IFR altitude
- Expected altitude

### Missed Approach Procedure

1. **Climb:** Full power, pitch up
2. **Configure:** Flaps as required, positive rate gear up
3. **Navigate:** Follow published missed approach
4. **Communicate:** Notify ATC

### Emergency Squawk Codes

| Code | Meaning |
|------|---------|
| 7500 | Hijack |
| 7600 | Lost Communications |
| 7700 | Emergency |

---

## Quick Reference

### Common Abbreviations

| Abbrev | Meaning |
|--------|---------|
| AGL | Above Ground Level |
| MSL | Mean Sea Level |
| DA | Decision Altitude |
| DH | Decision Height |
| MDA | Minimum Descent Altitude |
| MAP | Missed Approach Point |
| FAF | Final Approach Fix |
| IAF | Initial Approach Fix |
| IF | Intermediate Fix |
| HAT | Height Above Touchdown |
| TDZE | Touchdown Zone Elevation |

### Approach Lighting Systems

| System | Visibility Required |
|--------|---------------------|
| ALSF-1/2 | 1400-2400 ft |
| MALSR | 1400 ft |
| SSALR | 1400 ft |
| ODALS | 1400 ft |
| REIL | None required |

---

## Practice Recommendations

1. **Start with VFR** - Learn navigation basics first
2. **Use simple aircraft** - C172 before A320
3. **Practice holds** - Master entries and timing
4. **Fly approaches** - ILS first, then non-precision
5. **Use ATC** - Practice communications
6. **Study charts** - Understand symbols and procedures
7. **Join VATSIM/IVAO** - Real ATC adds immersion
