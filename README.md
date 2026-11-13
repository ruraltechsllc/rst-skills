# rst-skills

Rural Solutions' Agent Skills, served to the team through Conduit (pack: rst-skills). Each skill is `skills/<name>/SKILL.md`; `.claude-plugin/plugin.json` carries the version.

| Skill | What it does |
|---|---|
| rs-today | What's next, my day, NOD check-in, close out |
| rs-tickets | The board |
| rs-ticket | Go deep on one ticket: new-ticket or escalation brief |
| rs-projects | Read, build and close projects |
| rs-lifecycle | A person, a device or a whole client starting or leaving |
| rs-bec-check | A suspected compromised account |
| rs-visual | A plain-language HTML page for a client, published to IT Glue or the website |

## Releasing a change
1. Edit the skill, bump `version` in `.claude-plugin/plugin.json` and the skill's footer line.
2. Commit and push to `main`.
3. In Conduit (Skill Packs, Custom), press the sync arrow on the ruraltechsllc/rst-skills card, then review and enable any new or changed skill. Conduit serves it as pack `custom-ruraltechsllc-rst-skills`.

This repo is public, so Conduit can read it. Never put passwords, keys, tokens or client secrets in a skill.

Owner: Thomas.
