# Bullet Poochaandi – Runway Gen-4.5 Text-to-Video Prompts (Synced to Song)

Song: "Urulaikizhangu Chella Kutty" (Tamil, 3:16 = 196 s)
Model: **Runway Gen-4.5, Text to Video**
New look: Kutty is a **living animated potato**. Amma is a **mother potato**. Poochaandi is a **new towering bogeyman with huge wide-open glowing eyes that never blink**.

---

## 1. How the sync works (read once)

- Verses follow your lyrics (wake, brush, bath, eat, school, homework, phone, sleep). Block start times come from your earlier file, whose labels differed (it had school twice and no sleep verse): 0:08, 0:31, 0:55, 1:18, 1:42, 2:05, 2:29, 2:52. The song ends at 3:16. These are approximate, so check them against your audio.
- Every verse is about 23.5 s. Each verse is cut into **3 clips: A (5 s), B (10 s), C (10 s, trimmed to about 8.5 s)**. Together they cover the verse exactly.
- Every clip prompt contains **second-by-second beats** that match the lyric line sung at that moment. The time offsets inside a verse are my estimates (A = 0–5, B = 5–15, C = 15–23.5 s). Slide clips by ear in your editor.
- Runway Gen-4.5 has **no audio input**, so it cannot lip-sync by itself. For exact mouth sync, run the finished clips through Runway's lip-sync / Act-Two tool, or any lip-sync tool, using your song vocals. Without that, mouths will move in a generic way.
- If your Runway duration selector offers other lengths, you can use them. Just keep each verse's clips adding up to about 23.5 s.

## 2. Consistency (text-to-video has no memory between clips)

Each prompt below repeats the same short character descriptions word for word. **Do not reword them.** If you want the strongest consistency, generate one still image of each character first (Runway text-to-image), then use it as a reference/first frame. The prompts still work as plain text-to-video.

| Character | Text used in every prompt |
|---|---|
| **KUTTY** | Kutty, a chubby living brown baby potato with two green sprouts, big shiny black eyes and tiny red slippers |
| **AMMA** | Amma, a warm mother potato in a green saree with red bindi and jasmine flowers on her sprout |
| **POOCHAANDI** | Bullet Poochaandi, a towering horned bogeyman with peacock-feather crown, black beard, orange cape, and huge wide-open glowing red unblinking eyes, riding a roaring flame-wheeled Bullet motorcycle with a glowing skull headlight |
| **STYLE** | Stylized 3D animated feature-film look, glossy tactile potato skin, warm golden light with orange glow, cinematic, 16:9. |

Prefer a human mother? Find-and-replace `Amma, a warm mother potato in a green saree with red bindi and jasmine flowers on her sprout` with `Amma, a warm young Tamil mother in a green saree with red bindi and jasmine flowers in her braid` in this file.

## 3. Poochaandi's moves (same in every verse, so kids learn them)

1. **REV, REV:** fists twist the handlebar twice, a flash on each rev.
2. **WHEELIE:** front wheel pops up, feather crown bounces.
3. **EYES + SLOW POINT:** his huge eyes snap fully open, and he freezes and slowly points at the camera.

Kutty reacts every time with the **Jelly Shake**: eyes pop, body trembles like jelly, sprouts droop. At the end of every verse a **gold star** pops above Kutty and Poochaandi gives a slow approving nod. Eight verses give 8 stars.

## 4. Master timeline

