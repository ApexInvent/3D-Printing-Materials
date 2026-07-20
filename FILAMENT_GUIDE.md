# 3D Printing Material Guide

A practical reference to common FDM 3D printing filaments: recommended print settings, physical properties, strengths, watch-outs and typical uses. From easy PLA to high-performance PEEK.

## How to read this

- **Ratings** are a 0-100 relative guide where higher is always better on that axis. For "Low odour", higher means less smell; for "Food-safe", higher means a more realistic food-contact option.
- **Print settings** are typical starting points curated from manufacturer datasheets (Prusament, Polymaker, Bambu Lab, Fillamentum). They vary by brand and printer, so always check your spool's own label.
- "Amorphous" materials soften over a range rather than melting at a sharp point.

## Quick reference

| Material | Difficulty | Nozzle | Bed | Speed | Density | Tg | Melting |
|---|---|---|---|---|---|---|---|
| PLA | Beginner | 190-220 °C | 20-60 °C | 50-150 mm/s | 1.24 g/cm³ | 60 °C | 155 °C |
| PLA-CF | Intermediate | 200-230 °C | 30-60 °C | 40-100 mm/s | 1.29 g/cm³ | 60 °C | 155 °C |
| Silk PLA | Beginner | 200-230 °C | 30-60 °C | 40-90 mm/s | 1.23 g/cm³ | 60 °C | 155 °C |
| Matte PLA | Beginner | 190-220 °C | 30-60 °C | 50-120 mm/s | 1.25 g/cm³ | 60 °C | 155 °C |
| Wood PLA | Intermediate | 190-220 °C | 30-60 °C | 30-80 mm/s | 1.2 g/cm³ | 60 °C | 155 °C |
| Tough PLA | Intermediate | 210-240 °C | 40-60 °C | 40-100 mm/s | 1.22 g/cm³ | 60 °C | 155 °C |
| PETG | Intermediate | 230-250 °C | 70-85 °C | 40-100 mm/s | 1.27 g/cm³ | 80 °C | Amorphous |
| PETG-CF | Advanced | 240-260 °C | 70-90 °C | 30-80 mm/s | 1.3 g/cm³ | 82 °C | Amorphous |
| ABS | Advanced | 230-260 °C | 90-110 °C | 40-80 mm/s | 1.04 g/cm³ | 105 °C | Amorphous |
| ASA | Advanced | 240-260 °C | 90-110 °C | 40-80 mm/s | 1.07 g/cm³ | 100 °C | Amorphous |
| ASA-CF | Advanced | 250-270 °C | 90-110 °C | 30-70 mm/s | 1.11 g/cm³ | 100 °C | Amorphous |
| TPU (95A) | Intermediate | 210-235 °C | 30-60 °C | 15-40 mm/s | 1.21 g/cm³ | -35 °C | Amorphous |
| TPE | Advanced | 210-235 °C | 30-55 °C | 10-25 mm/s | 1.2 g/cm³ | -40 °C | Amorphous |
| Nylon (PA) | Advanced | 240-270 °C | 70-90 °C | 30-70 mm/s | 1.14 g/cm³ | 50 °C | 220 °C |
| PA-CF (Nylon-CF) | Advanced | 260-300 °C | 50-90 °C | 30-60 mm/s | 1.16 g/cm³ | 60 °C | 220 °C |
| Polycarbonate (PC) | Advanced | 260-300 °C | 100-120 °C | 25-60 mm/s | 1.2 g/cm³ | 145 °C | Amorphous |
| PC-ABS | Advanced | 250-275 °C | 90-110 °C | 30-70 mm/s | 1.1 g/cm³ | 125 °C | Amorphous |
| HIPS | Intermediate | 230-245 °C | 90-110 °C | 40-80 mm/s | 1.05 g/cm³ | 100 °C | Amorphous |
| PVA | Advanced | 190-220 °C | 45-60 °C | 30-60 mm/s | 1.23 g/cm³ | 45 °C | Amorphous |
| PVB | Intermediate | 195-220 °C | 60-75 °C | 30-70 mm/s | 1.09 g/cm³ | 65 °C | Amorphous |
| Polypropylene (PP) | Advanced | 220-250 °C | 85-100 °C | 30-70 mm/s | 0.9 g/cm³ | -10 °C | 160 °C |
| PET-CF | Advanced | 260-290 °C | 80-100 °C | 30-60 mm/s | 1.3 g/cm³ | 80 °C | 255 °C |
| PPS-CF | Advanced | 310-340 °C | 100-120 °C | 20-50 mm/s | 1.35 g/cm³ | 90 °C | 280 °C |
| PEEK | Advanced | 360-450 °C | 120-160 °C | 20-40 mm/s | 1.3 g/cm³ | 143 °C | 343 °C |

