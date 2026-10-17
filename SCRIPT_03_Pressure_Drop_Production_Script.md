# SCRIPT 03 — Pressure Drop: Loadmaster Reyes' Dawn Delivery
### [TEMPLATE v3 (action edition) — Google Flow only · clips of 4/6/8/10 s · character & prop sheets → fixed aircraft plates → per-scene reference image → per-scene video · 9:16 STRICTLY for every image and video · global lock appended to every prompt · negative prompt on every video · no on-screen text · BGM + SFX only]

**Logline:** On a night cargo flight carrying a donor-organ case, the rear ramp seal tears at altitude. The captain dives, the loadmaster chases the sliding case across the cabin, and they land at sunrise to hand it to the waiting surgeon.
**Duration:** 0:30 | **Total Scenes:** 4 = 4 reference images = 4 videos (8 s + 4 s + 8 s + 10 s = 30 s, no trimming needed)
**Image generation:** Google Flow only — **aspect ratio 9:16 on every generation**
**Video generation:** Google Flow — one prompt per scene, exact clip length, own sound design and own negative prompt
**Dialogue/Audio rule:** NO speech, radio chatter or synthetic voice callouts; only instrumental BGM and diegetic SFX (alarms are plain electronic tones).

**Logic notes (why nothing contradicts itself):**
1. **One aircraft, one layout:** cockpit forward, cabin 12 m, ramp aft, case 5 m forward of the ramp. A layout map and five plates lock the geography.
2. **Screen and light locks:** in cabin side-views forward is always screen-left and the ramp screen-right; dawn light only from the starboard side, which is also where the tear is, so the slit's golden shaft is lit consistently.
3. **Physics:** a small 25 cm slit (not a hole) makes air flow *toward* the tear, so loose straps and the case slide aft, and Reyes is pulled aft with the flow on an overhead-track tether. The emergency dive brings the aircraft to breathable air, which is why the masks come off after landing.
4. **Cockpit insert:** S002 is a 4 s cutaway, so S003 starts from the last frame of S001 (the cabin state is unchanged).
5. **Safety logic:** the case never leaves the aircraft; no fire, no crash, no injury.

**Segment map**

| # | Segment | Scene | Time | Clip |
|---|---|---|---|---|
| 1 | The Tear | S001 | 0:00–0:08 | 8 s |
| 2 | The Dive | S002 | 0:08–0:12 | 4 s |
| 3 | The Slide | S003 | 0:12–0:20 | 8 s |
| 4 | Touchdown | S004 | 0:20–0:30 | 10 s |

---

## ⚠️ GLOBAL LOCK BLOCK — append this in full to the END of every single prompt below (Step 1, Step 2, every Step 3, every Step 4)

```
GLOBAL LOCK:
ASPECT RATIO — STRICTLY 9:16 vertical portrait (1080x1920) for every image and every video. Never 16:9, 1:1, 4:3 or 4:5; no letterbox, pillarbox or black bars. Compose natively for vertical and keep faces and key action inside the central safe area.
NO OTHER CHANGES — Generate exactly what this prompt describes and nothing more: one continuous shot with no cuts, no extra characters, no extra props, no extra events, no new locations, no text. Do not add, remove, rename or restyle anything that is not written here.
CONTINUITY — Loadmaster Reyes, Capt. Voss, F/O Lind, Dr. Okafor and the Organ Transport Case keep their exact faces, hair, skin tone, uniforms, colours and proportions from their saved reference sheets in every shot: no redesign, recolour, age change or scale drift.
FIXED AIRCRAFT — One single aircraft only, the twin-turboprop freighter "Freighter": a 12 m long, 3 m wide cylindrical cargo cabin with ribbed light-grey aluminium frames, quilted grey wall panels, brushed-aluminium floor with parallel tie-down rails and round floor rings, a cool white LED ceiling strip, a continuous overhead steel safety-tether track, red fold-down jump seats on both walls, small round windows on both walls, a grey bulkhead door at the FORWARD end leading to the two-seat cockpit (Capt. Voss left seat, F/O Lind right seat), and at the AFT end a closed rear cargo ramp door with a black rubber perimeter seal. The orange-and-white Organ Transport Case is strapped with two orange ratchet straps to floor rings at mid-cabin, 5 m forward of the ramp, with a yellow wall oxygen station on the starboard wall beside it. The seal tears only at the ramp door's upper STARBOARD corner (a 25 cm slit). Never rearrange, mirror, rebuild or replace any part of this layout.
SCREEN + LIGHT LOCK — In side-view cabin shots the camera stands against the PORT wall looking at the starboard wall: FORWARD (cockpit) is always screen-LEFT and AFT (ramp) always screen-RIGHT. Dawn light enters ONLY from the aircraft's STARBOARD (right) side, through the starboard windows and later the starboard tear, and finally the lowered ramp. Interior otherwise cool white LED; after the tear (Scene 1, 2.5 s) a red alarm light pulses and thin white condensation mist streams toward the tear. One colour grade throughout: cool steel-blue shadows, warm amber-gold dawn highlights, natural skin tones.
STYLE — Photorealistic cinematic live-action, 35mm anamorphic lens look, shallow depth of field on close shots, fine natural film grain, real material physics: straps whip, mist swirls, metal flexes, fabric moves naturally.
HARD RULES — No on-screen text, captions, subtitles, logos or watermarks; no lettering on uniforms, the aircraft, vehicles, instruments or the case (instrument dials stay blurred and unreadable). Faces are clear, natural and fully rendered, identical in every shot (invented fictional faces). No gore, no blood, no injury, no explosion, no fire, no crash.
ZERO AI ARTIFACTS — No morphing, warping, melting, flicker, extra or duplicated limbs/people/objects, floating objects, texture smearing, plastic skin, distorted hands or anatomy.
AUDIO — Instrumental cinematic BGM plus diegetic SFX only (engines, wind, electronic alarm tones, straps, metal, hydraulics). No dialogue, narration, radio chatter or synthetic voice callouts in any language; characters never speak (breathing and exertion only).
CAMERA — Smooth, physically plausible motion only; each shot opens with the camera motion the previous shot closed on.
```

