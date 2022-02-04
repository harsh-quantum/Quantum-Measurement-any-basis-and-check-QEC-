# Quantum-Measurement-in-any-basis-and-check-1 qubit-QEC

Qiskit is one of the good tool where you can do the simulation of Quantum Circuit. When we want to measure the qubit in X basis unfortunatly that feature is not present in QisKIT but we can modify our circuit by adding the H Gate in the end. Currently, there is no such function avaiable that will give us flexibity in which we measure the qubit in any basis.
With the help of Compleness theorem we can change the one basis into another, Thanks to Professor M -->  follow the link if you want to know the maths behind it [Change of basis](https://www.youtube.com/watch?v=CDmXvPDMIFs/)\

Secondly, The main issue in quantum computation is ERRORS which comes mainly due to the interaction of environment and qubit. In all over the world scientist trying to reduce the error and developing the quantum error correction code which help us to preserve or retrieve the information if it got effected by an environment.\
There are different types of codes like Shor 9 qubit code , steane 7 qubit code which are present and help us to protect the information in qubits. \
But what is capability of any code which will correct the 1 single qubit error. This can be done with the help of stabilisers. Majorily there are 3 types of error we generally take into account i.e X,Y and Z also called as Pauili error.In this notebook we can see that we can test our error correction code with the help of parity check matrix.

To resolve the above issues i made the two notebooks which will be helpful specially in the field of measurement based quantum computing. Second note give you more insight about the any 1 qubit error correction code .Also you can try your own code and test it weather it will correct all the pauli errors or not.

![Screenshot 2022-02-04 190255](https://user-images.githubusercontent.com/82764276/152537634-e2d3410a-33e1-4d7c-bd2d-f4bc76398eae.png)
\
\
![download](https://user-images.githubusercontent.com/82764276/152537694-6de6de65-ec91-4a2e-8c5f-10fbfa2acc57.png)
\
\
![download (1)](https://user-images.githubusercontent.com/82764276/152537735-19e5a358-336e-4535-80c8-281d964327db.png)
\
\
![Screenshot 2022-02-04 190211](https://user-images.githubusercontent.com/82764276/152537829-2283b9b7-d2d8-4ec0-949c-556cace4e041.png)
\
\
![Screenshot 2022-02-04 190019](https://user-images.githubusercontent.com/82764276/152537898-126d10d2-7b30-4e05-99ef-61e02f3e3ced.png)


### REFERENCES :
[1] D. Gottesman. Stabilizer Codes and Quantum Error Correction. Ph.D. thesis, California Institute of Technology, Pasadena, CA, 199 \
[2] Scott Aaaronson and Daniel Gottesman, “Improved Simulation of Stabilizer Circuits”, Phys. Rev. A 70(052328), 2004. https://arxiv.org/abs/quant-ph/0406196
