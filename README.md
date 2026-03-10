# OpenClaw Skills

A collection of skills for [OpenClaw](https://docs.openclaw.ai) — extending its capabilities through reusable, modular skill definitions.

## Available Skills

| Skill | Description |
|-------|-------------|
| [configure-OpenClaw](skills/configure-OpenClaw/) | Safely modify `openclaw.json` configuration with validated patches. Covers all config sections including agents, channels, auth, tools, gateway, session, cron, hooks, and more. |

## Usage

Install a skill by adding it to your OpenClaw configuration's `skills.entries` section, or follow the individual skill's setup instructions.

## Contributing

To add a new skill, create a directory under `skills/` with a `SKILL.md` file defining the skill's name, description, and instructions.
