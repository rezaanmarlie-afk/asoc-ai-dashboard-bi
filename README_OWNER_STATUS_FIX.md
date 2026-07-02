# Version 5.4.6 - Owner Preservation Fix

Fixes a bug where editing a use case status, including changing it to **AI Opportunity**, could make the editable list display the current editing user as the owner.

Changes:
- Existing `created_by` metadata is preserved on edit.
- Existing `technical_owner` is preserved if the edit form submits it blank.
- Admin table now displays **Technical Owner**, not `created_by`.
- The Technical Owner field no longer defaults to the logged-in user when editing existing records.

No existing AI use case, BI, PPT export, dashboard calculation, or status exclusion logic was intentionally changed.
