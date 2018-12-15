# UTB Symbolic Simplifications

(This file last edited 15-12-2018)

This coding project is a supplement to a research paper in collaboration with Holger Haas and David Cory, to appear shortly. The research paper is concerned with the finding control sequences for quantum gates that are robust to variations in the Hamiltonian. In particular, we present and investigate methods for computing terms quantifying the robustness that are efficient and also enable straightforward computations of gradients for use in numerical optimization. These methods are based on constructing auxiliary differential equations of higher dimension whose generators are given by upper triangular block (UTB) matrices.

This repository contains Mathematica code for verifying a conjecture in the paper, related to the computation of such terms having a particular form. This is explained in the file *description.pdf*. 
Generally, the functionality is: 
* Symbolically represents expressions resulting from time-ordered exponential of UTB matrices
* Given a UTB matrix, finds and simplifies the expressions for its time ordered exponential using replacement rules.
* Contains code for verifying the conjecture for any pair of non-negative integers, as well as the output of this code for all pairs drawn from 0, ..., 15

## Contents

* *description.pdf* contains a description of the purpose of the code, as well as a description of its design.
* *UTBSymbolicSimplifications* is the Mathematica notebook, containing the code, as well as some example applications.