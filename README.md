[![Mathematica](https://img.shields.io/badge/Wolfram-Mathematica-DD1100?logo=wolfram-mathematica&logoColor=DD1100)](https://www.wolfram.com/mathematica/)
[![View notebooks](https://wolfr.am/HAAhzkRq)](https://wolfr.am/1ek3Mq22e)

# Majorana-Magnon Interactions in Topological Shiba Chains

![Sketch](MajoranaMagnonYSR.gif)

This repository provides the source code for some analytical and numerical implementations of the manuscript *Majorana-Magnon interactions in topological Shiba chains* [[1](#refer-anchor-1)].

## Overview

The code contains two sections, each performing a specific task:

1. **Overlap Integrals in Yu-Shiba-Rusinov Chains**: This section provides the analytical derivation of overlap integrals that have been widely used in the effective Hamiltonian of Yu-Shiba-Rusinov chains [[2](#refer-anchor-2)].
   
2. **Robustness of Visibility**: This section generates random realizations of the system by adding random disorders to the pristine system. We also provide the specific realizations of the system that are used in the figures of the manuscript [[1](#refer-anchor-1)].

## Usage

The code `MajoranaMagnonYSR.nb` is written by the Wolfram Language in the form of Mathematica notebook ([view online](https://wolfr.am/1ek3Mq22e)). Please note that the code uses several global constants that are defined at the beginning of the code. You may need to adjust these constants depending on your specific use case. Additional code and data for generating other figures in the manuscript are available from the corresponding authors upon reasonable request.

## References

<div id="refer-anchor-1"></div> 

[1] P.-X. Shen*, V. Perrin*, M. Trif, and P. Simon, Majorana-magnon interactions in topological Shiba chains, [arXiv:2303.13513 (2023)](https://arxiv.org/abs/2303.13513).

<div id="refer-anchor-2"></div>

[2] P. M. R. Brydon, S. Das Sarma, H.-Y. Hui, and J. D. Sau, Topological Yu-Shiba-Rusinov chain from spin-orbit coupling, [Phys. Rev. B 91, 064505 (2015)](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.91.064505).
