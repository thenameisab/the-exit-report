# the-exit-report

A single-page weekly report site. `index.html` is the source page; `site/index.html` is the published copy served by GitHub Pages.

## Writing

All prose in this project goes through the `no-ai-slop` skill in `.claude/skills/no-ai-slop/`. That covers report copy, headings, chart labels and captions, blurbs, README text, and any draft written or edited here — not just when someone asks for an edit pass.

When writing or revising prose:

1. Read `.claude/skills/no-ai-slop/SKILL.md` before drafting.
2. Apply its rules: preserve the writer's voice, cut the banned words and patterns, stay concrete.
3. Check the result against `.claude/skills/no-ai-slop/eval.md` and fix anything that fails before returning it.

When editing existing copy, make the minimum effective edit and say what changed.

Code, comments, and commit messages are exempt.

The skill is vendored from https://github.com/petergyang/no-ai-slop (MIT, commit `d30eddb`). To update it, copy `skills/no-ai-slop/SKILL.md` and `eval.md` from that repo.