**If Flow warns that a prompt is too long**, append this SHORT LOCK instead:

```
GLOBAL LOCK (short): STRICT 9:16 vertical, no black bars. One continuous shot; add nothing that is not written. Same faces, uniforms and orange-and-white case as the saved sheets. Same fixed freighter layout; cabin side-views: forward screen-left, ramp screen-right; dawn light only from the starboard side. Photorealistic cinematic 35mm look, steel-blue shadows, amber highlights. No text/logos, no gore, no fire, no crash. No speech or voice callouts: music + SFX only. No morphing, flicker, extra limbs or objects.
```

### NEGATIVE PROMPTS
Paste into Flow's negative-prompt field if it shows one; otherwise append to the end of the prompt as `AVOID: …`.

**NEG-IMG (all Step 1, 2 and 3 images):**
```
text, captions, subtitles, logos, watermarks, readable instrument numbers, letters on uniforms or aircraft, 16:9, 4:3, 1:1, horizontal frame, letterbox, black bars, cropped head, extra people, extra limbs, extra fingers, distorted hands, morphing, face change, identity drift, plastic skin, waxy skin, cartoon, anime, illustration, painting, CGI look, video-game look, low resolution, blur, noise, gore, blood, fire, flames, smoke, explosion, passenger seats, airline cabin, floating objects, duplicate objects, mirrored layout
```
**NEG-VID (master — every Step 4 video also adds its own scene-specific extras, printed under each video prompt):**
```
text, captions, subtitles, logos, watermarks, readable instrument numbers, letters on uniforms or aircraft, speech, talking, dialogue, narration, voice-over, radio chatter, synthetic voice callouts, lip movement, singing, humming, whispering, lyrics, choir, 16:9, 4:3, 1:1, horizontal frame, letterbox, black bars, pillarbox, cropped head, subject cut off, scene cut, jump cut, hard cut, zoom glitch, sudden lighting change, changing location, changed aircraft layout, mirrored layout, extra people, crowd, passengers, animals, fire, flames, engine fire, smoke trail, explosion, fireball, crash, aircraft breaking apart, gore, blood, injury, morphing, warping, melting, face change, identity drift, age change, extra limbs, extra fingers, fused fingers, distorted hands, duplicate case, duplicate characters, floating objects, flicker, jitter, frame stutter, texture smearing, plastic skin, waxy skin, cartoon, anime, illustration, painting, 3D render look, video-game look, uncanny face, changed uniform, changed case colour, case with text or symbols, light from the port side, night with no dawn glow, snow, harsh overexposure, big lens-flare blobs, time-lapse, unrequested slow motion
```

### Quick Flow settings
- Aspect ratio **9:16** on every image and every video. Audio **on** for videos. Generate 2–4 variations and keep the best.
- S001 and S002 = *Frames to video* from their reference images. S003 = *Frames to video* from the **exact last frame of S001**. S004 = from the **exact last frame of S003**. Each `S00X_Ref.png` is the visual target and the fallback start frame.
- Attach the listed character sheets and plates as ingredients wherever Flow allows it.

---

# STEP 1 — CHARACTER & PROP REFERENCE IMAGES (Google Flow — image generation ONLY, 9:16)

