# Mathematical argument and proof sketches

## State what is being claimed

For a theorem, show the objects, hypotheses, quantifiers, conclusion, and scope. Keep assumptions that make the conclusion true on the main slide; move technical variants to backup only when they are not needed to interpret that conclusion.

Say whether a result is standard background, a cited result, a new result in the supplied research, or a conjecture. Verify bibliographic claims from their sources. Do not fabricate priority or novelty from the absence of a citation in the supplied notes.

For a scaling statement such as E(h) = O(h^p), identify the norm, the limit h → 0, and which parameters may enter the constant. Distinguish a fixed-dimension statement from a bound uniform in dimension. If several parameters vary simultaneously, state the path through parameter space.

## Explain the proof's decisive step

Present the obstacle before the device that resolves it. A useful proof sketch gives:

1. The quantity or invariant that will be controlled.
2. The estimate or construction that changes the problem.
3. The step that closes the argument and the assumption it uses.

This is a decision guide, not a mandatory three-slide structure. If a sketch omits a nontrivial step, name the step rather than hiding it behind “clearly.” Preserve logical connectors and essential inequalities when shortening a proof. Distinguish sufficient conditions from necessary ones.

Use a toy case to explain a mechanism when it isolates the difficulty. Check whether symmetry, equal weights, diagonal structure, or a special boundary removes an obstacle present in the claimed general case. Explain exactly what the toy case does and does not establish.

## Targeted mathematical checks

- Are vectors, matrices, domains, and function spaces compatible in each key equation?
- Are gradients and adjoints taken in the stated inner product or coordinates?
- Are normalization, measure, and constants consistent across definitions and figures?
- Do differentiation, integration, and limit exchanges require an assumption that disappeared from the slide?
- Do endpoint cases and simple special cases agree with the claim?
- Does an equivalent reformulation remain equivalent after truncation, discretization, or regularization?

Check the formulas that carry the argument; do not claim this checklist constitutes a proof or a formal verification.

## Example: residual versus error

Let A = diag(1, epsilon), 0 < epsilon <= 1, and b = 0. For the approximation x = (0, 1)^T, the exact solution is x_star = 0 and the residual is r = Ax - b = (0, epsilon)^T. Thus ||r||_2 = epsilon but ||x - x_star||_2 = 1.

The implication is that an absolute residual alone does not certify small Euclidean solution error uniformly as epsilon → 0. It does not prove every ill-conditioned problem has large observed error. A slide should preserve that distinction.
