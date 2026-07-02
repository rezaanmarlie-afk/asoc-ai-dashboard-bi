# Version 5.4.1 – ASOC Benefits Intelligence Domain Alignment

This build keeps AI removed and focuses on making Benefits Intelligence relevant to the dashboard use-case register.

## Key changes

- BI records now link directly to dashboard AI use cases using `ai_use_case_id`.
- BI domains are inherited from `data/use_cases.json` and use the exact dashboard domain taxonomy:
  - Configuration Management
  - Fault Management
  - OSS
  - Performance Management
- Business Unit is standardised to `ASOC` because the dashboard tracks ASOC benefits across all ASOC domains.
- Benefits Intelligence now includes ASOC domain tracking cards.
- BI Admin now guides users to select a dashboard AI use case first.
- Selecting a use case auto-fills / aligns domain, sponsor, owner and use-case name.
- Inline save now preserves existing enriched fields instead of blanking fields that were not visible in the row editor.
- Enriched sample data is regenerated from the actual dashboard AI use cases.

## Import file

Use:

`benefits_intelligence_enriched_sample_import.csv`

It contains 444 rows linked to the current AI use-case register.

