# Skills all

Reusable agent skills for Guru Team and OpenCode.

## Import into Guru Team

Open Skills, choose Import, and paste this source:

```text
https://github.com/ai-tools-all/skills-all/tree/main/skills/guru-digest
```

The import field takes a repository source, not pasted Markdown. Importing saves the skill in your library. Select it for the agent that should use it.

## Available skills

- [guru-digest](skills/guru-digest/SKILL.md): Turn a source link and instructions or Markdown into a Learning Harness v3 digest, validate it, and publish with `bun run deploy` through Cloudflare.

Provide your app's absolute directory and the account to use for verification in your prompt. The agent must have access to that checkout, its dependencies, and Cloudflare authentication. App login is separate from deployment authentication. No credentials or machine-specific account settings are included here.
