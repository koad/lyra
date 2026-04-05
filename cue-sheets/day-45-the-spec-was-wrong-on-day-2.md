---
title: "Music Cue Sheet — The Spec Was Wrong on Day 2"
video: day-45-the-spec-was-wrong-on-day-2
day: 45
director: Lyra
created: 2026-04-05
runtime-target: "8–10 minutes"
rufus-script: "~/.rufus/productions/day-45-the-spec-was-wrong-on-day-2/script.md"
arc: operational retrospective — Day 2
---

# Music Cue Sheet: "The Spec Was Wrong on Day 2"

## Video Overview

**Runtime target:** 8–10 minutes
**Emotional arc:** Forensic reconstruction, then satisfaction. Not triumph. The episode after the failure episode. Day 44 was a silent routing error. Day 45 is a different kind of wrong: a spec written before the thing it described existed, corrected the same day someone built against it. The satisfaction is the satisfaction of a test suite turning green — not excitement, not pride, just relief that the system works the way it claims to. The final spoken line is: "That is what `11abae4` is." Then 6 seconds of silence. Cut to black.

This is not a failure episode. The tone is analytical: forensic reconstruction through the evidence, then settled recognition of a feedback mechanism that worked. The six divergences are not proof that the spec-writing process is broken. They are proof that a first-draft spec is a hypothesis and that hypotheses require operational evidence to correct.

**Music direction for this video: ambient underscore in Segment 1 only — present from 0:00 and complete before or at the moment the git log output holds for 8 seconds of silence. Silence from the first evidence hold through end. No ambient return.**

---

## The Opening as a Music Problem

The video opens on a blank terminal. "On Day 2, Vesta shipped the trust bond spec." — 3 seconds. "On Day 4, Juno implemented 11 bonds against it." — 2 seconds. "The spec was wrong in six places." — 4 seconds of silence. Then: correction same session, field report same day, that is the entire story.

The ambient serves the window before the correction sequence lands on screen — the viewer is watching the claim be stated in plain terms before the git log renders the evidence. The ambient provides the room in which "the spec was wrong in six places" can register before the viewer sees the commits that prove it.

The fade must be complete before the git log output holds. When the correction sequence is on screen — `cdd8181` (Day 2, spec written) and `11abae4` (Day 4, spec corrected) visible simultaneously — the viewer needs to read the commit messages and locate the two-day span. The ambient must be gone for that reading.

Everything from Segment 2's git log hold through Segment 6's final cut to black requires silence. The money shot is two commits in the same screen. The viewer reads the messages and understands the entire story without narration. Music during the hold would score the correction before the viewer has read it.

---

## Why Ambient Cannot Continue Past the Git Log Hold

The git log renders and holds for 8 seconds. This is the central terminal scene of the episode — the viewer locating the correction sequence: `cdd8181` at the bottom (Day 2, the hypothesis), `11abae4` just above it (Day 4, the correction, +135/-45), then two more corrections above that from the same session. Three specs corrected in one session. One git log.

The script direction is explicit: "Do not narrate. Let the viewer locate the sequence." Music during the hold would direct the viewer's attention before the viewer has found the pattern. The satisfaction of seeing the loop close in the git log is in the git log. The viewer reads it. That experience requires silence.

Everything from the git log hold through the close requires silence for the same reason:

- The `git show 11abae4 --stat` output in Segment 3 holds for 6 seconds. The viewer is reading the commit message and file stats — one file, 135 lines added, 45 removed. The commit message names all corrections explicitly. Music here would score the correction as significant before the viewer has read what was corrected.
- Segments 4 and 5 run over blank terminal. The narration is the theoretical payload: spec bends to lived system, the informality of the loop is a constraint worth naming, the async gap is still open. Each statement requires the space it is given.
- Segment 6 is the close. "The loop is the mechanism. The mechanism is the infrastructure." is the theoretical claim that closes the argument. "That is what `11abae4` is." is the final line. Ambient return would import warmth into what Rufus calls "no inflection, statement, then silence."

No ambient return.

---

## The Correction Sequence as the Money Shot

In Day 45, the money shot is not a gap. It is the opposite: the git log showing the hypothesis (`cdd8181`) and the correction (`11abae4`) in the same screen, two days apart, the correction committed within the same session as the implementation that revealed the errors. The viewer should be able to read the commit messages and understand the entire story without narration.

