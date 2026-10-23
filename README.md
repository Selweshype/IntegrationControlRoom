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

## Seated or standing

The game is made to be played seated (a swivel chair is best: the modules are on the left, front and right).
The page measures the player's eye height at the start of every screen and moves the content to match,
so it also works when players swap the headset. Hold the Meta button on the right controller to re-centre.

To preview the seated view on a laptop: https://selweshype.github.io/IntegrationControlRoom/?eye=1.2

## Notes

- `index.html` is self-contained (no external dependencies), so it keeps working offline once it has loaded.
- Game content (warm-up items, error rules, field mapping, conflict fields) lives in the JSON inside `<script id="data" type="application/json">`. The printed team manual depends on these rules.