| Clip | Song time | Length | Lyric in this clip |
|---|---|---|---|
| INTRO | 0:00–0:08 | 10 s, trim to 8 | Instrumental |
| V1-A / B / C | 0:08–0:13 / 0:13–0:23 / 0:23–0:31 | 5 / 10 / 10 | Wake up |
| V2-A / B / C | 0:31–0:36 / 0:36–0:46 / 0:46–0:55 | 5 / 10 / 10 | Brush teeth |
| V3-A / B / C | 0:55–1:00 / 1:00–1:10 / 1:10–1:18 | 5 / 10 / 10 | Bath |
| V4-A / B / C | 1:18–1:23 / 1:23–1:33 / 1:33–1:42 | 5 / 10 / 10 | Eat food |
| V5-A / B / C | 1:42–1:47 / 1:47–1:57 / 1:57–2:05 | 5 / 10 / 10 | School |
| V6-A / B / C | 2:05–2:10 / 2:10–2:20 / 2:20–2:29 | 5 / 10 / 10 | Homework |
| V7-A / B / C | 2:29–2:34 / 2:34–2:44 / 2:44–2:52 | 5 / 10 / 10 | Phone away |
| V8-A / B / C | 2:52–2:57 / 2:57–3:07 / 3:07–3:16 | 5 / 10 / 10 | Sleep |
| PAYOFF (optional) | after 3:16 | 5 s | Outro |

Trim every C clip to its song window and every INTRO to 8 s.

---

# INTRO · 0:00–0:08 · generate 10 s, trim to 8 s

*Instrumental hook.*

```
Pitch-black stormy night. Two huge wide-open glowing red eyes snap open in the dark and stare at the camera. A glowing orange-and-teal portal tears open in the purple sky. Bullet Poochaandi, a towering horned bogeyman with peacock-feather crown, black beard, orange cape and huge wide-open unblinking glowing red eyes, bursts out of the portal on a roaring flame-wheeled Bullet motorcycle with a glowing skull headlight, doing a wheelie straight toward the camera. Thunder flash, he lands on a floating cliff, revs twice with a flash on each rev, then freezes and slowly points at the camera. Fast push-in, small camera shake on each rev. Stylized 3D animated feature-film look, warm orange glow, cinematic, 16:9.
```

---

# VERSE 1 · WAKE UP

### V1-A · 0:08–0:13 · 5 s
*Lyric:* உருளைக்கிழங்கு செல்ல குட்டி தூங்கி எழுந்திடு / பத்து நிமிஷம் தூங்கிக்கிறேன் டிஸ்டர்ப் பண்ணாத

```
Sunny morning in a cozy Tamil village bedroom. 0-2.5 s: Amma, a warm mother potato in a green saree with red bindi and jasmine flowers on her sprout, tugs the quilt and talks lovingly. 2.5-5 s: Kutty, a chubby living brown baby potato with two green sprouts, big shiny black eyes and tiny red slippers, pops his head out, holds up ten stubby fingers, speaks cheekily, then slips back under the quilt. Gentle handheld sway. Stylized 3D animated feature-film look, glossy tactile potato skin, warm golden light, cinematic, 16:9.
```

### V1-B · 0:13–0:23 · 10 s
*Lyric:* புல்லட்டு பூச்சாண்டி வந்துடுவாரு / அவர் பக்கத்துல வந்தாக்கா பயந்துடுவே நீ

```
Same bedroom. 0-2 s: Amma raises one finger with a knowing smile. The window glows orange, thunder flashes. 2-5 s: Bullet Poochaandi, a towering horned bogeyman with peacock-feather crown, black beard, orange cape and huge wide-open glowing red unblinking eyes, looms outside the window on a roaring flame-wheeled Bullet motorcycle with a glowing skull headlight, revs twice with a flash on each rev, then does a wheelie. 5-8 s: he freezes and slowly points into the room, eyes bulging wide. Kutty the chubby brown baby potato with two green sprouts pops up, eyes huge, trembling like jelly, sprouts drooping. 8-10 s: Kutty ducks behind Amma's saree and peeks out. Slow push-in. Stylized 3D animated feature-film look, orange glow, cinematic, 16:9.
```

### V1-C · 0:23–0:31 · 10 s, trim to 8.5 s
*Lyric:* வேணாம் மம்மி வேணாம் மம்மி ப்ளீஸ் வேணாம் / அவரு கிட்ட சொல்லாத எழுந்திருச்சிட்டேன்

