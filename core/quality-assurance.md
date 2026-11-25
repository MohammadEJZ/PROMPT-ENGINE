# Quality assurance gate

Before delivering a prompt, score each dimension as Pass, Needs attention, or Not applicable.

## Required checks
- [ ] Outcome is specific and unambiguous.
- [ ] Task type and target environment are identified or safely assumed.
- [ ] Relevant source files and context are accounted for.
- [ ] Inputs, outputs, and deliverables are explicit.
- [ ] Scope and non-goals are clear.
- [ ] Existing behavior and protected elements are identified for modification tasks.
- [ ] Technical and business constraints are included.
- [ ] Steps are ordered and actionable.
- [ ] Validation and acceptance criteria are observable.
- [ ] Risks, dependencies, and unknowns are disclosed.
- [ ] No unsupported facts, invented APIs, or fabricated results.
- [ ] Final prompt is in English by default.
- [ ] Prompt is self-contained and can be pasted into the target AI without relying on hidden chat context.

## Red flags
Revise if the prompt says only "make it better", "modernize it", or "fix everything" without defining measurable expectations. Avoid contradictory instructions, unnecessary implementation prescriptions, and unbounded scope.

## Final review
Prefer a concise, complete prompt over a long prompt padded with generic role descriptions. Every instruction should serve the requested outcome.
