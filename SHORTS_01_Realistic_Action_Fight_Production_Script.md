# SHORTS 01 — NIGHT RUN & CONTAINER YARD: Two Realistic Action-Fight Shorts
### [TEMPLATE v4 — Google Flow only · 8 s clips · Step 1 characters → Step 2 fixed environment plates → Step 3 per-scene reference image → Step 4 per-scene video · global lock appended to every prompt · no on-screen text · BGM + diegetic SFX only]

| | Short 1 — NIGHT RUN | Short 2 — CONTAINER YARD |
|---|---|---|
| **Length** | 56 s (7 clips × 8 s) | 48 s (6 clips × 8 s) |
| **Fixed environment** | Rain-slick city rooftops at night | Shipping-container yard at dawn |
| **Story** | A courier races across rooftops with a sealed case and fights off two pursuers using only her body, her speed and the rooftop itself | The next morning she walks into a container yard to deliver the case and one last brawl decides who walks out with it |
| **Format** | Vertical 9:16 for Shorts (generate 16:9 if you prefer to crop) | Same |

Both are inside the "more than 30 s, under 1 min" window. Short 2 continues directly from the last frame of Short 1, so they can be posted as Part 1 and Part 2.

**Assumptions made for the blank input fields (change if needed):**
- **Style:** grounded, realistic cinematic action thriller, like a stunt-driven chase film: real weight, real physics, practical lighting, no superpowers, no CGI-looking effects.
- **Characters:** three invented fictional people and one prop. No real people, no look-alikes of celebrities or public figures, no brands, no logos, no readable text anywhere.
- **Fight style:** hand-to-hand martial arts and parkour only. Strikes are blocked, parried, glanced or land on padded or soft things; opponents stagger, roll and get up. **No blood, no gore, no weapons, no one is ever seriously hurt.** The danger is shown by speed, near-misses and environment.
- **Resolution honesty:** "8K" is written into the prompts as a look keyword (large-format cinema detail). Google Flow's actual export resolution depends on the model and plan, so upscale in the editor if you need higher.

---

## ⚠️ GLOBAL LOCK BLOCK — append this in full to the END of every single prompt below (Step 1, Step 2, every Step 3, every Step 4)

```
GLOBAL LOCK:
CONTINUITY — Keep Rhea, Dax, Wire and the Black Case (including faces, hair, skin tone, clothing, wear marks and the cyan light seam) in exact colour/design/proportion continuity from their saved reference sheets — no redesign, recolour, age drift or costume drift. Keep each short inside its fixed environment exactly as shown in its saved environment plates: same layout, same props in the same places, same weather and time of day. Between shots keep screen direction consistent (Rhea runs left-to-right on the rooftop unless a prompt says she turns).
STYLE — Photorealistic cinematic action thriller, shot on a large-format digital cinema camera with 35mm anamorphic lenses, 8K-level fine detail, natural film grain, 180-degree shutter motion blur, a rich but natural grade (teal shadows, warm sodium-lamp highlights, deep blacks, no crushed detail). Real material physics: wet concrete reflects light, cloth and hair follow motion with believable weight, steam diffuses, metal dents and rings, dust and rain spray behave naturally. Grounded stunt-performer movement with weight transfer, counter-balance, recovery and breath.
HARD RULES — No on-screen text, captions, logos, brand names, readable signs or watermarks anywhere. Human characters have clear, natural, fully visible faces (realistic skin texture, pores, eyes, expressions) that match their saved reference sheets exactly in every shot; these are invented fictional faces, not likenesses of any real person. Faces never morph, age or change between shots. Fighting is stylised martial-arts stunt choreography only: blocks, parries, dodges, throws, sweeps, glancing strikes and falls onto soft surfaces. No blood, no wounds, no gore, no weapons of any kind, no one lying injured, no one in real danger of death. Villains stumble, roll and stand again.
ZERO AI ARTIFACTS — No morphing, warping, melting, flicker, extra or duplicated limbs/fingers, merged bodies, swapped limbs between fighters, rubbery or boneless motion, floaty or weightless jumps, plastic skin, texture smearing, inconsistent shadows, distorted hands or anatomy, characters passing through each other or through walls, sudden costume or prop changes, text-like marks.
LIGHTING — Follow the time of day and light written in each prompt, with one consistent colour grade across both shorts; no sudden unintended light jumps inside a shot.
AUDIO — Generated audio is ONLY instrumental cinematic BGM (low pulsing synth, driving percussion, tense strings, deep brass hits) plus diegetic SFX (footsteps, rain, wind, clothing rustle, impacts on cloth and metal, breaths as non-vocal air, steam hiss, helicopter, distant city, gulls, crane creak). Absolutely no dialogue, no voice-over, no speech in any language, no shouting, no screaming, no grunting or yelling voices, no singing, no chanting. People never speak and their mouths stay closed or tight with effort. Any quoted or timing text in the prompt is a camera/timing cue, never spoken words.
CAMERA — One continuous, physically plausible camera move per clip (tracking, handheld push, low glide, crane rise); no whip-cuts inside a clip; each clip's opening camera motion matches the previous clip's closing motion vector. Keep the two fighters fully visible, readable and well separated from the background.
```