## Materials

### PLA
*Polylactic acid* · **Beginner**

> The easiest filament to print and the natural starting point. Great detail and stiffness for models and light-duty parts, but it softens in heat and goes brittle outdoors.

| Nozzle | Bed | Speed | Density | Glass transition | Melting point |
|---|---|---|---|---|---|
| 190-220 °C | 20-60 °C | 50-150 mm/s | 1.24 g/cm³ | 60 °C | 155 °C |

**Requirements:** Enclosure: No · Heated bed: No · Dry filament: No · Cooling fan: Yes · Warping: low

**Ratings (0-100):** Strength 55 · Flexibility 12 · Impact 30 · Heat 20 · UV / weather 35 · Moisture 45 · Food-safe 55 · Low odour 92 · Ease 98

**Tags:** beginner-friendly

**Good for:** Display models and figurines; Prototypes and fit checks; Low-stress indoor parts

**Strengths:**
- Prints cleanly on almost any machine
- Sharp detail and a wide colour range
- Very low odour, plant-based

**Watch-outs:**
- Softens above 55 °C, so never leave it in a car
- Brittle over time, poor outdoors
- Not for load-bearing or heat

---

### PLA-CF
*Polylactic acid, carbon-filled* · **Intermediate**

> PLA stiffened with chopped carbon fibre for a matte, rigid finish that hides layer lines. Stiffer than plain PLA but just as heat-shy, and it chews through brass nozzles.

| Nozzle | Bed | Speed | Density | Glass transition | Melting point |
|---|---|---|---|---|---|
| 200-230 °C | 30-60 °C | 40-100 mm/s | 1.29 g/cm³ | 60 °C | 155 °C |

**Requirements:** Enclosure: No · Heated bed: No · Dry filament: Yes · Cooling fan: Yes · Warping: low

**Ratings (0-100):** Strength 68 · Flexibility 8 · Impact 28 · Heat 25 · UV / weather 35 · Moisture 45 · Food-safe 20 · Low odour 90 · Ease 70

**Tags:** engineering

**Good for:** Stiff jigs and fixtures; Matte-finish display pieces; Lightweight structural brackets (indoors)

**Strengths:**
- Noticeably stiffer than PLA
- Premium matte, low-glare surface
- Prints nearly as easily as PLA

**Watch-outs:**
- Needs a hardened steel nozzle
- Same poor heat resistance as PLA
- Fibres make it more brittle, not tougher

---

### Silk PLA
*Polylactic acid, silk blend* · **Beginner**

> PLA with a glossy, almost metallic sheen. Made purely for looks, and the additives that give the shine also make it weaker and less detailed than standard PLA.

| Nozzle | Bed | Speed | Density | Glass transition | Melting point |
|---|---|---|---|---|---|
| 200-230 °C | 30-60 °C | 40-90 mm/s | 1.23 g/cm³ | 60 °C | 155 °C |

**Requirements:** Enclosure: No · Heated bed: No · Dry filament: No · Cooling fan: Yes · Warping: low

**Ratings (0-100):** Strength 45 · Flexibility 14 · Impact 24 · Heat 20 · UV / weather 35 · Moisture 45 · Food-safe 20 · Low odour 90 · Ease 82

**Tags:** beginner-friendly

**Good for:** Vases and decorative prints; Gifts and ornaments; Show pieces where shine matters

**Strengths:**
- Eye-catching glossy finish
- Easy, PLA-like printing
- Hides layer lines well on curves

**Watch-outs:**
- Weaker and more brittle than PLA
- Softer detail on small features
- Purely decorative, not functional

---

### Matte PLA
*Polylactic acid, matte blend* · **Beginner**

> PLA with a flat, chalky finish that reads as more premium and hides layer lines beautifully. Prints like normal PLA with a slightly more abrasive feed.