The secondary evidence scene — `git show 11abae4 --stat` rendering the size and scope of the correction — anchors the six divergences as a concrete record. One file. 135 additions. 45 deletions. The commit message names four of the six corrections explicitly.

Segments 4 and 5 run over blank terminal with no commands typed. Segment 4 is the analytical payload — spec as hypothesis, spec bends to lived system, the distinction between correct-on-paper and broken-on-disk. Segment 5 is the honest accounting — the loop worked informally, the async gap is not yet closed. Segment 6 closes on the git log hashes named as dates in the record.

No commands will be typed during Segments 4, 5, or 6. The blank terminal keeps the close grounded as technical content throughout.

---

## Comparison with Prior Videos

Day 30: No music. Forensic. Git log as argument.
Day 36: No music. Three bond files. Governance is files on disk.
Day 37: Ambient in opening only. PRIMER framing. Evidence in silence.
Day 38: Ambient in opening only. Coordination problem raised. Evidence in silence.
Day 39: Ambient in opening only. Protocol demonstrated. Evidence in silence.
Day 40: Ambient in opening only. Sovereignty argument. Evidence in silence.
Day 41: Ambient in opening only. Architecture audit. Evidence in silence.
Day 42: Ambient in opening only. Verification sequence. Evidence in silence.
Day 43: Ambient in opening only. Arc closure. Architecture in silence.
Day 44: Ambient in opening only. Operational retrospective (failure). Evidence in silence.
Day 45: Ambient in opening only. Operational retrospective (loop closure). Evidence in silence.

Day 45 continues the retrospective arc. Its ambient pattern matches Days 37–44: opening only, complete before first evidence hold, silence through close. The satisfaction of the loop closure must not be scored — it is the same low-register satisfaction you feel when a test suite turns green, not a triumph, and music would elevate it past what it actually is.

Decision: ambient opening only. Complete before the git log holds for 8 seconds. Silence through the 6-second post-close hold and cut to black.

---

## Segment-by-Segment Direction

### Segment 1 — The Claim (0:00–1:00)

Blank terminal. Five declarative sentences. Day 2, Day 4, six places, same session, that is the entire story.

**Music: low ambient underscore, enter at 0:00.**

The ambient serves the window from "On Day 2, Vesta shipped the trust bond spec." through the four-sentence claim — the viewer is watching the entire story be stated in plain terms before the evidence renders. The ambient provides the room in which "the spec was wrong in six places" can register as a claim before the git log confirms it.

Fade begins as Segment 2's narration opens ("The claim this operation makes about specs..."). The fade must be complete before the git log is executed and the 8-second hold begins. When the correction sequence is on screen, the ambient must be gone. The reading moment requires silence.

Style: non-melodic ambient, same character as the Days 37–44 series. No melody, no chord progression, no pulse, no rhythm. Cool to neutral.
Level: -18 to -20 dB under voice. Texture only.
Fade: begin at or before the transition into Segment 2. Complete before or at the moment the git log output holds.

### Segment 2 — The Correction Sequence (1:00–3:30) — CENTRAL TERMINAL SCENE

Screen cleared. Claim about what this operation does differently narrated. "Look at the record." — 2-second pause. `git -C /home/koad/.vesta log --oneline` typed and executed. Output renders. 8-second hold. Then narration — forensic.

**Music: none.**

The git log is the central terminal scene. The 8-second hold is mandatory. Do not narrate. Do not score. The viewer is locating the correction sequence.

"There it is." — 4-second pause. Short. Flat. Not triumphant. Observation only.

Each narration beat after annotates the sequence: `cdd8181` at the bottom named (Day 2, spec written before a single bond existed), `11abae4` named (April 2nd, Day 4, the correction), then the two additional corrections from the same session.

"The loop closed in hours." — 4-second silence. Segment 2 close. Stated flat. Silence.

### Segment 3 — The Six Divergences (3:30–5:45) — FIELD REPORT TERMINAL SCENE

Screen cleared. Field report framing narrated. "The document reads like a unit test reporting failures." — 2-second pause. `git -C /home/koad/.vesta show 11abae4 --stat` typed and executed. Output holds 6 seconds. Then the six divergences named as distinct beats.

**Music: none.**

The `git show --stat` output is the correction made visible: one file, 135 additions, 45 deletions, commit message naming the corrections explicitly. The 6-second hold is the reading moment. Silence throughout.

After the hold: "One file. One hundred and thirty-five lines added. Forty-five removed." — 3-second pause. Silence.

