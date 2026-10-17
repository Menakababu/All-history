# THRILLER 01 — THE LAST FERRY: A 32-Second Chase Thriller (No Fight Scenes)
### [TEMPLATE v5 — Google Flow only · 4 clips × 8 s = 32 s · Step 1 characters → Step 2 fixed environment plates → Step 3 per-scene reference image → Step 4 per-scene video · global lock on every prompt · no on-screen text · BGM + diegetic SFX only · no fighting]

**Duration:** 0:32 (4 × 8 s) | **Format:** 9:16 for Shorts (or 16:9, your choice) | **Pace:** medium, a hard jog that becomes a run. Nothing is sped up and nothing is superhuman.
**Genre:** a chase against the clock. The only "enemy" is a misunderstanding.

**Story in one line:** A courier carrying a sealed medical cooler must reach the last ferry before it leaves at sunset. A bumped fruit stall and a wrong assumption send an older security guard chasing him through the harbour town, until the guard sees what is inside the cooler.

**Moral:** *Before you judge someone who is running, ask what they are running for, and then help them get there.* (It is shown, never written on screen.)

**Hollywood-level feel, without copying anyone:** I can't use a real actor's name or likeness in the prompts, and Flow would likely block it. The prompts instead use the techniques that make big-studio stunt thrillers feel real: long unbroken tracking takes, a real-location look, practical-stunt realism (real weight, real stumbles), large-format cinema lenses, and tension built from the ticking clock (the ferry horn, the sinking sun and the rising gangway) rather than from speed.

---

## NATURAL-HUMAN-ACTIVITY RULES (the anti-AI-slop contract)

These are baked into every video prompt. Keep them if you edit anything.
1. **Medium pace:** Kabir runs at about 70% effort and a steady stride, with a visible arm swing and a natural heel-to-toe rhythm. The guard jogs heavily and slowly closes the gap only because Kabir loses time. No sprinting like a movie superhero.
2. **Real body signals:** breathing that gets heavier clip by clip, sweat at the temples and collar, a shirt sticking to the back, a hand pressed to the side during the last stretch.
3. **Real physics and logic:** he bumps the stall *then* oranges roll; he slows for a corner; the wet quay steps make him take small steps; the gangway is lifted by a deckhand with a rope and winch, not by magic.
4. **Real crowd behaviour:** bystanders step aside, glance, stare and carry on; nobody stands still in his way for a convenient reason.
5. **No fighting at all.** No weapons (the guard has a whistle and a torch clipped to his belt, nothing else), no tackles, no shoving, no one is hurt.
6. **One continuous camera move per clip.** No whip pans, no fast cuts inside a clip.
7. **Two people maximum in the foreground**, always with space between them, so limbs never merge.
8. **Screen direction:** Kabir always runs **left to right**. The guard is always behind him (screen left).
9. **Continuity props:** the red-and-white cooler on his **right** shoulder; the steel watch on his **left** wrist; the same sweat-darkened blue shirt from clip 1 to clip 4; the sun gets lower in each clip.

---

## ⚠️ GLOBAL LOCK BLOCK — append this in full to the END of every single prompt below (Step 1, Step 2, every Step 3, every Step 4)

