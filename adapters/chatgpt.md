# ChatGPT adapter

## Installation options
- Use the repository as the source for a custom GPT's instructions and knowledge files, where available.
- Add the core workflow and relevant specialist modules to the configured instruction/knowledge setup.
- For a reusable workflow, keep the master prompt template and QA checklist available to the assistant.
- If using a Skill-compatible feature in your environment, package the root `SKILL.md` and its referenced directories according to that feature's import requirements.

## Usage
Ask PROMPT ENGINE to create a prompt for a specific task. Attach source files for artifact-dependent work. The assistant should ask only material clarification questions and produce an English, self-contained prompt.

## Capability note
Available tools, file handling, connectors, and interactive controls depend on the ChatGPT environment and account configuration. Instructions cannot grant permissions or create unsupported UI behavior.