---

# STEP 1 — CHARACTER & PROP REFERENCE IMAGES (Google Flow — image generation ONLY)

> Every sheet: realistic photographic style (see GLOBAL LOCK), neutral grey studio background, soft key light from upper left. Each subject gets a **Portrait** prompt and a **6-Angle Turnaround** prompt. Attach BOTH files wherever that subject appears.

### 1A. Rhea Voss — the courier (hero)
**Portrait Image Prompt — Google Flow:**
Full-body standing portrait of Rhea, an invented fictional woman of 32, athletic and compact, facing the camera in a ready, relaxed stance, with a clearly visible, fully detailed face: determined hazel eyes, strong straight eyebrows, high cheekbones, a small healed scar on the chin, light freckles, a calm focused expression. Dark brown hair in a tight low ponytail with a few loose damp strands. Warm tan skin with realistic texture. Clothing: a charcoal fitted technical jacket with a zipped collar (no logos), black stretch trousers, grip-soled black trail boots, black fingerless gloves, a matte-black cross-body strap across her chest. Camera at eye level, neutral grey studio background, soft key light upper left, macro-level detail on the face, stitching, fabric weave and boot soles. An invented fictional person, not a likeness of anyone real. Locked reference design.
**Save as:** `Rhea_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Rhea_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT (face fully visible, identical to the portrait), REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM (boots and ground contact), neutral grey background, matched lighting/scale, neutral pose. Add a second row of five close-up face panels (focused, effort, surprised, determined, relieved) locking the face.
**Save as:** `Rhea_6Angle.png`
**Usage note:** Attach both files to every scene where Rhea appears: all scenes S1-01 to S2-06.

### 1B. Dax Corren — the heavy pursuer
**Portrait Image Prompt — Google Flow:**
Full-body standing portrait of Dax, an invented fictional man of 44, very tall and broad, facing the camera with a heavy, steady stance, with a clearly visible, fully detailed face: shaved head, thick reddish-brown stubble beard, a broad nose, small deep-set grey eyes, a slightly crooked jaw, heavy brow, a stern unreadable expression. Pale, weathered skin with realistic texture. Clothing: a dark grey zip-up work jacket, black heavy cargo trousers, thick black leather boots, black leather gloves. Neutral grey studio background, soft key light upper left, macro detail on face, fabric folds and boot leather. An invented fictional person. Locked reference design.
**Save as:** `Dax_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Dax_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM (boots and ground contact), neutral grey background, matched lighting/scale, neutral pose. Add a second row of five close-up face panels (stern, angry, winded, surprised, grudging respect) locking the face.
**Save as:** `Dax_6Angle.png`
**Usage note:** Attach both files to every scene where Dax appears: S1-01, S1-03 to S1-07 (and as a distant shape in S1-01), S2-02 to S2-06.

### 1C. Wire — the fast pursuer
**Portrait Image Prompt — Google Flow:**
Full-body standing portrait of Wire, an invented fictional man of 28, lean and agile, facing the camera in a loose, springy stance, with a clearly visible, fully detailed face: sharp cheekbones, narrow dark eyes, thin dark eyebrows, short dark undercut hair, a silver stud in the left ear, light stubble, a confident smirk. Olive skin with realistic texture. Clothing: a dark olive hooded parka with the hood DOWN so the face and hair are always visible, a black fitted t-shirt, slim dark jeans, black trainers with white soles, taped knuckles. Neutral grey studio background, soft key light upper left, macro detail on the face, zip, fabric texture. An invented fictional person. Locked reference design.
**Save as:** `Wire_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Wire_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM (trainers and ground contact), neutral grey background, matched lighting/scale, neutral pose, hood down in every panel. Add a second row of five close-up face panels (smirk, focused, strained, startled, grudging nod) locking the face.
**Save as:** `Wire_6Angle.png`
**Usage note:** Attach both files to every scene where Wire appears: S1-01, S1-02, S1-04 to S1-06, S2-02, S2-04 to S2-06.

### 1D. The Black Case
**Portrait Image Prompt — Google Flow:**
A compact matte-black aluminium hard case, 40 cm wide, rounded corners, two brushed-steel latches, a short nylon carry strap, a thin continuous cyan light seam glowing softly around the lid edge, light scuffs and a small dent at one corner showing use, no logos, no text, no labels. Three-quarter view on a neutral grey surface, soft key light upper left, macro detail on the latches, scuffed anodised metal and the glowing seam. Locked reference design.
**Save as:** `Case_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Case_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM, neutral grey background, matched lighting/scale, the cyan seam glowing at the same brightness in every panel.
**Save as:** `Case_6Angle.png`
**Usage note:** Attach both files to every scene where the case is visible: S1-01 to S1-07, S2-01, S2-03, S2-06.

