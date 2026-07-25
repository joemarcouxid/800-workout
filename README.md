# Lane 1 — Sprint Training

A single-page phone app for a high-school sprinter. Enter your next competition date and it shows **this week's training** — track work and gym/adjunct work, day by day — automatically adjusting to how far out the meet is.

It's the app version of the Peak Performance Planner spreadsheet: same phases, same session logic.

## How it works

The plan uses a short-to-long sprint model. As your meet gets closer, the training shifts:

| Weeks out | Block | Focus |
|-----------|-------|-------|
| 20+ | General Prep I | Off-season base: tempo, strength, drills. Very little fast running. |
| 12–19 | General Prep II | Base + max velocity introduced. Strength goes heavier. |
| 6–11 | Specific Prep | Speed-endurance work appears, tempo drops. |
| 3–5 | Early Comp / Pre-Comp | Race sharpening, speed-dominant. |
| 1–2 | Main Competition | Compete. Low volume, meet is the hard effort. |
| 0 | Championship / Peak | Taper and peak. |

Each day card shows the **track** session and the **gym/adjunct** session. Orange = hard day, green = easy day, gold = race. Keep hard days 48h apart.

## Put it online (free, ~2 minutes)

1. Create a new GitHub repository.
2. Upload `index.html` (and this README).
3. Go to **Settings → Pages**, set **Source** to your `main` branch, `/root`, and save.
4. GitHub gives you a link like `https://yourname.github.io/your-repo/` — open it on your phone and add it to your home screen.

No build step, no dependencies, no server. It's one HTML file.

## Note

This follows one coaching model (short-to-long, tempo-heavy base). It's a solid, defensible starting point — not the only valid approach. Adjust with your coach based on how you actually train and recover.
