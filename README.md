# MarkDone

**Local-first AI context builder and private file converters for documents, code, and structured data.**

Prepare files for Claude, Codex, ChatGPT, Cursor-style coding agents, and other LLM workflows without uploading your documents to a server.

👉 **[markdone.dev](https://markdone.dev)**

[![Website](https://img.shields.io/badge/website-markdone.dev-2563eb)](https://markdone.dev)
[![AI Context Builder](https://img.shields.io/badge/AI%20Context%20Builder-local--first-16a34a)](https://markdone.dev/ai-context-builder/)
[![Privacy](https://img.shields.io/badge/privacy-files%20stay%20local-8b5cf6)](https://markdone.dev)
[![Price](https://img.shields.io/badge/core%20tools-free-22c55e)](https://markdone.dev)

---

## What is MarkDone?

MarkDone is a browser-based toolkit for preparing private files for AI workflows and converting everyday documents locally.

The main feature is the **[AI Context Builder](https://markdone.dev/ai-context-builder/)**: drop PDFs, DOCX files, Markdown, JSON, YAML, CSV, or text files and generate one structured AI-ready context handoff with source boundaries, token estimates, secret warnings, and optional redaction.

It is built for developers, founders, students, and teams who want to use LLMs with real project material without blindly uploading private files to a random conversion service.

## Main feature: AI Context Builder

Use MarkDone to turn mixed files into a clean context pack for an LLM or coding agent.

| Feature | What it does |
|---------|--------------|
| Mixed file input | Reads PDF, DOCX, Markdown, JSON, YAML, CSV, and text files |
| Source boundaries | Keeps each file clearly labeled in the generated Markdown output |
| Token estimate | Shows how large the final context is before you paste it into an LLM |
| Secret warnings | Detects common API keys, bearer tokens, private keys, JWTs, cloud keys, and password-like assignments |
| Optional redaction | Replaces detected sensitive values before export |
| Include/exclude files | Keep only the sources that matter for the task |
| Local processing | File contents are processed in the browser, not uploaded |

Useful for:

- Giving Claude, Codex, ChatGPT, or another coding agent the right project context.
- Packaging repository docs, specs, configs, logs, and notes into one reviewable handoff.
- Preparing PDFs and Word documents for AI summarization without uploading them.
- Checking for secrets before pasting source material into an AI tool.
- Estimating whether a prompt or context pack will fit inside an LLM context window.

## Other local tools

| Tool | What it does |
|------|--------------|
| [Markdown -> PDF](https://markdone.dev/markdown-to-pdf/) | Convert Markdown to PDF with live preview, tables, code blocks, Mermaid diagrams, and LaTeX-style math |
| [Word -> PDF](https://markdone.dev/word-to-pdf/) | Convert modern DOCX files to PDF locally |
| [Excel -> PDF](https://markdone.dev/excel-to-pdf/) | Convert XLSX spreadsheets to PDF with fit-columns, one-page, and readable export modes |
| [README -> PDF](https://markdone.dev/readme-to-pdf/) | Export GitHub README files to clean PDFs |
| [Mermaid -> PDF](https://markdone.dev/mermaid-to-pdf/) | Render Mermaid diagrams and export them to PDF |
| [JSON -> TOON](https://markdone.dev/json-to-toon/) | Convert JSON to the compact TOON format and estimate token savings for LLM prompts |
| [TOON -> JSON](https://markdone.dev/toon-to-json/) | Convert TOON back into standard JSON |
| [JSON -> YAML](https://markdone.dev/json-to-yaml/) | Turn JSON payloads into readable YAML |
| [YAML -> JSON](https://markdone.dev/yaml-to-json/) | Parse YAML into clean JSON |
| [CSV -> JSON](https://markdone.dev/csv-to-json/) | Convert CSV data into JSON arrays |
| [JSON -> CSV](https://markdone.dev/json-to-csv/) | Flatten JSON arrays and API responses into spreadsheet-ready CSV |
| [Token Counter](https://markdone.dev/token-counter/) | Estimate LLM tokens locally for prompts, Markdown, JSON, TOON, and other text |

## Why local-first?

Many file converters and AI utilities start by uploading your file to a backend. That can be fine for throwaway content, but it is risky for:

- source code and private repositories
- contracts and business documents
- customer exports and support logs
- spreadsheets with financial or operational data
- `.env` files, configs, API payloads, and internal docs
- AI prompts that contain unreleased product or company context

MarkDone is designed around a simpler default: **process the file where it already is: in your browser.**

## FAQ

**Is my file uploaded when I use MarkDone?**  
No. File parsing, conversion, token estimation, secret scanning, and context generation run locally in your browser.

**What is the AI Context Builder for?**  
It helps you prepare real files for LLMs and coding agents. Instead of pasting scattered files one by one, you get one structured Markdown handoff with file names, source boundaries, token estimates, and optional redaction.

**Does MarkDone work only for developers?**  
No. Developers get a lot of value from the context builder, JSON tools, TOON conversion, and README/PDF workflows, but MarkDone also works for students, operators, founders, and anyone handling private documents.

**What is TOON?**  
TOON is a compact text format for structured data. It can reduce token usage when you need to pass table-like JSON data into an LLM prompt.

**Do I need an account?**  
No. The core tools are usable without an account.

---

## Links

- Website: **[markdone.dev](https://markdone.dev)**
- AI Context Builder: **[markdone.dev/ai-context-builder](https://markdone.dev/ai-context-builder/)**
- Blog: **[markdone.dev/blog](https://markdone.dev/blog/)**
- Legal & Privacy: **[markdone.dev/legal](https://markdone.dev/legal/)**

---

*MarkDone — local-first AI context, document conversion, structured data, and token workflows. Made in Vienna.*