### 1A. Loadmaster ("Reyes")
**Portrait Image Prompt — Google Flow:**
Vertical 9:16 full-body standing portrait of Loadmaster Kade Reyes, a lean, athletic air-cargo loadmaster in his early 30s, facing the camera in a neutral relaxed pose, with a clearly visible, fully detailed face: warm medium-brown skin, short black curly hair, a neatly trimmed short black beard, dark brown eyes, strong straight brows, a small scar on the chin, a focused, steady, quietly confident expression. Charcoal-grey flight coverall with sleeves pushed to the elbows, a bright orange chest-and-thigh safety harness with a short orange safety tether and steel carabiner clipped to the chest ring and a second spare steel carabiner on the left hip, black fingerless-palm work gloves, grey ear-defender headset resting around the neck, black lace-up boots, a blank grey name tape (no letters). Worn, oil-streaked fabrics. Neutral grey seamless background, soft key light from upper left, macro detail on skin, harness webbing, stitching and carabiner metal. An invented fictional face. Locked reference design.
**Save as:** `Reyes_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Reyes_Portrait.png` as exact reference, generate ONE vertical 9:16 character sheet in four rows: row 1 FRONT and REAR full-body; row 2 LEFT SIDE and RIGHT SIDE; row 3 TOP-DOWN and BOTTOM/UNDERCARRIAGE (boots and ground contact); row 4 three close-up face panels (front, left profile, right profile) locking the face. Neutral grey seamless background, matched lighting and scale, neutral standing pose in every panel, no labels or text.
**Save as:** `Reyes_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S001, S003, S004.

### 1B. Captain ("Capt. Voss")
**Portrait Image Prompt — Google Flow:**
Vertical 9:16 waist-up portrait of Capt. Mara Voss, a composed senior cargo pilot in her early 50s, facing the camera in a neutral pose, with a clearly visible, fully detailed face: fair skin with fine lines at the eyes, grey-blue eyes, a short silver-streaked auburn bob, a strong jaw, a calm, commanding expression. Crisp white pilot shirt with navy epaulettes carrying four gold stripes, a navy tie, a slim black aviation headset worn with the boom mic pushed up, a plain silver wristwatch. Neutral grey seamless background, soft key light from upper left, macro detail on skin, fabric weave and gold braid. An invented fictional face. Locked reference design.
**Save as:** `Voss_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Voss_Portrait.png` as exact reference, generate ONE vertical 9:16 sheet in three rows: row 1 FRONT and REAR waist-up; row 2 LEFT SIDE and RIGHT SIDE waist-up; row 3 three close-up face panels (front, left profile, right profile) locking the face. Neutral grey seamless background, matched lighting and scale, no labels or text.
**Save as:** `Voss_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S002, S004.

### 1C. First Officer ("F/O Lind")
**Portrait Image Prompt — Google Flow:**
Vertical 9:16 waist-up portrait of First Officer Tomas Lind, a sharp, alert co-pilot in his late 20s, facing the camera in a neutral pose, with a clearly visible, fully detailed face: pale skin with light freckles, green eyes, short sandy-blond hair, a clean-shaven square face, a focused, slightly tense expression. Crisp white pilot shirt with navy epaulettes carrying three gold stripes, a navy tie, a slim black aviation headset with the boom mic pushed up. Neutral grey seamless background, soft key light from upper left, macro detail on skin and fabric. An invented fictional face. Locked reference design.
**Save as:** `Lind_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Lind_Portrait.png` as exact reference, generate ONE vertical 9:16 sheet in three rows: row 1 FRONT and REAR waist-up; row 2 LEFT SIDE and RIGHT SIDE waist-up; row 3 three close-up face panels (front, left profile, right profile) locking the face. Neutral grey seamless background, matched lighting and scale, no labels or text.
**Save as:** `Lind_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S002.

### 1D. Transplant Surgeon ("Dr. Okafor")
**Portrait Image Prompt — Google Flow:**
Vertical 9:16 full-body standing portrait of Dr. Imani Okafor, a determined transplant surgeon in her early 40s, facing the camera in a neutral pose, with a clearly visible, fully detailed face: deep brown skin, short natural black hair, warm dark-brown eyes, high cheekbones, a hopeful, urgent expression. Teal surgical scrubs under an open charcoal-grey fleece jacket, a blue surgical cap pushed back on her head, white running shoes, blue nitrile gloves in her left hand, a blank white ID card on a lanyard (no text). Neutral grey seamless background, soft key light from upper left, macro detail on skin and fabric weave. An invented fictional face. Locked reference design.
**Save as:** `Okafor_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Okafor_Portrait.png` as exact reference, generate ONE vertical 9:16 character sheet in four rows: row 1 FRONT and REAR full-body; row 2 LEFT SIDE and RIGHT SIDE; row 3 TOP-DOWN and BOTTOM/UNDERCARRIAGE (shoes and ground contact); row 4 three close-up face panels (front, left profile, right profile) locking the face. Neutral grey seamless background, matched lighting and scale, no labels or text.
**Save as:** `Okafor_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S004.

### 1E. Organ Transport Case (prop, "the Case")
**Portrait Image Prompt — Google Flow:**
Vertical 9:16 product shot of a rugged hard-shell medical transport case, 60 x 40 x 40 cm, two-tone orange lower shell and white lid, two chrome latches on the front, a black rubber top carry handle, a small round green LED status light on the top-right of the lid that is lit, scuffed corners, a steel carabiner attached to the handle, absolutely no text, labels, symbols or logos. Three-quarter front view on a neutral grey surface, soft key light from upper left, macro detail on latch metal, rubber grip and scuffs. Locked reference design.
**Save as:** `Case_Portrait.png`
**6-Angle Turnaround Image Prompt — Google Flow:**
Using the saved `Case_Portrait.png` as exact reference, generate ONE vertical 9:16 sheet in three rows of two: FRONT and REAR; LEFT SIDE and RIGHT SIDE; TOP-DOWN and BOTTOM. Same colours, same green LED position, same handle and carabiner in every panel, neutral grey background, matched lighting and scale, no labels or text.
**Save as:** `Case_6Angle.png`
**Usage note:** Attach both files to every scene where this appears: S001, S003, S004.

---

# STEP 2 — FIXED AIRCRAFT PLATES (Google Flow — image generation ONLY, 9:16)

**Layout map (top-down, for your reference — not an image prompt):**

