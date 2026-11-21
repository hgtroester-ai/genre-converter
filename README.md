# Genre Converter
### by HGT · Supported with AI

**Build complete drum arrangements. Shape the groove. Give every song its own development.**

![Drum Construction Kit – Full Interface](./GenreConverter.png)

Genre Converter is an independent Ableton Live extension for creating genre-based MIDI drum arrangements. It combines genre-specific groove engines, drummer profiles, fills, song-section development and arrangement-level musical dramaturgy.

Instead of relying on a static loop, Genre Converter helps build drum parts that evolve across Intro, Verse, Chorus, Bridge and Outro sections.

---

## 1. Key Features

### Genre-Based Drum Generation

Choose from 25 selectable musical genres and genre variations, including:

- Classic Rock and Alternative Rock
- Blues, Jazz and Jazz-Funk
- Punk and Proto-Punk
- Funk and New Orleans Funk
- Reggae and Dub
- Ska and Two Tone
- Hip-Hop, Drum & Bass and Jungle
- DanceBeatz and additional style variations

Each genre uses its own groove vocabulary, rhythmic character and specialized pattern or fill logic.

### Drummer Profiles & Performance Feel

Shape the playing character of the generated performance.

- **Drummer Profiles:** Choose genre-oriented drummer characters.
- **Performance Feel / Pocket:** Adjust the amount of human timing nuance.
- **Swing:** Apply the genre's supported 8th- or 16th-note swing feel.
- **Groove Variation:** Control variation within the generated groove.
- **Velocity Dynamics:** Shape accents, ghost notes and performance expression.

### Song Sections & Arrangement

Build a complete drum arrangement with individual song sections.

- Intro
- Verse
- Chorus
- Bridge
- Outro

Sections can have their own musical settings and development. Genre and drummer character can shape the performance across the arrangement.

### First / Second / Final Pass

Create subtle development between repeated song sections.

The pass intelligence can make restrained changes between the First, Second and Final Pass while retaining the identity of the original groove. Section-aware variation helps repeated verses or choruses feel related without being identical.

### Fill Engine

Generate genre-aware fills and transitions.

- Fills can respond to genre, section and repetition context.
- Specialized fill logic supports styles such as Funk, Punk, Jazz, Reggae, Ska and Jungle.
- Fill intensity and variation controls shape the character of transitions.
- Phrase-aware placement supports musical section endings and transitions.

### Song Dramaturgy

Shape the energy curve of the arrangement with four musical arc presets:

- **Classic Build**
- **Slow Burn**
- **Drop & Return**
- **Cinematic Rise**

Dramaturgy Strength blends the selected arc with the established section-energy behaviour. Next Section can be set automatically or directed to a chosen section or Song End. Transition shaping works on existing notes and respects lane locks.

### MIDI Map & Lane Controls

Use the MIDI mapping options to match the generated drum notes to the destination instrument. Lane locks protect selected drum lanes from unwanted changes during supported generation and refinement operations.

Third-party product names used in MIDI mapping identify note assignments only. They do not indicate that audio recordings, samples, presets or software from those manufacturers are included.

### Audio Preview

Audition the generated drum performance before using it in your Ableton Live arrangement.

The preview engine uses the same performance transformation principles as the generated MIDI, so groove timing and velocity expression are intended to correspond to the MIDI result.

- Preview playback and Stop control
- Preview mixer and lane routing
- Stereo panning and level controls
- Velocity-layer playback
- Preview stability and level protection

---

## 2. How to Use

**Step 1 – Choose a Genre**

Select the musical style that provides the foundation for your drum arrangement.

**Step 2 – Set the Tempo and Groove**

Adjust BPM, Performance Feel / Pocket, Swing and Groove Variation to shape the basic performance.

**Step 3 – Choose a Drummer Character**

Select a suitable Drummer Profile and adjust the performance settings.

**Step 4 – Shape the Song Sections**

Work with Intro, Verse, Chorus, Bridge and Outro. Set the section development and pass behaviour.

**Step 5 – Configure Fills and Song Dramaturgy**

Choose fill behaviour and, if desired, a Song Arc preset and Next Section transition.

**Step 6 – Preview and Create MIDI**

Audition the result, refine the settings and generate the MIDI arrangement for further editing in Ableton Live.

---

## 3. Installation & Requirements

### System Requirements

- Ableton Live Suite with Extensions support.
- At release time, Ableton lists Extensions for Live 12 Suite Beta 12.4.5 or later.
- macOS or Windows systems supported by the corresponding Ableton Live version.

**Important:** Ableton Extensions are not available in Live Standard, Intro or Lite. Availability and compatibility depend on Ableton's current Extensions support and beta programme.

