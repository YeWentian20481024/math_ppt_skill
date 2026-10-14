---
name: math-research-presentation
description: Create, revise, or review mathematical research talks with progressive arguments, explicit assumptions, readable derivations, and interpretable numerical evidence. Use for slide structure, proof sketches, experiment explanations, annotated revisions, and rehearsal. Preserve the requested Beamer, PowerPoint, or other editable format.
---

# Mathematical Research Presentations

Make the mathematical dependencies and evidence visible. A polished layout cannot repair a missing assumption, an unexplained method choice, or an unsupported conclusion.

This skill governs scientific exposition. Use the available document tools for the requested format; it does not require another named skill, a particular editor, or a service. Do not infer a conversion to PowerPoint solely from a colloquial request for “PPT.” Preserve the existing working format unless conversion is requested.

## Start from the talk, not a template

Infer the audience, duration, purpose, and revision scope from the request and supplied materials. Ask only about consequential missing information; otherwise state a reasonable assumption and proceed. Do not impose a mandatory interview.

Identify the few conclusions the audience should retain and the prerequisites needed to understand them. Allocate time to conceptual difficulty rather than a universal minutes-per-slide rule. Keep a shorter route through the talk, with dispensable detail in backup pages. A derivation may need more speaking time than several figures.

Honor the requested style, language, notation, and speaker-note conventions. Do not invent an author or institution. Font size, aspect ratio, overlays, section names, navigation dots, and reference-page counts are choices, not universal mathematical standards.

## Build the dependency chain

When creating or restructuring a talk, keep a compact logic map:

| Content identity | Question answered | Mathematics or evidence | Supported conclusion | Next unresolved issue |
|---|---|---|---|---|

Use a progression appropriate to the subject. Problem → obstacle → mechanism → method → discriminating evidence is useful for numerical research; a theorem talk may instead follow a motivating example → conjecture → obstruction → lemma → theorem. Do not force either outline onto every talk.

- Introduce a concept where it becomes necessary, with its actual mathematical definition.
- Separate an overview of design choices, an explanation of coupled controls, and the executable algorithm. Avoid repeated flowcharts doing the same job.
- For nested algorithms, show the outer update, inner calls, returned quantities, and feedback.
- Pair a construction with its immediate consequence: a mesh with its refinement pattern, a coordinate change with its transformed geometry.
- Separate the core method, an experiment explaining its mechanism, and implementation troubleshooting. Keep an implementation detail in the main argument only when it changes the method or the interpretation of evidence.
- Explain transitions through an unresolved question or consequence. Presenter cues can live in notes without filling the audience slides with repeated summaries.

Describe the existing page separately from your proposed improvement. A request for a logic review alone does not authorize restructuring or deletion. Once restructuring is requested, carry out justified choices without asking again for routine decisions.

## Explain and check the mathematics

Introduce domains, symbols, normalization, dimensions, and prerequisites before they affect a displayed formula. Expand an expectation, operator, or objective into its concrete mathematical content before relying on shorthand. Preserve the equalities that bridge two concepts; prose is not a substitute for a missing derivation.

For theorem and asymptotic talks, read [mathematical argument](references/mathematical-argument.md). For computational talks, also read [numerical evidence](references/numerical-evidence.md). Use only the references relevant to the task.

Distinguish proved statements, formal derivations, observed trends, and conjectures. State the assumptions needed for a conclusion beside it. For an asymptotic claim, identify the limiting variable, quantities held fixed, and dependencies of the hidden constants. A fitted slope does not prove a theorem or a uniform bound.

Check consequential formulas against the source: signs, dimensions, normalization, boundary conditions, quantifiers, and limiting cases. Identify missing evidence rather than silently repairing the underlying research. Slide revision does not authorize new scientific runs or changes to experimental parameters.

## Show evidence that can be interpreted

Before the first result of an experiment, show its mathematical problem and relevant conditions on audience slides. A case nickname or oral explanation alone is insufficient. Reuse a common setup for related cases. Put configuration details that do not affect interpretation in backup or companion material.

Choose plots for the question they answer. Define axes, units, norms, normalization, and reference solutions. Use an error plot, inset, or table when overlapping solution curves hide the difference. Distinguish schematic illustrations, exact toy calculations, and measured research results.

Report unsuccessful runs, unfavorable comparisons, and the scope of positive findings. Put a qualification beside the result whose interpretation it changes. End with claims traceable to displayed evidence, not a broader claim suggested only by the title.

## Revise the correct artifact

For annotated decks, read the actual saved PDF and identify its matching editable source. Preserve the annotated original. Track content by a stable frame label or identity, not only by page numbers after insertions. Distinguish deletion, replacement, relocation, and requests for explanation.

Do not restore deleted prose under a new heading. If the user also requests an explanation in chat, deliver it there; slide or note edits alone do not satisfy that request. Do not assume an old generator reflects the newest revision.

For annotation, navigation, and layout work, read [revision and delivery](references/revision-and-delivery.md). A global theme change requires a full rendering review because header height and margins can change every page.

## Rehearse the reasoning and verify the output

Walk through the main route as if the audience had not participated in the research. At each first use, check that a symbol or premise is already available. Before an experiment result, check that the audience knows what is being tested. Read the final claims backward to locate their support. Remove repetition without removing the premises of later pages.

Estimate a speaking-time budget and label it as an estimate unless an actual timed rehearsal occurred. Anticipate questions about assumptions, competing methods, failure cases, and generality; use backup pages for substantive answers rather than arbitrary page quotas.

Compile or export, inspect the rendered pages, and verify changed references and links. Report what was actually checked, what remains uncertain, and where the editable source and audience version are saved. If tooling is unavailable, preserve the source and state the limitation; do not claim successful rendering.

## Maintain and share without carrying private context

Learn only from explicit durable preferences or demonstrated failures. Keep general rules separate from personal defaults, project facts, and temporary revision instructions. Past authorization is not portable permission for future work. Do not embed conversation transcripts, local paths, identities, credentials, or unpublished numerical records in a reusable public skill.

For public examples, create independent mathematical examples or fully inspect redacted artifacts, including metadata, notes, comments, links, attachments, and tracked history. Replacing visible names or a few formulas is not sufficient anonymization.

When demonstrating this skill, show a presentation decision: the original page or sequence, the revised version using the same substantive content, the edit, and why it improves comprehension. A standalone explanation of an interesting scientific problem is not by itself a demonstration of slide improvement. See the independent [example package](examples/README.md) for visible before/after comparisons and editable Beamer source.
