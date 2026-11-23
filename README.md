# Claude skills

A collection of useful Claude skills.

## Structure

- `skills/` contains one folder for each skill.
- Each skill folder contains a `SKILL.md` file. Other files for the skill go in the same folder.

## Add a skill

1. Make a folder in `skills/` with a kebab-case name, for example `skills/my-skill/`.
2. Put a `SKILL.md` file in the folder. Start the file with frontmatter that has `name` and `description`.

## Submodules

These skill collections are git submodules in `skills/`:

- `skills/mattpocock-skills`: https://github.com/mattpocock/skills
- `skills/agent-skills`: https://github.com/addyosmani/agent-skills
- `skills/security-audit-skill`: https://github.com/cloudflare/security-audit-skill
- `skills/obsidian-skills`: https://github.com/kepano/obsidian-skills
- `skills/elephant-goldfish-model`: https://github.com/google/elephant-goldfish-model
- `skills/janestreet-agent-skills`: https://github.com/janestreet/agent_skills
- `skills/wolfram-system-modeler-ai-toolkit`: https://github.com/WolframResearch/system-modeler-ai-toolkit

After you clone this repository, run `git submodule update --init` to get them.
To update them to the latest version, run `git submodule update --remote`.
