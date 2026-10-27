# W3 EN · W3_AIIntentGap · QA report

Date: 2026-10-27 · Status: **licensed master, pending Director release authorization. Not published.**

- Narrator: Kokoro-82M `am_michael` (Apache-2.0; model `beb0d1848dee9a49…`, voices `bca610b8308e8d99…`)
- Duration: 48.36 s (timing derived from the narration)
- Closing frame disclosure: "AI-generated narration"
- Overall automated QA: **PASS**

| Check | Result | Detail |
|---|---|---|
| clean video | pass | h264 High 1920x1080 yuv420p 30/1 |
| clean audio | pass | 1 stream(s) aac ch=1 48000Hz |
| clean duration | pass | 48.37s (plan 48.36s) |
| captioned video | pass | h264 High 1920x1080 yuv420p 30/1 |
| captioned audio | pass | 1 stream(s) aac ch=1 48000Hz |
| captioned duration | pass | 48.37s (plan 48.36s) |
| narration only silence | pass | 7 non-speech windows, loudest -91.0 dB |
| loudness | pass | -16.8 LUFS integrated, true peak -1.3 dBFS |
| vtt matches burned captions | pass | 8 cues |
| captions in order no overlap | pass |  |
| captions equal script | pass |  |
| captions synced to speech | pass | every cue lies inside its narration line |
| caption breaks clean | pass |  |
| asr intelligibility | pass | en word error 9% (small offline model) |
| brand terms english | pass | "AI Intent Gap" -> EN ASR: "that last time is your a i intent gap" / "AI Intent Gap" -> EN ASR: "this gives us a starting point after your ten training hours will measure your a i intent gap again to compare the results and establish your progress" |
| narrator locked voice | pass | kokoro:am_michael (expected kokoro:am_michael) |
| licensing evidence | pass | Kokoro-82M Apache-2.0; model and voice-pack hashes match the audited release files |
| no T0 T2 learner copy | pass | narration + captions scanned |
| clean mobile compat | pass | H.264 High L40 · AAC LC · faststart True |
| captioned mobile compat | pass | H.264 High L40 · AAC LC · faststart True |
| av sync | pass | start offset 0.000s, video 48.37s / audio 48.36s |
| logo fidelity | pass | mean abs diff 0.92/255 vs official master |

## Visual review
Frame sheet `_QA_FRAMES.png` (from the final open-caption MP4, one frame per scene plus the closing frame) reviewed for overflow, clipped text, caption placement and logo integrity.

## Offline ASR transcript (intelligibility check only)

> sometimes a i doesn't deliver the result you expect it you may spend extra time correcting answers rewriting instructions or starting over that last time is your ai intent gap in this step will estimated using a few simple questions about your daily a i use unsuccessful results and the time spent correcting them use your best estimates they don't need to be perfect this gives us a starting point after your ten training hours will measure your a i intent gap again to compare the results and establish your progress

## SHA-256

- `4cb2e5067e7a466629eb2dfae456eb4c49b407cf133d3eba52d08cf4b05b274b`  TOTC_VIDEO_W3_AIIntentGap_EN.mp4
- `5a424874ab441c84f09f1106db9c093e722d838952a97bce610c2b4a7cf5c66b`  TOTC_VIDEO_W3_AIIntentGap_EN_OPEN_CAPTIONS.mp4
- `ef415ec7593d830f7e7bee90c3eb1a1bbe30cac87fb049cf9e4aa8594076bc74`  TOTC_VIDEO_W3_AIIntentGap_EN.vtt
- `f6d95153b270030137abaf7ae98568f61b3e7bb3892894fbd6063b02b4378b84`  TOTC_VIDEO_W3_AIIntentGap_EN_poster_1920x1080.png
- `82ff651ba978fd5ff282f2c3c2551df1743e9b4274ef2b7420c16b3e21c75a3b`  TOTC_VIDEO_W3_AIIntentGap_EN_SCRIPT.txt