Each of the six divergences is a distinct beat. Do not run them together. The list is the unit test output — concise, attributed, factual:

- File extension (.signed vs .md + .md.asc) — 3-second pause. Silence.
- Naming convention (grantor-type buries grantee, grantor-to-grantee preserves it) — 3-second pause. Silence.
- Missing peer bond type (most common type in the system, absent from spec) — 4-second silence. Silence.
- Two signing procedures (Keybase for humans, GPG for AI — two security models, not one) — 3-second pause. Silence.
- Status tracking absent; implementation notes absent — both added in `11abae4`. — 4-second silence. Silence.

"Six predictions. Six corrections. All in one commit. All in one session." — 4-second silence. Segment 3 close. Silence.

### Segment 4 — Why the Spec Was Wrong (5:45–7:15)

Blank terminal. No command typed. Analytical payload.

**Music: none.**

"The spec was not wrong because Vesta made errors." — 3-second pause. Silence.
The first-draft spec as hypothesis explained: written before the implementation, corrected when building reports back. — 4-second silence. Silence.

Each gap explained in its structural terms: peer bond type missing because the team didn't exist yet as concrete relationships; naming convention failure only visible once you have 11 bonds to search. — 4-second silence. Silence.

**"The design principle that emerged from this: when spec and lived system disagree, the lived system is the source of truth."** — 3-second pause. Silence.
**"Spec bends to lived system. Not the other way."** — 4-second silence. Pivot line. Flat. Silence.

Standard approach described and its failure explained: spec defines truth, implementation deviates, implementation gets fixed — fails when spec predates the implementation. — 3-second pause. Silence.

**"If Juno had conformed to the spec rather than documenting divergence, the trust bond system would have `.signed` files no GPG tool produces, a naming scheme that loses the grantee at filing time, and eight bonds with an undefined type. Correct on paper. Broken on disk."** — 4-second silence. Segment 4 close. Each half paired: "Correct on paper." pause. "Broken on disk." Silence.

### Segment 5 — The Loop Requirement (7:15–8:30)

Blank terminal. Honest accounting.

**Music: none.**

"The loop worked in this case because Juno and Vesta were actively collaborating in real time." — 3-second pause. Silence.
The informal mechanism described: committed log file, direct conversation, same session. — 4-second silence. Silence.

"That informality is a constraint worth naming." — 2-second pause. Silence.
"The loop worked because both entities treated it as a priority. It would not survive a less active implementation phase." — 3-second pause. Silence.

The still-open question named: Vulcan builds, Vesta maintains specs, two entities with no shared session, the bounded-timeframe guarantee does not exist. — 4-second silence. Silence.

"The six divergences in the trust bond spec are not proof that the spec-writing process is broken." — 2-second pause. Silence.
"They are proof that a first-draft spec is a hypothesis and that hypotheses require operational evidence to correct." — 3-second pause. Silence.

"The evidence mechanism that worked on Day 4 was informal. The correction was immediate." — 4-second silence. Silence.
"Making that pattern reliable at scale — across entities that don't share sessions, on specs that cover systems not yet built — is the design problem that Day 4 raised." — 3-second pause. Silence.

**"And did not fully solve."** — 4-second silence. Do not soften. Silence.

### Segment 6 — The Record (8:30–9:30) — CLOSING

Blank terminal. Very slow. Each line stands alone.

**Music: none.**

"The trust bond spec was wrong from Day 2 until Day 4." — 3-second pause. Silence.
"Written on a Tuesday. Corrected the following Thursday." — 2-second pause. Silence.
"Within the same session as the implementation that revealed the errors." — 4-second silence. Silence.

"The git log is the audit trail." — 2-second pause. Silence.
"`cdd8181` — spec written, Day 2. Field report filed. `11abae4` — spec corrected, Day 4. Time elapsed: two days, one session." — 4-second silence. Hashes read as dates in the record. Silence.

"The correction is committed. The trust bonds are canonical. The spec that Vesta maintains now reflects what the implementation actually does, because the implementation ran and reported back." — 3-second pause. Silence.

**"The loop is the mechanism."** — 2-second pause. Silence.
**"The mechanism is the infrastructure."** — 4-second silence. Paired. Do not rush. The theoretical close. Silence.

**"That is what `11abae4` is."**

**[6 seconds of silence. Blank terminal on screen. Cut to black. No fade. No music. No title card.]**

---

## Cue List

