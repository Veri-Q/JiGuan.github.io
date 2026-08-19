---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## Research Focus

My research develops **formal methods for trustworthy quantum computing**, with a focus on the correctness, security, privacy, and reliability of quantum systems, algorithms, programs, and hardware-facing applications. The long-term goal is to make quantum systems not only powerful, but also **verifiable, robust, privacy-preserving, and deployable**.

The work connects formal verification, quantum information, quantum programming, quantum machine learning, and NISQ-era algorithm design. It also feeds into **[VeriQ](https://www.veri-q.com)**, our trustworthy quantum computing toolchain.

<div class="research-snapshot" markdown="1">
**Core themes:** quantum model checking; verification of quantum programs and circuits; robustness, fairness, and privacy in quantum machine learning; quantum algorithms for verification-relevant primitives; NISQ-oriented simulation, synthesis, and chemistry applications.

**Publication map:** this page highlights representative work by research direction. The full chronological list is available on the [Publications]({{ site.baseurl }}/publications/) page.
</div>

---

## Research Modules

<section class="research-area" markdown="1">
<div class="research-area__eyebrow">Theme 1</div>

### Correctness of Quantum Systems

Quantum systems are difficult to verify because their states are continuous, high-dimensional, and measurement-dependent. I study mathematical models, temporal logics, and model-checking algorithms for reasoning about quantum system behavior.

**Representative contributions**
- Formal models for quantum Markov chains and quantum continuous-time Markov chains.
- Decomposition and reachability analysis for long-run quantum system behavior.
- Temporal/logical specifications for dynamic correctness properties.
- Verification of emerging quantum programming patterns, including ancilla safety and tensor-network-style state representations.

**Related publications**
- Li, J., Mei, J., Fang, W., and **Guan, J.\***. *Formal Verification of Quantum Ancilla Safety*. **CAV 2026**. [Paper](https://link.springer.com/chapter/10.1007/978-3-032-32537-2_16) · [DOI](https://doi.org/10.1007/978-3-032-32537-2_16) · [arXiv](https://arxiv.org/abs/2608.13099) · [PDF](https://link.springer.com/content/pdf/10.1007/978-3-032-32537-2_16.pdf) · [Artifact](https://doi.org/10.5281/zenodo.19784589) · [GitHub](https://github.com/Veri-Q/Ancilla-Safety)
- Xu, M., Chen, Y., and **Guan, J.\***. *Model Checking Matrix Product States Against Linear Chain Logic*. **CAV 2026**. [Paper](https://link.springer.com/chapter/10.1007/978-3-032-32537-2_17) · [DOI](https://doi.org/10.1007/978-3-032-32537-2_17) · [arXiv](https://arxiv.org/abs/2605.14356) · [PDF](https://link.springer.com/content/pdf/10.1007/978-3-032-32537-2_17.pdf) · [Artifact](https://doi.org/10.5281/zenodo.19694363) · [GitHub](https://github.com/Veri-Q/MC-MPS)
- **Guan, J.\***, Feng, Y., Turrini, A., and Ying, M. *Measurement-based Verification of Quantum Markov Chains*. **CAV 2024**. [Paper](https://link.springer.com/chapter/10.1007/978-3-031-65633-0_24) · [DOI](https://doi.org/10.1007/978-3-031-65633-0_24) · [arXiv](https://arxiv.org/abs/2405.05825)
- Mei, J., Xu, M., **Guan, J.**, Deng, Y., and Yu, N. *Checking Continuous Stochastic Logic Against Quantum Continuous-time Markov Chains*. **LMCS 2025**. [Paper](https://lmcs.episciences.org/16897) · [DOI](https://doi.org/10.46298/lmcs-21%284:22%292025) · [arXiv](https://arxiv.org/abs/2202.05412)
- **Guan, J.** and Yu, N. *A Probabilistic Logic for Verifying Continuous-time Markov Chains*. **TACAS 2022**. [Paper](https://link.springer.com/chapter/10.1007/978-3-030-99527-0_1) · [DOI](https://doi.org/10.1007/978-3-030-99527-0_1) · [arXiv](https://arxiv.org/abs/2004.08059)
- Xu, M., Mei, J., **Guan, J.\***, and Yu, N. *Model Checking Quantum Continuous-Time Markov Chains*. **CONCUR 2021**. [Paper](https://drops.dagstuhl.de/entities/document/10.4230/LIPIcs.CONCUR.2021.13) · [DOI](https://doi.org/10.4230/LIPIcs.CONCUR.2021.13) · [arXiv](https://arxiv.org/abs/2105.00382)
- **Guan, J.\***, Feng, Y., and Ying, M. *Decomposition of Quantum Markov Chains and Its Applications*. **JCSS 2018**. [Paper](https://www.sciencedirect.com/science/article/pii/S0022000018301223) · [DOI](https://doi.org/10.1016/j.jcss.2018.01.005) · [arXiv](https://arxiv.org/abs/1608.06024)

<p class="research-area__note">These results connect with the monograph <em>Model Checking Quantum Systems: Principles and Algorithms</em> by Ying, Feng, Yu, and Duan.</p>
</section>

<section class="research-area" markdown="1">
<div class="research-area__eyebrow">Theme 2</div>

### Robust, Fair, and Privacy-Preserving Quantum Algorithms

Quantum machine learning and quantum data-processing pipelines can be vulnerable to noise, adversarial perturbations, and privacy leakage. I develop formal definitions, verification algorithms, and mechanisms for trustworthy quantum learning and privacy.

**Representative contributions**
- Formal verification of local/global robustness for quantum classifiers.
- Fairness verification for quantum machine learning.
- Differential privacy analysis for quantum algorithms and quantum local privacy mechanisms.
- Hardware-facing robustness benchmarking and validation on superconducting quantum processors.

**Related publications**
- **Guan, J.\***. *Optimal Mechanisms for Quantum Local Differential Privacy*. **ACM CCS 2025**. [Paper](https://dl.acm.org/doi/10.1145/3719027.3765178) · [DOI](https://doi.org/10.1145/3719027.3765178) · [arXiv](https://arxiv.org/abs/2407.13516)
- **Guan, J.\***, Fang, W., Huang, M., and Ying, M. *Detecting Violations of Differential Privacy for Quantum Algorithms*. **ACM CCS 2023**. [Paper](https://dl.acm.org/doi/10.1145/3576915.3623108) · [DOI](https://doi.org/10.1145/3576915.3623108) · [arXiv](https://arxiv.org/abs/2309.04819)
- **Guan, J.\***, Fang, W., and Ying, M. *Verifying Fairness in Quantum Machine Learning*. **CAV 2022**. [Paper](https://link.springer.com/chapter/10.1007/978-3-031-13188-2_20) · [DOI](https://doi.org/10.1007/978-3-031-13188-2_20) · [arXiv](https://arxiv.org/abs/2207.11173)
- **Guan, J.\***, Fang, W., and Ying, M. *Robustness Verification of Quantum Classifiers*. **CAV 2021**. [Paper](https://link.springer.com/chapter/10.1007/978-3-030-81685-8_7) · [DOI](https://doi.org/10.1007/978-3-030-81685-8_7) · [arXiv](https://arxiv.org/abs/2008.07230)
- Zhang, H. F., Chen, Z. Y., Wang, P., Guo, L. L., Wang, T. L., Yang, X. Y., Zhao, R. Z., Zhao, Z. A., Zhang, S., Du, L., Tao, H. R., ..., **Guan, J.\***, Duan, P., and Guo, G. *Experimental Robustness Benchmark of Quantum Neural Network on a Superconducting Quantum Processor*. **SCIENCE CHINA Physics, Mechanics & Astronomy**, 2025. [arXiv](https://arxiv.org/abs/2505.16714)
- **Guan, J.** and Ying, M. *Verifying Adversarial Robustness in Quantum Machine Learning: From Theory to Physical Validation via a Software Tool*. In **Quantum Robustness in Artificial Intelligence**. Springer. [Chapter](https://link.springer.com/chapter/10.1007/978-3-032-11153-1_10) · [DOI](https://doi.org/10.1007/978-3-032-11153-1_10) · [Chapter PDF]({{ site.baseurl }}/files/quantum-robustness-ai-chapter.pdf)
- Li, C., Ying, M., and **Guan, J.\***. *Differential Privacy of Quantum and Quantum-Inspired-Classical Recommendation Algorithms*. [arXiv](https://arxiv.org/abs/2502.04758)
</section>

<section class="research-area" markdown="1">
<div class="research-area__eyebrow">Theme 3</div>

### Quantum Program Analysis, Simulation, and Design Automation

Trustworthy quantum computing needs tools that can analyze quantum programs, optimize circuits, simulate noisy behavior, and check equivalence. I work on formal and algorithmic foundations for quantum design automation and quantum software analysis.

**Representative contributions**
- Symbolic simulation and analysis for quantum programs with loops and sequential quantum circuits.
- Robustness verification tools for quantum machine learning models.
- Simulation and equivalence checking of noisy quantum circuits.
- Exact and approximate synthesis/optimization for quantum circuits.

**Related publications**
- Li, Z., **Guan, J.\***, and Ying, M. *QSeqSim: A Symbolic Simulator for Qiskit While Loops Using Sequential Quantum Circuits*. **FM 2026**. [Paper](https://link.springer.com/chapter/10.1007/978-3-032-26204-2_30) · [DOI](https://doi.org/10.1007/978-3-032-26204-2_30) · [arXiv](https://arxiv.org/abs/2605.14881) · [PDF]({{ site.baseurl }}/files/qseqsim-fm2026.pdf) · [GitHub](https://github.com/Veri-Q/QSeqSim)
- Li, C., Zhou, X., **Guan, J.\***, Meng, F., Zhu, P., and Luo, Y. *Lin-search: Scaling Exact Synthesis of CNOT Circuits via Hybrid Iterative Deepening Search*. **DAC 2026**. [Program](https://63dac.conference-program.com/contributors/) · [Paper by request](mailto:guanji1992@gmail.com?subject=Request%20for%20Lin-search)
- Huang, M., **Guan, J.\***, Fang, W., and Ying, M. *Approximation Methods for Simulation and Equivalence Checking of Noisy Quantum Circuits*. **IEEE TCAD 2025**. [Paper](https://doi.org/10.1109/TCAD.2025.3623498) · [DOI](https://doi.org/10.1109/TCAD.2025.3623498) · [arXiv](https://arxiv.org/abs/2503.10340)
- Lin, Y., **Guan, J.\***, Fang, W., Ying, M., and Su, Z. *A Robustness Verification Tool for Quantum Machine Learning Models*. **FM 2024**. [Paper](https://link.springer.com/chapter/10.1007/978-3-031-71162-6_21) · [DOI](https://doi.org/10.1007/978-3-031-71162-6_21) · [arXiv](https://arxiv.org/abs/2407.13533) · [GitHub](https://github.com/Veri-Q/VeriQR)
- Huang, M., **Guan, J.\***, Fang, W., and Ying, M. *Approximation Algorithm for Noisy Quantum Circuit Simulation*. **DATE 2024**. [Paper](https://ieeexplore.ieee.org/document/10546657) · [DOI](https://doi.org/10.23919/DATE58400.2024.10546657) · [arXiv](https://arxiv.org/abs/2211.17028)
- He, R., **Guan, J.**, Hong, X., Cui, G., Wang, S., and Ying, S. *RH: An Architecture for Redesigning Quantum Circuits on Quantum Hardware Devices*. [arXiv](https://arxiv.org/abs/2412.20893)
- Chen, K., Fang, W., **Guan, J.\***, Hong, X., Huang, M., Liu, J., Wang, Q., and Ying, M. *VeriQBench: A Benchmark for Multiple Types of Quantum Circuits*. [arXiv](https://arxiv.org/abs/2206.10880) · [GitHub](https://github.com/Veri-Q/Benchmark)
</section>

<section class="research-area" markdown="1">
<div class="research-area__eyebrow">Theme 4</div>

### Quantum Algorithms, NISQ Applications, and Verification Primitives

I also study quantum algorithms and NISQ applications that interact with verification, simulation, and trustworthy computing, including quantum information metrics, quantum games, and chemistry-oriented variational algorithms.

**Representative contributions**
- Quantum algorithms for fidelity estimation, entropy, trace distance, and hitting probabilities.
- VQE ansatz design for chemistry simulations with symmetry and compactness considerations.
- Quantum game and property-partitioning experiments on superconducting processors.
- NISQ-oriented methods that connect algorithm design with verification and reliability.

**Related publications**
- He, R., Ablimit, A., Hong, X., Chai, Q., Zhou, J., **Guan, J.**, Cui, G., and Ying, S. *Hamiltonian-Informed Point Group Symmetry-Respecting Ansätze for the Variational Quantum Eigensolver*. **Journal of Chemical Theory and Computation**, 2026. [Paper](https://pubs.acs.org/doi/10.1021/acs.jctc.6c00057) · [DOI](https://doi.org/10.1021/acs.jctc.6c00057) · [arXiv](https://arxiv.org/abs/2512.21087)
- He, R., Hong, X., Chai, Q., **Guan, J.**, Zhou, J., Ablimit, A., Cui, G., and Ying, S. *Constructing Compact ADAPT Unitary Coupled-Cluster Ansatz with Parameter-Based Criterion*. **Journal of Chemical Theory and Computation**, 2026. [Paper](https://pubs.acs.org/doi/10.1021/acs.jctc.6c00269) · [DOI](https://doi.org/10.1021/acs.jctc.6c00269) · [arXiv](https://arxiv.org/abs/2602.04253)
- Jiang, H., Fu, J., Xu, M., **Guan, J.**, and Ying, S. *A Quantum Game Designed for Property Partitioning with Implementation on Superconducting Quantum Processors*. **Theoretical Computer Science**, 2026. [Paper](https://doi.org/10.1016/j.tcs.2026.115816) · [DOI](https://doi.org/10.1016/j.tcs.2026.115816)
- Wang, Q., **Guan, J.**, Liu, J., Zhang, Z., and Ying, M. *New Quantum Algorithms for Computing Quantum Entropies and Distances*. **IEEE Transactions on Information Theory**, 2024. [Paper](https://ieeexplore.ieee.org/document/10530179) · [DOI](https://doi.org/10.1109/TIT.2024.3399014) · [arXiv](https://arxiv.org/abs/2203.13522)
- Wang, Q., Zhang, Z., Chen, K., **Guan, J.\***, Fang, W., Liu, J., and Ying, M. *Quantum Algorithm for Fidelity Estimation*. **IEEE Transactions on Information Theory**, 2022. [Paper](https://ieeexplore.ieee.org/document/9875352) · [DOI](https://doi.org/10.1109/TIT.2022.3203985) · [arXiv](https://arxiv.org/abs/2103.09076)
- **Guan, J.\***, Wang, Q., and Ying, M. *An HHL-Based Algorithm for Computing Hitting Probabilities of Quantum Random Walks*. **Quantum Information & Computation**, 2021. [Paper](https://www.rintonpress.com/journals/doi/QIC21.5-6-4.html) · [DOI](https://doi.org/10.26421/QIC21.5-6-4) · [arXiv](https://arxiv.org/abs/2009.03618)
</section>

---

## VeriQ Toolchain

<div class="research-toolchain" markdown="1">
**VeriQ** is our toolchain for trustworthy quantum computing, spanning:

- **Verification and model checking:** correctness of quantum systems, Markovian models, and program-level properties.
- **Robustness and privacy:** formal verification of quantum machine learning robustness, fairness, and differential privacy.
- **Simulation and equivalence checking:** scalable analysis for noisy quantum circuits and dynamic quantum programs.
- **Design automation:** circuit synthesis, optimization, benchmarking, and hardware-aware redesign.

Representative tools and artifacts include **VeriQR**, **QSeqSim**, **VeriQBench**, noisy-circuit simulation/equivalence-checking methods, and hardware-facing robustness benchmarks.

[Visit VeriQ](https://www.veri-q.com) · [View full publication list]({{ site.baseurl }}/publications/)
</div>

---

## Future Research Directions

1. **End-to-end trustworthy quantum software.** Develop verification, testing, and certification methods for dynamic quantum circuits, quantum programs with control flow, and hybrid quantum-classical workflows.
2. **Trustworthy quantum machine learning.** Build robust, fair, and privacy-preserving quantum learning systems, with both formal guarantees and hardware validation.
3. **Scalable NISQ algorithms and design automation.** Improve simulation, synthesis, optimization, and ansatz design for practical NISQ applications, especially when correctness and reliability matter.
4. **Quantum acceleration for formal verification.** Explore quantum algorithms for verification-relevant primitives such as fidelity, distance, entropy, and reachability.

These directions continue the central theme of my work: bringing the rigor of formal methods into quantum computing so that future quantum systems can be trusted in practice.
