# VR Integration Control Room

A WebXR page with two VR games for the ERP / Lime CRM integration workshop:

1. **"Who owns the data?"** – warm-up game.
2. **"Integration Control Room"** – the main game.

Open it in the Meta Quest browser and press **Enter VR**.

**Live link:** https://selweshype.github.io/IntegrationControlRoom/

## Shift length

The shift lasts 6 minutes by default. Add `?time=` with a number of seconds to change it.
For an 8-minute shift:

https://selweshype.github.io/IntegrationControlRoom/?time=480

## Notes

- `index.html` is self-contained (no external dependencies), so it keeps working offline once it has loaded.
- Game content (warm-up items, error rules, field mapping, conflict fields) lives in the JSON inside `<script id="data" type="application/json">`. The printed team manual depends on these rules.
