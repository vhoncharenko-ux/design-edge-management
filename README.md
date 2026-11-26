# Edge management UI — prototype

Interactive HTML prototype of the redesigned **Edges** page in ThingsBoard (Edge management → Edges).
Goal: bring the new Edges screens to the platform's visual language without changing functionality.

- Single self-contained file: `index.html` (platform CSS compiled from `thingsboard/thingsboard` master, Angular Material 20, M2 theme).
- Open it locally in a browser, or via GitHub Pages once it is enabled (Settings → Pages → Deploy from branch `main`, folder `/`).
- The dock at the bottom switches variants and modes (Views: Separate / Combined, Open as: Side panel / Full screen, Dashboard, scenario).

## Edges list (24.11)
- Responsive: columns hide by priority as the table gets narrower — Managed by (<1400) → Version (<1200) → traffic numbers, sparklines stay (<1050) → Edge type (<900) → Uplink / Downlink (<760); then horizontal scroll. Name, Status, Network always visible.
- `Lagging only (N)` switch in the toolbar: shows active edges with lag in uplink or downlink.

Prototype only — not production code.
