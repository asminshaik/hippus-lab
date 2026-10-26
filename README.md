# Hippus Lab

An interactive simulation that asks whether Algebra 2 functions can tell a calm pupil from a stressed one, using real eye-tracking recordings from 35 people.

**Open it:** https://asminshaik.github.io/hippus-lab/

## Research question

Can non-linear algebraic modeling, specifically sinusoidal wave equations and quadratic vertex analysis, mathematically differentiate pupil dynamics in healthy baseline subjects versus subjects under acute cognitive stress, using open-source clinical datasets?

- **Independent variable:** cognitive state (baseline vs. acute stress)
- **Dependent variables:** hippus wave amplitude A, wave constant B (frequency), and quadratic vertex curvature a during constriction
- **Hypothesis:** under acute stress, pupil oscillations show higher amplitude and higher frequency, seen as a significant rise in the wave constant B

## What's on the site

- **Simulate:** an animated eye driven by each participant's recorded pupil, with the live fit of `y = A·sin(B(t − C)) + D` and the constriction parabolas `y = a(t − h)² + k`
- **Results:** the conclusion, paired t-tests with effect sizes and 95% confidence intervals, a stress-onset average, and resilience vs. stress response
- **My eye:** repeat the experiment on yourself with a mini version of the study's NASA MATB-II stress task, using a phone or this device's camera. Videos are analyzed in the browser and never uploaded.
- **Data & method** and a plain-language **Glossary**

Everything runs in the browser. There is no server and no tracking.

## Data

Pupil recordings come from the PhysioNet dataset by Roy & Nuamah (2026), shared under the Open Database License. See [DATA-LICENSE.md](DATA-LICENSE.md) for attribution, what was changed, and the license of `docs/data.json`.

This project is an educational experiment, not a medical test.

## Author

Asmin Shaik, 2026
