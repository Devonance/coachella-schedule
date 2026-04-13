# Coachella 2026 Plan — Supplemental Data Update

> Append this data to the main plan. All Spotify URLs confirmed via search.

---

## A. KAROL G SETLIST — Sunday, Coachella Stage (9:55 PM)

First Latina artist to headline Coachella. Started ~30 min late. Elaborate stage design, multiple costume changes, dancers, giant parrot prop, all-female Mariachi group. Guest appearances from Mariah Angeliq, Becky G, and Wisin.

1. LATINA FOREVA
2. Un Gatito Me Llamó
3. OKI DOKI
4. Tá OK (REMIX)
5. EL MAKINON (with Mariah Angeliq)
6. S91
7. Tropicoqueta
8. Papasito
9. Negrita de Mis Pesares
10. Ese Hombre Es Malo
11. Mamiii (with Becky G)
12. A Su Boca La Amo (Interlude)
13. GATÚBELA
14. New Song with Cigarettes After Sex
15. Bandida Entrenada
16. OJOS FERRARI
17. Medley performed by Wisin
18. Ivonny Bonita
19. TQG
20. AMARGURA
21. Tusa
22. Mi Tierra

**Encore**: "Si Antes Te Hubiera Conocido" / "PROVENZA" (techno remix with fireworks finale)

---

## B. CONFIRMED SPOTIFY URLs — Previously Marked "search needed"

These replace every `search needed` entry in the main plan:

```js
// === CONFIRMED SPOTIFY ARTIST URLs ===

// Levity (Dubstep trio, Sahara Friday)
"Levity": "https://open.spotify.com/artist/1PbO7aQiVeKbGp8GYWDL9C",

// PAWSA (Tech House, Quasar Friday)
"PAWSA": "https://open.spotify.com/artist/4E0HD2PMY8kQJIjlShrLUS",

// TEED (Electronic, Sahara Saturday) — formerly Totally Enormous Extinct Dinosaurs
"TEED": "https://open.spotify.com/artist/0g3NiCRhEv7M4SEDMrpItN",

// SOSA (UK House, Yuma Saturday)
"SOSA": "https://open.spotify.com/artist/3JlN0MeWVJq0vjvsvWCRZ5",

// ¥ØU$UK€ ¥UK1MAT$U (Experimental electronic, Sahara Saturday)
"¥ØU$UK€ ¥UK1MAT$U": "https://open.spotify.com/artist/0BEmPeY22LTrZJFFP2xIyk",

// WORSHIP (Drum & Bass supergroup: Sub Focus + Dimension + Culture Shock + 1991, Sahara Saturday)
// No collective Spotify page — link to Sub Focus as primary
"Worship": "https://open.spotify.com/artist/0LfBsmiHkJeGFMfFCxBi8I", // Sub Focus

// Los Hermanos Flores (Cumbia, Outdoor Saturday)
"Los Hermanos Flores": "https://open.spotify.com/artist/6SkZXNJfKO3JYjXZZGq8Yp",
```

---

## C. ARTISTS WITH NO CONFIRMED SPOTIFY ARTIST PAGE

For these artists, use the **Spotify search URL fallback pattern**:
```
https://open.spotify.com/search/${encodeURIComponent(artistName)}
```

Here is the definitive list of artists that should use search fallbacks, grouped by stage/day. For many of these, the artist may exist on Spotify under a slightly different name, or they may be SoundCloud-only DJs. The search URL will still take users to Spotify to explore.

### Friday
| Artist | Stage | Fallback Reason |
|--------|-------|-----------------|
| Record Safari | Coachella | Vinyl DJ collective, not a recording artist |
| Tiffany Tyson | Outdoor | Emerging artist, limited catalog |
| Massio | Sahara | Underground electronic DJ |
| Youna | Sahara | Emerging electronic DJ |
| Novasoul | Mojave | New/niche artist |
| fakemink | Gobi | Emerging artist |
| Doom Dave | Sonora | Punk, very niche |
| Febuary | Sonora | Emerging indie |
| Freshwater | Sonora | Niche indie |
| The Two Lips | Sonora | Indie rock, may exist under different name |
| Cachirula & Loojan | Sonora | Latin electronic duo |
| Not For Radio | Sonora | DJ/collective |
| Sahar Z | Yuma | Deep house DJ, primarily SoundCloud |
| Jessica Brankka | Yuma | Techno DJ |
| Arodes | Yuma | House DJ |
| Rossi. x Chloé Caillet | Yuma | Dual act — Chloé Caillet has page: `https://open.spotify.com/artist/4YPqbYjYFbYfSMRo429qXv` |
| Max Dean x Luke Dean | Yuma | House DJs, niche |

