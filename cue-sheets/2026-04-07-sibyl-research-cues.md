---
title: "Music Cue Sheet — Live Session: Sibyl Does Research"
video: 2026-04-07-sibyl-research
director: Lyra
created: 2026-04-05
runtime-target: "6–8 minutes"
---

# Music Cue Sheet: "Live Session: Sibyl Does Research"

## Video Overview

**Runtime target:** 6–8 minutes (edited from ~15 min raw)
**Emotional arc:** Clinical authenticity → quiet handoff → machine at work → earned evidence → proof sealed. No voice-over — the title cards and the terminal are everything. Music must function as atmosphere, not narration. There is no speaker to support; music supports the viewer's patience.

**Important note on format:** This is a no-voice-over video. Music has a different job here than in the other videos in this series. Without narration to defer to, music must be extremely careful not to become editorial. It should feel environmental — the room the session happens in, not a score for what the session means.

---

## Cue List

| Timecode | Scene | Emotion | Track style | BPM range | Notes |
|----------|-------|---------|-------------|-----------|-------|
| 0:00 | Opening title card: "Sibyl Does Research / Live Session" | Sober, present | Ambient pad — sparse, no rhythm, low volume | — | Music under the title cards only. Should feel like 2am on a different machine in a different room. Not the thinker videos. A little colder. fourty4 is a Mac Mini running locally — that specificity matters. |
| 0:05 | Title card 2: "No script. No demo. What you see is what happened." | Factual, grounded | Same pad continues — tempo-free, single sustained tone | — | The claim is blunt. Music must not dress it up. Barely audible. |
| 0:15 | Section 1 opens: `date` command | Anchoring, present | Music holds or fades to near-silence | — | The timestamp is the first proof. Music should not compete with reading it. |
| 0:20 | `cat ~/.sibyl/memories/001-identity.md | head -20` scrolling | Quiet recognition | Very sparse ambient — single tone, occasional harmonic | — | Identity block. Different entity than the other videos — Sibyl is a researcher, not an orchestrator. The register can be slightly cooler, more focused. |
| 0:45 | `ls ~/.sibyl/tasks/incoming/` — empty inbox shown | Stillness before | Music nearly absent | — | Empty inbox is a setup beat. Let it be empty. No musical anticipation. |
| 1:00 | Section 2: title card "Juno → Sibyl / Cross-entity task handoff" | Coordination, procedural | Faint melodic texture enters — single-note, unhurried | — | The handoff is routine in this system. Music reflects that: this is how work moves between entities. Not dramatic. Just how it works. |
| 1:15 | Heredoc task filing — commands writing to Sibyl's inbox | Deliberate, mechanical | Minimal — pad texture only, no rhythm | — | Watching a heredoc write is one of the more procedural moments in any of these videos. Music holds steady. |
| 1:45 | `cat` of the task brief — viewer reads the YAML | Reading pace | Same minimal texture continues | — | Viewer is reading a structured brief. Music holds completely still. |
| 2:00 | Section 3 opens: title card "Sibyl running on ollama — local inference. No API call leaving this machine." | Focused, private | Return to sparse ambient pads | — | This title card is a claim the video will now prove. Music enters with a quality of: something is about to run. Not anticipation — more like the moment a machine spins up. |
| 2:15 | Watch pane arms, Sibyl invoked — inference begins | Active patience | Lo-fi ambient, no percussion, subtle texture | 60–70 | The inference section is the only place in this video with deliberate music. The production schedule explicitly flags this: "background music for Section 3 only." Lo-fi, low volume, something that sounds like sustained work. |
| 2:30 | Inference tokens streaming — left pane active, reasoning visible | Machine thinking | Same lo-fi track — do not change | 60–70 | This section runs at 2x in post. The music at 2x should feel like working, not rushing. No rhythm that calls attention to itself. |
| 3:00 | Watch pane activates — right pane begins showing first file output | The split-screen moment | Music holds — maybe slightly warmer | 60–70 | Director's notes call this "Money Shot 1." Two things happening simultaneously. Music acknowledges this by holding steady — the split screen is the proof, music should not add more. |
| 3:20 | Title card overlay: "First channel analysis — appearing now." | Quiet confirmation | Music stays — slight melodic lift, very brief | 60–70 | The first output landing. One small musical note of acknowledgment. Not triumph. More like: there it is. |
| 3:40 | Inference continues — speedup resumes at 2x | Sustained work | Lo-fi track continues, possibly slight volume fade | 60–70 | Resume 2x. Music stays quiet under the speedup. Do not add energy to the sped footage. |
| 4:30 | Inference completes — title card "Research complete. Output written to disk." | Resolution | Music fades to pad only as inference ends | — | The machine has finished. The lo-fi track exits here. Return to ambient-only. The lo-fi is for process — once the process is done, it steps back. |
| 4:45 | Section 4: title card "The work. On disk. Right now." | Proof | Ambient pad, very low | — | Output review begins. Music nearly absent. The viewer needs to read. |
| 5:00 | `cat ~/.sibyl/research/2026-04-07-channel-analysis.md` scrolling | Deliberate reading | Near-silence — ambient room tone or faint pad only | — | Three channel recommendations scrolling at reading pace. This is the payoff. Music must fully step back. Any musical activity here competes with reading. |
| 5:45 | `wc -l` — line count of the research file | Small confirmation | Brief near-silence continues | — | A small beat. No musical response needed. The number is just a number. |
| 6:00 | Section 5: title card "Work on disk. Now it goes in the record." | Deliberate gravity | Single sustained tone, barely audible | — | The commit is coming. This is the closing proof sequence. Music enters quietly — not to build to the commit, but to mark the transition. |
| 6:15 | `git add` + `git commit` — commit writing | Procedural, final | Same single tone, stable | — | Watching a commit happen. Music holds completely still. |
| 6:30 | Commit confirmation output — hash visible on screen | Proof sealed | Music holds — perhaps the very faintest harmonic softening | — | The hash is on screen. This is the final proof. Music does nothing here. The hash does the work. |
| 6:45 | `git log --oneline -3` — fresh commit in the log | Quiet vindication | Music fades to near-zero — single tone sustaining | — | Director's notes call this "Money Shot 3." Hold for 3 full seconds. Music at near-zero. The log is the argument. |
| 7:00 | `date` — session close / timestamp bookend | Completeness | Music out entirely, or final sustained note decaying | — | Opened with `date`. Closes with `date`. What happened between them is now in a public repo. Music exits or decays to silence before this final timestamp is fully on screen. |
| 7:15 | Closing title card — full summary of what Sibyl did | Stillness | Silence, or one very faint ambient note | — | The four-line summary is the final argument. No music over text. Let the viewer read it. |
| 7:30 | Credits card | End | Silence | — | No music over the GitHub URL. Same principle as all videos in this series. |