```
                 STARBOARD (right) side: dawn light + the tear
  ┌──────────┬───────────────────────────────────────────────┬────┐
  │ COCKPIT  │ bulkhead   CABIN 12 m                  RAMP DOOR│ ◀ tear at
  │ Voss (L) │ door       [Case]──5 m──▶                 (aft) │   upper
  │ Lind (R) │            yellow O2 station (stbd wall)        │   starboard
  └──────────┴───────────────────────────────────────────────┴────┘   corner
   FORWARD ◀──────────────────────────────────────────────▶ AFT
  Camera (side views): against the PORT wall.  Screen-left = FORWARD, screen-right = AFT.
```

| Plate | Name | Save as | Used in |
|---|---|---|---|
| 2A | Freighter cabin — side view, intact | `Cabin_A_Intact.png` | S001 |
| 2B | Ramp door — seal tear (close view) | `Cabin_B_RampTear.png` | S001 (end), S003, S004 |
| 2C | Cockpit | `Cabin_C_Cockpit.png` | S002 |
| 2D | Freighter cabin — side view, damaged state | `Cabin_D_Damaged.png` | S003, S004 |
| 2E | Runway at sunrise, seen through the lowered ramp | `Cabin_E_RampOpen.png` | S004 |

### 2A. Freighter cabin — side view, intact
**Environment Image Prompt — Google Flow:**
Using the saved Case sheet for the case: vertical 9:16 photorealistic side-on view of a 12 m long, 3 m wide cylindrical cargo cabin of a twin-turboprop freighter: ribbed light-grey aluminium frames, quilted grey wall panels, a brushed-aluminium floor with parallel tie-down rails and round floor rings, a cool white LED strip along the ceiling, a continuous overhead steel safety-tether track, red fold-down jump seats on both walls, small round windows on both walls with a warm dawn glow in the starboard windows, a grey bulkhead door at the forward end, and at the aft end a closed rear cargo ramp door with a black rubber perimeter seal, the camera low at hip height against the PORT wall looking at the starboard wall, FORWARD at screen-left, the closed ramp door at screen-right (no people). The orange-and-white transport case is strapped with two orange ratchet straps to floor rings at mid-cabin, its green LED lit; a yellow wall oxygen station with a clear mask is on the starboard wall beside it; no other cargo. Calm pre-event mood, steady cool LED light with golden dawn glow in the starboard windows. Locked environment layout.
**Save as:** `Cabin_A_Intact.png`

### 2B. Ramp door — seal tear (close view)
**Environment Image Prompt — Google Flow:**
Vertical 9:16 photorealistic close view of the closed rear cargo ramp door at the aft end of the freighter cabin (no people): a 25 cm long slit torn in the black rubber perimeter seal at the ramp door's upper STARBOARD corner, a narrow golden shaft of dawn light streaming through it across the floor, thin white condensation mist streaking toward the slit, loose orange strap ends fluttering toward it, a red alarm light pulsing on the ceiling. Locked environment layout.
**Save as:** `Cabin_B_RampTear.png`

### 2C. Cockpit
**Environment Image Prompt — Google Flow:**
Vertical 9:16 photorealistic view from behind and between the two seats of the freighter cockpit looking forward (no people): two seats (left for the captain, right for the first officer), a glareshield, rows of switches, two yokes, blurred unreadable instrument displays glowing softly, a large curved windscreen showing a deep-blue pre-dawn sky above a pale gold glow on the STARBOARD (right) horizon over a bank of cloud, a red master-warning light on the glareshield (unlit). Cool instrument glow, calm mood. Locked environment layout.
**Save as:** `Cabin_C_Cockpit.png`

### 2D. Freighter cabin — side view, damaged state
**Environment Image Prompt — Google Flow:**
Using the saved Case sheet for the case: vertical 9:16 photorealistic side-on view of the same cabin as `Cabin_A_Intact.png` (same layout, camera against the PORT wall, FORWARD at screen-left, ramp at screen-right) but in the damaged state (no people): a 25 cm slit in the ramp door seal at its upper STARBOARD corner at the far right with a golden shaft of dawn light, thin white mist streaming toward it, loose orange straps streaming toward it, a red alarm light pulsing on the ceiling, the transport case still strapped at mid-cabin with its green LED lit. Tense mood. Locked environment layout.
**Save as:** `Cabin_D_Damaged.png`

### 2E. Runway at sunrise, seen through the lowered ramp
**Environment Image Prompt — Google Flow:**
Vertical 9:16 photorealistic view from inside the freighter cabin looking aft out of the fully lowered rear ramp (no people): a long empty runway stretching away under a clear gold-pink sunrise sky, the low sun at the right side of the frame, flat warm light flooding up the ramp into the cabin, one plain white ambulance (no text, no markings) with blue emergency lights flashing about 40 m beyond the ramp. Calm, relieved mood. Locked environment layout.
**Save as:** `Cabin_E_RampOpen.png`

---

# STEP 3 & STEP 4 — SCENES (clips of 4, 8 and 10 seconds)

