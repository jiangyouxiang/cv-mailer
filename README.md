# CV Mailer

`cv-mailer` is a Codex skill for drafting, reviewing, sending, and verifying job application emails with resume attachments through Mail MCP.

The skill requires the complete message, recipients, links, formatting, and attachments to be shown as **UNSENT**. It permits sending only after the user explicitly approves that exact version.

## Requirements

- Codex with skill support
- A configured Mail MCP server exposed as `mail`

## Install

Install with the Codex skill installer from this repository, or copy this repository into your Codex skills directory as `cv-mailer`.

Restart Codex or begin a new turn after installation so the skill can be discovered.

## Usage

Ask Codex to use `$cv-mailer` to prepare an application email. Review the complete unsent snapshot, request any revisions, and explicitly say `send` only when the exact version is ready.

## License

MIT
