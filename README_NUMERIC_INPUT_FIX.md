# Numeric Input Validation Fix

Fixes browser validation errors after importing use cases where numeric values were stored with floating point precision (for example `12.000000000000002`) or imported decimals.

Changes:
- Use case admin numeric inputs now use `step="any"`.
- Annual value, implementation cost and hours saved are normalised to whole numbers on save/import.
- MTTR improvement and reuse score are rounded to two decimals on save/import.
- Existing import update-by-ID logic is unchanged.
