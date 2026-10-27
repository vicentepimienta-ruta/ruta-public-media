# TOtC Video Pilot 001 — Clean-Voice Revision — QA Report (2026-10-26)

**Deliverable:** `TOTC_VIDEO_PILOT_001_Welcome_EN_CLEAN_VOICE.mp4` (1920×1080, 16:9, 30 fps, H.264 High yuv420p + AAC-LC stereo, 29.8 s, 1.4 MB, faststart, no autoplay). Also delivered: `_OPEN_CAPTIONS` variant, synchronized VTT, poster, final script. Visual production unchanged from the approved foundation (same template, logo, brand system; timeline stretched 2.2 s so the calmer read keeps natural pauses).

## Audio contains narration ONLY — verified
- The MP4 holds exactly one audio stream, built solely from the four narration lines (no music file enters the ffmpeg filter graph; v1/v2 music tracks discarded, not suppressed from a mix).
- Measured silence outside speech: 0.0–2.5 s and 26.0–29.8 s read **−91 dB mean and max** (digital silence). No ambient bed, stingers, transition sounds, or audio logo anywhere.
- Processing limited to a 70 Hz high-pass and loudness normalization: no reverb, echo, chorus or effects.

## Voice
Two calm narrator candidates were produced and measured against the direction (warm, mature, reassuring, conversational, no announcer delivery):
| Candidate | Register | Pace | Pitch variation (CV) | Loudness steadiness (RMS σ) |
|---|---|---|---|---|
| **en_US-hfc_male-medium (selected)** | Warm low male (~118 Hz) | 2.9 words/s | 0.26 (even, unexaggerated) | 6.4 dB (steadiest) |
| en_US-lessac-high | Mid/neutral (~197 Hz) | 3.1 words/s | 0.23 | 7.2 dB |
| (replaced) en_US-ryan | ~155 Hz | 3.5 words/s — too pushed | 0.25 | 7.3 dB |
**Recommendation: hfc_male** — lowest register, slowest natural pace, steadiest loudness; reads as a thoughtful instructor welcoming one learner. Pacing slowed further (length_scale 1.15), softer energy (noise settings reduced), lines start at 2.7 / 5.6 / 11.2 / 21.4 s with natural pauses; speech ends ≈24.8 s.

## Levels
Integrated −17.2 LUFS, LRA 4.0 LU (consistent loudness), true peak −4.3 dBFS. Speech passages ≈ −21 dB mean.

## Captions
VTT re-timed to the new voice (5 cues, verbatim script, boundaries on the measured sentence pauses); open-captions variant burns the same cues. Checked against frames at 3.5 / 8 / 14.5 / 19 / 23 / 28.5 s: text matches speech, nothing cropped, logo and brand unchanged.

## Scope guard
No deployment, no wizard changes, no Spanish version, no Videos 2–5 (awaiting Director approval of this narrator). Per MISSION TOTC-VIDEO-005, the approved production principle is applied going forward: one calm narrator, no music, no effects.