| Timecode | Scene | Emotion | Music | Notes |
|----------|-------|---------|-------|-------|
| 0:00 | Blank terminal, prompt only | The claim arriving | Ambient in | Non-melodic, -18 to -20 dB. Viewer about to watch the story of a spec that was wrong before the evidence renders. |
| 0:03 | VO: "On Day 2, Vesta shipped the trust bond spec." | Day 2 | Ambient at floor | 3-second silence after. Ambient holds. |
| 0:09 | VO: "On Day 4, Juno implemented 11 bonds against it." | Day 4 | Ambient at floor | 2-second silence after. Ambient holds. |
| 0:13 | VO: "The spec was wrong in six places." | The claim | Ambient at floor | 4-SECOND SILENCE after. The weight of the claim. Ambient holds. |
| 0:21 | VO: pause — 4 seconds | Claim held | Ambient at floor | Do not fill. Ambient continues. |
| 0:25 | VO: "Juno found all six during implementation, wrote a field report, and Vesta issued the corrections the same session." | Resolution stated | Ambient at floor | 3-second pause after. Ambient continues. |
| 0:33 | VO: "That is the entire story. The rest of this video is the evidence." | Frame | Ambient completing | Fade begins as Segment 2 narration opens. |
| 0:40 | VO: pause — 4 seconds | Frame held | Ambient completing | Do not fill. Fade continues. |
| 1:00 | VO: "The claim this operation makes about specs..." | Segment 2 narration begins | Ambient completing | Fade must complete before git log output holds. |
| 1:20 | `git -C /home/koad/.vesta log --oneline` typed | Command forming | Ambient complete | Silence while typing. Ambient complete before execute. |
| 1:28 | [Execute. Output renders fully.] | Git log on screen | None | Do not interrupt. |
| 1:30 | HOLD — 8 seconds on output | CENTRAL TERMINAL SCENE — THE CORRECTION SEQUENCE | None | 8 FULL SECONDS per script. The central terminal scene. Do not narrate. Do not score. Viewer locates cdd8181 → 11abae4. |
| 1:38 | VO: "There it is." | Sequence found | None | 4-second pause after. Flat. Not triumphant. Observation only. Silence. |
| 1:42 | VO: pause — 4 seconds | Observed | None | Do not fill. |
| 1:46 | VO: "Day 2 at the bottom: `cdd8181` — 'Draft onboarding package.'" | Day 2 named | None | 3-second pause after. Silence. |
| 1:54 | VO: "Four commits up: `11abae4` — 'Reconcile trust.md with field report...' That's April 2nd. That's Day 4." | Day 4 named | None | 3-second pause after. Silence. |
| 2:04 | VO: "Then `110679f` — three bugs in team.md. Then `8334549` — commands.md. All three corrections in the same session." | Three corrections | None | 4-SECOND SILENCE after. Silence. |
| 2:16 | VO: "The loop closed in hours." | Segment 2 close | None | 4-SECOND SILENCE after. Stated flat. Silence. |
| 2:24 | [Screen cleared.] | Transition to Segment 3 | None | In silence. |
| 2:26 | VO: "The mechanism that closed the loop is a field report." | Segment 3 opens | None | 3-second pause after. Silence. |
| 2:34 | VO: Field report framing | The document described | None | Silence. |
| 2:46 | VO: "The document reads like a unit test reporting failures." | The framing | None | 2-second pause after. Silence. |
| 2:50 | `git -C /home/koad/.vesta show 11abae4 --stat` typed | Command forming | None | Silence while typing. |
| 3:04 | [Execute. Commit message and file stats render.] | Correction stats on screen | None | Do not interrupt. |
| 3:06 | HOLD — 6 seconds on output | Post-render hold | None | Reading moment. One file. +135/-45. Commit message names corrections explicitly. Silence. |
| 3:12 | VO: "One file. One hundred and thirty-five lines added. Forty-five removed." | Stats read | None | 3-second pause after. Silence. |
| 3:18 | VO: "The commit message names the corrections explicitly: fix format, fix naming, add peer type, document signing UX." | Four of six named | None | 3-second pause after. Silence. |
| 3:26 | VO: "Those are four of the six divergences. Here is what each one actually was." | Into the list | None | 2-second pause after. Silence. |
| 3:31 | VO: First divergence — file extension | Item 1 | None | 3-second pause after. Stated concisely. Silence. |
| 3:40 | VO: Second divergence — naming convention | Item 2 | None | 3-second pause after. Silence. |
| 3:50 | VO: Third divergence — missing peer bond type | Item 3 | None | 4-SECOND SILENCE after. "The most common type in the system was absent." Silence. |
| 3:58 | VO: Fourth divergence — two signing procedures | Item 4 | None | 3-second pause after. "Two security models, not one." Silence. |
| 4:08 | VO: Items 5 and 6 — status tracking, implementation notes | Items 5 and 6 | None | 4-SECOND SILENCE after. Silence. |
| 4:18 | VO: "Six predictions. Six corrections. All in one commit. All in one session." | Segment 3 close | None | 4-SECOND SILENCE after. Silence. |
| 4:28 | [Screen cleared. Blank terminal. No more commands.] | SEGMENT 4 BEGINS | None | Blank terminal persists through end. Do not fill. |
| 4:34 | VO: "The spec was not wrong because Vesta made errors." | Segment 4 opens | None | 3-second pause after. Against blank terminal. Silence. |
| 4:40 | VO: First-draft spec as hypothesis explained | The argument | None | 4-SECOND SILENCE after. Blank terminal. Silence. |
| 4:52 | VO: Peer bond gap explained structurally | Item 3 explained | None | 3-second pause after. Silence. |
| 5:00 | VO: Naming convention failure explained | Item 2 explained | None | 4-SECOND SILENCE after. Silence. |
| 5:10 | VO: "The design principle that emerged from this: when spec and lived system disagree, the lived system is the source of truth." | THE PRINCIPLE | None | 3-second pause after. Blank terminal. Silence. |
| 5:18 | VO: "Spec bends to lived system. Not the other way." | PIVOT LINE | None | 4-SECOND SILENCE after. Flat. The principle in its shortest form. Silence. |
| 5:26 | VO: Standard approach described and its failure | Inversion | None | 3-second pause after. Silence. |
| 5:36 | VO: "If Juno had conformed to the spec..." | The consequence | None | Silence. |
| 5:48 | VO: "Correct on paper." | First half | None | Pause between the two halves. Silence. |
| 5:51 | VO: "Broken on disk." | Second half | None | 4-SECOND SILENCE after. Segment 4 close. Silence. |
| 6:00 | VO: "The loop worked in this case because Juno and Vesta were actively collaborating in real time." | Segment 5 opens | None | 3-second pause after. Against blank terminal. Silence. |
| 6:08 | VO: Informal mechanism described | The mechanism | None | 4-SECOND SILENCE after. Blank terminal. Silence. |
| 6:18 | VO: "That informality is a constraint worth naming." | Honest | None | 2-second pause after. Silence. |
| 6:22 | VO: "The loop worked because both entities treated it as a priority." | The condition | None | 3-second pause after. Silence. |
| 6:30 | VO: The still-open question — async gap | The gap | None | 4-SECOND SILENCE after. Blank terminal. Silence. |
| 6:44 | VO: "The six divergences in the trust bond spec are not proof that the spec-writing process is broken." | Reframed | None | 2-second pause after. Silence. |
| 6:49 | VO: "They are proof that a first-draft spec is a hypothesis and that hypotheses require operational evidence to correct." | The argument | None | 3-second pause after. Silence. |
| 6:58 | VO: "The evidence mechanism that worked on Day 4 was informal. The correction was immediate." | The state | None | 4-SECOND SILENCE after. Silence. |
| 7:08 | VO: "Making that pattern reliable at scale..." | The open problem | None | 3-second pause after. Silence. |
| 7:16 | VO: "And did not fully solve." | THE HONEST CLOSE | None | 4-SECOND SILENCE after. Do not soften. Blank terminal. Silence. |
| 7:26 | VO: "The trust bond spec was wrong from Day 2 until Day 4." | CLOSING BEGINS | None | 3-second pause after. Against blank terminal. Silence. |
| 7:32 | VO: "Written on a Tuesday. Corrected the following Thursday." | The timeline | None | 2-second pause after. Silence. |
| 7:36 | VO: "Within the same session as the implementation that revealed the errors." | The compression | None | 4-SECOND SILENCE after. Silence. |
| 7:44 | VO: "The git log is the audit trail." | Named | None | 2-second pause after. Silence. |
| 7:48 | VO: "`cdd8181` — spec written, Day 2. Field report filed. `11abae4` — spec corrected, Day 4. Time elapsed: two days, one session." | The hashes as dates | None | 4-SECOND SILENCE after. Silence. |
| 7:58 | VO: "The correction is committed. The trust bonds are canonical. The spec that Vesta maintains now reflects what the implementation actually does, because the implementation ran and reported back." | The state | None | 3-second pause after. Silence. |
| 8:08 | VO: "The loop is the mechanism." | First half | None | 2-second pause after. Paired. Do not rush. Silence. |
| 8:12 | VO: "The mechanism is the infrastructure." | Second half | None | 4-SECOND SILENCE after. The theoretical close. Silence. |
| 8:20 | VO: "That is what `11abae4` is." | THE FINAL LINE | None | No inflection. Statement. No ambient. No fade. |
| 8:21 | SILENCE — 6 seconds | Pre-cut hold | None | 6 FULL SECONDS per script. Blank terminal on screen. The silence is the close. |
| 8:27 | Cut to black | End | None | No fade. No music. No title card. Hard cut. |

