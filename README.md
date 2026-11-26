# Draft Recommendation Letter

An Agent Skill for drafting, revising, and reviewing academic and professional letters of recommendation in **Codex, Claude Code, and Claude**. It helps recommenders turn firsthand observations into a tailored endorsement for admissions, scholarships, fellowships, academic appointments, or employment. It also supports structured recommendation forms.

## Install in Codex

For one project, run this from its root directory.

```sh
git clone https://github.com/aravindgopisetty/draft-recommendation-letter.git .agents/skills/draft-recommendation-letter
```

For all your projects, place the whole `draft-recommendation-letter` folder in `.agents/skills` under your home directory. Restart Codex if the skill does not appear. [Codex guidance on skill locations](https://learn.chatgpt.com/docs/build-skills#where-codex-loads-local-skills)

## Install in Claude Code

For one project, run this from its root directory.

```sh
git clone https://github.com/aravindgopisetty/draft-recommendation-letter.git .claude/skills/draft-recommendation-letter
```

For all your projects, place the folder in `.claude/skills` under your home directory. Run `/draft-recommendation-letter` in Claude Code. [Claude Code skills documentation](https://code.claude.com/docs/en/skills)

## Install in Claude on the web or desktop

Download and extract the repository, then rename the extracted folder to `draft-recommendation-letter` and ZIP the folder. With code execution enabled, open **Customize → Skills** in Claude and choose **Upload a skill**. Select the ZIP and enable the skill. [Claude Help Center instructions](https://support.claude.com/en/articles/12512180-use-skills-in-claude)

## Use the skill

In Codex, mention `$draft-recommendation-letter`. In Claude Code, use `/draft-recommendation-letter`. In Claude chat, ask Claude to use the Draft Recommendation Letter skill. Share the opportunity, how you know the candidate, what you observed firsthand, and any instructions or length limits from the recipient.

> Draft a letter for a former direct report applying to a master's program. Ask me for any missing details that would help you explain why I recommend them.

The skill keeps factual gaps visible and calibrates the endorsement to the evidence. The recommender reviews the final wording and follows the recipient's authorship and submission rules.

## Files

- [SKILL.md](SKILL.md) defines the drafting and review workflow.
- [Evidence and formats](references/evidence-and-formats.md) covers opportunity-specific evidence, fictional examples, and structured prompts.
- [Codex metadata](agents/openai.yaml) supplies the display name and starter prompt.
