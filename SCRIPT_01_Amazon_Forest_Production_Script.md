# SCRIPT 01 — அமேசன் காடு: The Forest That Keeps Its Secrets
### [TEMPLATE v3 — Google Flow only · 8s scenes · subject sheets → environment plates → per-scene reference image → per-scene video · global lock appended to every prompt · no on-screen text · no visible faces · BGM + diegetic SFX only]

**Duration:** 7:30 | **Total Scenes:** 57 (8s each, final scene trimmed to land at 7:30)
**Image generation:** Google Flow only (Step 1 subject sheets, Step 2 environment plates, Step 3 scene reference images)
**Video generation:** Google Flow — one video prompt per scene, built from that scene's saved reference image, each carrying its own sound design
**Payoff:** The camera rises from one silhouetted survivor to the endless living canopy, so the viewer feels how many untold stories still hide in the forest, then ends on a night sky and one last firefly.
**Dialogue/Audio rule:** No dialogue in generated clips, only BGM and diegetic SFX. The Tamil voice-over is recorded separately and laid over the clips in the edit.

**Assumptions made for the blank input fields (change if needed):**
- **Style:** photorealistic cinematic documentary, 35mm anamorphic look.
- **Subjects:** the ones in Step 1.
- **Hard rules:** no on-screen text. No visible faces on any human, only silhouette, back-turned, distant or shadowed. No gore or violence on screen, only implied.
- **Real people:** the figures are generic period characters, not likenesses of real individuals.

**Segment map (Step 0 math: 7:30 = 450 s ÷ 8 = 56.25 → 57 scenes)**

| # | Segment | Scenes | Time |
|---|---|---|---|
| 1 | Hook | S001–S003 | 0:00–0:24 |
| 2 | Tanaru — The Man of the Hole | S004–S008 | 0:24–1:04 |
| 3 | Tanaru — The Lone Survivor | S009–S014 | 1:04–1:52 |
| 4 | Fawcett — The Obsession | S015–S020 | 1:52–2:40 |
| 5 | Fawcett — The Vanishing | S021–S027 | 2:40–3:36 |
| 6 | The River's Hidden Dangers | S028–S037 | 3:36–4:56 |
| 7 | The Rubber Tapper's Voice | S038–S043 | 4:56–5:44 |
| 8 | The Sacrifice & Legacy | S044–S048 | 5:44–6:24 |
| 9 | The Danger That Continues | S049–S055 | 6:24–7:20 |
| 10 | Final Wide / Outro | S056–S057 | 7:20–7:30 |

---

## ⚠️ GLOBAL LOCK BLOCK — append this in full to the END of every single prompt below (Step 1, Step 2, every Step 3, every Step 4)

```
GLOBAL LOCK:
CONTINUITY — Keep Tanaru-Man, Z-Party Explorers, Seringueiro Rubber Tapper, Scarlet-1 Macaw, Sucuri-Titan Anaconda, Red-Belly Piranha, Needle-Fish Candiru, Sky-Eye Survey Drone and Iron-Reaper Bulldozer in exact color/decal/proportion continuity from their saved reference sheets — no redesign, recolor, or scale drift. Keep every environment identical to its saved environment plate.
STYLE — Photorealistic cinematic documentary, 35mm anamorphic lens look, shallow depth of field on close shots, natural film grain, rich but natural color grade (deep emerald greens, warm amber light shafts, muted earth tones). Real material physics: wet leaves glisten, mud clumps, smoke diffuses, water refracts, wood grain and rust stay stable.
HARD RULES — No on-screen text, captions, logos or watermarks. Humans appear ONLY as silhouettes, back-turned, distant or with faces fully hidden in natural shadow, hat brims, feather headdress shade or backlight; never a readable face. No gore, no visible violence, no weapons pointed at a person: danger is shown by aftermath, shadow, sound and reaction of animals and objects. Historic and tragic events are implied through symbolic imagery (empty hammock, quiet clearing, dropped hat, shafts of light), never re-enacted.
ZERO AI ARTIFACTS — No morphing, warping, melting, flicker, extra or duplicated limbs/parts, floating debris, texture smearing, plastic skin or fur, inconsistent shadows, distorted hands or anatomy.
LIGHTING — Continuity of time-of-day per setting: rainforest = filtered green daylight with amber shafts; Tanaru = golden dusk; 1925 expedition = misty warm morning; river = bright overcast day; rubber trail = dawn; deforestation = smoky orange dusk; closing = night with stars and fireflies. No sudden light jumps between consecutive shots unless the script beat is a deliberate flash-cut.
AUDIO — Diegetic SFX + evolving cinematic BGM only; no dialogue, no singing, no spoken words in the generated clip.
CAMERA — Smooth, physically plausible motion only; each shot's opening camera motion matches the previous shot's closing motion vector for a seamless cut.
```

---

# STEP 1 — SUBJECT REFERENCE IMAGES (Google Flow — image generation ONLY)

### 1A. Lone Forest Dweller ("Tanaru-Man")
**Portrait Image Prompt — Google Flow:**
Full-body standing portrait of a lean, weathered indigenous man in his 50s from an uncontacted Amazon community, standing in a neutral relaxed pose, seen in three-quarter back view with his face turned away and hidden in deep natural shadow under long dark hair. Bare torso with faint red urucum (annatto) pigment on the upper arms, plain woven cotton waist cord and short loincloth, a straight hand-carved wooden bow about 1.5 m long with fibre string in his left hand, and three cane arrows with feather fletching in a woven-fibre quiver on his back. Skin shows realistic sun-weathered texture and old scars. Camera at eye level, soft grey studio-style background, warm key light from the upper left, macro-level detail on fibre weave, feather barbs and skin texture. Respectful, dignified, no face visible. Locked reference design.
**Save as:** `TanaruMan_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `TanaruMan_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT (face kept in natural shadow), REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE (feet and ground contact view), neutral grey background, matched lighting/scale, neutral pose in every panel.
**Save as:** `TanaruMan_6Angle.png`
**Usage note:** Attach both files to every scene where the lone man appears (S010, S011, S013, S055).

### 1B. 1925 Expedition Party ("Z-Party Explorers")
**Portrait Image Prompt — Google Flow:**
Group portrait of three 1920s British explorers standing in a line: a tall lean older colonel in the centre with a waxed-canvas khaki jacket, riding breeches, leather puttees, a wide-brim pith sun helmet and a leather map case; a young man on his left in a similar khaki outfit with a canvas rucksack and a rolled bedroll; a companion on his right with a slouch hat, a brass compass at his belt and a machete in a leather sheath. All faces hidden under hat brims and shadow, viewed slightly from behind. Worn, sweat-stained fabrics, brass buckles, cracked leather. Grey neutral background, soft key light from upper left, macro detail on stitching, brass patina and leather grain. Locked reference design.
**Save as:** `Explorers_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Explorers_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround of the same three-man group: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE (boots and ground), neutral grey background, matched lighting/scale, neutral pose in every panel.
**Save as:** `Explorers_6Angle.png`
**Usage note:** Attach to every scene showing the 1925 party (S015–S022).

### 1C. Rubber Tapper ("Seringueiro")
**Portrait Image Prompt — Google Flow:**
Full-body portrait of a Brazilian rubber tapper (seringueiro) in his 40s, standing in a relaxed pose seen from behind, face hidden under a wide straw hat. Faded blue cotton shirt with rolled sleeves, worn brown trousers, rubber boots, a small curved tapping knife at his belt, a tin cup and a canvas shoulder bag, a headlamp on the hat brim. Realistic sun-worn fabric, mud on boots, latex stains on the sleeves. Grey background, warm key light from upper right, macro detail on straw weave and latex-stained cloth. Locked reference design.
**Save as:** `Tapper_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Tapper_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT (face shadowed by hat), REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE (boots and ground contact), neutral grey background, matched lighting/scale, neutral pose in every panel.
**Save as:** `Tapper_6Angle.png`
**Usage note:** Attach to S038–S046 and S048.