---

## The Ambient Opening Decision

Day 45 is the episode after the failure episode. The video opens on a blank terminal and states the entire story in five sentences before any evidence renders. The ambient opening serves the window in which "the spec was wrong in six places" can register as a claim — the viewer watching the complete narrative arc be stated upfront, before the git log confirms it.

Days 37–44 each warranted ambient because they opened with framing before evidence. Day 45's framing is a claim followed immediately by its resolution: wrong in six places, corrections same session. The ambient provides the room in which that compression — from Day 2 hypothesis to Day 4 correction, two days, one session — can register as a compressed timeline before the record expands it.

The close is satisfaction: the loop closed, the correction committed, the mechanism working. Ambient return would convert satisfaction into warmth. The satisfaction in this video is the satisfaction you feel when a test suite turns green — not warm, not triumphant, just: relief that the system works the way it claims to. The final line is a statement naming a specific commit. The 6 seconds of silence that follow are the close.

Decision: ambient opening only. Complete before the git log holds for 8 seconds. Silence through the 6-second post-close hold and cut to black.

---

## Silence Notes for the Editor

**The mandatory holds (per Rufus script):**

1. **Git log output hold — 8 seconds (Segment 2):** THE CENTRAL TERMINAL SCENE. The correction sequence. Do not narrate. Do not score. The viewer is locating `cdd8181` → `11abae4`. Do not abbreviate.
2. **`git show 11abae4 --stat` output hold — 6 seconds (Segment 3):** Reading moment. One file. 135 additions. 45 deletions. Commit message names corrections explicitly. Silence.
3. **Six divergences — each item is a distinct beat (Segment 3):** Do not run them together. The list is the unit test output. Present each item concisely, then pause. Silence between each.
4. **Closing: each clause stands alone (Segment 6):** "The loop is the mechanism. The mechanism is the infrastructure." — paired lines, do not rush, each gets its own beat. "`cdd8181`... `11abae4`..." — read as dates in the record, not technical minutiae.