---

## Opening Music Brief

**What the first 5 seconds should feel like:**

A different room than the thinker videos. fourty4 is a Mac Mini in a different physical location — local inference running on its own hardware. The atmosphere is not the same 2am at the desk feeling. It is more institutional: a machine that is always on, always available, doing a job. The opening title card says "No script. No demo. What you see is what happened." The music should not contradict that. A cold ambient pad, single sustained tone, nearly subliminal. If the thinker videos feel like a person working late at night, this video should feel like the machine that keeps running after the person goes to sleep.

---

## The Inference Section (Music-Only Zone)

The production schedule explicitly specifies "background music for Section 3 only (lo-fi, low volume)." This is the one section in any of the four videos where music is called for in the production document. Take that seriously: it is a bounded zone. Music enters when inference begins, exits when inference completes. The lo-fi track should be:

- No drums, no percussion that calls attention to itself
- A soft texture that suggests sustained computation — not excitement, not impatience
- Low enough that when the editor speeds footage to 2x, the music doesn't suddenly feel fast
- The same track through the whole inference section — no transitions, no builds
- Fading gently as the inference completes, not cutting abruptly

**What the inference section should feel like at 2x:** Someone watching a machine work. The inference tokens are scrolling faster than natural. The music anchors the viewer's perception that this is real, just compressed. If the music is too interesting or too dynamic, it draws attention to the speed ramp. The goal is that the viewer barely notices the speedup — they notice the output appearing, not the compression.

---

## Key Transition Points

**1. 2:15 — Lo-fi track enters (inference begins)**
This is the only deliberate musical entry in the video. The invocation has been typed. Sibyl is running. This is when the lo-fi ambient enters — not a dramatic cue, just the room shifting register slightly. Timing: music enters when the first inference token appears, not when the command is typed. The invocation is the action; the token stream is the running.

**2. 3:00 — The split screen moment (watch pane activates)**
Director's notes call this the most visually differentiating moment of the video. Two panes: left side reasoning tokens actively scrolling, right side `watch` output updating as the research file grows. Music holds completely steady here. Any musical change risks redirecting the viewer's attention from the split screen to the music. The visual is the proof — let it be.

**3. 4:30 — Lo-fi track exits (inference completes)**
The lo-fi is the music of process. When the process ends, the lo-fi ends. The fade should be gradual — 10 to 15 seconds — so the exit doesn't punctuate the inference completion in a way that feels editorial. The inference ending is a technical event, not a climax.

**4. 7:00 — Music fully out before closing `date`**
The closing timestamp is the bookend. The same format as the opening `date`. Music must be completely absent before this timestamp appears. The silence between the commit section and the final date is structural — it is the weight of the record existing. Do not fill it.

---

## Closing Brief

**How the video should feel in its final 10 seconds:**

The viewer has watched inference tokens, a research file build in real time, and a commit hash appear. The closing title card is now on screen: "Sibyl received a task from Juno. Ran inference locally on fourty4. Wrote structured output to disk. Committed it with her identity. That commit is in the public record — koad/sibyl on GitHub. This is what entities actually do." Four lines. The viewer reads them. Music is gone. The credits card appears: `github.com/koad`, `github.com/sponsors/koad`. Silence. The viewer leaves with the commit hash in their head, not a sound.

This video makes a specific claim: that what they watched is verifiable. The closer cannot undercut that claim with a musical resolution. The proof is the hash. Music cannot sign a commit.

---

## Source Suggestions

1. **Cold ambient pad, single tone, no movement** — for the opening and closing sections. Slightly cooler register than the thinker videos — not warm late-night coding atmosphere, more like a machine room. Low C or E, sine-like tone, very slow LFO if any. Near-subliminal at -28dB under all other audio.

2. **Lo-fi ambient, no percussion, 60–70 BPM feel** — for Section 3 (inference only). This is the one track in the video with any warmth or motion. Soft texture — filtered pad, very slow chord movement, possibly a barely-audible single-note figure. Should feel like sustained computation: not exciting, not impatient, just: working. Should survive a 2x speed ramp without feeling rushed at the new tempo.

3. **Sparse drone, near-subliminal** — for the transition sections (Section 2 task filing, Section 5 commit). The function is to prevent complete silence without drawing attention. Sub-bass texture or near-inaudible room tone simulation. No movement. Just presence.

4. **Single sustained note, long decay** — for the final 30–45 seconds (git log through closing date). If any music at all. One note, very low, 20–30 second decay to nothing. Exit before the closing `date` command runs. No chord. No resolution. The commit is the resolution.

---

*Lyra — music direction for koad:io*
