 📦 Release Notes — v11 (current)

Status: Stable • Known issues: none (fallbacks are intentional design, not defects) • Price: Free for now

✨ What’s new in v11
	•	🚀 Auto-start intake — no manual “run” command; accepts all-at-once uploads or guides step-by-step (resume → job post → options).
	•	🎛️ Style Pack with auto-suggest + multi-select override: Classic, Hybrid, Technical Individual Contributor, Executive, Healthcare, Federal, Academic Curriculum Vitae.
	•	💌 Evidence-only cover letters — warm/professional/direct tones; built from your real wins and the job’s needs (no clichés, no invented claims). If metrics are missing, you’ll get a friendly Accomplishment Nudge to add them.
	•	🏛️ Federal (USAJOBS) mode — “11:59 p.m. Eastern Time” reminder, cut-off detection, Specialized Experience alignment, Month/Year and Hours/Week prompts, USAJOBS badge and checklist PDF.
	•	🔒 ATS-safe (Applicant Tracking System) composition — single column, no tables/columns/text boxes, clean page breaks, consistent bullets; acronyms expanded once for clarity.
	•	🛡️ Risk & salary awareness — flags up-front fees / Telegram-only “interviews” / fake checks / crypto gift-card tasks; JOFDAV awareness; salary-transparency nudge where relevant.
	•	🖼️ OCR fallback for screenshots and image-only PDFs (best effort; polite nudge if OCR engine is unavailable).
	•	🔗 Link health checks for guides/reports (never modifies the resume).
	•	🅱️ A/B bullet variant + de-dup + tighten — optional second resume with metric-first ordering; caps to 6 bullets per role; aims for 1–2 lines each.
	•	🧷 Style memory — remembers your last style/length/options during the session.
	•	🔁 Idempotent runs — skips rebuilds when inputs and options haven’t changed.
	•	📦 Mobile-first ZIP — organized folders (/Resume, /Cover, /Guides, /Reports, /Federal) and a small README_first.rtf for iPhone/Android users.
	•	🧾 Output engines — Word (DOCX) is canonical, PDF when available, Rich Text Format (RTF) fallback (no plain .txt).
	•	🔐 Safe-Share ATS copy — hides phone number and street address by default (you can turn this off).

🧪 Internal QA checklist (v11)

Inputs (DOCX/PDF/screenshots) → pass (OCR fallback where possible)
Style suggest + user override + multi-style generation → pass
Federal gate (Month/Year + Hours/Week + badge/checklist) → pass
ATS formatting (single column, clean page breaks, acronym expansion) → pass
Outputs (DOCX/PDF/RTF) + mobile ZIP folders → pass
Idempotent runs (unchanged inputs) → pass
Privacy default (ATS copy masks phone/street) → pass

📥 Download (Assets)

Get the latest files here:
https://github.com/hoguej77/hogueresmaster/releases/latest

Look under Assets on that page (bottom) and download:
	•	HogueResMaster_v11.py (single file)
	•	or the release ZIP (contains the same file and example assets)

📱 Quick Start (Mobile — iPhone & Android)
	1.	Open the latest release link above. Under Assets, tap the file to download (long-press on iPhone/Android if needed → “Download Linked File”).
	2.	Open your AI app (ChatGPT, Google Gemini, or Microsoft Copilot).
	3.	In a single chat, upload:
• Your resume (Word, PDF, or screenshot)
• The job posting (file, screenshot, or link)
• The file HogueResMaster_v11.py (or the ZIP)
	4.	That’s it — it auto-starts and shows a friendly style screen with a suggested option.
	5.	You’ll receive:
• Resume (DOCX; RTF if needed)
• Cover Letter (authentic, evidence-only)
• Interview Guide (PDF when available)
• ATS-safe copy (privacy-safe by default)
• Redline summary (before → after)
• USAJOBS checklist (federal only)
• Deliverables.zip (mobile-friendly folders)

💻 Optional (Desktop)

If you have Python 3.10+ installed, you can run the script directly. Outputs save to the out/ folder with names like:
First_Last_Company_Title_Style_YYYY-MM-DD_SUFFIX.*

🥊 Why HogueResMaster is different
	•	ATS-first, not template-first: single column, no tables/columns/text boxes that break Applicant Tracking System parsing.
	•	Authentic cover letters: grounded in your real results; no fluff or invented claims.
	•	Federal-aware: Month/Year + Hours/Week prompts, Specialized Experience mapping, closing-time reminders, badge + checklist.
	•	Mobile-friendly delivery: organized ZIP folders + mini README for iPhone/Android.
	•	Safety built-in: scam flags, JOFDAV awareness, and salary-transparency nudges.
	•	Productivity wins: optional A/B bullet variant and idempotent runs to save time.

🆓 Free for now

After years of helping, representing, and assisting Veterans, this project is offered at no cost for now to everyone.

📚 Full history / roadmap

For a complete change log and future updates, see the dedicated file:
CHANGELOG.md in the repository root.

🔗 Useful links

Latest release: https://github.com/hoguej77/hogueresmaster/releases/latest
Website: https://hoguej77.github.io/hogueresmaster/

— Created & coded by Jonathan Hogue