```
GLOBAL LOCK:
CONTINUITY — Keep Kabir, Mr. Hale, Nurse Lena and the Medical Cooler (including faces, hair, skin tone, clothing, wear, sweat level and the red-and-white cooler with the steel clasp) in exact colour/design/proportion continuity from their saved reference sheets — no redesign, recolour, age drift or costume drift. Keep the harbour town inside its fixed environment exactly as shown in the saved environment plates: same layout, same props in the same places, same weather. Kabir always runs left-to-right on screen, the guard behind him on screen-left. The sun is lower and the light warmer in each successive clip.
STYLE — Photorealistic cinematic thriller, shot on a large-format digital cinema camera with 40mm and 65mm lenses, extremely fine detail, natural film grain, 180-degree shutter motion blur, rich natural grade (warm golden-hour highlights, teal-blue shadows, deep blacks, no crushed detail). Real material physics: wet stone reflects light, oranges roll with believable speed, rope and cloth follow motion with weight, breath mists faintly in the cooling evening air. Ordinary human movement with true weight transfer, balance and recovery: nothing superhuman.
HARD RULES — No on-screen text, captions, logos, brand names, readable signs or watermarks anywhere; shop signs, the ferry and the cooler show no readable letters. Human characters have clear, natural, fully visible faces (realistic skin texture, pores, sweat, eyes, expressions) that match their saved reference sheets exactly in every shot; these are invented fictional faces, not likenesses of any real person. Faces never morph, age or change between shots. No fighting, no weapons, no violence, no tackling, no one injured, no vehicles hitting anyone. Danger is shown only by time pressure, distance and effort.
ZERO AI ARTIFACTS — No morphing, warping, melting, flicker, extra or duplicated limbs/fingers, merged bodies, rubbery or boneless motion, floaty or weightless steps or jumps, sliding feet, plastic skin, texture smearing, inconsistent shadows, distorted hands or anatomy, crowd faces that twist, people passing through objects, sudden costume or prop changes, text-like marks.
LIGHTING — Follow the time of day written in each prompt (golden hour sinking toward sunset across the four clips) with one consistent colour grade; no sudden unintended light jumps inside a shot.
AUDIO — Generated audio is ONLY instrumental cinematic BGM (ticking low percussion, tense strings, a slowly rising pulse, one warm resolving chord at the end) plus diegetic SFX (footsteps, breathing as non-vocal air, rolling oranges, a security whistle, a ferry horn, harbour water, gulls, a winch, rope, crowd murmur-free ambience). Absolutely no dialogue, no shouting, no speech in any language, no screaming, no singing, no chanting. People never speak and their mouths stay closed or open only to breathe. Any quoted or timing text in the prompt is a camera/timing cue, never spoken words.
CAMERA — One continuous, physically plausible camera move per clip (steady tracking, low glide, handheld push, crane rise); no whip cuts inside a clip; each clip's opening camera motion matches the previous clip's closing motion vector. Keep both people fully visible, readable and separated from each other.
```

---

# STEP 1 — CHARACTER & PROP REFERENCE IMAGES (Google Flow — image generation ONLY)

> Every sheet: realistic photographic style (see GLOBAL LOCK), neutral grey studio background, soft key light from upper left. Each subject gets a **Portrait** prompt and a **6-Angle Turnaround** prompt. Attach BOTH files wherever that subject appears.

### 1A. Kabir — the courier
**Portrait Image Prompt — Google Flow:**
Full-body standing portrait of Kabir, an invented fictional man of 31, lean and fit but ordinary, facing the camera in a relaxed stance, with a clearly visible, fully detailed face: dark brown eyes with a worried, honest look, thick dark eyebrows, short black hair slightly damp, a day's stubble, a small healed nick in the right eyebrow, warm brown skin with realistic texture. Clothing: a plain navy-blue cotton shirt with the sleeves rolled to the forearm, slim grey work trousers, sturdy black running-style shoes with worn soles, a steel wristwatch on the LEFT wrist, a webbing strap over the RIGHT shoulder (the cooler will hang from it). Neutral grey studio background, soft key light upper left, macro detail on the face, shirt weave and shoe soles. An invented fictional person. Locked reference design.
**Save as:** `Kabir_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Kabir_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT (face fully visible, identical to the portrait), REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM (shoes and ground contact), neutral grey background, matched lighting/scale. Add a second row of five close-up face panels (calm, anxious, strained, relieved, grateful) locking the face.
**Save as:** `Kabir_6Angle.png`
**Usage note:** Attach both files to every scene where Kabir appears: S01–S04.

### 1B. Mr. Hale — the harbour security guard
**Portrait Image Prompt — Google Flow:**
Full-body standing portrait of Mr. Hale, an invented fictional man of 56, solid and slightly heavy, facing the camera in a stern but tired stance, with a clearly visible, fully detailed face: grey close-cropped hair, a thick grey moustache, deep lines at the eyes, heavy eyelids, a stubborn jaw, reading glasses pushed up on the forehead, fair skin with realistic texture and a flushed look. Clothing: a plain dark-grey security uniform shirt and trousers with no badges, logos or text, a flat peaked cap, a silver whistle on a lanyard around the neck, a small torch clipped to his belt, polished black shoes with thick soles. No weapon of any kind. Neutral grey studio background, soft key light upper left, macro detail on the face, cap fabric and the whistle. An invented fictional person. Locked reference design.
**Save as:** `Hale_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Hale_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM (shoes and ground contact), neutral grey background, matched lighting/scale. Add a second row of five close-up face panels (stern, suspicious, winded, realising, kind) locking the face.
**Save as:** `Hale_6Angle.png`
**Usage note:** Attach both files to every scene where Mr. Hale appears: S01–S04.