| Nozzle | Bed | Speed | Density | Glass transition | Melting point |
|---|---|---|---|---|---|
| 190-220 °C | 30-60 °C | 50-120 mm/s | 1.25 g/cm³ | 60 °C | 155 °C |

**Requirements:** Enclosure: No · Heated bed: No · Dry filament: No · Cooling fan: Yes · Warping: low

**Ratings (0-100):** Strength 52 · Flexibility 12 · Impact 28 · Heat 20 · UV / weather 35 · Moisture 45 · Food-safe 20 · Low odour 90 · Ease 90

**Tags:** beginner-friendly

**Good for:** Architectural and product models; Props and cosplay bases; Photogenic display prints

**Strengths:**
- Flat, glare-free finish
- Hides layer lines exceptionally well
- As easy to print as standard PLA

**Watch-outs:**
- Mildly abrasive over time
- Same heat and outdoor limits as PLA
- Not for functional loads

---

### Wood PLA
*Polylactic acid, wood-fill* · **Intermediate**

> PLA blended with real wood fibre that sands, stains and even smells like timber. Lovely for decor, but the particles clog fine nozzles and make it brittle.

| Nozzle | Bed | Speed | Density | Glass transition | Melting point |
|---|---|---|---|---|---|
| 190-220 °C | 30-60 °C | 30-80 mm/s | 1.2 g/cm³ | 60 °C | 155 °C |

**Requirements:** Enclosure: No · Heated bed: No · Dry filament: Yes · Cooling fan: Yes · Warping: low

**Ratings (0-100):** Strength 40 · Flexibility 8 · Impact 20 · Heat 20 · UV / weather 35 · Moisture 35 · Food-safe 15 · Low odour 88 · Ease 68

**Good for:** Decor with a timber look; Sign-writing and plaques; Sand-and-stain craft pieces

**Strengths:**
- Genuine wood look, feel and smell
- Sands and stains like timber
- Warm, matte finish

**Watch-outs:**
- Clogs small (0.4 mm) nozzles, so go 0.6 mm
- Brittle and low strength
- Colour varies with print temperature

---

### Tough PLA
*Polylactic acid, toughened* · **Intermediate**

> PLA reformulated to absorb impact more like ABS while keeping PLA-easy printing. A good step up when plain PLA cracks but you do not want an enclosure.

| Nozzle | Bed | Speed | Density | Glass transition | Melting point |
|---|---|---|---|---|---|
| 210-240 °C | 40-60 °C | 40-100 mm/s | 1.22 g/cm³ | 60 °C | 155 °C |

**Requirements:** Enclosure: No · Heated bed: Yes · Dry filament: No · Cooling fan: Yes · Warping: low

**Ratings (0-100):** Strength 60 · Flexibility 18 · Impact 58 · Heat 25 · UV / weather 35 · Moisture 50 · Food-safe 20 · Low odour 88 · Ease 80

**Tags:** engineering

**Good for:** Tools and jigs that take knocks; Functional prototypes; RC and hobby parts

**Strengths:**
- Much better impact resistance than PLA
- No enclosure needed
- Cleaner to print than ABS

**Watch-outs:**
- Still softens in heat like PLA
- Pricier than standard PLA
- Not UV-stable for outdoors

---

### PETG
*Glycol-modified PET* · **Intermediate**

> The all-rounder: tougher and more heat- and water-resistant than PLA, still fairly easy to print. The go-to for functional parts that live indoors or take some weather.

| Nozzle | Bed | Speed | Density | Glass transition | Melting point |
|---|---|---|---|---|---|
| 230-250 °C | 70-85 °C | 40-100 mm/s | 1.27 g/cm³ | 80 °C | Amorphous |

**Requirements:** Enclosure: No · Heated bed: Yes · Dry filament: Yes · Cooling fan: Yes · Warping: low

**Ratings (0-100):** Strength 65 · Flexibility 26 · Impact 58 · Heat 50 · UV / weather 55 · Moisture 78 · Food-safe 80 · Low odour 80 · Ease 72

**Tags:** food-safe, outdoor-safe

**Good for:** Functional brackets and enclosures; Water-tight and outdoor-ish parts; Food and drink containers (see notes)

**Strengths:**
- Strong, tough and slightly flexible
- Handles moisture and mild outdoor use
- Low warping, no enclosure required