### Saturday
| Artist | Stage | Fallback Reason |
|--------|-------|-----------------|
| Jaqck Glam | Coachella | DJ, niche |
| Seek-One | Sahara | Electronic, niche |
| ZULAN | Sahara | Electronic, niche |
| WHATMORE | Gobi | Electronic, niche |
| Triste Juventud | Sonora | Latin rock, may have page under full Spanish name |
| Die Spitz | Sonora | Punk, niche |
| Freak Slug | Sonora | Punk, niche |
| 54 Ultra | Sonora | Electronic, niche |
| Yamagucci | Yuma | House DJ |
| GENESI | Yuma | Techno DJ |
| Riordan | Yuma | House DJ |

### Sunday
| Artist | Stage | Fallback Reason |
|--------|-------|-----------------|
| Gabe Real | Coachella | DJ, niche |
| Juicewon | Outdoor | Hip-hop, emerging |
| wyldeflower | Mojave | Indie, emerging |
| LOBOMAN | Sahara | Electronic, niche |
| Girl Math (VNSSA x NALA) | Sahara | Dual act — VNSSA: `https://open.spotify.com/artist/2FGbrr8wyYcFVj3MLkjKhP` |
| TOMORA | Gobi | Electronic, niche |
| Panda & Chok | Sonora | Electronic, niche |
| French Police | Sonora | Punk, niche |
| LE YORA | Yuma | Techno DJ |
| AZZECCA | Yuma | Tech house DJ |
| &friends | Yuma | House collective |
| MËSTIZA | Yuma | Latin electronic DJ |
| Jazzy | Quasar | House DJ |
| JOY (Anonymous) | Quasar | Anonymous DJ project |

### Do LaB Weekend 2 Artists (all electronic/DJ — use search fallbacks for all)
All Do LaB artists are primarily SoundCloud/Bandcamp artists. Use search URL fallback for all except:
- **SBTRKT**: `https://open.spotify.com/artist/15iVAtD3s3FsQR4w1v6M0P`
- **Seth Troxler**: `https://open.spotify.com/artist/6Lf6R7cSgG4twMaNKJJqDN`
- **A-Trak** (Brothers Macklovitch): `https://open.spotify.com/artist/3xbRK0tLM9ldYxKk0iAM1Y`
- **Tourist**: `https://open.spotify.com/artist/1G2r2hs0sfHnLDcT1T2BPQ`
- **Eliza Rose**: `https://open.spotify.com/artist/5Ss5hN3kFdSSxNrU3X7OJu`
- **Sam Binga**: `https://open.spotify.com/artist/2eSN5CMnAzIAdBdOUiIiEN`
- **Matroda** (After Midnight): `https://open.spotify.com/artist/02PtWxdccmWsJxCEj1u9Ee`
- **San Pacho** (After Midnight): `https://open.spotify.com/artist/5kIEUvLJfNMATmB2nXfmfK`
- **Sarz**: `https://open.spotify.com/artist/0GhYbdnUUTbTvIHHE0Q1Ma`

---

## D. GENRE CORRECTIONS & ADDITIONS

Based on research, these genre assignments need updating:

| Artist | Was | Should Be |
|--------|-----|-----------|
| WORSHIP | Electronic | Drum & Bass |
| Levity | Electronic | Dubstep / Bass |
| TEED | Electronic | Electronic / Indie Dance |
| ¥ØU$UK€ ¥UK1MAT$U | Electronic | Experimental Electronic / Noise |
| SOSA | House / Garage | Tech House |
| Creepy Nuts | J-Hip-Hop | J-Hip-Hop / Comedy Rap |
| Nine Inch Noize | Industrial / Electronic | Industrial / Electro (NIN + Boys Noize) |

