# SCRIPT 01 — அமேசன் காடு: The Forest That Keeps Its Secrets
### [TEMPLATE v3 — Google Flow only · voice-over slots of 4/6/8/10 s, Flow clips generated at 8 or 10 s · subject sheets → unique location per scene → per-scene reference image → per-scene video · global lock appended to every prompt · no on-screen text · consistent visible faces · BGM + diegetic SFX only]

**Duration:** 6:54 (matches the timestamped voice-over file) | **Total Scenes:** 68 = 68 reference images = 68 videos (2 × 10 s, 15 × 8 s, 35 × 6 s, 16 × 4 s = 414 s, no trimming needed)
**Image generation:** Google Flow only (Step 1 subject sheets, Step 2 location plan, Step 3 scene reference images)
**Video generation:** Google Flow — one video prompt per scene, each generated in Flow as an 8 s or 10 s clip (a 4/6/8/10 s voice-over slot plus spare seconds to trim), built from that scene's saved reference image, each carrying its own sound design
**Payoff:** The camera rises from one lone survivor to the endless living canopy, so the viewer feels how many untold stories still hide in the forest, then ends on a night sky and one last firefly.
**Dialogue/Audio rule:** The generated clips contain NO voice of any kind: only instrumental BGM and diegetic SFX. Your recorded Tamil voice-over ("AMAZON FINAL VOICE", 6:54) is added in the edit; every scene is timed to its spoken lines.

**Assumptions made for the blank input fields (change if needed):**
- **Style:** photorealistic cinematic documentary, 35mm anamorphic look.
- **Subjects:** the ones in Step 1.
- **Hard rules:** no on-screen text. Human characters have clear, fully rendered faces that stay identical across every scene (invented fictional faces, not likenesses of real people). No gore or violence on screen, only implied.
- **Real people:** the figures are fictional characters inspired by the events, with invented faces, not likenesses of real individuals.

**Segment map (Step 0 math: 6:54 = 414 s, cut on the voice-over phrase boundaries into 4/6/8/10 s slots → 68 scenes)**

| # | Segment | Scenes | Time |
|---|---|---|---|
| 1 | Hook | S001–S009 | 0:00–0:56 |
| 2 | Tanaru — The Man of the Hole | S010–S015 | 0:56–1:28 |
| 3 | Tanaru — The Lone Survivor | S016–S025 | 1:28–2:32 |
| 4 | The Pattern & Fawcett — The Obsession | S026–S031 | 2:32–3:06 |
| 5 | Fawcett — The Vanishing | S032–S038 | 3:06–3:44 |
| 6 | The River's Hidden Dangers | S039–S047 | 3:44–4:40 |
| 7 | The Rubber Tapper's Voice | S048–S052 | 4:40–5:10 |
| 8 | The Sacrifice & Legacy | S053–S057 | 5:10–5:36 |
| 9 | The Danger That Continues | S058–S064 | 5:36–6:24 |
| 10 | Final Wide / Outro | S065–S068 | 6:24–6:54 |

---

## ⚠️ GLOBAL LOCK BLOCK — append this in full to the END of every single prompt below (Step 1, Step 2, every Step 3, every Step 4)

```
GLOBAL LOCK:
CONTINUITY — Keep Tanaru-Man, Z-Party Explorers, Seringueiro Rubber Tapper, Scarlet-1 Macaw, Sucuri-Titan Anaconda, Red-Belly Piranha, Needle-Fish Candiru, Sky-Eye Survey Drone and Iron-Reaper Bulldozer (including faces, hair and skin tone) in exact color/decal/proportion continuity from their saved reference sheets — no redesign, recolor, or scale drift. Every scene takes place in its own unique location exactly as written in its prompt; never copy or reuse the previous scene's location, background or composition.
STYLE — Photorealistic cinematic documentary, 35mm anamorphic lens look, shallow depth of field on close shots, natural film grain, rich but natural color grade (deep emerald greens, warm amber light shafts, muted earth tones). Real material physics: wet leaves glisten, mud clumps, smoke diffuses, water refracts, wood grain and rust stay stable.
HARD RULES — No on-screen text, captions, logos or watermarks. Human characters have clear, natural, fully visible faces (realistic skin texture, eyes, expressions) that match their saved reference sheets exactly in every shot; these are invented fictional faces, not likenesses of any real person. Faces never morph, age, or change between shots. No gore, no visible violence, no weapons pointed at a person: danger is shown by aftermath, shadow, sound and the reaction of people, animals and objects. Historic and tragic events are implied through symbolic imagery (empty hammock, quiet clearing, dropped hat, shafts of light) and grief or fear on faces, never re-enacted.
ZERO AI ARTIFACTS — No morphing, warping, melting, flicker, extra or duplicated limbs/parts, floating debris, texture smearing, plastic skin or fur, inconsistent shadows, distorted hands or anatomy.
LIGHTING — Follow the time of day and light written in each scene's prompt, and keep one consistent cinematic colour grade across all locations (deep emerald greens, warm amber, muted earth tones) so different places still feel like one film; no sudden unintended light jumps inside a shot.
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
**Usage note:** Attach both files to every scene where this subject appears: S010–S011, S018–S020, S023–S024, S064.

### 1B. 1925 Expedition Party ("Z-Party Explorers")
**Portrait Image Prompt — Google Flow:**
Group portrait of three 1920s British explorers standing in a line facing the camera, each with a clearly visible, fully detailed face: a tall lean older colonel in the centre (long angular face, deep sun-weathered lines, grey moustache, pale blue eyes, short grey hair, stern and determined) wearing a waxed-canvas khaki jacket, riding breeches, leather puttees, a wide-brim pith sun helmet and carrying a leather map case; a young man on his left (clean-shaven, freckled, hazel eyes, tousled brown hair, eager expression) in a similar khaki outfit with a canvas rucksack and a rolled bedroll; a companion on his right (round face, dark stubble, brown eyes, calm expression) with a slouch hat, a brass compass at his belt and a machete in a leather sheath. Worn, sweat-stained fabrics, brass buckles, cracked leather. Grey neutral background, soft key light from upper left, macro detail on faces, stitching, brass patina and leather grain. Invented fictional faces. Locked reference design.
**Save as:** `Explorers_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Explorers_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround of the same three-man group: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE (boots and ground), neutral grey background, matched lighting/scale, neutral pose in every panel.
**Save as:** `Explorers_6Angle.png`
**Usage note:** Attach both files to every scene where this subject appears: S027–S033.

### 1C. Rubber Tapper ("Seringueiro")
**Portrait Image Prompt — Google Flow:**
Full-body portrait of a Brazilian rubber tapper (seringueiro) in his 40s, facing the camera in a relaxed pose, with a clearly visible, fully detailed face: warm brown skin, short black hair, a neat dark moustache, kind dark eyes with laugh lines, a sweat-lined forehead and a thoughtful, determined expression, with the wide straw hat pushed back so the face is lit. Faded blue cotton shirt with rolled sleeves, worn brown trousers, rubber boots, a small curved tapping knife at his belt, a tin cup and a canvas shoulder bag, a headlamp on the hat brim. Realistic sun-worn fabric, mud on boots, latex stains on the sleeves. Grey background, warm key light from upper right, macro detail on the face, straw weave and latex-stained cloth. An invented fictional face. Locked reference design.
**Save as:** `Tapper_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Tapper_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT (face fully visible, identical to the portrait), REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE (boots and ground contact), neutral grey background, matched lighting/scale, neutral pose in every panel. Add a second row of three close-up face panels (front, left profile, right profile) locking the face.
**Save as:** `Tapper_6Angle.png`
**Usage note:** Attach both files to every scene where this subject appears: S040, S049–S053, S055.

### 1D. Scarlet Macaw ("Scarlet-1")
**Portrait Image Prompt — Google Flow:**
A single adult scarlet macaw perched on a natural branch, 85 cm long, vivid scarlet body, yellow-and-blue wing coverts, blue tail-feather tips, pale bare face patch, dark curved beak. Side-profile view, sharp macro-level feather barb detail, grey neutral background, soft key light from the upper left. Locked reference design.
**Save as:** `Macaw_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Macaw_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral grey background, matched lighting/scale, perched pose in every panel with wings folded.
**Save as:** `Macaw_6Angle.png`
**Usage note:** Attach both files to every scene where this subject appears: S024, S065.

### 1E. Green Anaconda ("Sucuri-Titan")
**Portrait Image Prompt — Google Flow:**
A giant green anaconda, 5.5 m long, thick as a man's thigh, olive-green skin with rounded black blotches in two alternating rows, a dark stripe behind the eye, yellow-cream belly edge, coiled loosely in a S-curve on a neutral surface. Wet glossy scales with realistic per-scale detail. Camera at three-quarter high angle, grey background, soft key light upper left, macro detail on scale texture and the amber eye with a vertical pupil. Locked reference design.
**Save as:** `Anaconda_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Anaconda_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT (head-on), REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE (belly scales), neutral grey background, matched lighting/scale, same loose S-coil pose in every panel.
**Save as:** `Anaconda_6Angle.png`
**Usage note:** Attach both files to every scene where this subject appears: S044–S046.

### 1F. Red-Bellied Piranha ("Red-Belly Piranha")
**Portrait Image Prompt — Google Flow:**
A single adult red-bellied piranha, 25 cm, silver-grey flanks with darker speckles, deep red-orange belly and gill area, a blunt head with an underbite and a row of triangular razor teeth, forked tail edged in black. Side profile, mid-water pose, neutral grey gradient background as if photographed in a tank, key light upper left, macro detail on scales and teeth. Locked reference design.
**Save as:** `Piranha_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Piranha_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT (open-mouth teeth view), REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral grey background, matched lighting/scale, neutral swimming pose in every panel.
**Save as:** `Piranha_6Angle.png`
**Usage note:** Attach both files to every scene where this subject appears: S042–S043.

### 1G. Candiru ("Needle-Fish")
**Portrait Image Prompt — Google Flow:**
A tiny translucent candiru catfish, 4 cm long, eel-like slender body, near-transparent pinkish-grey skin with a visible spine, small barbels, backward-pointing gill spines, shown in extreme macro, side profile, floating in clear water against a neutral grey-blue background, key light upper left, crisp macro detail. Locked reference design.
**Save as:** `Candiru_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Candiru_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral grey background, matched lighting/scale, neutral pose in every panel.
**Save as:** `Candiru_6Angle.png`
**Usage note:** Attach both files to every scene where this subject appears: S039–S041.

### 1H. Survey Drone ("Sky-Eye")
**Portrait Image Prompt — Google Flow:**
A small white fixed-wing survey drone with a 1.8 m wingspan, matte white fuselage, slim swept wings, a rear pusher propeller, a small camera gimbal pod under the nose, a thin dark-grey antenna, no text or logos anywhere. Displayed on a neutral grey surface, three-quarter front view, key light upper left, macro detail on carbon-fibre panel seams and the propeller. Locked reference design.
**Save as:** `Drone_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Drone_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral grey background, matched lighting/scale, neutral pose in every panel.
**Save as:** `Drone_6Angle.png`
**Usage note:** Attach both files to every scene where this subject appears: S059.

