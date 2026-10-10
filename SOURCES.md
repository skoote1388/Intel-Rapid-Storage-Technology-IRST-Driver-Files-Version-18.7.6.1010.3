# Sources & Checksums

Version: **18.7.6.1010.3**
Retrieved: [YYYY-MM-DD]
Source: Intel official download page (link in REDISTRIBUTION.md)

These hashes let anyone confirm the files here match the originals.

## How these were generated

Extracted from the official `SetupRST.exe` using:

    SetupRST.exe -extractdrivers SetupRST_extracted

## SHA-256 checksums

| File | SHA-256 |
| --- | --- |
| [Drivers\...\iaStorAC.inf] | [paste hash] |
| [Drivers\...\iaStorAC.sys] | [paste hash] |
| [add one row per file] | |

## Regenerate on your own machine

Windows:

    certutil -hashfile "<filename>" SHA256

Linux / macOS:

    sha256sum "<filename>"
