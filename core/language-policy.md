# Language engine and localization policy

## Independent language settings
Treat these as separate:
- Conversation language: language used to communicate with the user.
- Interface language: language used in any questionnaire, form, or UI.
- Prompt output language: language of the final generated prompt.

## Default behavior
- Detect conversation language automatically.
- Match the user's language for questions, explanations, and execution notes.
- Default interface language to the user's language.
- Set final prompt output language to **English**.

## English prompt requirements
The final prompt must be idiomatic, precise professional English. Translate intent, not merely words. Keep exact source labels, proper nouns, identifiers, field names, formulas, and literal UI copy unchanged when translation would damage fidelity. Add brief English explanations around retained non-English terms when needed.

## Explicit override
If the user explicitly requests another prompt-output language, follow that request for the current task. Otherwise English remains the default.

## Multilingual inputs
Accept requirements and source files in any language supported by the host model. Do not reject a task because its source language differs from the prompt-output language.
