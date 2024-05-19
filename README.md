## Quantum Error Correction: Simulations and Stabilizer Implementations


In this notebook, we first implement the measurement of a ZZ stabilizer. We compare the execution using a simulator and on real hardware.

Next, we simulate a bit flip error on a 3-qubit system. The noise model is quite simple: for each qubit, we apply an X gate with a probability p. In other words, each qubit has a probability p of flipping. We analyze how error detection evolves with p.

Finally, we implement an XX stabilizer for phase flip correction.