**How each scene is shaped:** Header → **Story beat** → **Entry state** → Step 3 Ingredients → Step 3 Reference Image Prompt → Step 4 Ingredients → Video Prompt (exact clip length, in-clip second marks where `0s` = clip start) → **Negative prompt (video)** → Sound → **Exit state** → Cut→.
Append the GLOBAL LOCK BLOCK to every Step 3 and Step 4 prompt. In Step 4, paste the **Sound** text at the end under `AUDIO DIRECTION:` (the PASTE-READY file already does this).

### Segment 1 — The Tear | 0:00–0:08

**S001 — The Tear | 0:00–0:08 (8s)**
Story beat: Calm cargo run before dawn. A hard bump, a bang, and the ramp seal tears; Reyes grabs oxygen.
Entry state: Reyes crouched beside the case at mid-cabin tightening a strap; calm cabin.
Step 3 Ingredients: Subject Reference Images: `Reyes_Portrait.png`, `Reyes_6Angle.png`, `Case_Portrait.png`, `Case_6Angle.png` · Environment Reference Images: `Cabin_A_Intact.png`, `Cabin_B_RampTear.png` · Scene Continuity Reference: none (first scene)
Step 3 — Reference Image Prompt (Google Flow, 9:16):
Vertical 9:16 cinematic side-view inside the cargo cabin of the freighter (layout exactly as the saved Cabin_A environment reference), camera low at hip height against the port wall, forward screen-left, closed ramp door at screen-right. Loadmaster Reyes (use the character reference) crouches beside the orange-and-white transport case at mid-cabin, tightening an orange ratchet strap with his right hand, face in clear three-quarter view toward the camera, calm and focused; the case's green LED is lit; the yellow oxygen station on the starboard wall behind him; golden dawn glow in the starboard windows, cool white LED light, quiet tension, photorealistic.
Save as: `S001_Ref.png`
Step 4 Ingredients: Starting Frame: `S001_Ref.png` · Also attach: `Reyes_Portrait.png`, `Reyes_6Angle.png`, `Case_Portrait.png`, `Cabin_A_Intact.png`, `Cabin_B_RampTear.png`
Video Prompt (Google Flow, 8s, 9:16):
Vertical 9:16, cinematic, no text, no subtitles. I2V from `S001_Ref.png`, one continuous shot, 8 seconds, camera low against the port wall, subtle handheld drift. 0–1.5s: Reyes ratchets the orange strap one more click and taps the case's green LED; steady engine hum, calm. 1.5–2.5s: one hard bump shakes the cabin; the straps jump. At 2.5s a loud metallic BANG: the rubber seal of the ramp door tears at its upper starboard corner (screen-right, far side); a narrow golden shaft of dawn light and a streak of white mist shoot through the slit; air starts to whistle; loose orange strap ends flutter toward it. 3–4.5s: a red alarm light begins pulsing on the ceiling; Reyes snaps his head toward the tear. 4.5–6s: he lunges to the starboard wall, rips the clear mask from the yellow oxygen station. 6–7.5s: he pulls the mask over his nose and mouth and grabs the overhead rail beside the case with his left hand, his tether sliding on the overhead track. 7–8s: he braces, mist streaming aft across him. Last frame: Reyes masked, left hand gripping the overhead rail beside the strapped case, face visible toward camera, red alarm pulsing, golden slit of light at far right. No speech, narration, whispering, radio chatter or lip movement: characters never speak. Audio is music and sound effects only.
Save as: `S001_Video.mp4` · also save the final frame as `S001_LastFrame.png` (start frame for the next scene)
Negative prompt (video): NEG-VID master + tear on the port side, tear at the wrong corner, large hole in the fuselage, aircraft breaking apart, explosion, fire, smoke, people sucked out, Reyes thrown across the cabin, passengers, other crew, Reyes speaking, mask missing, case moving before 2.5 s.
Sound (BGM+SFX only, no voice or speech): BGM: low pulsing synth bass drone with soft ticking from 0s; a violent low-brass BRAAM with sub drop at 2.5s; tight rising string tremolo from 3s; a single heartbeat thump at 7s. SFX: steady twin-turboprop hum and cabin air, ratchet clicks at 1s, a dull hard bump at 1.5s, a loud metallic bang at 2.5s, rising air whistle from 2.5s, electronic alarm tone (one beep per second, no voice) from 3s, mask-pull plastic crack at 5s, oxygen hiss at 6s, loose straps flapping.
Exit state: Reyes masked, left hand on the overhead rail beside the strapped case, face toward camera, red alarm pulsing, golden slit at far right, mist streaming aft.
Cut→S002: hard cut to the cockpit, matching the rising tension and the alarm tone.

### Segment 2 — The Dive | 0:08–0:12

