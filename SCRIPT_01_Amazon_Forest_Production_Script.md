# SCRIPT 01 — அமேசன் காடு: The Forest That Keeps Its Secrets
### [TEMPLATE v3 — Google Flow only · 8s scenes · subject sheets → environment plates → per-scene reference image → per-scene video · global lock appended to every prompt · no on-screen text · consistent visible faces · BGM + diegetic SFX only]

**Duration:** 6:54 (matches the timestamped voice-over file) | **Total Scenes:** 52 (8s each, final scene trimmed to 6s to land at 6:54)
**Image generation:** Google Flow only (Step 1 subject sheets, Step 2 environment plates, Step 3 scene reference images)
**Video generation:** Google Flow — one video prompt per scene, built from that scene's saved reference image, each carrying its own sound design
**Payoff:** The camera rises from one lone survivor to the endless living canopy, so the viewer feels how many untold stories still hide in the forest, then ends on a night sky and one last firefly.
**Dialogue/Audio rule:** The generated clips contain NO voice of any kind: only instrumental BGM and diegetic SFX. Your recorded Tamil voice-over ("AMAZON FINAL VOICE", 6:54) is added in the edit; every scene is timed to its spoken lines.

**Assumptions made for the blank input fields (change if needed):**
- **Style:** photorealistic cinematic documentary, 35mm anamorphic look.
- **Subjects:** the ones in Step 1.
- **Hard rules:** no on-screen text. Human characters have clear, fully rendered faces that stay identical across every scene (invented fictional faces, not likenesses of real people). No gore or violence on screen, only implied.
- **Real people:** the figures are fictional characters inspired by the events, with invented faces, not likenesses of real individuals.

**Segment map (Step 0 math: 6:54 = 414 s ÷ 8 = 51.75 → 52 scenes)**

| # | Segment | Scenes | Time |
|---|---|---|---|
| 1 | Hook | S001–S007 | 0:00–0:56 |
| 2 | Tanaru — The Man of the Hole | S008–S011 | 0:56–1:28 |
| 3 | Tanaru — The Lone Survivor | S012–S019 | 1:28–2:32 |
| 4 | The Pattern & Fawcett — The Obsession | S020–S023 | 2:32–3:04 |
| 5 | Fawcett — The Vanishing | S024–S028 | 3:04–3:44 |
| 6 | The River's Hidden Dangers | S029–S035 | 3:44–4:40 |
| 7 | The Rubber Tapper's Voice | S036–S039 | 4:40–5:12 |
| 8 | The Sacrifice & Legacy | S040–S042 | 5:12–5:36 |
| 9 | The Danger That Continues | S043–S048 | 5:36–6:24 |
| 10 | Final Wide / Outro | S049–S052 | 6:24–6:54 |

---

## ⚠️ GLOBAL LOCK BLOCK — append this in full to the END of every single prompt below (Step 1, Step 2, every Step 3, every Step 4)

```
GLOBAL LOCK:
CONTINUITY — Keep Tanaru-Man, Z-Party Explorers, Seringueiro Rubber Tapper, Scarlet-1 Macaw, Sucuri-Titan Anaconda, Red-Belly Piranha, Needle-Fish Candiru, Sky-Eye Survey Drone and Iron-Reaper Bulldozer (including faces, hair and skin tone) in exact color/decal/proportion continuity from their saved reference sheets — no redesign, recolor, or scale drift. Keep every environment identical to its saved environment plate.
STYLE — Photorealistic cinematic documentary, 35mm anamorphic lens look, shallow depth of field on close shots, natural film grain, rich but natural color grade (deep emerald greens, warm amber light shafts, muted earth tones). Real material physics: wet leaves glisten, mud clumps, smoke diffuses, water refracts, wood grain and rust stay stable.
HARD RULES — No on-screen text, captions, logos or watermarks. Human characters have clear, natural, fully visible faces (realistic skin texture, eyes, expressions) that match their saved reference sheets exactly in every shot; these are invented fictional faces, not likenesses of any real person. Faces never morph, age, or change between shots. No gore, no visible violence, no weapons pointed at a person: danger is shown by aftermath, shadow, sound and the reaction of people, animals and objects. Historic and tragic events are implied through symbolic imagery (empty hammock, quiet clearing, dropped hat, shafts of light) and grief or fear on faces, never re-enacted.
ZERO AI ARTIFACTS — No morphing, warping, melting, flicker, extra or duplicated limbs/parts, floating debris, texture smearing, plastic skin or fur, inconsistent shadows, distorted hands or anatomy.
LIGHTING — Continuity of time-of-day per setting: rainforest = filtered green daylight with amber shafts; Tanaru = golden dusk; 1925 expedition = misty warm morning; river = bright overcast day; rubber trail = dawn; deforestation = smoky orange dusk; closing = night with stars and fireflies. No sudden light jumps between consecutive shots unless the script beat is a deliberate flash-cut.
AUDIO — Generated audio is ONLY instrumental cinematic BGM plus diegetic SFX (wind, water, birds, footsteps, fire, machines). Absolutely no dialogue, no voice-over, no narration, no speech in any language, no whispering, no humming, no singing, no chanting, no crowd voices; people never speak and their mouths stay closed. Any quoted or timing text in the prompt is a camera/timing cue, never spoken words.
CAMERA — Smooth, physically plausible motion only; each shot's opening camera motion matches the previous shot's closing motion vector for a seamless cut.
```

---

# STEP 1 — SUBJECT REFERENCE IMAGES (Google Flow — image generation ONLY)

### 1A. Lone Forest Dweller ("Tanaru-Man")
**Portrait Image Prompt — Google Flow:**
Full-body standing portrait of a lean, weathered indigenous man in his 50s from an uncontacted Amazon community, facing the camera in a neutral relaxed pose, with a clearly visible, dignified, fully detailed face: deep-set dark brown eyes, high cheekbones, a strong nose, deep lines around the eyes and mouth, short straight black hair with streaks of grey, and a thin stripe of red urucum (annatto) pigment across each cheek; his expression is calm, watchful and quietly sorrowful. Bare torso with faint red pigment on the upper arms, plain woven cotton waist cord and short loincloth, a straight hand-carved wooden bow about 1.5 m long with fibre string in his left hand, and three cane arrows with feather fletching in a woven-fibre quiver on his back. Skin shows realistic sun-weathered texture and old scars. Camera at eye level, soft grey studio-style background, warm key light from the upper left, macro-level detail on the face, fibre weave, feather barbs and skin texture. An invented fictional face, respectful and dignified. Locked reference design.
**Save as:** `TanaruMan_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `TanaruMan_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT (face fully visible, identical to the portrait), REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE (feet and ground contact view), neutral grey background, matched lighting/scale, neutral pose in every panel. Add a second row of three close-up face panels (front, left profile, right profile) locking the face.
**Save as:** `TanaruMan_6Angle.png`
**Usage note:** Attach both files to every scene where this subject appears: S008–S009, S013–S015, S017–S018, S048.

### 1B. 1925 Expedition Party ("Z-Party Explorers")
**Portrait Image Prompt — Google Flow:**
Group portrait of three 1920s British explorers standing in a line facing the camera, each with a clearly visible, fully detailed face: a tall lean older colonel in the centre (long angular face, deep sun-weathered lines, grey moustache, pale blue eyes, short grey hair, stern and determined) wearing a waxed-canvas khaki jacket, riding breeches, leather puttees, a wide-brim pith sun helmet and carrying a leather map case; a young man on his left (clean-shaven, freckled, hazel eyes, tousled brown hair, eager expression) in a similar khaki outfit with a canvas rucksack and a rolled bedroll; a companion on his right (round face, dark stubble, brown eyes, calm expression) with a slouch hat, a brass compass at his belt and a machete in a leather sheath. Worn, sweat-stained fabrics, brass buckles, cracked leather. Grey neutral background, soft key light from upper left, macro detail on faces, stitching, brass patina and leather grain. Invented fictional faces. Locked reference design.
**Save as:** `Explorers_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Explorers_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround of the same three-man group: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE (boots and ground), neutral grey background, matched lighting/scale, neutral pose in every panel.
**Save as:** `Explorers_6Angle.png`
**Usage note:** Attach both files to every scene where this subject appears: S021–S025.

### 1C. Rubber Tapper ("Seringueiro")
**Portrait Image Prompt — Google Flow:**
Full-body portrait of a Brazilian rubber tapper (seringueiro) in his 40s, facing the camera in a relaxed pose, with a clearly visible, fully detailed face: warm brown skin, short black hair, a neat dark moustache, kind dark eyes with laugh lines, a sweat-lined forehead and a thoughtful, determined expression, with the wide straw hat pushed back so the face is lit. Faded blue cotton shirt with rolled sleeves, worn brown trousers, rubber boots, a small curved tapping knife at his belt, a tin cup and a canvas shoulder bag, a headlamp on the hat brim. Realistic sun-worn fabric, mud on boots, latex stains on the sleeves. Grey background, warm key light from upper right, macro detail on the face, straw weave and latex-stained cloth. An invented fictional face. Locked reference design.
**Save as:** `Tapper_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Tapper_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT (face fully visible, identical to the portrait), REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE (boots and ground contact), neutral grey background, matched lighting/scale, neutral pose in every panel. Add a second row of three close-up face panels (front, left profile, right profile) locking the face.
**Save as:** `Tapper_6Angle.png`
**Usage note:** Attach both files to every scene where this subject appears: S030, S036–S041.

### 1D. Scarlet Macaw ("Scarlet-1")
**Portrait Image Prompt — Google Flow:**
A single adult scarlet macaw perched on a natural branch, 85 cm long, vivid scarlet body, yellow-and-blue wing coverts, blue tail-feather tips, pale bare face patch, dark curved beak. Side-profile view, sharp macro-level feather barb detail, grey neutral background, soft key light from the upper left. Locked reference design.
**Save as:** `Macaw_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Macaw_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral grey background, matched lighting/scale, perched pose in every panel with wings folded.
**Save as:** `Macaw_6Angle.png`
**Usage note:** Attach both files to every scene where this subject appears: S018, S049.

### 1E. Green Anaconda ("Sucuri-Titan")
**Portrait Image Prompt — Google Flow:**
A giant green anaconda, 5.5 m long, thick as a man's thigh, olive-green skin with rounded black blotches in two alternating rows, a dark stripe behind the eye, yellow-cream belly edge, coiled loosely in a S-curve on a neutral surface. Wet glossy scales with realistic per-scale detail. Camera at three-quarter high angle, grey background, soft key light upper left, macro detail on scale texture and the amber eye with a vertical pupil. Locked reference design.
**Save as:** `Anaconda_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Anaconda_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT (head-on), REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE (belly scales), neutral grey background, matched lighting/scale, same loose S-coil pose in every panel.
**Save as:** `Anaconda_6Angle.png`
**Usage note:** Attach both files to every scene where this subject appears: S033–S034.

