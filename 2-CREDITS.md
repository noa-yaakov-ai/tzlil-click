# צליל קליק / Tzlil Click

A free, Hebrew-first, device-local soundboard by Noa's Tools.

## Bundled sounds

All eight sounds are by **Kenney**, from **Interface Sounds 1.0** (2020).
Each original file is covered by the pack's **Creative Commons Zero (CC0 1.0)** license.
The original OGGs were decoded to PCM WAV for broad browser support; no creative alterations were made.
The WAVs are embedded locally in index.html, not hotlinked.

| Button | Original file |
| --- | --- |
| בול בפוני | Audio/confirmation_001.ogg |
| אופס! | Audio/error_004.ogg |
| גונג קטן | Audio/bong_001.ogg |
| קליק | Audio/click_001.ogg |
| עולים למעלה | Audio/maximize_001.ogg |
| יורדים רגע | Audio/minimize_001.ogg |
| סוויץ׳ | Audio/switch_001.ogg |
| טיפה | Audio/drop_001.ogg |

Verified 2026-10-15:
- Creator: https://kenney.nl/assets/interface-sounds
- Creator-uploaded distribution and CC0 declaration: https://opengameart.org/content/interface-sounds
- Downloaded archive: https://opengameart.org/sites/default/files/kenney_interfaceSounds.zip
- License: https://creativecommons.org/publicdomain/zero/1.0/

## Original license text, included with the downloaded pack

    Interface Sounds (1.0)
    Created/distributed by Kenney (www.kenney.nl)
    Creation date: 11-02-2020
    License: (Creative Commons Zero, CC0)
    http://creativecommons.org/publicdomain/zero/1.0/
    This content is free to use in personal, educational and commercial projects.
    Support us by crediting Kenney or www.kenney.nl (this is not mandatory)

## Your own audio

Recording or importing a sound does not change its license. Only use audio you own or have permission to use.
The app does not publish, upload or share imported audio. Microphone audio, editing and IndexedDB storage stay in the browser.
Exporting or sharing audio is your choice. Backups contain your sounds: keep them private if needed.

## App behavior

- Static HTML, CSS and JavaScript, no dependencies, backend, keys, accounts, paid services, or analytics.
- Microphone requires HTTPS (or localhost) and permission. Recording is capped at 60 seconds.
- Imports: up to 20 MiB, up to 120 seconds, in formats the browser can decode.
- Trim selection, gain, playback rate (changes pitch), fade in/out, WAV export.
- Edits are baked into saved WAVs. Built-in edits save a personal copy.
- Local IndexedDB storage. Clearing site data or switching browsers/devices will not carry your board over.
- Manual JSON backup and restore. Backups merge by ID and require confirmation; restore is atomic.
- No public user uploads, sharing feed, cloud sync, music search, or pitch-preserving time stretch.
- No offline service worker in this version. Once open, user audio works locally; reloading the app initially needs a connection.

## App source

Application code: MIT License, copyright 2026 Noa's Tools.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
