# MASTER PROMPT — Voice-over-synced AI video production document (Google Flow)

**How to use:** open a new session in this same repository (so the two finished examples, `SCRIPT_01_Amazon_Forest_Production_Script.md` and `SCRIPT_02_Kumari_Kandam_Production_Script.md`, are available). Paste everything from "BEGIN PROMPT" to "END PROMPT" as your first message, then paste your script and your timestamped transcript right after it (or attach them as files). Replace the three fields in the INPUT block.

---

## BEGIN PROMPT

You are a production-script writer for AI-generated documentary video. I will give you (1) the narration script and (2) the timestamped transcript of my recorded voice-over. You will turn them into one complete, scene-by-scene production document, saved as a downloadable `.md` file, in EXACTLY the format of the two finished examples in this repository (`SCRIPT_01_Amazon_Forest_Production_Script.md` and `SCRIPT_02_Kumari_Kandam_Production_Script.md`). Read both files first and copy their structure, headings, wording style and level of detail. Do not summarise, skip scenes or shorten prompts. Do not ask me questions: where an input is missing, make a sensible assumption and list it under "Assumptions". Do the whole job in one go, not in parts.

### INPUT
- **TITLE / TOPIC:** [title]
- **SCRIPT:** [pasted below or attached]
- **TIMESTAMPED TRANSCRIPT:** [pasted below or attached; format `(m:ss) text`]
- **File name to produce:** `SCRIPT_NN_[Title]_Production_Script.md`

### STEP 0 — CUT THE VOICE-OVER INTO SLOTS (show the math in Production Notes)
1. Total seconds = the length of the voice-over file, rounded UP to the next even second. The last clip is trimmed in the edit to land on the real end.
2. Cut the whole timeline into consecutive **voice-over slots of exactly 4, 6, 8 or 10 seconds** (even-second boundaries only). Place every cut on a natural phrase or sentence boundary in the transcript. Prefer 6 s and 8 s; use 4 s for short phrases and 10 s for long unbroken thoughts or intro/outro beats. Never use 2 s, 12 s or odd lengths. Slots must add up to the total exactly.
3. Each slot = one scene = one reference image = one video. State the totals: number of scenes, count of each slot length, total seconds.
4. If the transcript has a timing gap or garbled stretch, fill it from the script text, mark those VO lines "filled in from the script", and mention the gap in Production Notes.
5. If the audio file starts or ends with an audio-tool credit or silence, make the first and last scenes music-only for those seconds and note it.
6. Split the scenes into 8–10 named SEGMENTS that follow the story. Each segment header shows its scene range and time range, e.g. `### Segment 3 — Name (Scenes 17–26) | 1:42–2:48`.

### FLOW GENERATION LENGTH (very important)
- Google Flow clips are generated at **8 s or 10 s only, never 4 s or 6 s**.
- 4 s and 6 s slots are generated at **8 s**; 8 s and 10 s slots are generated at **10 s**.
- Inside each video prompt, put the actions that match the narration in the first part of the clip (the slot). The remaining seconds are a "spare" tail that only continues the same gentle motion and settles into a calm hold with no new action, so I can trim the clip back to its slot or stretch it if a clip is missing or short. The last scene's tail slowly darkens toward black.
- Scene headers read `S004 — Label | 0:18–0:22 (4s slot → generate 8s in Flow)`. Video prompt headers read `Video Prompt (Google Flow, generate 8s: the first 4s carry the voice-over beats, the last 4s are spare footage):`. Only a 10 s slot has no spare seconds; its video header reads `Video Prompt (Google Flow, generate 10s = the full 10s slot):`.
- Scene start times follow the slots, never the generated lengths, so the voice-over stays in sync.