### 1I. Logging Bulldozer ("Iron-Reaper")
**Portrait Image Prompt — Google Flow:**
A heavy yellow crawler bulldozer, 1:1 scale, mud-caked steel tracks, a wide front blade with worn edge, a rear ripper claw, a cab with a dark tinted windshield (no operator visible), a black vertical exhaust stack, dusty red-earth splatter over the yellow paint, no brand names or logos. Three-quarter front view on a neutral grey surface, key light upper left, macro detail on track links, hydraulic rams and paint chips. Locked reference design.
**Save as:** `Bulldozer_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Bulldozer_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral grey background, matched lighting/scale, neutral pose in every panel.
**Save as:** `Bulldozer_6Angle.png`
**Usage note:** Attach both files to every scene where this subject appears: S016, S062.

---

# STEP 2 — LOCATION PLAN (no reusable environment plates: every scene has its own unique place)

There are no shared environment-plate images. Each scene's Step 3 prompt fully describes its own location, and `Environment Reference Image` is `none`. Generate each reference image from its prompt plus the subject sheets. The table lists the location of every scene so you can check that no place repeats.

| Scene | Time | Length | Unique location |
|---|---|---|---|
| S001 | 0:00–0:10 | 10s | High aerial over the meeting of two rivers at sunrise (brown and black water side by side) |
| S002 | 0:10–0:16 | 6s | Above the clouds: the forest sea rolling to the far Andean foothills at dawn |
| S003 | 0:16–0:22 | 6s | Crown of a colossal emergent kapok tree towering above the canopy at sunrise |
| S004 | 0:22–0:26 | 4s | Dark forest floor among giant buttress roots and hanging lianas |
| S005 | 0:26–0:32 | 6s | Hidden oxbow lake in the forest at early morning, one thatched roof on its bank |
| S006 | 0:32–0:36 | 4s | Forested ridge line at dusk under towering thunderclouds with an orange glow on the horizon |
| S007 | 0:36–0:42 | 6s | A valley filled with white fog at first light, one thatched roof emerging at its edge |
| S008 | 0:42–0:52 | 10s | Twilight over a smoke-hazed river valley with a dull red sun and a line of small fires |
| S009 | 0:52–0:56 | 4s | Rondônia farmland frontier from the air: straight red dirt roads, pasture, one forest island |
| S010 | 0:56–1:02 | 6s | Small cassava and banana garden clearing inside the forest, late golden afternoon |
| S011 | 1:02–1:08 | 6s | Doorway of his palm-thatch hut: smoke-blackened palm wall, packed red earth, warm dusk |
| S012 | 1:08–1:12 | 4s | Rim of a deep hand-dug pit at the edge of a dry palm grove, late golden light |
| S013 | 1:12–1:18 | 6s | Fern and palm-seedling forest floor seen from directly above, a field of hand-dug pits |
| S014 | 1:18–1:22 | 4s | Animal trail beside a muddy clay bank in late golden light |
| S015 | 1:22–1:28 | 6s | Inside the hut: woven palm walls, packed-earth floor, a round pit, an empty hammock, dusty light through thatch gaps |
| S016 | 1:28–1:34 | 6s | 1970s frontier road with a barbed-wire fence and a wooden ranch gate under a smoky orange sky |
| S017 | 1:34–1:40 | 6s | Cattle pasture of charred stumps with a lone ranch house and pickup at smoky dusk |
| S018 | 1:40–1:44 | 4s | A larger village clearing beside a stream after a tragedy: ruined thatched huts at smoky dusk |
| S019 | 1:44–1:52 | 8s | A leafy hillside observation blind high above a valley clearing |
| S020 | 1:52–1:58 | 6s | Shallow creek crossing with mossy rocks at the forest edge, golden dusk |
| S021 | 1:58–2:04 | 6s | Narrow forest footpath under a canopy tunnel, seasons passing |
| S022 | 2:04–2:10 | 6s | Dew-covered packed-earth yard in front of his small sleeping hut, early morning |
| S023 | 2:10–2:16 | 6s | His smaller sleeping hut: low thatched shelter with a woven doorway, hammock inside, soft morning light |
| S024 | 2:16–2:24 | 8s | Macro on the hammock's woven fibres in a narrow shaft of morning light through a thatch gap |
| S025 | 2:24–2:32 | 8s | The clearing at night under moonlight, mist rising from a nearby stream |
| S026 | 2:32–2:38 | 6s | Braided river network of the Xingu basin at pre-dawn from the air, tiny smoke threads |
| S027 | 2:38–2:42 | 4s | A cobbled colonial town street at misty dawn in 1925 |
| S028 | 2:42–2:48 | 6s | Wooden veranda of a 1925 riverside trading-post lodge at misty morning |
| S029 | 2:48–2:52 | 4s | Inside a canvas expedition tent at night, a map on a camp table lit by an oil lantern |
| S030 | 2:52–3:00 | 8s | A London-style geographical society map room: oak desk, green-shaded lamp, brass globe |
| S031 | 3:00–3:06 | 6s | A wooden river jetty with a steam launch and a canoe at misty dawn |
| S032 | 3:06–3:12 | 6s | Dry cerrado savanna trail with buriti palms at golden morning, forest wall on the horizon |
| S033 | 3:12–3:16 | 4s | A lantern-lit campsite on a jungle riverbank under a big tree at night |
| S034 | 3:16–3:20 | 4s | A muddy trailhead where a forest path meets a red-clay road, wooden survey stakes at its edge, dawn |
| S035 | 3:20–3:26 | 6s | Leaf-litter under a giant Brazil-nut tree, round nut pods on the ground, deep forest |
| S036 | 3:26–3:30 | 4s | A small forest clearing at dusk with a row of weathered wooden crosses overgrown with vines |
| S037 | 3:30–3:36 | 6s | A forested ridge with straight earthwork ditches and terraces in mist at dawn |
| S038 | 3:36–3:44 | 8s | A hidden multi-tiered waterfall in a mossy forest gorge with rolling mist |
| S039 | 3:44–3:50 | 6s | The wide muddy Amazon main channel with sandbanks, then underwater shallows |
| S040 | 3:50–3:56 | 6s | A riverside stilt-house village with wooden canoes and a floating dock, overcast morning |
| S041 | 3:56–4:02 | 6s | Underwater in a black-water creek mouth among tangled submerged roots |
| S042 | 4:02–4:08 | 6s | Flooded forest (igapó) underwater: drowned trunks in dark green water |
| S043 | 4:08–4:16 | 8s | Floodplain lake in the dry season: clear water turning into a shrinking mud pool |
| S044 | 4:16–4:22 | 6s | Marsh lagoon covered with water hyacinth and lily pads at midday |
| S045 | 4:22–4:26 | 4s | A sandy riverbank drinking spot at dusk with a white egret |
| S046 | 4:26–4:32 | 6s | A small riverside vegetable garden (chácara) with a wooden fence and banana plants at midday |
| S047 | 4:32–4:40 | 8s | Red-soil riverbank cliff at the water's edge with a giant tree and an approaching storm |
| S048 | 4:40–4:44 | 4s | A quiet dirt road at the edge of the forest at dawn with mist over red earth |
| S049 | 4:44–4:50 | 6s | Rubber-tree estate trail at dawn (seringal), mist and tin cups |
| S050 | 4:50–4:56 | 6s | A slope grove of rubber trees overlooking a smoking clear-cut valley |
| S051 | 4:56–5:04 | 8s | Dusty village square before a small wooden union hall with a tin roof, golden hour |
| S052 | 5:04–5:10 | 6s | Rustic wooden room interior: table by a shuttered window, late afternoon light |
| S053 | 5:10–5:16 | 6s | Back yard of a wooden stilt house at blue-hour dusk |
| S054 | 5:16–5:20 | 4s | A small-town police post at night with a single bare bulb and an old jeep |
| S055 | 5:20–5:26 | 6s | A simple wooden memorial post at the forest edge under a giant tree, night turning to sunrise |
| S056 | 5:26–5:32 | 6s | A protected reserve's horseshoe oxbow lake at sunrise with a small canoe landing, aerial |
| S057 | 5:32–5:36 | 4s | A huge lone rubber tree in a forest clearing at sunrise with a tin cup on its trunk |
| S058 | 5:36–5:40 | 4s | A silent misty river valley at cold blue dawn seen from a high bank |
| S059 | 5:40–5:46 | 6s | A jungle airstrip clearing at cold blue dawn with a survey drone on a launch rail |
| S060 | 5:46–5:52 | 6s | Drone point-of-view over a hillside village beside a small stream, morning mist |
| S061 | 5:52–6:00 | 8s | A rocky stream bank in a shallow forest gorge: an abandoned camp |
| S062 | 6:00–6:08 | 8s | Red-earth logging road and sawmill landing with towering stacks of felled logs, smoky dusk |
| S063 | 6:08–6:16 | 8s | A burning hillside fire front at dusk seen from a high aerial, with a peaceful clearing beyond |
| S064 | 6:16–6:24 | 8s | A rocky outcrop at the forest edge overlooking a valley with a glowing horizon at dusk |
| S065 | 6:24–6:32 | 8s | A maze of forested river islands and channels at misty sunrise |
| S066 | 6:32–6:40 | 8s | A vast flat-topped forested plateau above a sea of clouds at sunrise, wind waves on the canopy |
| S067 | 6:40–6:48 | 8s | A quiet river sandbar beach at nightfall with driftwood and fireflies at the treeline |
| S068 | 6:48–6:54 | 6s | A forest clearing at night under the Milky Way with hundreds of fireflies |

---

# STEP 3 & STEP 4 — SCENES (voice-over slots of 4, 6, 8 and 10 seconds; every Flow video is generated at 8 or 10 seconds)

**How each scene is shaped:**
Header line (scene number, label, time range and clip length) → **VO sync** (editor note only, never paste into Flow: the spoken lines and their timestamps inside this clip) → Step 3 Ingredients → Step 3 Reference Image Prompt → Step 4 Ingredients → Video Prompt (Google Flow, generated at 8 s or 10 s; in-clip second marks where `0s` = the clip's start, the voice-over beats first and spare seconds after) → Sound → Cut→ to the next scene.
Append the GLOBAL LOCK BLOCK to the end of every Step 3 and Step 4 prompt.

---

### Segment 1 — Hook (Scenes 1–9) | 0:00–0:56

**S001 — Silent intro over two rivers | 0:00–0:10 (10s slot → generate 10s in Flow)**
VO sync: (0:00–0:07) audio-file intro credit, no narration → BGM only · (0:07) "வணக்கம்" · (0:09) "இன்று நாம என்ன பார்க்கப் போறோம்னா"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: none (unique location, described in the prompt: High aerial over the meeting of two rivers at sunrise (brown and black water side by side)) · Scene Continuity Reference: none (first scene in the series)
Step 3 — Reference Image Prompt (Google Flow):
Ultra-wide drone-style aerial shot at sunrise over the meeting of two great rivers, one muddy brown and one dark tea-black, running side by side between banks of unbroken emerald rainforest, low clouds drifting, a pale gold sun on the horizon, no roads, boats or buildings.
Save as: `S001_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S001_Ref.png`
Video Prompt (Google Flow, generate 10s = the full 10s slot):
I2V from `S001_Ref.png`. 0–7s: the camera glides slowly forward along the line where the two rivers meet, mist curling off the water and treetops, the sun edging up, a flock of distant parrots crossing far below; 7–10s: the sun clears the horizon, the light warms and the motion eases. Slow, majestic, no cuts. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): Deep low string drone and a distant war-drum heartbeat fade in; wind rush, birdsong, a distant howler-monkey call; the music dips slightly at 7s to open space.
Cut→S002: Hard cut, continuing the same glide upward.

**S002 — A place not fully understood | 0:10–0:16 (6s slot → generate 8s in Flow)**
VO sync: (0:10) "இந்த உலகத்தில இருக்குற காடுகள்ல" · (0:12) "மனிதனே இன்னும் முழுசா புரிஞ்சுக்க முடியாத" · (0:15) "ஒரு இடம் இருக்கு"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: none (unique location, described in the prompt: Above the clouds: the forest sea rolling to the far Andean foothills at dawn) · Scene Continuity Reference: `S001_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Very high aerial view above thin clouds at dawn, an endless green sea of canopy rolling toward faint blue mountain foothills on the far horizon, cloud shadows drifting across the forest, gold light, no signs of humans.
Save as: `S002_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S002_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the voice-over beats, the last 2s are spare footage):
I2V from `S002_Ref.png`. 0–3s: the camera rises above the cloud layer and tilts up so the forest seems to widen to the horizon; 3–6s: cloud banks thicken and drift across the canopy so parts of the forest vanish; the last second holds on one dark cloud-shadowed valley. 6–8s (spare 2s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 6s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): Music thins to a sustained cello note with a hint of mystery; wind, distant birds, a low resonance at 3s as the clouds thicken. From 6s to 8s the music and ambience sustain and ease down.
Cut→S003: Match cut on the dark valley, becoming a dive toward a single giant tree.

**S003 — The Amazon forest, no signal | 0:16–0:22 (6s slot → generate 8s in Flow)**
VO sync: (0:16) "அது எது தெரியுமா" · (0:17) "அமேசான் காடு" · (0:18) "இந்த காடு எவ்வளவு பெரிசுன்னா" · (0:19) "இதில ஒரு பகுதிக்குள்ள போனா" · (0:21) "உங்களுக்கு ஜீபிஎஸ் சிக்னலே கிடைக்காது"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: none (unique location, described in the prompt: Crown of a colossal emergent kapok tree towering above the canopy at sunrise) · Scene Continuity Reference: `S002_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Low aerial view from just above the flat spreading crown of a colossal kapok (sumaúma) tree rising above the surrounding canopy, orchids and bromeliads on its branches, sun rays fanning behind it, a small dark gap in the leaves beside its trunk.
Save as: `S003_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S003_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the voice-over beats, the last 2s are spare footage):
I2V from `S003_Ref.png`. 0–1s: hold; at 1s the sun flares golden behind the crown in one strong beat; 1–3s: the camera tilts down and begins a smooth dive along the trunk toward the dark gap; 3–6s: it plunges down through branches and leaves and the light drops from gold to deep green as the canopy closes overhead. 6–8s (spare 2s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 6s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): A strong orchestral hit on the sun flare at 1s; a descending whoosh through leaves; the music turns hushed with a low drone; a faint electronic dropout crackle at 5s hinting at lost signal. From 6s to 8s the music and ambience sustain and ease down.
Cut→S004: Continuous dive, arriving among the roots far below.

**S004 — Sunlight never touches the ground | 0:22–0:26 (4s slot → generate 8s in Flow)**
VO sync: (0:23) "சூரிய வெளிச்சம்" · (0:24) "கீழே தரைய தொடவே தொடாது"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: none (unique location, described in the prompt: Dark forest floor among giant buttress roots and hanging lianas) · Scene Continuity Reference: `S003_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Extreme low-angle shot on the dark forest floor among the enormous flat buttress roots of a giant tree, lianas hanging, looking up a tunnel of trunks toward a few fading amber shafts of light high above, the ground deep in green shadow with mist.
Save as: `S004_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S004_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the voice-over beats, the last 4s are spare footage):
I2V from `S004_Ref.png`. 0–2s: the light shafts fade and thin out until the floor is nearly dark; 2–4s: a beat of stillness as the camera tilts down slowly along a buttress root. 4–8s (spare 4s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 4s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): The cello note fades; dripping water, insect hum; a soft, mysterious pad rises at 2s. From 4s to 8s the music and ambience sustain and ease down.
Cut→S005: Hard cut to an aerial push toward a smoke thread.

**S005 — People the world has never seen | 0:26–0:32 (6s slot → generate 8s in Flow)**
VO sync: (0:26) "இன்னும் சொல்லப் போனா" · (0:27) "இந்த நொடிக்கூட" · (0:28) "இந்த காட்டுக்குள்ள வெளி உலகத்தைப் பாக்காத" · (0:30) "யாருக்கும் தெரியாத மனிதர்கள்"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: none (unique location, described in the prompt: Hidden oxbow lake in the forest at early morning, one thatched roof on its bank) · Scene Continuity Reference: `S004_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Aerial view at early morning pushing in toward a small crescent-shaped oxbow lake hidden deep in the forest, mirror-still water reflecting the canopy, a single palm-thatch roof on its bank and one thin thread of smoke rising straight up, no people visible.
Save as: `S005_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S005_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the voice-over beats, the last 2s are spare footage):
I2V from `S005_Ref.png`. 0–3s: the camera pushes in slowly toward the lake as mist lifts off the water; 3–5s: the reflection and the smoke thread become crisp; 5–6s: the camera settles over the thatched roof. 6–8s (spare 2s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 6s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): A suspense bed with a low pulsing synth; one distant wooden knock at 4s, then a hush. From 6s to 8s the music and ambience sustain and ease down.
Cut→S006: Hard cut to a stormy ridge.

**S006 — A story more thrilling | 0:32–0:36 (4s slot → generate 8s in Flow)**
VO sync: (0:32) "வளந்துட்டு இருக்காங்க" · (0:33) "ஆனா நான் இப்ப சொல்லப் போற கதை" · (0:35) "அதை விட திரில்லூட்டும்"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: none (unique location, described in the prompt: Forested ridge line at dusk under towering thunderclouds with an orange glow on the horizon) · Scene Continuity Reference: `S005_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide aerial view at dusk over a long forested ridge under towering dark thunderclouds edged in gold, a faint band of dark smoke and an orange glow on the far horizon behind the ridge.
Save as: `S006_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S006_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the voice-over beats, the last 4s are spare footage):
I2V from `S006_Ref.png`. 0–2s: the camera pulls back and rises smoothly over the ridge; 2–4s: the thunderclouds roll slowly, their edges gold, and the orange glow on the horizon brightens. 4–8s (spare 4s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 4s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): The pulse builds with an ominous low brass note; wind and a distant low thunder rumble at 3s. From 4s to 8s the music and ambience sustain and ease down.
Cut→S007: Cross-dissolve into a fog-filled valley.

**S007 — A true incident, not a myth | 0:36–0:42 (6s slot → generate 8s in Flow)**
VO sync: (0:36) "ஏனா இது கட்டுக் கதை இல்ல" · (0:38) "இது நடந்த சம்பவம்" · (0:39) "2022 வருசம் வரைக்கும்"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: none (unique location, described in the prompt: A valley filled with white fog at first light, one thatched roof emerging at its edge) · Scene Continuity Reference: `S006_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Aerial view at first light over a valley filled with white fog, a single palm-thatch roof emerging from the mist at the valley's edge, no smoke and no people.
Save as: `S007_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S007_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the voice-over beats, the last 2s are spare footage):
I2V from `S007_Ref.png`. 0–3s: the camera glides slowly over the fog; 3–5s: the fog thins slightly and the thatched roof becomes clear; 5–6s: the camera holds still on it. 6–8s (spare 2s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 6s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): Music drops to a hushed pad; wind; a single struck low note at 4s. From 6s to 8s the music and ambience sustain and ease down.
Cut→S008: Cross-dissolve into a smoky twilight sky.

**S008 — Watch until the last part | 0:42–0:52 (10s slot → generate 10s in Flow)**
VO sync: (0:42) "நடந்துக்கிட்டே இருந்தது" · (0:43) "இந்த வீடியோவை கடைசி வரைக்கும் பாருங்க" · (0:45) "ஏனா கடைசி பகுதில சொல்ற உண்மை" · (0:47) "இன்னைக்கும் அமேசான் காட்டுக்குள்ள" · (0:48) "நடந்துக்கிட்டு இருக்குற" · (0:50) "ஒரு ஆபத்தை பத்தினது" · (0:51) "பிரேசில் நாட்டுல"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: none (unique location, described in the prompt: Twilight over a smoke-hazed river valley with a dull red sun and a line of small fires) · Scene Continuity Reference: `S007_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide aerial view at twilight over a smoke-hazed river valley, the sun a dull red disc through thick haze, a thin orange line of small fires glowing along the far riverbank, dark forest below.
Save as: `S008_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S008_Ref.png`
Video Prompt (Google Flow, generate 10s = the full 10s slot):
I2V from `S008_Ref.png`. 0–4s: the camera glides forward as haze drifts across the valley; 4–7s: the orange fire line grows brighter, foreshadowing a danger to come; 7–10s: the camera rises and pulls back over the valley, then holds high and wide as the smoke rises. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): An ominous low brass note rises at 4s over the pulse; wind; a faint crackle of distant fire from 7s.
Cut→S009: Cross-dissolve into farmland from the air.