**Watch-outs:**
- Stringy, so tune retraction
- Absorbs moisture; dry before printing
- Sticks a bit too well to some beds

---

### PETG-CF
*Glycol-modified PET, carbon-filled* · **Advanced**

> PETG stiffened with carbon fibre for rigid, dimensionally stable engineering parts with a handsome matte-black finish. Abrasive, and it wants a dry spool.

| Nozzle | Bed | Speed | Density | Glass transition | Melting point |
|---|---|---|---|---|---|
| 240-260 °C | 70-90 °C | 30-80 mm/s | 1.3 g/cm³ | 82 °C | Amorphous |

**Requirements:** Enclosure: No · Heated bed: Yes · Dry filament: Yes · Cooling fan: Yes · Warping: low

**Ratings (0-100):** Strength 78 · Flexibility 12 · Impact 55 · Heat 55 · UV / weather 55 · Moisture 78 · Food-safe 15 · Low odour 78 · Ease 58

**Tags:** engineering

**Good for:** Rigid brackets and mounts; Drone and RC frames; Dimensionally stable fixtures

**Strengths:**
- Stiffer and more stable than plain PETG
- Premium matte finish
- Keeps PETG toughness and moisture resistance

**Watch-outs:**
- Needs a hardened nozzle
- Very sensitive to damp filament
- Harder to get glassy surfaces

---

### ABS
*Acrylonitrile butadiene styrene* · **Advanced**

> The classic engineering plastic: heat-resistant, tough and easy to sand, glue and vapour-smooth. The catch is warping and styrene fumes, so it needs an enclosure and ventilation.

| Nozzle | Bed | Speed | Density | Glass transition | Melting point |
|---|---|---|---|---|---|
| 230-260 °C | 90-110 °C | 40-80 mm/s | 1.04 g/cm³ | 105 °C | Amorphous |

**Requirements:** Enclosure: Yes · Heated bed: Yes · Dry filament: No · Cooling fan: No · Warping: high

**Ratings (0-100):** Strength 60 · Flexibility 20 · Impact 62 · Heat 78 · UV / weather 40 · Moisture 65 · Food-safe 15 · Low odour 28 · Ease 42

**Tags:** engineering

**Good for:** Heat-exposed functional parts; Enclosures and housings; Parts you plan to sand, glue or smooth

**Strengths:**
- Good heat resistance (~100 °C)
- Tough and easy to post-process
- Acetone-smoothable to a glossy finish

**Watch-outs:**
- Warps badly without an enclosure
- Styrene fumes, so ventilate well
- Not UV-stable outdoors (use ASA)

---

### ASA
*Acrylonitrile styrene acrylate* · **Advanced**

> Essentially weatherproof ABS: the same strength and heat resistance but genuinely UV-stable, so it keeps its colour and toughness in the sun. The default for outdoor parts.

| Nozzle | Bed | Speed | Density | Glass transition | Melting point |
|---|---|---|---|---|---|
| 240-260 °C | 90-110 °C | 40-80 mm/s | 1.07 g/cm³ | 100 °C | Amorphous |

**Requirements:** Enclosure: Yes · Heated bed: Yes · Dry filament: Yes · Cooling fan: No · Warping: high

**Ratings (0-100):** Strength 60 · Flexibility 20 · Impact 60 · Heat 78 · UV / weather 92 · Moisture 72 · Food-safe 15 · Low odour 32 · Ease 44

**Tags:** outdoor-safe, engineering

**Good for:** Outdoor fittings and enclosures; Automotive and garden parts; Anything left in the sun

**Strengths:**
- Excellent UV and weather resistance
- ABS-level strength and heat resistance
- Acetone-smoothable

**Watch-outs:**
- Warps without an enclosure
- Fumes, so ventilate the workspace
- Fussier than PETG to dial in

---

### ASA-CF
*Acrylonitrile styrene acrylate, carbon-filled* · **Advanced**

> Carbon-reinforced ASA for outdoor engineering parts that need to stay rigid and dimensionally stable in the weather. All the demands of ASA plus a hardened nozzle.

| Nozzle | Bed | Speed | Density | Glass transition | Melting point |
|---|---|---|---|---|---|
| 250-270 °C | 90-110 °C | 30-70 mm/s | 1.11 g/cm³ | 100 °C | Amorphous |