### 1F. Red-Bellied Piranha ("Red-Belly Piranha")
**Portrait Image Prompt — Google Flow:**
A single adult red-bellied piranha, 25 cm, silver-grey flanks with darker speckles, deep red-orange belly and gill area, a blunt head with an underbite and a row of triangular razor teeth, forked tail edged in black. Side profile, mid-water pose, neutral grey gradient background as if photographed in a tank, key light upper left, macro detail on scales and teeth. Locked reference design.
**Save as:** `Piranha_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Piranha_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT (open-mouth teeth view), REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral grey background, matched lighting/scale, neutral swimming pose in every panel.
**Save as:** `Piranha_6Angle.png`
**Usage note:** Attach both files to every scene where this subject appears: S031–S032.

### 1G. Candiru ("Needle-Fish")
**Portrait Image Prompt — Google Flow:**
A tiny translucent candiru catfish, 4 cm long, eel-like slender body, near-transparent pinkish-grey skin with a visible spine, small barbels, backward-pointing gill spines, shown in extreme macro, side profile, floating in clear water against a neutral grey-blue background, key light upper left, crisp macro detail. Locked reference design.
**Save as:** `Candiru_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Candiru_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral grey background, matched lighting/scale, neutral pose in every panel.
**Save as:** `Candiru_6Angle.png`
**Usage note:** Attach both files to every scene where this subject appears: S029–S030.

### 1H. Survey Drone ("Sky-Eye")
**Portrait Image Prompt — Google Flow:**
A small white fixed-wing survey drone with a 1.8 m wingspan, matte white fuselage, slim swept wings, a rear pusher propeller, a small camera gimbal pod under the nose, a thin dark-grey antenna, no text or logos anywhere. Displayed on a neutral grey surface, three-quarter front view, key light upper left, macro detail on carbon-fibre panel seams and the propeller. Locked reference design.
**Save as:** `Drone_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Drone_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral grey background, matched lighting/scale, neutral pose in every panel.
**Save as:** `Drone_6Angle.png`
**Usage note:** Attach both files to every scene where this subject appears: S043.

### 1I. Logging Bulldozer ("Iron-Reaper")
**Portrait Image Prompt — Google Flow:**
A heavy yellow crawler bulldozer, 1:1 scale, mud-caked steel tracks, a wide front blade with worn edge, a rear ripper claw, a cab with a dark tinted windshield (no operator visible), a black vertical exhaust stack, dusty red-earth splatter over the yellow paint, no brand names or logos. Three-quarter front view on a neutral grey surface, key light upper left, macro detail on track links, hydraulic rams and paint chips. Locked reference design.
**Save as:** `Bulldozer_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Bulldozer_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral grey background, matched lighting/scale, neutral pose in every panel.
**Save as:** `Bulldozer_6Angle.png`
**Usage note:** Attach both files to every scene where this subject appears: S012, S046.

---

# STEP 2 — ENVIRONMENT REFERENCE IMAGES (Google Flow — image generation ONLY)

### 2A. Setting A — Primary Rainforest Interior (green gloom, daytime)
**Environment Image Prompt — Google Flow:**
Wide interior view of dense primary Amazon rainforest at midday: towering buttressed trunks, hanging lianas, layered canopy so thick that only a few thin amber shafts of light reach the leaf-litter floor, mist between trunks, giant ferns, mossy fallen logs, wet leaves and fungi. Deep emerald green tones. Completely empty of humans, animals and machines — pure environment plate.
**Save as:** `SettingA_Env.png`
**Usage note:** S004, S014, S026–S028, S045.

### 2B. Setting B — Tanaru Clearing & Palm-Thatch Hut (golden dusk)
**Environment Image Prompt — Google Flow:**
A small forest clearing at golden dusk with a simple open-fronted palm-thatch hut (visible earthen floor, an empty woven hammock hung between two poles, a cold fire pit, a few clay pots), several deep round pits dug into the red earth around the clearing edge, scattered banana plants, a jungle wall behind. Warm amber low sun rays through haze. Completely empty of any people or animals — pure environment plate.
**Save as:** `SettingB_Env.png`
**Usage note:** S008–S011, S013, S015–S019, S048.

### 2C. Setting C — 1925 Expedition River-Camp & Jungle Trail (misty warm morning)
**Environment Image Prompt — Google Flow:**
A narrow muddy jungle trail beside a slow tributary at early morning, warm pink-gold light in the mist, a small abandoned camp with a canvas tent, a wooden supply crate, a folded canvas tarpaulin and an unlit lantern, tall trees framing the trail, vines. Completely empty of people — pure environment plate.
**Save as:** `SettingC_Env.png`
**Usage note:** S021–S025.

### 2D. Setting D — Amazon River & Underwater Shallows (bright overcast)
**Environment Image Prompt — Google Flow:**
A wide brown-tea Amazon tributary under bright overcast light, a sandy bank with half-submerged roots and flooded trees, floating lily pads and driftwood. Include a matching underwater view: murky tea-brown shallow water with drifting sunlit particles, submerged roots and sand. Completely empty of animals and people — pure environment plate.
**Save as:** `SettingD_Env.png`
**Usage note:** S029–S035.

### 2E. Setting E — Rubber-Tapping Trail (dawn)
**Environment Image Prompt — Google Flow:**
A narrow forest trail at dawn lined with rubber trees carrying diagonal cut scars and small tin cups collecting white latex, low mist, soft gold rim light through the trunks, mud path, dew on leaves. Completely empty of people — pure environment plate.
**Save as:** `SettingE_Env.png`
**Usage note:** S036–S038.

### 2F. Setting F — Wooden Rural House Backyard (dusk)
**Environment Image Prompt — Google Flow:**
The back yard of a simple wooden stilt house at blue-hour dusk, a wooden porch with a hanging towel, a clothesline, a water barrel, a dirt yard, and a dark treeline behind; a single warm light glows from a window. Quiet, ominous stillness. Completely empty of people — pure environment plate.
**Save as:** `SettingF_Env.png`
**Usage note:** S039–S041.

### 2G. Setting G — Aerial Canopy at Dawn with Forest-Edge Frontier
**Environment Image Prompt — Google Flow:**
High aerial view of an endless emerald Amazon canopy at dawn with rolling mist. On the right side of the frame the canopy ends abruptly at a line of cleared brown pasture and thin roads. One tiny clearing with a thin thread of smoke sits deep in the canopy. Completely empty of vehicles, drones, animals and people — pure environment plate.
**Save as:** `SettingG_Env.png`
**Usage note:** S001–S003, S005–S007, S020, S042–S044, S047, S049–S050.

### 2H. Setting H — Deforestation Frontier (smoky orange dusk)
**Environment Image Prompt — Google Flow:**
A burned and cleared forest frontier at smoky orange dusk: charred stumps, glowing embers, fresh red earth, a bulldozer-cut road, fallen giant trunks, smoke columns rising into a hazy sun, an intact wall of forest at the edge. Completely empty of humans, animals and machines — pure environment plate.
**Save as:** `SettingH_Env.png`
**Usage note:** S012, S046.

### 2I. Setting I — Night Forest with Stars & Fireflies
**Environment Image Prompt — Google Flow:**
A quiet forest clearing at night, a huge starry sky, Milky Way overhead, a black silhouette treeline, hundreds of soft-glowing fireflies among the ferns, a faint river mist. Completely empty of humans, animals and machines — pure environment plate.
**Save as:** `SettingI_Env.png`
**Usage note:** S051–S052.

---

# STEP 3 & STEP 4 — SCENES (re-timed to the voice-over timestamps)

**How each scene is shaped:**
Header line (scene number, label, timestamp) → **VO sync** (editor note only, never paste into Flow: the spoken lines and their timestamps that fall inside this scene) → Step 3 Ingredients → Step 3 Reference Image Prompt → Step 4 Ingredients → Video Prompt (with in-clip second marks, where `0s` = the scene's start time) → Sound → Cut→ to the next scene.
Append the GLOBAL LOCK BLOCK to the end of every Step 3 and Step 4 prompt.

---

### Segment 1 — Hook (Scenes 1–7)

**S001 — Endless canopy, silent intro | 0:00–0:08**
VO sync: (0:00–0:07) audio-file intro credit, no narration → keep BGM only · (0:07) "வணக்கம்"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: `SettingG_Env.png` · Scene Continuity Reference: none (first scene in the series)
Step 3 — Reference Image Prompt (Google Flow):
Ultra-wide drone-style aerial shot at dawn over an endless emerald Amazon canopy, thick mist rolling between the treetops, a pale gold sun on the horizon, an enormous sense of scale with no roads or buildings in the foreground.
Save as: `S001_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S001_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S001_Ref.png`. 0–6s: the camera glides slowly forward over the canopy, mist curling around the treetops, the sun edging up; a flock of distant parrots crosses far below. 6–8s: the motion eases, the sun clears the horizon and the light warms, ready for the narrator's first word at 7s. Slow, majestic, no cuts. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): Deep low string drone and distant war-drum heartbeat fade in; wind rush, birdsong, a distant howler-monkey call; the music dips slightly at 7s to open space for the voice.
Cut→S002: Hard cut, continuing the same forward glide.

**S002 — A place man cannot fully understand | 0:08–0:16**
VO sync: (0:09) "இன்று நாம என்ன பார்க்கப் போறோம்னா" · (0:10) "இந்த உலகத்தில இருக்குற காடுகள்ல" · (0:12) "மனிதனே இன்னும் முழுசா புரிஞ்சுக்க முடியாத" · (0:15) "ஒரு இடம் இருக்கு"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: `SettingG_Env.png` · Scene Continuity Reference: `S001_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Very high aerial view of the canopy stretching to the curved horizon in gold dawn light, thin mist banks drifting across it, a few emerald hills rising from the green sea, no roads or people.
Save as: `S002_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S002_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S002_Ref.png`. 0–4s: the camera rises slowly and tilts up so the forest seems to widen to the horizon; 4–8s: mist banks thicken and drift across the canopy, so parts of the forest vanish behind them; the last second holds on one dark mist-hidden valley. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): Music thins to a sustained cello note with a hint of mystery; wind, distant birds, a low resonance as the mist thickens at 4s.
Cut→S003: Match cut on the mist-hidden valley, continuing the descent.

**S003 — "Amazon forest" | 0:16–0:24**
VO sync: (0:16) "அது எது தெரியுமா" · (0:17) "அமேசான் காடு" · (0:18) "இந்த காடு எவ்வளவு பெரிசுன்னா" · (0:19) "இதில ஒரு பகுதிக்குள்ள போனா" · (0:21) "உங்களுக்கு ஜீபிஎஸ் சிக்னலே கிடைக்காது" · (0:23) "சூரிய வெளிச்சம்"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: `SettingG_Env.png` · Scene Continuity Reference: `S002_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Aerial shot looking down at a mist-covered valley of canopy where a small dark gap opens between giant crowns, sun rays fanning over the treetops, an enormous forest with no signs of humans.
Save as: `S003_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S003_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S003_Ref.png`. 0–1s: hold; at 1s the sun flares golden over the canopy in one strong beat; 2–5s: the camera tilts down and begins a smooth dive toward the dark gap; 5–8s: it plunges through the gap between leaves and branches, and the light drops from gold to deep green as the canopy closes overhead. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): A strong orchestral hit on the sun flare at 1s; then a descending whoosh through leaves; the music turns hushed with a low drone; a faint electronic dropout crackle at 5s hinting at lost signal.
Cut→S004: Continuous dive, the camera arriving in the green gloom below.

