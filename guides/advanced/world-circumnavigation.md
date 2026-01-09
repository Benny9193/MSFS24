# World Circumnavigation Planner

The ultimate flight sim adventure - flying around the world.

---

## Overview

| Route Type | Distance | Time (C172) | Time (Jet) |
|------------|----------|-------------|------------|
| Equatorial | ~21,600 nm | 200+ hrs | 50+ hrs |
| Northern | ~14,000 nm | 130+ hrs | 35+ hrs |
| Southern | ~18,000 nm | 170+ hrs | 45+ hrs |

### Requirements (FAI Rules)
- Cross all meridians
- Start and end at same point
- Minimum distance: 21,600 nm (equatorial)
- Northern route: Tropic of Cancer minimum
- Southern route: Tropic of Capricorn minimum

---

## Classic Eastbound Route

### Why Eastbound?
- Prevailing westerly winds (jet stream)
- Tailwinds across Atlantic and Pacific
- Most efficient direction

### Route Overview
```
North America → Atlantic → Europe → Middle East →
South Asia → Southeast Asia → Pacific → North America
```

---

## Detailed Route: Eastbound Classic

### Leg 1: North America Start
| # | From | To | Distance | Notes |
|---|------|-----|----------|-------|
| 1 | KSFO San Francisco | KDEN Denver | 950 nm | Over Rockies |
| 2 | KDEN Denver | KORD Chicago | 800 nm | Great Plains |
| 3 | KORD Chicago | KJFK New York | 650 nm | Eastern seaboard |

### Leg 2: Atlantic Crossing
| # | From | To | Distance | Notes |
|---|------|-----|----------|-------|
| 4 | KJFK New York | CYYT St. John's | 900 nm | Canadian Maritimes |
| 5 | CYYT St. John's | BIKF Reykjavik | 1,200 nm | North Atlantic! |
| 6 | BIKF Reykjavik | EGPH Edinburgh | 750 nm | Scotland arrival |

### Leg 3: Europe
| # | From | To | Distance | Notes |
|---|------|-----|----------|-------|
| 7 | EGPH Edinburgh | LFPG Paris | 400 nm | Channel crossing |
| 8 | LFPG Paris | LSZH Zurich | 250 nm | Alps begin |
| 9 | LSZH Zurich | LOWW Vienna | 340 nm | Central Europe |
| 10 | LOWW Vienna | LTFM Istanbul | 750 nm | Balkans crossing |

### Leg 4: Middle East
| # | From | To | Distance | Notes |
|---|------|-----|----------|-------|
| 11 | LTFM Istanbul | LLBG Tel Aviv | 650 nm | Eastern Med |
| 12 | LLBG Tel Aviv | OMDB Dubai | 1,200 nm | Arabian Peninsula |

### Leg 5: South Asia
| # | From | To | Distance | Notes |
|---|------|-----|----------|-------|
| 13 | OMDB Dubai | VABB Mumbai | 1,050 nm | Arabian Sea |
| 14 | VABB Mumbai | VIDP Delhi | 700 nm | Across India |
| 15 | VIDP Delhi | VNKT Kathmandu | 450 nm | Himalayan foothills |
| 16 | VNKT Kathmandu | VGHS Dhaka | 350 nm | Bangladesh |
| 17 | VGHS Dhaka | VTBS Bangkok | 850 nm | Myanmar overfly |

### Leg 6: Southeast Asia
| # | From | To | Distance | Notes |
|---|------|-----|----------|-------|
| 18 | VTBS Bangkok | WSSS Singapore | 750 nm | Malaysia |
| 19 | WSSS Singapore | WIII Jakarta | 520 nm | Java Sea |
| 20 | WIII Jakarta | WADD Bali | 530 nm | Indonesian islands |

### Leg 7: Australia/Pacific Setup
| # | From | To | Distance | Notes |
|---|------|-----|----------|-------|
| 21 | WADD Bali | YPDN Darwin | 1,000 nm | Timor Sea |
| 22 | YPDN Darwin | YBCS Cairns | 900 nm | Across Top End |
| 23 | YBCS Cairns | NFFN Nadi, Fiji | 1,800 nm | Coral Sea! |

### Leg 8: Pacific Crossing
| # | From | To | Distance | Notes |
|---|------|-----|----------|-------|
| 24 | NFFN Fiji | NTAA Papeete | 1,700 nm | South Pacific |
| 25 | NTAA Papeete | MMTP Kiritimati | 1,100 nm | Christmas Island |
| 26 | MMTP Kiritimati | PHNL Honolulu | 1,150 nm | Hawaii! |
| 27 | PHNL Honolulu | KSFO San Francisco | 2,100 nm | Home stretch! |

### Total: ~21,800 nm | 27 legs

---

## Northern Route (Faster)

### Advantages
- Shorter distance (~14,000 nm)
- More airports/alternates
- Better infrastructure
- Temperate weather (mostly)

### Route
```
Seattle → Canada → Greenland → Iceland →
UK → Europe → Russia → Alaska → Seattle
```