---

# STEP 2 — FIXED ENVIRONMENT PLATES (Google Flow — image generation ONLY)

> The environment is **locked once** and reused. Generate these plates first, save them, then attach the right plates to every Step 3 prompt. Never describe the location differently between scenes: that keeps the layout, props and light identical.

## ENVIRONMENT 1 — "The Rooftops" (Short 1) — night, light drizzle, wet concrete

Layout rule (so the fight geography stays continuous): the run goes **left to right**. Plate A (start) → a 3 m gap → Plate B (water tank and pipes, middle) → Plate C (far edge with the parapet and a lower roof). Keep the neon glow below the roofs on the camera-left side, the distant skyline on the right.

### 2A. Rooftop Plate A — "Start Run"
**Environment Image Prompt — Google Flow:**
Wide establishing shot of a long flat concrete rooftop of an old city building at night, light drizzle, the surface wet and reflecting amber sodium lights and cyan neon glow rising from the street below on the left, a steel rooftop access door in a brick stair-housing at the left, rows of square ventilation units and short pipes in the middle, a low parapet along the right edge with a three-metre gap to the next rooftop in the distance, a dense city skyline with lit windows far behind, no people, no text or signs, 8K-level detail, anamorphic lens feel.
**Save as:** `Env1_A_Start.png`

### 2B. Rooftop Plate B — "Tank and Pipes"
**Environment Image Prompt — Google Flow:**
Wide shot of the next rooftop in the same night drizzle and same colour grade: a large old wooden-and-steel water tank on a steel tower on the left, a tangle of insulated steam pipes running across the roof at knee height with two red-wheel steam valves, a stack of tarpaulin-wrapped bundles and sand bags against a low wall on the right (a soft landing area), puddles reflecting amber and cyan light, a lower rooftop visible beyond the parapet, no people, no text.
**Save as:** `Env1_B_TankPipes.png`

### 2C. Rooftop Plate C — "The Edge"
**Environment Image Prompt — Google Flow:**
Wide shot of the far end of the rooftops in the same night drizzle: a waist-high parapet wall with a metal antenna mast, a thick steel cable anchored to the mast running down and away across the open gap toward a distant lit building, the full city skyline with a river of light below, a faint helicopter spotlight beam in the sky, wet concrete shining, no people, no text.
**Save as:** `Env1_C_Edge.png`

### 2D. Rooftop 6-Angle layout sheet
**Environment Image Prompt — Google Flow:**
Using `Env1_A_Start.png`, `Env1_B_TankPipes.png` and `Env1_C_Edge.png` as exact reference, generate an overhead layout view of the whole rooftop route showing the start roof, the gap, the tank roof and the edge roof in order left to right, with all props in the exact same positions as the plates.
**Save as:** `Env1_Layout.png`
**Usage note:** Attach `Env1_Layout.png` plus the plate(s) for each scene as listed per scene.

## ENVIRONMENT 2 — "The Container Yard" (Short 2) — dawn, mist, cold blue to warm gold

Layout rule: the yard entrance is at the left, the stacks of containers form a corridor in the middle, and the crane and the dock edge are on the right, with the sunrise behind the crane.

### 2E. Yard Plate D — "The Entrance"
**Environment Image Prompt — Google Flow:**
Wide establishing shot of a shipping-container yard at dawn, low mist on the ground, cold blue sky turning gold at the horizon, hundreds of weathered containers in faded red, green, blue and rust-orange stacked three high in long rows with no markings or text, a wide gravel-and-concrete lane running into the yard from the left, puddles reflecting the sky, a tall portal crane silhouette against the sunrise on the right, gulls in the air, no people, no text.
**Save as:** `Env2_D_Entrance.png`

### 2F. Yard Plate E — "The Corridor"
**Environment Image Prompt — Google Flow:**
Medium-wide shot down a narrow corridor between two walls of stacked containers in the same dawn light, 3 metres wide, corrugated steel walls with scuffs and dents but no text, a loose heap of cardboard bales and a stack of wooden pallets at the far end (a soft landing area), a metal ladder on the left wall, one container with a flat roof edge at head height of the second tier, a strip of gold light at the end of the corridor, mist on the ground, no people.
**Save as:** `Env2_E_Corridor.png`

### 2G. Yard Plate F — "Crane and Dock"
**Environment Image Prompt — Google Flow:**
Wide shot of the quayside at the same dawn: the tall portal crane with a heavy hook on a chain hanging at head-height above the concrete dock apron, calm dark water with a golden sun path behind, a low steel table and bollards on the dock edge, a few stacked foam-wrapped cargo bales on the right (soft landing area), seagulls, long shadows, no people, no text.
**Save as:** `Env2_F_CraneDock.png`