### Installation

1. Download the latest `.ablx` file from GitHub Releases.
2. Open Ableton Live.
3. Navigate to **Settings / Preferences → Extensions**.
4. Select **Install Extension** and choose the downloaded `.ablx` file. Alternatively, drag the `.ablx` file onto the Extensions settings page.
5. Restart Live if required.

### Updates

1. Visit the GitHub Releases section.
2. Download the latest `.ablx` package.
3. Install the updated extension through Live's Extensions settings.
4. Restart Live if required.

---

## 4. Compatibility & Technology

- Developed for Ableton Live using the Ableton Extensions SDK.
- Distributed as an installable Ableton Extension (`.ablx`).
- The SDK runtime is integrated into the `.ablx` application bundle.
- Rebuilding from source requires the matching Ableton Extensions SDK and CLI obtained separately from Ableton.

The public source archive does not redistribute the Ableton SDK or CLI as standalone packages. No separate JavaScript development environment or SDK installation is required to use the pre-built `.ablx` package.

---

## 5. Audio Assets, Sources & Licenses

### Audio Preview — Phazite Sounds

The Genre Converter 9.6.2 preview uses **37 embedded MP3 sound payloads derived from Phazite Sounds**, documented under the **CC0 1.0 Universal** dedication.

- **Sound source:** [Phazite Sounds](https://github.com/august-byrne/phazite-sounds)
- **License:** [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/)

The sound set contains four velocity layers each for Kick, Snare, Rim / Side Stick, Low Tom, Mid Tom, High Tom, Closed Hi-Hat, Open Hi-Hat and Ride, plus one dedicated long-decay Crash one-shot.

MIDI velocity selects one of four recorded layers: 1–31, 32–63, 64–95 and 96–127. The 37 MP3 payloads are embedded in the extension. Loose duplicate MP3 files and the original WAV/FLAC source recordings are not included in the public source archive.

HGT names Phazite Sounds as the source for transparency. Asset provenance and SHA-256 checksums are recorded in `SOUND-ASSETS.md` and `SOUND-ASSET-MANIFEST.json`.

### MIDI Mapping Compatibility

Toontrack / EZdrummer, Native Instruments Battery / Kontakt and Korg names may appear as MIDI mapping or compatibility references. These identify MIDI note assignments only. No audio recordings, samples, presets or software from these manufacturers are included. Such references do not imply endorsement, partnership or affiliation.

### Project and Third-Party Licenses

The HGT Free Music Creator License 1.0 applies only to original Genre Converter project material owned or controlled by HGT.

The license permits free use of the unmodified software for personal, educational, professional and commercial music production. Music created with the software may be edited, released and monetized. Free redistribution of the unmodified official release is permitted with the license and notices retained. Paid redistribution and public distribution of modified or derivative software versions require prior written permission from the relevant rights holder.

The HGT project license does not replace or change the separate CC0 1.0 dedication for the Phazite sound assets or the Ableton Extensions SDK license.

For detailed information, see the files included in the source package:

- `LICENSE.md` — HGT Free Music Creator License 1.0
- `THIRD-PARTY-NOTICES.md` — Ableton SDK, audio assets and trademark notices
- `SOUND-ASSETS.md` — Phazite Sounds provenance and audio asset details
- `SOUND-ASSET-MANIFEST.json` — embedded audio payload hashes and byte lengths
- `RELEASE-NOTES-9.6.2.md` — release-specific changes and verification limits

For the central documentation covering all three HGT Ableton Extensions:

- [Sources & Documentation](https://github.com/hgtroester-ai/hgt-ableton-extensions/tree/main/Documentation)
- [Sources — English](https://github.com/hgtroester-ai/hgt-ableton-extensions/blob/main/Documentation/SOURCES.md)
- [Quellen — Deutsch](https://github.com/hgtroester-ai/hgt-ableton-extensions/blob/main/Documentation/SOURCES_DE.md)

---

## 6. Downloads

**Latest release: Genre Converter 9.6.3**

- [Download installable Ableton Extension (.ablx)](https://github.com/hgtroester-ai/genre-converter/releases/download/v9.6.3/Genre_Konverter_9.6.3.ablx)
- [Download complete source code (.zip)](https://github.com/hgtroester-ai/genre-converter/releases/download/v9.6.3/Genre_Konverter_9.6.3_source.zip)

Check [GitHub Releases](https://github.com/hgtroester-ai/genre-converter/releases) for version numbers, updates and release notes.

---
---

## 7. About HGT

**The only good system is a sound system.**

Music connects people.

Independent development, creative ideas and a shared passion for music.

**HGT – Developed with passion. Shared with the community.**

Free to use. Community supported.