### 1D. Scarlet Macaw ("Scarlet-1")
**Portrait Image Prompt — Google Flow:**
A single adult scarlet macaw perched on a natural branch, 85 cm long, vivid scarlet body, yellow-and-blue wing coverts, blue tail-feather tips, pale bare face patch, dark curved beak. Side-profile view, sharp macro-level feather barb detail, grey neutral background, soft key light from the upper left. Locked reference design.
**Save as:** `Macaw_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Macaw_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral grey background, matched lighting/scale, perched pose in every panel with wings folded.
**Save as:** `Macaw_6Angle.png`
**Usage note:** Attach to S014 and any scene with a macaw or macaw feathers.

### 1E. Green Anaconda ("Sucuri-Titan")
**Portrait Image Prompt — Google Flow:**
A giant green anaconda, 5.5 m long, thick as a man's thigh, olive-green skin with rounded black blotches in two alternating rows, a dark stripe behind the eye, yellow-cream belly edge, coiled loosely in a S-curve on a neutral surface. Wet glossy scales with realistic per-scale detail. Camera at three-quarter high angle, grey background, soft key light upper left, macro detail on scale texture and the amber eye with a vertical pupil. Locked reference design.
**Save as:** `Anaconda_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Anaconda_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT (head-on), REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE (belly scales), neutral grey background, matched lighting/scale, same loose S-coil pose in every panel.
**Save as:** `Anaconda_6Angle.png`
**Usage note:** Attach to S034–S036 and S037 if the coil is visible.

### 1F. Red-Bellied Piranha ("Red-Belly Piranha")
**Portrait Image Prompt — Google Flow:**
A single adult red-bellied piranha, 25 cm, silver-grey flanks with darker speckles, deep red-orange belly and gill area, a blunt head with an underbite and a row of triangular razor teeth, forked tail edged in black. Side profile, mid-water pose, neutral grey gradient background as if photographed in a tank, key light upper left, macro detail on scales and teeth. Locked reference design.
**Save as:** `Piranha_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Piranha_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT (open-mouth teeth view), REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral grey background, matched lighting/scale, neutral swimming pose in every panel.
**Save as:** `Piranha_6Angle.png`
**Usage note:** Attach to S030–S033. For a shoal, duplicate the same fish design at consistent scale.

### 1G. Candiru ("Needle-Fish")
**Portrait Image Prompt — Google Flow:**
A tiny translucent candiru catfish, 4 cm long, eel-like slender body, near-transparent pinkish-grey skin with a visible spine, small barbels, backward-pointing gill spines, shown in extreme macro, side profile, floating in clear water against a neutral grey-blue background, key light upper left, crisp macro detail. Locked reference design.
**Save as:** `Candiru_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Candiru_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral grey background, matched lighting/scale, neutral pose in every panel.
**Save as:** `Candiru_6Angle.png`
**Usage note:** Attach to S028–S029 only.

### 1H. Survey Drone ("Sky-Eye")
**Portrait Image Prompt — Google Flow:**
A small white fixed-wing survey drone with a 1.8 m wingspan, matte white fuselage, slim swept wings, a rear pusher propeller, a small camera gimbal pod under the nose, a thin dark-grey antenna, no text or logos anywhere. Displayed on a neutral grey surface, three-quarter front view, key light upper left, macro detail on carbon-fibre panel seams and the propeller. Locked reference design.
**Save as:** `Drone_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Drone_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral grey background, matched lighting/scale, neutral pose in every panel.
**Save as:** `Drone_6Angle.png`
**Usage note:** Attach to S049–S051.

### 1I. Logging Bulldozer ("Iron-Reaper")
**Portrait Image Prompt — Google Flow:**
A heavy yellow crawler bulldozer, 1:1 scale, mud-caked steel tracks, a wide front blade with worn edge, a rear ripper claw, a cab with a dark tinted windshield (no operator visible), a black vertical exhaust stack, dusty red-earth splatter over the yellow paint, no brand names or logos. Three-quarter front view on a neutral grey surface, key light upper left, macro detail on track links, hydraulic rams and paint chips. Locked reference design.
**Save as:** `Bulldozer_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Bulldozer_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral grey background, matched lighting/scale, neutral pose in every panel.
**Save as:** `Bulldozer_6Angle.png`
**Usage note:** Attach to S009 and S053.

---

# STEP 2 — ENVIRONMENT REFERENCE IMAGES (Google Flow — image generation ONLY)

### 2A. Setting A — Primary Rainforest Interior (green gloom, daytime)
**Environment Image Prompt — Google Flow:**
Wide interior view of dense primary Amazon rainforest at midday: towering buttressed trunks, hanging lianas, layered canopy so thick that only a few thin amber shafts of light reach the leaf-litter floor, mist between trunks, giant ferns, mossy fallen logs, wet leaves and fungi. Deep emerald green tones. Completely empty of humans, animals and machines — pure environment plate.
**Save as:** `SettingA_Env.png`
**Usage note:** S002, S008, S011, S024, S025, S027, S052.

### 2B. Setting B — Tanaru Clearing & Palm-Thatch Hut (golden dusk)
**Environment Image Prompt — Google Flow:**
A small forest clearing at golden dusk with a simple open-fronted palm-thatch hut (visible earthen floor, an empty woven hammock hung between two poles, a cold fire pit, a few clay pots), several deep round pits dug into the red earth around the clearing edge, scattered banana plants, a jungle wall behind. Warm amber low sun rays through haze. Completely empty of any people or animals — pure environment plate.
**Save as:** `SettingB_Env.png`
**Usage note:** S005–S007, S010, S012–S014, S055.

### 2C. Setting C — 1925 Expedition River-Camp & Jungle Trail (misty warm morning)
**Environment Image Prompt — Google Flow:**
A narrow muddy jungle trail beside a slow tributary at early morning, warm pink-gold light in the mist, a small abandoned camp with a canvas tent, a wooden supply crate, a folded canvas tarpaulin and an unlit lantern, tall trees framing the trail, vines. Completely empty of people — pure environment plate.
**Save as:** `SettingC_Env.png`
**Usage note:** S015–S023, S026.

### 2D. Setting D — Amazon River & Underwater Shallows (bright overcast)
**Environment Image Prompt — Google Flow:**
A wide brown-tea Amazon tributary under bright overcast light, a sandy bank with half-submerged roots and flooded trees, floating lily pads and driftwood. Include a matching underwater view: murky tea-brown shallow water with drifting sunlit particles, submerged roots and sand. Completely empty of animals and people — pure environment plate.
**Save as:** `SettingD_Env.png`
**Usage note:** S028–S037.

### 2E. Setting E — Rubber-Tapping Trail (dawn)
**Environment Image Prompt — Google Flow:**
A narrow forest trail at dawn lined with rubber trees carrying diagonal cut scars and small tin cups collecting white latex, low mist, soft gold rim light through the trunks, mud path, dew on leaves. Completely empty of people — pure environment plate.
**Save as:** `SettingE_Env.png`
**Usage note:** S038–S042, S047, S048.

### 2F. Setting F — Wooden Rural House Backyard (dusk)
**Environment Image Prompt — Google Flow:**
The back yard of a simple wooden stilt house at blue-hour dusk, a wooden porch with a hanging towel, a clothesline, a water barrel, a dirt yard, and a dark treeline behind; a single warm light glows from a window. Quiet, ominous stillness. Completely empty of people — pure environment plate.
**Save as:** `SettingF_Env.png`
**Usage note:** S043–S046.

### 2G. Setting G — Aerial Canopy at Dawn with Forest-Edge Frontier
**Environment Image Prompt — Google Flow:**
High aerial view of an endless emerald Amazon canopy at dawn with rolling mist. On the right side of the frame the canopy ends abruptly at a line of cleared brown pasture and thin roads. One tiny clearing with a thin thread of smoke sits deep in the canopy. Completely empty of vehicles, drones, animals and people — pure environment plate.
**Save as:** `SettingG_Env.png`
**Usage note:** S001, S003, S004, S047, S049–S051, S054, S056.

### 2H. Setting H — Deforestation Frontier (smoky orange dusk)
**Environment Image Prompt — Google Flow:**
A burned and cleared forest frontier at smoky orange dusk: charred stumps, glowing embers, fresh red earth, a bulldozer-cut road, fallen giant trunks, smoke columns rising into a hazy sun, an intact wall of forest at the edge. Completely empty of humans, animals and machines — pure environment plate.
**Save as:** `SettingH_Env.png`
**Usage note:** S009, S053, S054.

### 2I. Setting I — Night Forest with Stars & Fireflies
**Environment Image Prompt — Google Flow:**
A quiet forest clearing at night, a huge starry sky, Milky Way overhead, a black silhouette treeline, hundreds of soft-glowing fireflies among the ferns, a faint river mist. Completely empty of humans, animals and machines — pure environment plate.
**Save as:** `SettingI_Env.png`
**Usage note:** S057.

---

# STEP 3 & STEP 4 — SCENES

