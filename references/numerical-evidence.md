# Numerical experiments as evidence

## Define the problem before ranking methods

Separate component tests, complete-solver tests, and application tests. Identify the extra claim tested at each level. A component improvement does not establish an end-to-end speedup or application accuracy.

Show the function, integral, optimization problem, or governing equation. For a PDE show the domain, initial and boundary conditions, and coefficients necessary to define the case. Identify the model, reference, varying factors, controlled factors, and relevant discretization. A common setup page can serve multiple result pages; a catalog of every software option is not required.

If two factors vary together, describe the tested family. Do not attribute all changes to just one factor. Compare against the actual implemented baseline, not the name or guarantees of a broader literature method.

## Keep distinct quantities distinct

- Internal stopping and refinement criteria describe algorithm decisions; independent errors describe results.
- Implementation checks test whether code performs the intended operations. An error threshold chosen for a study is not automatically a code-correctness criterion.
- Parameter error, residual, objective error, flux error, and final solution error need separate definitions and a mathematical argument before one can replace another.
- Agreement between two methods measures consistency; accuracy requires an appropriate reference.
- A high-resolution reference can still contain model, discretization, or solver error. Identify which error it controls and which it retains.
- Regularization changes the target. Report discrepancy from the original target as well as the regularized solver status.

Separate continuous sensitivity, approximation or integration error, floating-point assembly and solve error, optimization control, and outer discretization. Report observed effects separately from explanations that still need a controlled test.

## Compare cost and robustness honestly

Specify the actual error range for cost comparisons. Equal nominal tolerances or nominal budgets do not establish equal accuracy or resources. Distinguish node counts, new function evaluations, repeated visits, matrix operations, and wall-clock time.

Keep failures, timeouts, partial progress, and one-sided successes visible. Do not compute a same-task speedup between a completed run and a stopped partial run. For time-dependent problems compare solutions at the same physical time, with an independent reference and consistent normalization.

Report repetitions and the aggregation rule where timings support a performance claim. Do not imply statistical significance from a single exploratory run. If a correction changes results, label old and new versions and do not combine them into one ranking. A successful replay of one step does not establish a repaired full simulation.

## Make plots discriminating

Use the physical solution plot to show behavior and a separate error view when the difference is too small to see. Do not distort axes to imply practical importance; explain magnification. Match scales and colors across comparisons. Provide labels or line styles in addition to color.

For convergence plots, state what was refined, what stayed fixed, how error was measured, and the reference slope. Distinguish an asymptotic trend from pre-asymptotic or roundoff-dominated data. If the data cannot identify a mechanism, state the missing measurement and the smallest discriminating comparison; do not invent results to complete the story.
