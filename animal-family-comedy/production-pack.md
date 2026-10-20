# "பொண்ணு பாக்குற படலம்" – Animal Family Comedy
Production pack for Google Flow (3 scenes, 6 video shots, 4 characters)

---

## 0. How this works in Flow (read once)

- **Voices:** Flow (Veo) has **no voice-picker dropdown**. The voice is generated from the voice description plus the Tamil line you put in the video prompt. So under each character I give a **VOICE TAG**. Paste it into every video prompt that character speaks in. This keeps the voice as consistent as Veo allows. Voice can still drift between clips. If Tamil lip-sync or accent comes out wrong, generate the shot with the same prompt, then dub the line with a Tamil TTS voice (a young male, a deep older male, a middle-aged female and a young female) and keep Veo's picture.
- **Ingredients limit:** one video generation takes **max 3 ingredient images**. We have 4 characters + 1 environment, so we first build two group images (GRP01, GRP02). Every scene keyframe then needs only **3 ingredients**.
- **Renaming:** Flow does not rename files from the prompt text. Each prompt ends with a `SAVE AS:` line. Give that line to your rename agent, or rename by hand after download.
- **Aspect ratio:** 16:9. **Clip length:** 8 s each. Use Veo "Ingredients to video" (or "Frames to video" with the keyframe as the first frame when you want the exact set-up).
- I could not verify the exact UI of "agent mode" here. The workflow below works with plain Flow tools, so just follow the same ingredient and file-name rules in agent mode.

**Generation order**
1. Character portraits (4) → 2. Character angle sheets (24) → 3. Environments (3 + reverse angles) → 4. Group images GRP01, GRP02 → 5. Scene keyframes (6) → 6. Videos (6).

---

## 1. Story and shot list

| Scene | Place | Shot | Dialogue (Tamil) | Speaker |
|---|---|---|---|---|
| S01 | Bride's house living room | S01-Shot01 | "பொண்ணு எங்களுக்கு ரொம்ப புடுச்சிருக்கு" | Rangasamy (father) |
| S01 | Living room | S01-Shot02 | "டாமி செல்லம் பொண்ணு கிட்ட தனியா பேசணும்னா பேசிட்டு வா" | Rangasamy |
| S02 | Backyard courtyard with swing | S02-Shot01 | "உன்னால என்ன தூக்க முடியுமா ஆ?" | Tommy (son) |
| S02 | Courtyard | S02-Shot02 | no dialogue (lift gag, giggles only) | – |
| S03 | Front veranda (thinnai) | S03-Shot01 | "அப்பா எனக்கு இந்த பொண்ணு ரொம்ப ரொம்ப புடுச்சிருக்கு… சீக்கிரமா கல்யாணத்த ரெடி பண்ணுப்பா" | Tommy |
| S03 | Veranda | S03-Shot02 | "அடப்பாவி சண்டாளா! இதுக்கு தான் பொண்ணு பாக்க வந்தப்ப தூக்க சொன்னியா?" | Rangasamy |

**Joke:** lazy Tommy only wants a wife strong enough to carry him. He tests the girl by asking her to lift him. Dad realises it only at the end.

---

## 2. Characters

