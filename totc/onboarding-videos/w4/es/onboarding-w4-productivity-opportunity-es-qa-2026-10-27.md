# W4 ES · W4_ProductivityOpportunity · QA report

Date: 2026-10-27 · Status: **licensed master, pending Director release authorization. Not published.**

- Narrator: Kokoro-82M `em_alex` (Apache-2.0; model `beb0d1848dee9a49…`, voices `bca610b8308e8d99…`)
- Duration: 47.74 s (timing derived from the narration)
- Closing frame disclosure: "Narración generada con IA"
- Overall automated QA: **PASS**

| Check | Result | Detail |
|---|---|---|
| clean video | pass | h264 High 1920x1080 yuv420p 30/1 |
| clean audio | pass | 1 stream(s) aac ch=1 48000Hz |
| clean duration | pass | 47.74s (plan 47.74s) |
| captioned video | pass | h264 High 1920x1080 yuv420p 30/1 |
| captioned audio | pass | 1 stream(s) aac ch=1 48000Hz |
| captioned duration | pass | 47.74s (plan 47.74s) |
| narration only silence | pass | 7 non-speech windows, loudest -91.0 dB |
| loudness | pass | -16.5 LUFS integrated, true peak -1.4 dBFS |
| vtt matches burned captions | pass | 10 cues |
| captions in order no overlap | pass |  |
| captions equal script | pass |  |
| captions synced to speech | pass | every cue lies inside its narration line |
| caption breaks clean | pass |  |
| asr intelligibility | pass | es word error 13% (small offline model) |
| brand terms english | pass | "AI Intent Gap" -> EN ASR: "hold up with is better quantity ample for three aesthetical standard the to a i intend gap" / "AI Intent Gap" -> EN ASR: "this boys the to enter in a into ball but a more some of these to a i intend gap you look back at a mosque on to boon to the party that" |
| narrator locked voice | pass | kokoro:em_alex (expected kokoro:em_alex) |
| licensing evidence | pass | Kokoro-82M Apache-2.0; model and voice-pack hashes match the audited release files |
| no T0 T2 learner copy | pass | narration + captions scanned |
| clean mobile compat | pass | H.264 High L40 · AAC LC · faststart True |
| captioned mobile compat | pass | H.264 High L40 · AAC LC · faststart True |
| av sync | pass | start offset 0.000s, video 47.73s / audio 47.74s |
| logo fidelity | pass | mean abs diff 0.91/255 vs official master |

## Visual review
Frame sheet `_QA_FRAMES.png` (from the final open-caption MP4, one frame per scene plus the closing frame) reviewed for overflow, clipped text, caption placement and logo integrity.

## Offline ASR transcript (intelligibility check only)

> ahora puedes ver cuánto tiempo podría estar costando te tu ella y encendía y lo más importante puedes explorar cuanto de ese tiempo podrías recuperar si trabajas de forma más efectiva con la primero te mostraremos las horas potenciales y después un valor estimado de ese tiempo también puedes explorar un ejemplo independiente de como la automatización supervisada con ia podría ayudarte con el trabajo repetitivo son ilustraciones no ahorros garantizados después de tu entrenamiento volveremos a medir tu ella y ensanchaba y lo con pararemos con tu punto de partida

## SHA-256

- `3c359d3ff549348f183db3522834db914b572987b52c8316a3410e1681c7a3cb`  TOTC_VIDEO_W4_ProductivityOpportunity_ES.mp4
- `7a11cd7e68e012445749f62c5a0f9c0949e845490b9a3967a1ae28d75f246cfd`  TOTC_VIDEO_W4_ProductivityOpportunity_ES_OPEN_CAPTIONS.mp4
- `247cdeca570efe36a364558fea267c96f064a54ede34e5cb0baa3c29e21771c3`  TOTC_VIDEO_W4_ProductivityOpportunity_ES.vtt
- `bc05fd4375c503deb278c2ae36ff4559151e5fea7bf2ae8905a69b6cb54a4802`  TOTC_VIDEO_W4_ProductivityOpportunity_ES_poster_1920x1080.png
- `6ccddf00829de8be979d453a2fdaefe8dc443deba98f376d46cd8d2a63a3ad67`  TOTC_VIDEO_W4_ProductivityOpportunity_ES_SCRIPT.txt