### 1C. Nurse Lena — on the ferry
**Portrait Image Prompt — Google Flow:**
Full-body standing portrait of Lena, an invented fictional woman of 38, with a clearly visible, fully detailed face: kind tired eyes, light brown skin with realistic texture, a calm expression, black hair tied back in a low bun. Clothing: a pale-blue plain medical tunic and trousers with no badges, logos or text, a thin grey cardigan, comfortable white shoes, a stethoscope around her neck, a small cloth shoulder bag. Neutral grey studio background, soft key light upper left, macro detail on the face and fabric. An invented fictional person. Locked reference design.
**Save as:** `Lena_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Lena_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM, neutral grey background, matched lighting/scale. Add a second row of five close-up face panels (worried, hopeful, relieved, grateful, gentle smile) locking the face.
**Save as:** `Lena_6Angle.png`
**Usage note:** Attach both files to every scene where Lena appears: S04.

### 1D. The Medical Cooler
**Portrait Image Prompt — Google Flow:**
A compact insulated medical transport cooler, 35 cm wide, rounded hard plastic shell in red and white, a steel clasp on the front, a short woven carry strap, a tiny green indicator light on the lid, light scuffs on the corners, no logos, no text, no labels, no symbols that read as letters (a plain white cross shape is not used). Three-quarter view on a neutral grey surface, soft key light upper left, macro detail on the clasp, scuffed plastic and the green light. Locked reference design.
**Save as:** `Cooler_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Cooler_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM, neutral grey background, matched lighting/scale, the green light on in every panel.
**Save as:** `Cooler_6Angle.png`
**Usage note:** Attach both files to every scene where the cooler is visible: S01–S04.

---

# STEP 2 — FIXED ENVIRONMENT PLATES (Google Flow — image generation ONLY)

> The harbour town is **locked once** and reused. Generate the plates first, save them, then attach the right plates to every Step 3 prompt. Never describe the town differently between scenes.

**Layout rule (so the run reads continuously):** the whole route goes **left to right**. Plate A (market street) → Plate B (the stone quay and steps) → Plate C (the ferry and gangway). The sea is on the right of the frame, the old town buildings on the left. The sun is low over the sea on the right, so Kabir runs *toward* the light.

### 2A. Plate A — "The Market Street"
**Environment Image Prompt — Google Flow:**
Wide shot of a narrow cobbled market street in an old harbour town at golden hour, warm low sun at the far right end of the street, open-air stalls on both sides with plain striped awnings and fruit crates (a fruit stall with a pyramid of oranges in the left foreground), a few shoppers walking, whitewashed stone buildings with wooden shutters, laundry on a line overhead, a glimpse of calm sea and a ferry funnel at the end of the street, long warm shadows, no signs with readable text, no people running.
**Save as:** `Env_A_Market.png`

### 2B. Plate B — "The Stone Quay"
**Environment Image Prompt — Google Flow:**
Wide shot of an old stone harbour quay at golden hour just before sunset, a broad stone promenade with a low wall on the left and wide worn stone steps descending to a lower quay on the right, iron mooring bollards, a coil of rope, damp patches on the stone catching the sun, fishing boats bobbing, gulls, the large ferry visible alongside the lower quay in the distance, a wall of warm sun glare on the water, no people, no text.
**Save as:** `Env_B_Quay.png`