### Key Legs
| # | From | To | Distance | Notes |
|---|------|-----|----------|-------|
| 1 | KSEA Seattle | CYEG Edmonton | 650 nm | Canada |
| 2 | CYEG Edmonton | CYYZ Toronto | 1,500 nm | Trans-Canada |
| 3 | CYYZ Toronto | CYYR Goose Bay | 850 nm | Labrador |
| 4 | CYYR Goose Bay | BGSF Sondrestrom | 750 nm | Greenland |
| 5 | BGSF Greenland | BIKF Reykjavik | 700 nm | Iceland |
| 6 | BIKF Reykjavik | EGLL London | 1,150 nm | UK arrival |
| 7 | EGLL London | UUEE Moscow | 1,350 nm | Russia |
| 8 | UUEE Moscow | UNNT Novosibirsk | 1,550 nm | Siberia |
| 9 | UNNT Novosibirsk | UHPP Petropavlovsk | 2,400 nm | Far East |
| 10 | UHPP Kamchatka | PANC Anchorage | 1,600 nm | Bering crossing |
| 11 | PANC Anchorage | KSEA Seattle | 1,250 nm | Home |

### Total: ~13,750 nm | 11 legs

---

## Southern Route (Scenic)

### Advantages
- More scenic
- Warmer weather
- Island hopping
- Adventure factor

### Route
```
Cape Town → Australia → Pacific Islands →
South America → Atlantic → Africa → Cape Town
```

### Key Legs
| # | From | To | Distance | Notes |
|---|------|-----|----------|-------|
| 1 | FACT Cape Town | FSIA Mahé, Seychelles | 2,400 nm | Indian Ocean |
| 2 | FSIA Seychelles | VRMM Maldives | 1,200 nm | Atolls |
| 3 | VRMM Maldives | WIII Jakarta | 2,100 nm | Indonesia |
| 4 | WIII Jakarta | YSSY Sydney | 2,900 nm | Australia |
| 5 | YSSY Sydney | NZAA Auckland | 1,350 nm | Tasman Sea |
| 6 | NZAA Auckland | NTAA Papeete | 2,300 nm | Polynesia |
| 7 | NTAA Tahiti | SCIP Easter Island | 2,350 nm | Remote! |
| 8 | SCIP Easter | SCEL Santiago | 2,000 nm | Chile |
| 9 | SCEL Santiago | SAEZ Buenos Aires | 700 nm | Argentina |
| 10 | SAEZ Buenos Aires | FACT Cape Town | 3,800 nm | South Atlantic! |

### Total: ~21,100 nm | 10 legs (longer sectors)

---

## Aircraft Selection

### Single-Engine Piston
| Aircraft | Range | Speed | Challenge |
|----------|-------|-------|-----------|
| Cessna 172 | 640 nm | 120 kt | Very High |
| Cessna 182 | 900 nm | 140 kt | High |
| Cirrus SR22 | 1,000 nm | 180 kt | Moderate |
| Mooney M20 | 1,100 nm | 175 kt | Moderate |

**Challenges:** Ocean crossings, fuel, endurance

### Twin-Engine Piston
| Aircraft | Range | Speed | Challenge |
|----------|-------|-------|-----------|
| Beech Baron | 1,200 nm | 200 kt | Moderate |
| Piper Seneca | 800 nm | 180 kt | Moderate |
| Diamond DA62 | 1,100 nm | 180 kt | Moderate |

**Better for:** Twin-engine safety over water

### Turboprop
| Aircraft | Range | Speed | Challenge |
|----------|-------|-------|-----------|
| TBM 930 | 1,700 nm | 330 kt | Lower |
| Pilatus PC-12 | 1,800 nm | 280 kt | Lower |
| King Air 350 | 1,800 nm | 310 kt | Lower |

**Ideal for:** Realistic circumnavigation

### Jet
| Aircraft | Range | Speed | Challenge |
|----------|-------|-------|-----------|
| Citation CJ4 | 2,000 nm | 450 kt | Low |
| Longitude | 3,500 nm | 480 kt | Very Low |
| Global Express | 6,000 nm | 510 kt | Minimal |

**For:** Speed runners, minimal stops

---

## Ocean Crossing Considerations

### Atlantic Crossing Options

**Northern Route (Recommended):**
```
KJFK → CYYT (900 nm) → BIKF (1,200 nm) → EGLL (1,150 nm)
Longest leg: 1,200 nm
```

**Southern Route:**
```
KFLL → TXKF Bermuda (750 nm) → LPLA Azores (1,800 nm) → LPPT (900 nm)
Longest leg: 1,800 nm (requires long-range aircraft)
```

### Pacific Crossing Options

**Northern (Alaska Route):**
```
PAFA Fairbanks → UHPP Kamchatka (1,600 nm) → RJTT Tokyo (1,500 nm)
```

**Central (Hawaii Route):**
```
KSFO → PHNL (2,100 nm) → PKMJ Majuro (2,300 nm) → Multiple hops
Longest leg: 2,300 nm
```

**Southern (Island Hopping):**
```
NZAA → NFTF Fiji (1,350 nm) → NTAA Tahiti (1,700 nm) → etc.
More stops, shorter legs
```

