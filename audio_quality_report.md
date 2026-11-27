# Audio Quality Report

## Status: audio generation blocked

No narration WAV or MP3 has been generated. No synchronized final SRT has been generated. No placeholder audio files were created.

## Script review completed before final-copy preparation

- The latest approved Bangladesh Bank script on the repository `main` branch matches the local `documentary_script.md`; the repository's `storyboard.md` and `research_sources.md` were also read.
- The narration clearly explains that SWIFT is a financial messaging network and does not directly transfer or hold the funds. It does not claim SWIFT or the Federal Reserve systems were hacked.
- The narration uses the required figures: approximately $951 million across 35 attempted instructions; approximately $81 million reaching the Philippines; an approximately $20 million Sri Lanka instruction stopped after a spelling discrepancy prompted clarification; and approximately $15 million recovered.
- The printer is described as a visibility and response problem, not the transfer mechanism or sole cause.
- North Korean attribution is explicitly framed as allegations in U.S. Department of Justice legal filings, not a final court verdict.
- No invented dialogue, quotations, email text, or events were added.
- **Pacing issue:** the source narration is 1,945 words. The earlier estimate of approximately 1,700 words understates it. At 12:45, this requires about 153 words per minute before allowing for pauses. The final timing must be verified with the selected narrator and edit.
- No material factual contradiction or grammatical error was identified in the narration during this review. The pacing/word-count mismatch is documented for the audio session.

## Environment and blocker

- Available local speech tool: `espeak-ng` only. Its available synthesized voice quality does not meet the requested natural, mature, cinematic documentary narration standard, so it was not used.
- No configured TTS API credentials or local neural voice-generation packages were found in the inspected environment.
- Consequently there is no generated audio to measure, normalize, inspect for clipping, or use to synchronize captions.

## Requested audio measurements

- Actual duration: **Unavailable — audio not generated**
- Narration word count: **1,945**
- Average narration speed: **Unavailable — requires actual audio duration**
- WAV sample rate / bit depth: **Unavailable — no WAV generated**
- Number of generated audio sections: **0** (the script is organized into 10 narration sections)
- Pronunciation or generation issues: **No audio generation was attempted; pronunciation has not been audibly verified.**
- Script section coverage: **All 10 narration sections from the approved script are present in `narration_final_script.md` and `narration_sections.md`.**
- SRT synchronization: **Not completed; no actual audio exists to synchronize against.**

## Exact next step

Provide access to an approved high-quality neural TTS service (API credentials and permission to use that service), or install/provide a suitable licensed American English neural voice engine and model. Then generate all 10 sections with one fixed voice, assemble the WAV and MP3, measure the real duration and loudness, and create captions from the resulting audio. The current timing JSON contains editorial target windows only; it is not audio timing.

## Files not created

`narration_master.wav`, `narration_master.mp3`, and `captions_bangladesh_final.srt` are intentionally absent because their required contents cannot be produced or verified in this environment.