**S009 — Rondônia and a forest named Tanaru | 0:52–0:56 (4s slot → generate 8s in Flow)**
VO sync: (0:52) "ரொண்டோனியா மாகாணத்துல" · (0:54) "ஒரு காடு இருக்கு" · (0:55) "அதோட பேரு தனாரு"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: none (unique location, described in the prompt: Rondônia farmland frontier from the air: straight red dirt roads, pasture, one forest island) · Scene Continuity Reference: `S008_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
High aerial view descending toward a small isolated island of dense green forest surrounded by cleared brown pasture, straight red dirt roads and a few cattle dots, dawn light, the island glowing in a lone patch of sun.
Save as: `S009_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S009_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the voice-over beats, the last 4s are spare footage):
I2V from `S009_Ref.png`. 0–2s: the camera glides forward over cleared pasture and straight red roads; 2–4s: it tilts down toward the forest island and the sun brightens it. 4–8s (spare 4s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 4s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): A sombre low piano motif enters over the strings; wind and distant cattle lowing; a soft swell at 3s. From 4s to 8s the music and ambience sustain and ease down.
Cut→S010: Cross-dissolve down into a garden clearing.

---

### Segment 2 — Tanaru — The Man of the Hole (Scenes 10–15) | 0:56–1:28

**S010 — One man, alone for 26 years | 0:56–1:02 (6s slot → generate 8s in Flow)**
VO sync: (0:56) "இந்த காட்டுக்குள்ள" · (0:57) "கடந்த 26 வருசமா" · (0:58) "ஒரே ஒரு மனிசன் மட்டும்" · (1:00) "தனியா வாழ்ந்திருக்கான்" · (1:01) "இவனுக்கு பேரு கிடையாது"
Step 3 Ingredients: Vehicle/Subject Reference Image: `TanaruMan_Portrait.png`, `TanaruMan_6Angle.png` · Environment Reference Image: none (unique location, described in the prompt: Small cassava and banana garden clearing inside the forest, late golden afternoon) · Scene Continuity Reference: `S009_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide shot from behind blurred foreground leaves into a small forest garden clearing in late golden afternoon: rows of cassava plants and banana trees, a smoke-blackened palm-thatch roof at the far edge, the lone man standing small among the plants, his body turned partly away, face not yet clear.
Save as: `S010_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S010_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the voice-over beats, the last 2s are spare footage):
I2V from `S010_Ref.png`. 0–2s: the camera creeps forward through the foreground leaves; 2–4s: the leaves part and the camera slides closer as he stands alone among the cassava; at 4s he slowly turns so his lined, watchful face is clearly visible; 4–6s: the camera holds a medium shot as he looks toward the trees, calm and unspeaking. 6–8s (spare 2s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 6s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): The piano motif continues over a soft pad; forest evening ambience; a single low string swell at 4s. From 6s to 8s the music and ambience sustain and ease down.
Cut→S011: Hard cut to a close view of his face.

**S011 — No name, no known language | 1:02–1:08 (6s slot → generate 8s in Flow)**
VO sync: (1:03) "இவன் என்ன மொழி பேசுறான்னு" · (1:04) "யாருக்கும் தெரியாது" · (1:05) "அவனோட கூட்டத்தைப் பத்தி" · (1:06) "எந்த பதிவும் இல்ல"
Step 3 Ingredients: Vehicle/Subject Reference Image: `TanaruMan_Portrait.png`, `TanaruMan_6Angle.png` · Environment Reference Image: none (unique location, described in the prompt: Doorway of his palm-thatch hut: smoke-blackened palm wall, packed red earth, warm dusk) · Scene Continuity Reference: `S010_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Close-up of the lone man's lined face in three-quarter profile at his hut doorway, dark watchful eyes lit by warm dusk light, a smoke-blackened palm-leaf wall behind him.
Save as: `S011_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S011_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the voice-over beats, the last 2s are spare footage):
I2V from `S011_Ref.png`. 0–3s: a very slow push-in on his face; his eyes glance away and his expression stays sorrowful; 3–6s: the camera keeps easing closer to a still, silent hold on his eyes. 6–8s (spare 2s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 6s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): The music drops to a hollow low tone; fire crackle from off-screen; a soft breath of wind. From 6s to 8s the music and ambience sustain and ease down.
Cut→S012: Hard cut to the rim of a pit.

**S012 — Man of the Hole | 1:08–1:12 (4s slot → generate 8s in Flow)**
VO sync: (1:08) "ஆனா இந்த உலகம் அவனை" · (1:09) "Man of the Hole" · (1:10) "அப்படின்னு கூப்பிட்டுச்சு"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: none (unique location, described in the prompt: Rim of a deep hand-dug pit at the edge of a dry palm grove, late golden light) · Scene Continuity Reference: `S011_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Macro at the rim of a deep, perfectly round hand-dug pit in red earth at the edge of a dry palm grove in late golden light, soil crumbling at the lip, a few dry leaves, dark depth below.
Save as: `S012_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S012_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the voice-over beats, the last 4s are spare footage):
I2V from `S012_Ref.png`. 0–2s: the camera pushes toward the rim and tilts down as a small clump of soil tumbles in; 2–4s: a slow rack focus from the lip to the dark depths. 4–8s (spare 4s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 4s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): The music holds a low pulsing tone; soil crumbling and a soft thud; a deep resonant hit with a fading echo at 1s. From 4s to 8s the music and ambience sustain and ease down.
Cut→S013: Match cut on the dark circle, becoming a top-down view.

**S013 — He dug deep holes everywhere | 1:12–1:18 (6s slot → generate 8s in Flow)**
VO sync: (1:13) "ஏன் இந்த பேரு தெரியுமா" · (1:14) "இந்த மனிசன் காட்டுக்குள்ள" · (1:16) "ஆளுக்கு ஒரு இடத்துல" · (1:17) "ஆழமான குழிகள்"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: none (unique location, described in the prompt: Fern and palm-seedling forest floor seen from directly above, a field of hand-dug pits) · Scene Continuity Reference: `S012_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Straight top-down view of a forest floor carpeted with ferns and palm seedlings in dusk light, a single deep round hand-dug pit in the centre, a line of bare footprints leading off between the plants.
Save as: `S013_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S013_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the voice-over beats, the last 2s are spare footage):
I2V from `S013_Ref.png`. 0–2s: the camera holds over the single pit; 2–4s: it rises slowly straight up and a second and a third pit come into view one after another; 4–6s: further pits appear across the fern floor, forming a scattered pattern. 6–8s (spare 2s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 6s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): Slow rising strings; soil crumble, leaf rustle; a soft percussive thud as each new pit appears. From 6s to 8s the music and ambience sustain and ease down.
Cut→S014: Hard cut to an animal trail.

**S014 — Pits to trap animals | 1:18–1:22 (4s slot → generate 8s in Flow)**
VO sync: (1:18) "தோண்டி வைச்சிருந்தான்" · (1:19) "சில குழிகள்" · (1:20) "மிருகங்களை பிடிக்குற வலைக்கு"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: none (unique location, described in the prompt: Animal trail beside a muddy clay bank in late golden light) · Scene Continuity Reference: `S013_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Low view along an animal trail beside a muddy clay bank in late golden light, hoof-prints in the mud, a pit covered with a thin lattice of branches and leaves in the middle of the trail.
Save as: `S014_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S014_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the voice-over beats, the last 4s are spare footage):
I2V from `S014_Ref.png`. 0–2s: the camera glides low along the trail past the hoof-prints; 2–4s: it slows and stops at the covered trap as a leaf settles on it. 4–8s (spare 4s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 4s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): Light percussive rhythm; leaf rustle, distant birds; a sting on the covered trap at 3s. From 4s to 8s the music and ambience sustain and ease down.
Cut→S015: Hard cut to the hut interior.

**S015 — A hiding place, and an empty hole inside the house | 1:22–1:28 (6s slot → generate 8s in Flow)**
VO sync: (1:22) "சில குழிகள்" · (1:23) "அவன் ஒளிஞ்சுக்குற இடத்துக்கு" · (1:24) "ஒரு வீட்டுக்குள்ளேயே" · (1:25) "ஒரு காலி குழி இருந்துச்சு" · (1:26) "அது எதுக்குன்னு" · (1:27) "இன்னைக்கும் யாருக்கும் புரியல"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: none (unique location, described in the prompt: Inside the hut: woven palm walls, packed-earth floor, a round pit, an empty hammock, dusty light through thatch gaps) · Scene Continuity Reference: `S014_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Interior view from just inside the low doorway of the palm-thatch hut: woven palm walls, packed red-earth floor, an empty hammock strung in a corner, shafts of dusty golden light through gaps in the thatch, a small sunken hiding hollow beside the doorpost and a round pit dug into the floor's centre; no people.
Save as: `S015_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S015_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the voice-over beats, the last 2s are spare footage):
I2V from `S015_Ref.png`. 0–2s: the camera dollies in at ground level past the small sunken hollow beside the doorpost; 2–3s: it glides along the woven wall past the empty hammock; 3–5s: it slows and stops over the round empty pit; 5–6s: a slow rack focus into the pit's depth. 6–8s (spare 2s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 6s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): Music thins to a hollow held note; hammock rope creak, a faint wind through thatch; a low sting at 3s on the pit. From 6s to 8s the music and ambience sustain and ease down.
Cut→S016: Hard cut to a smoky frontier road.

---

### Segment 3 — Tanaru — The Lone Survivor (Scenes 16–25) | 1:28–2:32

**S016 — The 1970s: outsiders arrive | 1:28–1:34 (6s slot → generate 8s in Flow)**
VO sync: (1:29) "இப்போ இவன் ஏன் தனியாயிருந்தான்னு தெரியுமா" · (1:31) "1970களில் ஆரம்பிச்சு"
Step 3 Ingredients: Vehicle/Subject Reference Image: `Bulldozer_Portrait.png`, `Bulldozer_6Angle.png` · Environment Reference Image: none (unique location, described in the prompt: 1970s frontier road with a barbed-wire fence and a wooden ranch gate under a smoky orange sky) · Scene Continuity Reference: `S015_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide low-angle shot at smoky orange dusk along a red-earth frontier road with a barbed-wire fence and a rough wooden ranch gate in the foreground, black smoke on the horizon, and far in the haze the small yellow shape of a bulldozer.
Save as: `S016_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S016_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the voice-over beats, the last 2s are spare footage):
I2V from `S016_Ref.png`. 0–2s: the camera holds still on the empty road as smoke drifts past the gate; 2–4s: the bulldozer emerges from the haze and grows larger; 4–6s: it rolls closer with its blade pushing soil while the camera dollies back ahead of it. 6–8s (spare 2s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 6s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): A dark low brass drone and a slow taiko; from 2s the diesel rumble and track clank rise; wood cracking at the end. From 6s to 8s the music and ambience sustain and ease down.
Cut→S017: Hard cut to a ranch pasture.

**S017 — Ranchers and land-grabbers wipe out his people | 1:34–1:40 (6s slot → generate 8s in Flow)**
VO sync: (1:34) "நிலம் பிடிக்குற வெளியாட்கள்" · (1:36) "கேட்டில் ரெஞ்சர்ஸ்" · (1:37) "லேண்ட் கிராபர்ஸ்" · (1:38) "இவனோட முழு கூட்டத்தையுமே அழிச்சுட்டாங்க"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: none (unique location, described in the prompt: Cattle pasture of charred stumps with a lone ranch house and pickup at smoky dusk) · Scene Continuity Reference: `S016_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide low view at smoky dusk of a fenced cattle pasture with dozens of charred stumps still smouldering, a lone ranch house with a tin roof and a pickup truck far in the distance, a wall of forest at the far edge, smoke drifting; no people.
Save as: `S017_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S017_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the voice-over beats, the last 2s are spare footage):
I2V from `S017_Ref.png`. 0–2s: the camera holds as smoke drifts across the pasture; 2–4s: it pushes slowly toward the forest wall; 4–6s: smoke thickens and covers the forest wall until it darkens. Nothing violent is shown. 6–8s (spare 2s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 6s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): A dark low drone and a slow taiko; distant cattle, crackling embers; a hush at 5s. From 6s to 8s the music and ambience sustain and ease down.
Cut→S018: Hard cut to a burned village.

**S018 — A massacre, and one survivor | 1:40–1:44 (4s slot → generate 8s in Flow)**
VO sync: (1:40) "அது ஒரு படுகொலை" · (1:41) "இவன் ஒருத்தன் மட்டும் தப்பிச்சிருக்கான்" · (1:43) "அதுக்கப்புறம் இவனை யாருமே நம்பல"
Step 3 Ingredients: Vehicle/Subject Reference Image: `TanaruMan_Portrait.png`, `TanaruMan_6Angle.png` · Environment Reference Image: none (unique location, described in the prompt: A larger village clearing beside a stream after a tragedy: ruined thatched huts at smoky dusk) · Scene Continuity Reference: `S017_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide view at smoky dusk of a large village clearing beside a shallow stream after a tragedy: a ring of ruined, half-burnt thatched huts, empty hammocks swaying between charred poles, cold fire pits, scattered clay pots, drifting smoke, and at the frame edge a man crouched behind a tree, half visible, watching.
Save as: `S018_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S018_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the voice-over beats, the last 4s are spare footage):
I2V from `S018_Ref.png`. 0–2s: the camera glides sideways along the ring of ruined huts and the stream, empty hammocks swaying; 2–4s: the man steps out from behind the tree, his face visible with fear and grief. Nothing violent is shown. 4–8s (spare 4s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 4s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): Music turns mournful with a low cello; stream trickle, creaking hammock ropes; a soft low sting at 3s. From 4s to 8s the music and ambience sustain and ease down.
Cut→S019: Cross-dissolve to a hillside observation blind.

