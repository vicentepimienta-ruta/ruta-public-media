# W5 ES · W5_TransformationStartsHere · QA report

Date: 2026-10-27 · Status: **licensed master, pending Director release authorization. Not published.**

- Narrator: Kokoro-82M `em_alex` (Apache-2.0; model `beb0d1848dee9a49…`, voices `bca610b8308e8d99…`)
- Duration: 52.57 s (timing derived from the narration)
- Closing frame disclosure: "Narración generada con IA"
- Overall automated QA: **PASS**

| Check | Result | Detail |
|---|---|---|
| clean video | pass | h264 High 1920x1080 yuv420p 30/1 |
| clean audio | pass | 1 stream(s) aac ch=1 48000Hz |
| clean duration | pass | 52.57s (plan 52.57s) |
| captioned video | pass | h264 High 1920x1080 yuv420p 30/1 |
| captioned audio | pass | 1 stream(s) aac ch=1 48000Hz |
| captioned duration | pass | 52.57s (plan 52.57s) |
| narration only silence | pass | 8 non-speech windows, loudest -91.0 dB |
| loudness | pass | -16.7 LUFS integrated, true peak -1.5 dBFS |
| vtt matches burned captions | pass | 10 cues |
| captions in order no overlap | pass |  |
| captions equal script | pass |  |
| captions synced to speech | pass | every cue lies inside its narration line |
| caption breaks clean | pass |  |
| asr intelligibility | pass | es word error 21% (small offline model) |
| brand terms english | pass | "Think Outside the Chat" -> EN ASR: "hold up with a most common sight of to transform my soon can think outside the chat" / "AI Intent Gap" -> EN ASR: "this was the the as old as the internet me and together ball but a more some of these to a i intend gap year about what a morsel progress oh cast look at other" |
| narrator locked voice | pass | kokoro:em_alex (expected kokoro:em_alex) |
| licensing evidence | pass | Kokoro-82M Apache-2.0; model and voice-pack hashes match the audited release files |
| no T0 T2 learner copy | pass | narration + captions scanned |
| clean mobile compat | pass | H.264 High L40 · AAC LC · faststart True |
| captioned mobile compat | pass | H.264 High L40 · AAC LC · faststart True |
| av sync | pass | start offset 0.000s, video 52.57s / audio 52.57s |
| logo fidelity | pass | mean abs diff 0.92/255 vs official master |

## Visual review
Frame sheet `_QA_FRAMES.png` (from the final open-caption MP4, one frame per scene plus the closing frame) reviewed for overflow, clipped text, caption placement and logo integrity.

## Offline ASR transcript (intelligibility check only)

> completas de tu evaluación inicial ahora podemos comenzar tu transformación con chen causa y de juntos identifica haremos un resultado significativo que te gustaría lograr en tu trabajo aprenderás a comunicarse de forma más efectiva con la laia a crear trabajo útil a partir de in formación confiable y con el tiempo a delegar tareas definidas sin perder el control humano nuestro recorrido sigue tres etapas aprender implementar y delegar después de diez horas de entrenamiento guiado volveremos a medir tu ella y en tan cap y evaluar haremos el progreso que has logrado tu primer paso está completo tu transformación apenas comienza

## SHA-256

- `7464a2806b9aa18ebc28f586b07cd94bbaf88440953631a6e64daba6ec2e5719`  TOTC_VIDEO_W5_TransformationStartsHere_ES.mp4
- `0abefbe7a5cc1405326dd19721c55ae9390586f2c3cb4b183b9da11d410a82a5`  TOTC_VIDEO_W5_TransformationStartsHere_ES_OPEN_CAPTIONS.mp4
- `6838cdf16f1196c9fa35317ee1d60bdce8f7d2306991cca819e775930ace72b4`  TOTC_VIDEO_W5_TransformationStartsHere_ES.vtt
- `65f7e469cac5815482d7450b59dcfcadbdf4c9d828cf9e257b5406abb9c1101e`  TOTC_VIDEO_W5_TransformationStartsHere_ES_poster_1920x1080.png
- `c39bfe3f2af5794dd99797be537b401029dfb7d41d5708e58293a55bf4627621`  TOTC_VIDEO_W5_TransformationStartsHere_ES_SCRIPT.txt
