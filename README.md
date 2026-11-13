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
3. In Conduit, re-import or sync the pack from this repo, then review and enable any new or changed skill.

Owner: Thomas.
