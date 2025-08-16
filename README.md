# HogueResMaster

AI-powered resume and career accelerator that helps every job seeker stand out — fast, safe, and professional.

### Why this gets you noticed
Most companies use an Applicant Tracking System (ATS) — software that scans and ranks resumes before a human reads them. HogueResMaster rebuilds your resume from scratch with ATS-safe structure (clear headings, clean lists, no tables or text boxes) so automated scanners can parse it correctly and recruiters see the right story. You get polish and parseability.

## ✨ What it does
- 📑 Transforms any resume (student, veteran, or professional) into a polished, recruiter-ready, ATS-safe document.
- ⚡ Tailors your resume to a job posting by scanning and matching keywords automatically.
- 🎯 Boosts interview confidence with an Interview Guide and STAR prompts (Situation, Task, Action, Result).
- 🛡️ Saves time with basic scam-signal checks and safe-apply awareness.
- 🏥 Smart add-ons for healthcare and CV (Curriculum Vitae) style roles.
- 🖨️ Exports that work anywhere: DOCX primary, RTF (Rich Text Format) fallback, PDF (Portable Document Format) guide.

## 📱 Quick start (iPhone / Android / Desktop)
You don’t need to install anything. Use ChatGPT, Google Gemini, or Microsoft Copilot.

1) In one conversation, upload:
   - Your resume (Word, PDF, or screenshot)
   - The job posting (file, screenshot, or link)
   - The file HogueResMaster (.py)
2) Type exactly: Run HogueResMaster
3) Download your outputs:
   - 📝 Resume (DOCX; falls back to RTF if the Word library isn’t available)
   - 📄 Cover Letter (DOCX; falls back to RTF)
   - 📊 Interview Guide (HTML, plus a real PDF when ReportLab is available)
   - 🔍 ATS-safe Text (optimized for scanners)
   - ✏️ Redline (before vs. after)
   - ✅ Manifest JSON (files + scores)

Mobile tip (iPhone/Android): Long-press a link → “Download Linked File” (iOS Safari) or “Download link” (Android Chrome).

## 🔑 Why it’s different
- Built for ATS and people. Clean structure the bots can read; crisp wording recruiters appreciate.
- Rebuild, not patch. It re-creates a clean resume instead of editing around broken templates or text boxes.
- Mobile-first flow. Works straight from iPhone/Android with 2 simple steps.
- No gimmicks. Clear outputs, transparent scoring, professional formatting.

## 🧩 Outputs & file naming
All files follow a clear pattern:
`First_Last_Company_Title_YYYY-MM-DD_*`

You’ll see:
- _RESUME.docx (or .rtf when needed)
- _COVER.docx (or .rtf)
- _GUIDE.html and _GUIDE.pdf (PDF when ReportLab is present)
- _ATS.txt
- _REDLINE.diff.txt
- _MANIFEST.json

## 🔧 Optional switches (desktop / advanced)
- `--check_updates yes` → check GitHub Releases for a newer version (default: `no`)

## 🔗 Links
- Project site (GitHub Pages): https://hoguej77.github.io/hogueresmaster/
- All releases: https://github.com/hoguej77/hogueresmaster/releases

To download on mobile: open the latest release → scroll to “Assets” → tap the .py or .zip.

## 💬 FAQ (short)
**What is ATS (Applicant Tracking System)?**  
Software that scans resumes for keywords/structure before a human review. Clean, simple formatting helps your resume be parsed correctly and ranked fairly.

**Can I use this for an internal promotion?**  
Yes. Upload your current resume and the internal posting. The tool will tailor content and keywords to the new role.

**Will a PDF resume be read by ATS?**  
Some systems do, many prefer Word or plain text. That’s why we output DOCX/RTF plus a separate ATS-safe text file.

## ❤️ Support / Sponsors
If this helps you, you can support development via the “Sponsor” button on the repository. Thank you!

## 🔐 License
All rights reserved. You may use the generated outputs for your own job search. Commercial redistribution or hosted resale of this code requires written permission from the author.

# Changelog

## v9.2.2 — RTF fallback, polished outputs
- ✅ RTF (Rich Text Format) fallback for Resume and Cover when the Word library (python-docx) isn’t available — no more plain text; preserves bold headings and bullets; opens in Microsoft Word, Apple Pages, and Google Docs.
- ✅ Manifest now records the actual produced format (DOCX or RTF).
- ✅ Keeps PDF guide and opt-in update checker from v9.2.1.

## v9.2.1 — Real PDF guide + opt-in updates
- ✅ Interview Guide PDF generated with ReportLab when available; always writes HTML (HyperText Markup Language) as fallback.
- ✅ Update checker is opt-in via `--check_updates yes` (default: off).

## v9.2 — Mobile-first + clarity
- ✅ Mobile-first quick start for ChatGPT, Google Gemini, and Microsoft Copilot.
- ✅ First-mention acronym expansion for clarity (e.g., Applicant Tracking System (ATS), Situation–Task–Action–Result (STAR)).
- ✅ Cleaner DOCX layout (headings, bullet lists, ATS-safe sections).
- ✅ Stable file naming and per-run manifest/logs.

## v9.1 — Sponsor-ready docs
- ✅ Simplified iPhone/Android instructions and README polish for early testers and sponsors.

## v9.0 — Foundation for beta scale
- ✅ Batch scaffolding and job-scan JSON groundwork.
- ✅ Risk banner surfaced early in the run summary to highlight potential posting red flags (design in place; data plumbing introduced).

## v8.8 — Stability and cleanups
- ✅ Consolidated internal logs, change tracking, and placeholders for future automation.
- ✅ Formatting and spacing passes to reduce page-break “cliff-hangers.”

## v8.5 — Preview presets and user experience
- ✅ Streamlined level presets (e.g., one-page vs two-page); clearer “resume level” picker.
- ✅ More consistent output naming across runs.

## v8.3 — Learning from market feedback
- ✅ Hardened parsing against locked templates and text-box-heavy resumes from third-party builders.
- ✅ Safer extraction path for screenshots and inconsistent uploads.

## v8.1 — Formatting fidelity
- ✅ Cleaner underlines for contact blocks, polished star/bullet rendering, and better page-break hygiene.

## v8.0 — Holistic revamp
- ✅ Rebuilt output pipeline with emphasis on professional tone, modern formatting, and consistency across devices.
- ✅ Interview “cheat sheet” expanded toward a study-guide format.

## v7.6 — Auto-mode (no flags)
- ✅ Auto-detect uploads and infer company and job title from the job posting.
- ✅ One-command run; fewer prompts.

## v7.5 — Name extraction
- ✅ Auto-extract candidate name from the resume contents and header.

## v7.4 — Print options and consolidated beta build
- ✅ Added print-friendly options.
- ✅ Introduced the mission statement and consolidated the beta-usable build.

## v1–v7 (internal prototypes; summarized)
- v6.x: HTML Interview Guide; redline (before vs after) diff; improved file naming.
- v5.x: DOCX writers for Resume and Cover; basic job parsing; composite scoring (keyword match, scan health, hire likelihood with letter grade).
- v4.x: Reading for common formats (DOCX, PDF, TXT); early scam-signal patterns and job shortlisting JSON.
- v3.x: Domain add-ons (healthcare): Electronic Medical Record (EMR) and compliance keywords (HIPAA, OSHA); certifications and specialties surfacing.
- v2.x: Action-verb and metric heuristics; ATS-oriented text output; keyword coverage scoring.
- v1.0: Minimal pipeline — read resume and job description, build a clean resume scaffold, and output starter files.
