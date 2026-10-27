# W1 EN · W1_Welcome · QA report

Date: 2026-10-27 · Status: **licensed master, pending Director release authorization. Not published.**

- Narrator: Kokoro-82M `am_michael` (Apache-2.0; model `beb0d1848dee9a49…`, voices `bca610b8308e8d99…`)
- Duration: 31.46 s (timing derived from the narration)
- Closing frame disclosure: "AI-generated narration"
- Overall automated QA: **PASS**

| Check | Result | Detail |
|---|---|---|
| clean video | pass | h264 High 1920x1080 yuv420p 30/1 |
| clean audio | pass | 1 stream(s) aac ch=1 48000Hz |
| clean duration | pass | 31.47s (plan 31.46s) |
| captioned video | pass | h264 High 1920x1080 yuv420p 30/1 |
| captioned audio | pass | 1 stream(s) aac ch=1 48000Hz |
| captioned duration | pass | 31.47s (plan 31.46s) |
| narration only silence | pass | 5 non-speech windows, loudest -91.0 dB |
| loudness | pass | -17.2 LUFS integrated, true peak -1.5 dBFS |
| vtt matches burned captions | pass | 5 cues |
| captions in order no overlap | pass |  |
| captions equal script | pass |  |
| captions synced to speech | pass | every cue lies inside its narration line |
| caption breaks clean | pass |  |
| asr intelligibility | pass | en word error 2% (small offline model) |
| brand terms english | pass | "Think Outside the Chat" -> EN ASR: "welcome to think outside the chat" |
| narrator locked voice | pass | kokoro:am_michael (expected kokoro:am_michael) |
| licensing evidence | pass | Kokoro-82M Apache-2.0; model and voice-pack hashes match the audited release files |
| no T0 T2 learner copy | pass | narration + captions scanned |
| clean mobile compat | pass | H.264 High L40 · AAC LC · faststart True |
| captioned mobile compat | pass | H.264 High L40 · AAC LC · faststart True |
| av sync | pass | start offset 0.000s, video 31.47s / audio 31.46s |
| logo fidelity | pass | mean abs diff 0.91/255 vs official master |

## Visual review
Frame sheet `_QA_FRAMES.png` (from the final open-caption MP4, one frame per scene plus the closing frame) reviewed for overflow, clipped text, caption placement and logo integrity.

## Offline ASR transcript (intelligibility check only)

> welcome to think outside the chat you already use a i now it's time to discover what more can do for you over the next ten training hours you'll learn to work smarter create useful results and eventually delegate work to a i agents first let's get to know you and discover your starting point

## SHA-256

- `e71a20d8abb0f22ce9efae57b2581b76bfc09a5bb80e4fad7c4a5a2a269d87ae`  TOTC_VIDEO_W1_Welcome_EN.mp4
- `f3c3208aab676e4a9dc6b7fc61c1e44b3daaf2de0553706a88977c4fc1e2443b`  TOTC_VIDEO_W1_Welcome_EN_OPEN_CAPTIONS.mp4
- `cc679f7f6f25d437b6a30b028e235875b6f6abf6cffadafc95e80ac7194b404e`  TOTC_VIDEO_W1_Welcome_EN.vtt
- `5247f4e30350622a416b8bfdf7d76ac141035f86b99a3e5610dd7bc800be632d`  TOTC_VIDEO_W1_Welcome_EN_poster_1920x1080.png
- `af718fb953f99ac199897945ef995453ea87c0098606ad095565b9226e76df77`  TOTC_VIDEO_W1_Welcome_EN_SCRIPT.txt