**S019 — Watched from a distance | 1:44–1:52 (8s slot → generate 10s in Flow)**
VO sync: (1:45) "பிரேசில் அரசாங்கத்தோட" · (1:46) "FUNAI அப்படின்னு ஒரு துறை இருக்கு" · (1:48) "இவங்க தூரத்தில இருந்தே" · (1:49) "இவனை கண்காணிச்சாங்க" · (1:50) "ஆனா நெருங்கவே இல்ல"
Step 3 Ingredients: Vehicle/Subject Reference Image: `TanaruMan_Portrait.png`, `TanaruMan_6Angle.png` · Environment Reference Image: none (unique location, described in the prompt: A leafy hillside observation blind high above a valley clearing) · Scene Continuity Reference: `S018_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Medium telephoto shot from a leaf-covered hillside blind high above a valley, framed by blurred foreground leaves, far below a small clearing where the lone man crouches at his fire in golden dusk light, his profile just visible.
Save as: `S019_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S019_Ref.png`
Video Prompt (Google Flow, generate 10s: the first 8s carry the voice-over beats, the last 2s are spare footage):
I2V from `S019_Ref.png`. 0–3s: a slow lateral creep behind the foreground leaves; 3–6s: the camera eases back so the man is smaller and more distant behind the leaf screen while he tends the fire and glances toward the trees; 6–8s: the camera stops at the same distance, refusing to move nearer. 8–10s (spare 2s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 8s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): Quiet held-breath ambience, faint fire crackle, insects, a soft pad; a subtle camera-focus click at 3s; a distant woodpecker. From 8s to 10s the music and ambience sustain and ease down.
Cut→S020: Hard cut to a creek crossing.

**S020 — The warning arrow | 1:52–1:58 (6s slot → generate 8s in Flow)**
VO sync: (1:52) "ஏனா இவன் நெருங்கற யாரையும்" · (1:54) "அம்பு எய்து விரட்டி அடிப்பான்" · (1:55) "நினைச்சு பாருங்க" · (1:56) "26 வருசம்" · (1:57) "ஒரு மனிசன் மட்டும்"
Step 3 Ingredients: Vehicle/Subject Reference Image: `TanaruMan_Portrait.png`, `TanaruMan_6Angle.png` · Environment Reference Image: none (unique location, described in the prompt: Shallow creek crossing with mossy rocks at the forest edge, golden dusk) · Scene Continuity Reference: `S019_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Medium shot of the lone man standing on a mossy rock in a shallow forest creek at golden dusk, three-quarter profile, face clearly visible with a fierce, wary expression, bow raised and a feathered arrow drawn toward trees on the far bank, water rippling around the rocks; no target in frame.
Save as: `S020_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S020_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the voice-over beats, the last 2s are spare footage):
I2V from `S020_Ref.png`. 0–2s: the camera pushes in slowly as he draws the bow tight; 2–3s: he releases and the arrow flies out of frame into the far trees, a warning shot, striking a trunk; 3–6s: he lowers the bow, the fierce look softening into a lonely, exhausted stare as the camera pushes to a close view of his face. 6–8s (spare 2s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 6s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): Music thins to one held string note; bow-string creak, arrow whoosh, wood thud at 2s; the note swells into a lonely melody at 4s. From 6s to 8s the music and ambience sustain and ease down.
Cut→S021: Cross-dissolve into a time-lapse along a footpath.

**S021 — The forest was his world | 1:58–2:04 (6s slot → generate 8s in Flow)**
VO sync: (1:59) "பேச யாருமே இல்ல" · (2:00) "தன் கலாச்சாரத்தைப் பகிர்ற" · (2:01) "யாருமே இல்ல" · (2:02) "காடே அவனது உலகம்"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: none (unique location, described in the prompt: Narrow forest footpath under a canopy tunnel, seasons passing) · Scene Continuity Reference: `S020_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Locked-off view down a narrow footpath through a tunnel of trees in golden dusk light, fallen leaves on the ground, the hint of a thatched roof far at the end of the path, no people.
Save as: `S021_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S021_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the voice-over beats, the last 2s are spare footage):
I2V from `S021_Ref.png`. 0–6s: a time-lapse of the seasons: leaves fall, rain passes, green returns, light shafts sweep across the path, and by the last second the light settles into a calm, soft morning glow; the camera stays locked. 6–8s (spare 2s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 6s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): Slow melancholic solo flute; fast wind whoosh, day-night bird and cricket cycles, passing rain; the sound calms to a soft morning ambience at 5s. From 6s to 8s the music and ambience sustain and ease down.
Cut→S022: Cross-dissolve to a dew-covered yard.

**S022 — August 2022: a visitor arrives | 2:04–2:10 (6s slot → generate 8s in Flow)**
VO sync: (2:04) "2022 ஆகஸ்ட் மாசம்" · (2:06) "FUNAI ஆபீசர் ஒருத்தர்" · (2:07) "வழக்கம் போல சுத்தி பாக்கப் போனார்" · (2:09) "அப்போ அவனோட குடிசைக்குள்ள"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: none (unique location, described in the prompt: Dew-covered packed-earth yard in front of his small sleeping hut, early morning) · Scene Continuity Reference: `S021_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Low view in soft early-morning light across a dew-covered yard of packed earth toward a small thatched sleeping hut with a low woven doorway, banana leaves beaded with dew, no people, a calm quiet.
Save as: `S022_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S022_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the voice-over beats, the last 2s are spare footage):
I2V from `S022_Ref.png`. 0–3s: the camera walks forward across the yard as if a visitor, dew drops shaking off the leaves; 3–5s: it reaches the doorway; 5–6s: it slows at the threshold, looking into the dim interior. 6–8s (spare 2s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 6s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): Soft morning ambience, light footsteps in dew; the flute melody fades to a single held note. From 6s to 8s the music and ambience sustain and ease down.
Cut→S023: Match cut through the doorway into the hut.

**S023 — Found in the hammock | 2:10–2:16 (6s slot → generate 8s in Flow)**
VO sync: (2:10) "ஒரு தூக்கு கட்டில்ல" · (2:12) "அந்த மனிசன் இறந்து கிடந்தான்" · (2:13) "எந்த வன்முறையும் இல்ல" · (2:15) "வேற ஆளோட சுவடே இல்ல"
Step 3 Ingredients: Vehicle/Subject Reference Image: `TanaruMan_Portrait.png`, `TanaruMan_6Angle.png` · Environment Reference Image: none (unique location, described in the prompt: His smaller sleeping hut: low thatched shelter with a woven doorway, hammock inside, soft morning light) · Scene Continuity Reference: `S022_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Soft-lit view from the low woven doorway of a small thatched sleeping hut in the morning: a woven hammock hangs in the centre with the lone man lying still and peaceful in it, eyes closed, calm face, nothing disturbed, gentle daylight through the doorway.
Save as: `S023_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S023_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the voice-over beats, the last 2s are spare footage):
I2V from `S023_Ref.png`. 0–2s: the camera moves slowly through the doorway toward the hammock; 2–3s: it stops and holds on his peaceful, still face; 3–5s: it pans gently across the tidy hut, bow, pots and cold fire all undisturbed; 5–6s: it tilts down to the earthen floor showing only one line of his own footprints. Nothing graphic. 6–8s (spare 2s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 6s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): The flute fades to a single soft sustained string; a faint breeze through thatch and a gentle hammock creak; a hush at 3s. From 6s to 8s the music and ambience sustain and ease down.
Cut→S024: Match cut on the hammock, moving to a macro.

**S024 — The macaw feathers | 2:16–2:24 (8s slot → generate 10s in Flow)**
VO sync: (2:16) "ஆனா அவன் படுத்திருந்த விதம்" · (2:18) "அவன் மேல மக்காவ் பறவையோட" · (2:20) "இறகுகள் அலங்காரமா வெச்சிருந்தான்" · (2:22) "மரணத்துக்கு தன்னைத்தானே"
Step 3 Ingredients: Vehicle/Subject Reference Image: `Macaw_Portrait.png`, `Macaw_6Angle.png`, `TanaruMan_Portrait.png`, `TanaruMan_6Angle.png` · Environment Reference Image: none (unique location, described in the prompt: Macro on the hammock's woven fibres in a narrow shaft of morning light through a thatch gap) · Scene Continuity Reference: `S023_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Close top-down view of the hammock's woven fibres in a narrow shaft of morning light through a gap in the thatch, scarlet-and-blue macaw feathers laid carefully and symmetrically over the man's chest, his calm face at the top edge of frame with closed eyes.
Save as: `S024_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S024_Ref.png`
Video Prompt (Google Flow, generate 10s: the first 8s carry the voice-over beats, the last 2s are spare footage):
I2V from `S024_Ref.png`. 0–2s: a slow push-in on the hammock; 2–4s: a gentle drift down over the feathers with a breeze stirring one feather; 4–6s: the camera glides slowly up to his peaceful face; 6–8s: it holds still, a scarlet feather settling in the last second. 8–10s (spare 2s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 8s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): A slow, reverent string melody; soft feather rustle, a breeze; one distant macaw call at 2s; silence in the last second. From 8s to 10s the music and ambience sustain and ease down.
Cut→S025: Slow cross-dissolve, pulling outside to the night.

**S025 — Everything vanished with him | 2:24–2:32 (8s slot → generate 10s in Flow)**
VO sync: (2:24) "தயார் பண்ணிக்கிட்ட மாதிரி" · (2:25) "இதில தான் இருக்கு உண்மையான திகில்" · (2:27) "இவன் வாழ்ந்த மொழி" · (2:28) "இவன் கூட்டத்தோட பேரு" · (2:29) "இவனோட சொந்த பேரு" · (2:31) "எல்லாமே இவனோட இறப்போட"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: none (unique location, described in the prompt: The clearing at night under moonlight, mist rising from a nearby stream) · Scene Continuity Reference: `S024_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide view from outside the little hut at night: the doorway dark, the small fire at its entrance nearly burnt out, moonlight and a thick mist rising from a nearby stream, banana leaves silver in the moonlight, no people.
Save as: `S025_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S025_Ref.png`
Video Prompt (Google Flow, generate 10s: the first 8s carry the voice-over beats, the last 2s are spare footage):
I2V from `S025_Ref.png`. 0–3s: the camera pulls slowly back from the hut; 3–6s: mist thickens and drifts across the clearing while the fire embers glow lower; 6–8s: the last ember dies, the smoke dissolves and the hut fades into the mist and darkness. 8–10s (spare 2s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 8s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): The melody fades to a single low note; crackle of dying embers, a fading breeze; a last soft hiss at 7s. From 8s to 10s the music and ambience sustain and ease down.
Cut→S026: Cross-dissolve, the camera rising into a pre-dawn sky.

---

### Segment 4 — The Pattern & Fawcett — The Obsession (Scenes 26–31) | 2:32–3:06

**S026 — One page of a bigger pattern | 2:32–2:38 (6s slot → generate 8s in Flow)**
VO sync: (2:32) "மறைஞ்சு போச்சு" · (2:33) "ஆனா இது ஒரு தனி சம்பவம் இல்ல" · (2:35) "இது ஒரு பெரிய பேட்டர்னோட" · (2:37) "ஒரு பகுதி மட்டும் தான்"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: none (unique location, described in the prompt: Braided river network of the Xingu basin at pre-dawn from the air, tiny smoke threads) · Scene Continuity Reference: `S025_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
High aerial view at pre-dawn blue light over a branching network of rivers and lakes threading through unbroken forest, several tiny distant smoke threads rising from hidden clearings, mist along the water.
Save as: `S026_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S026_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the voice-over beats, the last 2s are spare footage):
I2V from `S026_Ref.png`. 0–4s: the camera rises and drifts forward, revealing more and more small smoke threads across the forest so a pattern forms; 4–6s: the sun rises and the colour warms to a sepia-tinged golden haze, ready for a dissolve. 6–8s (spare 2s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 6s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): A slow rising string line; wind and distant birds; at 4s a soft old-film warmth enters with a gentle harp. From 6s to 8s the music and ambience sustain and ease down.
Cut→S027: Cross-dissolve into a 1925 colonial street.

**S027 — 1925: an English army officer | 2:38–2:42 (4s slot → generate 8s in Flow)**
VO sync: (2:38) "1925ம் வருடம்" · (2:40) "ஆங்கிலேய ஆர்மி அதிகாரி ஒருத்தர்"
Step 3 Ingredients: Vehicle/Subject Reference Image: `Explorers_Portrait.png`, `Explorers_6Angle.png` · Environment Reference Image: none (unique location, described in the prompt: A cobbled colonial town street at misty dawn in 1925) · Scene Continuity Reference: `S026_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Medium wide shot of a cobbled colonial town street at misty dawn in 1925, whitewashed low buildings, a mule cart, the tall grey-moustached colonel in a pith helmet and khaki walking toward the camera, face clearly visible and resolute, warm sepia-tinted morning light.
Save as: `S027_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S027_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the voice-over beats, the last 4s are spare footage):
I2V from `S027_Ref.png`. 0–2s: the camera tracks backward ahead of him as he walks; 2–4s: he lifts his gaze toward the distance with quiet conviction. 4–8s (spare 4s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 4s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): A warm adventurous theme on harp and pizzicato strings; cobble footsteps, a mule bell, dawn birds. From 4s to 8s the music and ambience sustain and ease down.
Cut→S028: Hard cut to a lodge veranda.

**S028 — His belief in a hidden ancient city | 2:42–2:48 (6s slot → generate 8s in Flow)**
VO sync: (2:42) "பெயர் பெர்சி ஃபாசெட்" · (2:43) "இவருக்கு ஒரு நம்பிக்கை இருந்தது" · (2:45) "அமேசான் காட்டுக்குள்ள" · (2:46) "ஒரு பழங்கால நகரம்" · (2:47) "ஒளிஞ்சிருக்குன்னு"
Step 3 Ingredients: Vehicle/Subject Reference Image: `Explorers_Portrait.png`, `Explorers_6Angle.png` · Environment Reference Image: none (unique location, described in the prompt: Wooden veranda of a 1925 riverside trading-post lodge at misty morning) · Scene Continuity Reference: `S027_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Medium shot in warm misty morning light on the wooden veranda of a 1925 riverside trading-post lodge: the tall grey-moustached colonel in his pith helmet seated at a plank table studying a hand-drawn map, face clearly visible, a lantern and a tin mug beside the map, a slow brown river and canoes behind him.
Save as: `S028_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S028_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the voice-over beats, the last 2s are spare footage):
I2V from `S028_Ref.png`. 0–2s: the camera settles; 2–4s: it pushes in slowly toward the colonel's face as his pale blue eyes light with conviction; 4–6s: a rack focus drops from his face to the map on the table where a hand-inked circle marks an empty unmapped centre. 6–8s (spare 2s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 6s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): The theme on pizzicato strings; paper rustle, lantern flutter, river lapping, dawn birds; a soft mystery sting at 5s on the circled mark. From 6s to 8s the music and ambience sustain and ease down.
Cut→S029: Hard cut to a map inside a tent.

**S029 — He named it | 2:48–2:52 (4s slot → generate 8s in Flow)**
VO sync: (2:48) "இவர் அதுக்கு பெயர் வெச்சிருந்தார்" · (2:51) "இவர் இதுக்கு முன்னாடியே"
Step 3 Ingredients: Vehicle/Subject Reference Image: `Explorers_Portrait.png`, `Explorers_6Angle.png` · Environment Reference Image: none (unique location, described in the prompt: Inside a canvas expedition tent at night, a map on a camp table lit by an oil lantern) · Scene Continuity Reference: `S028_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Macro top-down view of a hand-drawn map spread on a camp table inside a canvas expedition tent at night, lit by a single oil lantern, ink rivers winding across the paper, one circled geometric glyph deep in the unmapped centre; no readable letters or words.
Save as: `S029_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S029_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the voice-over beats, the last 4s are spare footage):
I2V from `S029_Ref.png`. 0–2s: the glyph seems to glow softly in the lantern's flicker; 2–4s: the camera glides slowly along a river line toward it. 4–8s (spare 4s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 4s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): A hushed harp and low strings; lantern flame flutter, paper crinkle, night insects. From 4s to 8s the music and ambience sustain and ease down.
Cut→S030: Hard cut to a map room.

**S030 — Many journeys in and out; the society trusted his maps | 2:52–3:00 (8s slot → generate 10s in Flow)**
VO sync: (2:52) "பல தடவை அமேசான் காட்டுக்குள்ள" · (2:54) "போய்த் திரும்பி வந்திருக்கார்" · (2:55) "ராயல் ஜியாகிராஃபிக்கல் சொசைட்டிக்கூட" · (2:57) "இவரோட வரைபடம் தயாரிப்புல" · (2:59) "நம்பிக்கை வெச்சிருந்துச்சு"
Step 3 Ingredients: Vehicle/Subject Reference Image: `Explorers_Portrait.png`, `Explorers_6Angle.png` · Environment Reference Image: none (unique location, described in the prompt: A London-style geographical society map room: oak desk, green-shaded lamp, brass globe) · Scene Continuity Reference: `S029_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Macro top-down view of a large hand-drawn map on a polished oak table in a wood-panelled 1920s map room lit by a green-shaded brass lamp, a brass globe and brass dividers on the desk, ink rivers winding across the paper, one circled geometric glyph deep in the unmapped centre and dotted routes looping out and back; no readable letters or words.
Save as: `S030_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S030_Ref.png`
Video Prompt (Google Flow, generate 10s: the first 8s carry the voice-over beats, the last 2s are spare footage):
I2V from `S030_Ref.png`. 0–3s: the camera holds tight on the circled glyph in the lamplight; 3–6s: it glides slowly along the dotted inked routes that loop out into the unmapped forest and return to the river; 6–8s: it rises to show the whole map with the globe and dividers beside it. 8–10s (spare 2s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 8s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): A hushed harp and low strings; paper crinkle, a slow clock tick, lamp hum; a soft reverent swell at 6s. From 8s to 10s the music and ambience sustain and ease down.
Cut→S031: Hard cut to a river jetty.

