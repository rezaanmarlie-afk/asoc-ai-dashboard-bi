# AIDash BI Only Release

This build removes the Executive AI Analyst / AI Settings / Ollama integration and keeps the focus on Benefits Intelligence.

Preserved:
- Login and MFA
- Dashboard
- Use-case admin
- Benefits Intelligence
- BI Admin
- BI CSV import/export
- Dashboard CSV export/import
- PowerPoint export
- Users, security, audit, backups, system pages

Removed for now:
- /executive-ai-analyst
- /admin/ai-settings
- AI chat / Ask the Portfolio
- AI-generated PPT slide
- executive_ai_settings.json

Run locally:
```powershell
cd C:\AIH\apps\aidash6
python -m venv .venv
.\.venv\Scripts\activate
python -m pip install -r requirements.txt
python -m uvicorn app:app --host 127.0.0.1 --port 8000 --reload
```
