# Claude Brand Guidelines Anthropic Skill

A skill for applying Anthropic's visual identity to supported artifacts. It describes the same official-style color palette, typography hierarchy, fallback fonts, and accent-color behavior documented in the skill instructions.

## What It Covers

- **Core palette:** Dark, light, and neutral gray colors.
- **Accent palette:** Orange, blue, and green for visual emphasis.
- **Typography:** Poppins headings and Lora body text, with system fallbacks.
- **Text formatting:** Consistent hierarchy and readable contrast.
- **Visual elements:** Accent colors for shapes and other non-text elements.

## Installation

Clone the repository into your Claude skills directory:

```bash
git clone https://github.com/Brajesh31/claude-brand-guidelines-anthropic-skill.git ~/.claude/skills/brand-guidelines-anthropic
```

## Using the Skill

Example request:

```text
Apply the brand-guidelines-anthropic skill to style this presentation
with Anthropic's palette and typography.
```

The instructions are in [SKILL.md](SKILL.md). The skill uses Poppins and Lora when available and falls back to Arial and Georgia otherwise.

## Brand Palette

| Role | Color |
|---|---|
| Dark | `#141413` |
| Light | `#faf9f5` |
| Mid gray | `#b0aea5` |
| Light gray | `#e8e6dc` |
| Orange accent | `#d97757` |
| Blue accent | `#6a9bcc` |
| Green accent | `#788c5d` |

## Usage Notes

Use the palette consistently and preserve sufficient contrast. Poppins and Lora must be installed in the environment for the exact typefaces to render; the documented fallback fonts support environments without them.

## License

See [LICENSE](LICENSE) for the repository license.
