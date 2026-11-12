# Zambezi Cup

⛳ **Virtual golf leagues — real 18-hole courses, free in your browser.**

Two courses live on the rota — **Leopard Links** (bushveld) and **Cheetah Sands**
(sandveld & riverfront) — each with a deterministic daily pin sheet, per-hole and
continuous-course 3D views, and a Wordle-style scorecard built for sharing.

- 🏌️ **Play** → [zambezi.golf](https://www.zambezi.golf)
- 📓 **Devlog** → [zambezi.golf/devlog](https://www.zambezi.golf/devlog)
- 💼 **Hiring** → Game Engine Dev · Data/ML Engineer — [zambezi.golf/careers](https://www.zambezi.golf/careers)
- 🦋 **Posts** → [@zambezi.golf](https://bsky.app/profile/zambezi.golf)

## Open source

Small dependency-free TypeScript utilities lifted from the game, in
[**zambezi-utils**](https://github.com/Zambezigolf/zambezi-utils):

| file | what it is |
|---|---|
| [`seeded-shapes.ts`](https://github.com/Zambezigolf/zambezi-utils/blob/main/seeded-shapes.ts) | Deterministic seeded polygons & discs — irregular hazards/trees for procedural maps |
| [`postcard.ts`](https://github.com/Zambezigolf/zambezi-utils/blob/main/postcard.ts) | Render a branded share-card PNG in the browser (canvas → PNG → share sheet) |
| [`share-intents.ts`](https://github.com/Zambezigolf/zambezi-utils/blob/main/share-intents.ts) | Wordle-style emoji scorecard + social intent links (Bluesky, X, WhatsApp, FB, LinkedIn) |
| [`daily-pins.ts`](https://github.com/Zambezigolf/zambezi-utils/blob/main/daily-pins.ts) | Deterministic daily-selection helpers — everyone plays the same sheet today |

Built by **Namutitima Virtual Gaming**.
