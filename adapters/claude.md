# Claude adapter

## Installation
1. Download or clone this repository.
2. Ensure `SKILL.md` is at the root of the Skill package.
3. Include the `core/`, `modules/`, and `templates/` directories so the skill can load its specialist instructions.
4. Package the folder as a ZIP if the Claude interface requires an uploaded Skill archive.
5. Enable the Skill in Claude's settings and test with a simple request.

## Usage
Invoke PROMPT ENGINE and describe the desired outcome. Attach source files when the task depends on them. The skill should ask adaptive questions and return the final prompt in English.

## UI capability note
A Skill's Markdown instructions do not, by themselves, create a custom persistent form or guarantee that controls render in the chat composer. If the host supports Artifacts or interactive UI, those may be used as a separate interface. Do not assume Artifact state automatically transfers to the conversation; explicitly summarize or pass collected answers through supported host features.
