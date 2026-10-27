# TOtC Onboarding Wizard Videos

Explainer videos for the Think Outside the Chat™ learner onboarding wizard: one per wizard step (W1 to W5), each in English and Spanish.

Structure: `w{1..5}/{en,es}/`. Each language folder holds `onboarding-w<N>-<name>-<lang>.mp4` (H.264 1080p, AAC), `.vtt` captions, `-poster.png`, `-script.txt` and a `-qa-<date>.md` report. `manifest.json` is the single source of truth for what exists, its public URL, its checksum and its release status.

Status values:
- `approved`: released by the Director and served at media.rutamethod.com.
- `pending-release`: licensed master staged on a review branch; not served until the Director merges it to `main`.

Narration: Kokoro-82M v1.0 (Apache-2.0), English voice `am_michael`, Spanish voice `em_alex`. One narrator per language, voice only, no music, no effects. English brand terms inside Spanish narration are pronounced in English by the same voice, with no splicing. Every video closes with an AI-generated narration disclosure.

Brand Style Manual v2.1. LEARN, IMPLEMENT, DELEGATE. Human-Led. AI-Assisted.