```
Bedroom. 0-3.5 s: Kutty, a chubby brown baby potato with two green sprouts and tiny red slippers, hugs Amma the mother potato's green saree, hands pressed together, pleading. 3.5-6.5 s: sped-up comedy, he folds the quilt and fluffs the pillow at lightning speed. 6.5-8.5 s: a gold star pops above his head, his sprouts stand up proudly, he points at himself; in the window Poochaandi's huge glowing eyes give a slow approving nod. Medium shot. Stylized 3D animated feature-film look, warm golden light, cinematic, 16:9.
```

---

# VERSE 2 · BRUSH TEETH

### V2-A · 0:31–0:36 · 5 s
*Lyric:* உருளைக்கிழங்கு செல்லக்குட்டி பல்லு விளக்கு / முடியாது போங்கம்மா நான் மாட்டேன்

```
Bright bathroom. 0-2.5 s: Amma, a warm mother potato in a green saree with red bindi and jasmine flowers on her sprout, holds out a toothbrush with rainbow paste. 2.5-5 s: Kutty, a chubby living brown baby potato with two green sprouts and tiny red slippers, on a small stool, zips his lips, shakes his head and stomps a tiny foot. Slight push-in. Stylized 3D animated feature-film look, glossy tactile potato skin, warm golden light, cinematic, 16:9.
```

### V2-B · 0:36–0:46 · 10 s
*Lyric:* புல்லட்டு பூச்சாண்டி வந்துடுவாரு / அவர் பக்கத்துல வந்தாக்கா பயந்துடுவே நீ

```
Bathroom mirror glows orange and the reflection changes. 0-2 s: lightning flash. 2-5 s: inside the mirror, Bullet Poochaandi, a towering horned bogeyman with peacock-feather crown, black beard, orange cape and huge wide-open glowing red unblinking eyes, spins a donut on his roaring flame-wheeled Bullet motorcycle, bubbles and sparkles swirling, an oversized toothbrush in his fist. 5-8 s: wheelie, then he freezes and slowly points the toothbrush at the camera, eyes bulging. Kutty the chubby brown baby potato with two green sprouts trembles like jelly, sprouts drooping. 8-10 s: Kutty covers his eyes and peeks through his fingers. Camera on the mirror, shake on each rev. Stylized 3D animated feature-film look, orange glow, cinematic, 16:9.
```

### V2-C · 0:46–0:55 · 10 s, trim to 8.5 s
*Lyric:* வேணாம் மம்மி வேணாம் மம்மி ப்ளீஸ் வேணாம் / அவரு கிட்ட சொல்லாத நான் பல்ல வெளக்கிட்டேன்

```
Bathroom. 0-3.5 s: Kutty, a chubby brown baby potato with two green sprouts, hugs Amma the mother potato and pleads, then brushes his teeth at lightning speed, foam bubbles flying. 3.5-6.5 s: rinses and grins with sparkly clean teeth. 6.5-8.5 s: a gold star pops above his head, sprouts stand tall; in the mirror corner Poochaandi's huge glowing eyes give a slow approving nod. Medium shot. Stylized 3D animated feature-film look, warm golden light, cinematic, 16:9.
```

---

# VERSE 3 · BATH

### V3-A · 0:55–1:00 · 5 s
*Lyric:* உருளக்கிழங்கு செல்லக்குட்டி குளிச்சு முடிச்சுடு / முடியாது போங்கம்மா நான் மாட்டேன்

```
Bright bathroom full of floating bubbles. 0-2.5 s: Amma, a warm mother potato in a green saree with red bindi and jasmine flowers on her sprout, holds a big towel and a bucket of bubbly water. 2.5-5 s: Kutty, a chubby living brown baby potato with two green sprouts and tiny red slippers, wearing a shower cap, waves his stubby arms "no no" and shakes his head. Steady camera. Stylized 3D animated feature-film look, glossy tactile potato skin, warm golden light, cinematic, 16:9.
```