**S031 — The last journey begins | 3:00–3:06 (6s slot → generate 8s in Flow)**
VO sync: (3:00) "இப்போ தன் மகன் ஜேக்குடனும்" · (3:02) "மகனோட நண்பர் ஒருத்தரோடும்" · (3:03) "கடைசி பயணத்துக்கு ஒன்னா சேர்ந்துட்டு" · (3:05) "கிளம்பினார்"
Step 3 Ingredients: Vehicle/Subject Reference Image: `Explorers_Portrait.png`, `Explorers_6Angle.png` · Environment Reference Image: none (unique location, described in the prompt: A wooden river jetty with a steam launch and a canoe at misty dawn) · Scene Continuity Reference: `S030_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide shot in warm misty dawn light on a wooden river jetty: the grey-moustached colonel in the centre facing the river, faces clearly visible, the young freckled man and the stubbled companion arriving down the jetty steps in soft focus, a small steam launch and a wooden canoe moored beside, bundles of gear.
Save as: `S031_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S031_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the voice-over beats, the last 2s are spare footage):
I2V from `S031_Ref.png`. 0–2s: the camera cranes slowly up and back as the colonel looks resolutely ahead; 2–4s: the young man and the companion walk into frame to stand beside him; 4–6s: the three step forward together toward the launch's gangplank, the camera arcing to a three-quarter front angle. 6–8s (spare 2s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 6s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): The adventurous theme rises to a hopeful swell with brass and strings; wooden jetty creaks, water lapping, a steam-launch whistle at 4s, dawn birds. From 6s to 8s the music and ambience sustain and ease down.
Cut→S032: Match cut on their stride, into a savanna trail.

---

### Segment 5 — Fawcett — The Vanishing (Scenes 32–38) | 3:06–3:44

**S032 — Deeper into the forest | 3:06–3:12 (6s slot → generate 8s in Flow)**
VO sync: (3:06) "பிரேசில் காட்டுக்குள்ள" · (3:07) "ஆழமா போன இவங்க" · (3:08) "ஒரு கடிதத்துல இதுக்கப்புறம்" · (3:09) "நாங்க அனுப்புற தகவல்" · (3:11) "யாருக்கும் கிடைக்காது"
Step 3 Ingredients: Vehicle/Subject Reference Image: `Explorers_Portrait.png`, `Explorers_6Angle.png` · Environment Reference Image: none (unique location, described in the prompt: Dry cerrado savanna trail with buriti palms at golden morning, forest wall on the horizon) · Scene Continuity Reference: `S031_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Low-angle shot at ground level along a dusty savanna trail dotted with buriti palms in golden morning light, three pairs of leather boots and puttees marching toward the camera beside mule hoofprints, the three explorers' faces just visible above, determined and dusty, a dark line of forest on the horizon.
Save as: `S032_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S032_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the voice-over beats, the last 2s are spare footage):
I2V from `S032_Ref.png`. 0–3s: the camera tracks backwards ahead of the marching boots, dust puffing, then tilts up to their faces; 3–6s: the dark forest wall grows on the horizon and the trail bends toward it, the light dimming as they near it. 6–8s (spare 2s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 6s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): A steady marching pulse that slows and turns uneasy at 3s; dry wind, dusty boot steps, a far mule bell, cicadas; the music thins at 6s. From 6s to 8s the music and ambience sustain and ease down.
Cut→S033: Hard cut to a letter at night.

**S033 — The last letter; then they vanished | 3:12–3:16 (4s slot → generate 8s in Flow)**
VO sync: (3:12) "அப்படின்னு எழுதி அனுப்புனாங்க" · (3:13) "அதுக்கப்புறம் மூனு பேருமே" · (3:14) "காணாம போய்ட்டாங்க" · (3:15) "அடுத்த 90 வருசம்"
Step 3 Ingredients: Vehicle/Subject Reference Image: `Explorers_Portrait.png`, `Explorers_6Angle.png` · Environment Reference Image: none (unique location, described in the prompt: A lantern-lit campsite on a jungle riverbank under a big tree at night) · Scene Continuity Reference: `S032_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Macro of a folded letter sealed with a red wax seal on a wooden crate at night, a lantern glowing behind it, faint blurred ink lines on the paper edge that are not legible, a canvas tent and the roots of a big tree in soft focus.
Save as: `S033_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S033_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the voice-over beats, the last 4s are spare footage):
I2V from `S033_Ref.png`. 0–1s: the lantern flame flickers over the wax seal; 1–2s: the flame gutters and goes out; 2–4s: the camera pulls smoothly back to reveal the camp empty under the big tree in the moonlight. 4–8s (spare 4s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 4s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): A solo violin, then silence at 1s as the flame dies; night crickets, slow river lapping. From 4s to 8s the music and ambience sustain and ease down.
Cut→S034: Hard cut to a trailhead at dawn.

**S034 — Ninety years of searchers | 3:16–3:20 (4s slot → generate 8s in Flow)**
VO sync: (3:17) "நூற்றுக்கணக்கான ஆட்கள்" · (3:18) "இவங்களைத் தேடி" · (3:19) "காட்டுக்குள்ள போனாங்க"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: none (unique location, described in the prompt: A muddy trailhead where a forest path meets a red-clay road, wooden survey stakes at its edge, dawn) · Scene Continuity Reference: `S033_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Low view at dawn of a muddy trailhead where a forest path meets a red-clay road, wooden survey stakes leaning at its edge, low mist, no people.
Save as: `S034_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S034_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the voice-over beats, the last 4s are spare footage):
I2V from `S034_Ref.png`. 0–4s: a time-lapse in which dozens of boot prints of different sizes appear across the mud, one group after another, all leading into the trees, while the camera pushes slowly forward. 4–8s (spare 4s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 4s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): A steady rhythm of footsteps building; wind, distant birds, a low pad. From 4s to 8s the music and ambience sustain and ease down.
Cut→S035: Hard cut to a bone in the leaf-litter.

**S035 — Bones that were not his | 3:20–3:26 (6s slot → generate 8s in Flow)**
VO sync: (3:20) "சிலருக்கு எலும்புக் கூடு கிடைச்சது" · (3:21) "ஆனா" · (3:22) "DNA டெஸ்ட் பண்ணும்போது" · (3:24) "இது Fawcett-உடையது இல்ல" · (3:25) "சிலர் திரும்பவே இல்ல"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: none (unique location, described in the prompt: Leaf-litter under a giant Brazil-nut tree, round nut pods on the ground, deep forest) · Scene Continuity Reference: `S034_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Macro of a single old bleached long bone half-buried in mossy leaf-litter beside a rotted scrap of khaki cloth and a few round Brazil-nut pods, the huge buttress of the tree behind, a shaft of amber light across it, ferns blurred; respectful and non-graphic.
Save as: `S035_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S035_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the voice-over beats, the last 2s are spare footage):
I2V from `S035_Ref.png`. 0–2s: the camera pushes in slowly on the bone; 2–4s: the amber shaft of light drifts off the bone and the scene cools; 4–6s: the camera tilts up past the moss to an old pith helmet hanging on a broken branch, swaying in the mist. 6–8s (spare 2s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 6s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): A dissonant low string cluster; a droplet plink, a beetle's rustle; a wood creak from the helmet at 5s. From 6s to 8s the music and ambience sustain and ease down.
Cut→S036: Hard cut to a clearing of crosses.

**S036 — Thousands of lives lost | 3:26–3:30 (4s slot → generate 8s in Flow)**
VO sync: (3:26) "இந்த தேடுதலே" · (3:27) "பல ஆயிரம் உயிர்களை" · (3:29) "இன்னைக்கு வரைக்கும்"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: none (unique location, described in the prompt: A small forest clearing at dusk with a row of weathered wooden crosses overgrown with vines) · Scene Continuity Reference: `S035_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Low view in a small forest clearing at dusk of a row of weathered wooden crosses overgrown with vines and moss, a shaft of last light between the trunks, mist, no people.
Save as: `S036_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S036_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the voice-over beats, the last 4s are spare footage):
I2V from `S036_Ref.png`. 0–2s: the camera glides slowly along the row of crosses; 2–4s: the last light fades and mist drifts through. 4–8s (spare 4s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 4s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): The music drops to a single bowed note; wind, a wood creak, an insect hush. From 4s to 8s the music and ambience sustain and ease down.
Cut→S037: Cross-dissolve into a misty ridge.

**S037 — Nobody knows what became of him | 3:30–3:36 (6s slot → generate 8s in Flow)**
VO sync: (3:30) "பெர்சி ஃபாசெட்டுக்கு" · (3:31) "என்ன ஆச்சுன்னு" · (3:32) "யாருக்குமே தெரியாது" · (3:33) "இவரோட City of Z" · (3:35) "இருக்கா இல்லையா"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: none (unique location, described in the prompt: A forested ridge with straight earthwork ditches and terraces in mist at dawn) · Scene Continuity Reference: `S036_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide low view at dawn of a misty forested ridge where perfectly straight earthen ditches and terraced platforms show through the trees, moss-covered stone steps half-hidden beneath roots, warm amber shafts of light; it is unclear whether these are ruins or natural.
Save as: `S037_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S037_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the voice-over beats, the last 2s are spare footage):
I2V from `S037_Ref.png`. 0–3s: the camera glides slowly forward along the ridge trail; 3–5s: the straight ditches and stone steps become clearer through the mist; 5–6s: the mist swirls back in and partly hides them. 6–8s (spare 2s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 6s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): A hopeful yet uneasy theme on solo horn and low strings; wind, distant jungle calls; a tonal sting at 4s as the steps appear. From 6s to 8s the music and ambience sustain and ease down.
Cut→S038: Hard cut to a mist-filled waterfall gorge.

**S038 — The forest keeps its secrets | 3:36–3:44 (8s slot → generate 10s in Flow)**
VO sync: (3:36) "அப்படிங்கறதே" · (3:37) "ஒரு பெரிய மர்மமா இருக்கு" · (3:38) "ஆனா" · (3:39) "ஒன்னு மட்டும் நிச்சயம்" · (3:40) "அமேசான் காடு" · (3:41) "தன் ரகசியத்தை காப்பாத்துறதுல" · (3:42) "கில்லாடி" · (3:43) "இப்ப மனிசங்க மட்டும் இல்ல"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: none (unique location, described in the prompt: A hidden multi-tiered waterfall in a mossy forest gorge with rolling mist) · Scene Continuity Reference: `S037_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide view of a hidden multi-tiered waterfall dropping into a mossy forest gorge, thick mist rolling off the falls and swallowing the far side, giant ferns and roots, a soft green light.
Save as: `S038_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S038_Ref.png`
Video Prompt (Google Flow, generate 10s: the first 8s carry the voice-over beats, the last 2s are spare footage):
I2V from `S038_Ref.png`. 0–3s: the mist thickens and swallows the far side of the gorge; 3–6s: the camera rises up along the falls; 6–8s: it breaks into light above the gorge rim and tilts to show a brown river winding across the forest beyond. 8–10s (spare 2s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 8s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): The horn theme fades; a waterfall roar and soft wind; a whoosh as the camera rises at 3s; a rising note at 6s. From 8s to 10s the music and ambience sustain and ease down.
Cut→S039: Hard cut to a skimming shot over the river.

---

### Segment 6 — The River's Hidden Dangers (Scenes 39–47) | 3:44–4:40

**S039 — The river itself is a living danger | 3:44–3:50 (6s slot → generate 8s in Flow)**
VO sync: (3:44) "அமேசான் நதியே" · (3:45) "ஒரு உயிருள்ள ஆபத்து" · (3:47) "இதில ஒரு மீன் இருக்கு" · (3:48) "பேரு கேண்டிரு"
Step 3 Ingredients: Vehicle/Subject Reference Image: `Candiru_Portrait.png`, `Candiru_6Angle.png` · Environment Reference Image: none (unique location, described in the prompt: The wide muddy Amazon main channel with sandbanks, then underwater shallows) · Scene Continuity Reference: `S038_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Low tracking view skimming just above the wide brown main channel of the Amazon toward a misty bend with sandbanks, roots and branches overhanging one bank, bright overcast light, ripples on the water.
Save as: `S039_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S039_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the voice-over beats, the last 2s are spare footage):
I2V from `S039_Ref.png`. 0–2s: the camera skims forward over the water surface; 2–3s: it dips smoothly into the tea-brown water, particles swirling; 3–6s: underwater, a tiny translucent candiru hangs in the current beside a sand grain and a leaf edge for scale. 6–8s (spare 2s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 6s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): The music turns wary with a low drone; water rush, then a muffled underwater ambience from 3s; soft bubble pops and a faint high sting on the fish. From 6s to 8s the music and ambience sustain and ease down.
Cut→S040: Match cut on the small fish, into a village dock.

**S040 — Locals stay careful in the water | 3:50–3:56 (6s slot → generate 8s in Flow)**
VO sync: (3:50) "இது பாக்கரதுக்கு ஒரு இஞ்சு கூட இருக்காது" · (3:52) "ஆனா லோக்கல் மக்கள்" · (3:53) "இதுக்கு பயந்தே" · (3:54) "நதியில் ஈரமா நிக்கும்போது" · (3:55) "ஜாக்கிரதையா இருப்பாங்க"
Step 3 Ingredients: Vehicle/Subject Reference Image: `Tapper_Portrait.png`, `Tapper_6Angle.png`, `Candiru_Portrait.png`, `Candiru_6Angle.png` · Environment Reference Image: none (unique location, described in the prompt: A riverside stilt-house village with wooden canoes and a floating dock, overcast morning) · Scene Continuity Reference: `S039_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Medium shot from a floating wooden dock at a riverside stilt-house village in bright overcast morning light: a local man in a straw hat standing knee-deep at the dock's edge, face visible with a wary, careful expression as he looks down at the water, canoes tied along the dock, stilt houses behind, a faint thin needle-like shadow in the water beneath.
Save as: `S040_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S040_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the voice-over beats, the last 2s are spare footage):
I2V from `S040_Ref.png`. 0–2s: the man glances at the water; 2–4s: he slowly and carefully climbs out onto the dock; 4–6s: the camera dips below the dock to show the thin candiru shadow following the ripple line. Nothing shown on a body. 6–8s (spare 2s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 6s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): Suspense pulse over low strings; water lapping, canoes knocking gently against the dock, careful footsteps on planks; a muffled underwater tone from 4s. From 6s to 8s the music and ambience sustain and ease down.
Cut→S041: Hard cut to a black-water creek mouth.

**S041 — It slips into an opening, and stays | 3:56–4:02 (6s slot → generate 8s in Flow)**
VO sync: (3:56) "ஏன்னா இது உடம்பல்" · (3:58) "திறந்த இடங்கள்ல" · (3:58) "நுழைஞ்சு உக்காந்து இருக்கும்" · (3:59) "ஒரு தடவை நுழைஞ்சா" · (4:00) "அதை வெளியே எடுக்கவே" · (4:01) "ஆப்ரேஷன் பண்ணணும்"
Step 3 Ingredients: Vehicle/Subject Reference Image: `Candiru_Portrait.png`, `Candiru_6Angle.png` · Environment Reference Image: none (unique location, described in the prompt: Underwater in a black-water creek mouth among tangled submerged roots) · Scene Continuity Reference: `S040_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Underwater macro in a black-water creek mouth among tangled submerged roots, sunlit particles drifting, a tiny translucent candiru near a narrow crack in a root.
Save as: `S041_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S041_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the voice-over beats, the last 2s are spare footage):
I2V from `S041_Ref.png`. 0–3s: the candiru follows the current toward the crack; 3–5s: it slips inside and vanishes; 5–6s: the camera holds on the dark crack as particles swirl. 6–8s (spare 2s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 6s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): A low tense drone; muffled underwater ambience, tiny bubble pops; a soft sting at 4s. From 6s to 8s the music and ambience sustain and ease down.
Cut→S042: Hard cut to a dark flooded forest.

**S042 — The movie myth of the piranha | 4:02–4:08 (6s slot → generate 8s in Flow)**
VO sync: (4:02) "பிறகு" · (4:03) "பிரான்ஹா மீன்" · (4:04) "சினிமாவுல காமிக்குற மாதிரி" · (4:05) "மனிசனை நிமிசத்துல" · (4:06) "தின்னுடுவாங்கன்னு" · (4:07) "காமிச்சிருக்காங்க"
Step 3 Ingredients: Vehicle/Subject Reference Image: `Piranha_Portrait.png`, `Piranha_6Angle.png` · Environment Reference Image: none (unique location, described in the prompt: Flooded forest (igapó) underwater: drowned trunks in dark green water) · Scene Continuity Reference: `S041_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Low-angle underwater shot in a flooded forest, a dark shoal of about fifteen red-bellied piranhas among drowned tree trunks and hanging roots in dark green-black water below a bright silver surface, dramatic thriller lighting.
Save as: `S042_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S042_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the voice-over beats, the last 2s are spare footage):
I2V from `S042_Ref.png`. 0–1s: the camera drifts through dark drowned trunks; at 1s the shoal swings into view and turns toward the lens in a dramatic thriller-style approach; 2–5s: the shoal swirls and charges closer, teeth glinting, exactly like a movie; 5–6s: the shoal turns sharply away. 6–8s (spare 2s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 6s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): A horror-movie style rising string tremolo and pounding bass from 1s; muffled water rush, fin flicks; a sharp sting at 2s. From 6s to 8s the music and ambience sustain and ease down.
Cut→S043: Hard cut to a calm lone fish in a clear lake.

**S043 — Alone, calm; together, when water shrinks, dangerous | 4:08–4:16 (8s slot → generate 10s in Flow)**
VO sync: (4:08) "உண்மையில தனியா இருக்கும்போது" · (4:09) "இது பெரும்பாலும்" · (4:10) "அபாயகரம் இல்ல" · (4:11) "ஆனா நீர் குறைஞ்சு" · (4:12) "உணவு கிடைக்காம" · (4:13) "ஒரு பெரிய கூட்டமா இருக்கும்போது" · (4:15) "ஆபத்து நிஜம் தான்"
Step 3 Ingredients: Vehicle/Subject Reference Image: `Piranha_Portrait.png`, `Piranha_6Angle.png` · Environment Reference Image: none (unique location, described in the prompt: Floodplain lake in the dry season: clear water turning into a shrinking mud pool) · Scene Continuity Reference: `S042_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Underwater view in a clear floodplain lake of a lone piranha cruising peacefully beside water-lily stems and a sunken branch, soft shafts of light and drifting particles, calm mood.
Save as: `S043_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S043_Ref.png`
Video Prompt (Google Flow, generate 10s: the first 8s carry the voice-over beats, the last 2s are spare footage):
I2V from `S043_Ref.png`. 0–3s: the camera tracks alongside the lone piranha as it glides calmly and nibbles a drifting fruit; 3–4s: the camera rises through the surface; 4–8s: above water a time-lapse shows the lake shrinking to a small pool with cracked mud spreading while dozens of piranhas crowd the pool and churn the surface harder and harder. 8–10s (spare 2s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 8s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): Gentle low pizzicato; soft underwater tone; from 3s a building tension with rising drums, splashes and fin slaps; dry wind at 7s. From 8s to 10s the music and ambience sustain and ease down.
Cut→S044: Whip pan to a marsh lagoon.

