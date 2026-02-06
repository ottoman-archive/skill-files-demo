# skill-files-demo

Three skill files from the **Opening the Ottoman Archive** Ottoman Turkish HTR/OCR project, demonstrating a two-stage pipeline for transcribing Ottoman Turkish documents using large language models (LLMs).

## Core Pipeline

### The core pipeline contains two stages (1) visual capture (2) semantic processing

1. **V3-S-Minimal** — Visual capture protocol for use with Google Gemini 3 Pro Preview. Pure script-to-Unicode conversion with zero semantic interpretation. Designed for Perso-Arabic script documents.

2. **V3-T-Government-Gazette** — Semantic processing protocol for use with Claude Opus 4.5 or 4.6. Takes the visual capture output and performs transcription, transliteration, translation, and named entity recognition.

## Optional Preparatory Step

3. **[S0-V1-Layout-Analysis](S0-V1.2-Layout-Analysis.md)** — Document layout diagnosis. Detects and classifies distinct regions of a document image. Results inform which variant of the V3-S and V3-T files to use or how to adapt them.

## Other Skill Files

Additional skill files are under development in collaboration with Ottoman Turkish scholars. Once they have been tested and validated they will be made publicly available with full documentation. These skill files will cover a wide range of script, document type, and genre from the C16th to the early C20th.

**You can find a summary description of all our skill files under development in our [public wiki](https://github.com/ottoman-archive/.github/wiki).**

<p align="center">
  <img src="https://github.com/ottoman-archive/.github/raw/main/images/Public_Wiki_06022026.png" width="1000" alt="Opening the Ottoman Archive — Generative Lives, January 4th 2026">
</p>

For research purposes, skill files under development can be requested by contacting Colin Greenstreet at colin.greenstreet@gmail.com.

## Project

Part of the [Opening the Ottoman Archive](https://github.com/ottoman-archive) initiative. For methodology and documentation, see the [project wiki](https://github.com/ottoman-archive/.github/wiki).