**Requirements:** Enclosure: Yes · Heated bed: Yes · Dry filament: Yes · Cooling fan: No · Warping: medium

**Ratings (0-100):** Strength 75 · Flexibility 12 · Impact 55 · Heat 80 · UV / weather 92 · Moisture 72 · Food-safe 12 · Low odour 32 · Ease 40

**Tags:** outdoor-safe, engineering

**Good for:** Outdoor brackets and housings; Automotive exterior parts; Weatherproof structural fixtures

**Strengths:**
- Weatherproof and rigid
- Lower warping than plain ASA
- Stable in sun and heat

**Watch-outs:**
- Needs an enclosure and hardened nozzle
- Fumes on printing
- More brittle than plain ASA

---

### TPU (95A)
*Thermoplastic polyurethane* · **Intermediate**

> A rubber-like flexible filament that bends, stretches and springs back. Prints on most machines if you slow right down; a direct-drive extruder makes it far easier.

| Nozzle | Bed | Speed | Density | Glass transition | Melting point |
|---|---|---|---|---|---|
| 210-235 °C | 30-60 °C | 15-40 mm/s | 1.21 g/cm³ | -35 °C | Amorphous |

**Requirements:** Enclosure: No · Heated bed: Yes · Dry filament: Yes · Cooling fan: Yes · Warping: low

**Ratings (0-100):** Strength 40 · Flexibility 95 · Impact 90 · Heat 35 · UV / weather 45 · Moisture 70 · Food-safe 20 · Low odour 78 · Ease 46

**Tags:** flexible

**Good for:** Phone cases and bumpers; Gaskets, seals and grips; Shoe soles and wearables

**Strengths:**
- Genuinely flexible and springy
- Superb impact and tear resistance
- Grippy, rubber-like feel

**Watch-outs:**
- Must print slowly
- Bowden setups struggle, so prefer direct drive
- Stringy; dry the filament first

---

### TPE
*Thermoplastic elastomer* · **Advanced**

> Softer and stretchier than TPU, closer to real rubber. That softness makes it the trickiest flexible to feed, so it needs a slow, well-tuned direct-drive setup.

| Nozzle | Bed | Speed | Density | Glass transition | Melting point |
|---|---|---|---|---|---|
| 210-235 °C | 30-55 °C | 10-25 mm/s | 1.2 g/cm³ | -40 °C | Amorphous |

**Requirements:** Enclosure: No · Heated bed: Yes · Dry filament: Yes · Cooling fan: Yes · Warping: low

**Ratings (0-100):** Strength 32 · Flexibility 98 · Impact 88 · Heat 35 · UV / weather 45 · Moisture 70 · Food-safe 20 · Low odour 76 · Ease 32

**Tags:** flexible

**Good for:** Soft-touch grips and pads; Rubber-like seals; Wearable and cushioning parts

**Strengths:**
- Very soft, very stretchy
- Excellent vibration damping
- Rubbery, tactile finish

**Watch-outs:**
- Hardest flexible to feed reliably
- Very slow printing
- Direct drive essentially required

---

### Nylon (PA)
*Polyamide* · **Advanced**

> A tough, wear-resistant engineering plastic with a bit of natural flex, excellent for gears, hinges and living parts. Its weakness is water: it drinks moisture and must be printed bone-dry.

| Nozzle | Bed | Speed | Density | Glass transition | Melting point |
|---|---|---|---|---|---|
| 240-270 °C | 70-90 °C | 30-70 mm/s | 1.14 g/cm³ | 50 °C | 220 °C |

**Requirements:** Enclosure: Yes · Heated bed: Yes · Dry filament: Yes · Cooling fan: No · Warping: high

**Ratings (0-100):** Strength 78 · Flexibility 42 · Impact 88 · Heat 72 · UV / weather 40 · Moisture 30 · Food-safe 15 · Low odour 60 · Ease 30

**Tags:** engineering

**Good for:** Gears, bushings and bearings; Living hinges and clips; High-wear mechanical parts

**Strengths:**
- Tough, wear-resistant and self-lubricating
- Handles heat and repeated stress
- Natural flex resists shattering

**Watch-outs:**
- Extremely hygroscopic, so dry and keep dry
- Warps; wants an enclosure
- Poor moisture resistance in use

---

