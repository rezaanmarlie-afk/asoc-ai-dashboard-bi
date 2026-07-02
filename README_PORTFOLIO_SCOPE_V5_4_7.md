# Version 5.4.7 - Portfolio Scope Settings

This release keeps the main dashboard landing page clean and moves calculation scope controls to a separate admin page.

## New page

`/admin/portfolio-scope`

Menu label: **Dashboard Settings**

## What it controls

The saved Portfolio Scope is now the single source of truth for calculations across:

- Dashboard KPI cards
- Executive gauges
- Portfolio value by domain
- Hours saved by domain
- Sponsor value view
- Portfolio delivery mix
- AI portfolio heatmap
- Benefits Intelligence
- PowerPoint export

## Supported scope filters

- Included statuses
- Excluded statuses
- Included domains
- Included markets
- Included sponsors
- Included technical owners
- Included benefit types
- Minimum confidence threshold

## Recommended realised-benefit scope

Exclude these statuses from realised-benefit calculations:

- AI Opportunity
- Planned
- Sandbox
- Retired

## Notes

The dashboard landing page now only shows a concise scope label and a link to change settings. It no longer exposes multi-select scope controls on the executive landing page.
