# An Introduction to Applied Probability and Stochastic Processes
### Open Lecture Notes

**Matthew Lorig** — Department of Applied Mathematics, University of Washington

These are open, forkable lecture notes giving a broad introduction to measure-theoretic probability and stochastic processes, with a focus on applications. They were written for a two-quarter course for first-year PhD students in applied mathematics at the University of Washington. They should also be useful to graduate students in statistics, engineering, economics and finance, and to anyone studying the subject on their own.

Mathematical statements (definitions, theorems, propositions, lemmas and corollaries) are intended to be rigorously true. Proofs are sometimes sketched or use simplifying assumptions, and the notes say so where this is the case.

## Download

The compiled PDF of each version is attached to the [Releases](https://github.com/mattlorig/intro-probability-stochastic-processes/releases) page.

## Contents

1. Review of probability
2. Information and conditioning
3. Generating and characteristic functions
4. Discrete-time Markov chains
5. Continuous-time Markov chains
6. Convergence of random variables
7. Brownian motion
8. Stochastic calculus
9. SDEs and PDEs
10. Jump diffusions
11. Stochastic control
12. Optimal stopping
13. Monte Carlo methods

Most chapters end with exercises, and solutions are collected in a final chapter.

## Building from source

The notes are a single self-contained LaTeX file (the bibliography and figures are included in it). Compile with

    pdflatex ProbStochProc.tex
    pdflatex ProbStochProc.tex

The second run resolves cross-references. Any recent TeX Live or MiKTeX installation should have the required packages.

## Contributing

Corrections, improvements and new material are welcome. Please open an [issue](https://github.com/mattlorig/intro-probability-stochastic-processes/issues) to report an error or suggest a change, or fork the repository and submit a pull request. Text shown in blue in the PDF marks material that is still under development, and is a good place to start.

## How to cite

An arXiv identifier and DOI will be added here shortly. In the meantime, please cite as:

    @misc{lorig-probability-notes,
      author       = {Lorig, Matthew},
      title        = {An Introduction to Applied Probability and Stochastic Processes: Open Lecture Notes},
      year         = {2026},
      howpublished = {\url{https://github.com/mattlorig/intro-probability-stochastic-processes}},
      note         = {Version 1.70}
    }

## License

These notes are licensed under the [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/) (CC BY-SA 4.0). You may share and adapt the material for any purpose, provided you give appropriate credit and distribute your contributions under the same license.
