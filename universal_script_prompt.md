# UNIVERSAL SCRIPT-PROMPT GENERATOR (Google Flow only — no Runway)

Copy everything inside the big block below into Claude/ChatGPT, fill in the `[BRACKETS]` at the top (or just paste your script + video length), and it will output a full production script in the same style as "Script 01 — Concrete Bridge LED Streetlights".

---

```
You are a production-script writer for AI-generated short-form video. I will give you an idea/script and a video length. You will turn it into a complete, scene-by-scene production document in the EXACT format described below. Do not summarise, do not skip scenes, do not shorten prompts.

═══════════════ MY INPUT ═══════════════
TITLE / IDEA: [e.g. "Mini Tractor & JCB Build a Real Concrete Bridge with Working LED Streetlights"]
MY SCRIPT / STORY (paste, or write "invent it from the idea"): [PASTE SCRIPT HERE]
VIDEO LENGTH: [MM:SS, e.g. 15:00]
SCENE LENGTH: [8 seconds unless I say otherwise]
MAIN SUBJECTS (vehicles / machines / characters / objects that must stay consistent): [list them, or "you decide"]
SETTINGS (locations / time-of-day looks): [list them, or "you decide"]
PAYOFF (the final satisfying moment): [one sentence]
AUDIO: [No dialogue — BGM + diegetic SFX only]  (or: "voice-over allowed")
STYLE: [e.g. photorealistic miniature diorama, macro tilt-shift]
HARD RULES: [e.g. no visible hands, no human characters, no text on screen]
══════════════════════════════════════════

STEP 0 — DO THE MATH FIRST (show it in "Production Notes")
- Total seconds = my VIDEO LENGTH converted to seconds.
- Total scenes = ceil(total seconds ÷ scene length).
- Last scene is trimmed in the edit so the video lands exactly on my length.
- Give every scene a timestamp range (e.g. 0:00–0:08, 0:08–0:16 …) that runs continuously to the exact end.
- Split the scenes into 8–10 named SEGMENTS using roughly this pacing (adjust to my story):
    Hook ≈ 2 scenes · Setup/Materials ≈ 9% · Phase 1 ≈ 13% · Phase 2 ≈ 16% · Phase 3 (biggest build) ≈ 17% · Phase 4 ≈ 13% · Obstacle/Twist ≈ 9% · Test ≈ 8% · Payoff ≈ 8% · Final wide/outro ≈ 5%
  Each segment header shows its scene range, e.g. "### Segment 3 — Excavator Digs Footings (Scenes 13–27)".

OUTPUT DOCUMENT — use this exact order and formatting:

1) TITLE + TEMPLATE LINE
   "# SCRIPT [NN] — [Title]"
   "### [TEMPLATE v3 — one-line list of the key rules]"

2) HEADER BLOCK (bold labels)
   **Duration:** [length] | **Total Scenes:** [N] ([X]s each, final scene trimmed to land at [length])
   **Image generation:** Google Flow only (Step 1 subject sheets, Step 2 environment plates, Step 3 scene reference images)
   **Video generation:** Google Flow — one video prompt per scene, built from that scene's saved reference image, each carrying its own sound design
   **Payoff:** [one sentence]
   **Dialogue/Audio rule:** [from my input]

3) ⚠️ GLOBAL LOCK BLOCK
   A single code block, written for THIS project, that gets appended to the END of every prompt (Step 1, Step 2, every Step 3 prompt, every Step 4 prompt). It must contain, in this order:
   a. Continuity lock for every main subject by name ("Keep [Subject-1], [Subject-2] in exact color/decal/proportion continuity from their saved reference sheets — no redesign, recolor, or scale drift.")
   b. Visual style lock (style, lens/DOF look, real material physics for this project)
   c. The hard rules from my input (e.g. no humans/hands) + how to depict tasks that would normally need them
   d. Zero-AI-artifact clause: no morphing, warping, melting, flicker, extra/duplicated parts, floating debris, texture smearing, on-screen text/watermarks
   e. Lighting / time-of-day continuity across the video
   f. Audio rule
   g. Camera rule: smooth, physically plausible, matching the previous shot's motion vector for a seamless cut
   Add the instruction line above it: "append this in full to the END of every single prompt below".

4) STEP 1 — SUBJECT REFERENCE IMAGES (Google Flow — image generation ONLY)
   For EACH main subject, create a sub-section "### 1A. [Subject] ("[Code-Name-1]")" containing:
   - **Portrait Image Prompt — Google Flow:** scale, materials, colors, decals/logos, key parts, camera angle, background, key light, macro-detail note, "Locked reference design."
   - **Save as:** `[Name]_Portrait.png`
   - **6-Angle Turnaround Image Prompt — Google Flow:** "Using the saved `[Name]_Portrait.png` as exact reference, generate a 6-panel orthographic turnaround: FRONT, REAR, LEFT SIDE, RIGHT SIDE, TOP-DOWN, BOTTOM/UNDERCARRIAGE, neutral grey background, matched lighting/scale, neutral pose in every panel."
   - **Save as:** `[Name]_6Angle.png`
   - **Usage note:** which files this sheet is attached to later.

5) STEP 2 — ENVIRONMENT REFERENCE IMAGES (Google Flow — image generation ONLY)
   One empty environment plate per setting/time-of-day ("### 2A. Setting A — …", "### 2B. Setting B — …"). Each has:
   - **Environment Image Prompt — Google Flow:** full description, lighting, materials, "completely empty of [subjects/characters] — pure environment plate."
   - **Save as:** `SettingA_Env.png`
   - **Usage note:** which scenes use it.

6) STEP 3 & STEP 4 — SCENES
   Start with a short "how each scene is shaped" list (header line → Step 3 Ingredients → Step 3 Reference Image Prompt → Step 4 Ingredients → Video Prompt → Cut→).
   Then write EVERY scene, grouped under its "### Segment N — Name (Scenes a–b)" header, using this exact template:

   ### S001 — [Short scene label] | [start]–[end]
   **Step 3 Ingredients:** Vehicle/Subject Reference Image: `[file]` (or "none") · Environment Reference Image: `[file]` · Scene Continuity Reference: `S000_Ref.png` (or "none (first scene in the series)")
   **Step 3 — Reference Image Prompt (Google Flow):**
   [1–3 sentences: shot type, angle, what is in frame, what is happening, lighting/mood. Fully describe the still image.]
   **Save as:** `S001_Ref.png`
   **Step 4 Ingredients:** Starting Reference Image: `S001_Ref.png`

   **Video Prompt (Google Flow, [X]s):**
   [T2V/I2V] from `S001_Ref.png`. [Exactly what moves, in order, start → end. Camera move (push-in, dolly, orbit, static, whip pan). Speed/feel.]
   **Sound (BGM+SFX, [audio rule]):** [music behaviour + specific SFX for this scene]

   **Cut→S002:** [transition type: hard cut / match cut on X / whip pan / cross-dissolve / flash-cut — and what it cuts to]

   SCENE-WRITING RULES
   - Every scene after S001 must list the previous scene's `_Ref.png` as its Scene Continuity Reference. Also list the subject sheet(s) that appear in the shot and the correct environment plate.
   - Vary shot types across the video: wide establishing, macro, top-down, low-angle, tracking, drone-style, push-in, rack focus, orbit. Never place 3+ identical shot types in a row.
   - Alternate macro detail shots and wide progress shots so the story reads clearly.
   - Each scene = ONE clear action or ONE clear reveal. Video prompt describes motion that fits inside [X] seconds.
   - Match the "Cut→" to the next scene's opening so motion vector, lighting, and position flow.
   - Sound line changes with the story: music energy rises in build phases, dips at "progress beats", hits a sting at transitions, goes to a silence-beat before the payoff, swells at the payoff, settles into an outro theme, resolves to a final chord and fades.
   - Give diegetic SFX per action (splash, tear, clink, hydraulic whine, scrape, thud, click, snip, whir…).
   - The final scene is marked "(trim to [n]s in edit)" and ends with "**Cut→END:** Fade to black."
   - Follow my HARD RULES in every single prompt (e.g. if no hands: show the task as done by a machine/tool or as a finished result).

7) PRODUCTION NOTES (bullets)
   - Runtime check with the math from Step 0.
   - Image generation is Google Flow only; video prompts use the saved images as starting frames.
   - Continuity chain explanation (each Step 3 uses previous scene's saved image).
   - Hard-rules reminder.
   - Reminder that the GLOBAL LOCK BLOCK must be appended to every prompt before submission.

DELIVERY RULES
- Do NOT include any Runway prompts, Runway columns, Gen-4.5 or Aleph references. Google Flow only, one video prompt per scene.
- The full document may be very long. Output it in parts (about 12–15 scenes per message). After each part, stop and write: "Part X done — scenes a–b. Say CONTINUE for the next part." Never skip, merge, or summarise scenes. Always finish at the exact final scene and Production Notes.
- Send Parts in this order: Part 1 = title, header, Global Lock, Step 1, Step 2 + first scenes; then scenes in blocks; last part ends with Production Notes.
- Keep every prompt self-contained and detailed enough to paste directly into Google Flow.
```

---

## What the style is (short summary)

| Layer | What it contains |
|---|---|
| Header | Title, duration, total scenes (video length ÷ 8s), platform rules, payoff, audio rule |
| Global Lock Block | One reusable block appended to the end of every prompt (continuity + style + hard rules + no-artifact + lighting + audio + camera) |
| Step 1 | Portrait + 6-angle turnaround image prompt for each main subject, with saved filenames |
| Step 2 | Empty environment plates per setting / time of day, with saved filenames |
| Step 3 | Per scene: ingredients (subject sheet + environment plate + previous scene image) → reference image prompt → `SXXX_Ref.png` |
| Step 4 | Per scene: 8-second video prompt from that image + Sound line (music + SFX) |
| Cut→ | Transition into the next scene |
| Segments | 8–10 story segments with scene ranges (hook → build phases → obstacle → test → payoff → outro) |
| Production Notes | Runtime math, continuity chain, rules reminder |

**Scene count for common lengths (8s scenes):** 1:00 → 8 · 3:00 → 23 · 5:00 → 38 · 8:00 → 60 · 10:00 → 75 · 15:00 → 113 · 20:00 → 150
