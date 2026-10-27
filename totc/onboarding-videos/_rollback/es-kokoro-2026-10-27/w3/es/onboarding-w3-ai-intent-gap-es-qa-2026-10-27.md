# W3 ES · W3_AIIntentGap · QA report

Date: 2026-10-27 · Status: **licensed master, pending Director release authorization. Not published.**

- Narrator: Kokoro-82M `em_alex` (Apache-2.0; model `beb0d1848dee9a49…`, voices `bca610b8308e8d99…`)
- Duration: 48.51 s (timing derived from the narration)
- Closing frame disclosure: "Narración generada con IA"
- Overall automated QA: **PASS**

| Check | Result | Detail |
|---|---|---|
| clean video | pass | h264 High 1920x1080 yuv420p 30/1 |
| clean audio | pass | 1 stream(s) aac ch=1 48000Hz |
| clean duration | pass | 48.51s (plan 48.51s) |
| captioned video | pass | h264 High 1920x1080 yuv420p 30/1 |
| captioned audio | pass | 1 stream(s) aac ch=1 48000Hz |
| captioned duration | pass | 48.51s (plan 48.51s) |
| narration only silence | pass | 7 non-speech windows, loudest -91.0 dB |
| loudness | pass | -16.8 LUFS integrated, true peak -1.5 dBFS |
| vtt matches burned captions | pass | 9 cues |
| captions in order no overlap | pass |  |
| captions equal script | pass |  |
| captions synced to speech | pass | every cue lies inside its narration line |
| caption breaks clean | pass |  |
| asr intelligibility | pass | es word error 15% (small offline model) |
| brand terms english | pass | "AI Intent Gap" -> EN ASR: "the temple better the though is to a i intend gap" / "AI Intent Gap" -> EN ASR: "stoners don't want to the party that this boys that was the as old as the internet me into ball ramos i'm a the to a i intend gap but a comparable have received ah those establish their to progress" |
| narrator locked voice | pass | kokoro:em_alex (expected kokoro:em_alex) |
| licensing evidence | pass | Kokoro-82M Apache-2.0; model and voice-pack hashes match the audited release files |
| no T0 T2 learner copy | pass | narration + captions scanned |
| clean mobile compat | pass | H.264 High L40 · AAC LC · faststart True |
| captioned mobile compat | pass | H.264 High L40 · AAC LC · faststart True |
| av sync | pass | start offset 0.000s, video 48.50s / audio 48.51s |
| logo fidelity | pass | mean abs diff 0.91/255 vs official master |

## Visual review
Frame sheet `_QA_FRAMES.png` (from the final open-caption MP4, one frame per scene plus the closing frame) reviewed for overflow, clipped text, caption placement and logo integrity.

## Offline ASR transcript (intelligibility check only)

> a veces laia no entrega el resultado que esperabas puedes terminar dedicando tiempo extra corregir respuestas reescribir instrucciones o empezar de nuevo ese tiempo perdido es tu ella y en en este paso lo estima haremos con unas preguntas sencillas sobre tu uso diario de laia los resultados que no funcionan y el tiempo que dedicas a corregirlos usa tus mejores estimaciones no tienen que ser perfectas esto nos da un punto de partida después de tus diez horas de entrenamiento volveremos a medir tu ella y entendí gap para comparar los resultados y establecer tu progreso

## SHA-256

- `01d5e8033133c4a32c8b029add3368f121d4d3371e2b8eb90670feee4051f722`  TOTC_VIDEO_W3_AIIntentGap_ES.mp4
- `1f313c496d504a2738e87cd860d2c17d6e485032a362c66f7b2f36847a65a629`  TOTC_VIDEO_W3_AIIntentGap_ES_OPEN_CAPTIONS.mp4
- `9bd442a31487f364c573166d46d6850db9fb3a5109ffe3f2c28d6a8c38682b6f`  TOTC_VIDEO_W3_AIIntentGap_ES.vtt
- `0041018eedabbaaa61951e89faa3362f787496c9f1618dd488d63e7c63734fa1`  TOTC_VIDEO_W3_AIIntentGap_ES_poster_1920x1080.png
- `e95a53e5f7db3e038d92e8565bc5e5138e546a8910d310e1368bef3af4996164`  TOTC_VIDEO_W3_AIIntentGap_ES_SCRIPT.txt
