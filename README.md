Hardware crosstalk in multi-tenant superconducting quantum
computers constitutes a significant security threat, enabling
adversaries to inject targeted errors across tenant boundaries.
We present the first end-to-end framework for mapping
physical pulse-level attacks to interpretable logical error
channels, integrating density-matrix simulation, quantum process
tomography (QPT), and a novel isometry-based circuit extraction
method. Our pipeline reconstructs the complete induced error
channel and fits an effective logical circuit model, revealing a
fundamentally asymmetric attack mechanism: one adversarial
qubit acts as a driver to set the induced logical rotation, while a
second, the catalyst, refines the attack’s coherence. Demonstrated
on a linear three-qubit system, our approach shows that such
attacks can significantly disrupt diverse quantum protocols,
sometimes reducing accuracy to random guessing, while remaining
effective and stealthy even under realistic hardware parameter
variations. We further propose a protocol-level detection strategy
based on observable attack signatures, showing that stealthy
attacks can be exposed through targeted monitoring and providing
a foundation for future defense-in-depth in quantum cloud
platforms.

Read the paper: https://dl.acm.org/doi/10.1145/3733825.3765282

