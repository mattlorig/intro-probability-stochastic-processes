# Contributing

Thank you for helping improve these notes! Contributions of all sizes are welcome, from fixing a typo to adding a new section or exercise.

## Reporting an error or suggesting a change

Open an [issue](https://github.com/mattlorig/intro-probability-stochastic-processes/issues) and include:

- the version number (shown on the title page) and the chapter, section, or equation number;
- a short description of the problem or suggestion;
- if relevant, the corrected text or a proposed fix.

## Submitting a change

1. Fork this repository and create a branch for your change.
2. Edit `ProbStochProc.tex`. Please keep each pull request focused on one topic (e.g., "fix typos in Chapter 4" or "add exercise on Poisson processes").
3. Check that the file compiles without errors (`pdflatex ProbStochProc.tex`, run twice).
4. Open a pull request describing what you changed and why.

## Style guidelines

- **Rigor.** Definitions, theorems, propositions, lemmas and corollaries should be rigorously true. Proofs may be sketched or use simplifying assumptions, provided this is stated (e.g., `\begin{proof}[Sketch of proof]`).
- **Applied focus.** Favor clear explanations, examples and intuition over technical generality.
- **Notation and macros.** Use the macros defined in the preamble (e.g., `\Pb`, `\Eb`, `\dd`) rather than defining new ones where possible.
- **Labels.** Give new theorems, equations and exercises descriptive labels (e.g., `\label{thm:ito.formula}`, `\label{exer:7.9}`), and make sure they don't duplicate existing labels.
- **Exercises.** New exercises should come with a solution in the Solutions chapter.
- **Sources.** If material is adapted from another source, cite it, and make sure its use is compatible with the CC BY-SA 4.0 license. Do not copy text verbatim from copyrighted books.
- **Work in progress.** Material that is incomplete or needs checking can be marked in blue with `\blu{...}`.

## License

By contributing, you agree that your contributions will be licensed under the [CC BY-SA 4.0 License](https://creativecommons.org/licenses/by-sa/4.0/), the same license that covers the rest of the notes.
