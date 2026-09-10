# Michael Borja — Portfolio V4.3

V4.3 is a focused revision of V4.2. It keeps the V4.1/V4.2 editorial visual system, but restructures the healthcare freelance work into one continuous client case study instead of presenting the spreadsheet automation and Web App work as separate portfolio projects.

## Main narrative change

The public site now presents the healthcare engagement under the fictional public name **Demo Healthcare Group** as a single solution journey across two Upwork contracts:

1. **Phase 1 — Google Sheets operations system**  
   Upwork title: **Excel Spreadsheet Automation Specialist**  
   May 2025 – Mar 2026 · 212 billed hours · 5.0/5.0

   Michael first built the working operational and reporting interface in Google Sheets. The system used structured entry fields, dropdowns, validation, conditional formatting, search/filter controls, update actions, archive controls, status tracking, billing fields, and reporting logic.

2. **Phase 2 — Production Web App frontend**  
   Upwork title: **Full-Stack Google Workspace Developer**  
   Mar 2026 – Jul 2026 · 108 billed hours · 5.0/5.0

   After the spreadsheet solution had been used for several months, Michael proposed separating the user-facing workflow from the underlying Google Sheets data layer, then built the role-based Web App frontend and supporting Google Workspace integrations.

Together, these phases represent **320 billed hours across two 5.0/5.0 contracts for the same client**.

## What was removed

- The standalone **Excel & Sheets Reporting Automation** card was removed from Featured Work.
- The standalone spreadsheet-automation case study was removed from Additional Case Studies.
- The two healthcare contracts are no longer shown as separate Upwork portfolio cards.

The underlying contract history is still stated accurately: **three Upwork contracts across two client relationships** in the US and Australia.

## Flagship case study structure

The healthcare flagship now tells the full continuous story through:

- Same-client project evolution
- My role across both phases
- Problem → Approach → Solution → Result
- Phase 1 visual evidence: sanitized Google Sheets operations system
- Phase 2 visual evidence: sanitized production Web App screenshots
- System workflow map and technology stack

This makes the project read as an example of solution evolution and architectural judgment, rather than two disconnected jobs.

## Screenshot privacy

The original Phase 1 spreadsheet screenshot is **not included** in this package.

The public portfolio uses these portfolio-safe screenshots:

- `screenshot-sheets-phase1.png` — a sanitized portfolio version based on the original Google Sheets interface;
- `screenshot-dashboard.png` — sanitized operational dashboard / home overview;
- `screenshot-visits.png` — sanitized visiting dashboard;
- `screenshot-master-list.png` — sanitized master list dashboard;
- `screenshot-facility-performance.png` — sanitized facility performance dashboard;
- `screenshot-billing-matrix.png` — sanitized billing weekly matrix;
- `screenshot-session-timeout.png` — sanitized session timeout / security screen.

The healthcare engagement is identified publicly only as **Demo Healthcare Group**. All visible patient names, record IDs, room numbers, facility names, provider/administrator names, visit dates, diagnoses, insurance information, CPT codes, statistics, counts, and activity records shown in the screenshots are fictional/demo data created for portfolio use and are not taken from or derived from actual patient or production records. Original client branding, private URLs, credentials, and internal system details must not be added to the public repository or deployed site. Where Record IDs are visible, they remain alphanumeric to reflect the application structure without exposing real identifiers.

## Additional case-study interaction

The Additional Case Studies section uses native HTML `<details>` accordions with an explicit **View case study** label, outlined `+ / −` indicator, and hover/focus feedback. This keeps the editorial visual style while making it immediately clear that each row can be expanded.

## Project structure

```text
michael-borja-portfolio-v4.3/
├── index.html
├── README.md
└── assets/
    ├── css/style.css
    ├── js/main.js
    ├── images/
    │   ├── favicon.svg
    │   ├── og-cover.svg
    │   └── healthcare/
    │       ├── screenshot-sheets-phase1.png
    │       ├── screenshot-dashboard.png
    │       ├── screenshot-visits.png
    │       ├── screenshot-master-list.png
    │       ├── screenshot-facility-performance.png
    │       ├── screenshot-billing-matrix.png
    │       └── screenshot-session-timeout.png
    └── resume/
        └── Michael-Borja-Resume-Public.pdf
```

## Local preview

```bash
cd michael-borja-portfolio-v4.3
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Cloudflare Pages

```text
Framework preset: None
Build command: exit 0
Build output directory: .
Root directory: leave blank
```

The site remains static HTML/CSS/vanilla JavaScript and requires no framework or build tool.
