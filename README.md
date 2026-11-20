# MLP-Recover – Prototype (NESFIC-D-08)

A single-file, front-end prototype for recovering value from multi-layer plastic (MLP) at Assam MRFs.

## Run
No install needed. Open `index.html` in any modern browser (Chrome, Edge, Firefox).
Optional local server: `python3 -m http.server 8000` then visit http://localhost:8000

## What is real vs simulated
- **Built:** MRF selector, picker lookup, bale ledger, pathway/economics calculator, printable report.
- **Simulated:** conveyor detections (scripted; no ML model), MRF capacities/volumes, prices.
- **Not built:** backend, database, login, real MRF integration. State resets on reload.

## Files
- `index.html` – the whole prototype (HTML/CSS/JS)
- `MLP-Recover_Proposal.pdf` – submission PDF
- `DEMO_GUIDE.md` – what to show judges
- `mkpdf2.py` – script that regenerates the PDF (needs reportlab, Pillow; screenshots in `shots/`)
