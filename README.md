# FIDE Digital Platform — prototype

Clickable prototype of the three parts of the FIDE Digital Platform:

- **FIDE Core** — the internal system of FIDE. Switch roles in the top bar: Secretariat, Councillor (Africa), Commission chair, Grants coordinator, Management, Treasurer, Accounting.
- **FIDE Connect** — the platform for organisations. People sign in with their personal FIDE ChessID and choose the organisation they act for by its FIDE Org ID; for national federations the Org ID is their FIDE code (for example `KSB`).
- **FIDE ChessID** — the identity of individual people: players, coaches, arbiters, parents.

The PDC development-grant process works end to end:

1. Application (project, budget, targets)
2. Revision — FIDE asks for more information, the federation answers
3. Application check (window, project limit, dues, overdue reports, sanctions, budget)
4. Councillor evaluation
5. Commission evaluation (amount and special conditions)
6. Approval by Management and Treasurer in parallel
7. Decision and agreement — conditions, termination, penalties, sanctions; e-signature; project code issued
8. Bank details and payment of tranche 1
9. Final report and publication — ChessID figures (growth of the federation's ChessID base, new ChessIDs via the project code, women and girls, first FIDE ratings) are filled in automatically; the federation adds participants, coaches, schools, media reach and spending; targets are compared with results

Other modules (membership and dues, events, ratings and titles, finance) are shown as planned phases.

The guide bar under the header walks through the demo in 15 steps. "Reset demo" restores the starting data.

All organisations, people and figures are mock data. The demo date is fixed at 14 April 2027; the report step skips ahead to the end of the project.

## Run

Single static file, no build step. Open `index.html` in a browser, or enable GitHub Pages for this repository (Settings → Pages → Deploy from a branch → `main`, `/ (root)`).