### 2C. Plate C — "The Ferry and the Gangway"
**Environment Image Prompt — Google Flow:**
Wide shot of the lower quay and a white-and-blue passenger ferry at sunset, its side-door gangway of steel and wood lying across a gap of about one metre of dark water, a deckhand in a plain orange vest at the winch beside the door starting to raise the gangway on chains, a rope loop around a bollard, a warm orange sun sinking behind the ferry, long reflections on the water, a few passengers on the upper deck, no text on the hull, no readable letters.
**Save as:** `Env_C_Ferry.png`

### 2D. Route Layout sheet
**Environment Image Prompt — Google Flow:**
Using `Env_A_Market.png`, `Env_B_Quay.png` and `Env_C_Ferry.png` as exact reference, generate an overhead layout view of the full route left to right: the market street, the promenade, the stone steps, the lower quay and the ferry with its gangway, with every prop in the exact same position as in the plates.
**Save as:** `Env_Layout.png`

---

# STEP 3 & STEP 4 — SCENES (four 8-second clips)

**How each scene is shaped:**
Header (scene number, label, time, clip length) → **Story beat + moral beat** (editor note only, never paste into Flow) → Step 3 Ingredients → Step 3 Reference Image Prompt → Step 4 Ingredients → Video Prompt (Google Flow, exactly 8 s, in-clip second marks where `0s` = the clip start) → Sound → Cut→.
Append the GLOBAL LOCK BLOCK to the end of every Step 3 and Step 4 prompt.
Every video prompt ends with: "No speech, shouting, narration, whispering or singing: people's mouths stay closed or open only to breathe. Audio is music and sound effects only."

---

### S01 — The bump | 0:00–0:08 (8s)
Story beat: Kabir is already late. A tiny mistake — a bumped fruit stall — starts a misunderstanding. The guard sees only a man running away with a bag.
Moral beat: *Things look different from one side.*
Step 3 Ingredients: Subjects: `Kabir_Portrait.png`, `Kabir_6Angle.png`, `Cooler_Portrait.png`, `Cooler_6Angle.png`, `Hale_Portrait.png`, `Hale_6Angle.png` · Environment: `Env_A_Market.png`, `Env_Layout.png` · Continuity: none (first scene)
Step 3 — Reference Image Prompt (Google Flow):
Medium-wide frame on Env Plate A at golden hour: Kabir in the foreground left-of-centre in a brisk walk-to-jog, the red-and-white cooler hanging from his right shoulder, glancing at the steel watch on his left wrist with a worried face; his elbow has just touched the corner of the fruit stall, and three oranges are beginning to roll off the pyramid; at the far end of the street, small in the background, Mr. Hale in his dark-grey uniform standing with a hand on his belt, looking toward him.
Save as: `S01_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S01_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S01_Ref.png`. 0–2s: the camera tracks steadily alongside at chest height as Kabir hurries along the market street, checks his watch and quickens to a jog; 2–4s: his elbow catches the corner of the fruit stall and three oranges roll off the pyramid and bounce on the cobbles; the stall owner turns and lifts a hand in annoyance; 4–6s: Kabir half turns with a guilty wince and a quick raised palm of apology but does not stop; the ferry horn sounds in the distance and his eyes lift to the funnel at the end of the street; 6–8s: at the far end Mr. Hale lowers his reading glasses over his eyes, sees Kabir hurry away with the red-and-white case, frowns and breaks into a heavy jog; the camera keeps tracking left to right with Kabir. Medium pace, natural breathing, no sped-up motion.
Sound (BGM+SFX only): A low ticking percussion starts like a clock; footsteps on cobbles, oranges bouncing on stone at 3s, a crowd-murmur-free market ambience, a deep ferry horn at 5s, a steel whistle blast at 7s.
Cut→S02: Continuous motion, same speed and direction.