### PA-CF (Nylon-CF)
*Polyamide, carbon-filled* · **Advanced**

> Carbon-fibre nylon, one of the strongest and stiffest desktop materials, with near-aluminium rigidity at a fraction of the weight. Demanding: high heat, a dry box and a hardened nozzle.

| Nozzle | Bed | Speed | Density | Glass transition | Melting point |
|---|---|---|---|---|---|
| 260-300 °C | 50-90 °C | 30-60 mm/s | 1.16 g/cm³ | 60 °C | 220 °C |

**Requirements:** Enclosure: Yes · Heated bed: Yes · Dry filament: Yes · Cooling fan: No · Warping: medium

**Ratings (0-100):** Strength 92 · Flexibility 18 · Impact 80 · Heat 82 · UV / weather 45 · Moisture 35 · Food-safe 12 · Low odour 60 · Ease 26

**Tags:** engineering

**Good for:** Drone and RC structural frames; End-use industrial brackets; Tooling and jigs under load

**Strengths:**
- Outstanding strength-to-weight
- Very stiff and dimensionally stable
- Good heat resistance

**Watch-outs:**
- Needs a hardened nozzle and high temps
- Must be kept dry
- One of the harder materials to master

---

### Polycarbonate (PC)
*Polycarbonate* · **Advanced**

> The toughness and heat-resistance champion of common filaments: impact-resistant and usable near boiling temperatures. It prints hot, warps hard and needs a proper enclosure.

| Nozzle | Bed | Speed | Density | Glass transition | Melting point |
|---|---|---|---|---|---|
| 260-300 °C | 100-120 °C | 25-60 mm/s | 1.2 g/cm³ | 145 °C | Amorphous |

**Requirements:** Enclosure: Yes · Heated bed: Yes · Dry filament: Yes · Cooling fan: No · Warping: high

**Ratings (0-100):** Strength 85 · Flexibility 22 · Impact 82 · Heat 92 · UV / weather 45 · Moisture 55 · Food-safe 15 · Low odour 45 · Ease 24

**Tags:** engineering

**Good for:** High-heat functional parts; Impact-resistant guards and mounts; Near-clear structural pieces

**Strengths:**
- Exceptional impact strength
- Handles ~110 °C+ heat
- Can be nearly transparent

**Watch-outs:**
- Needs very high temps and an enclosure
- Warps aggressively
- Must be dried before printing

---

### PC-ABS
*Polycarbonate / ABS blend* · **Advanced**

> A blend that trades a little of PC heat resistance for ABS-like printability. A practical middle ground when you want more toughness and heat than ABS but PC is a handful.

| Nozzle | Bed | Speed | Density | Glass transition | Melting point |
|---|---|---|---|---|---|
| 250-275 °C | 90-110 °C | 30-70 mm/s | 1.1 g/cm³ | 125 °C | Amorphous |

**Requirements:** Enclosure: Yes · Heated bed: Yes · Dry filament: Yes · Cooling fan: No · Warping: high

**Ratings (0-100):** Strength 72 · Flexibility 22 · Impact 78 · Heat 82 · UV / weather 40 · Moisture 60 · Food-safe 12 · Low odour 35 · Ease 38

**Tags:** engineering

**Good for:** Automotive and electronics housings; Heat-exposed tough parts; Functional parts needing impact and heat

**Strengths:**
- Tougher and more heat-resistant than ABS
- Easier to print than pure PC
- Good surface finish

**Watch-outs:**
- Still needs an enclosure
- Warps and fumes like ABS
- Dry before printing

---

### HIPS
*High-impact polystyrene* · **Intermediate**

> Light and easy to sand, but its real job is a dissolvable support for ABS: it melts away in limonene, leaving clean overhangs. Prints much like ABS and wants the same enclosure.

| Nozzle | Bed | Speed | Density | Glass transition | Melting point |
|---|---|---|---|---|---|
| 230-245 °C | 90-110 °C | 40-80 mm/s | 1.05 g/cm³ | 100 °C | Amorphous |

**Requirements:** Enclosure: Yes · Heated bed: Yes · Dry filament: No · Cooling fan: No · Warping: medium

**Ratings (0-100):** Strength 45 · Flexibility 18 · Impact 55 · Heat 70 · UV / weather 30 · Moisture 55 · Food-safe 12 · Low odour 40 · Ease 55