**S044 — The heaviest snake, hiding in the water | 4:16–4:22 (6s slot → generate 8s in Flow)**
VO sync: (4:16) "இன்னும் ஒன்னு" · (4:17) "அனகோண்டா" · (4:17) "இது உலகத்திலேயே" · (4:18) "பாரம் அதிகமான பாம்பு" · (4:20) "இது நீருக்குள்ள ஒளிஞ்சிருந்து" · (4:21) "தண்ணீர் குடிக்க வர மிருகங்களை வேட்டையாடும்"
Step 3 Ingredients: Vehicle/Subject Reference Image: `Anaconda_Portrait.png`, `Anaconda_6Angle.png` · Environment Reference Image: none (unique location, described in the prompt: Marsh lagoon covered with water hyacinth and lily pads at midday) · Scene Continuity Reference: `S043_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Water-level view in a marsh lagoon covered with floating water hyacinth and lily pads at midday, the still surface at the bottom edge of the frame and the eyes and snout of a giant green anaconda rising just above it among the plants.
Save as: `S044_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S044_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the voice-over beats, the last 2s are spare footage):
I2V from `S044_Ref.png`. 0–1s: the surface is still, then the snout rises slightly; 1–4s: the camera pulls slowly back and lowers through the surface to reveal the huge olive body coiled among the plant roots underwater; 4–6s: it lies almost motionless, a bird's shadow passing over the surface. 6–8s (spare 2s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 6s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): A very low slow drone with a heartbeat; water lapping, an insect hum; a hiss at 1s; a muffled underwater tone from 3s. From 6s to 8s the music and ambience sustain and ease down.
Cut→S045: Hard cut to a drinking spot on a riverbank.

**S045 — Animals come to drink; people are rarely attacked | 4:22–4:26 (4s slot → generate 8s in Flow)**
VO sync: (4:23) "மனிசங்களை தாக்கினது" · (4:25) "அபூர்வம் தான்" · (4:25) "ஆனா"
Step 3 Ingredients: Vehicle/Subject Reference Image: `Anaconda_Portrait.png`, `Anaconda_6Angle.png` · Environment Reference Image: none (unique location, described in the prompt: A sandy riverbank drinking spot at dusk with a white egret) · Scene Continuity Reference: `S044_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
High three-quarter angle at dusk above a sandy riverbank drinking spot, a white egret standing at the water's edge lowering its beak to drink, and beneath the murky surface a long dark olive coil faintly visible in the shallows.
Save as: `S045_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S045_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the voice-over beats, the last 4s are spare footage):
I2V from `S045_Ref.png`. 0–2s: the egret dips its beak to drink as a slow ripple spreads from below; 2–4s: the egret stiffens and leaps into flight while the ripple settles around the coil. Nothing violent is shown. 4–8s (spare 4s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 4s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): The low drone holds, then a sharp string stab at 2s; a soft drink, a sudden wing flap, a small splash. From 4s to 8s the music and ambience sustain and ease down.
Cut→S046: Hard cut to a garden.

**S046 — The recorded 1997 incident | 4:26–4:32 (6s slot → generate 8s in Flow)**
VO sync: (4:26) "1997ம் வருசம்" · (4:28) "பிரேசில்ல ஒரு தோட்டக்காரர் மேல்" · (4:30) "அனகோண்டா தாக்கினது" · (4:31) "பதிவு பண்ணப்பட்ட உண்மையான சம்பவம்"
Step 3 Ingredients: Vehicle/Subject Reference Image: `Anaconda_Portrait.png`, `Anaconda_6Angle.png` · Environment Reference Image: none (unique location, described in the prompt: A small riverside vegetable garden (chácara) with a wooden fence and banana plants at midday) · Scene Continuity Reference: `S045_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide shot at midday of a small riverside vegetable garden with a wooden fence and banana plants, a hoe leaning against a stake and a woven basket on the soil, the brown river just beyond a strip of reeds; among the reeds at the water's edge a dark olive coil is barely visible.
Save as: `S046_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S046_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the voice-over beats, the last 2s are spare footage):
I2V from `S046_Ref.png`. 0–2s: the camera holds still as a slow ripple moves in the reeds; 2–4s: it pushes slowly toward the hoe and basket; 4–6s: the ripple crosses toward the garden and birds flush from the reeds. Nothing violent shown. 6–8s (spare 2s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 6s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): Held low tone; reed rustle, water drips; a tension sting at 2s; distant birds flushing at 5s. From 6s to 8s the music and ambience sustain and ease down.
Cut→S047: Cut to a riverbank cliff.

**S047 — Water, soil, tree, wind: nowhere is safe | 4:32–4:40 (8s slot → generate 10s in Flow)**
VO sync: (4:33) "இந்த காடு" · (4:33) "உங்களை எப்படி எல்லாம் எச்சரிக்கை பண்ணுதுன்னு பாருங்க" · (4:36) "நீர்" · (4:36) "மண்" · (4:37) "மரம்" · (4:37) "காத்து" · (4:38) "எதுவுமே பாதுகாப்பு இல்ல" · (4:39) "இப்ப ஒரு உண்மையான சம்பவம் சொல்றேன்"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: none (unique location, described in the prompt: Red-soil riverbank cliff at the water's edge with a giant tree and an approaching storm) · Scene Continuity Reference: `S046_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Low view at the base of a red-soil riverbank cliff at the water's edge, the brown river surface at the bottom of the frame, exposed roots and a giant tree rising above, dark storm clouds building overhead, thin mist.
Save as: `S047_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S047_Ref.png`
Video Prompt (Google Flow, generate 10s: the first 8s carry the voice-over beats, the last 2s are spare footage):
I2V from `S047_Ref.png`. 0–4s: the camera holds at the water surface as ripples pass and the water darkens; 4–5s: it tilts up over the red muddy bank; 5–6s: it climbs the trunk; 6–7s: it reaches the canopy, which sways hard in a gust; 7–8s: the wind drops and everything goes still. 8–10s (spare 2s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 8s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): A wary theme; water lapping, a wet mud squelch, a wood creak, a wind gust rising; a sudden hush at 7s. From 8s to 10s the music and ambience sustain and ease down.
Cut→S048: Cross-dissolve to a misty road.

---

### Segment 7 — The Rubber Tapper's Voice (Scenes 48–52) | 4:40–5:10

**S048 — Now a true story, about people | 4:40–4:44 (4s slot → generate 8s in Flow)**
VO sync: (4:41) "இது காட்டுல இருக்குற மிருகங்களைப் பற்றி இல்ல" · (4:43) "மனிதர்களைப் பற்றி"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: none (unique location, described in the prompt: A quiet dirt road at the edge of the forest at dawn with mist over red earth) · Scene Continuity Reference: `S047_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Quiet dirt road at the edge of the forest at dawn, mist lying low over red earth, a line of rubber trees just visible at the roadside, first gold light, no people or vehicles.
Save as: `S048_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S048_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the voice-over beats, the last 4s are spare footage):
I2V from `S048_Ref.png`. 0–2s: the camera glides forward along the road as mist swirls; 2–4s: a shaft of gold light sweeps across the road and the camera slows. 4–8s (spare 4s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 4s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): A warm guitar begins softly under the wind; dawn birds. From 4s to 8s the music and ambience sustain and ease down.
Cut→S049: Hard cut to the rubber trail.

**S049 — Chico Mendes, a rubber tapper | 4:44–4:50 (6s slot → generate 8s in Flow)**
VO sync: (4:44) "சிக்கோ மெண்டஸ்" · (4:45) "அப்படின்னு ஒரு ஆள்" · (4:46) "இவர் பிரேசில்ல ரப்பர் மரத்துல இருந்து" · (4:49) "பால் எடுக்குற தொழிலாளி"
Step 3 Ingredients: Vehicle/Subject Reference Image: `Tapper_Portrait.png`, `Tapper_6Angle.png` · Environment Reference Image: none (unique location, described in the prompt: Rubber-tree estate trail at dawn (seringal), mist and tin cups) · Scene Continuity Reference: `S048_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide shot at dawn on a misty rubber-tree trail, the rubber tapper in a straw hat walking toward the camera between trunks marked with diagonal cut scars, his face clearly visible and calm, the headlamp on his hat glowing faintly, gold rim light through the mist, tin cups on the trees.
Save as: `S049_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S049_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the voice-over beats, the last 2s are spare footage):
I2V from `S049_Ref.png`. 0–2s: he steps into a shaft of gold light and the camera settles on his face; 2–6s: the camera tracks backwards ahead of him as he walks and touches a rubber tree. 6–8s (spare 2s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 6s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): A warm humble guitar and flute theme; boots on mud, dawn birds; a soft chime as he enters the light at 1s. From 6s to 8s the music and ambience sustain and ease down.
Cut→S050: Hard cut to a slope grove.

**S050 — He grew up in the forest and grieved its loss | 4:50–4:56 (6s slot → generate 8s in Flow)**
VO sync: (4:50) "இவர் வளர்ந்ததே அமேசான் காட்டுக்குள்ள தான்" · (4:52) "இவருக்கு காடு அழிக்கப்பட்டதை பாத்தா" · (4:54) "ரொம்ப வருத்தம்"
Step 3 Ingredients: Vehicle/Subject Reference Image: `Tapper_Portrait.png`, `Tapper_6Angle.png` · Environment Reference Image: none (unique location, described in the prompt: A slope grove of rubber trees overlooking a smoking clear-cut valley) · Scene Continuity Reference: `S049_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Macro of a curved tapping knife making a fresh diagonal cut into a rubber tree's bark on a hillside grove, a thin line of white latex beading along the cut, the tapper's latex-stained sleeve and calm face softly visible, and far behind in soft focus a valley slope with a column of smoke rising from a cleared hillside.
Save as: `S050_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S050_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the voice-over beats, the last 2s are spare footage):
I2V from `S050_Ref.png`. 0–2s: the knife draws a smooth shallow cut and milky latex wells up and runs down into a tin cup; 2–4s: the camera rises from the cup along his arm to his face; 4–6s: he turns to look toward the smoke on the far slope, his brow furrowing with sorrow. 6–8s (spare 2s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 6s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): The theme stays warm; knife scrape and latex drip; from 4s a low cello darkens the music and a distant chainsaw whine rises. From 6s to 8s the music and ambience sustain and ease down.
Cut→S051: Cut to a village square.