**S004 — Sunlight never touches the ground | 0:24–0:32**
VO sync: (0:24) "கீழே தரைய தொடவே தொடாது" · (0:26) "இன்னும் சொல்லப் போனா" · (0:27) "இந்த நொடிக்கூட" · (0:28) "இந்த காட்டுக்குள்ள வெளி உலகத்தைப் பாக்காத" · (0:30) "யாருக்கும் தெரியாத மனிதர்கள்" · (0:32) "வளந்துட்டு இருக்காங்க"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: `SettingA_Env.png` · Scene Continuity Reference: `S003_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Extreme low-angle shot on the forest floor looking up a tunnel of giant trunks, a few fading amber shafts of light high above, the ground around the camera deep in green shadow with mist.
Save as: `S004_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S004_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S004_Ref.png`. 0–3s: the light shafts fade and thin out until the floor is nearly dark; 3–4s: a beat of stillness; 4–8s: the camera tilts down slowly along a trunk and glides forward between the roots; far away a very faint thread of smoke and a warm glow appear between the trunks and the shot holds on it. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): The cello note fades; dripping water, insect hum; a soft, mysterious pad rises at 4s; one distant wooden knock at 6s.
Cut→S005: Match cut on the distant glow, becoming an aerial push toward the same smoke thread.

**S005 — "This is a true story" | 0:32–0:40**
VO sync: (0:33) "ஆனா நான் இப்ப சொல்லப் போற கதை" · (0:35) "அதை விட திரில்லூட்டும்" · (0:36) "ஏனா இது கட்டுக் கதை இல்ல" · (0:38) "இது நடந்த சம்பவம்" · (0:39) "2022 வருசம் வரைக்கும்"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: `SettingG_Env.png` · Scene Continuity Reference: `S004_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Aerial view pushing in toward one tiny forest clearing with a single thin thread of smoke rising straight up in the morning mist, a palm-thatch roof just visible, no people visible.
Save as: `S005_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S005_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S005_Ref.png`. 0–4s: the camera pushes in slowly toward the clearing as the mist parts; 4–6s: the shot sharpens and the smoke thread becomes crisp; 6–8s: the camera settles over the thatched roof and holds steady on it. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): A suspense bed with a low pulsing synth; the pulse tightens at 4s; a single struck low note at 7s.
Cut→S006: Hard cut to a wider aerial that pulls away from the clearing.

**S006 — A warning on the horizon | 0:40–0:48**
VO sync: (0:42) "நடந்துக்கிட்டே இருந்தது" · (0:43) "இந்த வீடியோவை கடைசி வரைக்கும் பாருங்க" · (0:45) "ஏனா கடைசி பகுதில சொல்ற உண்மை" · (0:47) "இன்னைக்கும் அமேசான் காட்டுக்குள்ள"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: `SettingG_Env.png` · Scene Continuity Reference: `S005_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Wide aerial view at dawn from above the clearing, the smoke thread small in the middle of an endless canopy, and far on the horizon a faint band of dark smoke and an orange glow beginning to show.
Save as: `S006_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S006_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S006_Ref.png`. 0–3s: the camera pulls back and rises smoothly, the clearing shrinking below; 3–6s: the horizon smoke thickens and the orange glow grows brighter, foreshadowing a danger to come; 6–8s: the camera holds a high wide, the smoke still rising. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): The pulse continues under an ominous low brass note that rises at 4s; wind, distant faint crackle of fire at 6s.
Cut→S007: Cross-dissolve into a new aerial descending toward a green forest island.

**S007 — Tanaru | 0:48–0:56**
VO sync: (0:48) "நடந்துக்கிட்டு இருக்குற" · (0:50) "ஒரு ஆபத்தை பத்தினது" · (0:51) "பிரேசில் நாட்டுல" · (0:52) "ரொண்டோனியா மாகாணத்துல" · (0:54) "ஒரு காடு இருக்கு" · (0:55) "அதோட பேரு தனாரு"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: `SettingG_Env.png` · Scene Continuity Reference: `S006_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
High aerial view descending toward a small isolated island of dense green forest surrounded on all sides by cleared brown pasture and thin dirt roads, dawn light, the island glowing in a lone patch of sun.
Save as: `S007_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S007_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S007_Ref.png`. 0–3s: the camera glides forward over cleared pasture, the orange smoke glow still faint at the frame edge; 3–7s: it tilts down and descends toward the forest island, the sharp line where the trees stop clearly visible; 7–8s: the camera stops just above the island, the sun brightening it at 7s. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): A sombre low piano motif enters over the strings; wind and distant cattle lowing; a soft swell at 7s.
Cut→S008: Continuous descent through the canopy into the forest.

---

### Segment 2 — Tanaru: The Man of the Hole (Scenes 8–11)

**S008 — One man, alone for 26 years | 0:56–1:04**
VO sync: (0:56) "இந்த காட்டுக்குள்ள" · (0:57) "கடந்த 26 வருசமா" · (0:58) "ஒரே ஒரு மனிசன் மட்டும்" · (1:00) "தனியா வாழ்ந்திருக்கான்" · (1:01) "இவனுக்கு பேரு கிடையாது" · (1:03) "இவன் என்ன மொழி பேசுறான்னு" · (1:04) "யாருக்கும் தெரியாது"
Step 3 Ingredients: Vehicle/Subject Reference Image: `TanaruMan_Portrait.png`, `TanaruMan_6Angle.png` · Environment Reference Image: `SettingB_Env.png` · Scene Continuity Reference: `S007_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Wide shot from behind blurred foreground leaves into the golden-dusk clearing, the palm-thatch hut in the middle and the lone man standing small at its edge, his body turned partly away, his face not yet clear.
Save as: `S008_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S008_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S008_Ref.png`. 0–2s: the camera creeps forward through the foreground leaves; 2–5s: the leaves part and the camera slides closer as he stands alone, and at 4s he slowly turns so his lined, watchful face becomes clearly visible; 5–8s: the camera holds a medium shot as he looks toward the trees, calm and unspeaking. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): The piano motif continues over a soft pad; forest evening ambience; a single low string swell as the face is revealed at 4s.
Cut→S009: Hard cut to a closer shot of his face.

**S009 — "Man of the Hole" | 1:04–1:12**
VO sync: (1:05) "அவனோட கூட்டத்தைப் பத்தி" · (1:06) "எந்த பதிவும் இல்ல" · (1:08) "ஆனா இந்த உலகம் அவனை" · (1:09) "Man of the Hole" · (1:10) "அப்படின்னு கூப்பிட்டுச்சு"
Step 3 Ingredients: Vehicle/Subject Reference Image: `TanaruMan_Portrait.png`, `TanaruMan_6Angle.png` · Environment Reference Image: `SettingB_Env.png` · Scene Continuity Reference: `S008_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Close-up of the lone man's lined face in three-quarter profile, dark watchful eyes lit by golden dusk light, and in the soft-focus background a deep round pit dug into the red earth.
Save as: `S009_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S009_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S009_Ref.png`. 0–4s: a very slow push-in on his face; his eyes glance away and his expression stays sorrowful; 4–5s: a beat of stillness; 5–8s: a rack focus shifts from his face to the pit behind him and the camera holds on the dark round opening. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): The music drops to a hollow low tone; fire crackle from off-screen; at 5s a deep resonant "hole" hit with a fading echo.
Cut→S010: Match cut on the round dark pit, becoming a top-down shot of many pits.

**S010 — The deep holes | 1:12–1:20**
VO sync: (1:13) "ஏன் இந்த பேரு தெரியுமா" · (1:14) "இந்த மனிசன் காட்டுக்குள்ள" · (1:16) "ஆளுக்கு ஒரு இடத்துல" · (1:17) "ஆழமான குழிகள்" · (1:18) "தோண்டி வைச்சிருந்தான்" · (1:19) "சில குழிகள்" · (1:20) "மிருகங்களை பிடிக்குற வலைக்கு"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: `SettingB_Env.png` · Scene Continuity Reference: `S009_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Straight top-down view of the forest floor at golden dusk with a single deep round hand-dug pit in red earth in the centre, leaf-litter around it, and a line of bare footprints leading off into the trees.
Save as: `S010_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S010_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S010_Ref.png`. 0–3s: the camera rises slowly straight up from the pit; at 3s a second pit comes into view at the frame edge; 3–6s: as the camera keeps rising, further pits appear one after another across the forest floor, forming a scattered pattern; 6–8s: the camera drifts toward a pit covered with a thin lattice of branches and leaves, a trap, and holds on it. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): Slow rising strings; soil crumble, rustle of leaves; a soft percussive thud as each new pit appears; a light sting on the covered trap at 7s.
Cut→S011: Hard cut to a forward dolly at ground level.

**S011 — The empty hole inside the hut | 1:20–1:28**
VO sync: (1:22) "சில குழிகள்" · (1:23) "அவன் ஒளிஞ்சுக்குற இடத்துக்கு" · (1:24) "ஒரு வீட்டுக்குள்ளேயே" · (1:25) "ஒரு காலி குழி இருந்துச்சு" · (1:26) "அது எதுக்குன்னு" · (1:27) "இன்னைக்கும் யாருக்கும் புரியல"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: `SettingB_Env.png` · Scene Continuity Reference: `S010_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Low ground-level view along the forest floor at golden dusk toward the palm-thatch hut, a pit dug beneath a big root in the foreground, the open front of the hut glowing in the distance, no people in frame.
Save as: `S011_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S011_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S011_Ref.png`. 0–2s: the camera glides forward past the root-pit; 3–5s: it moves through the open front of the hut; 5–7s: it slows and stops over a round empty pit dug in the earthen floor, the empty hammock swaying above; 7–8s: a slow rack focus into the pit's depth. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): The music thins to a hollow held note; soft footstep-like percussion; hammock rope creak; a low sting at 5s on the pit.
Cut→S012: Hard cut to a smoky orange wide shot.

---

### Segment 3 — Tanaru: The Lone Survivor (Scenes 12–19)

