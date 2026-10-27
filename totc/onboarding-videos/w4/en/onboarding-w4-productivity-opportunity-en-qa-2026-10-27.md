# W4 EN · W4_ProductivityOpportunity · QA report

Date: 2026-10-27 · Status: **licensed master, pending Director release authorization. Not published.**

- Narrator: Kokoro-82M `am_michael` (Apache-2.0; model `beb0d1848dee9a49…`, voices `bca610b8308e8d99…`)
- Duration: 46.93 s (timing derived from the narration)
- Closing frame disclosure: "AI-generated narration"
- Overall automated QA: **PASS**

| Check | Result | Detail |
|---|---|---|
| clean video | pass | h264 High 1920x1080 yuv420p 30/1 |
| clean audio | pass | 1 stream(s) aac ch=1 48000Hz |
| clean duration | pass | 46.93s (plan 46.93s) |
| captioned video | pass | h264 High 1920x1080 yuv420p 30/1 |
| captioned audio | pass | 1 stream(s) aac ch=1 48000Hz |
| captioned duration | pass | 46.93s (plan 46.93s) |
| narration only silence | pass | 7 non-speech windows, loudest -91.0 dB |
| loudness | pass | -16.8 LUFS integrated, true peak -1.4 dBFS |
| vtt matches burned captions | pass | 9 cues |
| captions in order no overlap | pass |  |
| captions equal script | pass |  |
| captions synced to speech | pass | every cue lies inside its narration line |
| caption breaks clean | pass |  |
| asr intelligibility | pass | en word error 9% (small offline model) |
| brand terms english | pass | "AI Intent Gap" -> EN ASR: "now you can see what you're a i intent gap may be costing you and time" / "AI Intent Gap" -> EN ASR: "after your training will measure your a i intent gap again and compare it with your starting point" |
| narrator locked voice | pass | kokoro:am_michael (expected kokoro:am_michael) |
| licensing evidence | pass | Kokoro-82M Apache-2.0; model and voice-pack hashes match the audited release files |
| no T0 T2 learner copy | pass | narration + captions scanned |
| clean mobile compat | pass | H.264 High L40 · AAC LC · faststart True |
| captioned mobile compat | pass | H.264 High L40 · AAC LC · faststart True |
| av sync | pass | start offset 0.000s, video 46.93s / audio 46.93s |
| logo fidelity | pass | mean abs diff 0.91/255 vs official master |

## Visual review
Frame sheet `_QA_FRAMES.png` (from the final open-caption MP4, one frame per scene plus the closing frame) reviewed for overflow, clipped text, caption placement and logo integrity.

## Offline ASR transcript (intelligibility check only)

> now you can see what you're a i intent gap may be costing you and taught more importantly you can explore how much of that time you might recover by working more effectively with a i will show the potential hours first followed by an estimated value of that time you may also explore a separate example of how supervised ai automation could help with repetitive work these are illustrations not guaranteed savings after your training will measure your a i intent gap again and compare it with your starting point

## SHA-256

- `be33c61bd24210c687e9828fab7ee0651fafa669b5bdbc76cfeab036e07dfd77`  TOTC_VIDEO_W4_ProductivityOpportunity_EN.mp4
- `5f2017e97a163768ee13a63eec620368347bd8126743b7a35b5b4148ef2da39d`  TOTC_VIDEO_W4_ProductivityOpportunity_EN_OPEN_CAPTIONS.mp4
- `71698c57da662f88b7c32629e32f64d217eb1a7facd08d6d4e5dc53201503c96`  TOTC_VIDEO_W4_ProductivityOpportunity_EN.vtt
- `42640b43fe19b5430044474091f46290d5e011aef25a57ae650e756ca3de36e0`  TOTC_VIDEO_W4_ProductivityOpportunity_EN_poster_1920x1080.png
- `7161977b9b96d27fc89166a083e385afbed473793b042fe5ff8c078f7cc68607`  TOTC_VIDEO_W4_ProductivityOpportunity_EN_SCRIPT.txt