**Good for:** Dissolvable supports for ABS; Lightweight sandable models; Cosplay and prop bases

**Strengths:**
- Dissolves in limonene for clean supports
- Light and easy to sand
- Cheaper than most engineering plastics

**Watch-outs:**
- Needs an enclosure like ABS
- Weak on its own
- Limonene handling and ventilation

---

### PVA
*Polyvinyl alcohol* · **Advanced**

> A support material that simply dissolves in tap water, giving perfect overhangs and internal cavities on PLA and PETG prints. Extremely thirsty for moisture, so it lives in a dry box.

| Nozzle | Bed | Speed | Density | Glass transition | Melting point |
|---|---|---|---|---|---|
| 190-220 °C | 45-60 °C | 30-60 mm/s | 1.23 g/cm³ | 45 °C | Amorphous |

**Requirements:** Enclosure: No · Heated bed: Yes · Dry filament: Yes · Cooling fan: Yes · Warping: low

**Ratings (0-100):** Strength 35 · Flexibility 20 · Impact 25 · Heat 25 · UV / weather 20 · Moisture 5 · Food-safe 10 · Low odour 80 · Ease 45

**Good for:** Water-dissolvable supports; Complex overhangs on dual extruders; Internal cavities and channels

**Strengths:**
- Dissolves cleanly in plain water
- Great multi-material support for PLA/PETG
- No solvents needed

**Watch-outs:**
- Absorbs moisture almost instantly
- Needs a second extruder to be useful
- Expensive for what it is

---

### PVB
*Polyvinyl butyral* · **Intermediate**

> A PLA-easy filament you can vapour-smooth with isopropyl alcohol to a glassy, transparent shine, with no sanding. Ideal for see-through decorative prints and light-pipes.

| Nozzle | Bed | Speed | Density | Glass transition | Melting point |
|---|---|---|---|---|---|
| 195-220 °C | 60-75 °C | 30-70 mm/s | 1.09 g/cm³ | 65 °C | Amorphous |

**Requirements:** Enclosure: No · Heated bed: Yes · Dry filament: Yes · Cooling fan: Yes · Warping: low

**Ratings (0-100):** Strength 50 · Flexibility 20 · Impact 35 · Heat 25 · UV / weather 35 · Moisture 45 · Food-safe 12 · Low odour 82 · Ease 72

**Good for:** Transparent vases and lamps; Smoothable decorative prints; Light guides and diffusers

**Strengths:**
- IPA vapour-smooths to a glassy finish
- Prints almost as easily as PLA
- Good clarity when smoothed

**Watch-outs:**
- Absorbs moisture; keep it dry
- Modest strength and heat resistance
- Smoothing needs IPA and care

---

### Polypropylene (PP)
*Polypropylene* · **Advanced**

> Lightweight, chemically inert and endlessly fatigue-resistant, the material for living hinges and food tubs. The trade-off is bed adhesion: almost nothing sticks to it, so it warps and lifts.

| Nozzle | Bed | Speed | Density | Glass transition | Melting point |
|---|---|---|---|---|---|
| 220-250 °C | 85-100 °C | 30-70 mm/s | 0.9 g/cm³ | -10 °C | 160 °C |

**Requirements:** Enclosure: Yes · Heated bed: Yes · Dry filament: Yes · Cooling fan: Yes · Warping: high

**Ratings (0-100):** Strength 45 · Flexibility 60 · Impact 75 · Heat 55 · UV / weather 50 · Moisture 85 · Food-safe 82 · Low odour 70 · Ease 30

**Tags:** food-safe, flexible

**Good for:** Living hinges and snap-fits; Food and chemical containers; Fatigue-resistant flexing parts

**Strengths:**
- Nearly unbreakable in repeated flexing
- Chemically inert and moisture-proof
- Very light (floats in water)

**Watch-outs:**
- Notoriously hard to stick to the bed
- Warps badly; needs a PP-specific surface
- Fussy to dial in

---

### PET-CF
*Polyethylene terephthalate, carbon-filled* · **Advanced**

> Industrial-grade carbon-filled PET: high strength, high heat resistance and excellent dimensional stability for near-end-use engineering parts. Runs hot and needs a dry box and hardened nozzle.

