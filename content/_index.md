+++
title = "Dynamics Strike Back"
+++

A dynamical system evolves a state over time---either in discrete time, like a recurrent neural network, or in continuous time, like an ordinary differential equation. Their inductive bias for temporal evolution once made dynamical systems the default primitive for sequential data, from hidden Markov models to LSTMs and neural ODEs. But because they appear "inherently sequential"---to reach a final state, one seemingly must pass through every intermediate step---they underutilize parallel hardware, and the rise of GPUs and the transformer pushed dynamics out of the spotlight.

Dynamics are now striking back. A wave of breakthroughs---together with the desire to move beyond autoregressive inference---has returned dynamical systems to the center of machine learning along three pillars:

- **Looped transformers** iterate a shared block to scale test-time compute, effectively turning the transformer architecture into an RNN in depth.
- **Diffusion language models** generate text without autoregressive inference, by running a dynamical system in depth.
- **RNNs and state-space models** rival attention on long sequences while keeping a compact, constant-size recurrent state.

Underpinning all three, **parallel-in-time algorithms** evaluate and train dynamical systems efficiently on modern accelerators, dissolving the "inherently sequential" barrier. This workshop brings together researchers who use dynamical systems for machine learning to share best practices and tackle common problems---accelerating progress and enabling cross-discipline transfer.

{{ new_block() }}

# Call for Papers

We invite **non-archival short papers of up to 4 pages** (excluding references and appendices) on dynamical systems in machine learning. The workshop welcomes architectural, algorithmic, theoretical, hardware-aware, and applied contributions. Themes of interest include:

- **Dynamics-based architectures**, including looped and recurrent transformers; diffusion, flow, and score-based language models; RNNs and SSMs; neural ODEs; deep equilibrium models; oscillator-based computing; and energy-based models.
- **Parallel-in-time** evaluation and training of dynamical systems, from RNNs, SSMs, and ODEs to MCMC, particle methods, and Kalman filtering.
- **Theoretical limits** of sequential versus parallel computation, including formal characterizations of what is "inherently sequential."
- **Hardware-aware kernels and systems** for dynamics-based models.
- **Applications** of dynamics-based models to reasoning, generation, and probabilistic inference, especially as a new axis of scaling.
- **Negative results**, failure modes, and benchmarks for dynamics-based architectures.

## Key dates

- **Submission deadline:** August 29, 2026 (AOE)
- **Author notification:** September 29, 2026 (AOE)
- **Workshop:** December 11–13, 2026 (co-located with NeurIPS 2026)

{{ button(name = "Full Call for Papers", url = "papers")}}
