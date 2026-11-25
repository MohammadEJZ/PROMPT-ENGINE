# Usage examples

## Dashboard modification
**User request:** "Update this dashboard to add a competitor comparison tab. Do not change the existing tabs or KPI calculations."

Expected engine behavior:
- Inspect the supplied dashboard and data sources.
- Preserve existing tabs, calculations, filters, and styles outside the requested scope.
- Ask about comparison dimensions only if they cannot be inferred from the data.
- Produce an English implementation prompt with file-specific instructions and regression checks.

## Data analysis
**User request:** "Analyze these sales records and identify the drivers of declining performance."

Expected engine behavior:
- Profile data quality and time coverage.
- Clarify the definition of performance only if ambiguous.
- Separate descriptive patterns from causal explanations.
- Require transparent calculations and limitations.

## Brand identity
**User request:** "Create a modern identity for an enterprise intelligence platform."

Expected engine behavior:
- Establish positioning and audience before visual execution.
- Ask for brand name and desired attributes if missing.
- Specify logo, typography, color, visual language, and usage contexts.
- Define evaluation criteria for distinctiveness and scalability.

## Corporate email
**User request:** "Write a formal follow-up asking for the delayed project report."

Expected engine behavior:
- Draft directly if recipient/context are sufficiently clear.
- Do not invent a deadline or prior commitment.
- Produce a ready-to-send email in the requested language.
