# paperwrite

A shared paper-writing method for all research projects, usable by Claude, Codex, Gemini, GPT or a person.

**Paper-writing skill:** [`skills/research-paper-story-writing/SKILL.md`](skills/research-paper-story-writing/SKILL.md)

What it covers:

- story first: a key content map, then the Introduction reasoned backward and then forward;
- templates for the title, Abstract/Summary, Introduction, Methods, Results, Discussion and Limitations;
- paragraph and sentence craft: one message per paragraph, flow, reverse outlining, writing with LLM help;
- a five-dimension adversarial self-review, and a claim–evidence map;
- venue formats (iScience/Cell Press, MDPI, CV/ML conferences);
- value judgement: incremental contribution, honest conditional findings, limitations framed as scope.

## How to use

**Claude:** the skill is installed in the author's Claude account under the same name. This file is the reference copy. When the account copy changes, update it here too, and the other way round.

**Codex / Gemini / GPT, in another project repository:** add one line to that repository's `AGENTS.md` or `GEMINI.md`:

```
When writing or revising the paper, first read and follow
https://github.com/Casey-sketch-cyber/paperwrite/blob/main/skills/research-paper-story-writing/SKILL.md
```

Then keep the project-specific content in the project repository: a `docs/PAPER_STORY.md` with the story, outline, terminology and evidence map. See [`templates/PAPER_STORY_TEMPLATE.md`](templates/PAPER_STORY_TEMPLATE.md).

**Example in use:** `Casey-sketch-cyber/research` (`docs/PAPER_STORY.md`, `GEMINI.md`).

## Sources and credit

The method adapts Peng Sida's public paper-writing template and its skill packaging. The adaptation adds empirical and computational journal papers, Cell Press formats, evidence discipline and a value-judgement section.

- Peng Sida, 论文写作模板 (paper-writing template): https://pengsida.notion.site/c1a22465a0fa4b15a12985223916048e
- Peng Sida, learning_research: https://github.com/pengsida/learning_research
- Master-cai, Research-Paper-Writing-Skills (MIT): https://github.com/Master-cai/Research-Paper-Writing-Skills

Credit these sources when quoting or adapting this material in public.
