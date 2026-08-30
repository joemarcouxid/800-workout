# Titus — Speed-Type 800

A single-page phone app for a high-school 800 m runner. Enter your next meet date and it shows the **next seven days** of training, day by day, adjusting to how far out the meet is. Every target time is calculated from your own PRs, so the plan updates itself as you improve.

## Who it's built for

A **speed-type 800 runner**: sprint speed well ahead of the aerobic engine (24.91 / 53.78 / 2:04.23 against a 5:04 mile). The plan protects the speed and builds the engine, not the other way round. The classification comes from Sandford et al.'s speed / hybrid / endurance subgroups for 800 m runners.

## What it does

**Works out your paces.** Enter five times once (200, 400, 800, mile, goal 800). Easy, steady, comfortably-hard and mile pace are derived from the mile PR; race and goal paces from the 800; the fast 200s from the 400. Every session then prints real target times rather than percentages.

**Rearranges itself.** Each day is a dropdown; today opens automatically. If you end up doing a different day's session today, open it and tap **"I did this one today instead."** It moves onto today and the rest of the week rebuilds around it — hard days stay apart, the day off stays in, the race stays on the actual meet date, and the day-before-the-meet session only ever lands the day before the meet. If two hard days end up next to each other anyway, the day is flagged.

**Matches your equipment.** Set *Weights* to full gym, home gym, or nothing, and *Hills* to yes or no. Every strength and hill session rewrites itself: barbell work becomes dumbbell work becomes bodyweight work; hill sprints become flat grass sprints, stairs, or treadmill incline.

**Explains itself.** Every session has a *How it should feel* line and a *Why you are doing it* line with a source tag. No coaching shorthand.

## The blocks

| Weeks out | Block | Focus |
|-----------|-------|-------|
| 20+ | Build The Engine | Almost all aerobic. Speed kept alive with hill sprints and strides only. |
| 12–19 | Engine Plus Speed | Adds one mile-pace session. Lifting goes heavier. |
| 6–11 | Turn Speed Into 800s | Goal-pace running and top-speed work appear. |
| 3–5 | Sharpen | Broken 800s and race modelling. Volume drops. |
| 1–2 | Race Weeks | One quality day; the meet is the second hard effort. |
| 0 | Meet Week | Taper. Nothing new, nothing heavy, nothing long. |

Colour: orange = speed, blue = engine, green = easy, gold = race, grey = rest.

## Where it comes from

Full citations are in the app under *Where This Plan Comes From*. The main sources:

- **Sandford, Kilding, Ross & Laursen (2019)**, *Sports Medicine* 49:843–852 — maximum sprint speed and anaerobic speed reserve differentiate elite 800 m runners; the speed/hybrid/endurance subgroups.
- **Sandford & Stellingwerff (2019)**, "Question Your Categories" — identical 800 times, very different physiologies; train the individual.
- **Haugen, Sandbakk, Enoksen, Seiler & Tønnessen (2021)**, "Crossing the Golden Training Divide," *Sports Medicine* 51:1835–1854 — how world-class 800/1500 runners actually train.
- **Haugen, Sandbakk, Seiler & Tønnessen (2022)**, *Sports Medicine Open* 8:46 — ~80%+ of elite volume at low intensity.
- **Blagrove, Howatson & Hayes (2018)**, *Sports Medicine* 48:1117–1149, plus **Blagrove et al. (2018)**, *MSSE* 50:1224–1232 on post-pubertal adolescent runners — strength training for distance runners.
- **Llanos-Lagos et al. (2024)**, *Sports Medicine* — high-load and combined strength methods improve running economy.
- **Spencer & Gastin (2001)** — energy system contributions: ~43% aerobic at 400 m, ~66% at 800 m, ~84% at 1500 m.
- **Youth Running Consensus Statement (2021)**, *BJSM* — at least one rest day per week, planned breaks, adequate fuelling, training around growth.
- **Coaching practice** — Lydiard and Peter Coe periodisation; Charlie Francis and ALTIS (Pfaff, McMillan, Mackey) for year-round speed maintenance.

## Put it online (free, ~2 minutes)

1. Create a new GitHub repository.
2. Upload `index.html` and this README.
3. **Settings → Pages**, set **Source** to your `main` branch, `/root`, save.
4. Open the `github.io` link on your phone and add it to your home screen.

One HTML file. No build step, no dependencies, no server. Times, equipment settings and meet date save in the browser, so you enter them once.

## Note

This is one defensible model for one athlete, not the only valid approach, and not a substitute for your actual coach — who can see you run. Nothing here should be done through pain.