| Nozzle | Bed | Speed | Density | Glass transition | Melting point |
|---|---|---|---|---|---|
| 260-290 °C | 80-100 °C | 30-60 mm/s | 1.3 g/cm³ | 80 °C | 255 °C |

**Requirements:** Enclosure: Yes · Heated bed: Yes · Dry filament: Yes · Cooling fan: No · Warping: medium

**Ratings (0-100):** Strength 88 · Flexibility 14 · Impact 62 · Heat 85 · UV / weather 50 · Moisture 70 · Food-safe 10 · Low odour 60 · Ease 28

**Tags:** engineering

**Good for:** Near-end-use industrial parts; High-heat structural brackets; Manufacturing jigs and tooling

**Strengths:**
- High strength and heat resistance
- Excellent dimensional stability
- Stiff with a clean matte finish

**Watch-outs:**
- Needs high temps, enclosure and dry box
- Hardened nozzle required
- Unforgiving for beginners

---

### PPS-CF
*Polyphenylene sulfide, carbon-filled* · **Advanced**

> A high-performance engineering polymer with outstanding chemical and heat resistance, aimed at demanding end-use parts. Needs a high-temperature printer with an actively heated chamber.

| Nozzle | Bed | Speed | Density | Glass transition | Melting point |
|---|---|---|---|---|---|
| 310-340 °C | 100-120 °C | 20-50 mm/s | 1.35 g/cm³ | 90 °C | 280 °C |

**Requirements:** Enclosure: Yes · Heated bed: Yes · Dry filament: Yes · Cooling fan: No · Warping: medium

**Ratings (0-100):** Strength 90 · Flexibility 16 · Impact 65 · Heat 95 · UV / weather 55 · Moisture 85 · Food-safe 10 · Low odour 55 · Ease 18

**Tags:** engineering

**Good for:** Chemical-resistant end-use parts; Under-hood automotive components; High-temperature industrial fixtures

**Strengths:**
- Excellent heat and chemical resistance
- Strong, stiff and stable
- Flame-retardant grades available

**Watch-outs:**
- Requires a high-temp printer and heated chamber
- Expensive and specialist
- Very demanding to print

---

### PEEK
*Polyether ether ketone* · **Advanced**

> The top of the desktop pyramid: a metal-replacement polymer with extreme strength, heat and chemical resistance used in aerospace and medical parts. Only a handful of specialist printers can run it.

| Nozzle | Bed | Speed | Density | Glass transition | Melting point |
|---|---|---|---|---|---|
| 360-450 °C | 120-160 °C | 20-40 mm/s | 1.3 g/cm³ | 143 °C | 343 °C |

**Requirements:** Enclosure: Yes · Heated bed: Yes · Dry filament: Yes · Cooling fan: No · Warping: high

**Ratings (0-100):** Strength 95 · Flexibility 20 · Impact 78 · Heat 98 · UV / weather 60 · Moisture 85 · Food-safe 20 · Low odour 55 · Ease 10

**Tags:** engineering

**Good for:** Aerospace and medical components; Metal-replacement end-use parts; Extreme-temperature applications

**Strengths:**
- Metal-like strength and stiffness
- Withstands very high temperatures
- Outstanding chemical resistance

**Watch-outs:**
- Needs a specialist high-temp printer
- Very expensive
- Extremely difficult to print well

---

## Sources & references

The figures here are compiled and cross-referenced from published manufacturer technical data
sheets and knowledge bases. They are typical, real-world starting points rather than values copied
from any single spec sheet, so a specific brand or spool may differ. Always defer to the datasheet
printed on your own filament.

Primary references:

- **Prusa:** Prusament technical data sheets and the Prusa Knowledge Base material guides (https://prusament.com, https://help.prusa3d.com)
- **Polymaker:** per-product technical data sheets (https://polymaker.com)
- **Bambu Lab:** filament guides and the Bambu Lab Wiki (https://wiki.bambulab.com)
- **Fillamentum:** product technical data sheets (https://fillamentum.com)

Property ratings (strength, heat, UV, and so on) are a relative 0-100 guide for comparing materials
at a glance, not laboratory measurements. Print temperatures, bed temperatures, densities and
glass-transition figures are drawn from the datasheets above.

---

_Compiled by The 3D Printing Network (https://3dprintingsa.co.za). Print settings are starting points, not guarantees; verify against your filament's datasheet before printing._
