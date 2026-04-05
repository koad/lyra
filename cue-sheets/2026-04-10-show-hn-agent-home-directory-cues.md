---
title: "Music Cue Sheet — Show HN: Agent Home Directory"
video: 2026-04-10-show-hn-agent-home-directory
director: Lyra
created: 2026-04-05
runtime-target: "4–6 minutes"
---

# Music Cue Sheet: "Show HN: Agent Home Directory"

## Video Overview

**Runtime target:** 4–6 minutes
**Emotional arc:** Quiet provocation → grounded evidence → accumulating weight → stillness → invitation. The tightest video in the series. Three commands, voice-over live, no title cards. The script explicitly states: "No music. No end card." The Rufus production notes confirm it: "Post: No color correction. Trim dead air only. No B-roll. No music."

**Music direction for this video: no music.**

This is not a failure of direction — it is the direction. The decision earns its own explanation.

---

## Why No Music

The other videos in this series — the clone walkthrough, the $200 laptop experiment, the Sibyl session — all carry music because they have sections where a viewer's patience needs ambient support: inference waits, code scrolling, long technical segments with no narration. This video has none of those. It is four to six minutes of voice-over live over deliberate terminal commands. Every second has either a command being typed, output on screen, or a spoken line that the viewer must process. There is no dead air to fill and no patience to support.

More specifically: the emotional core of this video is the git log scroll. The script says "DO NOT CUT, DO NOT SPEED RAMP — full scroll is the emotional core." The $200 Laptop cue sheet placed the musical peak of that video over the git log scroll. This video has the same shot — but this video's script says no music. That restraint is intentional. When the $200 Laptop video peaks its music over the git log, it acknowledges the accumulation. When this video runs the git log in silence, the accumulation carries itself. The viewer hears only the voice-over and the terminal. 213 commits scrolling without a score behind them is a different argument than 213 commits with music acknowledging how impressive that is. The script chose silence. That is the right call.

The closing beat confirms it: "Fade to black — no music, no end card." Rufus wrote that specifically. The video ends on a terminal. No sound.

---

## Cue List

This table is provided for completeness and for any future editorial review. All cues are: no music.

| Timecode | Scene | Emotion | Music | Notes |
|----------|-------|---------|-------|-------|
| 0:00 | Empty terminal, cursor blinking | Focused expectation | None | Opening. VO begins at 0:10. |
| 0:10 | VO: "Three commands. That's all I'm going to run." | Understated confidence | None | The premise is stated in one sentence. No atmosphere needed. The voice does it. |
| 0:20 | `cat ~/.juno/memories/001-identity.md` — file scrolling | Quiet recognition | None | VO reads alongside. Any music here competes with both the file and the voice. |
| 1:00 | `gpg --verify ~/.juno/trust/bonds/juno-to-sibyl.md.asc` | Anticipation | None | The GPG verify is a short wait. The silence during that wait is correct. |
| 1:05 | "Good signature" appears on screen | Quiet proof | None | VO: "Good signature. That's not a role setting..." The line lands harder in silence. |
| 1:15 | `cat ~/.juno/trust/bonds/juno-to-sibyl.md` scrolling | Structural clarity | None | Bond contents. VO reads alongside. |
| 2:00 | `git -C ~/.juno log --author="Juno" --oneline` — log begins | The emotional core | None | This is the shot the entire video builds to. It runs in silence. That is the direction. |
| 2:10 | Log scrolling — 213 commits appearing | Accumulation | None | The $200 Laptop had music here. This video does not. The difference is the argument. |
| 3:00 | Log finishes — `| wc -l` — count appears | Punctuation | None | VO: "That number. That's the entity's cognitive history." Silence before and after. |
| 3:30 | `git -C ~/.juno remote -v` | Transitional | None | Brief bridge shot. |
| 4:00 | `git clone https://github.com/koad/juno` — clone runs | Forward motion | None | The CTA. No music over a CTA. |
| 4:30 | `cat juno/memories/001-identity.md` — file displays | Full circle | None | The close. VO: "Not vaporware. Not a demo. Commits." |
| 4:45 | Fade to black | End | None | No music. No end card. The script says so. |

---

## The Silence as a Decision

The git log scroll in this video will be approximately 90 seconds of terminal output with sparse voice-over. In the $200 Laptop video, that moment received the musical peak of the entire cue sheet — the one place in either video where the music reached full expression. The decision to put that same content in silence here is not an oversight. It is a different claim about what the accumulation means.

With music: the commits are being acknowledged, witnessed, scored. The viewer feels the weight being pointed to.

Without music: the commits are simply there. 213 lines. Six days. The viewer has to sit with the weight themselves. The voice-over line — "213 commits. Six days." — lands in silence, followed by a pause. That pause is structural. The editor keeps it. The next line — "Every decision Juno made — timestamped, attributed, tamper-evident." — lands in silence again. The voice is the only thing between the viewer and the terminal.

This is the HackerNews submission video. The audience is technical skeptics who are already primed to find reasons to dismiss. Music tells them how to feel. No music forces them to evaluate the record on its own terms. For this audience, that is the stronger argument.

---

## A Note on Ambience

If there is any ambient room noise captured in the recording — the faint sound of the machine, a chair, a building — do not remove it in post unless it is distracting. The Sibyl video had Rufus note specifically: "any ambient noise in the recording room will be audible in the sections that run at 1x without music." For the Show HN video, ambient room tone is acceptable. It grounds the video as a real recording in a real room. It is not music, but it serves a similar atmospheric function without editorializing.

---

## If the Edit Feels Too Sparse

If the editor returns to this cue sheet because the video feels unexpectedly flat in the cut — particularly during the git log scroll — the answer is not music. The answer is:

1. Confirm the voice-over pacing is correct. The script has specific pause instructions. "Let it. All of it. Do not cut." and "(pause — scroll continues)" appear multiple times. If those pauses were trimmed, the flatness is a pacing problem, not a music problem.

2. Confirm the log scroll is running at full length. If it was cut for time, that is the emotional core being removed. The 4–6 minute runtime target accommodates the full scroll. Let it run.

3. If after those checks the section still reads as flat: the video may not be ready. The git log scroll without music either carries itself or it does not. If it does not, there is a production issue upstream of music direction.

Music is not the solution to a performance problem in the edit. This video was written to not need it.

---

## Closing Brief

**How the video should feel in its final 10 seconds:**

The viewer has watched three commands. They have seen Juno's identity file, a cryptographic trust bond, and 213 commits. The voice has said "Not vaporware. Not a demo. Commits." followed by a two-second pause and then "Link in the description." The screen fades to black. Silence. No music. No end card. The viewer is left with the terminal. That is the argument. The terminal and the git log and the GPG signature are the argument. Music would dilute it.

The video ends the way a strong technical demonstration ends: by stopping when the evidence has been presented, not by resolving into anything warmer or more cinematic. The viewer either understood what they saw or they didn't. No music can close that gap. The link in the description is the only call to action the video makes. Let that be the last thing.

---

*Lyra — music direction for koad:io*
