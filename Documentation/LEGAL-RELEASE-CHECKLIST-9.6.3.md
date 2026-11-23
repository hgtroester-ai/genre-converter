# Legal and distribution checklist — Genre Konverter 9.6.3

## Completed in this package

- [x] HGT Free Music Creator License 1.0 replaces the draft license. It permits commercial use of music output and free redistribution of unmodified original releases; it restricts paid redistribution and public distribution of modified versions.
- [x] The license expressly limits its grant to rights HGT owns or controls and avoids claiming exclusive copyright in material that is not legally protectable or belongs to third parties.
- [x] Phazite Sounds is the single stated sound origin; its declared CC0 1.0 Universal dedication and embedded payload checksums are documented.
- [x] The `.ablx` includes the sound provenance/manifest and third-party notices.
- [x] The public source ZIP excludes the SDK tarballs, CLI tarballs, `sdk-retained.cjs` and generated `dist/` files containing a separate SDK runtime copy.
- [x] The source build requires locally obtained SDK/CLI packages from Ableton.
- [x] Ableton non-affiliation and compatibility-trademark notices are included; Toontrack/EZdrummer, Native Instruments and Korg references are identified as mapping/compatibility references only.
- [x] The package states the current Ableton beta compatibility limitation.

## External facts / conditions not controlled by this project

- Ableton's Extensions SDK is a public-beta feature. The official FAQ currently lists Live 12 Suite Beta 12.4.5 or later and excludes Standard, Intro and Lite. Ableton may change these requirements.
- The developer must hold and comply with the SDK license and obtain the matching SDK/CLI from Ableton. The included application bundle contains SDK runtime code only as part of the application under the SDK's application-distribution grant.
- CC0 is declared in the supplied Phazite Sounds manifest. The project has checked the source and embedded payload checksums, but cannot independently guarantee that the original uploader owned every underlying right.
- The HGT license is a project-specific usage license, not an OSI open-source license and not a legal opinion. Copyright enforceability in AI-assisted implementation depends on applicable law and the protectable human contributions.
- No lawyer has reviewed this release. For commercial distribution at scale, legal review of the license, SDK terms and rights provenance is recommended.

## Release status

The project-side documentation and packaging tasks listed above are complete. This is not a legal certification and cannot eliminate third-party claims or replace confirmation from Ableton or the sound rights holder.