**S051 — A voice for thousands of families | 4:56–5:04 (8s slot → generate 10s in Flow)**
VO sync: (4:56) "அதை நம்பி வாழ்ற" · (4:57) "தன் மாதிரி" · (4:58) "ஆயிரக்கணக்கான குடும்பங்களுக்கும்" · (5:00) "வாழ்வாதாரம் போயிடும்" · (5:01) "இவர் அரசாங்கத்துக்கு எதிரா" · (5:02) "பெரிய நில உரிமையாளருக்கு எதிரா"
Step 3 Ingredients: Vehicle/Subject Reference Image: `Tapper_Portrait.png`, `Tapper_6Angle.png` · Environment Reference Image: none (unique location, described in the prompt: Dusty village square before a small wooden union hall with a tin roof, golden hour) · Scene Continuity Reference: `S050_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide low view at golden hour of a dusty village square in front of a small wooden hall with a tin roof: the tapper stands in the foreground in profile, and dozens of tappers and families in straw hats stand in the square with serious weathered faces, warm light, a few chickens and a bicycle at the edges.
Save as: `S051_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S051_Ref.png`
Video Prompt (Google Flow, generate 10s: the first 8s carry the voice-over beats, the last 2s are spare footage):
I2V from `S051_Ref.png`. 0–4s: the camera drifts slowly along the crowd of tappers and their families as dust drifts in the light; 4–5s: the tapper turns to face the camera, resolute; 5–8s: he raises his straw hat high in the air and the others behind him raise theirs one by one. 8–10s (spare 2s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 8s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): The theme darkens for four seconds, then swells into determined strings and a warm synth pad at 5s; fabric rustle, boots shuffling in dust, a rooster far off. From 8s to 10s the music and ambience sustain and ease down.
Cut→S052: Cross-dissolve to a room interior.

**S052 — World attention, and an award | 5:04–5:10 (6s slot → generate 8s in Flow)**
VO sync: (5:04) "குரல் கொடுத்தார்" · (5:05) "சர்வதேச அளவில் கவனம் பெற்றார்" · (5:07) "ஐக்கிய நாடுகள் சபைக்கூட" · (5:08) "இவருக்கு விருது கொடுத்துச்சு" · (5:09) "ஆனா"
Step 3 Ingredients: Vehicle/Subject Reference Image: `Tapper_Portrait.png`, `Tapper_6Angle.png` · Environment Reference Image: none (unique location, described in the prompt: Rustic wooden room interior: table by a shuttered window, late afternoon light) · Scene Continuity Reference: `S051_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Macro of a modest brass medal on a blue ribbon lying on a rough wooden table beside a straw hat and a stack of folded papers with no legible writing, warm late-afternoon light through a window with wooden shutters, a simple room blurred behind, no text on the medal.
Save as: `S052_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S052_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the voice-over beats, the last 2s are spare footage):
I2V from `S052_Ref.png`. 0–2s: warm golden light glints across the brass as the camera pushes slowly in; 2–4s: a rack focus moves from the medal to the straw hat; 4–6s: clouds pass and the warm light fades into cold blue shadow through the shutters while a moth circles near the window. 6–8s (spare 2s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 6s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): A quiet dignified piano; light metal shimmer, ribbon rustle; at 4s the piano stops and a low drone enters; crickets grow. From 6s to 8s the music and ambience sustain and ease down.
Cut→S053: Hard cut to the dark back yard of a stilt house.

---

### Segment 8 — The Sacrifice & Legacy (Scenes 53–57) | 5:10–5:36

**S053 — December 22, 1988 | 5:10–5:16 (6s slot → generate 8s in Flow)**
VO sync: (5:10) "1988" · (5:11) "டிசம்பர் 22" · (5:12) "அவரோட சொந்த வீட்டுக்கு பின்னாடியே" · (5:14) "துப்பாக்கியால் சுட்டுக்கொல்லப்பட்டார்"
Step 3 Ingredients: Vehicle/Subject Reference Image: `Tapper_Portrait.png`, `Tapper_6Angle.png` · Environment Reference Image: none (unique location, described in the prompt: Back yard of a wooden stilt house at blue-hour dusk) · Scene Continuity Reference: `S052_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Locked-off wide shot of the back yard of a simple wooden stilt house at blue-hour dusk, a single window glowing, a straw hat resting on the porch rail, a towel hanging still, the dark treeline behind, held silence.
Save as: `S053_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S053_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the voice-over beats, the last 2s are spare footage):
I2V from `S053_Ref.png`. 0–3s: the camera holds still as crickets sound; at 3s a flock of birds bursts from the dark treeline and scatters and the straw hat trembles and slips from the rail, falling out of frame; 4–6s: silence, the towel swinging gently and the window light flickering once. Nothing violent is shown. 6–8s (spare 2s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 6s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): Sparse hushed piano; crickets; one distant sharp crack echoing at 3s, a burst of wings; then a long hush and a low tone. From 6s to 8s the music and ambience sustain and ease down.
Cut→S054: Hard cut to a police post at night.

**S054 — A landowner's family arrested | 5:16–5:20 (4s slot → generate 8s in Flow)**
VO sync: (5:16) "இதுக்கு காரணமா" · (5:17) "நில உரிமையாளர் குடும்பம்" · (5:18) "ஒன்னு கைது ஆனாங்க" · (5:19) "இவரோட மரணம்"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: none (unique location, described in the prompt: A small-town police post at night with a single bare bulb and an old jeep) · Scene Continuity Reference: `S053_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide view at night of a small-town police post: a whitewashed low building with a single bare bulb over its door, an old jeep parked in the dirt, moths swirling in the bulb's light, no people, deep shadows.
Save as: `S054_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S054_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the voice-over beats, the last 4s are spare footage):
I2V from `S054_Ref.png`. 0–2s: the camera pushes slowly toward the lit door; 2–4s: the bulb flickers and steadies as a distant engine dies away. 4–8s (spare 4s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 4s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): A sparse low tone, night insects, a distant engine fading; a door latch click at 3s. From 4s to 8s the music and ambience sustain and ease down.
Cut→S055: Cross-dissolve to a memorial post.

**S055 — His death made the world speak | 5:20–5:26 (6s slot → generate 8s in Flow)**
VO sync: (5:20) "உலக முழுக்க" · (5:21) "அமேசான் காட்டு அழிப்புப்பத்தி" · (5:23) "முதன்முறையா" · (5:23) "பெரிய அளவுல பேச வச்சிச்சு" · (5:25) "இன்னைக்கு அமேசான் காட்டுல இருக்குற"
Step 3 Ingredients: Vehicle/Subject Reference Image: `Tapper_Portrait.png`, `Tapper_6Angle.png` · Environment Reference Image: none (unique location, described in the prompt: A simple wooden memorial post at the forest edge under a giant tree, night turning to sunrise) · Scene Continuity Reference: `S054_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Low-angle close shot of a straw hat hanging on a simple wooden post at the forest edge under a giant tree at night, a small candle glowing in a jar at the post's foot, a moth circling above, the dark treeline behind.
Save as: `S055_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S055_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the voice-over beats, the last 2s are spare footage):
I2V from `S055_Ref.png`. 0–2s: a slow push-in on the hat and the candle; 2–4s: the camera lifts as a time-lapse turns the night to dawn and the sky glows gold above the forest; 4–6s: it rises over the treeline to reveal an unbroken green canopy in soft sunrise light. 6–8s (spare 2s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 6s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): A solo cello with a mournful line; moth wing flutter, crickets that turn to dawn birds at 3s; the cello lifts into a warm hopeful chord at 5s. From 6s to 8s the music and ambience sustain and ease down.
Cut→S056: Continuous rise, the camera flying on over the canopy.

**S056 — Protected areas born of his sacrifice | 5:26–5:32 (6s slot → generate 8s in Flow)**
VO sync: (5:27) "பாதுகாக்கப்பட்ட பகுதிகள் பல" · (5:28) "இன்னைக்கு அமேசான் காட்டுல இருக்குற" · (5:29) "பல பகுதிகள்" · (5:30) "இவரோட தியாகத்தால தான் உண்டாச்சு"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: none (unique location, described in the prompt: A protected reserve's horseshoe oxbow lake at sunrise with a small canoe landing, aerial) · Scene Continuity Reference: `S055_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
High aerial view at sunrise of an intact protected rainforest reserve, a large horseshoe oxbow lake mirroring the golden sky, mist lifting, a small wooden canoe landing on its shore with a narrow trail leading into the trees.
Save as: `S056_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S056_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the voice-over beats, the last 2s are spare footage):
I2V from `S056_Ref.png`. 0–3s: the camera glides forward over the glowing canopy and the mirror-like lake, birds crossing; 3–6s: it tilts down and descends toward the landing and the trail. 6–8s (spare 2s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 6s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): The cello theme blooms into a warm orchestral swell; birds waking up, wind over the trees. From 6s to 8s the music and ambience sustain and ease down.
Cut→S057: Hard cut to a lone rubber tree at sunrise.

**S057 — One man gave his life for the forest | 5:32–5:36 (4s slot → generate 8s in Flow)**
VO sync: (5:32) "ஒரு மனிசன்" · (5:33) "காட்டுக்காக தன் உயிரையே கொடுத்திருக்கான்" · (5:35) "இது கட்டுக்கதை இல்ல"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: none (unique location, described in the prompt: A huge lone rubber tree in a forest clearing at sunrise with a tin cup on its trunk) · Scene Continuity Reference: `S056_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Close view at sunrise of a huge lone rubber tree in a forest clearing, a tin cup on its trunk with white latex, gold sun flare through the leaves.
Save as: `S057_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S057_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the voice-over beats, the last 4s are spare footage):
I2V from `S057_Ref.png`. 0–2s: a drop of latex falls into the cup, making a ripple; 2–4s: the camera pushes slightly in as the sun flare glows. 4–8s (spare 4s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 4s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): A soft, warm piano resolves the theme; a latex drip; a gentle held chord. From 4s to 8s the music and ambience sustain and ease down.
Cut→S058: Hard cut to a cold blue dawn.

---

### Segment 9 — The Danger That Continues (Scenes 58–64) | 5:36–6:24

**S058 — The last part is the most important | 5:36–5:40 (4s slot → generate 8s in Flow)**
VO sync: (5:36) "சரித்திரம்" · (5:36) "நான் ஆரம்பத்தில சொன்னேன்னுல" · (5:37) "கடைசி பகுதி தான் மிக முக்கியம்னு"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: none (unique location, described in the prompt: A silent misty river valley at cold blue dawn seen from a high bank) · Scene Continuity Reference: `S057_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Cold blue dawn view of a silent misty river valley from a high bank, the water pale steel-grey, dark forest walls on both sides, low cloud, no people or vehicles.
Save as: `S058_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S058_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 4s carry the voice-over beats, the last 4s are spare footage):
I2V from `S058_Ref.png`. 0–2s: the camera holds as mist drifts over the water; 2–4s: it drifts slowly forward and the light warms very slightly. 4–8s (spare 4s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 4s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): The warm theme is replaced by a cool low tone; wind, a faint distant hum starting at 3s. From 4s to 8s the music and ambience sustain and ease down.
Cut→S059: Hard cut to a jungle airstrip.

**S059 — 2011: a drone flies over the Amazon | 5:40–5:46 (6s slot → generate 8s in Flow)**
VO sync: (5:40) "இதோ அது" · (5:40) "2011 வருசம்" · (5:42) "பிரேசில் அரசாங்கம்" · (5:43) "ஒரு ட்ரோன் விமானத்தை" · (5:44) "அமேசான் காட்டுக்குள்ள பறக்க விட்டாங்க"
Step 3 Ingredients: Vehicle/Subject Reference Image: `Drone_Portrait.png`, `Drone_6Angle.png` · Environment Reference Image: none (unique location, described in the prompt: A jungle airstrip clearing at cold blue dawn with a survey drone on a launch rail) · Scene Continuity Reference: `S058_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Cold blue dawn view of a short dirt airstrip carved into the forest, mist along its edges, a small white survey drone resting on a launch rail at the end of the strip, no people.
Save as: `S059_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S059_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the voice-over beats, the last 2s are spare footage):
I2V from `S059_Ref.png`. 0–2s: the light is cool and still over the strip; 2–4s: a faint propeller hum begins and the drone accelerates along the rail and lifts off; 4–6s: the camera tracks alongside it as it climbs above the trees and banks toward the deep forest. 6–8s (spare 2s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 6s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): A cool technological pulse and a low drone from 2s; propeller hum, wind rush. From 6s to 8s the music and ambience sustain and ease down.
Cut→S060: Match cut on the banking drone into its point of view.

**S060 — An uncontacted people found | 5:46–5:52 (6s slot → generate 8s in Flow)**
VO sync: (5:46) "அது கவாஹிவா" · (5:47) "அப்படின்னு ஒரு பழங்குடி மக்கள்" · (5:49) "இன்னும் வெளி உலகத்தோட" · (5:50) "எந்த தொடர்பும் இல்லாம" · (5:51) "வாழ்றத கண்டுபிடிச்சாங்க"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: none (unique location, described in the prompt: Drone point-of-view over a hillside village beside a small stream, morning mist) · Scene Continuity Reference: `S059_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Drone point-of-view aerial looking down at a hillside clearing beside a small stream with two round thatched huts, cleared garden rows and a thin thread of smoke, a few tiny distant figures moving between the huts, morning mist between the trees.
Save as: `S060_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S060_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the voice-over beats, the last 2s are spare footage):
I2V from `S060_Ref.png`. 0–2s: the camera glides forward over the canopy; 2–4s: it descends toward the huts as the tiny distant figures move about their day; 4–6s: the camera holds steady above the clearing. 6–8s (spare 2s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 6s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): The cool pulse continues under an awed string note; the drone hum in the distance; a hush at 5s. From 6s to 8s the music and ambience sustain and ease down.
Cut→S061: Hard cut to a rocky stream.

**S061 — They keep running from loggers and gold-seekers | 5:52–6:00 (8s slot → generate 10s in Flow)**
VO sync: (5:53) "இவங்க யாரோட கண்ணுக்கும் படாம" · (5:54) "ஒரு இடத்துல இருந்து" · (5:55) "இன்னொரு இடத்துக்கு" · (5:56) "ஓடிக்கிட்டே இருப்பாங்க" · (5:57) "ஏன்னா மரம் வெட்டுறவங்க" · (5:59) "சட்டவிரோதமா தங்கம் தேடுறவங்க"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: none (unique location, described in the prompt: A rocky stream bank in a shallow forest gorge: an abandoned camp) · Scene Continuity Reference: `S060_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Ground-level view beside a rocky forest stream in a shallow gorge: a small campfire still glowing on the gravel bank beside two hurriedly abandoned hammocks and a woven basket, wet stones, green light, no people.
Save as: `S061_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S061_Ref.png`
Video Prompt (Google Flow, generate 10s: the first 8s carry the voice-over beats, the last 2s are spare footage):
I2V from `S061_Ref.png`. 0–4s: the camera pushes in slowly toward the fire as a hammock rope still swings and the embers glow; 4–6s: the first distant sound of a chainsaw begins and grows; 6–8s: a distant metal clang of a digging tool joins in and the camera stops on the fire. 8–10s (spare 2s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 8s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): A low tremolo; crackling embers, stream trickle, hammock rope creak; from 4s a chainsaw whine growing, then distant metal clangs at 6s. From 8s to 10s the music and ambience sustain and ease down.
Cut→S062: Hard cut to a logging road at dusk.

