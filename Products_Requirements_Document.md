# SwiftMorph: MX to MT Viewer

## Purpose
To simplify the reading and interpretation of ISO 20022 MX messages by transforming them into MT-style formats, enabling analysts, auditors, and developers to work with financial messages more intuitively.

## Target Users
- Financial analysts
- Compliance officers
- Developers working on ISO 20022 migration
- Trade finance and remittance teams

## Core Features
- Paste or upload XML, TXT, CSV, HTML
- Live conversion of `pacs.008` to MT103-style output
- Excel-like grid for easy copying
- Export to TXT
- Embedded MX ↔ MT mapping directory
- Offline, macro-style deployment

## Technical Stack
- HTML + JavaScript (no dependencies)
- DOMParser for XML parsing
- Blob API for TXT export

## Future Enhancements
- Reverse MT → MX conversion
- Blockchain tagging for trade finance
- GPI tracker integration
- Drag-and-drop file support
