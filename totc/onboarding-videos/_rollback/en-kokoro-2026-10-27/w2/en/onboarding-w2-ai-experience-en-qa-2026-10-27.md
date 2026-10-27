# W2 EN · W2_AIExperience · QA report

Date: 2026-10-27 · Status: **licensed master, pending Director release authorization. Not published.**

- Narrator: Kokoro-82M `am_michael` (Apache-2.0; model `beb0d1848dee9a49…`, voices `bca610b8308e8d99…`)
- Duration: 45.1 s (timing derived from the narration)
- Closing frame disclosure: "AI-generated narration"
- Overall automated QA: **PASS**

| Check | Result | Detail |
|---|---|---|
| clean video | pass | h264 High 1920x1080 yuv420p 30/1 |
| clean audio | pass | 1 stream(s) aac ch=1 48000Hz |
| clean duration | pass | 45.10s (plan 45.1s) |
| captioned video | pass | h264 High 1920x1080 yuv420p 30/1 |
| captioned audio | pass | 1 stream(s) aac ch=1 48000Hz |
| captioned duration | pass | 45.10s (plan 45.1s) |
| narration only silence | pass | 7 non-speech windows, loudest -91.0 dB |
| loudness | pass | -16.7 LUFS integrated, true peak -1.3 dBFS |
| vtt matches burned captions | pass | 8 cues |
| captions in order no overlap | pass |  |
| captions equal script | pass |  |
| captions synced to speech | pass | every cue lies inside its narration line |
| caption breaks clean | pass |  |
| asr intelligibility | pass | en word error 4% (small offline model) |
| narrator locked voice | pass | kokoro:am_michael (expected kokoro:am_michael) |
| licensing evidence | pass | Kokoro-82M Apache-2.0; model and voice-pack hashes match the audited release files |
| no T0 T2 learner copy | pass | narration + captions scanned |
| clean mobile compat | pass | H.264 High L40 · AAC LC · faststart True |
| captioned mobile compat | pass | H.264 High L40 · AAC LC · faststart True |
| av sync | pass | start offset 0.000s, video 45.10s / audio 45.10s |
| logo fidelity | pass | mean abs diff 0.93/255 vs official master |

## Visual review
Frame sheet `_QA_FRAMES.png` (from the final open-caption MP4, one frame per scene plus the closing frame) reviewed for overflow, clipped text, caption placement and logo integrity.

## Offline ASR transcript (intelligibility check only)

> you already use a i but how you use it matters maybe you ask questions create content analyze information or use a i to support your daily work in this step will learn which tools you use what you use them for and how you interact with them will also ask approximately how many times you use a i during a working day there are no right or wrong answers just choose what best describes you today your answers will help us personalize your training and establish your starting point

## SHA-256

- `60c49a0430a3e61ffb8a3e168b8b8053f799fa637f9ba7c9f6c2018e6993b625`  TOTC_VIDEO_W2_AIExperience_EN.mp4
- `f2e26cbfef70673e2af1c3d058e1351123bcf25fb9bb59755f72120e544fb90f`  TOTC_VIDEO_W2_AIExperience_EN_OPEN_CAPTIONS.mp4
- `2b0cbf3682074a76e162585831d7d30dc8efa71e5bd2c66236032d76a0d745e2`  TOTC_VIDEO_W2_AIExperience_EN.vtt
- `3d8b78d60ce8e640f7858c3ceb0748d8482048f18e737a429560b19e5d019489`  TOTC_VIDEO_W2_AIExperience_EN_poster_1920x1080.png
- `a7e965a3b497d53e6b0403b668353c01e4e2fc5ec73f3b63a8af8819ed36f9f8`  TOTC_VIDEO_W2_AIExperience_EN_SCRIPT.txt
