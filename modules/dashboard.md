# Specialist module: Dashboard development

Use for BI dashboards, executive dashboards, operational monitoring, KPI systems, and interactive reports.

## Discover
- Audience and decisions the dashboard should support
- Source files, database, APIs, refresh process, and data ownership
- Metric definitions, units, targets, thresholds, and time grain
- Required dimensions, filters, drill-downs, and hierarchy
- Existing dashboard files and protected layout/logic
- Runtime environment, deployment, browser, and screen sizes

## Specify
- Information architecture and page/tab hierarchy
- KPI definitions with formulas and aggregation rules
- Data model, relationships, transformations, and validation
- Chart type, axes, sorting, labels, legends, and color semantics
- Filter dependencies, cross-filtering, search, and empty states
- Responsive layout, accessibility, loading, and error states

## Data integrity requirements
Never invent KPI values. Reconcile totals with source data. Check percentage scaling (0.14 vs 14%), currency/unit consistency, date boundaries, duplicate rows, null handling, and increase/decrease indicator semantics.

## Modification safeguards
If an existing dashboard is supplied, preserve unrelated structure, styling, calculations, filters, and data bindings. Implement only requested changes. Do not rebuild from scratch unless explicitly authorized.

## Acceptance criteria
Every KPI matches its documented formula; filters produce correct subsets; charts reflect the filtered data; labels and units are correct; no console/runtime errors; layout remains readable at target display sizes.
