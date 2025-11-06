# SwiftMorph: MX ↔ MT Message Viewer

SwiftMorph is a lightweight, offline-ready HTML+JS tool that transforms ISO 20022 MX messages (e.g., pacs.008) into simplified MT-style formats (e.g., MT103). Designed for analysts, auditors, and developers, it offers a live translation experience similar to Quillbot or Google Translate—just paste, view, and export.

## ✨ Features

- Paste or upload XML, TXT, CSV, or HTML files
- Live conversion of MX (ISO 20022) to MT-style layout
- Excel-like output grid for easy copy-paste
- Export to TXT format
- Embedded MX ↔ MT mapping reference
- Optional toggle for reverse MT → MX view

## 📁 How to Use

1. Open `index.html` in any browser (offline-ready)
2. Paste or upload your MX message
3. Click "Convert to MT View"
4. View results in the grid or export as TXT
5. Toggle "Reverse View" to simulate MT → MX mapping

## 🧠 MX ↔ MT Mapping Reference

| MX Field (pacs.008) | MT103 Tag | Description |
|---------------------|-----------|-------------|
| InstdAmt            | :32A:     | Amount and currency |
| Dbtr/Nm             | :50K:     | Ordering customer |
| Cdtr/Nm             | :59:      | Beneficiary |
| EndToEndId          | :20:      | Transaction reference |
| InstrId             | :21:      | Instruction ID |
| MsgId               | :23B:     | Message ID |

## 📦 Deployment

- No dependencies
- Single HTML file
- Ideal for macro-style, offline use

- # SwiftMorph: MX to MT Viewer

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