### V3-B · 1:00–1:10 · 10 s
*Lyric:* புல்லட்டு பூச்சாண்டி வந்துடுவாரு / அவர் பக்கத்துல வந்தாக்கா பயந்துடுவே நீ

```
Bathroom fills with orange glow and steam. 0-2 s: thunder flash, steam swirls. 2-5 s: Bullet Poochaandi, a towering horned bogeyman with peacock-feather crown, black beard, orange cape and huge wide-open glowing red unblinking eyes, skids his roaring flame-wheeled Bullet motorcycle through a puddle at the doorway in a big water-spray drift, a yellow rubber duck on his skull headlight. 5-8 s: wheelie, then he freezes and slowly points at Kutty, eyes bulging. Kutty the chubby brown baby potato with two green sprouts trembles like jelly, sprouts drooping. 8-10 s: Kutty ducks behind the bucket and peeks over the rim. Camera pans with the drift. Stylized 3D animated feature-film look, orange glow, cinematic, 16:9.
```

### V3-C · 1:10–1:18 · 10 s, trim to 8.5 s
*Lyric:* வேணாம் மம்மி வேணாம் மம்மி ப்ளீஸ் வேணாம் / அவரு கிட்ட சொல்லாத நான் குளிச்சு முடிச்சிட்டேன்

```
Bathroom. 0-3.5 s: Kutty, a chubby brown baby potato with two green sprouts, pleads to Amma the mother potato, then scrubs and splashes through a sped-up bubble wash. 3.5-6.5 s: he shakes like a puppy, droplets flying, wrapped in a hooded towel. 6.5-8.5 s: a gold star pops above his head, towel flares like a cape; in the doorway Poochaandi's huge glowing eyes give a slow approving nod beside the duck. Medium shot. Stylized 3D animated feature-film look, warm golden light, cinematic, 16:9.
```

---

# VERSE 4 · EAT FOOD

### V4-A · 1:18–1:23 · 5 s
*Lyric:* உருளைக்கிழங்கு செல்லக்குட்டி சாப்பாடு சாப்பிடு / முடியாது போங்கம்மா நான் மாட்டேன்

```
Tamil village dining area with idli, dosa and sambar rice on a banana leaf. 0-2.5 s: Amma, a warm mother potato in a green saree with red bindi and jasmine flowers on her sprout, brings a spoonful of food. 2.5-5 s: Kutty, a chubby living brown baby potato with two green sprouts and tiny red slippers, in a tiny high chair, turns away, pouts and shakes his head. Slow push-in. Stylized 3D animated feature-film look, glossy tactile potato skin, warm golden light, cinematic, 16:9.
```

### V4-B · 1:23–1:33 · 10 s
*Lyric:* புல்லட்டு பூச்சாண்டி வந்துடுவாரு / அவர் பக்கத்துல வந்தாக்கா பயந்துடுவே நீ

```
Kitchen doorway. 0-2 s: thunder flash, a roaring flame-wheeled Bullet motorcycle skids in. 2-5 s: Bullet Poochaandi, a towering horned bogeyman with peacock-feather crown, black beard, orange cape and huge wide-open glowing red unblinking eyes, revs twice with a flash on each rev, a dosa floating on orange sparkles beside him. 5-8 s: wheelie, then he freezes and slowly points at the plate, eyes bulging. Kutty the chubby brown baby potato with two green sprouts drops his spoon, trembles like jelly, sprouts drooping. 8-10 s: Kutty grabs the spoon with both hands, eyes wide. Slight camera shake. Stylized 3D animated feature-film look, orange glow, cinematic, 16:9.
```

### V4-C · 1:33–1:42 · 10 s, trim to 8.5 s
*Lyric:* வேணாம் மம்மி வேணாம் மம்மி ப்ளீஸ் வேணாம் / அவருகிட்ட சொல்லாத சாப்பிட்டு முடிச்சிட்டேன்