### 2H. Yard Layout sheet
**Environment Image Prompt — Google Flow:**
Using `Env2_D_Entrance.png`, `Env2_E_Corridor.png` and `Env2_F_CraneDock.png` as exact reference, generate an overhead layout view of the container yard from the entrance, through the corridor, to the crane and dock, with all props in the exact same positions as the plates.
**Save as:** `Env2_Layout.png`

---

# STEP 3 & STEP 4 — SCENES (8-second clips)

**How each scene is shaped:**
Header (scene number, label, time, clip length) → **Story beat** (editor note only, never paste into Flow) → Step 3 Ingredients → Step 3 Reference Image Prompt → Step 4 Ingredients → Video Prompt (Google Flow, exactly 8 s, in-clip second marks where `0s` = the clip start) → Sound → Cut→.
Append the GLOBAL LOCK BLOCK to the end of every Step 3 and Step 4 prompt.
Every video prompt ends with: "No speech, shouting, grunting, narration, whispering or singing: people's mouths stay closed or tight with effort. Audio is music and sound effects only."

**Safe-wording rules used in all video prompts** (if Flow ever blocks a prompt, change words to these): "strike" → "palm contact" · "hit" → "make contact" · "fight" → "sparring chase" · "knocked down" → "loses balance and rolls" · "attack" → "rush". Never write "kill", "blood", "weapon", "gun", "knife", "punch to the face". Keep strikes aimed at the torso or shoulder and always show the defender blocking or moving.

---

# SHORT 1 — NIGHT RUN (56 s, Environment 1: The Rooftops)

### S1-01 — Running with the case | 0:00–0:08
Story beat: Open already in motion. Rhea sprints toward camera, the case on her back strap; behind her two figures burst through the rooftop access door.
Step 3 Ingredients: Subjects: `Rhea_Portrait.png`, `Rhea_6Angle.png`, `Case_Portrait.png`, `Case_6Angle.png`, `Dax_Portrait.png`, `Wire_Portrait.png` · Environment: `Env1_A_Start.png`, `Env1_Layout.png` · Continuity: none (first scene)
Step 3 — Reference Image Prompt (Google Flow):
Low tracking-camera frame on the wet rooftop of Env1 Plate A at night: Rhea mid-sprint running left-to-right across the frame in a three-quarter profile, ponytail swinging, the black case with its glowing cyan seam strapped across her back, rain streaks lit amber, at the far left the steel access door open with the silhouettes of Dax and Wire stepping out, sharp focus on her face, reflections of neon on the puddles.
Save as: `S1-01_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S1-01_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S1-01_Ref.png`. 0–2s: the camera tracks alongside Rhea at hip height as she sprints left-to-right, rain spraying off her boots, her breath misting; 2–4s: behind her the access door bangs open and Dax and Wire run out, small and distant, the camera drifts to keep her in focus; 4–6s: Rhea glances back over her shoulder once, eyes narrowed, and lengthens her stride toward the right-hand parapet; 6–8s: the camera speeds with her toward the gap, the skyline filling the frame ahead. One continuous tracking shot.
Sound (BGM+SFX only): A low pulsing synth rises from silence with a driving heartbeat kick; rain, boots splashing, the metal door slam at 2s, a distant city hum.
Cut→S1-02: Continuous motion, the same speed and direction.

### S1-02 — The gap jump | 0:08–0:16
Story beat: A grounded stunt: a three-metre rooftop gap jump with a proper landing roll; Wire follows with a parkour vault.
Step 3 Ingredients: Subjects: `Rhea_*`, `Case_*`, `Wire_*` · Environment: `Env1_A_Start.png`, `Env1_B_TankPipes.png`, `Env1_Layout.png` · Continuity: `S1-01_Ref.png` (subject and colour-grade continuity only)
Step 3 — Reference Image Prompt (Google Flow):
Side-on wide frame at the right edge of Env1 Plate A: Rhea at the very top of a running jump, body horizontal, arms forward, both feet just leaving the parapet, a three-metre gap of dark air with a wet rooftop (Plate B, the water tank on the left of it) waiting on the far side, Wire running toward the parapet in the background, neon glow beneath, rain streaks.
Save as: `S1-02_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S1-02_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S1-02_Ref.png`. 0–2s: the camera tracks sideways along the edge as Rhea launches off the parapet with a driving push from her back leg; 2–4s: slow-motion beat in mid-air, her ponytail and jacket trailing, the gap a dark drop beneath her; 4–6s: she lands on the far rooftop with bent knees, drops her shoulder and rolls over it, springing back onto her feet without losing speed; 6–8s: behind her Wire reaches the parapet, plants one hand on it and vaults across, landing in a crouch with a splash. Grounded weight and recovery, no floating.
Sound (BGM+SFX only): The pulse drops to a held breath at 2s, then a heavy landing impact on wet concrete at 4s with a rolling cloth swish, the percussion kicking back in; rain, splash at 7s.
Cut→S1-03: Hard cut forward on the same direction.

