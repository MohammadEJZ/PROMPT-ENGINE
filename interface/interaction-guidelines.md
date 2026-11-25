# Interaction and interface guidelines

These guidelines define the desired experience when the host environment supports interactive UI.

## Experience principles
- Keep the interaction focused and progressive.
- Show only questions relevant to the selected task.
- Use clear labels and concise helper text.
- Support free-text answers and "Let the engine decide".
- Make optional fields skippable.
- Show progress only when the number of steps is meaningful and stable.
- Provide a review step before generating the final prompt.

## Suggested stages
1. **Goal** — desired outcome and task type.
2. **Context** — project, files, and existing state.
3. **Requirements** — key functional, technical, and design constraints.
4. **Validation** — acceptance criteria and output format.
5. **Generate** — English prompt preview and copy/export action.

## Host limitations
Do not promise a specific placement, native checkbox style, side panel, modal, or persistence behavior unless verified in the target host. If interactive UI is unavailable, use concise conversational questions instead of simulating nonfunctional controls.
