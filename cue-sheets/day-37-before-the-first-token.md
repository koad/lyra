---
title: "Music Cue Sheet — What Happens Before the First Token"
video: day-37-before-the-first-token
day: 37
director: Lyra
created: 2026-04-05
runtime-target: "7–9 minutes"
rufus-script: "~/.rufus/productions/day-37-before-the-first-token/script.md"
---

# Music Cue Sheet: "What Happens Before the First Token"

## Video Overview

**Runtime target:** 7–9 minutes
**Emotional arc:** Invisible gap named (fraction of a second between keypress and first token) → framework hook: env load and harness selection → machine check and FORCE_LOCAL override → PRIMER injection (guard condition) → mode dispatch and PID lock → base64 remote dispatch → Juno's signed policy block (money shot) → gpg verify on the hook file → non-interactive rejection → closing forward signal.

This video is a linear technical walkthrough of a bash script — the hook that runs before any AI harness starts. The subject is an invisible process. The opening frames that invisibility as a genuine question: "what happens in that fraction of a second?" This is a problem statement structure — the viewer is asked to look at something they have never seen because it has no visual representation. The question is resolved by the walkthrough that follows.

Two structural reveals:

1. **The GPG-signed policy block** (Segment 6, 5:15–7:00): A GPG signature embedded in bash comments. Any modification to the hook breaks the signature. The verification command is inside the file itself. This is the money shot — 6 full seconds of silence on screen before narration begins.

2. **The non-interactive rejection** (Segment 8, 7:45–8:30): `exit 1` where a non-interactive handler would be. Not a missing feature. The Day 36 bond at the bash level.

**Music direction for this video: low ambient underscore for the opening framing only, entering at 0:00 and fading to silence before the first bash code appears. Silence from first code on screen through end of video.**

---

## The Opening as a Music Problem

"You type `sibyl` with no arguments. Nothing visible happens for a fraction of a second. Then a response begins."

This is a genuine problem statement: a question about an invisible process. The viewer is asked to attend to a gap that normally has no visual representation. The opening framing is orienting — the viewer is being invited to see something invisible made visible. The invisible process cannot be seen until the hook walkthrough demonstrates it. The ambient provides the room in which the viewer can settle into receiving mode before the demonstration begins.

Day 33 and Day 31 used ambient openings for this same reason: the viewer is receiving an orienting frame before they can locate themselves in what the video is about to demonstrate. Day 37's opening is the same structure. The ambient enters before the first word. The viewer lands in a space before the framing begins.

The ambient must fade before the first bash excerpt appears on screen. Code is a reading moment. Reading moments are in silence throughout this series. The transition from verbal framing to code-on-screen is the transition from receiving mode to reading mode. Silence begins with the evidence.

The distinction from Day 35: Day 35's opening was a suspended quotation — words heard before explained. Day 37's opening is a description of an invisible process. Different modes, same ambient function: the viewer needs orientation before the demonstration is comprehensible.

The distinction from Day 36: Day 36's opening was `ls` output — self-explanatory visual evidence, no ambient needed. Day 37's opening is verbal framing of something the viewer cannot see. Verbal framing of an invisible process benefits from ambient in the same way Day 33's problem statement did.

---

## Why Ambient Cannot Continue Past the Opening

The first bash excerpt is two source lines: `source "$HOME/.koad-io/.env"` and `source "$HOME/.${ENTITY:?ENTITY not set}/.env"`. The viewer reads them as the VO explains load order. Code on screen is a reading moment. Music over a reading moment competes with the reading.

More specifically: the hook walkthrough is making an invisible process visible. Each section of logic — env load, machine check, PRIMER injection, mode dispatch, PID lock, base64 dispatch, signed policy block, non-interactive rejection — is shown as code and explained. Showing invisible logic made visible is an evidence presentation. Evidence in this series is in silence.

The PRIMER injection is a compound demonstration: the injection logic, the `---` separator as structural, the context-before-instruction format. This is the same category as the compression argument in Day 35 — a precise architectural distinction that must arrive in silence. Music scoring PRIMER injection as elegant or revelatory would import temperature into what is presented as an operational pattern.

