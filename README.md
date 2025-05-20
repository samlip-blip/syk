# syk
The SYK model consists of randomly interacting Majorana fermions and exhibits maximal quantum chaos, meaning it saturates the bound on quantum Lyapunov exponents, a measure of how quickly small perturbations grow over time. This behavior is closely related to the out-of-time-order correlators (OTOCs), which quantify how information spreads in a chaotic system [1],[2].

In the context of black holes, the SYK model serves as a toy model for understanding aspects of quantum gravity and holography. It shares similarities with the near-horizon dynamics of extremal black holes, particularly in how information is scrambled and lost to an observer outside the event horizon [2] [3]. The model's chaotic behavior mimics the way black holes process and obscure information, reinforcing ideas from the AdS/CFT correspondence—a theoretical framework linking quantum gravity and quantum field theory.

[1] https://arxiv.org/abs/2412.20182

[2] https://journals.aps.org/prl/pdf/10.1103/PhysRevLett.126.030602

[3] https://cond.scphys.kyoto-u.ac.jp/~tezuka/pdf/20190820-Nanjing-release.pdf

To simulate the SYK model for 6 Majorana fermions (3 qubits) with random couplings and scrambling dynamics, we'll use Qiskit along with OpenFermion for handling fermionic-to-qubit mappings.

In one of the future notebooks we will explore how to use random graphs to model how quantum information spreads inside a black hole.