### S1-03 — Dax blocks the path | 0:16–0:24
Story beat: The first contact. Rhea stops dead; the huge Dax steps in; she slips his swing and answers with a palm strike to the shoulder that spins him.
Step 3 Ingredients: Subjects: `Rhea_*`, `Case_*`, `Dax_*` · Environment: `Env1_B_TankPipes.png`, `Env1_Layout.png` · Continuity: `S1-02_Ref.png` (subject and colour-grade continuity only)
Step 3 — Reference Image Prompt (Google Flow):
Medium-wide frame on Env1 Plate B in the drizzle: Rhea in a low ready stance in the centre of the wet roof, case on her back, facing Dax who stands between her and the water tank with his shoulders wide, hands open and ready, both lit from the side by amber light with cyan neon behind, steam leaking from the pipes on the floor between them, faces fully visible.
Save as: `S1-03_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S1-03_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S1-03_Ref.png`. 0–2s: the camera pushes in slowly from a wide to a medium two-shot as the two circle, rain falling between them; 2–4s: Dax rushes forward and swings a heavy open-handed sweep at her shoulder height; 4–6s: Rhea ducks under it, the swing passing over her head, and steps inside; 6–8s: she plants a palm strike on his shoulder, he spins half a turn off balance with a heavy stagger, and she steps back into a ready stance. Clear separation between the two bodies, weight and momentum visible.
Sound (BGM+SFX only): A tight rhythmic synth pulse with a low brass swell at 2s; a whoosh of the swing at 3s, a dull cloth-and-body impact at 6s, boots scraping on the wet surface.
Cut→S1-04: Hard cut to a wider angle.

### S1-04 — Wire flanks | 0:24–0:32
Story beat: Two-on-one: Wire's fast kick forces Rhea to defend and counter with a sweep.
Step 3 Ingredients: Subjects: `Rhea_*`, `Dax_*`, `Wire_*` · Environment: `Env1_B_TankPipes.png`, `Env1_Layout.png` · Continuity: `S1-03_Ref.png` (subject and colour-grade continuity only)
Step 3 — Reference Image Prompt (Google Flow):
Wide frame on Env1 Plate B: Wire in mid-air in a spinning kick toward Rhea's raised forearm guard, Rhea in a low stance with both arms up blocking, Dax recovering in the background by the water tank tower, rain streaks lit amber, clear space between the bodies, faces fully visible.
Save as: `S1-04_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S1-04_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S1-04_Ref.png`. 0–2s: Wire's spinning kick lands on Rhea's raised forearms, she absorbs it and slides back half a step; 2–4s: she catches his ankle against her ribs and twists; 4–6s: she sweeps his standing leg with her own, he loses balance and falls onto his back on the wet roof, rolling away; 6–8s: Dax steps in from the side as Wire rises, and Rhea stands between them with her breath steaming, a ready stance, turning her shoulders. The camera orbits slowly 90 degrees around the three.
Sound (BGM+SFX only): Percussion builds a driving rhythm; a kick impact thump on cloth at 1s, a boot scrape and sweep whoosh at 4s, a wet roll on concrete, rain.
Cut→S1-05: Hard cut to a low angle.

### S1-05 — The steam valve | 0:32–0:40
Story beat: The smart escape: Rhea uses the roof itself: a knee-slide under the pipe and a kick to open the steam valve.
Step 3 Ingredients: Subjects: `Rhea_*`, `Dax_*`, `Wire_*` · Environment: `Env1_B_TankPipes.png` · Continuity: `S1-04_Ref.png` (subject and colour-grade continuity only)
Step 3 — Reference Image Prompt (Google Flow):
Low-angle frame at ground level on Env1 Plate B: Rhea sliding on her knees on the wet concrete under a knee-high insulated pipe toward the camera, one boot extended toward a red steam valve wheel, Dax and Wire rushing at her from the background, reflections in the puddles.
Save as: `S1-05_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S1-05_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S1-05_Ref.png`. 0–2s: Rhea slides under the pipe on her knees with her back arched, the camera tracking low ahead of her; 2–4s: she hooks the red valve wheel with her boot and kicks it round, a jet of white steam bursts out; 4–6s: the steam billows across the roof between her and the two chasers, who slow and shield their faces with their arms; 6–8s: she rolls to her feet and disappears into the cloud, the camera pushing into the white. Keep the steam natural and volumetric.
Sound (BGM+SFX only): A sharp metallic squeal of the valve wheel at 2s, a loud steam hiss that fills the mix at 3s, the music ducks to a tense held note then returns; boots sliding.
Cut→S1-06: Dissolve through the white steam.