### S02 — Through the lane | 0:08–0:16 (8s)
Story beat: The chase proper: Kabir weaves through a busy lane while the guard follows, the gap steady.
Moral beat: *He could stop to explain, but a life is waiting, and so he keeps going.*
Step 3 Ingredients: Subjects: `Kabir_*`, `Cooler_*`, `Hale_*` · Environment: `Env_A_Market.png`, `Env_Layout.png` · Continuity: `S01_Ref.png` (subject and colour-grade continuity only)
Step 3 — Reference Image Prompt (Google Flow):
Tracking frame further down the same market street (Env Plate A), the sun lower and warmer: Kabir jogging left-to-right with his shirt starting to darken with sweat, the cooler on his right shoulder, stepping around a man pushing a wooden handcart; in the middle ground a woman with a shopping basket stepping aside; Mr. Hale about twelve metres behind him on the left, jogging heavily with his cap in his hand.
Save as: `S02_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S02_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S02_Ref.png`. 0–2s: the camera tracks backward in front of Kabir at a steady medium pace as he jogs, breathing through his mouth, eyes forward; 2–4s: a man pushes a wooden handcart across his path and Kabir slows one step, shortens his stride, steers wide around it and gently touches the cart's edge with his left hand to keep his balance; 4–6s: a woman with a basket steps back against a wall to let him pass, her eyes following him; behind him Mr. Hale reaches the same cart, has to slow and sidestep and wipes his forehead with his sleeve; 6–8s: the street opens to the sun and the sea ahead, Kabir lengthens his stride slightly, glances once over his shoulder to see how far Hale is, and faces forward again. The gap is steady. Believable footfalls, no sliding.
Sound (BGM+SFX only): The ticking percussion gains a low string undertone; footsteps, wooden cart wheels on cobbles at 3s, cloth rustle, steady breathing, crowd ambience with no voices, a gull.
Cut→S03: Continuous motion, the camera swings in behind Kabir.

### S03 — The wet steps | 0:16–0:24 (8s)
Story beat: The turning point of tension: a stumble on wet stone steps and the gangway starting to rise below.
Moral beat: *Haste is not the same as speed: even the one who is right must watch his step.*
Step 3 Ingredients: Subjects: `Kabir_*`, `Cooler_*`, `Hale_*` · Environment: `Env_B_Quay.png`, `Env_Layout.png` · Continuity: `S02_Ref.png` (subject and colour-grade continuity only)
Step 3 — Reference Image Prompt (Google Flow):
Wide low-angle frame on Env Plate B at golden-orange light: Kabir at the top of the wide worn stone steps, one foot already down on a damp step, his arms slightly out for balance, the cooler swinging on his right shoulder, sweat on his face, the ferry visible below with its gangway just beginning to lift; far behind him on the promenade Mr. Hale, red-faced, one hand on his chest, still jogging.
Save as: `S03_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S03_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S03_Ref.png`. 0–2s: the camera glides low and wide as Kabir reaches the head of the steps and starts down, taking short careful strides; 2–4s: his right foot lands on a damp step and slips a few centimetres; he throws out his left arm, grabs the iron handrail, catches his balance with a small bent-knee recovery and the cooler swings against his hip; 4–6s: below, the ferry horn sounds again and the gangway lifts a little on its chains; he draws a sharp breath, steadies, and continues down faster but still under control; 6–8s: on the promenade behind him Mr. Hale reaches the top of the steps, slows, one hand on the wall, sees the cooler glinting and the ferry about to leave, and a flicker of doubt crosses his face. Natural stumble, natural recovery, no falling.
Sound (BGM+SFX only): The music pauses for a held note at the stumble (2s), then drives forward with strings; a shoe scuff on wet stone at 2s, a hand slapping an iron rail, chains clanking at 4s, the ferry horn, heavy breathing.
Cut→S04: Cut with continuous motion down toward the quay.