---

## Planning Tools

### Fuel Planning
```
Basic Formula:
Distance ÷ Ground Speed = Time
Time × Fuel Flow = Fuel Required
Add 45 min reserve (IFR) or 30 min (VFR)
Add alternate fuel if required
```

### Time Zones
- Eastbound: Lose time (sun rises earlier)
- Westbound: Gain time
- International Date Line: Skip/repeat a day

### Weather Windows
| Ocean | Best Season | Avoid |
|-------|-------------|-------|
| North Atlantic | June-August | Winter storms |
| South Atlantic | Year-round | Hurricane season |
| Pacific | April-October | Typhoon season |
| Indian | Nov-April | Monsoon (Jun-Sep) |

---

## Documentation & Tracking

### Flight Log Template
```
Date: ___________
Leg: ___ of ___
From: ____ (ICAO)
To: ____ (ICAO)
Distance: ____ nm
Time: ____ hrs
Aircraft: ____________
Notes: _______________
```

### Milestones to Capture
- [ ] First ocean crossing
- [ ] Equator crossing
- [ ] International Date Line
- [ ] Each continent
- [ ] Highest airport
- [ ] Most remote airport
- [ ] Longest single leg
- [ ] Arrival home!

---

## Challenge Variants

### Speed Run
- Use jets
- Minimize stops
- Direct routes
- Weather routing

### Realism Run
- GA aircraft only
- Accurate fuel
- Weather on
- No time compression

### Historic Recreation
- DC-3/vintage aircraft
- Original routes
- 1930s navigation

### Scenic Route
- Every continent
- Major landmarks
- Photography stops

### Charity Run
- Stream it
- Fundraise per mile
- Community participation

---

## Checkpoints Checklist

### Continents Visited
- [ ] North America (Start)
- [ ] Europe
- [ ] Asia
- [ ] Oceania/Australia
- [ ] South America (Southern routes)
- [ ] Africa (Southern routes)
- [ ] Antarctica (Extreme variant)

### Oceans Crossed
- [ ] Atlantic Ocean
- [ ] Pacific Ocean
- [ ] Indian Ocean (Southern)
- [ ] Arctic (Northern route)

### Lines Crossed
- [ ] Equator
- [ ] Prime Meridian (0°)
- [ ] International Date Line (180°)
- [ ] Tropic of Cancer
- [ ] Tropic of Capricorn
- [ ] Arctic Circle (Northern)

---

## Sample Itinerary: 30-Day Circumnavigation

### Week 1: Americas to Europe
| Day | Route | Distance |
|-----|-------|----------|
| 1 | SFO → Denver | 950 nm |
| 2 | Denver → Chicago → New York | 1,450 nm |
| 3 | New York → St. John's | 900 nm |
| 4 | St. John's → Reykjavik | 1,200 nm |
| 5 | Reykjavik → Edinburgh → Paris | 1,150 nm |
| 6 | Rest day / explore Paris | - |
| 7 | Paris → Vienna | 590 nm |

### Week 2: Europe to Asia
| Day | Route | Distance |
|-----|-------|----------|
| 8 | Vienna → Istanbul | 750 nm |
| 9 | Istanbul → Dubai | 1,800 nm |
| 10 | Dubai → Mumbai | 1,050 nm |
| 11 | Mumbai → Kathmandu | 1,150 nm |
| 12 | Kathmandu → Bangkok | 1,200 nm |
| 13 | Bangkok → Singapore | 750 nm |
| 14 | Rest day / explore Singapore | - |

### Week 3: Asia to Pacific
| Day | Route | Distance |
|-----|-------|----------|
| 15 | Singapore → Bali | 1,050 nm |
| 16 | Bali → Darwin | 1,000 nm |
| 17 | Darwin → Cairns | 900 nm |
| 18 | Cairns → Fiji | 1,800 nm |
| 19 | Fiji → Tahiti | 1,700 nm |
| 20 | Rest day / explore Tahiti | - |
| 21 | Tahiti → Christmas Island | 1,100 nm |

### Week 4: Pacific to Home
| Day | Route | Distance |
|-----|-------|----------|
| 22 | Christmas Island → Honolulu | 1,150 nm |
| 23 | Rest day / explore Hawaii | - |
| 24 | Honolulu → San Francisco | 2,100 nm |
| 25 | Celebration! | HOME! |

**Total: ~22,000 nm in 24 flying days**

---

## Quick Reference

### Essential Equipment
- Long-range tanks or planning
- GPS with oceanic waypoints
- HF radio capability
- Survival gear (immersion)
- Backup navigation

### Emergency Airports (Oceanic)
| Ocean | Divert Options |
|-------|---------------|
| North Atlantic | Iceland, Greenland, Azores |
| South Atlantic | Ascension, St. Helena |
| Pacific | Midway, Wake, Marshall Islands |
| Indian | Diego Garcia, Maldives |

### Success Tips
1. Plan extensively before departure
2. Check weather for each leg
3. Have alternates for every leg
4. Don't rush ocean crossings
5. Document everything
6. Enjoy the journey!
