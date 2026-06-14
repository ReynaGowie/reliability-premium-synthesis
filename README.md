# The Reliability Premium: Replication & Data

This repository is the central hub for **The Reliability Premium: Evidence for
Capacity-Constrained Models of Labor Productivity**. It holds the final
manuscript, figures, and tables.

The paper synthesizes four independent analyses spanning national economies,
individual time-use diaries, and physiological recordings. Each analysis was run
in its own specialized repository, and the code and data-access instructions live
there. The links below point to the repository that actually contains each
study's pipeline.

| Study | Paper section | What it tests | Code repository |
|---|---|---|---|
| **Study 1 — Macro Constraints** | §4.1 | Annual work hours vs. GDP per hour across countries | https://github.com/ReynaGowie/hours-vs-productivity-analysis |
| **Study 2 — Structural Time Use** | §4.2 | Structural Work Load (work + commute ÷ waking hours) and how little of it sleep explains | https://github.com/ReynaGowie/capacity-model-analysis |
| **Study 3 — Biological Buffers** | §4.3 | Sleep as a recovery buffer drawn down nonlinearly by work hours (244K ATUS diaries) | https://github.com/ReynaGowie/energy-productivity-analysis |
| **Study 4 — Physiological Signals** | §4.4 | Heart rate and HRV response to psychological vs. physical demand (WESAD, PhysioNet) | https://github.com/ReynaGowie/hrv-demand-analysis |

> **Note on repository names.** The two ATUS-based analyses are split across
> repos whose names don't line up with their roles: the *Structural Work Load*
> analysis (§4.2) lives in `capacity-model-analysis`, and the *sleep-buffer*
> regression (§4.3) lives in `energy-productivity-analysis`. The table above maps
> each study to the repository that contains its code, which is what to follow.

## Methods note

Country-level and biological-buffer (§4.3) estimates apply the relevant survey
sampling weights. The Structural Work Load figures in §4.2 are reported
**unweighted** over the active-worker sample, as a within-day allocation ratio.
See the manuscript's Methods section for full specifications.
