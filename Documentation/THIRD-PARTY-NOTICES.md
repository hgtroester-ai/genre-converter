# Third-party notices — Genre Konverter 9.6.3

## Ableton Extensions SDK 1.0.0-beta.0

The `.ablx` application bundle contains the SDK runtime code integrated into the application. Ableton's SDK archive, SDK source files, API documentation, examples and CLI are **not** redistributed separately in the public source archive. The SDK runtime is included only within the application bundle as permitted by the SDK license below.

The source archive intentionally excludes `sdk-retained.cjs`, generated `dist/modules/sdk.cjs`, SDK/CLI `.tgz` archives and all other standalone SDK material. A person rebuilding from source must obtain the matching SDK and CLI directly from Ableton through the Extensions SDK beta program.

### Ableton Extensions SDK License (as supplied with SDK 1.0.0-beta.0)

**Definitions.** **"We"** are Ableton AG, Schönhauser Allee 6-7, 10119 Berlin, Germany. **"You"** are the licensee of the Extensions SDK. **"Extensions SDK"** is a software development kit, including its documentation, provided to you by Ableton free of charge.

**Granted rights.** We grant to you a non-exclusive, worldwide, royalty-free, non-transferable license to use the Extensions SDK (a) to develop applications that can communicate with Ableton products, and (b) to publish, sell or otherwise distribute such applications under your own brand name that is using parts or all of the Extensions SDK.

**Feedback.** Notwithstanding any other provision in this license, if you provide any ideas, suggestions or recommendations to Ableton regarding the Extensions SDK and all its materials ("Feedback"), we are free to use and incorporate such Feedback in our products, without payment of royalties or other consideration to you so long as Ableton does not infringe your patents, copyrights or trademark rights in the Feedback.