**The key sentences requiring silence (do not score):**

- "The spec was wrong in six places." (Segment 1 — followed by 4 seconds of silence; the claim before the evidence)
- "The loop closed in hours." (Segment 2 — the summary of the correction sequence; stated flat)
- "Spec bends to lived system. Not the other way." (Segment 4 — the pivot line; slow, flat, let it stand alone)
- "Correct on paper. Broken on disk." (Segment 4 — paired; pause between them; each gets its own beat)
- "And did not fully solve." (Segment 5 — the honest accounting of the async gap; do not soften)
- "The loop is the mechanism." / "The mechanism is the infrastructure." (Segment 6 — paired; do not rush; the theoretical close)
- "That is what `11abae4` is." (Segment 6 — the final line; no inflection; followed by 6 seconds of silence and cut to black)

**The blank terminal in Segments 4, 5, and 6:**

No commands are typed after Segment 3. The blank terminal is the visual anchor — the narration is grounded as technical content through the theoretical close. Resist any impulse to fill the screen. The blank terminal through the final three segments is intentional.

**The ambient opening:**

Enters at 0:00. Serves the window from "On Day 2, Vesta shipped the trust bond spec." through the five-sentence claim — the viewer watching the complete story stated before the evidence renders. Provides the room in which the claim registers before the git log confirms it.

Fade must begin at or before the transition into Segment 2 narration. Complete before or at the moment the git log output holds for 8 seconds. The correction sequence must appear in silence.

Level: -18 to -20 dB under voice. Texture only. No melody, no chord progression, no pulse, no rhythm. Cool to neutral.

---

*Lyra — music direction for koad:io*
