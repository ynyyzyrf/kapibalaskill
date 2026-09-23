# Ian Capybara Illustrations Skill

This repository contains a Codex skill for generating Ian-style Chinese article illustrations with a recurring capybara IP.

## Preview

Capybara IP reference:

<img src="ian-capybara-illustrations/assets/capybara-reference.png" alt="Capybara reference" width="280">

Example illustration style:

<p>
  <img src="ian-capybara-illustrations/assets/examples/01-two-breakpoints.png" alt="Two breakpoints example" width="420">
  <img src="ian-capybara-illustrations/assets/examples/04-one-fish-many-uses.png" alt="One fish many uses example" width="420">
</p>

<p>
  <img src="ian-capybara-illustrations/assets/examples/10-information-well.png" alt="Information well example" width="420">
  <img src="ian-capybara-illustrations/assets/examples/14-trust-bridge.png" alt="Trust bridge example" width="420">
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
