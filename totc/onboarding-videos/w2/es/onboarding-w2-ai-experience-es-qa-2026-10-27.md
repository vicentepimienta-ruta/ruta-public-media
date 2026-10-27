# W2 ES · W2_AIExperience · QA report

Date: 2026-10-27 · Status: **licensed master, pending Director release authorization. Not published.**

- Narrator: Kokoro-82M `em_alex` (Apache-2.0; model `beb0d1848dee9a49…`, voices `bca610b8308e8d99…`)
- Duration: 46.24 s (timing derived from the narration)
- Closing frame disclosure: "Narración generada con IA"
- Overall automated QA: **PASS**

| Check | Result | Detail |
|---|---|---|
| clean video | pass | h264 High 1920x1080 yuv420p 30/1 |
| clean audio | pass | 1 stream(s) aac ch=1 48000Hz |
| clean duration | pass | 46.24s (plan 46.24s) |
| captioned video | pass | h264 High 1920x1080 yuv420p 30/1 |
| captioned audio | pass | 1 stream(s) aac ch=1 48000Hz |
| captioned duration | pass | 46.24s (plan 46.24s) |
| narration only silence | pass | 7 non-speech windows, loudest -91.0 dB |
| loudness | pass | -16.6 LUFS integrated, true peak -1.4 dBFS |
| vtt matches burned captions | pass | 9 cues |
| captions in order no overlap | pass |  |
| captions equal script | pass |  |
| captions synced to speech | pass | every cue lies inside its narration line |
| caption breaks clean | pass |  |
| asr intelligibility | pass | es word error 9% (small offline model) |
| narrator locked voice | pass | kokoro:em_alex (expected kokoro:em_alex) |
| licensing evidence | pass | Kokoro-82M Apache-2.0; model and voice-pack hashes match the audited release files |
| no T0 T2 learner copy | pass | narration + captions scanned |
| clean mobile compat | pass | H.264 High L40 · AAC LC · faststart True |
| captioned mobile compat | pass | H.264 High L40 · AAC LC · faststart True |
| av sync | pass | start offset 0.000s, video 46.23s / audio 46.24s |
| logo fidelity | pass | mean abs diff 0.93/255 vs official master |

## Visual review
Frame sheet `_QA_FRAMES.png` (from the final open-caption MP4, one frame per scene plus the closing frame) reviewed for overflow, clipped text, caption placement and logo integrity.

## Offline ASR transcript (intelligibility check only)

> ya usas la inteligencia artificial pero la forma en que la usas importa tal vez haces preguntas creas contenido analiza sin formación o usas laia para apoyar tu trabajo diario en este paso conoceremos que herramientas usas para que las usas y como interactúa con ellas también te preguntaremos cuántas veces aproximadamente usas laia durante un día laboral no hay respuestas correctas ni incorrectas solo elige lo que mejor te describa hoy tus respuestas nos ayudarán a personalizar tu entrenamiento y a establecer tu punto de partida

## SHA-256

- `16469047279ceea8cb271992090bc49f812873d9465d76b2d253f91745ce3bb7`  TOTC_VIDEO_W2_AIExperience_ES.mp4
- `50d86d7ab0564cda16c619d14fb150a33d15c3b8ba521dd0b56900ad08167af6`  TOTC_VIDEO_W2_AIExperience_ES_OPEN_CAPTIONS.mp4
- `22fe935ce735d1478093c72b2d83d9aa8a1f433a4337f6875371228121a3a9fa`  TOTC_VIDEO_W2_AIExperience_ES.vtt
- `6f028c5cbdbd4d6f97084d85a3026991a3672e46aa89acc22b1976e31a539055`  TOTC_VIDEO_W2_AIExperience_ES_poster_1920x1080.png
- `16f2934eee6e13623e70aead75c1616165fa85dda990d1a8329253f186a7953b`  TOTC_VIDEO_W2_AIExperience_ES_SCRIPT.txt
