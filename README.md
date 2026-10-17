# ThoughtSpot Operator prototype

Single-page Radiant Play prototype of the ThoughtSpot Operator (agentic side pane for the Developer tab).

- `index.html` is the whole prototype, self-contained except Google Fonts.
- Deploy on Coolify with the **Dockerfile** build pack, port **80**. Health check path: `/healthz`.
- To update: replace `index.html` with the latest `operator-handoff/prototype.html` from Radiant Play, commit, push. Coolify redeploys on push.