**Restrictions.** You may not (a) sell, license, sub-license, give away and/or distribute the Extensions SDK or parts of it outside of your application in any way to any other person or entity; (b) reverse-engineer the Extensions SDK; (c) use other than the material delivered with the Extensions SDK, including, but not limited to logos and trademarks delivered therewith; (d) violate the UI-guidelines delivered with the respective Extensions SDK. [Ableton’s Branding and Trademark Guidelines apply](https://www.ableton.com/en/legal/branding-trademark-guidelines/?language=en).

**Ownership and Confidentiality.** All copies of the Extensions SDK and any other information disclosed by Ableton hereunder are owned by Ableton, including all intellectual property rights therein. Except as otherwise set forth herein, you agree that any information disclosed by Ableton, including but not limited to pre-release software, SDK, hardware or services including related documentation and materials, provided to you as licensee of the Extensions SDK will be considered confidential information, as far as it is not generally and legitimately available to the public through no fault or breach of yours, was made available to the public by Ableton or is otherwise available to the public rightfully. Any confidential information supplied by Ableton or obtained by you may only be used by you for the purposes described herein and may not be disclosed to any third party or used to create any software or technology which is substantially similar to the expression of the Extensions technology provided with the Extensions SDK.

**Rights reserved.** We reserve the right (a) to revoke this license in the event that we have a reason to believe that you are acting in breach of this license and you did not cure such breach within 14 days upon demand in text; (b) to revoke this license in case of unintended use of the Extensions SDK; (c) to remove your application from our list of applications using Extensions SDK if, by our own judgement, the application is unusable with Extensions SDK; (d) to cease integrational support of the Extensions SDK.

**DISCLAIMER OF WARRANTY.** YOU EXPRESSLY UNDERSTAND AND AGREE THAT YOUR USE OF THE EXTENSIONS SDK IS AT YOUR SOLE RISK AND THAT THE EXTENSIONS SDK IS PROVIDED "AS IS" AND "AS AVAILABLE" WITHOUT WARRANTY OF ANY KIND FROM ABLETON. ABLETON EXPRESSLY DISCLAIMS ALL WARRANTIES AND CONDITIONS OF ANY KIND, WHETHER EXPRESS OR IMPLIED, INCLUDING, BUT NOT LIMITED TO THE IMPLIED WARRANTIES AND CONDITIONS OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NON-INFRINGEMENT, EXCEPT FOR FRAUDULENTLY CONCEALED DEFECTS.

**LIMITATION OF LIABILITY.** YOU EXPRESSLY UNDERSTAND AND AGREE THAT ABLETON, ITS SUBSIDIARIES AND AFFILIATES, AND ITS LICENSORS SHALL NOT BE LIABLE TO YOU UN DER ANY THEORY OF LIABILITY FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, CONSEQUENTIAL OR EXEMPLARY DAMAGES THAT MAY BE INCURRED BY YOU, INCLUDING ANY LOSS OF DATA, WHETHER OR NOT ABLETON OR ITS REPRESENTATIVES HAVE BEEN ADVISED OF OR SHOULD HAVE BEEN AWARE OF THE POSSIBILITY OF ANY SUCH LOSSES ARISING, EXCEPT FOR INTENT OR GROSS NEGLIGENCE. A CLAIM FOR DAMAGES ARISING FROM A LEGAL DEFECT OR A DEFECT IN THE EXTENSIONS SDK IS ONLY PERMISSIBLE IF ABLETON FRAUDULENTLY CONCEALS SUCH DEFECT.

**Indemnification.** You agree to defend, indemnify and hold harmless Ableton, its affiliates and their respective directors, officers, employees and agents from and against any and all claims, actions, suits or proceedings, as well as any losses, liabilities, damages, costs and expenses (including reasonable attorney's fees) arising out of or accruing from (a) your use of the Extensions SDK; (b) any application you develop using the Extensions SDK that infringes any copyright, trademark, trade secret, patent or other intellectual property right of any person or defames any person or violates their rights of publicity or privacy; (c) any non-compliance with this license; and (d) any breach of applicable laws.

**Support.** Subject to any statutory claims you may have under law (which shall not be affected), Ableton is not obliged to provide any additional technical support to Extensions SDK users.

**Updates.** We may update the Extensions SDK from time to time. Such updates may require modifications of this license. In the event that you do not accept such modifications you must not use the updated Extensions SDK, in which case Ableton does not warrant or guarantee support for older versions. By using an updated version of the Extensions SDK you accept the Ableton Extensions SDK License version that is assigned to the respective version of the Extensions SDK. Any version number of the Extensions SDK will be aligned with the version number of its respective license. 

**Survival Clause.** The provisions above regarding Feedback, Ownership and Confidentiality and indemnification will remain in full force and effect upon termination of this license for any reason whatsoever.

**Miscellaneous.** You may not assign this license without our prior written consent. Nothing contained herein shall constitute a partnership, joint venture, agency or employer-employee relationship between you and Ableton. This license will be exclusively governed by and construed in accordance with the laws of the Federal Republic of Germany, excluding its conflict of laws provisions and the UN Convention on the Sale of Goods (CISG) The exclusive venue for any dispute arising from this contract is - to the extent permitted - Berlin. This license may be signed digitally. This digital signature will be as valid as an original signature. Should one or more provisions of this license be or become invalid or unenforceable, the validity of the remaining provisions shall not be affected. The invalid or unenforceable provision shall be replaced by a provision whose purpose comes closest to the invalid or unenforceable provision.

## Ableton Extensions CLI

`@ableton-extensions/cli` 1.0.0-beta.0 is a development/package tool only. It is not included in the `.ablx` or the public source archive. Obtain it directly from Ableton as part of the official SDK distribution and comply with the terms supplied by Ableton. Do not copy the CLI package or its files into a public source release unless Ableton's then-current license expressly permits that distribution.

## Build-time tools (not bundled)

The source project declares TypeScript, esbuild, tsx and `@types/node` as development dependencies. They are build/test tools and are not included in the `.ablx` runtime bundle. Their upstream licenses apply when developers install them. Node.js is a separately installed development runtime; Ableton provides the Node-based Extension Host used to run Extensions in Live. No standalone Node.js runtime is redistributed here.

## Phazite Sounds — CC0 1.0 Universal

The 37 embedded MP3 payloads originate from **Phazite Sounds**. The source asset manifest identifies Phazite Sounds as the source project and declares **CC0 1.0 Universal**. This is the single provenance and license attribution used by Genre Konverter for these sound assets. The embedded MP3 payload checksums and original-source checksums where available are recorded in `SOUND-ASSET-MANIFEST.json`.

CC0 permits copying, modifying, distributing and performing the identified work, including for commercial purposes, to the extent the dedication is effective under applicable law. CC0 does not waive third-party trademark, privacy, publicity or other rights that may apply, and the affirmer provides no warranties. See the [CC0 1.0 deed](https://creativecommons.org/publicdomain/zero/1.0/) and [legal code](https://creativecommons.org/publicdomain/zero/1.0/legalcode).

Attribution is not required by CC0; HGT includes this provenance notice voluntarily. Original source WAV/FLAC recordings are not redistributed. Only the derived MP3 payloads are embedded.

## Compatibility references and trademarks

- **Ableton** and **Live** are trademarks of Ableton AG. Genre Konverter is an independent third-party extension. It is not affiliated with, authorized by, sponsored by or endorsed by Ableton AG. The names are used only to identify compatibility. Ableton's [Branding and Trademark Guidelines](https://www.ableton.com/en/legal/branding-trademark-guidelines/) apply.
- **EZdrummer 3** and **Toontrack** are trademarks of Toontrack Music AB. The extension uses a MIDI note-map compatibility reference only; no Toontrack recordings, samples, software, presets, logos or other Toontrack assets are included.
- **Battery 4** and **Kontakt 8** are product names/trademarks of Native Instruments. They are referenced only for MIDI mapping compatibility; no Native Instruments content is included.
- **Korg** and **Drumlogue** are trademarks of Korg Inc. They are referenced only for MIDI mapping compatibility; no Korg content is included.

All third-party names and marks remain the property of their respective owners. Their use does not imply endorsement, sponsorship or affiliation.