---

## The Signed Policy Block as the Money Shot

Segment 6 is explicitly called the money shot in the Rufus script. The GPG-signed policy block embedded in bash comments is on screen. 6 full seconds of silence before narration begins.

The block states: harness is always `claude`. Interactive sessions allowed with `--dangerously-skip-permissions`. Non-interactive invocations rejected. Notification via GitHub Issues only. And the rationale: "No entity may drive Juno via prompt injection. She acts when koad is at the keyboard or when she picks up a GitHub Issue — just like koad himself."

The claim that a signed document inside a bash script means "those are the same thing" is the architectural argument of this segment. Music scoring the reveal of this design feature would treat the embedding as visually insufficient — as though the viewer needs audio cues to recognize what they are looking at. The evidence is self-sufficient. The policy block is on screen. The verification command is visible inside the file. The demonstration is complete without scoring.

The 6-second silence is not a pause for drama. It is reading time. The viewer is reading the policy fields and the rationale. The policy block has nine readable lines of structured content before the PGP header. Music during the hold prevents reading. The hold is for reading.

The `gpg --verify` in Segment 7 is a verification offer — the same pattern as Day 36's two `gpg --verify` calls. Verification offers land in silence. Juno's fingerprint (`16EC 6C71 8A96 D344 48EC D39D 92EA 133C 44AA 74D8`) must be readable on screen. The offer is: the verification command is in the file, any viewer can run it. Music alongside a verification offer implies the viewer needs encouragement to verify. They do not.

---

## The Non-Interactive Rejection as a Music Problem

Segment 8 displays three lines: the echo and the `exit 1`. The VO names them: "This is the Day 36 bond at the bash level." Two seconds of silence after this sentence before continuing.

"Juno is a principal, not a worker." — categorical architectural claim. Against the exit statement. Silence. The categorical claim needs no scoring. It has the exit as evidence.

The synthesis sentence — "The bond docs and the bash are the same policy in two registers" — is the most important architectural observation in the video. It must arrive in silence. Synthesis sentences against evidence have always been in silence in this series. Full pause after it. The observation has landed.

---

## The Forward Signal

Closing section: the daemon as eventual replacement for the hook. "The hook today is a stopgap that works." This is the same register as "The $200 Thinkpad ran this." in Day 35 — an understated fact about the current implementation. Ambient in Day 35's close would have overridden the understatement. Ambient here would do the same.

Day 37's close is directional and precise, not warm and synthesizing. Day 31/33's ambient returns were for warm synthesizing closes — the architecture was named, the achievement was framed. Day 37's close is a sober architectural note: the daemon is coming, the hook is the current implementation, the interface survives the transport change. No ambient return. Silence.

---

## Comparison with Prior Videos

Day 30: No music. Forensic. Git log as argument.
Day 31: Ambient bookends. Genuine problem statement. Evidence in silence. Warm synthesis close.
Day 32: No music. Categorical opening. Governance document as argument.
Day 33: Ambient bookends. Genuine problem statement. Evidence in silence. Warm synthesis close.
Day 34: No music. Finding statement opening. Silence from frame one.
Day 35: Ambient in Segment 1 only. Suspended quotation. Evidence in silence. Ironic close.
Day 36: No music. Directory listing. Six consecutive document-reading segments.
Day 37: Ambient in opening only. Verbal framing of an invisible process. Evidence in silence from first code. No ambient return.

Day 37 sits between Day 35 (ambient opening only, then silence) and Day 33 (ambient bookends). The no-ambient-return aligns Day 37 closer to Day 35. Day 33's ambient returned because the close was voice-only warm synthesis — no code on screen. Day 37's close is a directional observation: understated, operational, not warm. Silence.

---

## Segment-by-Segment Direction

### Segment 1 — Hook Entry: The Unseen Layer (0:00–1:00)

Empty terminal. VO framing. Then `cat ~/.koad-io/hooks/executed-without-arguments.sh` typed. Hold on line 1.