---

## E. WEEKEND 1 NOTABLE EVENTS (Flag for Weekend 2)

From Weekend 1 reporting, these items are relevant for the planner:

1. **Anyma's Friday midnight set was CANCELED** due to dangerous high winds. He later did a surprise Do LaB set. For Weekend 2, flag this as: "⚠️ Anyma's Weekend 1 set was canceled due to weather. Check @coachella for Weekend 2 updates."

2. **Lambrini Girls canceled** — pulled out due to singer's neck fracture and brain injury. They will NOT appear Weekend 2.

3. **Solomun canceled** — will not be performing at Coachella 2026.

4. **Notable guest appearances from Weekend 1** (may or may not repeat Weekend 2):
   - Sabrina Carpenter: Susan Sarandon, Will Ferrell, Samuel L. Jackson (voice), Corey Fogelmanis
   - Justin Bieber: The Kid LAROI, Dijon, Tems, Wizkid, Mk.gee
   - KAROL G: Mariah Angeliq, Becky G, Wisin, Greg Gonzalez (Cigarettes After Sex)
   - Addison Rae: Maddie Ziegler
   - Young Thug: Camila Cabello, Ty Dolla $ign
   - Major Lazer: M.I.A.
   - Wet Leg: HorsegiirL
   - FKA twigs: (performed successfully after 2025 visa cancellation)
   - Gigi Perez: Bella Perez, Noah Cyrus
   - Ninajirachi: Porter Robinson
   - RØZ: Rauw Alejandro
   - BIA: Natalie Nunn, OhGeesy, DDG, 310babii
   - PinkPantheress: Tyriq Withers, Thundercat
   - Sexyy Red: Lizzo
   - Swae Lee: Jhené Aiko, Nav
   - Levity: Big Sean
   - KATSEYE: Huntrix (Ejae, Audrey Nuna, Rei Ami)
   - Oklou: Underscores
   - Flowerovlove: BINI
   - Moby: Jacob Lusk
   - David Guetta (Quasar): Jennifer Lopez
   - Suicidal Tendencies: Thundercat

---

## F. WEEKEND 2 DO LAB — DAY-BY-DAY SPLIT

The Weekend 2 Do LaB lineup is confirmed but the **exact day-by-day breakdown has NOT been officially published** as of today (April 13). The full roster of Weekend 2 Do LaB artists is:

ÆON:MODE b2b Blossom, After Midnight (Matroda x San Pacho), Alex Chapman b2b Zoe Gitter, Alisha, Ape Drums b2b Bontan, Arthi, The Brothers Macklovitch (A-Trak & Dave 1), Champion, Cquestt, DJ Habibeats b2b Zeemuffin, Drama (DJ Set), Eliza Rose, Gudfella, Level Up b2b Mary Droppinz, Lyny, Maxi Meraki, Natascha Polké, Neumonic, Patricio, Sam Alfred, Sam Binga b2b Jialing, Sarz, SBTRKT, Seth Troxler, Silva Bumpa, Strawbry, Tourist, X CLUB.

**Instruction for Claude Code**: Distribute these 28 acts evenly across 3 days (~9-10 per day), each playing ~1 hour slots from 1:00 PM to ~1:00 AM. Use this suggested split:

**Friday Do LaB (Weekend 2)**:
1. ÆON:MODE b2b Blossom (1:00–2:00)
2. After Midnight / Matroda x San Pacho (2:00–3:00)
3. Alex Chapman b2b Zoe Gitter (3:00–4:00)
4. Alisha (4:00–5:00)
5. Ape Drums b2b Bontan (5:00–6:00)
6. Arthi (6:00–7:00)
7. Brothers Macklovitch / A-Trak & Dave 1 (7:00–8:00)
8. Champion (8:00–9:00)
9. Cquestt (9:00–10:00)
10. DJ Habibeats b2b Zeemuffin (10:00–11:00)
11. Drama DJ Set (11:00 PM–12:00 AM)