**S002 — The Dive | 0:08–0:12 (4s)**
Story beat: In the cockpit the warnings flash; Capt. Voss masks up and puts the nose down.
Entry state: Calm cockpit, red warning unlit, pale gold glow on the starboard horizon.
Step 3 Ingredients: Subject Reference Images: `Voss_Portrait.png`, `Voss_6Angle.png`, `Lind_Portrait.png`, `Lind_6Angle.png` · Environment Reference Images: `Cabin_C_Cockpit.png` · Scene Continuity Reference: `S001_Ref.png` (colour grade and alarm tone only; do NOT reuse its location)
Step 3 — Reference Image Prompt (Google Flow, 9:16):
Vertical 9:16 cinematic shot in the freighter cockpit (layout exactly as the saved Cabin_C environment reference), camera behind and slightly right of the seats at a three-quarter angle: Capt. Voss (use the character reference) in the left seat, her face in clear profile looking forward, F/O Lind (use the character reference) in the right seat, his face partly visible, both in white shirts and headsets, hands near the controls, calm; the windscreen shows a deep-blue sky and a pale gold glow on the starboard horizon; the red master-warning light is unlit; photorealistic.
Save as: `S002_Ref.png`
Step 4 Ingredients: Starting Frame: `S002_Ref.png` · Also attach: `Voss_Portrait.png`, `Voss_6Angle.png`, `Lind_Portrait.png`, `Lind_6Angle.png`, `Cabin_C_Cockpit.png`
Video Prompt (Google Flow, 4s, 9:16):
Vertical 9:16, cinematic, no text, no subtitles. I2V from `S002_Ref.png`, one continuous shot, 4 seconds. 0–1s: the red master-warning light slams on and pulses; both pilots' eyes snap to the panel. 1–2s: Capt. Voss pulls her oxygen mask over her face with one hand while F/O Lind flicks a guarded switch with his right hand. 2–4s: Voss pushes the yoke forward with both hands; the nose drops, the horizon tilts, clouds rush up past the windscreen and the pale gold glow slides across the starboard side. Last frame: Voss masked with both hands on the yoke, face lit by pulsing red and gold, the camera pushing between the seats. No speech, narration, whispering, radio chatter or lip movement: characters never speak. Audio is music and sound effects only.
Save as: `S002_Video.mp4` · also save the final frame as `S002_LastFrame.png` (start frame for the next scene)
Negative prompt (video): NEG-VID master + readable instrument numbers, pilots speaking or shouting, radio chatter, smoke in the cockpit, windscreen cracked, fire, fireball, crash, ground visible too close, Lind in the left seat, Voss in the right seat.
Sound (BGM+SFX only, no voice or speech): BGM: the string tremolo keeps climbing into a hard rhythmic pulse at 2s. SFX: continuous electronic master-warning chime (no voice), oxygen mask hiss, switch clack at 1.5s, engines rising in pitch, rushing wind over the windscreen building from 2s, airframe creak.
Exit state: Voss masked, both hands on the yoke, nose pitched down, camera pushing between the seats.
Cut→S003: hard cut back to the cabin, continuing the nose-down tilt.

### Segment 3 — The Slide | 0:12–0:20

**S003 — The Slide | 0:12–0:20 (8s)**
Story beat: During the dive a strap snaps; the case slides toward the tear and Reyes dives after it.
Entry state: Same as S001's exit: Reyes masked, hand on the overhead rail beside the strapped case, red alarm pulsing.
Step 3 Ingredients: Subject Reference Images: `Reyes_Portrait.png`, `Reyes_6Angle.png`, `Case_Portrait.png`, `Case_6Angle.png` · Environment Reference Images: `Cabin_D_Damaged.png`, `Cabin_B_RampTear.png` · Scene Continuity Reference: last frame of the S001 clip (fallback: `S003_Ref.png`) — the cockpit insert S002 does not change the cabin
Step 3 — Reference Image Prompt (Google Flow, 9:16):
Vertical 9:16 cinematic side-view inside the damaged cargo cabin (layout exactly as the saved Cabin_D environment reference), camera low against the port wall, forward screen-left, ramp screen-right. Loadmaster Reyes (use the character reference) wears an oxygen mask and grips the overhead rail with his left hand beside the orange-and-white transport case strapped at mid-cabin, face toward camera, braced; a red alarm light pulsing; thin white mist and loose orange straps streaming toward the golden slit of light at far right; his orange tether clipped to the overhead track; photorealistic, tense.
Save as: `S003_Ref.png`
Step 4 Ingredients: Starting Frame: the exact last frame of the S001 clip (fallback: `S003_Ref.png`) · Also attach: `Reyes_Portrait.png`, `Reyes_6Angle.png`, `Case_Portrait.png`, `Case_6Angle.png`, `Cabin_D_Damaged.png`, `Cabin_B_RampTear.png`
Video Prompt (Google Flow, 8s, 9:16):
Vertical 9:16, cinematic, no text, no subtitles. Image-to-video from the start frame, one continuous shot, 8 seconds, camera low against the port wall tracking left-to-right with him, controlled handheld shake. 0–1s: the cabin pitches nose-down with the dive; the mist and straps stream harder toward the tear. At 1s one orange ratchet strap snaps with a crack, the other strap whips free, and the orange-and-white case lurches and skids aft (screen-right) along the floor rails toward the slit. 1–3.5s: Reyes releases the rail and launches after it, his tether paying out along the overhead track, mist swirling around him. 3.5–5.5s: he dives and slides on his chest, grabs the case's carry handle with his right hand just 1 m short of the tear, and the case stops. 5.5–7s: with his left hand he snaps the spare carabiner from his hip onto the nearest floor ring and the case handle; his tether goes taut. 7–8s: he holds on, the golden shaft of light through the slit falling across his masked face, the whistle softening as the aircraft descends. Last frame: Reyes lying prone near the ramp, right hand on the case handle clipped to the floor ring, masked face toward camera, tether taut, golden slit of light beside him. No speech, narration, whispering, radio chatter or lip movement: characters never speak. Audio is music and sound effects only.
Save as: `S003_Video.mp4` · also save the final frame as `S003_LastFrame.png` (start frame for the next scene)
Negative prompt (video): NEG-VID master + case sucked out, case falling out of the aircraft, Reyes pulled out, the slit widening into a hole, Reyes unclipped from the track, other people, case changing colour, case with text, fire, explosion, slow motion.
Sound (BGM+SFX only, no voice or speech): BGM: hard taiko and war-drum ostinato at 140 BPM from 1s with low-string rhythmic figures and a rising riser; the beat strips back to a single heartbeat at 5.5s; a held, shimmering string tone from 7s. SFX: dive whoosh at 0s, loud strap crack at 1s, metal case scraping along the floor rails 1–3.5s, tether whirring along the overhead track, pounding boots, ragged breath through the mask, a body-slide thud at 4s, carabiner click at 6s, air whistle softening from 7s.
Exit state: Reyes prone near the ramp, right hand on the case handle clipped to a floor ring, tether taut, masked face toward camera, golden slit of light beside him; camera low.
Cut→S004: continuous — same pose, same framing; the touchdown jolt begins right after the cut.

