# Ian Capybara Illustrations Skill

This repository contains a Codex skill for generating Ian-style Chinese article illustrations with a recurring capybara IP.

## Preview

PPT/video background examples made with this skill:

<p>
  <img src="preview/01-memory-problem.png" alt="Agent memory problem background" width="420">
  <img src="preview/02-three-layer-overview.png" alt="Agent memory three-layer overview background" width="420">
</p>

<p>
  <img src="preview/03-oumi-ai-tutor-memory.png" alt="Oumi AI tutor memory background" width="420">
  <img src="preview/08-shared-memory-foundation.png" alt="Shared memory foundation background" width="420">
</p>

## Skill

- Skill path: `ian-capybara-illustrations/`
- Skill name: `ian-capybara-illustrations`
- Purpose: generate clean, sparse, hand-drawn Chinese article or video explainer illustrations using a deadpan capybara character as the core action subject.

## Install

Use Codex skill installer with this GitHub path:

```bash
python ~/.codex/skills/.system/skill-installer/scripts/install-skill-from-github.py \
  --repo ynyyzyrf/kapibalaskill \
  --path ian-capybara-illustrations
```

After installation, use:

```text
$ian-capybara-illustrations
```

## Notes

The skill includes:

- `SKILL.md`
- `references/` for style, character, prompt, composition, and QA guidance
- `assets/capybara-reference.png` for low-frequency character calibration
- `assets/examples/` for sparse visual style calibration