**S012 — Outsiders arrive, 1970s | 1:28–1:36**
VO sync: (1:29) "இப்போ இவன் ஏன் தனியாயிருந்தான்னு தெரியுமா" · (1:31) "1970களில் ஆரம்பிச்சு" · (1:34) "நிலம் பிடிக்குற வெளியாட்கள்"
Step 3 Ingredients: Vehicle/Subject Reference Image: `Bulldozer_Portrait.png`, `Bulldozer_6Angle.png` · Environment Reference Image: `SettingH_Env.png` · Scene Continuity Reference: `S011_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Wide low-angle shot at smoky orange dusk along a red-earth road toward the forest wall, heavy smoke on the horizon, and far in the distance the small dark shape of a yellow bulldozer barely visible in the haze.
Save as: `S012_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S012_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S012_Ref.png`. 0–3s: the camera holds still on the empty road as smoke drifts; 3–5s: from 3s the bulldozer begins to emerge from the haze and grows larger as it advances; 5–8s: it rolls closer with its blade pushing soil, and the camera slowly dollies back ahead of it. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): Dark low brass drone and a slow taiko; from 3s the diesel rumble and track clank rise; wood cracking at the end.
Cut→S013: Hard cut to the emptied village clearing.

**S013 — His people destroyed | 1:36–1:44**
VO sync: (1:36) "கேட்டில் ரெஞ்சர்ஸ்" · (1:37) "லேண்ட் கிராபர்ஸ்" · (1:38) "இவனோட முழு கூட்டத்தையுமே அழிச்சுட்டாங்க" · (1:40) "அது ஒரு படுகொலை" · (1:41) "இவன் ஒருத்தன் மட்டும் தப்பிச்சிருக்கான்" · (1:43) "அதுக்கப்புறம் இவனை யாருமே நம்பல"
Step 3 Ingredients: Vehicle/Subject Reference Image: `TanaruMan_Portrait.png`, `TanaruMan_6Angle.png` · Environment Reference Image: `SettingB_Env.png` · Scene Continuity Reference: `S012_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Wide view at smoky dusk of the clearing after a tragedy: several empty hammocks hanging still between poles, cold fire pits, scattered clay pots, drifting smoke, and at the edge of frame a man crouched behind a tree, only half visible, watching.
Save as: `S013_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S013_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S013_Ref.png`. 0–4s: the camera glides slowly sideways across the silent clearing, empty hammocks swaying and smoke curling over cold hearths; 4–6s: the camera stops and the man slowly steps out from behind the tree, his face visible with fear and grief; 6–8s: he looks toward the forest edge, distrustful. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): Music turns mournful with a low cello; wind, creaking hammock ropes, distant fading engine; a soft low sting at 5s.
Cut→S014: Cross-dissolve into an observer's view through leaves.

**S014 — Watched from a distance | 1:44–1:52**
VO sync: (1:45) "பிரேசில் அரசாங்கத்தோட" · (1:46) "FUNAI அப்படின்னு ஒரு துறை இருக்கு" · (1:48) "இவங்க தூரத்தில இருந்தே" · (1:49) "இவனை கண்காணிச்சாங்க" · (1:50) "ஆனா நெருங்கவே இல்ல"
Step 3 Ingredients: Vehicle/Subject Reference Image: `TanaruMan_Portrait.png` · Environment Reference Image: `SettingA_Env.png` · Scene Continuity Reference: `S013_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Medium telephoto shot compressed through blurred foreground leaves, the lone man crouched at his hut fire far away in golden dusk light, his weathered face visible in profile; heavy leaf blur frames the shot like a hidden observer's view.
Save as: `S014_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S014_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S014_Ref.png`. 0–3s: a slow lateral creep behind the foreground leaves; 3–6s: at 3s the camera eases back so the man is smaller and more distant behind the leaf screen; he tends the fire and glances toward the trees; 6–8s: the camera stops at the same distance, refusing to move nearer. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): Quiet held-breath ambience, faint crackling fire, insects, a soft pad; a subtle camera-focus click at 3s; a distant woodpecker.
Cut→S015: Hard cut to a closer view of him raising the bow.

**S015 — The warning arrow | 1:52–2:00**
VO sync: (1:52) "ஏனா இவன் நெருங்கற யாரையும்" · (1:54) "அம்பு எய்து விரட்டி அடிப்பான்" · (1:55) "நினைச்சு பாருங்க" · (1:56) "26 வருசம்" · (1:57) "ஒரு மனிசன் மட்டும்" · (1:59) "பேச யாருமே இல்ல"
Step 3 Ingredients: Vehicle/Subject Reference Image: `TanaruMan_Portrait.png`, `TanaruMan_6Angle.png` · Environment Reference Image: `SettingB_Env.png` · Scene Continuity Reference: `S014_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Medium shot at golden dusk of the lone man at the edge of the clearing in three-quarter profile, face clearly visible with a fierce, wary expression, bow raised and a feathered arrow on the string pointing at the trees, orange smoke behind; no target in frame.
Save as: `S015_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S015_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S015_Ref.png`. 0–2s: the camera pushes in slowly as he draws the bow tight; 2–3s: he releases and the arrow flies out of frame into the dark trees, a warning shot, and we hear it strike a trunk; 3–8s: he lowers the bow, the fierce look softening into a lonely, exhausted stare; the camera pushes to a close view of his face. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): Music thins to one held string note; bow-string creak, whoosh of the arrow, a wood thud at 2s; the note swells softly at 4s into a lonely melody.
Cut→S016: Cross-dissolve into a time-lapse of the clearing.

**S016 — The forest was his world | 2:00–2:08**
VO sync: (2:00) "தன் கலாச்சாரத்தைப் பகிர்ற" · (2:01) "யாருமே இல்ல" · (2:02) "காடே அவனது உலகம்" · (2:04) "2022 ஆகஸ்ட் மாசம்" · (2:06) "FUNAI ஆபீசர் ஒருத்தர்" · (2:07) "வழக்கம் போல சுத்தி பாக்கப் போனார்"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: `SettingB_Env.png` · Scene Continuity Reference: `S015_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Locked-off wide shot of the empty clearing and palm-thatch hut at golden dusk, a sky full of streaking clouds, the fire pit glowing faintly and the hammock swaying, no people visible.
Save as: `S016_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S016_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S016_Ref.png`. 0–4s: a time-lapse of clouds and seasons: light moves from dusk through night, dawn and day, leaves grow slightly around the clearing while the hut stays unchanged; 4s: the light settles into a calm, soft late-morning glow; 5–8s: the camera begins a smooth forward move along a forest path toward the hut as if a visitor were walking. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): Slow melancholic solo flute; fast wind whoosh, day-night bird and cricket cycles; at 4s the sound calms to a soft morning ambience; light footsteps from 5s.
Cut→S017: Continuous forward move, the camera entering the hut.

**S017 — Found in the hammock | 2:08–2:16**
VO sync: (2:09) "அப்போ அவனோட குடிசைக்குள்ள" · (2:10) "ஒரு தூக்கு கட்டில்ல" · (2:12) "அந்த மனிசன் இறந்து கிடந்தான்" · (2:13) "எந்த வன்முறையும் இல்ல" · (2:15) "வேற ஆளோட சுவடே இல்ல"
Step 3 Ingredients: Vehicle/Subject Reference Image: `TanaruMan_Portrait.png` · Environment Reference Image: `SettingB_Env.png` · Scene Continuity Reference: `S016_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Soft-lit view from the doorway into the hut, a woven hammock hanging in the centre with the lone man lying still and peaceful in it, eyes closed, calm face, nothing disturbed, gentle daylight streaming across the earthen floor.
Save as: `S017_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S017_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S017_Ref.png`. 0–3s: the camera moves slowly through the doorway toward the hammock; 3–4s: it stops and holds on his peaceful, still face; 4–6s: the camera pans gently across the tidy hut, bow, pots and cold fire all undisturbed; 6–8s: it tilts down to the earthen floor, showing only one line of his own footprints. Nothing graphic. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): The flute fades to a single soft sustained string; a faint breeze through thatch and a gentle hammock creak; a hush at 4s; a very soft note at 7s.
Cut→S018: Match cut on the hammock, moving to a close top-down view of the feathers.

**S018 — The macaw feathers | 2:16–2:24**
VO sync: (2:16) "ஆனா அவன் படுத்திருந்த விதம்" · (2:18) "அவன் மேல மக்காவ் பறவையோட" · (2:20) "இறகுகள் அலங்காரமா வெச்சிருந்தான்" · (2:22) "மரணத்துக்கு தன்னைத்தானே" · (2:24) "தயார் பண்ணிக்கிட்ட மாதிரி"
Step 3 Ingredients: Vehicle/Subject Reference Image: `Macaw_Portrait.png`, `Macaw_6Angle.png`, `TanaruMan_Portrait.png` · Environment Reference Image: `SettingB_Env.png` · Scene Continuity Reference: `S017_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Close top-down view of the hammock, scarlet-and-blue macaw feathers laid carefully and symmetrically over the man's chest, his calm face at the top edge of frame with closed eyes, soft golden light.
Save as: `S018_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S018_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S018_Ref.png`. 0–2s: a slow push-in on the hammock; 2–4s: a gentle drift down over the feathers, a breeze stirring one feather; 4–6s: the camera glides slowly up to his peaceful face; 6–8s: it holds still, a scarlet feather settling in the last second. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): A slow, reverent string melody; a soft feather rustle, a breeze; one distant macaw call at 2s; silence in the last second.
Cut→S019: Slow cross-dissolve, the camera pulling back from the hut.

**S019 — Everything vanished with him | 2:24–2:32**
VO sync: (2:25) "இதில தான் இருக்கு உண்மையான திகில்" · (2:27) "இவன் வாழ்ந்த மொழி" · (2:28) "இவன் கூட்டத்தோட பேரு" · (2:29) "இவனோட சொந்த பேரு" · (2:31) "எல்லாமே இவனோட இறப்போட" · (2:32) "மறைஞ்சு போச்சு"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: `SettingB_Env.png` · Scene Continuity Reference: `S018_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Wide view from outside the hut looking at the open front at soft dusk, the hammock visible inside, the small fire at the entrance nearly burnt down, mist creeping over the clearing, no people visible.
Save as: `S019_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S019_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S019_Ref.png`. 0–3s: the camera pulls slowly back from the hut; 3–6s: mist thickens and drifts across the clearing, and the fire embers glow lower; 6–8s: the last ember dies and the smoke dissolves, and the hut fades into the mist and darkness. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): The melody fades to a single low note; crackle of dying embers, a fading breeze; a last soft hiss as the ember goes out at 7s.
Cut→S020: Cross-dissolve, the camera rising into the sky.

---

### Segment 4 — The Pattern & Fawcett: The Obsession (Scenes 20–23)

**S020 — One page of a bigger pattern | 2:32–2:40**
VO sync: (2:33) "ஆனா இது ஒரு தனி சம்பவம் இல்ல" · (2:35) "இது ஒரு பெரிய பேட்டர்னோட" · (2:37) "ஒரு பகுதி மட்டும் தான்" · (2:38) "1925ம் வருடம்"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: `SettingG_Env.png` · Scene Continuity Reference: `S019_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
High aerial view at pre-dawn blue light over the canopy, several tiny distant smoke threads and faint clearings scattered across the endless forest, mist between them.
Save as: `S020_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S020_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S020_Ref.png`. 0–5s: the camera rises and drifts forward, revealing more and more small smoke threads across the canopy so a pattern forms; 5–8s: the sun rises, the colour warms to a sepia-tinged golden tone and mist thickens across the frame, ending as a soft warm haze ready for a dissolve into a mist trail. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): A slow rising string line; wind and distant birds; at 6s a soft old-film-like warmth enters the music with a gentle harp.
Cut→S021: Cross-dissolve out of the haze into a 1925 trail camp.

**S021 — The colonel and his belief | 2:40–2:48**
VO sync: (2:40) "ஆங்கிலேய ஆர்மி அதிகாரி ஒருத்தர்" · (2:42) "பெயர் பெர்சி ஃபாசெட்" · (2:43) "இவருக்கு ஒரு நம்பிக்கை இருந்தது" · (2:45) "அமேசான் காட்டுக்குள்ள" · (2:46) "ஒரு பழங்கால நகரம்" · (2:47) "ஒளிஞ்சிருக்குன்னு"
Step 3 Ingredients: Vehicle/Subject Reference Image: `Explorers_Portrait.png`, `Explorers_6Angle.png` · Environment Reference Image: `SettingC_Env.png` · Scene Continuity Reference: `S020_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Medium shot in warm misty morning light at the 1925 camp: the tall grey-moustached colonel in his pith helmet seated at a crate studying a hand-drawn map, face clearly visible and lit by the morning light, a lantern beside the map, the canvas tent behind.
Save as: `S021_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S021_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S021_Ref.png`. 0–2s: the camera settles; 2–5s: it pushes in slowly toward the colonel's face as his pale blue eyes light with conviction; 5–8s: a rack focus drops from his face to the map on the crate where a hand-inked circle marks an empty unmapped centre. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): A gentle adventurous theme on pizzicato strings; paper rustle, lantern flutter, dawn birds; a soft mystery sting at 6s on the circled mark.
Cut→S022: Hard cut to a macro of the map.