### Segment 4 — Touchdown | 0:20–0:30

**S004 — Touchdown | 0:20–0:30 (10s)**
Story beat: They land at sunrise. The ramp lowers and Dr. Okafor receives the case.
Entry state: Same as S003's exit: Reyes prone near the ramp, case clipped to the floor ring.
Step 3 Ingredients: Subject Reference Images: `Reyes_Portrait.png`, `Reyes_6Angle.png`, `Case_Portrait.png`, `Case_6Angle.png`, `Okafor_Portrait.png`, `Okafor_6Angle.png`, `Voss_Portrait.png`, `Voss_6Angle.png` · Environment Reference Images: `Cabin_D_Damaged.png`, `Cabin_E_RampOpen.png` · Scene Continuity Reference: last frame of the S003 clip (fallback: `S004_Ref.png`)
Step 3 — Reference Image Prompt (Google Flow, 9:16):
Vertical 9:16 cinematic side-view inside the damaged cargo cabin (layout exactly as the saved Cabin_D environment reference), camera low against the port wall, forward screen-left, ramp at screen-right. Loadmaster Reyes (use the character reference) lies prone near the ramp wearing his oxygen mask, his right hand on the handle of the orange-and-white transport case, which is clipped to a floor ring by a steel carabiner, his orange tether taut to the overhead track, his face toward the camera; a golden shaft of dawn light from the slit beside him; thin mist, red alarm pulsing; photorealistic.
Save as: `S004_Ref.png`
Step 4 Ingredients: Starting Frame: the exact last frame of the S003 clip (fallback: `S004_Ref.png`) · Also attach: `Reyes_Portrait.png`, `Reyes_6Angle.png`, `Case_Portrait.png`, `Okafor_Portrait.png`, `Okafor_6Angle.png`, `Voss_Portrait.png`, `Voss_6Angle.png`, `Cabin_D_Damaged.png`, `Cabin_E_RampOpen.png`
Video Prompt (Google Flow, 10s, 9:16):
Vertical 9:16, cinematic, no text, no subtitles. Image-to-video from the start frame, one continuous shot, 10 seconds, camera low against the port wall. 0–1.5s: the aircraft touches down hard; the whole cabin slams and shudders, tyres screech, the dangling oxygen mask and straps swing; Reyes braces over the case. 1.5–3.5s: reverse-thrust roar and heavy braking, the mist thins and the air whistle fades. At 3.5s the aircraft stops and the cabin goes still. 3.5–5s: Reyes pulls off his mask, breathes out hard, checks the case; its green LED is still lit. 5–7s: a hydraulic whine; the ramp lowers at screen-right and warm golden sunrise floods the cabin, with the runway and a white ambulance with flashing blue lights beyond. 7–8.5s: Dr. Okafor runs up the ramp; Reyes unclips the carabiner and lifts the case, and she takes it in both hands, her hopeful gaze meeting his. 8.5–10s: Capt. Voss steps through the forward bulkhead door at screen-left and gives Reyes a small nod; Reyes sits back against the wall, looks toward the sunrise and smiles with relief as the camera slowly pulls back to a wide shot of the cabin and the open ramp; the image fades smoothly to black over the last 0.7s. No speech, narration, whispering, radio chatter or lip movement: characters never speak. Audio is music and sound effects only.
Save as: `S004_Video.mp4`
Negative prompt (video): NEG-VID master + aircraft crashing or skidding off the runway, fire, smoke, gear collapse, additional paramedics, stretcher, passengers, text or markings on the ambulance, Okafor snatching the case roughly, case dropped, case with text, sun on the wrong side, no fade to black, 'THE END' title card.
Sound (BGM+SFX only, no voice or speech): BGM: silence at the touchdown impact (0s) except natural sound; the drums return briefly 1.5–3.5s then drop out at 3.5s; at 5s a warm solo French horn plays the four-note motif (A–C–E–D) over soft strings, swelling at 7s into a resolved A-major chord that sustains and decays to silence at 10s. SFX: hard touchdown thud and tyre squeal at 0s, reverse-thrust roar 1–3.5s, engine spool-down, heavy breathing, mask pull at 4s, hydraulic ramp whine 5–6.5s, ramp touching down with a soft thump at 6.7s, distant sirens, running footsteps on the ramp at 7.2s, carabiner click at 7.7s, a soft exhale at 9s.
Exit state: Fade to black.
Cut→End of video (fade to black).

