# Agent Skills

Personal collection of AI agent skills. Compatible with the [Agent Skills](https://agentskills.io) format and installable via [`npx skills`](https://github.com/vercel-labs/skills).

## Installation

```sh
npx skills add <owner>/skills
```

## Skills

| Skill | Description |
| ----- | ----------- |
| [survey-filling](skills/survey-filling/) | Fill customer feedback surveys in a browser using standing answer rules; pause on unanswerable questions and confirm before submit |

## Layout

```text
skills/
└── <skill-name>/
    └── SKILL.md
```

Each skill is a flat folder under `skills/` with a required `SKILL.md`. No category nesting.
