# W5 EN · W5_TransformationStartsHere · QA report

Date: 2026-10-27 · Status: **licensed master, pending Director release authorization. Not published.**

- Narrator: Kokoro-82M `am_michael` (Apache-2.0; model `beb0d1848dee9a49…`, voices `bca610b8308e8d99…`)
- Duration: 52.67 s (timing derived from the narration)
- Closing frame disclosure: "AI-generated narration"
- Overall automated QA: **PASS**

| Check | Result | Detail |
|---|---|---|
| clean video | pass | h264 High 1920x1080 yuv420p 30/1 |
| clean audio | pass | 1 stream(s) aac ch=1 48000Hz |
| clean duration | pass | 52.67s (plan 52.67s) |
| captioned video | pass | h264 High 1920x1080 yuv420p 30/1 |
| captioned audio | pass | 1 stream(s) aac ch=1 48000Hz |
| captioned duration | pass | 52.67s (plan 52.67s) |
| narration only silence | pass | 8 non-speech windows, loudest -91.0 dB |
| loudness | pass | -16.9 LUFS integrated, true peak -1.4 dBFS |
| vtt matches burned captions | pass | 10 cues |
| captions in order no overlap | pass |  |
| captions equal script | pass |  |
| captions synced to speech | pass | every cue lies inside its narration line |
| caption breaks clean | pass |  |
| asr intelligibility | pass | en word error 5% (small offline model) |
| brand terms english | pass | "Think Outside the Chat" -> EN ASR: "now we can begin your think outside the chat transformation" / "AI Intent Gap" -> EN ASR: "after ten guided training hours will measure your a i intent gap again and evaluate the progress you've made" |
| narrator locked voice | pass | kokoro:am_michael (expected kokoro:am_michael) |
| licensing evidence | pass | Kokoro-82M Apache-2.0; model and voice-pack hashes match the audited release files |
| no T0 T2 learner copy | pass | narration + captions scanned |
| clean mobile compat | pass | H.264 High L40 · AAC LC · faststart True |
| captioned mobile compat | pass | H.264 High L40 · AAC LC · faststart True |
| av sync | pass | start offset 0.000s, video 52.67s / audio 52.67s |
| logo fidelity | pass | mean abs diff 0.92/255 vs official master |

## Visual review
Frame sheet `_QA_FRAMES.png` (from the final open-caption MP4, one frame per scene plus the closing frame) reviewed for overflow, clipped text, caption placement and logo integrity.

## Offline ASR transcript (intelligibility check only)

> you've completed your starting assessment now we can begin your think outside the chat transformation together will identify one meaningful result you'd like to achieve in your work you'll learn to communicate more effectively with a i create useful work from trusted information and eventually delegate define tasks while keeping human control our journey follows three stages learn implement and delegate after ten guided training hours will measure your a i intent gap again and evaluate the progress you've made your first step is complete your transformation is just beginning

## SHA-256

- `d7491a247b85f364db0cf13d0c61682a8d309a9d9ce87feb1e96ba2fa9a7d5e1`  TOTC_VIDEO_W5_TransformationStartsHere_EN.mp4
- `41cdfad1d90c1d9285fa6e74f807fef3c3c178bfbf32fe324fa5eb6e83ad4360`  TOTC_VIDEO_W5_TransformationStartsHere_EN_OPEN_CAPTIONS.mp4
- `47dd3b2f82b0ccbcac120bcab89c72b856d973e5bd79d9b705a45b806edfc840`  TOTC_VIDEO_W5_TransformationStartsHere_EN.vtt
- `cfc97fc08bf7313f3682d87a93f375ed04b291e7c2caefd612e3b1b7f563a199`  TOTC_VIDEO_W5_TransformationStartsHere_EN_poster_1920x1080.png
- `d7b01a971c50b1ac79cee06fc512a277b6dcd4b5c8d5c42f406b22e7574b582f`  TOTC_VIDEO_W5_TransformationStartsHere_EN_SCRIPT.txt
