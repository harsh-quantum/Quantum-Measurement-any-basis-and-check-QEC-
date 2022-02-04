# Quantum-Measurement-in-any-basis-and-check-1 qubit-QEC

Qiskit is one of the good tool where you can do the simulation of Quantum Circuit .\
As a student when i want to measure the qubit in x basis unfortunatly that feature is not present in QisKIT but we can modify our circuit bu adding the H Gate in the end. \
1: But there is no such function avaiable that will give us flexibity in which we measure the qubit in any basis.
With the help of Compleness theorem and then change the one basis into another, Thanks to Professor M -->  follow the link if you want to know the maths behind it [Change of basis](https://www.youtube.com/watch?v=CDmXvPDMIFs/)\

2: The main issue in quantum computation is ERRORS which comes mainly due to the interaction of environment and qubit.In all over the world scientist trying to reduce the error and developing the quantum error correction code whihch help us to preserve or retrieve the information if it got effected by an environment.\
There are different types of codes like Shor 9 qubit code , steane 7 qubit code which are present and help us to protect the information in qubits. \
But what is capability of any code which will correct the 1 single qubit error. This can be done with the help of stabilisers. Majorily there are 3 types of error we generally take into account i.e X,Y and Z also called as Pauili error.In this notebook we can see that we can test our error correction code with the help of parity check matrix.

### REFERENCES :
[1] D. Gottesman. Stabilizer Codes and Quantum Error Correction. Ph.D. thesis, California Institute of Technology, Pasadena, CA, 199
[2] Scott Aaaronson and Daniel Gottesman, “Improved Simulation of Stabilizer Circuits”, Phys. Rev. A 70(052328), 2004. https://arxiv.org/abs/quant-ph/0406196
