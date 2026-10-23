# il-giorno-di-chiusura

> Novel, novella, or long-form fiction

A **novel** project powered by [writekit](https://www.npmjs.com/package/writekit).

## Getting started

```bash
wk check          # validate project
wk build html     # preview as web page
wk build all      # build all formats (pdf, epub, html, docx, md)
wk stats          # word count and chapter balance
```

For the full command reference, configuration, and guide, see [`docs/writekit.md`](docs/writekit.md).

## Project structure

| Path | Purpose |
|---|---|
| `config.yaml` | Title, author, language, build settings |
| `style.yaml` | Writing rules — POV, tense, tone, text normalization |
| `synopsis.md` | Short summary / pitch |
| `timeline.yaml` | Chronological events |
| `manuscript/` | Your text — chapters, front/back matter |
| `outline/` | Planning and structure |
| `outline/chapters/` | Per-chapter outlines |
| `characters/` | Character sheets (name, role, backstory) |
| `world/` | Locations, cultures, systems |
| `contributors/` | Author/translator/editor bios |
| `notes/` | Free-form ideas and research |
| `reference/` | External material |
| `assets/` | Cover image, illustrations, fonts |
| `docs/` | writekit guide (auto-generated) |
| `build/` | Generated output |
