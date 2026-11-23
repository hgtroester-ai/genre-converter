# Genre Konverter 9.6.3 — Phazite Sounds Provenance Alignment

This is a documentation-only provenance alignment release based on Genre Konverter 9.6.2. No audio payload, audio engine, MIDI generation, groove, fill, arrangement, GUI layout or playback behavior was intentionally changed.

## Changes

- Standardized the sound source attribution throughout the release to **Phazite Sounds**.
- Standardized the declared sound license to **CC0 1.0 Universal**.
- Removed intermediate project/archive references from the public sound provenance documentation.
- Kept SHA-256 checksums for the 37 embedded MP3 payloads and the available original-source files.
- Updated the source manifest, README, sample documentation, third-party notices, license effective-release metadata, GUI version label, package version and Ableton manifest to 9.6.3.

## Preserved

- All 37 embedded MP3 payloads and their SHA-256 values.
- Closed Hi-Hat trim of approximately -3 dB and Open Hi-Hat trim of approximately -4 dB.
- MIDI output, velocity mapping, groove/genre intelligence, fills, song arrangement and audio playback implementation.

## Verification limits

The regression suite and package-integrity checks are run for this release. The installable `.ablx` is re-versioned from the previously packaged 9.6.2 runtime bundle because the Ableton SDK/CLI distribution is not included in the public source archive; a fresh SDK-based compile and an in-host Ableton Live launch/listening test are not claimed.
