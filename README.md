# Relativistic-quantum-simulation-qiskit
simulating Wigner rotation as a unitary operator, wigner rotation as controlled gate conditioned on momentum, spin-spin entanglement transfer to spin-momentum under relatisvistic motion. We simulate these in qiskit. 
There are 3 sections in the project, each based on a foundational research paper reference along:

Section 1: Simulate Wigner rotation as a unitary operator on spin degree of freedom. This is based on Quantum information and relativity theory by Asher Peres & Daniel R. Terno. We try to simulate a simple circuit to see how Lorentz boost affects spin state for different velocities and momentum direction.

Section 2: This is based on paper Spin-momentum correlation in relativistic single particle quantum states by M. A. Jafarizadeh & M. Mahdian. The paper shows how the spin of a single particle entangles with its momentum under a Lorentz boost. We try to create and simulate a circuit on what is shown in paper to implement a controlled Wigner rotation conditioned on momentum eigenstates. We show in qiskit (what is proved in paper) that under certain conditions, Controlled Wigner gate acts as a CNOT gate.

Section 3: This is based on paper Quantum Entanglement of moving bodies by Gingrich and Adani We extend section 2 from single particle to two particle system with their spin entangled. We study how relativistic transformations impact spin-spin entanglement of 2 particles and how it correlates with spin-momentum entanglement. Then we study the concurrence and reduced density matrix to show that spin-spin entanglement transfers to spin-momentum under a Lorentz boost.
