# PROMPT ENGINE

**An adaptive, modular prompt engineering system for professional AI workflows.**

PROMPT ENGINE turns goals, requirements, source files, and project context into structured, execution-ready prompts. It is designed for use with Claude and ChatGPT and supports seven specialist domains.

## Core principles
- **Adaptive discovery:** ask only the questions that materially improve the result.
- **Context-aware:** inspect supplied files, existing code, data models, constraints, and prior decisions before proposing changes.
- **Modular:** route work to a specialist module while preserving a consistent core workflow.
- **Professional output:** produce clear scope, requirements, implementation steps, acceptance criteria, assumptions, and risk controls.
- **English prompt output:** conversation and interface may be multilingual; the final generated prompt is always in English.

## Supported domains
1. Dashboard development
2. Data analysis
3. Software development and coding
4. Product, platform, and system development
5. Corporate communication and email
6. UI/UX and digital product design
7. Brand identity and visual systems

## Repository structure
```
PROMPT-ENGINE/
├── SKILL.md
├── core/
│   ├── workflow.md
│   ├── adaptive-discovery.md
│   ├── context-analysis.md
│   ├── language-policy.md
│   └── quality-assurance.md
├── modules/
│   ├── dashboard.md
│   ├── data-analysis.md
│   ├── coding.md
│   ├── platform-development.md
│   ├── corporate-email.md
│   ├── ui-ux-design.md
│   └── brand-identity.md
├── templates/
│   └── master-prompt.md
├── adapters/
│   ├── claude.md
│   └── chatgpt.md
├── interface/
│   └── interaction-guidelines.md
├── docs/
│   ├── architecture.md
│   └── usage-examples.md
└── tests/
    └── acceptance-checklist.md
```

## Quick start
1. Install or add this repository's `SKILL.md` as a Skill in your supported assistant environment.
2. Invoke the skill and describe the outcome you want.
3. Answer the adaptive clarification questions. You may skip non-essential questions.
4. Provide relevant files, examples, constraints, or existing project artifacts when available.
5. Review the generated English prompt and run it in the target AI environment.

## Language behavior
- Detect and use the user's conversation language for questions and explanations.
- Keep interface language, conversation language, and prompt-output language as separate settings.
- Default prompt-output language is **English** and must remain English unless the user explicitly requests a different output language.
- Preserve exact names, labels, field names, code identifiers, and quoted source text when translating requirements.

## Design philosophy
PROMPT ENGINE is a prompt specification and workflow framework, not a guarantee that an AI assistant can execute every requested action. Tool access, file access, deployment permissions, and platform-specific UI capabilities depend on the host environment.

## License
MIT. See [LICENSE](LICENSE).
