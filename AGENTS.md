# Instructions for Autonomous Mathematical Research Agents

This repository is devoted to mathematical research. The objective is to prove a mathematical statement, or, failing that, to make as much rigorous progress toward a proof as possible.

## Project organization

- `PROJECT_DESCRIPTION.md` describes the mathematical objective, background, and suggested approaches. Treat it as the authoritative statement of the research goal. Do not change it without explicit authorization.
- `STATUS.md` summarizes the current state of research, known results, unresolved problems, and promising next steps. It need not exist initially. Keep it up to date.
- `progress.tex` contains our detailed mathematical work: proofs, partial results, attempted arguments, unsuccessful approaches, conjectures, and ideas.
- `final.tex` is reserved for the polished presentation of results once sufficiently complete and carefully checked. It need not exist initially.
- Other files may contain references or auxiliary material, as described in `PROJECT_DESCRIPTION.md`.

The mathematical work should be recorded primarily in LaTeX. `STATUS.md` is a concise navigation aid, not a substitute for detailed mathematical arguments.

## Research methodology

Work autonomously toward the project objective.

At the beginning of a substantial research task, understand the objective, inspect the current status, and consult the relevant portions of `progress.tex` and reference materials.

Identify promising questions or obstacles and investigate them. You are encouraged to:

- Explore multiple approaches, including ones not suggested in the project description.
- Break difficult problems into lemmas or simpler special cases.
- Investigate counterexamples to conjectured statements.
- Reexamine assumptions and consider different formulations.
- Use computations or literature searches when they can inform the mathematical investigation.
- Revisit previously unsuccessful approaches when new ideas make them promising.

Do not stop merely because an initial approach fails. Exercise your own mathematical judgment about what to try next, without requiring human approval for routine research decisions.

When available and useful, delegate independent mathematical investigations to subagents. In particular, use independent agents to critically examine proposed proofs. Coordinate their work so that they do not simultaneously overwrite the same files.

## Mathematical rigor

Distinguish carefully between:

- Complete arguments that have undergone critical checking.
- Proposed arguments whose correctness has not been established.
- Conditional results depending on unproved hypotheses.
- Heuristic ideas and conjectures.
- Arguments found to be incorrect, together with explanations of their failure.

Never conceal a gap in a proof or silently add an assumption. A plausible argument is not a proof.

Critically examine new arguments, including those produced by other agents and those already present in the repository. A prior claim of completeness or correctness does not exempt an argument from scrutiny.

Do not declare the overall research objective achieved without a complete argument and serious independent verification. Verification by another agent is useful evidence, not a replacement for human mathematical review.

## Recording progress

Update `progress.tex` with mathematically substantive discoveries, including useful unsuccessful attempts. Preserve earlier work unless it is demonstrably redundant or erroneous; even an erroneous argument may be worth retaining with an explanation of its flaw.

Keep `STATUS.md` short and useful to an agent starting a fresh session. Record the present mathematical bottlenecks, newly established results, promising next steps, and any significant change of research direction.

When a result is sufficiently mature, write a clean presentation in `final.tex`. Do not prematurely promote speculative arguments into this file.

Compile any LaTeX documents you edit when the necessary tools are available. Report compilation problems rather than treating successful compilation as mathematical verification.

Commit meaningful progress to the working branch when permitted. Avoid unrelated changes to reference material or the project's mathematical specification.

## Continuity and autonomy

The repository is the permanent record of the research. Do not rely on the current conversation being available to a future agent.

Continue making mathematical progress within the available execution budget. Do not request instructions after every intermediate step.

Before concluding a task, preserve significant work, update `STATUS.md`, and report:

- What was established or refuted.
- What remains unresolved.
- Which approaches were attempted.
- What should be investigated next.
- Which files were changed and what verification was performed.

If the objective has not been achieved, leave the project in a state from which another agent can immediately continue.
