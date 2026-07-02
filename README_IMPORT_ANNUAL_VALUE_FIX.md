# Import Annual Value Fix

This release fixes CSV import where `annual_value` was imported incorrectly when the CSV contained Excel formulas or formatted currency values.

Fixes included:
- Evaluates simple Excel arithmetic formulas exported into CSV.
- Supports same-row formula references such as `[[#This Row],[hours_saved]]`.
- Imports numeric values with currency symbols, commas and percentage signs.
- Accepts `manager`/`ehod` aliases as well as `technical_owner`/`sponsor`.
- Preserves the existing CSV update/upsert behaviour using `id`.

A pre-calculated CSV is also provided: `OSS_ai_use_cases_IMPORT_READY_VALUES_FIXED.csv`.
