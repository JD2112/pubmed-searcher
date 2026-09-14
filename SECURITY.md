# Security Policy

We take the security of **PubMed Searcher** seriously.

## Architecture & Data Safety
- **Pure Client-Side**: PubMed Searcher executes entirely within your browser. 
- **Zero Query Logging**: Your search queries and reading activity communicate directly with NCBI E-Utilities (`ncbi.nlm.nih.gov`) and your chosen LLM provider (Groq or Google Gemini).
- **User Credentials**: Any API keys entered into Chanakya settings are stored only in your local browser's `localStorage` and sent over HTTPS exclusively to the official API endpoints of the respective AI providers.

## Reporting a Vulnerability

If you discover any security issue or vulnerability:
- **DO NOT** create a public GitHub issue.
- Please email the author directly at [jyotirmoy.das@liu.se](mailto:jyotirmoy.das@liu.se) or reach out via [GitHub Profile](https://github.com/JD2112).
- We will acknowledge receipt within 48 hours and work with you to remediate the issue promptly.
