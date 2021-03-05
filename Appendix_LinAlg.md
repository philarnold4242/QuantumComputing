# Linear algebra

https://qiskit.org/textbook/ch-appendix/linear_algebra.html


## Vectors and Vector Spaces

## Matrices and Matrix Operations 

We manipulate qubits in our quantum computer by applying sequences of quantum gates. 
Each quantum gate can be expressed as a matrix that can be applied to state vectors, 
thus changing the state.

Example: 

1. Pauli-X matrix: [[0, 1], [1, 0]]

2. Pauli-Y matrix: Hermitian and Unitary: [[0, -i], [i, 0]]

Two important types of matrices: Hermitian and Unitary

Definition: Conjugate transpose: First transpose [ij -> ji], then conjugate [*]: 
            https://en.wikipedia.org/wiki/Conjugate_transpose

* Hermitian: A is equal to its conjugate transpose

* Unitary: A^(-1) is equal to its conjugate transpose

The reason unitary matrices are important will become more apparent in the section on Hilbert spaces, 
and more so in the quantum mechanics subtopic of this textbook. 
The basic idea is that evolution of a quantum state by application of a unitary matrix 
"preserves" the norm (magnitude) of the quantum state.

Calculating inverse matrices is rarely important in quantum computing. 
Since most of the matrices we encounter are _unitary_, we can assume that 
the inverse is simply given by taking the conjugate transpose.


## Spanning Sets, Linear Dependence, and Bases