**S062 — They keep coming, even in 2026 | 6:00–6:08 (8s slot → generate 10s in Flow)**
VO sync: (6:00) "இவங்க பின்னாடியே வந்துகிட்டே இருக்காங்க" · (6:02) "இன்னைக்கு 2026ல" · (6:03) "இந்த நொடிக்கூட" · (6:05) "இது மாதிரி பல" · (6:05) "பழங்குடி மக்கள்" · (6:07) "தொகுதிகள் அமேசான் காட்டுக்குள்ள"
Step 3 Ingredients: Vehicle/Subject Reference Image: `Bulldozer_Portrait.png`, `Bulldozer_6Angle.png` · Environment Reference Image: none (unique location, described in the prompt: Red-earth logging road and sawmill landing with towering stacks of felled logs, smoky dusk) · Scene Continuity Reference: `S061_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Low-angle tracking view at smoky orange dusk of the yellow bulldozer rolling along a red-earth logging road past towering stacks of huge felled logs at a sawmill landing, dust and smoke around its tracks, no operator visible.
Save as: `S062_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S062_Ref.png`
Video Prompt (Google Flow, generate 10s: the first 8s carry the voice-over beats, the last 2s are spare footage):
I2V from `S062_Ref.png`. 0–3s: the camera tracks alongside the bulldozer as it moves ahead, its blade throwing soil; 3–5s: the camera cranes up and over the machine; 5–8s: it rises high above the canopy to show many faint smoke threads spread across the forest, many hidden communities. 8–10s (spare 2s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 8s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): Heavy drums and a brass drone that soften into a quiet ambient wind at 5s; diesel roar and track clank fading as the camera lifts. From 8s to 10s the music and ambience sustain and ease down.
Cut→S063: Continuous aerial, gliding forward to a fire front.

**S063 — They do not know the modern world; destruction nears them | 6:08–6:16 (8s slot → generate 10s in Flow)**
VO sync: (6:08) "மறைஞ்சு வாழ்றாங்க" · (6:09) "இவங்களுக்கு மாடர்ன் வேர்ல்ட்" · (6:10) "அப்படின்னு ஒன்னு தெரியவே தெரியாது" · (6:12) "ஆனா காடு அழிக்கப்படுற வேகம்" · (6:14) "இவங்களோட உலகத்தை நோக்கியும்"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: none (unique location, described in the prompt: A burning hillside fire front at dusk seen from a high aerial, with a peaceful clearing beyond) · Scene Continuity Reference: `S062_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
High aerial view at dusk of a burning hillside fire front advancing across cleared land, a glowing orange line and smoke columns, and beyond it at the edge of unbroken forest a small peaceful clearing with a thatched roof and a thin smoke thread.
Save as: `S063_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S063_Ref.png`
Video Prompt (Google Flow, generate 10s: the first 8s carry the voice-over beats, the last 2s are spare footage):
I2V from `S063_Ref.png`. 0–3s: the camera hovers over the calm clearing at the far edge as its smoke rises straight up; 3–5s: the camera turns slowly toward the fire line; 5–8s: the fire line grows and creeps forward across the cleared slope toward the forest, the camera gliding toward it. 8–10s (spare 2s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 8s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): Quiet melancholy pad; wind; from 3s a menacing rise of drums and roaring fire; a low brass swell at 6s. From 8s to 10s the music and ambience sustain and ease down.
Cut→S064: Cross-dissolve into the lone man's face.

**S064 — How many more, alone and nameless? | 6:16–6:24 (8s slot → generate 10s in Flow)**
VO sync: (6:16) "நெருங்கிக்கிட்டு இருக்கு" · (6:16) "நினைச்சு பாருங்க" · (6:17) "Man of the Hole மாதிரி" · (6:18) "இன்னும் எத்தனை பேர்" · (6:20) "தன் கூட்டமே அழிஞ்சு" · (6:21) "தனியா பேரு கூட இல்லாம" · (6:22) "இந்த நிமிசம் காட்டுக்குள்ள இருக்காங்களோ"
Step 3 Ingredients: Vehicle/Subject Reference Image: `TanaruMan_Portrait.png`, `TanaruMan_6Angle.png` · Environment Reference Image: none (unique location, described in the prompt: A rocky outcrop at the forest edge overlooking a valley with a glowing horizon at dusk) · Scene Continuity Reference: `S063_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Medium shot of the lone man standing on a rocky outcrop at the forest edge at dusk in three-quarter profile, bow at his side, face clearly visible and lit by a far orange glow filling the valley beyond, his eyes fixed on the fire with grief and quiet defiance.
Save as: `S064_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S064_Ref.png`
Video Prompt (Google Flow, generate 10s: the first 8s carry the voice-over beats, the last 2s are spare footage):
I2V from `S064_Ref.png`. 0–3s: a slow push-in toward his face, the far glow pulsing in his eyes; 3–6s: the camera keeps pushing in as he lowers his head slightly; 6–8s: he lifts his eyes again toward the fire and the camera holds still. 8–10s (spare 2s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 8s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): A lone flute over a soft pad; distant fire rumble, crickets; the music dips to near silence at 6s. From 8s to 10s the music and ambience sustain and ease down.
Cut→S065: Slow cross-dissolve into a bright dawn.

---

### Segment 10 — Final Wide / Outro (Scenes 65–68) | 6:24–6:54

**S065 — More than trees and animals | 6:24–6:32 (8s slot → generate 10s in Flow)**
VO sync: (6:24) "அமேசான் காடு" · (6:25) "இது வெறும் மரங்களும்" · (6:26) "மிருகங்களும் நிறைந்த இடம் இல்ல" · (6:28) "இது மனித சரித்திரத்தோட" · (6:29) "துக்கத்தோட" · (6:30) "தியாகத்தோட" · (6:31) "இன்னும் தீராத மர்மத்தோட"
Step 3 Ingredients: Vehicle/Subject Reference Image: `Macaw_Portrait.png`, `Macaw_6Angle.png` · Environment Reference Image: none (unique location, described in the prompt: A maze of forested river islands and channels at misty sunrise) · Scene Continuity Reference: `S064_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide aerial view at misty sunrise over a maze of forested river islands and channels, a pair of scarlet macaws flying low across the treetops, thick mist between the crowns, soft golden light.
Save as: `S065_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S065_Ref.png`
Video Prompt (Google Flow, generate 10s: the first 8s carry the voice-over beats, the last 2s are spare footage):
I2V from `S065_Ref.png`. 0–2s: the camera glides forward as the scarlet macaws cross the frame; 2–4s: it continues over the channels; 4–5s: the mist thickens and dims the light; 5–6s: bright gold rays break through the mist; 6–8s: the mist parts to reveal a long dark unexplored channel winding into the forest. 8–10s (spare 2s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 8s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): The outro theme builds with warm strings and flute; wind over the canopy, macaw calls; a soft harp accent at 5s. From 8s to 10s the music and ambience sustain and ease down.
Cut→S066: Continuous, the camera rising above the islands.

**S066 — A book with many unread pages | 6:32–6:40 (8s slot → generate 10s in Flow)**
VO sync: (6:33) "ஒரு புத்தகம்" · (6:34) "இதுல ஒரு பக்கம் மட்டும் தான்" · (6:35) "நம்ம இன்னும் புரட்டி பாத்திருக்கோம்" · (6:37) "இன்னும் நிறைய பக்கங்கள்" · (6:38) "படிக்கப்படாம மறைஞ்சு இருக்கு" · (6:39) "உங்களுக்கு"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: none (unique location, described in the prompt: A vast flat-topped forested plateau above a sea of clouds at sunrise, wind waves on the canopy) · Scene Continuity Reference: `S065_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Vast aerial view at sunrise of a flat-topped forested plateau rising above a sea of clouds in the valleys, gold sun rising, and a gust of wind starting to ripple across the leaves in wave patterns.
Save as: `S066_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S066_Ref.png`
Video Prompt (Google Flow, generate 10s: the first 8s carry the voice-over beats, the last 2s are spare footage):
I2V from `S066_Ref.png`. 0–1s: the camera rises slowly; at 1s a single strong wave of wind sweeps across the canopy like a page turning; 2–4s: the leaves settle; 4–6s: a series of smaller waves ripple across the far forest, one after another; 6–8s: cloud rolls in over the canopy so the far parts are hidden. 8–10s (spare 2s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 8s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): The outro theme swells with warm strings, flute and a soft synth pad; a paper-like whoosh of wind at 1s; a dawn bird chorus. From 8s to 10s the music and ambience sustain and ease down.
Cut→S067: Cross-dissolve into sunset over a river sandbar.

**S067 — The invitation, dusk into night | 6:40–6:48 (8s slot → generate 10s in Flow)**
VO sync: (6:40) "இதுல எந்த பகுதி" · (6:41) "அதிகம் திகில் தந்துச்சுன்னு" · (6:42) "கமெண்ட்ல சொல்லுங்க" · (6:43) "இது மாதிரி இன்னும்" · (6:44) "பல உண்மை சம்பவங்களை" · (6:44) "பாக்கணும்னா" · (6:45) "சப்ஸ்கிரைப் பண்ணி" · (6:46) "பெல் ஐகானை அழுத்துங்க" · (6:47) "அடுத்து வீடியோவில் சந்திக்கலாம்"
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: none (unique location, described in the prompt: A quiet river sandbar beach at nightfall with driftwood and fireflies at the treeline) · Scene Continuity Reference: `S066_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Wide view of a quiet river sandbar beach at nightfall, a deep orange sky fading to violet reflected in the calm water, driftwood on the sand, the dark forest wall behind with the first fireflies appearing and the first stars overhead, no people.
Save as: `S067_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S067_Ref.png`
Video Prompt (Google Flow, generate 10s: the first 8s carry the voice-over beats, the last 2s are spare footage):
I2V from `S067_Ref.png`. 0–3s: the sunset fades to deep blue night; 3–6s: the camera settles low over the sand toward the water; 6–8s: fireflies rise one by one from the treeline and multiply. 8–10s (spare 2s): the same gentle camera motion continues and settles into a calm hold with no new action, so the clip can be trimmed back to the 8s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): The outro theme softens to a gentle piano; crickets, night frogs and soft water lapping grow; a soft twinkling chime accent as each firefly appears from 6s. From 8s to 10s the music and ambience sustain and ease down.
Cut→S068: Continuous, the camera tilting up to the stars.

**S068 — Until the next video | 6:48–6:54 (6s slot → generate 8s in Flow)**
VO sync: (6:49) "நன்றி நன்றி நன்றி" · (6:51–6:54) audio-file outro credit, no narration → BGM only
Step 3 Ingredients: Vehicle/Subject Reference Image: none · Environment Reference Image: none (unique location, described in the prompt: A forest clearing at night under the Milky Way with hundreds of fireflies) · Scene Continuity Reference: `S067_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition)
Step 3 — Reference Image Prompt (Google Flow):
Quiet forest clearing at night, a sky full of stars and the Milky Way above a black treeline, hundreds of fireflies glowing softly among the ferns, and one bright firefly in the foreground drifting upward.
Save as: `S068_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S068_Ref.png`
Video Prompt (Google Flow, generate 8s: the first 6s carry the voice-over beats, the last 2s are spare footage):
I2V from `S068_Ref.png`. 0–2s: the camera tilts up slowly toward the stars while the fireflies glow; 2–4s: the foreground firefly lifts higher and glows; 4–6s: the firefly fades among the other lights and the frame settles on the Milky Way, ending on a complete closing beat. 6–8s (spare 2s): the image slowly darkens toward black with a gentle final hold, so the clip can be trimmed back to the 6s slot or stretched to cover extra voice-over. No speech, narration, whispering or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): The outro theme resolves to a final held chord and fades to silence by the end; soft night crickets fading last. From 6s to 8s the music and ambience sustain and ease down.
Cut→END: Fade to black over the last second.

---

# PRODUCTION NOTES

- **Total required:** 68 reference images (`S001_Ref.png` … `S068_Ref.png`) and 68 videos, one video per image. Plus the Step 1 subject sheets: 9 portraits and 9 six-angle turnarounds (18 images). There are no environment-plate images, because every scene has its own location. Overall: 68 scene images + 18 subject-sheet images = 86 images, and 68 videos.
- **Runtime check:** the voice file is 6:54 = 414 s. The clips are cut on natural phrase boundaries in the transcript: 2 × 10 s + 15 × 8 s + 35 × 6 s + 16 × 4 s = 20 + 120 + 210 + 64 = 414 s. Because the clip lengths add up to exactly 6:54, no clip needs trimming or overlapping, and the video ends exactly when the voice file ends.
- **Voice-over slot plan (where each clip lands on the timeline):**

| Clip length | Number of clips | Total seconds | Scenes |
|---|---|---|---|
| 4 s | 16 | 64 s | S004, S006, S009, S012, S014, S018, S027, S029, S033, S034, S036, S045, S048, S054, S057, S058 |
| 6 s | 35 | 210 s | S002, S003, S005, S007, S010, S011, S013, S015, S016, S017, S020, S021, S022, S023, S026, S028, S031, S032, S035, S037, S039, S040, S041, S042, S044, S046, S049, S050, S052, S053, S055, S056, S059, S060, S068 |
| 8 s | 15 | 120 s | S019, S024, S025, S030, S038, S043, S047, S051, S061, S062, S063, S064, S065, S066, S067 |
| 10 s | 2 | 20 s | S001, S008 |

- **What to generate in Flow (8 s or 10 s only):** every video is generated at 8 s or 10 s, never 4 s or 6 s, so you always have spare footage to trim instead of running short against the voice-over. A 4 s or 6 s voice-over slot is generated at 8 s; an 8 s or 10 s slot is generated at 10 s. Each prompt puts the beats that match the narration in the first part of the clip (the slot), and the spare seconds at the end only continue the same gentle motion and hold, with no new action.

| Generate in Flow | Number of videos | Footage | Voice-over slots covered | Scenes |
|---|---|---|---|---|
| 8 s | 51 | 408 s | 4 s slots (16) and 6 s slots (35) | S002, S003, S004, S005, S006, S007, S009, S010, S011, S012, S013, S014, S015, S016, S017, S018, S020, S021, S022, S023, S026, S027, S028, S029, S031, S032, S033, S034, S035, S036, S037, S039, S040, S041, S042, S044, S045, S046, S048, S049, S050, S052, S053, S054, S055, S056, S057, S058, S059, S060, S068 |
| 10 s | 17 | 170 s | 8 s slots (15) and 10 s slots (2) | S001, S008, S019, S024, S025, S030, S038, S043, S047, S051, S061, S062, S063, S064, S065, S066, S067 |
| **Total** | **68** | **578 s** | voice-over timeline 414 s | spare footage: 164 s |

- **How to use the spare seconds:** drop each clip at its scene start time and cut it back to its slot length (the header of each scene shows the slot). If a voice-over line runs longer than expected, or a clip is weaker than its neighbour, extend that clip into its spare seconds (or slow it slightly) instead of regenerating. The scene start times never change, so the voice-over stays in sync.
- **Timeline rule:** put the voice file on the timeline at 0:00, then place the clips in scene order, each trimmed to its slot length. Each scene's start time is the sum of the lengths before it, and the header of each scene shows its exact start and end time. Every "VO sync" line and every in-clip second mark in the video prompts is relative to that timeline.
- **How the in-clip marks work:** in each video prompt, "0–3s" means seconds from the start of that clip; the actions are placed so they land on the spoken line at that moment (see each scene's VO sync line). The narration words are deliberately NOT written inside the Flow prompts, so the model has nothing to speak.
- **Sync tolerance:** Flow can't hit an exact second every time, so treat the in-clip marks as targets. If a beat lands 1 s off, trim or stretch that clip by a second in the edit rather than regenerating. A few spoken words straddle a cut (for example "சரித்திரம்" at 5:36), which is normal in an edit.
- **Audio file credits:** the voice file has an audio-tool credit at 0:00–0:07 and again at 6:51–6:54. S001 and S068 are written so those seconds are music only. If you cut the credits from the audio, every clip start moves earlier by 7 s.
- **Sound design:** keep the BGM about 10–12 dB under the voice wherever there is narration, and let it swell only in the gaps (S001, S025, S064 end, S068).
- **Image generation is Google Flow only.** Step 1 subject sheets are unchanged. Step 2 is a location plan: every scene has its own unique place, written into its Step 3 prompt. Video prompts use each scene's saved image as the starting frame.
- **Continuity chain:** every Step 3 prompt lists the previous scene's saved `SXXX_Ref.png` as its Scene Continuity Reference, plus the subject sheets in the shot. The continuity image is for character look and colour grade only; the location must be new every time. Generate the scenes in order.
- **Hard-rules reminder:** no on-screen text; the generated clips contain no voice of any kind; human faces are fully visible and must match the face rows on the Step 1 sheets (fictional faces, no real likenesses); no gore or visible violence. Tragic events (the massacre, the death of the lone man, the 1988 killing) are shown only through symbols, sound and grief on faces.
- **Fact-check before publishing:** the candiru "enters the body" claim is largely folk myth. The 1997 anaconda attack on a gardener isn't a well-documented case. Check the Kawahiva "2011 drone" detail. The transcript has some mis-hearings (for example "City of Jet"), so recheck spellings if any text is added.
- **Reminder:** the GLOBAL LOCK BLOCK must be appended in full to the end of every prompt (Step 1, every Step 3 and every Step 4) before submission.