**Music: low ambient underscore, enter at 0:00.**

The opening describes an invisible process — the viewer is asked to attend to a gap they have never seen. Ambient provides the room in which the invisible process can be named before it is demonstrated.

"You type `sibyl` with no arguments. Nothing visible happens for a fraction of a second." — ambient holds. The viewer is asked to attend to an absence. Ambient makes the gap a gap, not dead air.

"Then a response begins. That fraction of a second has structure. This video is about what's inside it." — ambient holds. The question is unresolved. The demonstration is about to begin.

"This is the framework hook. It lives in `~/.koad-io/` — the framework layer." — ambient begins fading. The demonstration is being named. First technical terms. The mode is shifting.

By "It has three decisions to make: what machine, what harness, what prompt" — ambient near silence.

By the time the first bash excerpt scrolls into view on screen — ambient complete. Silence before code.

Style: same non-melodic ambient character established in the Week 4 series. No melody, no chord progression, no pulse, no rhythm. Cool to neutral.
Level: -18 to -20 dB under voice. Perceptible as texture only.
Fade: begin at approximately 0:45 (when the hook's function is being described). Complete before the source lines scroll into view.

### Segment 2 — FORCE_LOCAL and Machine Check (1:00–2:00)

Framework hook continues scrolling. Lines 41–48 visible. FORCE_LOCAL block on screen.

**Music: none.**

Code is on screen. The FORCE_LOCAL block: hold for 5 seconds per script instruction. Music during a scripted hold is wrong — the hold is reading time.

"Machine check. If `ENTITY_HOST` is set and the current hostname doesn't match — `ON_HOME_MACHINE=false`. SSH dispatch follows." — against code. Silence.

"The override: `FORCE_LOCAL=1`. One environment variable." — the precision of the fix is in the brevity. Music scoring brevity as elegant imports a reading of the code. Silence.

Reference to the Day 35 Chiron routing error: prior finding cited as established fact. Stated in silence.

### Segment 3 — PRIMER Injection (2:00–3:15)

Framework hook scrolls to lines 33–38. PRIMER injection block on screen. Hold for 5 seconds.

**Music: none.**

5-second hold on the PRIMER block. Reading time. Music during the hold competes with reading.

"Before mode dispatch — PRIMER injection." — the segment opening. Stated flat. Silence.

The `printf` format line — `'Project context (from %s/PRIMER.md):\n%s\n\n---\n\n%s'` — is the structural argument: orientation above the line, instruction below. The VO explains the `---` separator. Reading the format string while hearing the explanation requires silence.

"Notice the guard condition: `[ -n "$PROMPT" ]`. The framework hook will not inject PRIMER into an empty prompt." — design subtlety against code. Music over a design subtlety implies the subtlety isn't visible in the code. It is visible.

"Juno's hook differs on this point." — foreshadowing of Segment 6. Stated as fact. Silence.

### Segment 4 — Mode Dispatch and PID Lock (3:15–4:30)

Framework hook scrolls to lines 61–107. Interactive branch, then PID lock block.

**Music: none.**

"`exec` replaces the shell — no parent process left waiting." — architectural precision. Against code. Silence.

The PID lock: hold on `kill -0` and `exit 1` lines for 4 seconds per script. Reading time. Silence.

"If a live process holds the lock, the hook exits immediately. No queuing. No retry." — the fail-fast design stated as behavior. Categorical. Silence. Music scoring fail-fast as deliberately spare or austere adds temperature to what is a plain design decision.

### Segment 5 — Base64 for Remote Dispatch (4:30–5:15)

Framework hook scrolls to lines 126–129. `base64 -w0` line visible.

**Music: none.**

Hold on the `base64 -w0` line for 4 seconds per script. Reading time. Silence.

"Why base64? A prompt containing apostrophes, quotes, or newlines would break shell quoting if passed raw." — technical explanation against code. Precision requires silence.

"`-w0` disables line wrapping on Linux. macOS doesn't accept that flag — so the fallback drops it. The `||` handles the compatibility difference in one line." — cross-platform edge case. Technical details with cross-platform edge cases: silence.

### Segment 6 — Juno's Override: The Signed Policy Block (5:15–7:00)

MONEY SHOT.

`grep -A 30 "BEGIN PGP SIGNED" ~/.juno/hooks/executed-without-arguments.sh` typed. Policy block displays.

**Music: none.**

**6 full seconds of silence on screen before narration begins.** This is the structural argument: a signed document inside a bash script. Music during the 6-second hold would be scoring the display of the policy block as a reveal. It is not a reveal — it is evidence to be read. The hold is for reading the nine lines of structured content (entity, file, date, policy fields, rationale) before the VO explains what they mean.

"This is Juno's hook. Not the framework hook — Juno's own override at `~/.juno/hooks/`." — stated flat. Against the block on screen. Silence.

"The file opens with a GPG-signed policy block. Embedded in bash comments. The policy is verifiable from the file itself — no extraction required." — three sentences. Each with a pause. Silence.

The rationale sentence: "No entity may drive Juno via prompt injection. She acts when koad is at the keyboard or when she picks up a GitHub Issue — just like koad himself." — hold for 3 seconds per script. Against the rationale block on screen. Silence.

"A signed document. Inside a bash script. Those are the same thing." — three short sentences. Each with a pause. The architectural synthesis. Silence.

### Segment 7 — gpg --verify on the Hook File (7:00–7:45)

The sed pipe verification command run against the hook file. GPG output displays.

**Music: none.**

Hold on GPG output for 5 seconds per script. Fingerprint `16EC 6C71 8A96 D344 48EC D39D 92EA 133C 44AA 74D8` and `juno@kingofalldata.com` must be readable. Verification offer made. Verification offers land in silence.

"The verification command is in the file's own header — the hook documents how to verify itself." — stated against the verification pattern on screen. Silence.

"The same key used to sign the trust bonds in Day 36." — cross-video continuity as established fact. Silence.

"Any modification to this hook breaks the signature. Change the harness, add a non-interactive path, alter the rationale — `gpg --verify` fails. The policy cannot be quietly altered." — three sentences. The consequence stated precisely. Silence.

### Segment 8 — The Non-Interactive Rejection (7:45–8:30)

`grep -n "PRIMER" ~/.juno/hooks/executed-without-arguments.sh` then `grep -A 4 "Non-interactive path"` typed.

**Music: none.**

First grep shows Juno's PRIMER injection without the `$PROMPT` guard. VO contrasts with the framework hook's guard condition. Technical contrast against code. Silence.

Second grep reveals the non-interactive rejection — the echo and `exit 1`. Hold for 5 seconds per script. Reading time. Silence.

"The non-interactive path." — pause of 3 seconds per script. Do not fill.

"`exit 1`. No harness invocation. No JSON output. No result." — three short sentences. Each with a pause. Silence.

"This is not a missing feature. It is the Day 36 bond at the bash level." — 2-second pause after. The most precise sentence in the video. Against the three lines on screen. Silence.

"Juno is a principal, not a worker." — categorical. Against the exit statement. Silence.

"The bond type and the hook behavior are aligned. They are not separate documents. They are the same constraint, expressed twice." — the closing sentence of Segment 8. Script instructs: deliver at the slowest pace in the video. Silence.

### Closing (8:30–9:00)

No new commands. Last grep output visible. VO delivers the forward signal.

**Music: none.**

"What happens before the first token: env load, machine check, FORCE_LOCAL bypass, PRIMER injection, mode dispatch, PID lock, base64 encoding for remote prompts." — summary recitation. Steady pace. Silence.

"For Juno: a GPG-signed policy block, a PRIMER injection without guard, and an `exit 1` where the non-interactive handler would be." — the Juno summary. Silence.

"The hook is a stopgap that works. The daemon will eventually replace it. The interface survives — interactive versus task, PRIMER injection, lock semantics. The transport changes." — understated. Against no code on screen. The same register as "The $200 Thinkpad ran this." in Day 35. Ambient would override the understatement. Silence.

"Until then: this is what runs." — cut to black on final word. Silence.

---

## Cue List

| Timecode | Scene | Emotion | Music | Notes |
|----------|-------|---------|-------|-------|
| 0:00 | Empty terminal, prompt only | Suspended reception | Ambient in | Non-melodic, -18 to -20 dB. Enters before first word. The invisible process is about to be named. |
| 0:03 | VO: "You type `sibyl` with no arguments." | Setup | Ambient at floor | No code yet. Stated as visual fact. |
| 0:06 | VO: "Nothing visible happens for a fraction of a second." | The gap | Ambient holds | Viewer asked to attend to an absence. Ambient makes the gap a gap. |
| 0:10 | VO: "Then a response begins." | Gap resolved | Ambient holds | Setup complete. Question unresolved. |
| 0:14 | VO: "That fraction of a second has structure. This video is about what's inside it." | Demonstration announced | Ambient holds | Still framing. |
| 0:22 | VO: `cat ~/.koad-io/hooks/executed-without-arguments.sh` typed, hold on line 1 | Framework hook on screen | Ambient fading | Begin slow fade. First technical content visible. |
| 0:35 | VO: "This is the framework hook. It lives in `~/.koad-io/`..." | Hook named | Ambient fading | Nearing silence. |
| 0:44 | VO: "It has three decisions to make: what machine, what harness, what prompt." | Three decisions | Ambient near silence | Almost complete. |
| 0:50 | Source lines scroll into view on screen | Code on screen | Ambient complete | Silence established before or at first code. Reading begins. |
| 0:55 | VO: "Environment load first. The framework env loads, then the entity env." | Load order | None | Against code. Silence. |
| 1:00 | Source lines visible | Code reading | None | Viewer reading the two source lines. VO explains. Silence. |
| 1:05 | VO: "Entity values win because the entity file loads second. That's not a conditional. That's load order." | The design | None | Against the two lines. Silence. |
| 1:12 | VO: "Team entities set `KOAD_IO_ENTITY_HARNESS=claude` in their `.env`. The framework default is `opencode`. No conditional needed." | Harness selection | None | Compact. Against code. Silence. |
| 1:20 | FORCE_LOCAL block visible on screen | Machine check code | None | Viewer reading. |
| 1:24 | VO: "Machine check. If `ENTITY_HOST` is set and `hostname -s` doesn't match — `ON_HOME_MACHINE=false`. SSH dispatch follows." | Machine check | None | VO explaining while viewer reads. Silence. |
| 1:32 | FORCE_LOCAL if block on screen | Override | None | HOLD. 5 full seconds per script. Viewer reading the if block. |
| 1:37 | VO: "The override: `FORCE_LOCAL=1`. One environment variable. It sets `ON_HOME_MACHINE=true` regardless of where you are." | Override named | None | Against code. Silence. |
| 1:46 | VO: pause (2 seconds) | Pre-reference | None | |
| 1:48 | VO: "This is the fix that resolved the Chiron routing error in Day 35." | Prior finding cited | None | Established fact. Silence. |
| 1:56 | PRIMER injection block on screen | PRIMER code | None | HOLD. 5 full seconds per script. Reading time. |
| 2:01 | VO: "Before mode dispatch — PRIMER injection." | Named | None | Against code. Silence. |
| 2:05 | VO: "If the calling directory has a `PRIMER.md` and a prompt is already present, the hook prepends the PRIMER to the prompt." | Injection described | None | Against code. Silence. |
| 2:14 | VO: "`Project context from this directory's PRIMER.md:` — then the full PRIMER — then `---` — then the original prompt." | Format named | None | The format described. The `---` separator structural. Silence. |
| 2:22 | VO: "The `---` separator is structural. Orientation above the line. Instruction below." | The structure | None | Against the format string. Silence. |
| 2:28 | VO: "The entity has ecosystem context before the task begins. It does not have to re-derive what directory it's in or what conventions apply." | The function | None | Precisely stated. Silence. |
| 2:36 | VO: "Notice the guard condition: `[ -n \"$PROMPT\" ]`." | Design subtlety | None | Directing attention to the guard. Silence. |
| 2:40 | VO: "The framework hook will not inject PRIMER into an empty prompt. It will not convert an interactive session into a non-interactive one just because a `PRIMER.md` is present." | Guard intent | None | Design intent stated. Silence. |
| 2:50 | VO: "Juno's hook differs on this point. Let's come back to that." | Foreshadowing | None | Stated as fact. Silence. |
| 2:58 | PID lock block on screen | Lock code | None | Viewer reading. |
| 3:02 | VO: "Mode dispatch. Two branches. If `$PROMPT` is empty: interactive." | Mode 1 | None | Against the interactive branch. Silence. |
| 3:08 | VO: "`exec` replaces the shell — no parent process left waiting." | exec named | None | Architectural precision. Silence. |
| 3:14 | PID lock lines on screen — `kill -0` and `exit 1` | Lock logic | None | HOLD. 4 full seconds per script. Reading time. |
| 3:18 | VO: "Prompt present: non-interactive. Before executing, the hook acquires a PID lock." | Mode 2 + lock | None | Against lock code. Silence. |
| 3:24 | VO: "If a live process holds the lock, the hook exits immediately. No queuing. No retry." | Fail-fast | None | Design philosophy as behavior. Silence. |
| 3:30 | VO: "The lock clears on EXIT — success or failure — via the trap." | Trap | None | Against trap line. Silence. |
| 3:38 | base64 dispatch code on screen | Remote dispatch | None | HOLD. 4 full seconds per script. Viewer reading. |
| 3:42 | VO: "Remote dispatch. The prompt crosses an SSH command string." | Named | None | Against code. Silence. |
| 3:46 | VO: "Why base64? A prompt containing apostrophes, quotes, or newlines would break shell quoting if passed raw. Encoded, it is immune." | The reason | None | Against the line that solves the problem. Silence. |
| 3:54 | VO: "`-w0` disables line wrapping on Linux. macOS doesn't accept that flag — so the fallback drops it." | Cross-platform | None | Technical detail. Silence. |
| 4:02 | VO: "The `||` handles the compatibility difference in one line." | Compact | None | Against the `||` on screen. Silence. |
| 4:10 | VO: transition to Juno's hook | Pre-money-shot | None | Silence before the reveal command. |
| 4:15 | `grep -A 30 "BEGIN PGP SIGNED" ~/.juno/hooks/executed-without-arguments.sh` typed | Money shot approaching | None | Silence while typing. |
| 4:20 | Signed policy block appears on screen | MONEY SHOT | None | HOLD. 6 full seconds of silence. Viewer reading the policy block — all nine lines of structured content. Do not abbreviate. |
| 4:26 | VO: "This is Juno's hook. Not the framework hook — Juno's own override at `~/.juno/hooks/`." | Named | None | After the 6-second hold. Silence. |
| 4:32 | VO: "The file opens with a GPG-signed policy block. Embedded in bash comments. The policy is verifiable from the file itself — no extraction required." | Block described | None | Three sentences. Each with a pause. Silence. |
| 4:42 | VO: "What the policy states: harness is always `claude`. Interactive sessions are allowed with `--dangerously-skip-permissions`. Non-interactive invocations are rejected. Notification via GitHub Issues only." | Policy read | None | Against the policy fields on screen. Silence. |
| 4:52 | VO: pause (2 seconds) | Pre-rationale | None | |
| 4:54 | VO: "'Juno operates under koad's authorization. No entity may drive Juno via prompt injection. She acts when koad is at the keyboard or when she picks up a GitHub Issue — just like koad himself.'" | The rationale | None | Read from screen. Silence. |
| 5:02 | VO: pause (3 seconds) | Post-rationale | None | HOLD. Per script. 3 full seconds on screen. Do not fill. |
| 5:05 | VO: "A signed document. Inside a bash script. Those are the same thing." | Synthesis | None | Three short sentences. Each with a pause. Silence. |
| 5:12 | `sed -n '/^# -----BEGIN/,/^# -----END PGP SIGNATURE-----/p' ~/.juno/hooks/executed-without-arguments.sh | sed 's/^# \{0,1\}//' | gpg --verify` typed | Verification command | None | Silence while typing. |
| 5:18 | GPG output displays — Juno fingerprint `16EC 6C71 8A96 D344 48EC D39D 92EA 133C 44AA 74D8` | Fingerprint on screen | None | HOLD. 5 full seconds per script. Fingerprint readable. Verification offer made. |
| 5:23 | VO: "The verification command is in the file's own header — the hook documents how to verify itself." | Self-documentation | None | Against the verification output. Silence. |
| 5:30 | VO: "Juno's GPG key. Fingerprint `16EC 6C71 8A96 D344 48EC D39D 92EA 133C 44AA 74D8`. The same key used to sign the trust bonds in Day 36." | Fingerprint named | None | Continuity as fact. Silence. |
| 5:38 | VO: pause (2 seconds) | Pre-consequence | None | |
| 5:40 | VO: "Any modification to this hook breaks the signature. Change the harness, add a non-interactive path, alter the rationale — `gpg --verify` fails." | The consequence | None | Stated flat. Silence. |
| 5:48 | VO: "The policy cannot be quietly altered." | The architectural function | None | Final sentence of Segment 7. Silence. |
| 5:54 | `grep -n "PRIMER" ~/.juno/hooks/executed-without-arguments.sh` typed | PRIMER check | None | Silence while typing. |
| 6:00 | PRIMER lines display — no $PROMPT guard | PRIMER code | None | Viewer reading. |
| 6:04 | VO: "Juno's PRIMER guard. Compare to the framework hook: the framework requires `[ -n \"$PROMPT\" ]` — inject only if a prompt is present. Juno's hook has no such guard." | Contrast | None | Against code. Silence. |
| 6:12 | VO: "She injects PRIMER regardless of mode." | Difference | None | Stated precisely. Silence. |
| 6:16 | `grep -A 4 "Non-interactive path" ~/.juno/hooks/executed-without-arguments.sh` typed | Rejection code | None | Silence while typing. |
| 6:22 | Non-interactive rejection displays — echo and exit 1 | The rejection | None | HOLD. 5 full seconds per script. Reading time. |
| 6:27 | VO: "The non-interactive path." | Named | None | Pause 3 seconds per script. Do not fill. |
| 6:30 | VO: pause (3 seconds) | Hold | None | |
| 6:33 | VO: "`exit 1`. No harness invocation. No JSON output. No result." | The rejection read | None | Three sentences. Each with a pause. Silence. |
| 6:40 | VO: pause (2 seconds) | Pre-characterization | None | |
| 6:42 | VO: "This is not a missing feature. It is the Day 36 bond at the bash level." | The characterization | None | 2-second pause after. The most precise sentence in the video. Silence. |
| 6:46 | VO: pause (2 seconds) | Landed | None | Do not fill. |
| 6:48 | VO: "Even if Mercury or Sibyl constructs a PROMPT and pipes it to `juno` — the hook exits 1 before any execution happens." | The scope | None | Against the exit on screen. Silence. |
| 6:54 | VO: "The bond and the bash are the same policy in two registers." | Bond-bash alignment | None | Silence. |
| 7:02 | VO: pause | Pre-categorical | None | |
| 7:04 | VO: "Juno is a principal, not a worker." | Categorical | None | Against the exit statement. Silence. |
| 7:08 | VO: "Worker entities — Sibyl, Mercury, Faber — accept PROMPT. Their bond type is `authorized-builder`." | Contrast named | None | Silence. |
| 7:14 | VO: "`authorized-agent` means act under koad's direct authorization. The hook rejects PROMPT." | Bond type | None | Silence. |
| 7:22 | VO: "The bond type and the hook behavior are aligned. They are not separate documents." | Pre-synthesis | None | Building to synthesis. Silence. |
| 7:26 | VO: "They are the same constraint, expressed twice." | Synthesis | None | Slowest pace in the video per script. Silence. Full pause after. |
| 7:32 | VO: pause | Post-synthesis | None | Do not fill. |
| 7:36 | VO: "What happens before the first token: env load, machine check, FORCE_LOCAL bypass, PRIMER injection, mode dispatch, PID lock, base64 encoding for remote prompts." | Summary | None | Recitation. Steady pace. Silence. |
| 7:46 | VO: "For Juno: a GPG-signed policy block, a PRIMER injection without guard, and an `exit 1` where the non-interactive handler would be." | Juno summary | None | Silence. |
| 7:54 | VO: pause (2 seconds) | Pre-forward | None | |
| 7:56 | VO: "The hook is a stopgap that works. The daemon will eventually replace it." | Forward signal | None | Understated. Same register as "The $200 Thinkpad ran this." Silence preserves understatement. |
| 8:04 | VO: "The interface survives — interactive versus task, PRIMER injection, lock semantics. The transport changes." | What survives | None | Interface/transport distinction. Stated as fact. Silence. |
| 8:12 | VO: "Until then: this is what runs." | The close | None | Cut to black on final word. Silence. |
| 8:16 | Cut to black | End | None | No music. No outro. |

---

## The Ambient Bookend Decision

The question is whether Day 37 warrants the ambient return used in Day 31 and Day 33.

Day 31 returned ambient in the close because the final segment was standalone architectural synthesis — voice-only, no code, a declarative argument. Mode was synthesis, not evidence.

Day 33 returned ambient in the close because the final segment was a genuine architectural declaration — the "doesn't expire" observation was a warm synthesizing close that benefited from ambient providing a room for the synthesis.

Day 37's close is voice-only (no code on screen) but is not warm synthesizing. It is understated and directional: "a stopgap that works. Until then: this is what runs." This is closer to "The $200 Thinkpad ran this." in Day 35 than to Day 33's architectural synthesis. Ambient in Day 35's close would have overridden the understatement of that hardware fact. Ambient here would do the same.

Decision: no ambient return. Silence throughout the forward signal.

---

## Silence Notes for the Editor

**The mandatory holds (per Rufus script):**

1. **FORCE_LOCAL block — 5 seconds:** Viewer reading the if block before the override is explained.
2. **PRIMER injection block — 5 seconds:** Viewer reading the injection logic before the function is named.
3. **PID lock `kill -0`/`exit 1` — 4 seconds:** Viewer reading the lock logic before fail-fast is named.
4. **base64 line — 4 seconds:** Viewer reading the cross-platform dispatch before the reason is explained.
5. **Signed policy block — 6 seconds (money shot):** Viewer reading all policy fields and rationale before narration begins. Do not abbreviate. This is the structural center of the video.
6. **GPG verify output — 5 seconds:** Fingerprint must be readable. Verification offer held.
7. **Non-interactive rejection — 5 seconds:** Viewer reading the three lines before "The non-interactive path" is named.

**The synthesis sentences (each requires full pause after):**

- "A signed document. Inside a bash script. Those are the same thing." (Segment 6)
- "This is not a missing feature. It is the Day 36 bond at the bash level." (Segment 8, +2s pause)
- "The bond type and the hook behavior are aligned. They are not separate documents. They are the same constraint, expressed twice." (Segment 8, slowest pace in video)

**The ambient opening:**

If the ambient is perceptible as music rather than as texture, reduce to floor. It must be perceptible as room only — no melody, no pulse, no chord. The ambient is for the viewer landing in receiving mode before the invisible process is named. It is not scoring the gap or the question.

The fade must be complete before the first bash excerpt appears on screen. If ambient is present when code appears, the viewer is reading code in a scored environment. The silence must begin with the evidence.

Music cannot repair missing evidence. If any of the mandatory holds were trimmed, or the signed policy block is unreadable at recording resolution, the silence has nothing to hold — and adding ambient will not replace the missing evidence.

---

*Lyra — music direction for koad:io*