```
Dining area. 0-3.5 s: Kutty, a chubby brown baby potato with two green sprouts, pleads to Amma the mother potato, then gobbles his food in sped-up fast-forward. 3.5-6.5 s: he lifts the empty plate over his head triumphantly, rice on his cheeks. 6.5-8.5 s: a gold star pops above his head, sprouts stand tall; in the doorway Poochaandi's huge glowing eyes give a slow approving nod. Medium shot. Stylized 3D animated feature-film look, warm golden light, cinematic, 16:9.
```

---

# VERSE 5 · SCHOOL

### V5-A · 1:42–1:47 · 5 s
*Lyric:* உருளைக்கிழங்கு செல்லக்குட்டி ஸ்கூலுக்கு போயிடு / முடியாது போங்கம்மா நான் மாட்டேன்

```
House front door, morning. 0-2.5 s: Amma, a warm mother potato in a green saree with red bindi and jasmine flowers on her sprout, hands over a school bag and tiffin box. 2.5-5 s: Kutty, a chubby living brown baby potato with two green sprouts, wearing a tiny school tie and one red slipper, flops back on the floor, crosses his arms and kicks his feet. Steady camera. Stylized 3D animated feature-film look, glossy tactile potato skin, warm golden light, cinematic, 16:9.
```

### V5-B · 1:47–1:57 · 10 s
*Lyric:* புல்லட்டு பூச்சாண்டி வந்துடுவாரு / அவர் பக்கத்துல வந்தாக்கா பயந்துடுவே நீ

```
Sunny small-town street. 0-2 s: a yellow school bus drives along as a roaring flame-wheeled Bullet motorcycle roars up beside it. 2-5 s: Bullet Poochaandi, a towering horned bogeyman with peacock-feather crown, black beard, orange cape and huge wide-open glowing red unblinking eyes, revs twice, then does a wheelie alongside the bus, feathers flying. 5-8 s: he turns to the bus window, freezes and slowly points, eyes bulging. Kutty the chubby brown baby potato with two green sprouts at the window trembles like jelly and ducks down. 8-10 s: Kutty peeks up and sits straight. Tracking shot, motion blur. Stylized 3D animated feature-film look, orange glow, cinematic, 16:9.
```

### V5-C · 1:57–2:05 · 10 s, trim to 8.5 s
*Lyric:* வேணாம் மம்மி வேணாம் மம்மி ப்ளீஸ் வேணாம் / அம்மா அவருகிட்ட சொல்லாத ஸ்கூலுக்கு கிளம்பிட்டேன்

```
House gate and bus door. 0-3.5 s: Kutty, a chubby brown baby potato with two green sprouts and a school bag, hugs Amma the mother potato, pleads, then hops onto the bus. 3.5-6.5 s: he waves from the window, Amma blows a kiss. 6.5-8.5 s: a gold star pops above his head; far behind, Poochaandi's huge glowing eyes give a slow approving nod as he turns his bike away. Wide shot. Stylized 3D animated feature-film look, warm golden light, cinematic, 16:9.
```

---

# VERSE 6 · HOMEWORK

### V6-A · 2:05–2:10 · 5 s
*Lyric:* உருளைக்கிழங்கு செல்லக்குட்டி ஹோம் ஒர்க் பண்ணிடு / முடியாது போங்கம்மா நான் மாட்டேன்

```
Cozy evening living room with lamp light. 0-2.5 s: Amma, a warm mother potato in a green saree with red bindi and jasmine flowers on her sprout, taps a notebook on a study table. 2.5-5 s: Kutty, a chubby living brown baby potato with two green sprouts, lies flat on the carpet pretending to nap, then hides his face behind the notebook. Steady camera. Stylized 3D animated feature-film look, glossy tactile potato skin, warm lamp glow, cinematic, 16:9.
```

### V6-B · 2:10–2:20 · 10 s
*Lyric:* புல்லட்டு பூச்சாண்டி வந்துடுவாரு / அவர் பக்கத்துல வந்தாக்கா பயந்துடுவே நீ

