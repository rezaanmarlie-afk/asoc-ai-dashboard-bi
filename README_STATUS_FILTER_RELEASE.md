# Version 5.4.4 – Dashboard Status Filter

Changes added:

- Added new AI use case status: **AI Opportunity**.
- Added a dashboard-level **Dashboard Status View** selector.
- Dashboard can now show:
  - All Status
  - AI Opportunity
  - Planned
  - Sandbox
  - Prototype
  - In Progress
  - Pilot
  - Production
  - Measured
  - At Risk
  - Paused
  - Retired
- KPI cards, gauges, charts and the AI portfolio table now respect the selected status.
- `/api/summary` now accepts `?status=<status>` so dashboard charts use the same filter.
- Manage Use Cases status dropdown now includes AI Opportunity.
- BI Admin status dropdown also includes AI Opportunity.
