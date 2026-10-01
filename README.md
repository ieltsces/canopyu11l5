# English Practice: Unit 11 – Nature (2) 🏔️

An interactive practice website for young learners (4–10 years old).
Everything (pictures, code) is inside **one file**: `index.html`.

**Live demo:** `https://<your-username>.github.io/<repo-name>/`

## Contents

| Tab | Activity | What the child does |
|---|---|---|
| 1 📚 Vocabulary | Look, read and draw lines | Look at the picture, then click a sentence (1–7), then its ending (a–g). A coloured line joins correct pairs; wrong pairs shake. No score is shown. |
| 2 🖍️ Let’s draw | Read and complete the picture | Draw on the picture with crayons (10 colours, 3 sizes, eraser, undo, clear). 🔊 reads each instruction aloud; ☐ Done ticks it off. **Check my picture** opens 7 questions about the instructions (no score). 💾 saves the picture as PNG. |
| 3 💬 Let’s talk | Find the differences | Tap the pictures to circle differences. Write one difference in each of the 5 boxes. The checker looks at spelling, grammar and the pictures, and gives a hint question when the answer is wrong. |
| 4 ✏️ Reading & Writing | Write the animal words | Type or click a word from the box. Wrong answers get a hint question and a blinking circle on the picture. Correct words are crossed out in the box. |

## Answer keys

**Look, read and draw lines:** 1 f · 2 c · 3 a · 4 b · 5 g · 6 e · 7 d

**Check my picture (Let’s draw):** road – between the farm and the lake · men – at the top of the mountain · lorry – green · rocks – in front of the lake · clouds – two, grey · forest – behind the farm

**Find the differences (Picture A / Picture B):**

| # | Picture A | Picture B |
|---|---|---|
| 1 | two parrots | one parrot |
| 2 | a snake in the tree | a monkey in the tree |
| 3 | a lion on the rock | a bear on the rock |
| 4 | two tigers next to the water | two lions next to the water |
| 5 | ants on the rock | mice (rats) on the rock |

**Write the animal words:** (1) bear *(example)* · (2) fly · (3) giraffe · (4) hippo · (5) lion · (6) parrot · (7) kangaroo · (8) bat

## How the “find the differences” checker works

It checks each box in this order and shows **one** thing to fix at a time:

| Step | Example of a mistake | What the child sees |
|---|---|---|
| Spelling | *two parots* | red blinking letter / gap + 💡 Help |
| Grammar | *there is two parrots*, *two parrot*, *a ants*, *their are*, *Picture A there are…*, no verb | the wrong word blinks + short rule + 💡 Help |
| True for the pictures? | *In picture B there is a snake.* | “Look again! Can you see a snake in picture B?” + blinking circle |
| Is it a difference? | *In picture A there is a lion. In picture B there is a lion.* | “That is the same in both pictures” + hint question |
| Both pictures? | *In picture A there is a snake.* | “Now tell me about picture B too. What animal is in the tree in picture B?” |
| Capital letter / full stop | *in picture A …* / no “.” | red first letter / blinking box at the end |
| Same difference twice | two boxes about the parrots | “You already wrote about the parrots in box 1. Find a different one!” |

It accepts many ways of writing, e.g.
*In picture A there are two parrots, but in picture B there is one parrot.* ·
*Picture A has two parrots and picture B has one.* ·
*In picture A there is a snake but in picture B there isn’t.* ·
*In the first picture … in the second picture …* ·
*birds / rats / insects* for parrots / mice / ants.

## Project structure

```
index.html   ← the whole website (pictures embedded)
README.md
```

## How to publish on GitHub Pages

1. Create a new repository on GitHub (e.g. `unit11-nature-2`).
2. Upload `index.html` and `README.md`.
3. **Settings → Pages → Source:** `Deploy from a branch`, branch `main`, folder `/ (root)` → **Save**.
4. After about 1 minute open `https://<your-username>.github.io/unit11-nature-2/`.

## How to edit

Open `index.html` in a text editor and search for:

- `M_LEFT`, `M_RIGHT`, `M_KEY` – matching sentences and answers
- `INSTR` – drawing instructions; `CHQ` – “check my picture” questions (last number = correct option, 0 or 1)
- `FACTS` – how many of each animal are in picture A / B; `DIFFS` – names and hint questions of the 5 differences
- `R_KEY`, `R_HINT` – animal words answers and hint questions

## Notes

- Version is shown at the bottom of the page (v3). After uploading a new version, press **Ctrl + Shift + R** to reload.
- Answers are not saved; reloading the page starts again.
- 🔊 buttons use the browser’s voice (works best in Chrome / Edge / Safari).
- Pictures are from the course book and are for classroom use only.
