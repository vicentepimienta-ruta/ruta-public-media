# W1 ES · W1_Welcome · QA report

Date: 2026-10-27 · Status: **licensed master, pending Director release authorization. Not published.**

- Narrator: Kokoro-82M `em_alex` (Apache-2.0; model `beb0d1848dee9a49…`, voices `bca610b8308e8d99…`)
- Duration: 34.81 s (timing derived from the narration)
- Closing frame disclosure: "Narración generada con IA"
- Overall automated QA: **PASS**

| Check | Result | Detail |
|---|---|---|
| clean video | pass | h264 High 1920x1080 yuv420p 30/1 |
| clean audio | pass | 1 stream(s) aac ch=1 48000Hz |
| clean duration | pass | 34.81s (plan 34.81s) |
| captioned video | pass | h264 High 1920x1080 yuv420p 30/1 |
| captioned audio | pass | 1 stream(s) aac ch=1 48000Hz |
| captioned duration | pass | 34.81s (plan 34.81s) |
| narration only silence | pass | 5 non-speech windows, loudest -91.0 dB |
| loudness | pass | -16.9 LUFS integrated, true peak -1.5 dBFS |
| vtt matches burned captions | pass | 8 cues |
| captions in order no overlap | pass |  |
| captions equal script | pass |  |
| captions synced to speech | pass | every cue lies inside its narration line |
| caption breaks clean | pass |  |
| asr intelligibility | pass | es word error 9% (small offline model) |
| brand terms english | pass | "Think Outside the Chat" -> EN ASR: "the imbeni though i think outside the chat" |
| narrator locked voice | pass | kokoro:em_alex (expected kokoro:em_alex) |
| licensing evidence | pass | Kokoro-82M Apache-2.0; model and voice-pack hashes match the audited release files |
| no T0 T2 learner copy | pass | narration + captions scanned |
| clean mobile compat | pass | H.264 High L40 · AAC LC · faststart True |
| captioned mobile compat | pass | H.264 High L40 · AAC LC · faststart True |
| av sync | pass | start offset 0.000s, video 34.80s / audio 34.81s |
| logo fidelity | pass | mean abs diff 0.91/255 vs official master |

## Visual review
Frame sheet `_QA_FRAMES.png` (from the final open-caption MP4, one frame per scene plus the closing frame) reviewed for overflow, clipped text, caption placement and logo integrity.

## Offline ASR transcript (intelligibility check only)

> bienvenido hacen causas de echar ya usas la inteligencia artificial ahora es momento de descubrir todo lo que puede hacer por ti durante las próximas diez horas de entrenamiento aprenderás a trabajar de forma más inteligente crear resultados útiles y con el tiempo delegar trabajo agentes de inteligencia artificial primero vamos a conocerte y descubrir tu punto de partida

## SHA-256

- `25e03d9b3d4cec6b5bb5ea12d5fe1595766e2efed7b97cfae7a8def683b0abe7`  TOTC_VIDEO_W1_Welcome_ES.mp4
- `8888b3d5f27ca7589f514ca0c535507f851b0f9c417f476482cbf9fa8b902818`  TOTC_VIDEO_W1_Welcome_ES_OPEN_CAPTIONS.mp4
- `c0fd774ae91297de19ebc11f63f3ac5b82c17b59e155cf5491f851c75b0e4668`  TOTC_VIDEO_W1_Welcome_ES.vtt
- `6cf1289efb217ca80cd71987b92cf427a567497b0d7e207e95cbe77a71b6d66a`  TOTC_VIDEO_W1_Welcome_ES_poster_1920x1080.png
- `f1289288512bbcda9318cb1ef85df5004c79520341eb1cb051a2e8a3cc1b4626`  TOTC_VIDEO_W1_Welcome_ES_SCRIPT.txt