```
Living room. 0-2 s: a giant shadow rises on the wall, thunder flash. 2-5 s: Bullet Poochaandi, a towering horned bogeyman with peacock-feather crown, black beard, orange cape and huge wide-open glowing red unblinking eyes, spins his roaring flame-wheeled Bullet motorcycle in a 360 at the doorway, notebook pages fluttering. 5-8 s: wheelie, then he freezes and slowly points at the notebook, eyes bulging. Kutty the chubby brown baby potato with two green sprouts holds the notebook up like a shield, trembling like jelly. 8-10 s: Kutty grabs a pencil with both hands. Slight camera shake. Stylized 3D animated feature-film look, orange glow, cinematic, 16:9.
```

### V6-C · 2:20–2:29 · 10 s, trim to 8.5 s
*Lyric:* வேணாம் மம்மி வேணாம் மம்மி ப்ளீஸ் வேணாம் / அவருகிட்ட சொல்லாத ஹோம் ஒர்க் முடிச்சிட்டேன்

```
Living room. 0-3.5 s: Kutty, a chubby brown baby potato with two green sprouts, pleads to Amma the mother potato, then writes at lightning speed, the pencil a blur. 3.5-6.5 s: he lifts his finished notebook with a gold sticker while Amma hugs him. 6.5-8.5 s: a gold star pops above his head; in the window Poochaandi's huge glowing eyes give a slow approving nod. Medium shot. Stylized 3D animated feature-film look, warm golden light, cinematic, 16:9.
```

---

# VERSE 7 · PHONE AWAY

### V7-A · 2:29–2:34 · 5 s
*Lyric:* உருளைக்கிழங்கு செல்லக்குட்டி போன பாக்காத / முடியாது போங்கம்மா நான் மாட்டேன்

```
Evening bedroom. 0-2.5 s: Kutty, a chubby living brown baby potato with two green sprouts and tiny red slippers, under a quilt giggles at a glowing tablet, screen light on his cheeks. 2.5-5 s: Amma, a warm mother potato in a green saree with red bindi and jasmine flowers on her sprout, walks in with her hand out; Kutty hugs the tablet and shakes his head. Slow push-in. Stylized 3D animated feature-film look, glossy tactile potato skin, warm golden light, cinematic, 16:9.
```

### V7-B · 2:34–2:44 · 10 s
*Lyric:* புல்லட்டு பூச்சாண்டி வந்துடுவாரு / அவர் பக்கத்துல வந்தாக்கா பயந்துடுவே நீ

```
Bedroom. 0-2 s: the tablet screen flashes orange, thunder. 2-5 s: Bullet Poochaandi, a towering horned bogeyman with peacock-feather crown, black beard, orange cape and huge wide-open glowing red unblinking eyes, bursts out of the screen on his roaring flame-wheeled Bullet motorcycle in a wheelie and holds out one hand as if to say "give it to me". 5-8 s: he freezes and slowly points at Kutty, eyes bulging. Kutty the chubby brown baby potato with two green sprouts drops the tablet, trembling like jelly, sprouts drooping. 8-10 s: Kutty ducks behind Amma the mother potato. Push-in then small shake. Stylized 3D animated feature-film look, orange glow, cinematic, 16:9.
```

### V7-C · 2:44–2:52 · 10 s, trim to 8.5 s
*Lyric:* வேணாம் மம்மி வேணாம் மம்மி ப்ளீஸ் வேணாம் / அவர் கிட்ட சொல்லாத போனை வச்சுட்டேன்

```
Bedroom. 0-3.5 s: Kutty, a chubby brown baby potato with two green sprouts, pleads, then puts the tablet into Amma the mother potato's hands with both of his. 3.5-6.5 s: Amma hugs him. 6.5-8.5 s: a gold star pops above his head, sprouts stand tall; at the window Poochaandi's huge glowing eyes give a slow approving nod. Medium shot. Stylized 3D animated feature-film look, warm golden light, cinematic, 16:9.
```