---

# SOUND DESIGN MASTER (BGM · SFX · mix)

**Why this exists:** each Flow clip generates its own audio, so the music can restart at every cut. For a seamless Short, keep each clip's **SFX**, and lay the one continuous **master track** below underneath; mute the clips' own music if it clashes.

**Master BGM prompt (any AI music generator — 30 s, instrumental):**
```
Cinematic instrumental thriller underscore, exactly 30 seconds, no vocals, no choir, no lyrics. Four continuous movements. 0:00–0:08 'The Tear': low pulsing synth bass drone with soft ticking, tense and quiet, then a violent low-brass braam with sub drop at 0:02.5 and tight rising string tremolo. 0:08–0:12 'The Dive': the tremolo locks into a hard rhythmic pulse that climbs. 0:12–0:20 'The Slide': taiko and war-drum ostinato at 140 BPM with low-string rhythmic figures and a rising riser, stripping back to a single heartbeat at 0:17.5, then a shimmering held string tone. 0:20–0:30 'Touchdown': near-silence at the impact, brief drums to 0:23.5, then a warm solo French horn plays a four-note motif (A–C–E–D) over soft strings at 0:25, swelling at 0:27 into a resolved A-major chord that sustains and decays to silence at 0:30.
```

**Cue sheet:**

| Time | Music | SFX |
|---|---|---|
| 0:00–0:02 | Bass drone + soft ticking | Turboprop hum, ratchet clicks, calm cabin air |
| 0:01.5 | Ticking tightens | Dull hard bump |
| 0:02.5 | BRAAM + sub drop | Metallic BANG, air whistle begins |
| 0:03–0:06 | Rising string tremolo | Electronic alarm beeps (no voice), mask rip, oxygen hiss, straps flapping |
| 0:07 | Single heartbeat thump | Mist rush |
| 0:08–0:10 | Tremolo → rhythmic pulse | Master-warning chime, mask hiss, switch clack |
| 0:10–0:12 | Pulse climbs | Engines rising, wind over windscreen |
| 0:12–0:13 | Drums start at 0:13 | Dive whoosh, loud strap crack (0:13) |
| 0:13–0:15.5 | Taiko ostinato 140 BPM, riser | Case scraping on rails, tether whirring, pounding boots, breath |
| 0:15.5–0:17.5 | Beat strips to a heartbeat at 0:17.5 | Body-slide thud (0:16), carabiner click (0:18) |
| 0:19–0:20 | Held shimmering string tone | Whistle softens |
| 0:20 | Silence except natural sound | Touchdown thud, tyre squeal |
| 0:21.5–0:23.5 | Brief drums | Reverse-thrust roar, braking |
| 0:23.5 | Music drops out | Engine spool-down, silence, heavy breathing |
| 0:25–0:26.5 | Solo French horn motif enters | Mask pull, hydraulic ramp whine |
| 0:26.7–0:28 | Strings swell | Ramp thump, distant sirens, running boots, carabiner click |
| 0:28–0:30 | Resolved A-major chord decays to silence | Soft exhale; everything fades with the picture |

**Mix guide:** SFX stem –6 dB peak, master BGM –14 dB under SFX, the braam, strap crack, touchdown and collapse-style hits allowed to peak at –3 dB; 6-frame audio crossfades at every cut; target loudness –14 LUFS for YouTube Shorts / Reels.

# QC CHECKLIST (run on every generated clip before moving on)

- [ ] Frame is 9:16, no black bars, no readable text anywhere (instrument dials blurred).
- [ ] Faces and uniforms match the sheets; Reyes' orange harness, tether and hip carabiner unchanged; the case is orange-and-white with a black handle and green LED.
- [ ] Side-view cabin shots: forward screen-left, ramp screen-right; dawn light only from the starboard side.
- [ ] S001: nothing moves until the bump (1.5 s); the tear is a 25 cm slit at the upper STARBOARD corner of the ramp door, not a hole.
- [ ] S002: Voss in the LEFT seat, Lind in the RIGHT seat; no fire, no smoke.
- [ ] S003: strap snaps → case skids aft → Reyes dives → grabs the handle → clips to the floor ring; the case never leaves the aircraft.
- [ ] S004: safe landing, ramp lowers, Okafor takes the case, Voss gives a nod, fade to black.
- [ ] The last frame of each clip matches the entry state of the next scene (S003 starts from the last frame of S001, because S002 is a cockpit insert).

# SHORTS PUBLISHING (optional)

- **Title ideas:** "The Seal Tore Mid-Air. He Still Saved the Delivery" · "30 Seconds Over the Clouds"
- **Description:** A loadmaster chases a medical case across a depressurizing cargo plane to get it to a waiting surgeon by sunrise. AI-generated cinematic short.
- **Hashtags:** #shorts #aviation #action #cinematic #aivideo #googleflow #veo
- Keep the AI-generated / altered-content disclosure switched on when you upload.
