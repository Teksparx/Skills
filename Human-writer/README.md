# Human-writer

A Claude Code skill that rewrites AI-generated text to remove detectable patterns and watermarks while preserving meaning, facts, and the author's voice.

## What it does

- Removes surface-level AI tells (stock vocabulary, em-dashes, uniform rhythm)
- Fixes structural patterns that betray AI authorship (over-explained themes, tidy conclusions, formulaic sections)
- Reduces statistical watermarks through burstiness injection and token reordering
- Strips deterministic marks (invisible Unicode, homoglyphs, smart quotes)
- Preserves the original's facts, claims, and voice

## Use cases

- Humanizing emails, essays, blog posts, and documentation
- Cleaning AI-assisted drafts before publishing
- Removing AI patterns from text you own

## Based on

- StoryScope (COLM 2026) - fiction research on AI vs human writing patterns
- Wikipedia's "Signs of AI writing" - community-maintained pattern catalog
- Watermark reduction techniques from guillaumemeyer/watermarks-remover

## Installation

Copy the `SKILL.md` file to your Claude Code skills directory:

```
~/.claude/skills/human-writer/SKILL.md
```

## Usage

Invoke with `/human-writer` or ask Claude to humanize your text.

## License

MIT
