# Changelog

All notable changes to **PubMed Searcher** will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [2.0.0] - 2026-09-14

### Major Release: Client-Side Architecture & Chanakya AI Engine

#### Added
- **Chanakya Literature & Genomics Guru**: Integrated AI assistant with dual LLM provider support (Groq and Google Gemini) offering on-demand deep structured biological paper evaluations.
- **Dynamic 85% Viewport Evaluation Modal**: Resizable synthesis window dynamically occupying 85% of screen width for comfortable reading on all screen sizes.
- **Multi-Format Synthesis Export**:
  - **Microsoft Word (`.doc`)**: Generates cleanly formatted MSO Word document with paper metadata and rendered synthesis.
  - **Print / PDF (`.pdf`)**: Native print popup formatted with A4 layout and dedicated typography for instant Save-as-PDF.
  - **Markdown (`.md`)**: Direct markdown export for personal knowledge bases (Obsidian, Logseq).
- **Direct User API Key Management**: Secure modal for saving private user API keys locally in the browser with automatic model discovery and zero backend persistence.
- **Modern Unified Design System**: Redesigned UI aligned with `methylR 2.0 Hybrid` design language featuring Inter typography, smooth gradients, and custom scrollbars.
- **CSV Batch Citation Export**: Ability to select multiple search results and download bibliographic metadata in standard CSV.

#### Changed
- **Pure Client-Side Shift**: Replaced backend serverless proxy functions with direct client-side calls to NCBI E-Utilities and LLM providers.
- Improved search responsiveness with debounced inputs and automatic pagination controls.

#### Security
- Eliminated all server-side API keys, tokens, and proxy endpoints, ensuring zero risk of server-side credential leakage.
- Direct-to-browser encryption and local storage of user-provided API keys.

---

## [1.0.0] - 2025-05-20

### Initial Release
- Basic PubMed keyword search leveraging NCBI E-Utilities API.
- Abstract preview and direct PubMed / DOI linkouts.
- Initial experimental LLM summary prototype.