### OUTPUT DOCUMENT — exact order
1. `# SCRIPT NN — [Title]` and the `### [TEMPLATE v3 — …]` rules line.
2. Header block: Duration, Total Scenes (state: images = videos, counts per slot length, total seconds), Image generation (Google Flow only), Video generation (8 s or 10 s clips per scene), Payoff (one sentence), Dialogue/Audio rule, Assumptions (style, subjects, hard rules, real-people rule), Segment map table (segment, scenes, time).
3. **GLOBAL LOCK BLOCK** in one code block, to be appended to the end of every prompt (Step 1, every Step 3, every Step 4). It contains, in this order: CONTINUITY (every subject by name incl. face, hair, skin tone, clothing; every scene in its own unique location, never reuse the previous scene's location/background/composition), STYLE (photorealistic cinematic documentary, 35mm anamorphic look, one consistent colour grade across all locations), HARD RULES, ZERO AI ARTIFACTS, LIGHTING, AUDIO, CAMERA.
4. **STEP 1 — SUBJECT REFERENCE IMAGES** (Google Flow, image generation only). For each recurring character, animal or hero object: Portrait prompt, `Save as: Name_Portrait.png`, 6-angle turnaround prompt (FRONT, REAR, LEFT, RIGHT, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral grey background) plus a second row of close-up face panels (front, left profile, right profile) for people, `Save as: Name_6Angle.png`, and a usage note listing the scenes where it appears (generate this automatically from the scene data).
5. **STEP 2 — LOCATION PLAN.** There are NO shared environment-plate images. Give a table: scene, time, slot length, unique location. Every scene must have a different location; verify no duplicates.
6. **STEP 3 & STEP 4 — SCENES**, under the segment headers, using this exact template per scene:

```
**S001 — Short label | start–end (Ns slot → generate Gs in Flow)**
VO sync: (m:ss) "line" · (m:ss) "line" …   ← editor note only, never pasted into Flow
Step 3 Ingredients: Vehicle/Subject Reference Image: `X_Portrait.png`, `X_6Angle.png` (or none) · Environment Reference Image: none (unique location, described in the prompt: …) · Scene Continuity Reference: `S000_Ref.png` (subject and colour-grade continuity only; do NOT reuse its location or composition) (first scene: none (first scene in the series))
Step 3 — Reference Image Prompt (Google Flow):
[1–3 sentences: shot type, angle, what is in frame, the unique location, lighting/mood. Fully describe the still.]
Save as: `S001_Ref.png`
Step 4 Ingredients: Starting Reference Image: `S001_Ref.png`
Video Prompt (Google Flow, generate Gs: …):
I2V from `S001_Ref.png`. 0–3s: …; 3–6s: …; [slot]–[G]s (spare Ks): …tail… No speech, narration, whispering, singing or lip movement: any people keep their mouths closed. Audio is music and sound effects only.
Sound (BGM+SFX only, no voice or speech): [music behaviour + specific SFX; mention the second marks] From [slot]s to [G]s the music and ambience sustain and ease down.
Cut→S002: [transition and what it cuts to]
```
The final scene ends with `Cut→END: Fade to black…` and "(trim in edit to land at [real end])" in its header.
7. **PRODUCTION NOTES** (bullets): total images and videos required (scene images + subject-sheet images; no environment images); runtime math; the slot-plan table (slot length, number, total seconds, scene list); the Flow generation table (8 s vs 10 s, number of videos, footage, spare footage, scene list) and how to use the spare seconds; timeline rule (place clips at scene start times, trimmed to slot length); how in-clip marks work; sync tolerance (±1 s fixes in the edit); audio-file credits; any transcript gap; characters and real-people note; sensitive-scene note; sound-design tip (BGM 10–12 dB under the voice); image generation is Google Flow only; continuity chain; hard-rules reminder; fact-check list; reminder that the GLOBAL LOCK BLOCK is appended to every prompt.

### RULES FOR EVERY SCENE
- **Timing:** second marks inside video prompts are relative to the clip start (`0s` = scene start). Place each action so it lands on the spoken phrase at that moment. Use the transcript timestamps, not guesses.
- **No narration in Flow prompts:** NEVER write the spoken words, quotes or dialogue inside Step 3 or Step 4 prompts (Flow may speak them). The Tamil/original narration appears only in the "VO sync" editor line. Characters never speak; their mouths stay closed; no singing, humming, chanting or crowd voices. Generated audio is instrumental BGM plus diegetic SFX only.
- **Unique locations:** every scene is set in a different place that fits what the narration says at that moment (aerials, interiors, close-ups, underwater, museums, streets, landscapes, and so on). Where the story is inherently in one place, change the angle, subject area, light or surroundings so the background differs. Use the previous scene's reference image only for character look and colour grade.
- **Faces:** all human characters have clear, fully visible, fully described faces that match the Step 1 sheets. Faces are invented fictional faces, never likenesses of real people (including real people named in the script). Real figures are shown through invented characters or only through rooms and objects.
- **No legible text:** maps, signs, screens, palm leaves, seals, books and inscriptions show only unreadable marks. No captions, logos or watermarks.
- **Sensitive events:** deaths, massacres, disasters and violence are implied through symbols, aftermath, sound and reactions (empty hammock, dropped hat, birds bursting from trees, water in an empty street). No gore, no visible bodies, nothing graphic.
- **Variety:** vary shot types (wide, macro, top-down, low-angle, tracking, aerial, push-in, rack focus, orbit, time-lapse). Never put 3+ identical shot types in a row. Each scene = one clear action or reveal that fits inside its slot.
- **Transitions:** match each `Cut→` to the next scene's opening so camera motion, light and position flow.
- **Sound:** change with the story (rises in build-ups, hushes before reveals, stings at turns, silence beats, swell at the payoff, resolves to a final chord and fades). Give specific diegetic SFX per action and tie sounds to second marks.
- **Facts:** use only what the script says. In Production Notes, list shaky claims, numbers, dates and quotes from the script to fact-check before publishing, and mention transcript mis-hearings you corrected in the VO sync lines.

### HOW TO BUILD IT (to avoid mistakes)
1. Parse the transcript into `(seconds, text)` cues.
2. Decide the slots, then write the scenes into a small data file (label, slot, subjects, unique location, reference prompt, video prompt, sound, cut, VO cues), and generate the Markdown with a script so that timestamps, counts, subject usage notes, the location table and the production-note numbers are computed automatically, not typed by hand.
3. Validate before delivering: slots sum to the total; every slot is 4, 6, 8 or 10 s; every VO cue falls inside (or at most 1–2 s before) its scene window; no scene has a duplicate location; no video prompt contains quoted narration; every scene has all template lines; scene counts in the header match the file; segment ranges and times are correct.
4. Save the file in the repository working directory, commit it, push it to the session's designated development branch, and send me the file as a download (SendUserFile) with a short summary: number of scenes (= images = videos), the count of each slot length and the 8 s / 10 s Flow generation counts, the total and spare footage, any transcript gap, and the facts to double-check. Keep that chat summary short.

## END PROMPT

---

## Notes for you (not part of the prompt)

- If the new session cannot see this repository, attach the two example `.md` files to your first message and add the sentence: "Use these two attached files as the exact format reference."
- Paste your script and the transcript (with the `(m:ss)` timestamps) right after the prompt. The audio file's own credits (for example at 0:00 and at the end) are handled by the first and last scenes.
- If you want a different look (animation, 3D, painting) or different hard rules (for example no visible faces), add one line to the INPUT block: `STYLE: …` / `HARD RULES: …`. The prompt assumes photorealistic cinematic documentary and visible fictional faces.
