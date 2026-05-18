+++
title = "Workshop on Parallelizing \"Inherently Sequential\" Computation"
+++

The rise of massively parallel hardware has transformed AI and ML, yet many important models---including recurrent neural networks (RNNs), denoising diffusion models, and Markov chain Monte Carlo (MCMC)---were long believed to be "inherently sequential." Remarkably, researchers across different fields have independently converged on similar algorithmic breakthroughs to parallelize these processes, unlocking order-of-magnitude speedups on GPUs. Application domains of these parallel-in-time algorithms include:

- **Deep sequence modeling**, including linear attention, deep state space models (SSMs), and the parallelization of nonlinear recurrent neural networks (RNNs).
- **Deep generative modeling**, including parallelizing the sampling of diffusion models and structured variational autoencoders.
- **Classical probabilistic modeling**, including parallelizing Kalman filtering and smoothing, as well as Markov chain Monte Carlo (MCMC).

Yet because these communities rarely speak the same language, best practices remain siloed, and the full potential of these techniques is far from realized. This workshop breaks down these disciplinary walls, bringing together researchers for concrete discussions about shared techniques, open problems, and a path toward a unified algorithmic toolkit.

{{ new_block() }}

# Call for Papers

We invite **non-archival submissions of up to 4 pages** (excluding references and appendices) on parallelizing "inherently sequential" computation. The workshop welcomes algorithmic, hardware-aware, theoretical, and applied contributions. Concrete themes of interest include:

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

## Key dates

- **Submission deadline:** August 29, 2026 (AOE)
- **Author notification:** September 29, 2026 (AOE)
- **Workshop:** December 11–13, 2026 (co-located with NeurIPS 2026)

{{ button(name = "Full Call for Papers", url = "papers")}}
