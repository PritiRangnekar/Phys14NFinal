**Quantum Fourier Transforms, Final Project for PHYSICS 14N, Winter 2021.**

**.ipynb notebook:** has everything needed to run the code and see the results; it also includes complete documentation (line-by-line) and big picture to keep track of overall structure, specific equations that are applied, and comparison of the results to expectations.

**Additional image files:** in case you would like to see the expected results, generated in a "hard-coded" manner (foolproof) by running Qiskit's statevector simulator on the Bloch sphere. There are files to see "14" in the computational and Fourier bases, and "2" in the computational and Fourier bases - these are the 2 examples I use for the QFT and inverse QFT demos respectively.

**Article PDF**: To gain a better understanding of QFTs more conceptually, please read my article on the same topic (also in this repository as a PDF).

**Important point regarding Qiskit:** Note: This representation of the bitstring puts the most significant bit (MSB) on the left, and the least significant bit (LSB) on the right. This is the standard ordering of binary bitstrings. We order the qubits in the same way (qubit representing the MSB has index 0), which is why Qiskit uses a non-standard tensor product order. https://qiskit.org/documentation/tutorials/circuits/1_getting_started_with_qiskit.html

Thank you for reading!