### S1-06 — Inside the steam | 0:40–0:48
Story beat: The climax of the fight: Rhea throws Wire onto the soft tarps and sidesteps Dax's charge so he plunges into the sand-bag pile.
Step 3 Ingredients: Subjects: `Rhea_*`, `Dax_*`, `Wire_*` · Environment: `Env1_B_TankPipes.png`, `Env1_Layout.png` · Continuity: `S1-05_Ref.png` (subject and colour-grade continuity only)
Step 3 — Reference Image Prompt (Google Flow):
Medium frame inside thick white steam on Env1 Plate B, backlit by amber light: Rhea gripping Wire's wrist and shoulder in a hip-throw position, Wire's body horizontal in the air over her hip, the tarp-and-sandbag pile at the right edge of the frame, Dax a dark silhouette charging from the left, steam swirling.
Save as: `S1-06_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S1-06_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S1-06_Ref.png`. 0–2s: Rhea completes the hip throw, Wire flips over her hip and lands on the soft tarp bundles; 2–4s: she turns to face Dax's charge, her weight low; 4–6s: she sidesteps at the last moment and guides his shoulder with her hand, using his own momentum; 6–8s: Dax plunges into the sand-bag pile and the tarps, bags bursting open in puffs of dust, and stays on his hands and knees, winded. Rhea stands with her chest heaving, steam parting around her. Camera handheld, keeps all three in frame.
Sound (BGM+SFX only): A dense percussion roll builds, then a heavy soft thud of a body on tarps at 2s, a deep sand-bag crash at 7s with a puff of dust, a winded air exhale as non-vocal SFX, steam hiss fading.
Cut→S1-07: Hard cut to the final edge.

### S1-07 — The leap | 0:48–0:56
Story beat: The escape and the cliffhanger. Rhea clips the case's strap to the cable and drops off the edge into the neon night, while a helicopter spotlight sweeps.
Step 3 Ingredients: Subjects: `Rhea_*`, `Case_*` · Environment: `Env1_C_Edge.png`, `Env1_Layout.png` · Continuity: `S1-06_Ref.png` (subject and colour-grade continuity only)
Step 3 — Reference Image Prompt (Google Flow):
Wide low-angle frame on Env1 Plate C: Rhea standing on the waist-high parapet with her back to the camera, the black case with its cyan seam in her hand, a thick steel cable above her running from the antenna mast out over the glowing city, a helicopter spotlight beam crossing the wet roof behind her, rain, a cinematic silhouette against the neon skyline.
Save as: `S1-07_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S1-07_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S1-07_Ref.png`. 0–2s: the spotlight beam sweeps across the roof and across her back; she looks at the cyan light of the case once; 2–4s: she loops the case's strap over the cable with both hands and grips it; 4–6s: she steps off the parapet and swings out over the drop, the camera craning up behind her; 6–8s: the camera rises high above the roofs, showing her small on the cable above a river of neon light, the helicopter beam following. Slow and cinematic, held at the end.
Sound (BGM+SFX only): The theme swells into a full orchestral-synth climax with deep brass; a metal cable twang and a smooth rolling zip at 4s, helicopter rotor thump rising at 5s, wind, rain fading to silence at the end with one last low note.
Cut→S2-01: Match cut: the camera's rise dissolves into a dawn sky.

---

# SHORT 2 — CONTAINER YARD (48 s, Environment 2: The Container Yard)

### S2-01 — Dawn arrival | 0:00–0:08
Story beat: The next morning. Rhea walks into the yard with the case, wary.
Step 3 Ingredients: Subjects: `Rhea_*`, `Case_*` · Environment: `Env2_D_Entrance.png`, `Env2_Layout.png` · Continuity: `S1-07_Ref.png` (subject and colour-grade continuity only)
Step 3 — Reference Image Prompt (Google Flow):
Wide low frame on Env2 Plate D at dawn: Rhea walking from the left into the container yard along the gravel lane, the case in her right hand glowing cyan in the mist, tired but alert, hair damp, jacket dusty, long containers rising on both sides, the portal crane silhouette against the gold horizon, gulls.
Save as: `S2-01_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S2-01_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S2-01_Ref.png`. 0–3s: a slow dolly backward in front of Rhea as she walks left-to-right into the yard, mist curling around her boots; 3–5s: she slows, her head tilting as she senses movement among the containers; 5–7s: a distant echo of a metal clang makes her stop and tighten her grip on the case; 7–8s: the camera settles on her eyes scanning the rows. Calm, tense, grounded.
Sound (BGM+SFX only): A quiet pad and a single low string note; gravel crunching, gulls, a distant crane creak, one metal clang at 5s, a wind whistle.
Cut→S2-02: Hard cut to a wider angle.