### S04 — The gap and the rope | 0:24–0:32 (8s)
Story beat: The resolution. The gangway is rising; Kabir reaches the gap; the guard arrives, sees the cooler's green light and a nurse reaching from the deck, and chooses to help. The chase ends in cooperation.
Moral beat: *The man chasing you may be your biggest help the moment he understands.*
Step 3 Ingredients: Subjects: `Kabir_*`, `Cooler_*`, `Hale_*`, `Lena_*` · Environment: `Env_C_Ferry.png`, `Env_Layout.png` · Continuity: `S03_Ref.png` (subject and colour-grade continuity only)
Step 3 — Reference Image Prompt (Google Flow):
Wide frame on Env Plate C at sunset: the ferry's gangway raised about a metre above the quay edge with a dark gap of water, Kabir at the quay edge gripping the cooler strap with a desperate hopeful face, Nurse Lena at the ferry door with her hand stretched out toward him, the deckhand at the winch glancing back, Mr. Hale arriving on the right side of the frame holding a mooring rope in both hands, the cooler's small green light glowing, the orange sun low behind the ferry.
Save as: `S04_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S04_Ref.png`
Video Prompt (Google Flow, 8s):
I2V from `S04_Ref.png`. 0–2s: Kabir reaches the lower quay, slows to a stop at the edge, hands on the cooler strap, breathing hard, looking at the one-metre gap and the rising gangway; 2–4s: Mr. Hale arrives behind him, bent over with his hands on his knees; his eyes catch the green light on the cooler and then Nurse Lena on the deck with her arm stretched out; his face changes from suspicion to understanding; 4–6s: he straightens, lifts a hand to the deckhand in a "hold it" gesture, grabs the mooring rope and pulls it to lower the gangway the last half metre; 6–8s: Kabir steps across onto the gangway, hands the cooler to Lena, who clutches it to her chest with relief; Hale stays on the quay and lifts his cap to Kabir; the ferry slides slowly away into the orange sunset, and the camera cranes up and back to a golden wide shot. Warm, earned, no one hurt.
Sound (BGM+SFX only): The tension peaks with a held string note, then resolves into a single warm chord with soft piano; ferry engine, chain clank at 5s, a gentle wooden thud as the gangway settles, water lapping, a final low ferry horn at 7s, gulls.
Cut→END: Slow fade to black; hold 1 s of silence.

---

# QUALITY & PUBLISHING NOTES

**1. Why this should look real (checklist per clip):**
- Generate the **reference image first** and check faces, hands, the cooler on the **right** shoulder and the watch on the **left** wrist. Reject any still where the cooler switches side, the guard looks younger or the oranges multiply.
- Generate **2–3 takes** per clip and keep the one where the footsteps look planted (no sliding) and the stumble in S03 looks natural.
- If a clip runs too fast, add "at a steady medium jogging pace, real-time speed, no time-lapse" to the start of the Camera line.
- If the guard drifts out of frame, add "Mr. Hale is visible behind Kabir on screen-left in every shot".

**2. Continuity timeline:** golden hour → warmer orange → deep orange → sunset. Sweat level: none → light → clear → heavy. Distance between them: 90 m → 12 m → 30 m → arrives. The cooler's green light stays on the whole film.

**3. Safety:** invented fictional adults, no brands or logos, no text, no real people or look-alikes, no weapons or fighting, no injury, no vehicle collisions. The guard carries only a whistle and a torch. The "chase" is a misunderstanding that ends in cooperation.

**4. Audio:** if Flow adds stray voices, mute the clip and build the sound in the edit: a ticking clock-like percussion that tightens through S01–S03, a hold at the stumble, and a warm piano chord resolving at S04, plus SFX from a licensed library.

**5. Publishing (text lives in the metadata, never in the video):**
- Title: "Never Judge the Man Who's Running | THE LAST FERRY".
- Description hook: "No dialogue. A bumped fruit stall, a whistle and a ferry about to leave. Watch to the end."
- Tags: chase thriller short, cinematic short film, suspense, moral story, realistic AI film.
- Cover frame: S03's wet-steps frame or S04's sunset handover.