**S022 — The name on the map, and the earlier journeys | 2:48–2:56**
VO sync: (2:48) "இவர் அதுக்கு பெயர் வெச்சிருந்தார்" · (2:51) "இவர் இதுக்கு முன்னாடியே" · (2:52) "பல தடவை அமேசான் காட்டுக்குள்ள" · (2:54) "போய்த் திரும்பி வந்திருக்கார்" · (2:55) "ராயல் ஜியாகிராஃபிக்கல் சொசைட்டிக்கூட"
Step 3 Ingredients: Vehicle/Subject Reference Image: `Explorers_Portrait.png` · Environment Reference Image: `SettingC_Env.png` · Scene Continuity Reference: `S021_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Macro top-down view of a stained hand-drawn map on a wooden crate, ink rivers winding across it, one circled geometric glyph deep in the unmapped centre, several dotted routes looping out and back; no readable letters or words anywhere; warm morning light on the paper grain.
Save as: `S022_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S022_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S022_Ref.png`. 0–3s: the camera holds tight on the circled glyph as it seems to glow softly; 3–6s: the camera glides slowly along the dotted inked routes that loop out into the forest and return to the river; 6–8s: it rises slightly to show the whole map and a brass compass lying beside it. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): The theme drops to a hushed harp and low strings; paper crinkle, a lantern glass tick, a moth's wing flutter; a soft reverent swell at 7s.
Cut→S023: Hard cut to the trail head, wide.

**S023 — The last journey begins | 2:56–3:04**
VO sync: (2:57) "இவரோட வரைபடம் தயாரிப்புல" · (2:59) "நம்பிக்கை வெச்சிருந்துச்சு" · (3:00) "இப்போ தன் மகன் ஜேக்குடனும்" · (3:02) "மகனோட நண்பர் ஒருத்தரோடும்" · (3:03) "கடைசி பயணத்துக்கு ஒன்னா சேர்ந்துட்டு" · (3:05) "கிளம்பினார்"
Step 3 Ingredients: Vehicle/Subject Reference Image: `Explorers_Portrait.png`, `Explorers_6Angle.png` · Environment Reference Image: `SettingC_Env.png` · Scene Continuity Reference: `S022_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Wide establishing shot in warm misty morning light on a muddy jungle trail: the grey-moustached colonel alone in the centre facing a wall of towering trees, faces clearly visible, the young freckled man and the stubbled companion still at the tent in soft focus at frame left.
Save as: `S023_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S023_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S023_Ref.png`. 0–3s: the camera cranes slowly up and back as the colonel looks ahead resolutely; 3–5s: the young man and the companion walk into frame to stand beside him; 5–8s: the three step forward together onto the trail, the camera arcing to a three-quarter front angle. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): The adventurous theme rises to a hopeful swell with brass and strings; boots in mud, canvas rustle, dawn bird chorus; a drum accent as they step out at 5s.
Cut→S024: Match cut on their stride, into a ground-level tracking shot.

---

### Segment 5 — Fawcett: The Vanishing (Scenes 24–28)

**S024 — Deeper into the forest | 3:04–3:12**
VO sync: (3:05) "கிளம்பினார்" · (3:06) "பிரேசில் காட்டுக்குள்ள" · (3:07) "ஆழமா போன இவங்க" · (3:08) "ஒரு கடிதத்துல இதுக்கப்புறம்" · (3:09) "நாங்க அனுப்புற தகவல்" · (3:11) "யாருக்கும் கிடைக்காது"
Step 3 Ingredients: Vehicle/Subject Reference Image: `Explorers_Portrait.png`, `Explorers_6Angle.png` · Environment Reference Image: `SettingC_Env.png` · Scene Continuity Reference: `S023_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Low-angle shot at mud level of three pairs of leather boots and puttees marching along the trail toward the camera, thick jungle closing in behind, the three explorers' faces just visible above, determined and sweat-streaked.
Save as: `S024_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S024_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S024_Ref.png`. 0–4s: the camera tracks backwards ahead of the marching boots, mud squelching, then tilts up to their faces; 4–8s: the jungle closes in, the light dims and the trail narrows, and the three men pass into deeper shadow. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): The theme carries a steady marching pulse that slows and turns uneasy at 4s; squelching boots, leather creak, insects growing louder; music thins at 8s.
Cut→S025: Hard cut to a macro of a letter.

**S025 — The last letter, and the empty camp | 3:12–3:20**
VO sync: (3:12) "அப்படின்னு எழுதி அனுப்புனாங்க" · (3:13) "அதுக்கப்புறம் மூனு பேருமே" · (3:14) "காணாம போய்ட்டாங்க" · (3:15) "அடுத்த 90 வருசம்" · (3:17) "நூற்றுக்கணக்கான ஆட்கள்" · (3:18) "இவங்களைத் தேடி" · (3:19) "காட்டுக்குள்ள போனாங்க"
Step 3 Ingredients: Vehicle/Subject Reference Image: `Explorers_Portrait.png` · Environment Reference Image: `SettingC_Env.png` · Scene Continuity Reference: `S024_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Macro of a folded letter sealed with a red wax seal on a wooden crate, faint blurred ink lines on the paper edge that are not legible, a lantern glowing behind it, the canvas tent in soft focus.
Save as: `S025_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S025_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S025_Ref.png`. 0–2s: the lantern flame flickers over the wax seal; 2–3s: the flame gutters and goes out; 3–5s: the camera pulls smoothly back from the crate to reveal the whole camp empty and quiet in the mist; 5–8s: a time-lapse begins — dozens of boot prints in different sizes appear across the mud, one group after another, all leading into the trees. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): A solo violin, then silence at 2s as the flame dies; a hollow low pad with a slow tick; from 5s a steady rhythm of footsteps building.
Cut→S026: Hard cut to a bone in the leaf-litter.

**S026 — The bones that were not his | 3:20–3:28**
VO sync: (3:20) "சிலருக்கு எலும்புக் கூடு கிடைச்சது" · (3:21) "ஆனா" · (3:22) "DNA டெஸ்ட் பண்ணும்போது" · (3:24) "இது Fawcett-உடையது இல்ல" · (3:25) "சிலர் திரும்பவே இல்ல" · (3:26) "இந்த தேடுதலே" · (3:27) "பல ஆயிரம் உயிர்களை"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: `SettingA_Env.png` · Scene Continuity Reference: `S025_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Macro of a single old bleached long bone half-buried in mossy leaf-litter beside a rotted scrap of khaki cloth, a shaft of amber light across it, ferns blurred behind; respectful and non-graphic.
Save as: `S026_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S026_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S026_Ref.png`. 0–2s: the camera pushes in slowly on the bone; 2–4s: the amber shaft of light drifts off the bone and the scene cools; 4–6s: the camera tilts up past the moss to an old pith helmet hanging on a broken branch above; 6–8s: it holds there as the helmet sways in the mist. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): A dissonant low string cluster; a droplet plink, beetle rustle; a wood creak from the helmet at 5s; a hollow wind tone.
Cut→S027: Hard cut to a slow forward glide down the trail.

**S027 — Nobody knows what happened | 3:28–3:36**
VO sync: (3:29) "இன்னைக்கு வரைக்கும்" · (3:30) "பெர்சி ஃபாசெட்டுக்கு" · (3:31) "என்ன ஆச்சுன்னு" · (3:32) "யாருக்குமே தெரியாது" · (3:33) "இவரோட City of Z" · (3:35) "இருக்கா இல்லையா"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: `SettingA_Env.png` · Scene Continuity Reference: `S026_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Wide low view along a misty forest trail at dawn, giant trunks on both sides, and far ahead moss-covered stone terraces and steps half-hidden beneath tree roots in the mist, warm amber light shafts breaking through.
Save as: `S027_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S027_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S027_Ref.png`. 0–4s: the camera glides slowly forward down the empty trail; 4–6s: the stone steps become clearer through the mist; 6–8s: the mist swirls back in and partly hides the steps again, leaving it ambiguous. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): A hopeful yet uneasy theme on solo horn and low strings; wind, distant jungle calls; a tonal sting at 5s as the steps appear.
Cut→S028: Hard cut to the mist thickening.

**S028 — The forest keeps its secrets | 3:36–3:44**
VO sync: (3:36) "அப்படிங்கறதே" · (3:37) "ஒரு பெரிய மர்மமா இருக்கு" · (3:38) "ஆனா" · (3:39) "ஒன்னு மட்டும் நிச்சயம்" · (3:40) "அமேசான் காடு" · (3:41) "தன் ரகசியத்தை காப்பாத்துறதுல" · (3:42) "கில்லாடி" · (3:43) "இப்ப மனிசங்க மட்டும் இல்ல"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: `SettingA_Env.png` · Scene Continuity Reference: `S027_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Low wide view of thick white mist rolling across the mossy stone steps in the forest, the top of the steps lost in fog, giant roots and trunks around, a single scarlet macaw-coloured leaf on the stone in the foreground.
Save as: `S028_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S028_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S028_Ref.png`. 0–4s: the mist thickens and swallows the steps completely; 4–6s: the camera rises up through the mist and canopy; 6–8s: it breaks into light above the canopy and tilts to show a brown river winding through the forest. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): The horn theme fades; soft wind and a hush as the mist swallows the steps; a whoosh as the camera rises; a rising note at 6s.
Cut→S029: Hard cut to a skimming shot over the river.

---

### Segment 6 — The River's Hidden Dangers (Scenes 29–35)

**S029 — The living river and the tiny candiru | 3:44–3:52**
VO sync: (3:44) "அமேசான் நதியே" · (3:45) "ஒரு உயிருள்ள ஆபத்து" · (3:47) "இதில ஒரு மீன் இருக்கு" · (3:48) "பேரு கேண்டிரு" · (3:50) "இது பாக்கரதுக்கு ஒரு இஞ்சு கூட இருக்காது"
Step 3 Ingredients: Vehicle/Subject Reference Image: `Candiru_Portrait.png`, `Candiru_6Angle.png` · Environment Reference Image: `SettingD_Env.png` · Scene Continuity Reference: `S028_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Low tracking view skimming just above the brown Amazon river surface toward a misty bend, roots and branches overhanging both banks, bright overcast light, ripples on the water.
Save as: `S029_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S029_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S029_Ref.png`. 0–3s: the camera skims forward over the water surface; 3–4s: it dips smoothly into the tea-brown water, particles swirling; 4–8s: underwater a tiny translucent candiru hangs in the current beside a sand grain and a leaf edge for scale. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): The music turns wary with a low drone; water rush, then a muffled underwater ambience from 4s; soft bubble pops and a faint high sting on the fish.
Cut→S030: Match cut on the small fish, into a wider shallow-water shot.

