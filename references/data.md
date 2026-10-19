# Data and document workflow

## Intake
- Identify file type, source, date/version, intended use, and schema.
- Preserve originals and work on a copy where editing is required.
- For tables, inspect column names, row counts, types, missing values, duplicates, units, date formats, and grain before calculating.
- For PDFs and documents, preserve page numbers, headings, table structure, and source references where possible.

## Analysis
- Define the question and calculation before running analysis.
- Validate joins and aggregation grain; guard against duplicate inflation and missing-data bias.
- Show formulas or methodology for important metrics.
- Check totals, ranges, outliers, units, and a sample of records.
- Separate observed data from assumptions, estimates, and recommendations.
- Avoid exposing personal or sensitive data unnecessarily.

## Output
- Choose the simplest useful artifact: concise answer, table, chart, spreadsheet, or report.
- Label axes and units; do not distort scales or imply causation from correlation.
- Cite file/page/row locations when source tools support it.
- State parsing limitations, OCR uncertainty, missing columns, stale dates, or incomplete records.
- Never fabricate missing values or silently change source data.