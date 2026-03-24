# FolderFiles2TxtMd

Convert any project folder into a single `.txt` or `.md` file that AI models can easily ingest — **100% local, nothing leaves your browser**.

## Features

| Feature | Details |
|---|---|
| **Language-agnostic** | C/C++, Python, R, JS/TS, Java, Rust, Go, and more |
| **Output formats** | Plain `.txt` or Markdown (`.md`) with fenced code blocks & syntax hints |
| **Directory tree** | Optional tree prepended to the output so the AI sees the project structure |
| **Preset ignore patterns** | One-click presets for C++, Python, R, Node, Java, Rust, Go, plus a generic default |
| **Gitignore-style filtering** | Fully customisable ignore patterns |
| **Binary & size guard** | Auto-skips binary files; configurable max file-size threshold |
| **Zero dependencies** | Single self-contained HTML file — no build step, no server, no npm |
| **Privacy-first** | All processing happens locally in the browser |

## Quick Start

1. Open `FolderFiles2TxtMd.html` in any modern browser (Chrome, Edge, Firefox).
2. Click the upload area and select your project folder (or drag & drop).
3. Pick an ignore preset (e.g. **C / C++** for your CDM library).
4. Choose `.txt` or `.md` and click **Convert to Text**.
5. Upload the downloaded file to your AI model of choice.

## How It Works

The tool reads every file in the selected folder via the browser's File System API, applies ignore patterns and size/binary filters, then concatenates the remaining source files into a single output with clear per-file headers. When Markdown mode is selected, each file is wrapped in a fenced code block tagged with the correct language for syntax highlighting.

## Customising Ignore Patterns

The textarea accepts standard gitignore-style patterns (one per line). Lines starting with `#` are treated as comments. Click a preset button to load a starting set, then add or remove patterns as needed.

## Contributors

<!-- ALL-CONTRIBUTORS-LIST:START -->
| Avatar | Name | Role |
|---|---|---|
| <img src="https://github.com/Zhenglei-BCS.png" width="50"> | [@Zhenglei-BCS](https://github.com/Zhenglei-BCS) | Creator & maintainer |
| <img src="https://github.com/copilot.png" width="50"> | [@copilot](https://github.com/copilot) | AI pair programmer 🤖 |
<!-- ALL-CONTRIBUTORS-LIST:END -->