**S030 — Locals stay wary | 3:52–4:00**
VO sync: (3:52) "ஆனா லோக்கல் மக்கள்" · (3:53) "இதுக்கு பயந்தே" · (3:54) "நதியில் ஈரமா நிக்கும்போது" · (3:55) "ஜாக்கிரதையா இருப்பாங்க" · (3:56) "ஏன்னா இது உடம்பல்" · (3:58) "திறந்த இடங்கள்ல" · (3:58) "நுழைஞ்சு உக்காந்து இருக்கும்" · (3:59) "ஒரு தடவை நுழைஞ்சா"
Step 3 Ingredients: Vehicle/Subject Reference Image: `Tapper_Portrait.png`, `Candiru_Portrait.png` · Environment Reference Image: `SettingD_Env.png` · Scene Continuity Reference: `S029_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Medium shot from the riverbank of the rubber-tapper (a local man in a straw hat) standing ankle-deep in clear brown shallows in bright overcast light, his face visible with a careful, wary expression as he looks down at the water, a faint thin needle-like shadow in the sand beneath.
Save as: `S030_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S030_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S030_Ref.png`. 0–3s: the man glances at the water, then slowly and carefully steps back toward the bank; 4–6s: the camera cuts down through the surface to show the thin candiru shadow following the ripple line toward a root crack; 6–8s: the fish slips inside the crack in the root and vanishes. Nothing shown on a body. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): Suspense pulse over low strings; soft water lapping, careful footsteps; a muffled underwater tone from 4s; a soft sting at 7s.
Cut→S031: Hard cut to a dark, dramatic shoal.

**S031 — The movie piranha myth | 4:00–4:08**
VO sync: (4:00) "அதை வெளியே எடுக்கவே" · (4:01) "ஆப்ரேஷன் பண்ணணும்" · (4:02) "பிறகு" · (4:03) "பிரான்ஹா மீன்" · (4:04) "சினிமாவுல காமிக்குற மாதிரி" · (4:05) "மனிசனை நிமிசத்துல" · (4:06) "தின்னுடுவாங்கன்னு" · (4:07) "காமிச்சிருக்காங்க"
Step 3 Ingredients: Vehicle/Subject Reference Image: `Piranha_Portrait.png`, `Piranha_6Angle.png` · Environment Reference Image: `SettingD_Env.png` · Scene Continuity Reference: `S030_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Low-angle underwater shot looking up, a dark shoal of about fifteen red-bellied piranhas in murky water below a bright silver surface, dramatic thriller lighting with sun rays cutting through, roots framing the shot.
Save as: `S031_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S031_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S031_Ref.png`. 0–2s: the camera drifts through dark roots as the light dims; 3s: the shoal swings into view and turns toward the lens in a dramatic thriller-style approach; 4–7s: the shoal swirls and charges closer, teeth glinting, exactly like a movie; 7–8s: the shoal turns sharply away. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): A horror-movie style rising string tremolo and pounding bass from 3s; muffled water rush, fin flicks; a sharp sting at 4s.
Cut→S032: Hard cut to a calm single fish.

**S032 — Alone, calm; together, when water shrinks, dangerous | 4:08–4:16**
VO sync: (4:08) "உண்மையில தனியா இருக்கும்போது" · (4:09) "இது பெரும்பாலும்" · (4:10) "அபாயகரம் இல்ல" · (4:11) "ஆனா நீர் குறைஞ்சு" · (4:12) "உணவு கிடைக்காம" · (4:13) "ஒரு பெரிய கூட்டமா இருக்கும்போது" · (4:15) "ஆபத்து நிஜம் தான்"
Step 3 Ingredients: Vehicle/Subject Reference Image: `Piranha_Portrait.png`, `Piranha_6Angle.png` · Environment Reference Image: `SettingD_Env.png` · Scene Continuity Reference: `S031_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Underwater view of a lone piranha cruising peacefully past submerged roots and lily-pad stems in tea-brown water, soft shafts of light and drifting particles around it, calm mood.
Save as: `S032_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S032_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S032_Ref.png`. 0–3s: the camera tracks alongside the lone piranha as it glides calmly and nibbles a drifting fruit; 3–4s: the camera rises through the surface; 4–8s: above water a time-lapse shows the river pool shrinking and cracked mud spreading while dozens of piranhas crowd the small pool and churn the surface harder and harder. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): Gentle low pizzicato; soft underwater tone; from 3s a building tension with rising drums, splashes and fin slaps; dry wind at 7s.
Cut→S033: Whip pan to a still, quiet water surface.

**S033 — The heaviest snake | 4:16–4:24**
VO sync: (4:16) "இன்னும் ஒன்னு" · (4:17) "அனகோண்டா" · (4:17) "இது உலகத்திலேயே" · (4:18) "பாரம் அதிகமான பாம்பு" · (4:20) "இது நீருக்குள்ள ஒளிஞ்சிருந்து" · (4:21) "தண்ணீர் குடிக்க வர மிருகங்களை வேட்டையாடும்"
Step 3 Ingredients: Vehicle/Subject Reference Image: `Anaconda_Portrait.png`, `Anaconda_6Angle.png` · Environment Reference Image: `SettingD_Env.png` · Scene Continuity Reference: `S032_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Water-level view at the flooded roots of a riverbank, the still brown surface at the bottom edge of frame and above it the eyes and snout of a giant green anaconda, its long body lost in the brown water.
Save as: `S033_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S033_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S033_Ref.png`. 0–1s: the surface is still, then the snout rises slightly; 1–4s: the camera pulls slowly back and lowers through the surface to reveal the huge olive body coiled among the roots underwater; 4–8s: it lies almost motionless with only slow gill-like ripples, a bird's shadow passing over the surface. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): A very low slow drone with a heartbeat; water lapping, an insect hum; a hiss at 1s; a muffled underwater tone from 3s.
Cut→S034: Match cut to a close view of its eye.

**S034 — The recorded 1997 incident | 4:24–4:32**
VO sync: (4:23) "மனிசங்களை தாக்கினது" · (4:25) "அபூர்வம் தான்" · (4:25) "ஆனா" · (4:26) "1997ம் வருசம்" · (4:28) "பிரேசில்ல ஒரு தோட்டக்காரர் மேல்" · (4:30) "அனகோண்டா தாக்கினது" · (4:31) "பதிவு பண்ணப்பட்ட உண்மையான சம்பவம்"
Step 3 Ingredients: Vehicle/Subject Reference Image: `Anaconda_Portrait.png` · Environment Reference Image: `SettingD_Env.png` · Scene Continuity Reference: `S033_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Extreme macro of the anaconda's amber eye with its vertical pupil and wet olive scales, water droplets beading, and softly blurred behind it across the river a small riverbank vegetable garden with a hoe leaning against a stake and a woven basket, bright overcast light.
Save as: `S034_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S034_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S034_Ref.png`. 0–3s: the pupil narrows slightly; 3–5s: a rack focus shifts from the eye to the garden across the water; 5–8s: a slow ripple crosses the river toward the garden and the camera holds as birds fly off. Nothing violent shown. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): Held low tone; tongue flick, water drips; a tension sting at 3s; distant birds flushing at 6s.
Cut→S035: Cut to a slow tilt from the water up.

**S035 — Water, soil, tree, wind: nowhere safe | 4:32–4:40**
VO sync: (4:33) "இந்த காடு" · (4:33) "உங்களை எப்படி எல்லாம் எச்சரிக்கை பண்ணுதுன்னு பாருங்க" · (4:36) "நீர்" · (4:36) "மண்" · (4:37) "மரம்" · (4:37) "காத்து" · (4:38) "எதுவுமே பாதுகாப்பு இல்ல"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: `SettingD_Env.png` · Scene Continuity Reference: `S034_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Low view at the river's edge at the water surface, a muddy bank beside it with a giant trunk rising behind, thin mist above, bright overcast light.
Save as: `S035_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S035_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S035_Ref.png`. 0–4s: the camera holds at the water surface as ripples pass; 4s the water darkens; 4–5s the camera tilts up over the muddy bank; 5s it climbs the trunk; 5–6s it reaches the canopy, which sways hard in a gust; 6–8s: the wind drops completely and everything goes still. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): A wary theme; water lapping, a wet mud squelch, a wood creak, a wind gust rising; a sudden hush at 6s.
Cut→S036: Cross-dissolve to the dawn trail.

---

### Segment 7 — The Rubber Tapper's Voice (Scenes 36–39)

**S036 — Chico Mendes: a rubber tapper | 4:40–4:48**
VO sync: (4:39) "இப்ப ஒரு உண்மையான சம்பவம் சொல்றேன்" · (4:41) "இது காட்டுல இருக்குற மிருகங்களைப் பற்றி இல்ல" · (4:43) "மனிதர்களைப் பற்றி" · (4:44) "சிக்கோ மெண்டஸ்" · (4:45) "அப்படின்னு ஒரு ஆள்" · (4:46) "இவர் பிரேசில்ல ரப்பர் மரத்துல இருந்து"
Step 3 Ingredients: Vehicle/Subject Reference Image: `Tapper_Portrait.png`, `Tapper_6Angle.png` · Environment Reference Image: `SettingE_Env.png` · Scene Continuity Reference: `S035_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Wide shot at dawn on a misty rubber-tree trail, the rubber tapper in a straw hat walking toward the camera between the trunks, his face clearly visible and calm, the headlamp on his hat glowing faintly, gold rim light through the mist, tin cups on the trees.
Save as: `S036_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S036_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S036_Ref.png`. 0–3s: the mist swirls and light beams shift, the trail quiet; 4s: he steps into a shaft of gold light and the camera settles on his face; 5–8s: the camera tracks backwards ahead of him as he walks and touches a rubber tree. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): A warm humble guitar and flute theme enters; boots on mud, dawn birds; a soft chime as he enters the light at 4s.
Cut→S037: Hard cut to a macro on the cut in the bark.

**S037 — The forest he grew up in | 4:48–4:56**
VO sync: (4:49) "பால் எடுக்குற தொழிலாளி" · (4:50) "இவர் வளர்ந்ததே அமேசான் காட்டுக்குள்ள தான்" · (4:52) "இவருக்கு காடு அழிக்கப்பட்டதை பாத்தா" · (4:54) "ரொம்ப வருத்தம்"
Step 3 Ingredients: Vehicle/Subject Reference Image: `Tapper_Portrait.png` · Environment Reference Image: `SettingE_Env.png` · Scene Continuity Reference: `S036_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Macro of a curved tapping knife making a fresh diagonal cut into a rubber tree's bark, a thin line of white latex beading along the cut, the tapper's latex-stained sleeve and his calm face softly visible behind.
Save as: `S037_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S037_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S037_Ref.png`. 0–3s: the knife draws a smooth shallow cut and milky latex wells up and runs down into a tin cup; 3–5s: the camera rises from the cup along his arm to his face; 5–8s: he turns to look toward a dark column of smoke far above the ridge, his brow furrowing with sorrow. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): The theme stays warm; knife scrape and latex drip; from 5s a low cello darkens the music and a distant chainsaw whine rises.
Cut→S038: Cut to a wide trail with many people.

