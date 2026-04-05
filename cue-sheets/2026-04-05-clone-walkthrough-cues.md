---
title: "Music Cue Sheet — I Cloned a koad:io Entity"
video: 2026-04-05-clone-walkthrough
director: Lyra
created: 2026-04-05
runtime-target: "5–8 minutes"
---

# Music Cue Sheet: "I Cloned a koad:io Entity"

## Video Overview

**Runtime target:** 5–8 minutes
**Emotional arc:** Quiet curiosity → technical grounding → slow revelation → earned stillness. A viewer who has never seen an AI entity before arrives skeptical and leaves understanding something they can touch.

---

## Cue List

| Timecode | Scene | Emotion | Track style | BPM range | Notes |
|----------|-------|---------|-------------|-----------|-------|
| 0:00 | Empty terminal, cursor blinking | Anticipation, focus | Sparse ambient — single sustained tone, no rhythm | — | Music under but barely there. Viewer is reading the screen. Do not compete. |
| 0:05 | VO begins: "I want to show you something" | Curious, unhurried | Ambient pads, no percussion, slow filter sweep | — | Low in mix. Establishes the 2am-working atmosphere. |
| 0:20 | `git clone` command typed | Focused intent | Same pad, maybe a faint high-frequency texture enters | — | The act of typing should feel deliberate, not dramatic. |
| 0:35 | Clone output scrolling | Latency, patience | Hold the texture — no changes | — | Let the scroll breathe. No musical punctuation here. |
| 0:45 | `cd ~/.chiron-demo && ls` — directory reveals | Quiet discovery | Introduce a gentle melodic element — single-note motif, soft | 70–80 | A moment of "here it is." Low energy, not triumphant. |
| 1:15 | `cat README.md` scrolling — "Named for the centaur..." | Intellectual warmth | Same motif continues, slight harmonic lift | 70–80 | Reader is absorbing. Music matches the rhythm of reading. |
| 1:45 | `cat CLAUDE.md` — "the entity brief" | Structural clarity | Strip back to pads only — melodic element exits | — | Technical content. Music steps back. |
| 2:00 | SEGMENT 3: `cat hooks/...` — the hook code | Technical depth | Minimal — low drone, no movement | — | Most technical segment. Music nearly absent. Don't editorialize. |
| 2:30 | PID lock explanation in VO | Slight tension | Faint rhythmic texture — very soft, irregular pulse | — | Not dramatic tension. More like: something is running. |
| 2:45 | SEGMENT 4: `PROMPT='what is your role?' chiron` | Expectant wait | Return to pads — release the rhythmic texture | — | The invocation is quiet. This is a request, not a launch. |
| 3:00 | Inference waiting — cursor sitting | Patience, wonder | Soft evolving pad — slow modulation, no rhythm | — | The model is thinking. Don't fill this with energy. Let the wait breathe. |
| 3:30 | Chiron's response begins to appear | Revelation — earned | Gentle melodic lift — same motif from 0:45, slightly fuller | 70–80 | This is the payoff. Music acknowledges it but doesn't oversell it. |
| 4:00 | VO: "That's not me typing a system prompt — that's his memory" | Realization | Motif crests, then begins fading | — | Peak emotional moment. Brief. Then begin descent. |
| 4:30 | SEGMENT 5: `pwd` — `/home/[you]/.chiron-demo` | Stillness | Music fades to near-silence — pad sustain only | — | The simplest command. The most weight. Music mirrors that. |
| 4:45 | VO: "That's it." — pause | Deep stillness | Nearly silent — barely audible room tone or single sustained note | — | Let the pauses in VO exist without musical support. |
| 5:00 | VO: "Files on disk." — final beats | Resolution | Music out entirely, or final note held and released | — | By the last sentence, music should be gone. Silence is the closer. |
| 5:15 | Fade to black / outro slate | End | Silence, or a single ambient fade-out under title card | — | No music over the GitHub URL. Let the viewer sit. |

---

## Opening Music Brief

**What the first 5 seconds should feel like:**

Someone in a dark room, late at night, about to show you something they built. Not nervous — they know it works. There's a terminal on screen with nothing in it yet. The music should feel like the moment before a question is asked, not the moment before an explosion. Very low volume. A sustained pad, possibly with a slight high-frequency shimmer. Tempo-free. No attack, no rhythm. The viewer should barely notice the music is there — they should only notice it if it stopped.

---

## Key Transition Points

**1. 0:45 — The directory reveals (`ls` output appears)**
The clone completed. The directory is on disk. This is the first proof moment — when the abstract claim ("I'm going to show you something") becomes concrete. The melodic motif should enter here, soft and unhurried. Timing: music enters on the first line of `ls` output, not before. If it enters a beat early it reads as manufactured drama.

**2. 3:30 — Chiron's response begins to appear**
The model has been running. Now the output starts. This is the emotional payoff of the entire video — an entity knowing its own identity. The motif from 0:45 should return here, slightly fuller, as if the same idea arrived at its destination. Timing: the first word of Chiron's output appearing onscreen. Not the moment the command was run.

**3. 4:30 — `pwd` — one final command**
The script calls this out explicitly: "pacing matters most." The music should already be retreating. By the time VO reaches "That's it." — the first line of the close — music should be low enough that the silence between sentences is felt. Each VO pause is structural. The editor keeps them. Music must not fill them.

---

## Closing Brief

**How the video should feel in its final 10 seconds:**

The VO has ended. The viewer is looking at a terminal showing `/home/[you]/.chiron-demo`. Possibly a fade to black, possibly a static slate with `github.com/koad/chiron`. The music, if still present, should be a single held tone decaying — not resolving into a chord, not fading up. Just leaving. The emotional note is not triumph. It's quiet competence. The system works the way it was supposed to work. That's enough.

No music over the GitHub URL. Let the viewer sit with what they just saw.

---

## Source Suggestions

1. **Slow ambient pad, no drums, no melody** — C or D major tonality, long attack/release, 3–4 layered sine-like tones, light reverb. The kind of thing that sits under narration without calling attention to itself. Target: barely audible at -25dB under VO.

2. **Minimalist lo-fi ambient, 70–80 BPM, finger-picked or plucked single-note motif** — think late-night coding music. Nylon string, kalimba, or soft electric piano. Single notes only — no chords that feel editorial. Should feel like someone humming to themselves while working.

3. **Sparse electronic ambient, no drums, generative feel** — slow filter sweeps, occasional pitch-shifted texture. Good for the inference-wait section (Segment 4, 2:45–3:30). Nothing rhythmic. Should feel like computation happening quietly.

4. **Evolving drone, one or two notes, low register** — for the most technical segment (Segment 3, the hook code). Near-subliminal. The kind of track that disappears when you focus but is present when you don't. Avoids the feeling of "musical silence."

5. **Ambient outro, slow decay** — a single sustained note or chord that decays over 15–20 seconds. For the final close (4:30 onward). Should feel like the room after a conversation ends, not a credits roll.

---

*Lyra — music direction for koad:io*
