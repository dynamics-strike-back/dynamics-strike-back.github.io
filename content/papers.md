+++
title = "Papers"
+++

# Call for Papers

Parallel hardware has reshaped machine learning, motivating techniques that parallelize computations once assumed to be "inherently sequential." Researchers working on recurrent neural networks, diffusion models, Markov chain Monte Carlo, and more have independently converged on similar algorithmic breakthroughs---unlocking order-of-magnitude speedups on modern accelerators---yet best practices remain siloed across these communities. This workshop brings researchers together for concrete discussions about shared techniques, open problems, and future breakthroughs.

## Topics of interest

Concrete themes of interest include:

**Deep sequence modeling**
- Parallelizing nonlinear RNNs via fixed-point iteration or other techniques
- Block-parallel and chunked recurrent architectures
- Hardware-efficient kernels and implementations on modern accelerators

**Deep generative modeling**
- Parallel sampling from diffusion models (consistency models, distillation, parallel ODE/SDE solvers)
- Speculative and parallel decoding for autoregressive models
- Parallel-in-time methods for flow- and score-based generative models

**Classical probabilistic modeling**
- Parallel Kalman filtering and smoothing
- Parallel particle filters and sequential Monte Carlo
- Parallel Markov chain Monte Carlo

**Theory and limits of parallelizability**
- Computational complexity of Transformers, SSMs, and recurrent architectures
- Tradeoffs between parallelizability and expressivity 
- Hardness results and lower bounds for sequential tasks
- Toward a rigorous definition of "inherently sequential"

**Cross-cutting**
- Cross-pollination between scientific computing (parareal, MGRIT, multigrid-in-time) and ML
- Profiling, benchmarking, and best practices for parallel-in-time methods on GPUs/TPUs

## Scope

**In scope:** Works that reduce or circumvent sequential dependencies over sequence length or time --- via fixed-point reformulations, parallel scan, block-parallel structures, implicit layers, reordered updates, or algorithmic and architectural innovation --- yielding measurable speedups on modern accelerators. Also in scope: theoretical or empirical results on the limits of parallelizability.

**Out of scope:** Works that solely increase data or model parallelism without reducing sequential dependency.

## Submission format

- **Length:** 4 pages maximum, excluding references and appendices.
- **Style:** NeurIPS 2026 LaTeX style (template will be linked alongside the submission portal).
- **Review:** Double-blind; please anonymize submissions.
- **Non-archival:** The workshop is non-archival. Accepted papers will be posted on OpenReview for community visibility, but authors retain the right to publish their work elsewhere. Previously published work is not eligible.

## AI policy

AI-written submissions and AI-generated reviews are **not** accepted. AI assistance (e.g., for editing or coding support) is permitted, in line with standard guidelines used at MIT and NYU. Authors are responsible for the content of their submissions.

## Important dates

- **Submission deadline:** August 29, 2026 (AOE)
- **Reviewer bidding:** August 30 – September 4, 2026
- **Review deadline:** September 22, 2026 (AOE)
- **Author notification:** September 29, 2026 (AOE)
- **Workshop:** December 11–13, 2026 (co-located with NeurIPS 2026)

## Submission portal

Submissions will be handled through OpenReview. The submission link will be posted here closer to the deadline.

## Contact

For any questions, please contact the organizers at [xavier18@stanford.edu](mailto:xavier18@stanford.edu) or [scott.linderman@stanford.edu](mailto:scott.linderman@stanford.edu).
