# Lane 1 — 800 Build

A single-page phone app for a high-school 800m runner. Enter your next meet date and it shows **this week's training** — running and gym work, day by day — automatically adjusting to how far out the meet is.

Every target time is calculated from your own PRs, so the plan updates itself when you improve.

## Who it's built for

A **speed-type 800 runner**: 400 speed well ahead of the aerobic side. The plan protects the speed and builds the engine, rather than the other way round. If that's not you, the phase blocks in `index.html` are plain JavaScript and easy to reweight.

## How it works

Enter your times once (200, 400, 800, mile, goal 800) and the app works out every pace zone from them:

| Zone | Where it comes from |
|------|--------------------|
| Easy / Steady | Mile PR |
| Threshold | Mile PR |
| Mile pace (aerobic power) | Mile PR |
| 800 + goal pace | 800 PR and your goal |
| 400 pace / flat out | 400 and 200 PRs |

Then the week is built from your meet date:

| Weeks out | Block | Focus |
|-----------|-------|-------|
| 20+ | Build The Engine | Almost all aerobic. Speed kept alive with hill sprints and strides only. |
| 12–19 | Engine + Speed | Aerobic emphasis plus one mile-pace session. Strength goes heavier. |
| 6–11 | Turn Speed Into 800s | Goal-pace running and max-speed work appear. Threshold stays. |
| 3–5 | Sharpen | Broken 800s, speed endurance, race modelling. Volume drops. |
| 1–2 | Race Weeks | One quality day, meet is the second hard effort. |
| 0 | Championship Week | Taper. Nothing new, nothing heavy, nothing long. |

Each day card has three parts: **Running**, **Gym / Extra**, and **How it should feel**. The last one is the important one — it's what tells you whether you ran the session correctly.

Colour tells you the day at a glance: orange = speed, blue = engine, green = easy, gold = race, grey = rest. Never put two orange or blue days back to back.

## Put it online (free, ~2 minutes)

1. Create a new GitHub repository.
2. Upload `index.html` (and this README).
3. Go to **Settings → Pages**, set **Source** to your `main` branch, `/root`, and save.
4. GitHub gives you a link like `https://yourname.github.io/your-repo/` — open it on your phone and add it to your home screen.

No build step, no dependencies, no server. It's one HTML file. Your times and meet date save in the browser, so you only enter them once.

## Note

This follows one coaching model: build the aerobic system hard while protecting sprint speed, with one engine session and one speed session most weeks, and one complete rest day. It's a defensible starting point for a 15-year-old — not the only valid approach, and not a substitute for your actual coach. Nothing here should be run through pain.