**How each scene is shaped:**
Header line (scene number, label, timestamp) → Step 3 Ingredients (subject sheet · environment plate · previous scene's `_Ref.png`) → Step 3 Reference Image Prompt → Step 4 Ingredients (the saved `_Ref.png` as starting frame) → Video Prompt → Sound → Cut→ to the next scene.
Append the GLOBAL LOCK BLOCK to the end of every Step 3 and Step 4 prompt.

---

### Segment 1 — Hook (Scenes 1–3)

**S001 — Endless canopy wide reveal | 0:00–0:08**
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: `SettingG_Env.png` · Scene Continuity Reference: none (first scene in the series)
Step 3 — Reference Image Prompt (Google Flow):
Ultra-wide drone-style aerial shot at dawn over an endless emerald Amazon canopy, thick mist rolling between the treetops, a pale gold sun on the horizon, and an enormous sense of scale with no roads or buildings in the foreground.
Save as: `S001_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S001_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S001_Ref.png`. The camera glides slowly forward and drifts slightly downward over the canopy, mist curling around the treetops, the sun edging up and warming the light, a flock of distant parrots passing far below the frame. Slow, majestic, no cuts.
Sound (BGM+SFX, no dialogue): Deep low string drone and distant war-drum heartbeat fade in; wind rush, birdsong swells and a distant howler-monkey call.
Cut→S002: Hard cut to a low-angle shot as if the camera plunges beneath the canopy.

**S002 — Sunlight that never touches the ground | 0:08–0:16**
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: `SettingA_Env.png` · Scene Continuity Reference: `S001_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Extreme low-angle, looking straight up through a towering tunnel of tree trunks and layered leaves; sunlight is visible only as a few dying amber shafts high above, while the forest floor around the camera is deep in green shadow with mist.
Save as: `S002_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S002_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S002_Ref.png`. The camera tilts slowly upward from the leaf-litter to the canopy while light shafts fade and thin out; drifting mist and a few falling leaves cross the frame, and a rack focus shifts from a mossy trunk in the foreground to the distant bright canopy.
Sound (BGM+SFX, no dialogue): Music thins to a single sustained cello note; dripping water, insect hum and distant bird echoes; the shafts of light fade with a soft tonal whoosh.
Cut→S003: Match cut on the bright canopy gap, becoming an aerial view through the same gap.

**S003 — The smoke thread of hidden people | 0:16–0:24**
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: `SettingG_Env.png` · Scene Continuity Reference: `S002_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Aerial view pushing through a small gap in the canopy toward one tiny clearing deep in the forest, with a single thin thread of smoke rising straight up into the morning mist; no people visible, only a suggestion that someone lives there.
Save as: `S003_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S003_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S003_Ref.png`. A slow push-in toward the smoke thread, the mist parting and the canopy tilting past; the smoke wobbles gently in the still air; the camera stops on the tiny clearing as the light warms slightly. Mysterious, held breath.
Sound (BGM+SFX, no dialogue): Suspense bed slowly rises with a low pulsing synth; a single distant wooden knock, then a hush; a subtle sting as the smoke thread comes into focus.
Cut→S004: Cross-dissolve into a wider aerial view showing this small forest as an island.

---

### Segment 2 — Tanaru: The Man of the Hole (Scenes 4–8)

**S004 — Green island in a cleared land | 0:24–0:32**
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: `SettingG_Env.png` · Scene Continuity Reference: `S003_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
High aerial shot descending toward a small isolated island of dense green forest surrounded on all sides by cleared brown pasture and thin dirt roads, dawn light and rising mist, the island glowing in a lone patch of sun.
Save as: `S004_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S004_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S004_Ref.png`. The camera slowly descends and orbits about 30° around the forest island, revealing how sharply the tree line stops at the pasture; the sun brightens the island, mist drifting off the treetops.
Sound (BGM+SFX, no dialogue): A sombre, low piano motif enters over the string bed; wind, and distant cattle lowing far away.
Cut→S005: Hard cut to a macro shot at ground level inside that forest.

**S005 — The first hole | 0:32–0:40**
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: `SettingB_Env.png` · Scene Continuity Reference: `S004_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Macro close-up at the rim of a deep, perfectly round hand-dug pit in red earth, soil crumbling at the edge, a few dry leaves on the lip, and dark depth below, with the hut blurred in the golden dusk background.
Save as: `S005_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S005_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S005_Ref.png`. The camera slowly pushes toward the rim and tilts down into the pit; a small clump of soil tumbles in and disappears into the dark; a leaf floats down after it. Focus racks from the lip to the depths.
Sound (BGM+SFX, no dialogue): Music drops to a low pulsing tone; the crumble and soft thud of soil falling, then a hollow echo; a distant bird cut off.
Cut→S006: Match cut on the pit's dark circle, opening into the path toward the hut.

**S006 — Toward the hut | 0:40–0:48**
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: `SettingB_Env.png` · Scene Continuity Reference: `S005_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Low-angle tracking view along the forest floor between ferns and dug pits, the palm-thatch hut glowing in the golden dusk ahead, sun rays slicing through smoke haze, no people present.
Save as: `S006_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S006_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S006_Ref.png`. The camera tracks slowly forward at ground level, passing ferns in the foreground, gliding past two pits toward the hut; dust motes drift in the light; it ends holding the hut centred in frame.
Sound (BGM+SFX, no dialogue): Soft footstep-like percussion, distant twilight birdsong, insects; the music becomes tender and lonely.
Cut→S007: Hard cut to inside the hut, pushing in through the open front.

**S007 — The empty hole inside the hut | 0:48–0:56**
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: `SettingB_Env.png` · Scene Continuity Reference: `S006_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Interior view of the palm-thatch hut looking from the open front, a round pit dug into the earthen floor at the centre, an empty hammock hanging above and to the side, golden dusk light streaming across the floor.
Save as: `S007_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S007_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S007_Ref.png`. A slow push-in toward the pit, the empty hammock swaying slightly, dust motes floating in the light; a rack focus from the hammock to the pit ends on the dark hole.
Sound (BGM+SFX, no dialogue): Music thins to a hollow held note; the creak of hammock rope, a faint wind through thatch; a soft low sting on the pit.
Cut→S008: Match cut on the pit's circle, becoming a top-down view of several pits.

**S008 — Pits across the forest floor | 0:56–1:04**
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: `SettingA_Env.png` · Scene Continuity Reference: `S007_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Straight top-down view of the forest floor with several deep round pits scattered among leaf-litter, and a line of bare footprints in the mud winding between them into the trees; green dim light, nothing else in frame.
Save as: `S008_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S008_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S008_Ref.png`. The camera rises slowly straight up from the pits, so the scattered holes form a pattern, then follows the footprints toward the trees; a few leaves drift down. Smooth, steady.
Sound (BGM+SFX, no dialogue): Music builds slowly with soft strings; rustle of leaves, a distant single bird call; an ambient rise ending with a quiet sting.
Cut→S009: Hard cut to a smoky orange wide shot of the frontier.

---

### Segment 3 — Tanaru: The Lone Survivor (Scenes 9–14)

**S009 — Land grabbers arrive | 1:04–1:12**
Step 3 Ingredients: Vehicle/Subject Reference Image: `Bulldozer_Portrait.png`, `Bulldozer_6Angle.png` · Environment Reference Image: `SettingH_Env.png` · Scene Continuity Reference: `S008_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Wide low-angle shot at smoky orange dusk of a yellow bulldozer, seen from the front at a distance, pushing into the edge of the forest wall, with dust and smoke around its tracks and a fallen trunk in front of the blade; no operator visible.
Save as: `S009_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S009_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S009_Ref.png`. The bulldozer creeps forward, its blade pushing a fallen trunk and soil; dust and smoke roll past the camera; the camera holds static, then dollies back slowly as the machine advances. Heavy, ominous.
Sound (BGM+SFX, no dialogue): Music turns dark with a low brass drone and slow taiko hits; diesel engine rumble, tracks clanking, wood cracking, soil scraping.
Cut→S010: Hard cut to a silhouette at the forest edge, facing the machine sound.

**S010 — The warning arrow | 1:12–1:20**
Step 3 Ingredients: Vehicle/Subject Reference Image: `TanaruMan_Portrait.png`, `TanaruMan_6Angle.png` · Environment Reference Image: `SettingB_Env.png` · Scene Continuity Reference: `S009_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Backlit silhouette of the lone man at the edge of the clearing, seen from behind at golden dusk, bow raised and pointed toward the trees, feathered arrow on the string; no face visible and no target in frame, only a hazy dark tree line and orange smoke.
Save as: `S010_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S010_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S010_Ref.png`. The camera pushes in slowly from behind his shoulder; the man holds the drawn bow, still and tense; a breeze moves the smoke; he lowers the bow slowly and stays standing. Sombre, restrained.
Sound (BGM+SFX, no dialogue): Music thins to a single held string note; bow-string creak, a distant engine fading away, a cicada drone; a soft low sting as he lowers the bow.
Cut→S011: Cross-dissolve to a far-off observer's view through foliage.

**S011 — Watched from afar | 1:20–1:28**
Step 3 Ingredients: Vehicle/Subject Reference Image: `TanaruMan_Portrait.png` · Environment Reference Image: `SettingA_Env.png` · Scene Continuity Reference: `S010_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Long telephoto shot compressed through blurred foreground leaves, far away a small silhouetted figure at his hut fire in golden dusk light; heavy leaf blur frames the image like a hidden observer's view.
Save as: `S011_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S011_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S011_Ref.png`. A slow lateral creep behind the foreground leaves as the tiny distant figure tends the fire and then turns away into the hut; the leaves sway; focus racks from foreground leaves to the far clearing.
Sound (BGM+SFX, no dialogue): Quiet, held-breath ambience with faint crackling fire, insects and a very soft pad; a distant woodpecker.
Cut→S012: Match cut on the fire's glow into a time-lapse of the clearing.

**S012 — 26 years pass | 1:28–1:36**
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: `SettingB_Env.png` · Scene Continuity Reference: `S011_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Locked-off wide shot of the empty clearing and hut at golden dusk, a sky full of streaking clouds above, the fire pit glowing faintly, the hammock swaying, no people visible.
Save as: `S012_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S012_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S012_Ref.png`. A time-lapse: clouds rush overhead, light shifts from dusk to night to dawn to day and back to dusk several times, the shadows sweep, leaves grow around the clearing slightly; the camera stays locked and the hut itself does not change.
Sound (BGM+SFX, no dialogue): Music becomes slow and melancholic with a solo flute; fast wind whoosh, day-night bird and cricket cycles, passing rain; a soft chime at each dusk.
Cut→S013: Hard cut to a close view of him alone at the fire.

**S013 — Alone at the fire | 1:36–1:44**
Step 3 Ingredients: Vehicle/Subject Reference Image: `TanaruMan_Portrait.png`, `TanaruMan_6Angle.png` · Environment Reference Image: `SettingB_Env.png` · Scene Continuity Reference: `S012_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Medium shot from behind and slightly above of the lone man sitting cross-legged at a small fire in front of his hut, silhouetted by the flames, face hidden, the dark forest wall around him and nobody else in frame; the mood is deep loneliness.
Save as: `S013_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S013_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S013_Ref.png`. A very slow push-in from behind him; the flames flicker, sparks rise, and he lifts his head slightly toward the dark trees, then stays still. The camera ends framing just his silhouette against the fire glow.
Sound (BGM+SFX, no dialogue): Solo flute over a soft string pad, the fire crackling, insects and a distant owl; the music dips to near silence on his head-lift.
Cut→S014: Slow cross-dissolve into a glimpse of a macaw feather in the next scene.

**S014 — Macaw feathers on the hammock | 1:44–1:52**
Step 3 Ingredients: Vehicle/Subject Reference Image: `Macaw_Portrait.png`, `Macaw_6Angle.png` · Environment Reference Image: `SettingB_Env.png` · Scene Continuity Reference: `S013_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Medium-low shot inside the hut in soft warm golden light, a woven hammock hanging empty and still, with scarlet-and-blue macaw feathers laid carefully and symmetrically along its length; the fire pit is cold, a single scarlet macaw sits on the far roof pole, and no person is visible.
Save as: `S014_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S014_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S014_Ref.png`. The camera dollies slowly sideways along the hammock, feathers trembling in a faint breeze; a single feather lifts and settles again; the macaw on the pole tilts its head and stays; the camera ends on a close, soft-focus view of the feathers. Quiet, reverent.
Sound (BGM+SFX, no dialogue): Solo flute resolves into a slow, mournful string chord; a faint breeze through thatch, a soft feather rustle, one distant macaw call, then silence.
Cut→S015: Cross-dissolve, the scarlet feather colour melting into the dawn mist of a 1925 trail.

---

### Segment 4 — Fawcett: The Obsession (Scenes 15–20)

**S015 — 1925, the trail head | 1:52–2:00**
Step 3 Ingredients: Vehicle/Subject Reference Image: `Explorers_Portrait.png`, `Explorers_6Angle.png` · Environment Reference Image: `SettingC_Env.png` · Scene Continuity Reference: `S014_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Wide establishing shot in warm misty morning light on a muddy jungle trail, three khaki-clad explorers standing in a line seen from behind at the trail head, faces unseen under hat brims, looking into a wall of towering trees; the small camp and canvas tent sit at frame left.
Save as: `S015_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S015_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S015_Ref.png`. A slow crane-up from behind the trio, mist drifting between trunks; the colonel in the centre lifts a hand to point ahead, and the three step forward together; the camera settles at a higher wide angle as they enter the trail.
Sound (BGM+SFX, no dialogue): Adventurous, gentle orchestral theme enters with pizzicato strings and a soft snare; boots in mud, canvas rustle, a dawn bird chorus.
Cut→S016: Hard cut to a macro on a map lying on a supply crate.

**S016 — The map with the mark | 2:00–2:08**
Step 3 Ingredients: Vehicle/Subject Reference Image: `Explorers_Portrait.png` · Environment Reference Image: `SettingC_Env.png` · Scene Continuity Reference: `S015_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Macro top-down-angled view of a stained hand-drawn map spread on a wooden crate beside an unlit lantern, ink rivers winding across it with one circled geometric glyph deep in the unmapped centre, no readable letters or words anywhere; warm morning light on the paper grain.
Save as: `S016_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S016_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S016_Ref.png`. The camera glides slowly along a river line on the map toward the circled glyph, paper fibres and ink texture in sharp detail, a small moth landing on the map's edge; the focus racks from the paper edge to the glyph and holds.
Sound (BGM+SFX, no dialogue): The theme drops to a hushed harp and low strings; paper crinkle, a faint lantern glass tick, a moth's wing flutter; a soft mystery sting on the glyph.
Cut→S017: Hard cut to a low-angle tracking shot of boots on the trail.

**S017 — Boots in the mud | 2:08–2:16**
Step 3 Ingredients: Vehicle/Subject Reference Image: `Explorers_Portrait.png`, `Explorers_6Angle.png` · Environment Reference Image: `SettingC_Env.png` · Scene Continuity Reference: `S016_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Very low-angle shot at mud level of three pairs of leather boots and puttees marching along the trail toward the camera, mist behind them, each print filling with water; no faces visible.
Save as: `S017_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S017_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S017_Ref.png`. The camera tracks backwards at ground level ahead of the marching boots, mud squelching, water splashing from a puddle, and a rucksack strap swinging in the upper frame; steady rhythmic pace, no cuts.
Sound (BGM+SFX, no dialogue): The theme picks up energy with a steady marching pulse; squelching boots, splashes, leather creak, insects.
Cut→S018: Hard cut to a macro on the brass compass at the belt.

**S018 — The trembling compass | 2:16–2:24**
Step 3 Ingredients: Vehicle/Subject Reference Image: `Explorers_Portrait.png` · Environment Reference Image: `SettingC_Env.png` · Scene Continuity Reference: `S017_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Extreme macro of an old brass compass lying open on a mossy log, glass fogged at the edges, the needle steady on north, dew drops on the brass, blurred jungle in the background, no legible markings.
Save as: `S018_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S018_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S018_Ref.png`. The needle holds still, then begins to tremble and slowly swing off-axis; a single dew drop rolls down the brass; the camera pushes in slightly and ends on the shivering needle. Tense.
Sound (BGM+SFX, no dialogue): The music thins to a low held drone; fine metallic ticks of the needle, a drip, a distant animal call; a tense rising tone at the end.
Cut→S019: Cut to a high aerial rise showing the party tiny among giant trees.

**S019 — Swallowed by the forest | 2:24–2:32**
Step 3 Ingredients: Vehicle/Subject Reference Image: `Explorers_Portrait.png` · Environment Reference Image: `SettingC_Env.png` · Scene Continuity Reference: `S018_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Drone-style high angle looking down through a gap in giant trees at three tiny explorers on a narrow trail, the canopy closing in on all sides, warm morning mist between the leaves.
Save as: `S019_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S019_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S019_Ref.png`. The camera rises slowly straight up as the three tiny figures walk on and the leaves close over them, until only green canopy and mist fill the frame; the walk continues at a calm pace.
Sound (BGM+SFX, no dialogue): Orchestral swell with a soaring horn, then a hush as the canopy closes; wind rush and distant birds fading.
Cut→S020: Cut to a rack-focus close shot of the leader gazing ahead.

**S020 — The colonel's resolve | 2:32–2:40**
Step 3 Ingredients: Vehicle/Subject Reference Image: `Explorers_Portrait.png` · Environment Reference Image: `SettingC_Env.png` · Scene Continuity Reference: `S019_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Medium shot from behind and slightly to the side of the tall colonel in his pith helmet standing on a mossy rock above the river, leather map case at his hip, the other two men blurred behind, warm misty light, face hidden.
Save as: `S020_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S020_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S020_Ref.png`. A rack focus from the map case in the foreground to the misty far treeline, the colonel standing still, his jacket stirring in the breeze; the camera pushes in gently to his shoulder. Steady and resolute.
Sound (BGM+SFX, no dialogue): The theme reaches a hopeful, determined peak with brass and strings, then softens; river flow, leather creak, wind.
Cut→S021: Cross-dissolve into a macro of a sealed letter.

---

### Segment 5 — Fawcett: The Vanishing (Scenes 21–27)

**S021 — The last letter | 2:40–2:48**
Step 3 Ingredients: Vehicle/Subject Reference Image: `Explorers_Portrait.png` · Environment Reference Image: `SettingC_Env.png` · Scene Continuity Reference: `S020_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Macro of a folded letter sealed with a red wax seal on a wooden crate, the paper edge showing faint blurred ink lines that are not legible, a lantern glowing behind it, a canvas tent in soft focus.
Save as: `S021_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S021_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S021_Ref.png`. The lantern flame flickers, casting moving shadows over the wax seal; the camera dollies in very slowly; a warm breeze lifts the letter's corner and it settles; the light slowly dims.
Sound (BGM+SFX, no dialogue): A lonely solo violin over a soft pad; lantern flame flutter, paper rustle, a soft night insect chorus growing.
Cut→S022: Hard cut to a static wide shot of the trail in thick fog.

**S022 — Into the fog | 2:48–2:56**
Step 3 Ingredients: Vehicle/Subject Reference Image: `Explorers_Portrait.png`, `Explorers_6Angle.png` · Environment Reference Image: `SettingC_Env.png` · Scene Continuity Reference: `S021_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Locked-off wide shot down a narrow jungle trail in thick white fog, three small explorers seen from behind walking away from the camera, already half-swallowed by mist, huge tree trunks lining both sides.
Save as: `S022_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S022_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S022_Ref.png`. The camera stays locked; the three explorers keep walking away, growing smaller and passing behind trunks and into the fog until the trail is empty and only drifting mist remains. They exit naturally, with no morphing or fading effects.
Sound (BGM+SFX, no dialogue): The violin fades to a single note; footsteps grow fainter until they stop; a final hush of wind and a distant bird call.
Cut→S023: Hard cut to the same trail, empty and overgrown, showing decades pass.

**S023 — The camp, abandoned | 2:56–3:04**
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: `SettingC_Env.png` · Scene Continuity Reference: `S022_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Medium-wide view of the empty camp in misty light, the canvas tent sagging, the crate and unlit lantern untouched, no people, a lone silence hanging over the clearing.
Save as: `S023_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S023_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S023_Ref.png`. A slow push-in as a time-lapse plays: seasons pass, light shifts, vines creep up over the crate and tent, the canvas fades and rots, moss covers the lantern; the camera ends close on the vine-wrapped crate.
Sound (BGM+SFX, no dialogue): A hollow low pad with a slow-ticking clock-like pulse; wind, rain bursts and creaking canvas, an occasional bird call at each season shift.
Cut→S024: Match cut on the mud floor, becoming a top-down view of many footprints.

**S024 — A century of searchers | 3:04–3:12**
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: `SettingA_Env.png` · Scene Continuity Reference: `S023_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Straight top-down view of the forest floor with many overlapping boot prints in mud and leaf-litter, all leading into the deep forest, some sharp and fresh, some half-washed away, dim green light.
Save as: `S024_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S024_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S024_Ref.png`. The camera glides slowly forward over the prints, following them; rain begins and softens the older prints while new ones seem to hold, ending with the trail of prints vanishing into darkness between roots.
Sound (BGM+SFX, no dialogue): The music builds with slowly repeating strings; the patter of rain, mud squelch, a distant thunder rumble.
Cut→S025: Hard cut to a macro on a bleached bone.

**S025 — The wrong bones | 3:12–3:20**
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: `SettingA_Env.png` · Scene Continuity Reference: `S024_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Macro of a single old, bleached long bone half-buried in mossy leaf-litter beside a rotted scrap of khaki cloth, a shaft of amber light across it, ferns in the blurred background; respectful and non-graphic.
Save as: `S025_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S025_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S025_Ref.png`. The camera pushes in slowly across the bone, a beetle crossing the cloth, a droplet falling from a leaf onto the moss; the light shaft dims and the focus racks to the dark background.
Sound (BGM+SFX, no dialogue): A dissonant, low sustained string cluster; a droplet plink, a beetle's tiny rustle, a hollow wind tone.
Cut→S026: Hard cut to a low-angle view of a hat left on a branch.

**S026 — Those who never returned | 3:20–3:28**
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: `SettingC_Env.png` · Scene Continuity Reference: `S025_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Low-angle shot of an old weathered pith helmet hanging on a broken branch beside the trail, a rotting rucksack strap at the base of the tree, mist and dim green light, silent and empty.
Save as: `S026_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S026_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S026_Ref.png`. The camera orbits slowly about 40° around the hanging helmet while mist drifts through and the helmet sways gently; the trail behind is empty; the orbit ends on the helmet framed against dark trees.
Sound (BGM+SFX, no dialogue): The music drops to a single bowed note; a wood creak from the swaying helmet, insect hush, a far-off, fading bird.
Cut→S027: Cross-dissolve into a misty reveal of overgrown stone steps.

**S027 — The City of Z, or nothing | 3:28–3:36**
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: `SettingA_Env.png` · Scene Continuity Reference: `S026_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Wide, mysterious view through dense mist of faint moss-covered stone terraces and steps half-hidden beneath giant tree roots, warm amber light shafts breaking through the canopy; it is unclear whether these are ruins or natural rock.
Save as: `S027_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S027_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S027_Ref.png`. The camera glides slowly forward and up the stairs, mist parting and closing to hide the summit each time; the light shifts subtly; the shot ends with the top swallowed in fog.
Sound (BGM+SFX, no dialogue): A hopeful yet uneasy theme on solo horn and low strings, rising and left unresolved; wind, distant jungle calls, a low tonal sting as the mist closes.
Cut→S028: Whip pan into the river, a splash-flash transition into an underwater macro.

---

### Segment 6 — The River's Hidden Dangers (Scenes 28–37)

**S028 — The tiny candiru | 3:36–3:44**
Step 3 Ingredients: Vehicle/Subject Reference Image: `Candiru_Portrait.png`, `Candiru_6Angle.png` · Environment Reference Image: `SettingD_Env.png` · Scene Continuity Reference: `S027_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Extreme underwater macro of a tiny translucent candiru catfish hanging in murky tea-brown water, sun-lit particles drifting around it, a submerged root blurred behind, the fish barely the size of a finger against the scale of the river.
Save as: `S028_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S028_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S028_Ref.png`. The camera drifts slowly toward the fish as it hovers, its gills pulsing and barbels twitching; particles swirl past in a gentle current; the fish turns its head toward a faint plume in the water and stays alert.
Sound (BGM+SFX, no dialogue): Muffled underwater ambience with a deep low drone; soft bubble pops, water movement, a faint high sting on the fish's turn.
Cut→S029: Match cut on the fish's silhouette into a top-down river surface shot.

**S029 — A shadow in the shallows | 3:44–3:52**
Step 3 Ingredients: Vehicle/Subject Reference Image: `Candiru_Portrait.png` · Environment Reference Image: `SettingD_Env.png` · Scene Continuity Reference: `S028_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Top-down view through clear shallow tea-coloured water over a sandy bed, a thin dark needle-like shadow of the candiru slipping along the sand toward a submerged root, rings of ripples on the surface above, bright overcast light.
Save as: `S029_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S029_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S029_Ref.png`. The camera glides slowly forward above the surface, following the fish's shadow as it darts under the root and vanishes into darkness; ripples fade on the surface; a single leaf floats by.
Sound (BGM+SFX, no dialogue): Suspense pulse over a low string bed; light water lapping, a soft plink, a quick whoosh as the fish darts away.
Cut→S030: Hard cut to a low-angle underwater view of a shoal.

**S030 — The piranha shoal | 3:52–4:00**
Step 3 Ingredients: Vehicle/Subject Reference Image: `Piranha_Portrait.png`, `Piranha_6Angle.png` · Environment Reference Image: `SettingD_Env.png` · Scene Continuity Reference: `S029_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Low-angle underwater shot looking up, a shoal of about fifteen red-bellied piranhas swimming in murky tea-brown water beneath the bright silver surface, sunlight rays cutting through, roots framing the shot.
Save as: `S030_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S030_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S030_Ref.png`. The shoal glides across the frame in loose formation, turning in unison and flashing silver as they change direction, while the camera drifts slowly upward and sideways; movement is calm and orderly.
Sound (BGM+SFX, no dialogue): The music turns thrilling with a low pulsing bass and rising strings; muffled water rush, soft bubbles, tail flicks.
Cut→S031: Hard cut to a macro on a piranha's teeth.

**S031 — The truth about the teeth | 4:00–4:08**
Step 3 Ingredients: Vehicle/Subject Reference Image: `Piranha_Portrait.png`, `Piranha_6Angle.png` · Environment Reference Image: `SettingD_Env.png` · Scene Continuity Reference: `S030_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Extreme macro of a single red-bellied piranha's head in profile, mouth slightly open to show the row of triangular teeth, one dark eye, red-orange gill glowing in the filtered light, murky water blurred behind.
Save as: `S031_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S031_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S031_Ref.png`. The piranha opens and closes its mouth slowly in a breathing motion; the camera slowly circles a few degrees around its head; a small piece of fruit drifts past and the fish gently nips it, calm and unbothered.
Sound (BGM+SFX, no dialogue): The music relaxes to a curious, low pizzicato; soft water rush, a light click of the nip, tiny bubbles.
Cut→S032: Hard cut to a wide tracking shot of the fish going about its day.

**S032 — Alone, they are calm | 4:08–4:16**
Step 3 Ingredients: Vehicle/Subject Reference Image: `Piranha_Portrait.png` · Environment Reference Image: `SettingD_Env.png` · Scene Continuity Reference: `S031_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Wide underwater tracking view of a lone piranha cruising peacefully past submerged roots and lily-pad stems in tea-brown water, bright shafts of light and drifting particles around it.
Save as: `S032_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S032_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S032_Ref.png`. The camera tracks smoothly alongside the lone piranha as it glides between roots and settles beside a stem; small fish pass and it ignores them; the camera pulls out slightly at the end.
Sound (BGM+SFX, no dialogue): The music becomes gentle and almost playful; a water ambience with occasional bubbles and a soft tail flick.
Cut→S033: Hard cut to the same river, now drying, a locked-off wide shot.

**S033 — When the water shrinks | 4:16–4:24**
Step 3 Ingredients: Vehicle/Subject Reference Image: `Piranha_Portrait.png` · Environment Reference Image: `SettingD_Env.png` · Scene Continuity Reference: `S032_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Locked-off high angle view of a shrinking muddy river pool in dry season, cracked mud around the edges, dozens of piranhas crowded into a small brown pool, the surface rippling with fins, harsh overcast light.
Save as: `S033_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S033_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S033_Ref.png`. A time-lapse: the pool shrinks visibly, the mud edge cracks and widens, the crowded fish thrash and churn the water more and more, spray leaping up; the camera stays locked.
Sound (BGM+SFX, no dialogue): The music builds tension with a low tremolo and rising drums; splashing water, fin slaps, dry wind and cracking mud.
Cut→S034: Whip pan to a low water-level view of a still, calm river.

**S034 — Eyes above the water | 4:24–4:32**
Step 3 Ingredients: Vehicle/Subject Reference Image: `Anaconda_Portrait.png`, `Anaconda_6Angle.png` · Environment Reference Image: `SettingD_Env.png` · Scene Continuity Reference: `S033_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Water-level view at the flooded roots of a riverbank, the still surface at the bottom edge of frame, and just above it the eyes and snout of a giant green anaconda, its long body vanishing into the brown water behind it.
Save as: `S034_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S034_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S034_Ref.png`. The camera drifts slowly forward at water level, the anaconda staying almost motionless with only a slow, tiny ripple around its snout; a water strider crosses the surface; the camera stops close to the eyes.
Sound (BGM+SFX, no dialogue): A very low, slow drone with a subtle heartbeat; gentle lapping water, a faint insect hum, a soft hiss on the final second.
Cut→S035: Hard cut to a macro on its eye.

**S035 — The amber eye | 4:32–4:40**
Step 3 Ingredients: Vehicle/Subject Reference Image: `Anaconda_Portrait.png`, `Anaconda_6Angle.png` · Environment Reference Image: `SettingD_Env.png` · Scene Continuity Reference: `S034_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Extreme macro of the anaconda's amber eye with its vertical pupil and wet olive scales, drops of water beading on the skin, the blurred brown river behind.
Save as: `S035_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S035_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S035_Ref.png`. A rack focus from the eye to the flickering tongue at the snout and back; the pupil narrows slightly; a droplet slides down the scales; the camera creeps in a few centimetres.
Sound (BGM+SFX, no dialogue): Held low tone; wet tongue flick, slow water drips, a faint breath; a tension sting at the pupil narrowing.
Cut→S036: Hard cut to a high angle above the water surface at the bank.

**S036 — A bird comes to drink | 4:40–4:48**
Step 3 Ingredients: Vehicle/Subject Reference Image: `Anaconda_Portrait.png` · Environment Reference Image: `SettingD_Env.png` · Scene Continuity Reference: `S035_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
High three-quarter angle above a calm river bank, a white egret standing at the water's edge lowering its beak to drink, and beneath the murky surface a long dark olive coil of an anaconda faintly visible in the shallows below the bird.
Save as: `S036_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S036_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S036_Ref.png`. The egret dips its beak to drink and lifts its head; a slow ripple spreads from below; the bird stiffens, then leaps into flight with a flap of white wings and disappears; the camera holds, showing the ripple settling around the coil.
Sound (BGM+SFX, no dialogue): The music holds a low drone, then a sharp string stab as the bird flees; a soft drink, a sudden wing-flap, a splash of water.
Cut→S037: Cut to a skimming low tracking shot over the river's surface.

**S037 — Nothing is safe | 4:48–4:56**
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: `SettingD_Env.png` · Scene Continuity Reference: `S036_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Low tracking view skimming just above the river surface toward a misty bend, roots and branches overhanging both banks, bright overcast light, bubbles breaking on the water here and there.
Save as: `S037_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S037_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S037_Ref.png`. The camera skims forward over the water, passing roots and hanging vines; a few bubbles rise and pop; the mist at the bend grows closer; the camera slowly rises above the trees at the end.
Sound (BGM+SFX, no dialogue): The music gathers into a wary, driving theme; water rush, bubbles popping, insect drone, a distant bird warning call.
Cut→S038: Cross-dissolve to the dawn trail of a rubber tapper.

---

### Segment 7 — The Rubber Tapper's Voice (Scenes 38–43)

**S038 — The tapper at dawn | 4:56–5:04**
Step 3 Ingredients: Vehicle/Subject Reference Image: `Tapper_Portrait.png`, `Tapper_6Angle.png` · Environment Reference Image: `SettingE_Env.png` · Scene Continuity Reference: `S037_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Wide shot at dawn on a misty rubber-tree trail, a lone rubber tapper in a straw hat seen from behind walking between the trunks, the headlamp on his hat glowing faintly, gold rim light through the mist, tin cups on the trees.
Save as: `S038_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S038_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S038_Ref.png`. The camera follows a few metres behind him, gliding forward as he walks between the trunks; the mist swirls, light beams shift and a bird flies across; he stops at a tree and looks up.
Sound (BGM+SFX, no dialogue): A warm, humble guitar and flute theme enters; boots on mud, dawn birds, a soft wind.
Cut→S039: Hard cut to a macro on the knife cut.

**S039 — The cut that gives life | 5:04–5:12**
Step 3 Ingredients: Vehicle/Subject Reference Image: `Tapper_Portrait.png` · Environment Reference Image: `SettingE_Env.png` · Scene Continuity Reference: `S038_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Macro of a curved tapping knife making a fresh diagonal cut into a rubber tree's bark, a thin line of white latex beading along the cut, latex-stained sleeve blurred at the edge of frame, no face visible.
Save as: `S039_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S039_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S039_Ref.png`. The knife draws a smooth, shallow cut down the bark, and milky latex wells up and slowly runs along the groove; the camera tracks with it as a first drip forms.
Sound (BGM+SFX, no dialogue): The theme stays warm and gentle; the crisp scrape of the knife on bark, soft wet latex ooze, a droplet.
Cut→S040: Match cut on the falling drop, into a top-down cup.

**S040 — Drops in the cup | 5:12–5:20**
Step 3 Ingredients: Vehicle/Subject Reference Image: `Tapper_Portrait.png` · Environment Reference Image: `SettingE_Env.png` · Scene Continuity Reference: `S039_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Straight top-down view into a small tin cup half-filled with white latex, a fresh drop about to fall from the spout above, gold dawn light on the metal rim.
Save as: `S040_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S040_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S040_Ref.png`. Drops fall in slow rhythm into the cup, each making a soft circular ripple in the white latex; the camera pulls up slowly to show the tree, cup and cut in one frame.
Sound (BGM+SFX, no dialogue): A quiet, meditative guitar; the rhythmic plink of drops into latex, soft breeze.
Cut→S041: Hard cut to a wide low-angle view of the tapper turning toward a distant smoke.

**S041 — Smoke on the ridge | 5:20–5:28**
Step 3 Ingredients: Vehicle/Subject Reference Image: `Tapper_Portrait.png`, `Tapper_6Angle.png` · Environment Reference Image: `SettingE_Env.png` · Scene Continuity Reference: `S040_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Low-angle wide shot of the tapper standing small between giant trunks, seen from behind, his straw hat lifted, looking toward a dark column of smoke rising above the ridge far away, dawn light turning orange near the smoke.
Save as: `S041_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S041_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S041_Ref.png`. The camera pushes in slowly from behind his shoulder as he stands still watching the smoke grow; birds fly away from the ridge; the light in the mist shifts to orange.
Sound (BGM+SFX, no dialogue): The theme darkens with a low cello; a distant chainsaw whine, crackling far off, birds scattering.
Cut→S042: Hard cut to a wide backlit view of many silhouettes gathered.

**S042 — A voice, and many with him | 5:28–5:36**
Step 3 Ingredients: Vehicle/Subject Reference Image: `Tapper_Portrait.png` · Environment Reference Image: `SettingE_Env.png` · Scene Continuity Reference: `S041_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Wide backlit view at sunrise of the tapper standing in front of a line of dozens of other rubber tappers on the trail, all seen only as silhouettes with straw hats, some raising their hats overhead, golden light streaming from behind them through the trunks.
Save as: `S042_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S042_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S042_Ref.png`. The camera slowly pushes in from behind the tapper as more silhouettes raise their hats one by one; the sun rays intensify; the mist glows.
Sound (BGM+SFX, no dialogue): The music grows into a hopeful, determined swell with strings and a soft choir-like pad; a rustle of fabric, a murmuring crowd without words.
Cut→S043: Cross-dissolve to a quiet close-up of an award medal.

**S043 — The world notices | 5:36–5:44**
Step 3 Ingredients: Vehicle/Subject Reference Image: `Tapper_Portrait.png` · Environment Reference Image: `SettingF_Env.png` · Scene Continuity Reference: `S042_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Macro of a modest brass medal on a blue ribbon lying on a rough wooden porch rail beside a straw hat and a tapping knife, soft dusk light, the yard and wooden house blurred behind, no text or writing on the medal.
Save as: `S043_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S043_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S043_Ref.png`. A slow push-in on the medal as a breeze stirs the ribbon and the light glints across the brass; a rack focus moves from the medal to the straw hat and holds.
Sound (BGM+SFX, no dialogue): The theme quiets to a soft, dignified piano; a light metal shimmer, a ribbon rustle, crickets beginning.
Cut→S044: Hard cut to a locked wide of the quiet yard at dusk.

---

### Segment 8 — The Sacrifice & Legacy (Scenes 44–48)

**S044 — The quiet yard | 5:44–5:52**
Step 3 Ingredients: Vehicle/Subject Reference Image: `Tapper_Portrait.png` · Environment Reference Image: `SettingF_Env.png` · Scene Continuity Reference: `S043_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Locked-off wide shot of the back yard of the wooden stilt house at blue-hour dusk, a single window glowing, a straw hat resting on the porch rail, a hanging towel still in the air, the dark treeline behind, and a strange, held silence.
Save as: `S044_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S044_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S044_Ref.png`. The camera stays locked; a light breeze lifts the towel, the window light flickers slightly, crickets drift in and out; nothing else moves as the dusk deepens.
Sound (BGM+SFX, no dialogue): A very sparse, hushed piano note over a low drone; crickets, distant frog calls, a faint wind.
Cut→S045: Hard cut, pushing toward the dark treeline.

**S045 — Birds burst from the trees | 5:52–6:00**
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: `SettingF_Env.png` · Scene Continuity Reference: `S044_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Static low view across the yard toward the dark treeline at deep blue dusk, the porch light glowing at the frame edge, the trees silent and black.
Save as: `S045_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S045_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S045_Ref.png`. A slow creeping push-in on the treeline; suddenly a flock of birds bursts from the canopy into the sky and scatters; the porch light flickers once; silence returns as the camera holds. Nothing violent is shown.
Sound (BGM+SFX, no dialogue): Music cuts to near silence; one distant sharp crack echoing off the trees, a burst of wings, then a long hush with a single low tone.
Cut→S046: Hard cut to the fallen hat on the porch steps.

**S046 — The dropped hat | 6:00–6:08**
Step 3 Ingredients: Vehicle/Subject Reference Image: `Tapper_Portrait.png` · Environment Reference Image: `SettingF_Env.png` · Scene Continuity Reference: `S045_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Low-angle close shot of the straw hat lying on the wooden porch step in the dust, the warm window light spilling over it and a moth circling above, the dark yard blurred behind.
Save as: `S046_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S046_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S046_Ref.png`. A slow push-in on the hat, the moth circling, the light flickering and steadying; the camera tilts up slightly from the hat toward the glowing window and stops.
Sound (BGM+SFX, no dialogue): A solo cello with a slow, mournful line; moth wing flutter, a distant dog bark fading, crickets.
Cut→S047: Cross-dissolve into a bright dawn aerial.

**S047 — What his sacrifice saved | 6:08–6:16**
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: `SettingG_Env.png` · Scene Continuity Reference: `S046_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
High aerial view at sunrise of an intact protected rainforest reserve, the gold light spilling over the canopy, a winding river reflecting the sky, mist lifting; a rubber-tree trail is visible cutting through the trees at the frame edge.
Save as: `S047_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S047_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S047_Ref.png`. The camera rises and glides forward over the canopy as the sun clears the horizon, gold light sweeping across the treetops, flocks of birds crossing, the river shining. Slow and uplifting.
Sound (BGM+SFX, no dialogue): The cello theme blooms into a full, warm orchestral swell; birds waking up, wind over the trees.
Cut→S048: Cut to a close rack focus at the trail.

**S048 — The cup keeps filling | 6:16–6:24**
Step 3 Ingredients: Vehicle/Subject Reference Image: `Tapper_Portrait.png`, `Tapper_6Angle.png` · Environment Reference Image: `SettingE_Env.png` · Scene Continuity Reference: `S047_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Close view at dawn of a tin cup on a rubber tree filling with white latex, sun flare and mist behind it, and beyond it a blurred silhouette of a tapper in a straw hat walking down the trail, seen from behind.
Save as: `S048_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S048_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S048_Ref.png`. A drop of latex falls into the cup; a rack focus moves from the cup to the walking silhouette and back; sun flare grows across the lens; the tapper walks on down the trail out of frame.
Sound (BGM+SFX, no dialogue): The theme resolves into a soft, hopeful piano and strings; a latex drop plink, footsteps fading, a distant bird.
Cut→S049: Hard cut to a cold dawn aerial with a drone in flight.

---

### Segment 9 — The Danger That Continues (Scenes 49–55)

**S049 — The eye in the sky | 6:24–6:32**
Step 3 Ingredients: Vehicle/Subject Reference Image: `Drone_Portrait.png`, `Drone_6Angle.png` · Environment Reference Image: `SettingG_Env.png` · Scene Continuity Reference: `S048_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Wide aerial view at dawn of a small white fixed-wing survey drone flying in from the left over the endless canopy, seen from slightly above and behind, mist below and the cleared pasture line visible on the right.
Save as: `S049_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S049_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S049_Ref.png`. The camera tracks alongside the drone as it glides steadily over the canopy, its propeller spinning and its wings tilting gently in the breeze; the drone banks toward the deep forest.
Sound (BGM+SFX, no dialogue): A cool, technological pulse with a low drone enters; a steady electric propeller hum, wind rush.
Cut→S050: Hard cut to a macro on the camera gimbal.

**S050 — The lens that sees | 6:32–6:40**
Step 3 Ingredients: Vehicle/Subject Reference Image: `Drone_Portrait.png`, `Drone_6Angle.png` · Environment Reference Image: `SettingG_Env.png` · Scene Continuity Reference: `S049_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Extreme macro of the drone's camera gimbal pod under its nose, a glass lens reflecting the green canopy and the golden sun, the blurred propeller spinning in the background.
Save as: `S050_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S050_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S050_Ref.png`. The lens pivots slightly to tilt down and refocuses; the reflection of the canopy slides across the glass; the camera pushes in a little on the lens; the propeller spins steadily.
Sound (BGM+SFX, no dialogue): The pulse continues; servo whir and lens focus click, propeller hum.
Cut→S051: Match cut on the lens reflection into the drone's own point of view.

**S051 — What the drone found | 6:40–6:48**
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: `SettingG_Env.png` · Scene Continuity Reference: `S050_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Drone point-of-view aerial shot, looking down through a break in the canopy at a small forest clearing with two thatched huts and a thin thread of smoke, tiny distant silhouettes of people moving between the huts, gentle mist.
Save as: `S051_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S051_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S051_Ref.png`. The camera descends slowly toward the huts; the tiny figures see or sense the drone, pause, and then move away into the forest edge, leaving the clearing empty with the smoke still rising. Distant, no faces visible.
Sound (BGM+SFX, no dialogue): Music thins to a suspended, awed string note; the drone hum fading, a distant call between the trees.
Cut→S052: Hard cut to a ground-level push-in through foliage.

**S052 — A fire left burning | 6:48–6:56**
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: `SettingA_Env.png` · Scene Continuity Reference: `S051_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Ground-level view inside the forest of a small campfire still glowing beside two abandoned hammocks and a woven basket, hurriedly left, green light with amber shafts, no people in frame.
Save as: `S052_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S052_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S052_Ref.png`. The camera pushes in slowly toward the fire; a hammock rope still swings from a quick departure; embers glow; in the distance a chainsaw whine grows and the camera stops on the fire.
Sound (BGM+SFX, no dialogue): The music grows uneasy with a low tremolo; crackling embers, hammock rope creak, an approaching chainsaw whine.
Cut→S053: Hard cut to a low-angle tracking shot of a bulldozer on the new road.

**S053 — The road that follows them | 6:56–7:04**
Step 3 Ingredients: Vehicle/Subject Reference Image: `Bulldozer_Portrait.png`, `Bulldozer_6Angle.png` · Environment Reference Image: `SettingH_Env.png` · Scene Continuity Reference: `S052_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Low-angle tracking view at smoky orange dusk of the yellow bulldozer rolling along a fresh red-earth road toward the forest wall, dust and smoke around its tracks, charred stumps to the sides, no operator visible.
Save as: `S053_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S053_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S053_Ref.png`. The camera tracks alongside the bulldozer as it moves ahead, its blade throwing soil, tracks clanking, smoke swirling; the forest wall looms nearer in the background.
Sound (BGM+SFX, no dialogue): Heavy, ominous drums and a brass drone; diesel roar, tracks clanking, splintering wood.
Cut→S054: Cut to a high wide aerial of the fire line.

**S054 — The fire line advances | 7:04–7:12**
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: `SettingH_Env.png` · Scene Continuity Reference: `S053_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
High wide aerial view at orange dusk of a glowing fire line and smoke columns advancing across cleared land toward a dark green forest island, a tiny thread of smoke rising inside it, huge sunset haze above.
Save as: `S054_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S054_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S054_Ref.png`. The camera glides forward and slightly down as the fire line creeps across the land and the smoke columns twist upward; the small forest island glows on the horizon; the tiny thread of smoke inside it stays steady.
Sound (BGM+SFX, no dialogue): The score reaches a menacing peak with pounding percussion; roaring fire, wind, distant collapsing trees.
Cut→S055: Cut to a quiet silhouette looking out at the fire.

**S055 — How many are still there? | 7:12–7:20**
Step 3 Ingredients: Vehicle/Subject Reference Image: `TanaruMan_Portrait.png`, `TanaruMan_6Angle.png` · Environment Reference Image: `SettingB_Env.png` · Scene Continuity Reference: `S054_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Medium-wide shot from behind at the tree line of the clearing at dusk, a lone silhouetted man with a bow at his side, standing still and looking out toward a far orange glow of fire on the horizon; his face is never visible.
Save as: `S055_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S055_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S055_Ref.png`. A slow push-in from behind his shoulder; the far glow pulses; a breeze stirs the smoke and his hair; he lowers his head slightly and stays still while the camera settles. Quiet and heavy.
Sound (BGM+SFX, no dialogue): The music drops to a lone flute over a soft pad; distant fire rumble, crickets, and a deep silence beat before the next scene.
Cut→S056: Slow cross-dissolve through the silent beat into a bright dawn.

---

### Segment 10 — Final Wide / Outro (Scenes 56–57)

**S056 — The book of the forest | 7:20–7:28**
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: `SettingG_Env.png` · Scene Continuity Reference: `S055_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Vast aerial view at dawn of the endless emerald canopy stretching to the horizon, thick mist between treetops, gold sun rising, and a gust of wind sweeping across the leaves in wave patterns.
Save as: `S056_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S056_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S056_Ref.png`. The camera rises slowly and pulls back while wind sweeps a ripple across the canopy, the leaves turning silver-green like pages of a giant book; mist lifts and the sunlight brightens.
Sound (BGM+SFX, no dialogue): The outro theme swells with warm strings, flute and a soft choir-like pad; wind over the canopy, a chorus of dawn birds.
Cut→S057: Cross-dissolve to the night sky.

**S057 — One last firefly | 7:28–7:30 (trim to 2s in edit)**
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: `SettingI_Env.png` · Scene Continuity Reference: `S056_Ref.png`
Step 3 — Reference Image Prompt (Google Flow):
Quiet forest clearing at night, a sky full of stars and the Milky Way above a black treeline, fireflies glowing softly among the ferns, and one bright firefly in the foreground drifting upward.
Save as: `S057_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S057_Ref.png`
Video Prompt (Google Flow, 8s, use the first 2s):
I2V from `S057_Ref.png`. The camera tilts up slowly toward the stars while the foreground firefly lifts, glows, and fades among the other lights; make sure the first 2 seconds hold a complete closing beat.
Sound (BGM+SFX, no dialogue): The outro theme resolves to a final held chord and fades to silence; soft night crickets fading last.
Cut→END: Fade to black.

---

# PRODUCTION NOTES

- **Runtime check:** 7:30 = 450 s. 450 ÷ 8 = 56.25, so 57 scenes. Scenes S001–S056 are 8 s each (448 s). S057 nominally runs 7:28–7:36 and is trimmed to 2 s so the video ends at exactly 7:30.
- **Image generation is Google Flow only.** Step 1 subject sheets, Step 2 environment plates and Step 3 scene reference images are all made there. Video prompts use each scene's saved `_Ref.png` as the starting frame. One video prompt per scene.
- **Continuity chain:** every Step 3 prompt lists the previous scene's saved `SXXX_Ref.png` as its Scene Continuity Reference, plus the subject sheets in the shot and the correct environment plate. Generate the scenes in order so each reference image exists before it is needed.
- **Hard-rules reminder:** no on-screen text, no readable faces, no gore or visible violence. Tragic events (the massacre, Fawcett's disappearance, the 1988 killing) are shown only through symbols and sound: empty hammock, fog, dropped hat, birds bursting from trees. Humans are silhouettes, back-turned or distant.
- **Voice-over:** the generated clips carry only BGM and diegetic SFX. Lay the Tamil narration in the edit. Roughly 7:30 of narration is needed, so trim the 20-minute script to about 25–30% of its length. Keep the hook, the Tanaru story, the Fawcett story, one river-danger beat, the Chico Mendes story and the closing line.
- **Fact-check before recording:** the candiru "swims up the body" story is largely folk myth. The 1997 anaconda attack on a gardener isn't a well-documented case. Check the Kawahiva "2011 drone" detail.
- **Segment shifts to watch in the edit:** S043 (dusk medal) sits between the dawn trail scenes and the dusk yard on purpose. Colour-match it to Setting F.
- **Reminder:** the GLOBAL LOCK BLOCK must be appended in full to the end of every prompt (Step 1, Step 2, every Step 3 and every Step 4) before submission.