### S2-02 — The standoff | 0:08–0:16
Story beat: Dax and Wire appear from behind the containers and block the lane.
Step 3 Ingredients: Subjects: `Rhea_*`, `Case_*`, `Dax_*`, `Wire_*` · Environment: `Env2_D_Entrance.png`, `Env2_Layout.png` · Continuity: `S2-01_Ref.png` (subject and colour-grade continuity only)
Step 3 — Reference Image Prompt (Google Flow):
Wide frame on Env2 Plate D: Rhea in the foreground left in a ready stance holding the case low, Dax stepping out from behind a container in the middle ground, Wire sitting on top of a container two tiers up on the right, rim-lit by the sunrise, mist at their feet, all three faces visible.
Save as: `S2-02_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S2-02_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S2-02_Ref.png`. 0–3s: Dax steps out and folds his arms, blocking the lane, his eyes fixed on the case; 3–5s: Wire drops from the container roof, lands in a low crouch with a metallic thud, and rises with a smirk; 5–8s: Rhea sets the case on the ground between her feet, straightens, and slowly raises her hands into a guard, her eyes moving from one to the other. A slow orbit around the three.
Sound (BGM+SFX only): A sparse tense drone with a heartbeat low drum; boots on gravel, a heavy landing at 4s, a case set on the ground at 6s, gulls fading.
Cut→S2-03: Hard cut into the corridor.

### S2-03 — Corridor clash | 0:16–0:24
Story beat: Dax charges; the narrow corridor lets Rhea use the walls: block, knee, wall-push.
Step 3 Ingredients: Subjects: `Rhea_*`, `Dax_*`, `Case_*` · Environment: `Env2_E_Corridor.png`, `Env2_Layout.png` · Continuity: `S2-02_Ref.png` (subject and colour-grade continuity only)
Step 3 — Reference Image Prompt (Google Flow):
Medium frame down the narrow container corridor of Env2 Plate E: Rhea in a low guard with her back to the camera on the left, Dax lunging toward her with both arms out, the black case on the ground behind her, steel walls close on both sides, gold light and mist at the far end.
Save as: `S2-03_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S2-03_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S2-03_Ref.png`. 0–2s: Dax lunges and grabs for her jacket; Rhea twists out of his reach, trapping his wrist; 2–4s: she drives her knee into the side of his thigh, a glancing contact, and he bends forward; 4–6s: she shoves his shoulder into the container wall, the corrugated steel ringing and shaking with a dull boom; 6–8s: Dax stays against the wall, breathing hard, while Rhea backs a step and snaps her gaze up at a clang from above. The camera follows handheld from behind her shoulder.
Sound (BGM+SFX only): A pounding drum and bass-synth rhythm; cloth grabs, a thudding knee on fabric at 3s, a deep metal boom at 5s, boots scraping, a loose chain rattle above at 7s.
Cut→S2-04: Hard cut to a wide angle on the stacks.

### S2-04 — Over the containers | 0:24–0:32
Story beat: Wire attacks from above; Rhea uses the container wall for a one-step wall-run and flips over him.
Step 3 Ingredients: Subjects: `Rhea_*`, `Wire_*` · Environment: `Env2_E_Corridor.png`, `Env2_Layout.png` · Continuity: `S2-03_Ref.png` (subject and colour-grade continuity only)
Step 3 — Reference Image Prompt (Google Flow):
Low-angle frame in the container corridor of Env2 Plate E: Wire dropping from the second-tier container edge with his arms out toward Rhea, Rhea pushing off the corrugated wall with one boot in mid wall-step, her body turning upward and over, mist, gold light shafts through gaps between containers.
Save as: `S2-04_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S2-04_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S2-04_Ref.png`. 0–2s: Wire jumps down at her from the ledge; 2–4s: Rhea steps up the wall with one boot and flips backward and over him, passing his shoulder; 4–6s: she lands behind him, spins, and sweeps his feet while he is still turning; 6–8s: Wire drops to his hands and one knee on the gravel, looks up at her, and she holds a cool ready stance. The camera tracks low and orbits slightly. Believable body mechanics, real arc and weight.
Sound (BGM+SFX only): A fast percussive build; a boot squeak on metal at 2s, a cloth whoosh, soft landing on gravel at 5s, a metal wall ring.
Cut→S2-05: Hard cut to the dock.