**S038 — A voice against the powerful | 4:56–5:04**
VO sync: (4:56) "அதை நம்பி வாழ்ற" · (4:57) "தன் மாதிரி" · (4:58) "ஆயிரக்கணக்கான குடும்பங்களுக்கும்" · (5:00) "வாழ்வாதாரம் போயிடும்" · (5:01) "இவர் அரசாங்கத்துக்கு எதிரா" · (5:02) "பெரிய நில உரிமையாளருக்கு எதிரா" · (5:04) "குரல் கொடுத்தார்"
Step 3 Ingredients: Vehicle/Subject Reference Image: `Tapper_Portrait.png`, `Tapper_6Angle.png` · Environment Reference Image: `SettingE_Env.png` · Scene Continuity Reference: `S037_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Wide low view at dawn on the rubber trail: the tapper stands in the foreground with his back turned slightly and his face in profile, and behind him dozens of other tappers and families in straw hats stand along the trail among the trunks, serious weathered faces, gold light through the mist.
Save as: `S038_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S038_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S038_Ref.png`. 0–4s: the camera drifts slowly along the line of tappers and their families as smoke drifts in behind them; 4–5s: the tapper turns to face the camera, resolute; 5–8s: he raises his straw hat high in the air and the others behind him raise theirs one by one. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): The theme darkens under the first four seconds, then swells into a determined strings and warm synth pad at 5s; fabric rustle.
Cut→S039: Cross-dissolve to a quiet medal.

**S039 — International recognition | 5:04–5:12**
VO sync: (5:05) "சர்வதேச அளவில் கவனம் பெற்றார்" · (5:07) "ஐக்கிய நாடுகள் சபைக்கூட" · (5:08) "இவருக்கு விருது கொடுத்துச்சு" · (5:09) "ஆனா" · (5:10) "1988" · (5:11) "டிசம்பர் 22"
Step 3 Ingredients: Vehicle/Subject Reference Image: `Tapper_Portrait.png` · Environment Reference Image: `SettingF_Env.png` · Scene Continuity Reference: `S038_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Macro of a modest brass medal on a blue ribbon lying on a rough wooden porch rail beside a straw hat and a tapping knife, warm dusk light, the wooden house and yard blurred behind, no text or writing on the medal.
Save as: `S039_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S039_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S039_Ref.png`. 0–2s: warm golden light glints across the brass as the camera pushes slowly in; 2–4s: a rack focus moves from the medal to the straw hat; 4–6s: the warm light fades into a cold blue dusk; 6–8s: a moth circles and the yard's dark treeline is visible in soft focus. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): A quiet dignified piano; light metal shimmer, ribbon rustle; at 4s the piano stops and a low drone enters; crickets grow at 6s.
Cut→S040: Hard cut to a locked wide of the yard.

---

### Segment 8 — The Sacrifice & Legacy (Scenes 40–42)

**S040 — Behind his own house | 5:12–5:20**
VO sync: (5:12) "அவரோட சொந்த வீட்டுக்கு பின்னாடியே" · (5:14) "துப்பாக்கியால் சுட்டுக்கொல்லப்பட்டார்" · (5:16) "இதுக்கு காரணமா" · (5:17) "நில உரிமையாளர் குடும்பம்" · (5:18) "ஒன்னு கைது ஆனாங்க"
Step 3 Ingredients: Vehicle/Subject Reference Image: `Tapper_Portrait.png` · Environment Reference Image: `SettingF_Env.png` · Scene Continuity Reference: `S039_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Locked-off wide shot of the back yard of the wooden stilt house at blue-hour dusk, a single window glowing, a straw hat resting on the porch rail, a towel hanging still, the dark treeline behind, held silence.
Save as: `S040_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S040_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S040_Ref.png`. 0–2s: the camera holds still as crickets sound; 2s: a flock of birds bursts from the dark treeline and scatters; the straw hat trembles and slips from the rail, falling out of frame; 3–6s: silence, the towel swinging gently, the window light flickering once; 6–8s: a second, distant light and the sound of engines approach from far off-screen. Nothing violent is shown. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): Sparse hushed piano; crickets; one distant sharp crack echoing at 2s, a burst of wings; then a long hush and a low tone; faint engines from 6s.
Cut→S041: Hard cut to the dropped hat.

**S041 — His death made the world speak | 5:20–5:28**
VO sync: (5:19) "இவரோட மரணம்" · (5:20) "உலக முழுக்க" · (5:21) "அமேசான் காட்டு அழிப்புப்பத்தி" · (5:23) "முதன்முறையா" · (5:23) "பெரிய அளவுல பேச வச்சிச்சு" · (5:25) "இன்னைக்கு அமேசான் காட்டுல இருக்குற" · (5:27) "பாதுகாக்கப்பட்ட பகுதிகள் பல"
Step 3 Ingredients: Vehicle/Subject Reference Image: `Tapper_Portrait.png` · Environment Reference Image: `SettingF_Env.png` · Scene Continuity Reference: `S040_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Low-angle close shot of the straw hat lying on the wooden porch step in the dust, warm window light spilling over it, a moth circling above, the dark yard blurred behind.
Save as: `S041_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S041_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S041_Ref.png`. 0–3s: a slow push-in on the hat, the moth circling; 3–5s: the camera lifts and rises as a time-lapse turns the night to dawn and the sky glows gold above the treeline; 5–8s: it rises over the treeline to reveal an unbroken green canopy in soft sunrise light. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): A solo cello with a mournful line; moth wing flutter, crickets that turn to dawn birds at 4s; the cello lifts into a warm hopeful chord at 6s.
Cut→S042: Continuous rise, the camera flying on over the canopy.

**S042 — Saved by his sacrifice | 5:28–5:36**
VO sync: (5:28) "இன்னைக்கு அமேசான் காட்டுல இருக்குற" · (5:29) "பல பகுதிகள்" · (5:30) "இவரோட தியாகத்தால தான் உண்டாச்சு" · (5:32) "ஒரு மனிசன்" · (5:33) "காட்டுக்காக தன் உயிரையே கொடுத்திருக்கான்" · (5:35) "இது கட்டுக்கதை இல்ல" · (5:36) "சரித்திரம்"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: `SettingG_Env.png` · Scene Continuity Reference: `S041_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
High aerial view at sunrise of an intact protected rainforest reserve, gold light spilling over the canopy, a winding river reflecting the sky, mist lifting; a narrow rubber-tree trail visible at the edge of the trees.
Save as: `S042_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S042_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S042_Ref.png`. 0–4s: the camera glides forward over the glowing canopy, birds crossing, the river shining; 4–8s: it tilts down and descends through the mist toward the rubber trail and ends on a tin cup on a rubber tree with a single drop of latex falling into it at 6s. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): The cello theme blooms into a full warm orchestral swell; birds waking up, wind over the trees; a soft latex drip at 6s over a gentle held chord.
Cut→S043: Hard cut to a cold, quiet dawn.

---

### Segment 9 — The Danger That Continues (Scenes 43–48)

**S043 — "Here is that last part" | 5:36–5:44**
VO sync: (5:36) "நான் ஆரம்பத்தில சொன்னேன்னுல" · (5:37) "கடைசி பகுதி தான் மிக முக்கியம்னு" · (5:40) "இதோ அது" · (5:40) "2011 வருசம்" · (5:42) "பிரேசில் அரசாங்கம்" · (5:43) "ஒரு ட்ரோன் விமானத்தை"
Step 3 Ingredients: Vehicle/Subject Reference Image: `Drone_Portrait.png`, `Drone_6Angle.png` · Environment Reference Image: `SettingG_Env.png` · Scene Continuity Reference: `S042_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Cold blue dawn aerial view of the endless canopy with thin mist, a straight empty sky above, and at the far left edge the tiny white shape of a small survey drone just entering the frame.
Save as: `S043_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S043_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S043_Ref.png`. 0–3s: the light is cool and still over the canopy; 4s: a faint propeller hum begins and the drone moves fully into frame; 5–8s: the camera turns to track alongside it as it glides steadily and banks toward the deep forest. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): The warm theme is replaced by a cool technological pulse and low drone from 4s; propeller hum, wind rush.
Cut→S044: Match cut on the banking drone into its own point of view.

**S044 — The uncontacted people found | 5:44–5:52**
VO sync: (5:44) "அமேசான் காட்டுக்குள்ள பறக்க விட்டாங்க" · (5:46) "அது கவாஹிவா" · (5:47) "அப்படின்னு ஒரு பழங்குடி மக்கள்" · (5:49) "இன்னும் வெளி உலகத்தோட" · (5:50) "எந்த தொடர்பும் இல்லாம" · (5:51) "வாழ்றத கண்டுபிடிச்சாங்க"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: `SettingG_Env.png` · Scene Continuity Reference: `S043_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Drone point-of-view aerial shot looking down through a break in the canopy at a small forest clearing with two thatched huts and a thin thread of smoke, a few tiny distant figures moving between the huts, mist over the trees.
Save as: `S044_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S044_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S044_Ref.png`. 0–3s: the camera glides forward over the canopy; 3–6s: it descends toward the huts as the tiny distant figures move about their day; 6–8s: the camera holds steady above the clearing. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): Cool pulse continues under an awed string note; the drone hum in the distance; a hush at 6s.
Cut→S045: Hard cut to a ground-level push through foliage.

**S045 — They keep running | 5:52–6:00**
VO sync: (5:53) "இவங்க யாரோட கண்ணுக்கும் படாம" · (5:54) "ஒரு இடத்துல இருந்து" · (5:55) "இன்னொரு இடத்துக்கு" · (5:56) "ஓடிக்கிட்டே இருப்பாங்க" · (5:57) "ஏன்னா மரம் வெட்டுறவங்க" · (5:59) "சட்டவிரோதமா தங்கம் தேடுறவங்க"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: `SettingA_Env.png` · Scene Continuity Reference: `S044_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Ground-level view inside the forest of a small campfire still glowing beside two hurriedly abandoned hammocks and a woven basket, green light with amber shafts, no people in frame.
Save as: `S045_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S045_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S045_Ref.png`. 0–4s: the camera pushes in slowly toward the fire as a hammock rope still swings and the embers glow; 4–6s: the first distant sound of a chainsaw begins and grows; 6–8s: a distant metal clang of a digging tool joins in and the camera stops on the fire. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): A low tremolo; crackling embers, hammock rope creak; from 4s a chainsaw whine growing, then distant metal clangs at 6s.
Cut→S046: Hard cut to a low tracking shot on a road.