---

# VERSE 8 · SLEEP

### V8-A · 2:52–2:57 · 5 s
*Lyric:* உருளைக்கிழங்கு செல்ல குட்டி தூங்க போயிடு / முடியாது போங்கம்மா நான் மாட்டேன்

```
Night bedroom with a soft lamp. 0-2.5 s: Amma, a warm mother potato in a green saree with red bindi and jasmine flowers on her sprout, pats the pillow. 2.5-5 s: Kutty, a chubby living brown baby potato with two green sprouts and tiny red slippers, bounces on the bed with a big wide-awake pout and shakes his head. Slow push-in. Stylized 3D animated feature-film look, glossy tactile potato skin, warm golden light, cinematic, 16:9.
```

### V8-B · 2:57–3:07 · 10 s
*Lyric:* புல்லட்டு பூச்சாண்டி வந்துடுவாரு / அவர் பக்கத்துல வந்தாக்கா பயந்துடுவே நீ

```
Dim bedroom. 0-2 s: moonlight turns orange, thunder flash. 2-5 s: Bullet Poochaandi, a towering horned bogeyman with peacock-feather crown, black beard, orange cape and huge wide-open glowing red unblinking eyes, looms in the window on his roaring flame-wheeled Bullet motorcycle, revs twice with a flash on each rev, then does a wheelie. 5-8 s: he freezes and slowly points at the bed, eyes bulging. Kutty the chubby brown baby potato with two green sprouts trembles like jelly, sprouts drooping. 8-10 s: Kutty dives under the quilt, leaving only his sprouts sticking out. Slow push-in, small shake on each rev. Stylized 3D animated feature-film look, orange glow, cinematic, 16:9.
```

### V8-C · 3:07–3:16 · 10 s, trim to 9 s
*Lyric:* வேணாம் மம்மி வேணாம் மம்மி ப்ளீஸ் வேணாம் / ஐயோ அவருகிட்ட சொல்லாத தூங்க போயிட்டேன்

```
Bedroom turning into night. 0-3 s: Kutty, a chubby brown baby potato with two green sprouts, peeks out of the quilt and pleads to Amma the mother potato. 3-6 s: he snuggles in, eyes squeezed shut, sprouts drooping sleepily. 6-9 s: a gold star pops above him, the room dims to a soft glow; at the window Poochaandi's huge glowing eyes give a slow approving nod and he salutes gently. Slow pull-back. Stylized 3D animated feature-film look, warm golden light, cinematic, 16:9.
```

---

# PAYOFF · after 3:16 · 5 s (optional end card)

```
Golden-hour balcony. Kutty, a chubby living brown baby potato with two green sprouts, stands proudly with eight glowing gold stars floating around him beside Amma, a warm mother potato in a green saree with red bindi and jasmine flowers on her sprout. Bullet Poochaandi, a towering horned bogeyman with peacock-feather crown and huge wide-open glowing red eyes, hovers a few steps away on his flame-wheeled Bullet motorcycle, tips his crown, tosses Kutty a giant gold star and rides off into the sunset with a sparkle trail. Wide crane shot pulling back. Stylized 3D animated feature-film look, warm golden light, cinematic, 16:9.
```

---

# Editing checklist

- Place clips by the song times in each heading, then nudge by ear against the vocals.
- Add a thunder-hit/whoosh and a small zoom on each REV, REV.
- Show a star counter (1 to 8) in the corner as each C clip ends.
- Run lip-sync on the A and C clips (the ones where characters speak) for exact mouth sync.
- If Runway softens the scary eyes, lead with `dramatic cartoon bogeyman` and keep `wide-open glowing red eyes` as is. If a clip is blocked, replace `flame-wheeled` with `sparkle-wheeled` and retry.
- Thumbnail frame: V2-B or V3-B (Poochaandi's eyes at full bulge over a jelly-shaking Kutty). Shorts teaser: INTRO + V1-B + V3-B + V7-B + PAYOFF.