### S2-05 — The crane hook | 0:32–0:40
Story beat: The finale fight on the quay: Rhea swings from the crane chain and sends Dax back into the soft cargo bales.
Step 3 Ingredients: Subjects: `Rhea_*`, `Dax_*`, `Wire_*` · Environment: `Env2_F_CraneDock.png`, `Env2_Layout.png` · Continuity: `S2-04_Ref.png` (subject and colour-grade continuity only)
Step 3 — Reference Image Prompt (Google Flow):
Wide frame on Env2 Plate F: Rhea gripping the heavy crane hook chain with both hands and swinging in a low arc over the dock apron with her boots forward, Dax charging toward her from the left, Wire coming from behind a bollard, the foam-wrapped cargo bales on the right, golden sunrise path on the water, mist.
Save as: `S2-05_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S2-05_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S2-05_Ref.png`. 0–2s: Rhea swings along the chain as Dax closes in; 2–4s: at the end of her arc she plants both boots against Dax's raised forearms and pushes off, sending him stumbling backward; 4–6s: Dax stumbles several steps and drops back onto the foam-wrapped cargo bales with a soft crumpling thud; 6–8s: Rhea lands on the apron, slides to a stop, and Wire stops short, hands up, glancing at Dax. The camera cranes low to high with the swing.
Sound (BGM+SFX only): The theme returns big with brass and drums; a chain rattle and creaking crane at 1s, a heavy swing whoosh, a soft thud into bales at 5s, gulls scatter.
Cut→S2-06: Hard cut to the dock table.

### S2-06 — The handover | 0:40–0:48
Story beat: The resolution. The villains stop; Dax gives a nod; Rhea sets the case on the table; the cyan seam turns green; she walks into the sun.
Step 3 Ingredients: Subjects: `Rhea_*`, `Dax_*`, `Wire_*`, `Case_*` · Environment: `Env2_F_CraneDock.png`, `Env2_Layout.png` · Continuity: `S2-05_Ref.png` (subject and colour-grade continuity only)
Step 3 — Reference Image Prompt (Google Flow):
Wide frame on Env2 Plate F at full sunrise: Rhea in the centre placing the black case on the low steel table on the dock edge, the cyan seam of the case now glowing green, Dax standing up from the bales on the right brushing dust from his sleeve and giving a small respectful nod, Wire leaning on a bollard with a half smile, calm water and gold light, long shadows.
Save as: `S2-06_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S2-06_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S2-06_Ref.png`. 0–2s: Rhea sets the case on the table, the glow shifting from cyan to a soft green; 2–4s: Dax rises from the bales, brushes dust from his jacket and gives her a single slow nod; Wire exhales and shrugs; 4–6s: Rhea nods back, turns, and walks away toward the sunrise along the quay; 6–8s: the camera cranes up and away, the three small figures and the crane in a golden wide shot, mist rising from the water. Calm, earned finish.
Sound (BGM+SFX only): The music resolves into a warm sustained chord with soft strings; the case's gentle electronic chime at 1s, boots on concrete, waves lapping, gulls, final low note.
Cut→END: Slow fade to black; hold 1 s of silence.

---

# EDIT, SAFETY & QUALITY NOTES

**1. Anti-"AI slop" checklist (apply to every clip):**
- Keep **one subject action per 2 seconds** and no more than **two fighters in the foreground**: crowded choreography is where limbs merge and swap.
- Use **one continuous camera move** per clip. Avoid "rapid cuts", "chaotic", "shaky" and "explosion" in prompts; they cause warping.
- Always describe **weight**: "bent knees", "plants his boot", "recovers", "rolls over the shoulder". Avoid "flies", "floats", "superhuman".
- Generate the **reference image first**, check the two faces and hands, and only then make the video. Reject any still with merged hands or mismatched faces.
- Generate **2–3 takes per clip** and pick the one where the strikes visibly stop short or land on shoulders and jackets.
- Fix-ups: if a face drifts, redo the reference image; if bodies overlap, add "clear separation of one body-width between the fighters".

**2. Google Flow policy safety (why this version should pass):** invented fictional adults; no real or famous people, no brands or logos; no weapons, no blood or injuries, no one defenceless or in peril; the fight is stunt choreography with blocks, throws and soft landings; no text in frame; no copyrighted characters or franchise names. If a clip is still refused, reword with the safe-wording table above or reduce the action to "sparring" and "chase".

**3. Audio handling:** Flow's generated sound can include odd vocal noises; if you hear any, mute that clip and rebuild the audio in your editor: one continuous instrumental bed (pulsing synth, taiko-style drums, low brass; 100–120 BPM) rising from S1-01 to S1-07, a silence-and-reset at S2-01, and a bigger finish at S2-05, with SFX from a licensed SFX library.

**4. Continuity between the shorts:** S1-07's last frame (Rhea swinging over the neon city) and S2-01's first frame (dawn) are linked by a sky dissolve. Post Part 1 and Part 2 together as a Shorts playlist.

**5. Shorts publishing (text lives in the metadata, never in the video):**
- Titles: "She Had 60 Seconds to Cross the City | NIGHT RUN (Part 1)" · "The Last Handover | CONTAINER YARD (Part 2)".
- Description hook: "No dialogue. Just rain, steel and a sealed case. Watch to the end of Part 2."
- Tags: action short film, stunt choreography, cinematic action, rooftop chase, parkour, thriller short, AI film.
- Cover frames: S1-07 (Rhea on the parapet against the neon) and S2-06 (the green-glowing case at sunrise).
