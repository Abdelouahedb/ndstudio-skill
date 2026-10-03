# National Design Studio Inspired UI/UX

A reusable Codex skill for creating original website UI/UX inspired by [National Design Studio](https://ndstudio.gov/) and its selected portfolio.

The skill helps choose a suitable direction for the project: quiet editorial, monumental campaign, technical mission, warm service, or product narrative. It covers composition, typography, imagery, functional UX, responsive behavior, and verification.

## Install

Copy `SKILL.md`, `agents/`, and `references/` into your personal Codex skill folder:

- Windows: `C:\Users\YOUR_USER\.codex\skills\ndstudio\`
- macOS/Linux: `~/.codex/skills/ndstudio/`
- If you use a custom `CODEX_HOME`, use its `skills/ndstudio/` folder.

Keep the reference folders beside `SKILL.md` so its relative links resolve.

## Use

Invoke the skill in Codex with a brief such as:

```text
$ndstudio Build a website for my arts foundation, choosing the best direction from National Design Studio's portfolio.
```

For a narrower change:

```text
$ndstudio Refine this search results panel while preserving the app's existing brand and working behavior.
```

## Contents

- [SKILL.md](SKILL.md): selection criteria, design guidance, implementation, and verification.
- [Portfolio reference](references/portfolio.md): dated observations, primary-source links, and research limitations.
- [Implementation recipes](references/recipes.md): adaptable starting points for each design direction.
- [Codex interface metadata](agents/openai.yaml): display name and invocation prompt.

## Scope and provenance

This is an independent inspiration skill, not an official National Design Studio design system or an affiliated project. It does not distribute the studio's fonts, photography, logos, or website source code.

The research snapshot is dated September 30, 2026 and covers the studio homepage and its eight listed selected projects. Observations are separated from suggested adaptations. NASA Force's rendered visual composition was not verified; the reference documents that limitation. Final website quality still needs inspection in the actual project.
