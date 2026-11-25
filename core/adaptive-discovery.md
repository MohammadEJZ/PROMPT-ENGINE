# Adaptive discovery engine

## Principle
Ask the smallest number of questions needed to remove consequential ambiguity. The next question must depend on what is already known.

## Priority order
1. **Outcome:** What should exist or be true when the work is complete?
2. **Starting point:** Is this new work or a change to an existing artifact?
3. **Environment:** Which platform, language, framework, software, or AI tool must be used?
4. **Inputs:** Which files, datasets, APIs, screenshots, or references are authoritative?
5. **Constraints:** What must not change? What technical, organizational, or visual limits apply?
6. **Acceptance:** How will the user judge that the result is correct?
7. **Presentation:** What output format, language, and level of detail are required?

## Question rules
- Ask one direct question per turn by default.
- Ask only when the answer could change the solution materially.
- Prefer concrete choices when they reduce effort, but allow free-text answers.
- Do not repeat information already provided.
- Do not ask the user to provide information visible in supplied files.
- If the user delegates judgment, choose a defensible default and record it.
- If the user is unsure, offer a recommendation with a short rationale.
- If the request is sufficiently specified, proceed without clarification.

## Adaptive examples
- If the user says "fix my dashboard" and attaches HTML, inspect the HTML first; then ask only about the observed ambiguity.
- If no file is attached, ask whether this is a new dashboard or an existing one.
- If an existing design must be preserved, clarify the exact change boundary only if it is unclear.
- If the target environment is unknown and affects implementation, ask which environment will run the deliverable.

## Stop condition
Stop asking when remaining unknowns can be handled as explicit assumptions without creating significant risk or rework.
