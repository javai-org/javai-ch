# CLAUDE.md

## Purpose

This repository contains the source for [javai.ch](https://javai.ch/), a multilingual Hugo static website focused on AI regulation and compliance in Switzerland. It is the Swiss-focused companion to [javai.org](https://javai.org/), which hosts the technical open-source projects.

javai.ch covers standards and regulations that demand probabilistic testing of AI systems, with emphasis on:
- **FINMA** — Swiss financial market supervision and AI governance
- **ISO 42001** — international standard for AI management systems
- Other Swiss and international regulations as they emerge

The target audience is business managers, compliance officers, and IT leaders in Swiss enterprises and cantonal government — not developers. Content explains statistical and testing concepts in accessible, non-technical terms. Visitors seeking technical tools are directed to javai.org.

## Languages

The site is published in three languages: **English**, **German**, and **French**.

### Swiss German orthography

All German content **must** use Swiss Standard German (Schweizer Hochdeutsch) orthography. The key rule: **never use ß (Eszett)**. Always use **ss** instead.

Examples:
- ~~groß~~ → **gross**
- ~~daß~~ → **dass**
- ~~Straße~~ → **Strasse**
- ~~weiß~~ → **weiss**
- ~~Maßnahme~~ → **Massnahme**
- ~~gemäß~~ → **gemäss**
- ~~schließen~~ → **schliessen**
- ~~einschließlich~~ → **einschliesslich**

This applies to all German text: content files, i18n strings, commit messages, and any other German prose in this repository.

### Content directory structure

```
content/
├── en/    # English content
├── de/    # German content (Swiss orthography)
└── fr/    # French content
```

Each language has its own content directory. When adding new content, it must be created in all three languages.

## Technology

- **Hugo** static site generator (extended edition)
- **GitHub Pages** for hosting
- **GitHub Actions** for automated build and deploy on push to `main`
