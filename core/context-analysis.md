# Context and artifact analysis

## Source hierarchy
Use this precedence unless the user specifies otherwise:
1. Explicit instructions in the current request
2. Current-turn uploaded files and references
3. Confirmed project decisions from prior context
4. Existing implementation and data structures
5. Reasonable assumptions, clearly labeled

## For code and software
Inspect architecture, entry points, dependencies, data flow, state management, styling conventions, APIs, and existing tests. Identify the smallest safe change.

## For dashboards
Inspect source data, schema, joins/relationships, calculations, filters, date logic, chart encodings, empty states, and responsive behavior. Reconcile displayed metrics with source records.

## For spreadsheets and analysis
Identify sheets, headers, data types, units, missing values, duplicates, formulas, date formats, percentage scales, outliers, and source limitations. Do not silently clean or overwrite source data.

## For visual references
Describe observable layout, hierarchy, spacing, typography, color, interaction, and responsive patterns. Treat references as inspiration unless the user says to reproduce them.

## For documents and email
Extract audience, purpose, tone, key facts, requested action, deadlines, confidentiality, and approval constraints.

## Context report
Before drafting, internally classify each important item as:
- Confirmed
- Inferred
- Assumed
- Unknown
Do not present an inference as a fact. Preserve exact labels and terminology where required.