**S046 — Following behind them, today | 6:00–6:08**
VO sync: (6:00) "இவங்க பின்னாடியே வந்துகிட்டே இருக்காங்க" · (6:02) "இன்னைக்கு 2026ல" · (6:03) "இந்த நொடிக்கூட" · (6:05) "இது மாதிரி பல" · (6:05) "பழங்குடி மக்கள்" · (6:07) "தொகுதிகள் அமேசான் காட்டுக்குள்ள" · (6:08) "மறைஞ்சு வாழ்றாங்க"
Step 3 Ingredients: Vehicle/Subject Reference Image: `Bulldozer_Portrait.png`, `Bulldozer_6Angle.png` · Environment Reference Image: `SettingH_Env.png` · Scene Continuity Reference: `S045_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Low-angle tracking view at smoky orange dusk of the yellow bulldozer rolling along a fresh red-earth road toward the forest wall, dust and smoke around its tracks, charred stumps to the sides, no operator visible.
Save as: `S046_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S046_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S046_Ref.png`. 0–3s: the camera tracks alongside the bulldozer as it moves ahead, its blade throwing soil; 3–5s: the camera cranes up and over the machine; 5–8s: it rises high above the canopy to show many faint smoke threads spread across the forest, many hidden communities. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): Heavy drums and a brass drone that soften into a quiet ambient wind at 5s; diesel roar and track clank fading as the camera lifts.
Cut→S047: Continuous aerial, gliding forward.

**S047 — The pace of destruction nears them | 6:08–6:16**
VO sync: (6:09) "இவங்களுக்கு மாடர்ன் வேர்ல்ட்" · (6:10) "அப்படின்னு ஒன்னு தெரியவே தெரியாது" · (6:12) "ஆனா காடு அழிக்கப்படுற வேகம்" · (6:14) "இவங்களோட உலகத்தை நோக்கியும்" · (6:16) "நெருங்கிக்கிட்டு இருக்கு"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: `SettingG_Env.png` · Scene Continuity Reference: `S046_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Aerial view at dusk over a peaceful small clearing with thatched huts and a thin thread of smoke inside an unbroken canopy, and far behind it on the horizon a thin orange fire line and smoke columns.
Save as: `S047_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S047_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S047_Ref.png`. 0–3s: the camera hovers over the calm clearing as its smoke rises straight up; 3–5s: the camera turns slowly toward the horizon; 5–8s: the fire line grows and creeps forward across cleared land toward the forest, the camera gliding toward it. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): Quiet melancholy pad; wind; from 4s a menacing rise of drums and roaring fire; a low brass swell at 6s.
Cut→S048: Cross-dissolve into the lone man's face.

**S048 — How many more, alone and nameless? | 6:16–6:24**
VO sync: (6:16) "நினைச்சு பாருங்க" · (6:17) "Man of the Hole மாதிரி" · (6:18) "இன்னும் எத்தனை பேர்" · (6:20) "தன் கூட்டமே அழிஞ்சு" · (6:21) "தனியா பேரு கூட இல்லாம" · (6:22) "இந்த நிமிசம் காட்டுக்குள்ள இருக்காங்களோ"
Step 3 Ingredients: Vehicle/Subject Reference Image: `TanaruMan_Portrait.png`, `TanaruMan_6Angle.png` · Environment Reference Image: `SettingB_Env.png` · Scene Continuity Reference: `S047_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Medium shot at the tree line of the clearing at dusk, the lone man in three-quarter profile with his bow at his side, face clearly visible and lit by a far orange glow on the horizon, his eyes fixed on the fire with grief and quiet defiance.
Save as: `S048_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S048_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S048_Ref.png`. 0–3s: a slow push-in toward his face, the far glow pulsing in his eyes; 3–6s: the camera keeps pushing in as he lowers his head slightly; 6–8s: he lifts his eyes again toward the fire and the camera holds still. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): A lone flute over a soft pad; distant fire rumble, crickets; music dips to near silence at 6s.
Cut→S049: Slow cross-dissolve into a bright dawn.

---

### Segment 10 — Final Wide / Outro (Scenes 49–52)

**S049 — More than trees and animals | 6:24–6:32**
VO sync: (6:24) "அமேசான் காடு" · (6:25) "இது வெறும் மரங்களும்" · (6:26) "மிருகங்களும் நிறைந்த இடம் இல்ல" · (6:28) "இது மனித சரித்திரத்தோட" · (6:29) "துக்கத்தோட" · (6:30) "தியாகத்தோட" · (6:31) "இன்னும் தீராத மர்மத்தோட"
Step 3 Ingredients: Vehicle/Subject Reference Image: `Macaw_Portrait.png`, `Macaw_6Angle.png` · Environment Reference Image: `SettingG_Env.png` · Scene Continuity Reference: `S048_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Wide aerial view at sunrise over the emerald canopy stretching to the horizon, a pair of scarlet macaws flying low across the treetops, thick mist between the crowns, a soft golden light.
Save as: `S049_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S049_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S049_Ref.png`. 0–2s: the camera glides forward as the scarlet macaws cross the frame; 4–5s: the mist thickens and dims the light; 5–6s: bright gold rays break through the mist; 6–8s: the mist parts and reveals a faint moss-covered stone terrace deep in the trees. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): The outro theme builds with warm strings and flute; wind over the canopy, macaw calls; a soft harp accent at 6s.
Cut→S050: Continuous, the camera rising above the canopy.

**S050 — A book, one page turned | 6:32–6:40**
VO sync: (6:33) "ஒரு புத்தகம்" · (6:34) "இதுல ஒரு பக்கம் மட்டும் தான்" · (6:35) "நம்ம இன்னும் புரட்டி பாத்திருக்கோம்" · (6:37) "இன்னும் நிறைய பக்கங்கள்" · (6:38) "படிக்கப்படாம மறைஞ்சு இருக்கு"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: `SettingG_Env.png` · Scene Continuity Reference: `S049_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Vast aerial view at sunrise of the endless emerald canopy, mist between the treetops, gold sun rising, and a gust of wind starting to ripple across the leaves in wave patterns.
Save as: `S050_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S050_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S050_Ref.png`. 0–1s: the camera rises slowly; 2s: a single strong wave of wind sweeps across the canopy like a page turning; 3–4s: the leaves settle; 4–6s: a series of smaller waves ripple across the far forest, one after another; 6–8s: the mist rolls in over the canopy so the far parts are hidden. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): The outro theme swells, warm strings, flute and warm synth pad; a paper-like whoosh of wind at 2s; a dawn bird chorus.
Cut→S051: Cross-dissolve into sunset and stars.

**S051 — The call to action, dusk to night | 6:40–6:48**
VO sync: (6:39) "உங்களுக்கு" · (6:40) "இதுல எந்த பகுதி" · (6:41) "அதிகம் திகில் தந்துச்சுன்னு" · (6:42) "கமெண்ட்ல சொல்லுங்க" · (6:43) "இது மாதிரி இன்னும்" · (6:44) "பல உண்மை சம்பவங்களை" · (6:44) "பாக்கணும்னா" · (6:45) "சப்ஸ்கிரைப் பண்ணி" · (6:46) "பெல் ஐகானை அழுத்துங்க"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: `SettingI_Env.png` · Scene Continuity Reference: `S050_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Aerial view at sunset over the canopy, the sky deep orange fading to violet, mist over the treetops, the first stars appearing above the horizon.
Save as: `S051_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S051_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S051_Ref.png`. 0–3s: the camera descends slowly as the sunset fades to deep blue night; 3–6s: it settles low over a quiet forest clearing with a starry sky and the Milky Way above; 6–8s: fireflies rise from the ferns one by one and multiply. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): The outro theme softens to a gentle piano; crickets and night frogs grow; a soft twinkling chime accent as each firefly appears from 6s.
Cut→S052: Continuous, the camera tilting up to the stars.

**S052 — Until the next video | 6:48–6:54 (trim to 6s in edit)**
VO sync: (6:47) "அடுத்து வீடியோவில் சந்திக்கலாம்" · (6:49) "நன்றி நன்றி நன்றி" · (6:51–6:54) audio-file outro credit, no narration → BGM only
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: `SettingI_Env.png` · Scene Continuity Reference: `S051_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Quiet forest clearing at night, a sky full of stars and the Milky Way above a black treeline, hundreds of fireflies glowing softly among the ferns, and one bright firefly in the foreground drifting upward.
Save as: `S052_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S052_Ref.png`
Video Prompt (Google Flow, 8s, use the first 6s):
I2V from `S052_Ref.png`. 0–2s: the camera tilts up slowly toward the stars while the fireflies glow; 2–4s: the foreground firefly lifts higher and glows; 4–6s: the firefly fades among the other lights and the frame settles on the Milky Way; make sure the first 6 seconds hold a complete closing beat. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): The outro theme resolves to a final held chord and fades to silence by 6s; soft night crickets fading last.
Cut→END: Fade to black (last 1s of the 6s).

---

# PRODUCTION NOTES

- **Runtime check:** the voice file is 6:54 = 414 s. 414 ÷ 8 = 51.75, so 52 scenes. S001–S051 are 8 s each (408 s). S052 nominally runs 6:48–6:56 and is trimmed to 6 s so the video ends at exactly 6:54. The narration itself runs 0:07 to 6:49.
- **Timeline rule:** the video timeline is the same as the voice file. Place the voice file on the timeline at 0:00, then drop each clip at its scene start time (S001 at 0:00, S002 at 0:08, and so on: scene N starts at (N − 1) × 8 s). Every "VO sync" line and every in-clip second mark in the video prompts is relative to that timeline.
- **How the in-clip marks work:** in each video prompt, "0–3s" means seconds from the start of that clip; the actions are placed so they land on the spoken line at that moment (see each scene's VO sync line). The narration words are deliberately NOT written inside the Flow prompts, so the model has nothing to speak. Absolute time = scene start + clip second. Example: S003 "Amazon forest" at 0:17 is 1 s into S003 (0:16), and that is where the sun flare is placed.
- **Audio file credits:** the voice file has an audio-tool credit at 0:00–0:07 and again at 6:51–6:54. S001 and S052 are written so those seconds are BGM only. If you cut the credits from the audio, every scene start moves earlier by 7 s, and the first scene should be shortened to 1 s or the whole picture shifted to match.
- **Sync tolerance:** Google Flow cannot hit an exact second every time, so treat the in-clip marks as targets. If a beat lands ±1 s off, trim or extend the clip by 1 s in the edit rather than regenerating.
- **Sound design:** keep the BGM about 10–12 dB under the voice wherever there is narration, and let it swell only in the gaps (S001, S019, S048 end, S052).
- **Image generation is Google Flow only.** Step 1 subject sheets and Step 2 environment plates are unchanged (except the usage notes, which were regenerated for the new scene numbers). Step 3 reference images and Step 4 video prompts were rewritten to match the voice-over. One video prompt per scene.
- **Continuity chain:** every Step 3 prompt lists the previous scene's saved `SXXX_Ref.png` as its Scene Continuity Reference, plus the subject sheets in the shot and the correct environment plate. Generate the scenes in order.
- **Hard-rules reminder:** no on-screen text; human faces are fully visible and must match the face rows on the Step 1 sheets (fictional faces, no real likenesses); no gore or visible violence. Tragic events (the massacre, the death of the lone man, the 1988 killing) are shown only through symbols, sound and grief on faces.
- **Fact-check before publishing:** the candiru "enters the body" claim is largely folk myth. The 1997 anaconda attack on a gardener isn't a well-documented case. Check the Kawahiva "2011 drone" detail. The narration also calls Fawcett's city "City of Z", and the transcript has some mis-hearings (for example "City of Jet"), so recheck spellings if any text is added.
- **Reminder:** the GLOBAL LOCK BLOCK must be appended in full to the end of every prompt (Step 1, Step 2, every Step 3 and every Step 4) before submission.
