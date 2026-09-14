# PubMed Searcher

[![Live App](https://img.shields.io/badge/Live_App-pubmed--searcher.pages.dev-blue?style=plastic&logo=cloudflare)](https://pubmed-searcher.pages.dev)
[![Version](https://img.shields.io/badge/Version-v2.0.0-emerald?style=plastic)](CHANGELOG.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-amber?style=plastic)](LICENSE)


An intelligent, high-performance literature exploration and scientific synthesis platform designed for researchers. 

Hosted globally on Cloudflare Pages and powered by **Chanakya - AI Guru**, PubMed Searcher allows researchers to query PubMed publications, perform structured deep-dive evaluations, and export findings instantly.

## Live Web Application

Access the application directly in your browser with zero setup:

**[https://pubmed-searcher.pages.dev](https://pubmed-searcher.pages.dev)**

## Key Features

- **Real-Time PubMed Interrogation**: Direct integration with the NCBI E-Utilities API (ESearch & ESummary) with dynamic pagination and smart caching.
- **Chanakya AI Agent**: On-demand scientific evaluation co-pilot providing:
  - Executive biological syntheses & clinical significance
  - Inferred methodological and assay workflows
  - Epigenetic & molecular pathway insights
  - Bioinformatics facility takeaways
- **Zero-Exposure Privacy**: Pure client-side architecture. Users provide their own **Groq** or **Google Gemini** API key, stored exclusively in the user's browser `localStorage`. No keys or queries are logged or sent to intermediate servers.
- **Responsive 85% Dynamic Modal**: Wide-viewport synthesis viewer that adapts smoothly to screens from ultra-wide monitors to tablets.
- **Multi-Format Synthesis Export**:
  - **Word Document (`.doc`)**: Formatted Microsoft Word document with full article metadata header and structured headings.
  - **Print / PDF (`.pdf`)**: Formatted A4 printable summary view ready for "Save as PDF" or archival.
  - **Markdown (`.md`)**: Clean markdown format for Obsidian, Logseq, or GitHub notes.
- **Batch Export**: Select multiple search results and export citations directly to **CSV** for meta-analyses or reference managers.

## Quick Start Guide

1. Navigate to **[pubmed-searcher.pages.dev](https://pubmed-searcher.pages.dev)**.
2. Enter your PubMed search query (e.g., `"DNA methylation biomarkers"` or `"Single-cell RNA-seq in glioblastoma"`).
3. Browse retrieved articles, abstracts, and direct links to PubMed / DOI.
4. Click **"Synthesize with Chanakya"** on any paper:
   - On first use, click 🔑 to input your free [Groq](https://console.groq.com) or [Google Gemini](https://aistudio.google.com) API key.
   - Review the detailed biological evaluation.
   - Click **Word (.doc)**, **Print / PDF**, or **Markdown** to save the evaluation report.

> NOTE: Report contains "mermaid" code block for graphs. Use [mermaid.live](https://mermaid.live) to render the graphs.


## Release History

Please see the [CHANGELOG.md](CHANGELOG.md) for detailed version notes and roadmap milestones.

## Community & Support

We welcome community feedback, bug reports, and feature suggestions!

- **Found a bug?** Open an issue using our [Bug Report Template](https://github.com/JD2112/pubmed-searcher/issues/new?template=bug_report.md).
- **Have a feature idea?** Suggest enhancements via our [Feature Request Template](https://github.com/JD2112/pubmed-searcher/issues/new?template=feature_request.md).
- **Security:** Please review [SECURITY.md](SECURITY.md) to report vulnerabilities responsibly.

## Citation

If you use **PubMed Searcher** in your research, academic reviews, or publications, please cite it:

```bibtex
@software{das2026pubmedsearcher,
  author = {Das, Jyotirmoy},
  title = {PubMed Searcher: Intelligent Biomedical Literature Exploration & AI Synthesis Platform},
  year = {2026},
  version = {2.0.0},
  url = {https://pubmed-searcher.pages.dev}
}
```

Or view the [CITATION](CITATION.cff) file.

## License & Acknowledgements

This project is licensed under the [MIT License](LICENSE).

Developed with ❤️ by **[Jyotirmoy Das](https://github.com/JD2112)** • Bioinformatics Core Facility, Linköping University.

The authors would like to acknowledge the Core Facility, Faculty of Medicine and Health Sciences, Linköping University, Linköping, Sweden for their support. We would also like to acknowledge Clinical Genomics Linköping, Science for Life Laboratory, Sweden for their support.

## Trademark & Naming Disclaimer

*"Chanakya" is an academic research AI agent named in honor of the ancient historical philosopher and scholar (Kauṭilya). It is an independent scientific project developed for biomedical literature exploration and bioinformatics research. It is not affiliated with, sponsored by, or endorsed by any commercial entity or registered trademark holder operating under the Chanakya name.*

