# Procurement Solicitation Document Generator

Single-page, browser-only app for building procurement solicitation documents (RFP, RFT, RFQ, ITB, EOI and others). No backend. Project data stays in the browser's local storage.

## Run
Open `index.html` in a browser, or publish it with GitHub Pages (Settings > Pages > Deploy from branch `main`, folder `/`).

## Features
- Project details, source import (TXT, CSV, MD, DOCX, XLSX, text-based PDF)
- Design ideas review, requirements matrix, section builder, scope draft
- Evaluation weights and pricing schedule
- Guide template analysis (DOCX), numbering formats, cover/header/footer text
- Quality check, native DOCX export, print to PDF, JSON backup

## Notes
PDF extraction loads pdf.js and JSZip from cdnjs. All other processing is local.
