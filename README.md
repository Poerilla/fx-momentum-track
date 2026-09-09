# Strategy Track Record (public)

Static GitHub Pages site with abstracted strategy performance.
No instruments, session names, or trade entries/exits.

Tabs (see `docs/data/catalog.json`):

- **FX Momentum**
- **FX Breakout**
- **Index Breakout**

## Local preview

```bash
cd docs && python3 -m http.server 8765
# open http://127.0.0.1:8765/
```

Data under `docs/data/` is sanitized JSON only (no symbols).
Pages source: `/docs`.
