# Smart Prompt: Giant Typographic Poster Art Director

[Česky](README.cs.md)

A visual-direction prompt that guides users through a 5-question creative brief and builds a full-bleed English image-generation prompt for Giant Typographic double-exposure posters while preserving exact non-English diacritics.

## Run

1. Open [en/smart-typo-art-posters.md](en/smart-typo-art-posters.md) (or the Czech edition [cs/smart-prompt-typo-art-postery.md](cs/smart-prompt-typo-art-postery.md)).
2. Copy the entire Markdown content and paste it as a system prompt or first message in your AI assistant (ChatGPT, Claude, Gemini or a compatible workflow).
3. Answer the Phase 1 entry diagnostic questions supplied by the assistant. The Stop-Guard prevents generating any prompt or image until all 5 brief questions (subject, letter, exact text, background texture, palette/aspect ratio) are answered.

## Features

- Combines one giant serif or sans-serif letter, a photographic double-exposure subject, translucent color overlays and archival paper texture.
- Forces full-bleed output (`no frame, no mockup, no wall, edge-to-edge graphic print`) to avoid unwanted room mockups.
- Protects exact spelling and diacritics of custom poster text inside verbatim quotation marks.
- Triggers integrated image generation when available and offers 3 targeted refinement options per iteration.

## What it is not

This repository is a prompt specification, not an image-generation model or vector editor. Rendering text accurately still depends on the target image generator's typography capabilities.

## Languages

Both `en/smart-typo-art-posters.md` and `cs/smart-prompt-typo-art-postery.md` conduct the brief in the chosen language and output the final image-generator prompt in English.

## Data and privacy

Static Markdown files only. No telemetry, accounts or external assets.

## Files

| File | Purpose |
|---|---|
| [en/smart-typo-art-posters.md](en/smart-typo-art-posters.md) | English prompt edition |
| [cs/smart-prompt-typo-art-postery.md](cs/smart-prompt-typo-art-postery.md) | Czech prompt edition |
| [README.md](README.md) | English documentation |
| [README.cs.md](README.cs.md) | Czech documentation |
| [CHANGELOG.md](CHANGELOG.md) | Release history |
| [LICENSE](LICENSE) | CC0 1.0 Universal dedication |

## License and author

Dedicated to the public domain under [CC0 1.0 Universal](LICENSE). Author credit is informational.

### Author

**Luděk Sušický** — biologist, secondary-school and university teacher of computing subjects

- E-mail: [ludek.susicky@gmail.com](mailto:ludek.susicky@gmail.com)
- X: [@ludeksusicky](https://x.com/ludeksusicky)
- LinkedIn: [Luděk Sušický](https://www.linkedin.com/in/ludek-susicky/)
- GitHub: [@siberius](https://github.com/siberius) — more educational projects and open-source applications

[GitHub repository](https://github.com/siberius/smart-typo-art-posters)
