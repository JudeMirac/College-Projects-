# College analytics projects: Codex working instructions

## Scope

Maintain the independent coursework notebooks while preserving assignment context and reproducibility.

The user's current request takes precedence. This package authorizes no project changes by itself. Preserve the existing analytical intent and do not invent metrics, source data, successful tests, or model results.

## Repository baseline

Repository: JudeMirac/College-Projects-
Inspected branch: main
Inspected commit: 9ee133f14972486f85096cb0ecf955091e7633b3
This is a remote source assessment, not proof of a clean local worktree. Recheck branch, current HEAD, existing changes, and any nested instructions before implementation.

- Root notebooks: Linear Regression Assignment.ipynb, PCA Assignment.ipynb, SVM Assignment.ipynb, and NLP-Asignmemt.ipynb.
- README describes pandas, NumPy, scikit-learn, plotting libraries, and NLTK; no dependency manifest was found.

## Multi-agent workflow

Keep the lead focused on planning, integration, ambiguous decisions, and final review.

- coursework_explorer: Read-only repository mapping, dependency tracing, data-flow inspection, and targeted investigation. Model: gpt-6-luna; reasoning: high.
- coursework_worker: Small, clearly scoped code, notebook, documentation, and configuration changes. Model: gpt-6-luna; reasoning: high.
- coursework_engineer: Complex implementation, cross-file debugging, data-pipeline failures, and integration decisions. Model: gpt-6.1-sol; reasoning: medium.
- coursework_reviewer: Independent review for correctness, regressions, data leakage, reproducibility, and missed requirements. Model: gpt-6.1-sol; reasoning: medium.

Use one or two specialists for ordinary work. Delegate only bounded work with a clear output. Parallelize independent tasks and never give concurrent writers overlapping files. Ask the engineer to handle hard failures rather than repeatedly widening a routine worker's scope. Use independent review for meaningful analytical or functional changes. Do tiny tasks directly.

Read the relevant source before editing. Preserve unrelated user changes and established names. Review the final diff, perform proportionate verification, fix introduced regressions, and report changed paths, checks actually run, and limitations. Do not run expensive training, notebook execution, dataset regeneration, downloads, or external services merely for package validation.

## Project-specific rules

- Treat assignments as independent projects; do not impose one combined pipeline or shared dataset.
- Preserve assignment questions, explanatory work, citations, and evidence of the student's analysis.
- Retain existing filenames unless renaming is requested; keep the README aligned with the actual NLP-Asignmemt.ipynb filename.
- Do not invent missing datasets, successful grades, results, or execution claims.
- Review train/test separation, scaling and dimensionality-reduction fit boundaries as applicable, and avoid output churn.

## Verification

- Parse the affected notebook JSON and validate with nbformat if available without executing cells.
- Inspect imports and relative data paths for the selected assignment before proposing execution.
- No automated tests or complete dependency manifest were identified; do not fabricate an install or test command.
- Run only the requested notebook when its inputs/dependencies are available and execution is authorized.

Do not install dependencies or regenerate artifacts for documentation-only edits. For code changes, choose the smallest relevant check and distinguish syntax validation from runtime or analytical validation. Preserve train/test boundaries where applicable. Stop broadening checks once the relevant risks are covered.

## Assessment limitations

- Large notebook outputs and assignment datasets were not audited or executed.

Do not infer a deployment from another repository. Major redesign, destructive data changes, repository visibility changes, and deployment-architecture changes require explicit user authorization unless already part of the current request.