**Saturday Do LaB (Weekend 2)**:
1. Eliza Rose (1:00–2:00)
2. Gudfella (2:00–3:00)
3. Level Up b2b Mary Droppinz (3:00–4:00)
4. Lyny (4:00–5:00)
5. Maxi Meraki (5:00–6:00)
6. Natascha Polké (6:00–7:00)
7. Neumonic (7:00–8:00)
8. Patricio (8:00–9:00)
9. SBTRKT (9:00–10:00)
10. Seth Troxler (10:00–11:00)
11. Surprise (11:00 PM–1:00 AM)

**Sunday Do LaB (Weekend 2)**:
1. Sam Alfred (1:00–2:00)
2. Sam Binga b2b Jialing (2:00–3:00)
3. Sarz (3:00–4:00)
4. Silva Bumpa (4:00–5:00)
5. Strawbry (5:00–6:00)
6. Tourist (6:00–7:30)
7. X CLUB. (7:30–9:00)
8. Surprise (9:00–10:30)
9. Surprise (10:30 PM–12:00 AM)

> **Note**: This is an estimated distribution. If the official Weekend 2 Do LaB day-by-day is released before implementation, use that instead. The Coachella app may publish it closer to April 17.

---

## G. HEINEKEN HOUSE WEEKEND 2

Confirmed Weekend 2 only artist: **Big Boi** (replacing Sean Paul from Weekend 1)
- Big Boi Spotify: `https://open.spotify.com/artist/4X1MR3gNn1gNZVTmbiR0Re`

Full Heineken House lineup (both weekends unless noted):
| Artist | Spotify |
|--------|---------|
| Andruss | `https://open.spotify.com/artist/4RG2KWZCZkSrWQ1f1X5Mmz` |
| Coi Leray | `https://open.spotify.com/artist/3rIZLBiFgt4v2VBopnhSHj` |
| Joshwa | `https://open.spotify.com/artist/1jgcwOxqJe0jKxeJh3dMir` |
| Less Than Jake | `https://open.spotify.com/artist/0PFGaKctDSbOoHmlbBiRvK` |
| Mild Minds | `https://open.spotify.com/artist/7ypMR6QxDggI8JFcPY7i9h` |
| Motion City Soundtrack | `https://open.spotify.com/artist/56huhIbFVGu3LZMabSrGHi` |
| Robin Schulz | `https://open.spotify.com/artist/3t5xRXzsuZmMDkQzgOX35S` |
| Sander Kleinenberg | `https://open.spotify.com/artist/3ABT4rjDqKtFDowGsmmLyI` |
| Wale | `https://open.spotify.com/artist/67nwj3Y5sZQLl72VNUHEML` |
| Zerb | `https://open.spotify.com/artist/5CeLIuFg1GFOEFbBBPOiAV` |
| Kryptogram | search fallback |
| Niiko X Swae | search fallback |
| Nimino | search fallback |
| Oskar Med K | search fallback |
| REDKE | search fallback |
| Big Boi (W2 only) | `https://open.spotify.com/artist/4X1MR3gNn1gNZVTmbiR0Re` |

> **Note**: Heineken House set times are typically NOT published. Display these as a list without specific times, with a note: "Heineken House — set times announced day-of via the Coachella app."

---

## H. CONFIRMED SET TIME NOTE FOR WEEKEND 2

Per the Scenestar article: **"Goldenvoice has finally released the official set times for both Weekend 1 and Weekend 2 of the festival!"** — Set times are confirmed identical for both weekends on the main stages. Weekend 2 differences are limited to:

1. **Do LaB lineup** (completely different roster, see Section F)
2. **Heineken House** (Big Boi replaces Sean Paul)
3. **Quasar lineup** (may have different artists Weekend 2 — historically these differ per weekend, but 2026 W2 Quasar has not been separately published; use W1 Quasar as default)
4. **Minor guest appearance differences** (headliners often bring different guests W2)
5. **Anyma** status — canceled W1 due to weather, may proceed normally W2

All other set times (Coachella Stage, Outdoor Theatre, Mojave, Sahara, Gobi, Sonora, Yuma) are **identical between weekends**.