**Family 1 (groom's side): father and son, DOGS**
**Family 2 (bride's side): mother and daughter, ELEPHANTS**

### Global style line (already included inside every prompt below)
> Stylized 3D animated feature-film look, Pixar-quality, expressive anthropomorphic animal characters who walk upright and behave exactly like humans, with true animal heads, fur or skin, snout or trunk, ears, tail and paw-hands, wearing traditional Tamil Nadu clothes, soft cinematic lighting, 16:9.

### CH01 – TOMMY (the son, groom)
- **Animal:** Pug. Fawn-cream short fur, black mask and ears, wrinkled forehead, big round dark eyes, curly tail.
- **Build/personality:** young adult, chubby, round belly, lazy, always snacking, cheeky and innocent.
- **Costume:** maroon silk full-sleeve shirt, cream veshti with gold border, thin gold chain, hair-gel look on the head fur, small tilak mark.
- **VOICE TAG:** `young Tamil male voice, around 25, slightly nasal and whiny-sweet, lazy sing-song tone, cheeky and innocent`

### CH02 – RANGASAMY (the father)
- **Animal:** English Bulldog. Brown-and-white fur, heavy jowls, wrinkled flat face, small ears, strong stocky body, thick white moustache.
- **Personality:** proud, loud, 55 years old, a typical dramatic Tamil appa.
- **Costume:** white full-sleeve shirt, white veshti with a wide gold-and-red border, angavastram on the shoulder, round gold-rimmed glasses, vibhuti on forehead, gold ring.
- **VOICE TAG:** `deep gravelly Tamil male voice, around 55, booming and dramatic, Kongu/Madurai-flavoured accent, quick to shout`

### CH03 – GAJALAKSHMI (the mother, bride's side)
- **Animal:** Asian elephant. Soft grey skin, large ears, short trunk, small tusks, kind eyes with long lashes.
- **Personality:** warm, dignified, 45 years old, polite host who hides her giggles.
- **Costume:** emerald-green Kanjivaram silk saree with a gold zari border, red bindi, jasmine garland around the head top, gold earrings on the ear edge, bangles.
- **VOICE TAG:** `warm motherly Tamil female voice, around 45, soft and melodious, gentle laugh`

### CH04 – MULLAI (the daughter, bride)
- **Animal:** young Asian elephant. Lighter grey-pink skin, smaller ears, tiny tusk nubs, big shiny eyes with long lashes, taller and stronger than Tommy.
- **Personality:** shy at first, then confident and amused. Very strong.
- **Costume:** magenta-and-yellow silk half-saree (pavadai-davani) with gold border, jasmine flowers on the head, small bindi, jhumka earrings, bangles.
- **VOICE TAG:** `sweet clear young Tamil female voice, around 22, shy and soft, giggly`

---

## 3. Character portrait prompts (generate these first)

Use Flow image generation, 16:9 or 4:5, one image per prompt.

### CH01 TOMMY portrait
```
Stylized 3D animated feature-film look, Pixar-quality. Head-and-shoulders portrait of Tommy, an anthropomorphic PUG dog character: fawn-cream short fur, black mask and black folded ears, wrinkled forehead, big round dark innocent eyes, cheeky half-smile, slightly chubby round face. Wearing a maroon silk full-sleeve shirt, a thin gold chain and a small tilak mark. Animal head and fur are fully dog, only the behaviour is human. Plain soft light-grey studio background, soft cinematic key light, sharp focus, 16:9.
SAVE AS: CH01_Tommy_Portrait.png
```

### CH02 RANGASAMY portrait
```
Stylized 3D animated feature-film look, Pixar-quality. Head-and-shoulders portrait of Rangasamy, an anthropomorphic ENGLISH BULLDOG father character, age 55: brown-and-white fur, heavy jowls, wrinkled flat face, small rose ears, thick white moustache, proud dramatic expression. Wearing round gold-rimmed glasses, vibhuti stripes on the forehead, a white full-sleeve shirt and an angavastram over the shoulder. Fully dog anatomy, human behaviour. Plain soft light-grey studio background, soft cinematic key light, sharp focus, 16:9.
SAVE AS: CH02_Rangasamy_Portrait.png
```

### CH03 GAJALAKSHMI portrait
```
Stylized 3D animated feature-film look, Pixar-quality. Head-and-shoulders portrait of Gajalakshmi, an anthropomorphic ASIAN ELEPHANT mother character, age 45: soft grey wrinkled skin, large ears, short trunk, small ivory tusks, kind eyes with long lashes, dignified warm smile. Wearing an emerald-green Kanjivaram silk saree with gold zari border, a red bindi, a jasmine garland on top of the head, gold earrings and bangles. Fully elephant anatomy, human behaviour. Plain soft light-grey studio background, soft cinematic key light, sharp focus, 16:9.
SAVE AS: CH03_Gajalakshmi_Portrait.png
```

### CH04 MULLAI portrait
```
Stylized 3D animated feature-film look, Pixar-quality. Head-and-shoulders portrait of Mullai, an anthropomorphic young ASIAN ELEPHANT girl, age 22: lighter grey-pink skin, smaller ears, short trunk, tiny tusk nubs, big shiny eyes with long lashes, shy sweet smile. Wearing a magenta-and-yellow silk half-saree (pavadai-davani) with gold border, jasmine flowers on the head, a small bindi, jhumka earrings and bangles. Fully elephant anatomy, human behaviour. Plain soft light-grey studio background, soft cinematic key light, sharp focus, 16:9.
SAVE AS: CH04_Mullai_Portrait.png
```

---

## 4. Six-angle turnaround prompts

**Ingredient to upload for every angle prompt:** that character's portrait image (CH0X_..._Portrait.png).
**Template** (replace `[ID]` with the identity line from the table, replace `[ANGLE]` and the file name):

```
Using the uploaded portrait as the exact reference, same character, same face, same fur/skin colours, same costume, same proportions. [ID]. Full-body character model sheet shot, [ANGLE], relaxed neutral standing pose, plain light-grey studio background, even soft lighting, no shadows on the wall, no text. Stylized 3D animated feature-film look, Pixar-quality, 16:9.
SAVE AS: [FILE]
```

**Identity lines [ID]**
| Char | [ID] |
|---|---|
| Tommy | chubby fawn-cream PUG in a maroon silk shirt, cream veshti with gold border, gold chain, curly tail visible |
| Rangasamy | stocky brown-and-white ENGLISH BULLDOG in white shirt, white veshti with gold-red border, angavastram, round gold glasses |
| Gajalakshmi | grey ASIAN ELEPHANT mother in an emerald-green Kanjivaram silk saree with gold border, jasmine garland, bindi |
| Mullai | young pink-grey ASIAN ELEPHANT girl in a magenta-and-yellow silk half-saree with gold border, jasmine flowers on head |

**Six angles ([ANGLE] and file suffix)**
| # | [ANGLE] | File suffix |
|---|---|---|
| A1 | straight front view | `_A1_Front.png` |
| A2 | three-quarter view from front-left | `_A2_3Q-Left.png` |
| A3 | left side profile view | `_A3_Left-Profile.png` |
| A4 | back view | `_A4_Back.png` |
| A5 | right side profile view | `_A5_Right-Profile.png` |
| A6 | three-quarter view from front-right | `_A6_3Q-Right.png` |

Full file names (24): `CH01_Tommy_A1_Front.png` … `CH01_Tommy_A6_3Q-Right.png`, `CH02_Rangasamy_A1_Front.png` …, `CH03_Gajalakshmi_A1_Front.png` …, `CH04_Mullai_A1_Front.png` …

Tip: keep the Portrait + A1 Front as your **go-to ingredients** for every later step. Use the other angles only if a pose goes wrong.

---

## 5. Environment prompts (no characters in them)

### ENV01 – Bride's house living room (Scene 1)
```
Stylized 3D animated feature-film look, Pixar-quality, warm morning light. Interior of a middle-class Tamil Nadu house living room, empty of characters: a wooden sofa set with crocheted white covers on the left, a cane sofa and two plastic chairs on the right, a low teapoy in the middle with a steel tray of tea tumblers, a plate of murukku and banana chips, red-oxide polished floor with a woven mat, pale green-yellow walls with framed god photos garlanded with flowers, a lit brass kuthuvilakku lamp, a family photo wall, a ceiling fan, a window with grille and sunlight beams, an open back door leading to the courtyard. Wide establishing shot, eye-level, 16:9, no text.
SAVE AS: ENV01_LivingRoom_Wide.png
```
Reverse angle (for variety):
```
Same living room as the uploaded reference, same objects and colours, now seen from the opposite side: the front door with a mango-leaf thoranam on the left and the sofa set from behind, empty of characters. Stylized 3D animated feature-film look, 16:9.
SAVE AS: ENV01_LivingRoom_Reverse.png
```

### ENV02 – Backyard courtyard with swing (Scene 2)
```
Stylized 3D animated feature-film look, Pixar-quality, golden-hour evening light. Backyard courtyard of a Tamil Nadu village house, empty of characters: a wooden oonjal swing hanging from a big neem tree, a white rice-flour kolam drawn on the ground, tulsi maadam, potted jasmine and hibiscus plants, coconut trees behind a low whitewashed compound wall, a clay water pot, a small open doorway to the house on the left, warm sunset rays. Medium-wide shot, eye-level, 16:9, no text.
SAVE AS: ENV02_Courtyard_Wide.png
```
Close angle:
```
Same courtyard as the uploaded reference, same objects and colours, closer view of the wooden swing and the kolam with the compound wall and coconut trees behind, empty of characters. Stylized 3D animated feature-film look, 16:9.
SAVE AS: ENV02_Courtyard_Swing.png
```

### ENV03 – Front veranda / thinnai (Scene 3)
```
Stylized 3D animated feature-film look, Pixar-quality, late-afternoon light. Front veranda (thinnai) of a Tamil Nadu house, empty of characters: raised red-oxide platform with wooden pillars, a wooden bench, a small gate and three steps down to a quiet street, an old white Ambassador car parked at the gate, mango-leaf thoranam over the door behind, coconut trees and tiled-roof houses across the street, a hanging bulb, a stray tiled floor with a kolam. Medium-wide shot, eye-level, 16:9, no text.
SAVE AS: ENV03_Veranda_Wide.png
```
Reverse angle:
```
Same veranda as the uploaded reference, same objects and colours, now seen from the street side looking up at the thinnai, wooden pillars and open front door, empty of characters. Stylized 3D animated feature-film look, 16:9.
SAVE AS: ENV03_Veranda_Reverse.png
```

---

## 6. Group images (to stay within the 3-ingredient limit)

### GRP01 – Groom family
**Ingredients:** CH01_Tommy_A1_Front.png, CH02_Rangasamy_A1_Front.png
```
Use the two uploaded characters exactly as they are, same faces, fur, costumes and proportions. Tommy the chubby fawn PUG and his father Rangasamy the stocky brown-and-white BULLDOG standing side by side, father slightly taller and proud, son holding a plate of murukku. Full body, front view, plain light-grey studio background, soft light. Stylized 3D animated feature-film look, Pixar-quality, 16:9.
SAVE AS: GRP01_GroomFamily.png
```

### GRP02 – Bride family
**Ingredients:** CH03_Gajalakshmi_A1_Front.png, CH04_Mullai_A1_Front.png
```
Use the two uploaded characters exactly as they are, same faces, skin, costumes and proportions. Gajalakshmi the elephant mother in the green Kanjivaram saree and her daughter Mullai the younger elephant in the magenta-and-yellow half-saree, standing side by side, mother with a warm smile, daughter shy. Both are clearly taller than a pug dog would be. Full body, front view, plain light-grey studio background, soft light. Stylized 3D animated feature-film look, Pixar-quality, 16:9.
SAVE AS: GRP02_BrideFamily.png
```

---

## 7. Scene reference (keyframe) image prompts

Each keyframe uses **3 ingredients**. It is also the first frame / main reference for the video of that shot.

### S01 – Living room
**Ingredients:** ENV01_LivingRoom_Wide.png, GRP01_GroomFamily.png, GRP02_BrideFamily.png

**S01-Shot01 keyframe**
```
Keep the uploaded living room exactly as it is. Place the uploaded characters inside it with their exact looks and costumes: the groom family (pug Tommy and bulldog father Rangasamy) sitting on the wooden sofa on the left, the bride family (elephant mother Gajalakshmi and elephant daughter Mullai) sitting on the cane sofa on the right. Rangasamy beams proudly with one hand on his knee. Tommy slouches, holding a murukku, mouth full. Mullai looks down shyly. Gajalakshmi smiles politely. Tea tumblers and snacks on the teapoy in between. Medium-wide shot, eye-level, warm morning light. Stylized 3D animated feature-film look, Pixar-quality, 16:9.
SAVE AS: S01_Shot01_KF.png
```

**S01-Shot02 keyframe**
```
Same living room and same characters as the uploaded references. Rangasamy the bulldog turns to his son with a big indulgent smile and a hand gesture. Tommy the pug looks up, lazily half-rising from the sofa with a snack in his paw. Mullai the elephant daughter sits shyly, hands folded. Gajalakshmi looks at her daughter and nods toward the back door. Medium shot, slightly lower angle, warm morning light. Stylized 3D animated feature-film look, Pixar-quality, 16:9.
SAVE AS: S01_Shot02_KF.png
```

### S02 – Courtyard
**Ingredients:** ENV02_Courtyard_Wide.png, CH01_Tommy_A1_Front.png, CH04_Mullai_A1_Front.png

**S02-Shot01 keyframe**
```
Keep the uploaded courtyard exactly as it is. Place the two uploaded characters in it, exact looks and costumes: Mullai the young elephant girl standing near the swing, much taller and bigger than Tommy; Tommy the chubby pug looking up at her with a cheeky, hopeful grin, standing close with arms stretched out slightly like a child asking to be picked up. Golden-hour light. Medium two-shot, camera slightly below Mullai's eye level. Stylized 3D animated feature-film look, Pixar-quality, 16:9.
SAVE AS: S02_Shot01_KF.png
```

**S02-Shot02 keyframe**
```
Same courtyard and same two characters as the uploaded references. Mullai the elephant girl lifts Tommy the pug effortlessly high above her head with both hands, one arm straight up, calm and amused. Tommy sits on her palm like a toy, arms spread wide, eyes shut, huge delighted grin. The swing and coconut trees behind them, golden-hour light. Medium shot, low angle. Stylized 3D animated feature-film look, Pixar-quality, 16:9.
SAVE AS: S02_Shot02_KF.png
```

### S03 – Veranda
**Ingredients:** ENV03_Veranda_Wide.png, GRP01_GroomFamily.png, GRP02_BrideFamily.png

**S03-Shot01 keyframe**
```
Keep the uploaded veranda exactly as it is. Place the uploaded characters in it with exact looks and costumes: Rangasamy the bulldog seated on the wooden bench with a tea tumbler, in the foreground; Tommy the pug running up to him with a dreamy lovesick grin, fur slightly messy, one paw on his heart; in the doorway behind, Gajalakshmi the elephant mother and Mullai the elephant daughter standing together, watching with curious smiles. Medium shot, late-afternoon light. Stylized 3D animated feature-film look, Pixar-quality, 16:9.
SAVE AS: S03_Shot01_KF.png
```

**S03-Shot02 keyframe**
```
Same veranda and same characters as the uploaded references. Close-medium shot of Rangasamy the bulldog on the bench, round glasses sliding down his nose, eyes wide, one paw slapping his own forehead in shock and disbelief, tea tumbler spilling. Tommy the pug beside him shrugs innocently with a cheeky grin. In the soft-focus background, Gajalakshmi covers her trunk with the saree pallu hiding a giggle, Mullai looks away trying not to laugh. Late-afternoon light. Stylized 3D animated feature-film look, Pixar-quality, 16:9.
SAVE AS: S03_Shot02_KF.png
```

---

## 8. Video prompts (Veo, 8 s each)

**Settings:** Ingredients to video, 16:9, 8 s, audio on. Upload the listed **3 ingredients** per shot. If a shot comes out inconsistent, switch to Frames to video with the keyframe as the first frame.
**Common ending in every prompt:** no subtitles, no on-screen text, no background music, only natural ambience.

### S01-Shot01
**Ingredients:** S01_Shot01_KF.png, CH02_Rangasamy_A1_Front.png, CH01_Tommy_A1_Front.png
```
Stylized 3D animated feature-film look, Pixar-quality. Interior of the Tamil living room from the uploaded reference. The groom family sits on the left sofa, the bride family on the right sofa. Rangasamy the bulldog father slaps his knee, beams proudly and says in Tamil, with clear lip-sync: "பொண்ணு எங்களுக்கு ரொம்ப புடுச்சிருக்கு". Voice: deep gravelly Tamil male voice, around 55, booming and dramatic, Kongu/Madurai-flavoured accent. Meanwhile Tommy the pug keeps chewing a murukku, crunching loudly, not listening; Mullai twists her half-saree edge shyly looking down; Gajalakshmi smiles politely and nods. Camera: slow push-in from medium-wide to medium on Rangasamy, then slight pan to Mullai at the end. Ambience: ceiling fan hum, distant temple bell, crows outside, tumbler clink. No subtitles, no on-screen text, no background music.
SAVE AS: S01_Shot01_LivingRoom_FatherLikesGirl.mp4
```

### S01-Shot02
**Ingredients:** S01_Shot02_KF.png, CH02_Rangasamy_A1_Front.png, CH04_Mullai_A1_Front.png
```
Stylized 3D animated feature-film look, Pixar-quality. Same living room and characters as the uploaded references. Rangasamy the bulldog turns to his son Tommy with an indulgent smile and says in Tamil, with clear lip-sync: "டாமி செல்லம் பொண்ணு கிட்ட தனியா பேசணும்னா பேசிட்டு வா". Voice: deep gravelly Tamil male voice, around 55, warm now and teasing. Tommy slowly stands, brushing murukku crumbs off his belly. Gajalakshmi gestures to the back door with her trunk, Mullai rises shyly, and the two walk out through the back door towards the courtyard, Tommy waddling behind her. Camera: medium shot, gentle tracking follow to the door. Ambience: ceiling fan hum, footsteps on floor, crows. No subtitles, no on-screen text, no background music.
SAVE AS: S01_Shot02_LivingRoom_GoTalkAlone.mp4
```

### S02-Shot01
**Ingredients:** S02_Shot01_KF.png, CH01_Tommy_A1_Front.png, CH04_Mullai_A1_Front.png
```
Stylized 3D animated feature-film look, Pixar-quality. Courtyard from the uploaded reference at golden hour. Tommy the chubby pug looks up at the much taller Mullai the elephant girl, holds out his arms like a child and asks in Tamil, with clear lip-sync: "உன்னால என்ன தூக்க முடியுமா ஆ?". Voice: young Tamil male voice, around 25, slightly nasal and whiny-sweet, lazy sing-song, cheeky and innocent. Mullai blinks in surprise, ears flapping once, then a small amused smile appears. Camera: medium two-shot, slight low angle, slow push-in on Mullai's reaction. Ambience: evening birds, a distant temple bell, leaves rustling, swing creak. No subtitles, no on-screen text, no background music.
SAVE AS: S02_Shot01_Courtyard_CanYouLiftMe.mp4
```

### S02-Shot02
**Ingredients:** S02_Shot02_KF.png, CH01_Tommy_A1_Front.png, CH04_Mullai_A1_Front.png
```
Stylized 3D animated feature-film look, Pixar-quality. Same courtyard and characters as the uploaded references. Mullai the elephant girl scoops Tommy the chubby pug up in one effortless motion and lifts him high above her head on her palm, calm and amused, as if he weighs nothing. Tommy spreads his arms wide, shuts his eyes and giggles with joy. She gently turns once in place, then sets him down on the wooden swing, which creaks and sways. Tommy gives a big happy sigh. No spoken dialogue, only Tommy's happy giggle (young Tamil male voice) and Mullai's soft chuckle (sweet young Tamil female voice). Camera: low-angle medium shot following the lift upward, then a smooth tilt down to the swing. Ambience: evening birds, swing creak, leaves. No subtitles, no on-screen text, no background music.
SAVE AS: S02_Shot02_Courtyard_LiftGag.mp4
```

### S03-Shot01
**Ingredients:** S03_Shot01_KF.png, CH01_Tommy_A1_Front.png, CH02_Rangasamy_A1_Front.png
```
Stylized 3D animated feature-film look, Pixar-quality. Front veranda from the uploaded reference in late-afternoon light. Tommy the pug waddles up to his father Rangasamy who sits on the bench with a tea tumbler. With a lovesick grin and a paw on his chest, Tommy says in Tamil, with clear lip-sync and fast excited delivery: "அப்பா எனக்கு இந்த பொண்ணு ரொம்ப ரொம்ப புடுச்சிருக்கு… சீக்கிரமா கல்யாணத்த ரெடி பண்ணுப்பா". Voice: young Tamil male voice, around 25, slightly nasal and whiny-sweet, lazy sing-song, cheeky. Rangasamy smiles proudly and nods, tea halfway to his mouth. In the doorway behind them Gajalakshmi and Mullai watch. Camera: medium shot, slow push-in on Tommy. Ambience: street sounds, a distant auto horn, crows. No subtitles, no on-screen text, no background music.
SAVE AS: S03_Shot01_Veranda_MarryMeOff.mp4
```
Tip: if Veo cuts the second half of the line, split the clip into two 8 s prompts (first sentence / second sentence) and join them in editing.

### S03-Shot02
**Ingredients:** S03_Shot02_KF.png, CH02_Rangasamy_A1_Front.png, CH01_Tommy_A1_Front.png
```
Stylized 3D animated feature-film look, Pixar-quality. Same veranda and characters as the uploaded references. Close-medium shot. Rangasamy the bulldog freezes, then his eyes bulge, his glasses slip down his nose, and he slaps his forehead as the tea spills from his tumbler. He shouts in Tamil, with clear lip-sync: "அடப்பாவி சண்டாளா! இதுக்கு தான் பொண்ணு பாக்க வந்தப்ப தூக்க சொன்னியா?". Voice: deep gravelly Tamil male voice, around 55, booming, dramatic, outraged and exasperated. Tommy shrugs innocently and shows a cheeky grin. In the soft-focus background Gajalakshmi hides a giggle behind her saree pallu and Mullai turns away trying not to laugh. Camera: starts close-medium on Rangasamy, quick shake-zoom on the shout, then a pull-back to include Tommy. Ambience: crow caw, street sounds, a tumbler clink. No subtitles, no on-screen text, no background music.
SAVE AS: S03_Shot02_Veranda_FatherReaction.mp4
```

---

## 9. Master file-name list

| Type | Names |
|---|---|
| Portraits | CH01_Tommy_Portrait, CH02_Rangasamy_Portrait, CH03_Gajalakshmi_Portrait, CH04_Mullai_Portrait |
| Angles (24) | CH0X_Name_A1_Front, A2_3Q-Left, A3_Left-Profile, A4_Back, A5_Right-Profile, A6_3Q-Right |
| Environments | ENV01_LivingRoom_Wide / _Reverse, ENV02_Courtyard_Wide / _Swing, ENV03_Veranda_Wide / _Reverse |
| Groups | GRP01_GroomFamily, GRP02_BrideFamily |
| Keyframes | S01_Shot01_KF, S01_Shot02_KF, S02_Shot01_KF, S02_Shot02_KF, S03_Shot01_KF, S03_Shot02_KF |
| Videos | S01_Shot01_LivingRoom_FatherLikesGirl, S01_Shot02_LivingRoom_GoTalkAlone, S02_Shot01_Courtyard_CanYouLiftMe, S02_Shot02_Courtyard_LiftGag, S03_Shot01_Veranda_MarryMeOff, S03_Shot02_Veranda_FatherReaction |

## 10. Quick fixes
- **Characters look human?** Add "animal head, snout/trunk, fur/skin, tail, no human face" to the prompt.
- **Size gag not visible?** Add "Mullai is twice Tommy's height".
- **Wrong Tamil on lips?** Keep the line short, put it in quotes, one speaker per clip, and dub with TTS if needed.
- **Costume drifting?** Always upload the A1 Front image of the speaking character.
