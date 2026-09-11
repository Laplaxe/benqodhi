# Table 4 — Benchmarking methods and the repository

> **This file is a worked EXAMPLE.** It shows the level of detail expected from a
> note taker. The content below is illustrative, not an agreed workshop position.
> Replace it with the table's real conclusions.

- **Date:** 11 September 2026
- **Note takers:** A. Example, B. Example
- **Rapporteur:** C. Example

## Answers to the table's questions

### Q1 — Comparing approaches

How should standard classical, AI-based, hybrid and quantum approaches be compared
on the same problems?

Comparison: classical and ML. Problems related to HPC infrastructure. E.g. interconnector has an effect on the benchmarking.

AI based algorithm: training time should be taken into account. recording separately training and inference.

Origin of the data? If it is quantum you should work with the quantum computers 

### Q2 — What to measure

Which measures matter most: solution quality, running time, efficiency, energy
consumption, resources used, reproducibility?

Things you want: time, cost, accuracy.

Cost: related to architecture, but this is not enstablished a priori.

Benchmark of the checklist.

Example answer:

- **solution quality** achieved, including objective value and gap to best known;
- **time to reach the target**, using wall-clock time and reporting the hardware;
- **resources used**, including cores, GPUs, QPU shots and, where available, energy;
- **number of runs and success rate**, since heuristic and quantum methods are often
  stochastic;
- **reproducibility information**, including solver version, parameters and seed.

### Q3 — Online and credible

What is the simplest route to put benchmark material online, and who should
maintain or review it?

Example answer: start with a **public repository** with, per problem, a clear
description, instance files or data links, at least one baseline, the metrics, a
license and a named owner. The smallest first release could be one problem class
with one curated instance set, one classical baseline and one checker, published
with a fixed date and an owner.

## Conclusions for the recap

- **Strongest conclusions:** a fair comparison needs fixed targets, honest reporting
  and strong classical baselines; "online" should start small and versioned, not
  comprehensive.
- **Main infrastructure need:** a public, versioned repository with per-problem
  baselines and automatic checkers.
- **Why it matters:** without agreed reporting and strong baselines, claims of
  progress cannot be trusted or reproduced.
- **Most important missing piece:** owners for the first release and an agreed
  minimum reporting format.
- **Next action:** commit to one problem class as a first release, with a named owner
  and a target date.
- **Transversal next-step advice:** start with a minimal useful repository and grow
  it through clear review, credit and maintenance roles.

## Transversal reflection

Given the three pillars — infrastructure, community and governance — what advice,
suggestions or lessons from experience would you give for the next steps after the
workshop, so that BENQODHI can become a living benchmark repository and produce
useful final outputs?
