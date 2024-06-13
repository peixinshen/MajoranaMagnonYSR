[![Mathematica](https://img.shields.io/badge/Wolfram-Mathematica-DD1100?logo=wolfram-mathematica&logoColor=DD1100)](https://www.wolfram.com/mathematica/)
[![View notebooks](https://wolfr.am/HAAhzkRq)](https://wolfr.am/1ek3Mq22e)

# Majorana-Magnon Interactions in Topological Shiba Chains

![Sketch](MajoranaMagnonYSR.gif)

This repository provides the source code for some analytical and numerical implementations of the manuscript *Majorana-Magnon interactions in topological Shiba chains* [[1](#refer-anchor-1)].

## Overview

The code contains two sections, each performing a specific task:

1. **Overlap Integrals in Yu-Shiba-Rusinov Chains**: This section provides the analytical derivation of overlap integrals that have been widely used in the effective Hamiltonian of Yu-Shiba-Rusinov chains [[2](#refer-anchor-2)].
   
2. **Robustness of Visibility**: This section generates random realizations of the system by adding random disorders to the pristine system. We also provide the specific realizations of the system that are used in the figures of the paper [[1](#refer-anchor-1)].

## Usage

The code `MajoranaMagnonYSR.nb` is written by the Wolfram Language in the form of Mathematica notebook ([view online](https://wolfr.am/1ek3Mq22e)). Please note that the code uses several global constants that are defined at the beginning of the code. You may need to adjust these constants depending on your specific use case. Additional code and data for generating other figures in the paper are available from the corresponding authors upon reasonable request.

This notebook has been featured in the [Wolfram Community](https://community.wolfram.com/groups/-/m/t/3192232) in the editorial columns: [Staff Picks](http://wolfr.am/StaffPicks) and [Publication Materials](http://wolfr.am/PubMat).

## References

<div id="refer-anchor-1"></div> 

[1] P.-X. Shen*, V. Perrin*, M. Trif, and P. Simon, Majorana-magnon interactions in topological Shiba chains, [Phys. Rev. Res. 5, 033207 (2023)](https://journals.aps.org/prresearch/abstract/10.1103/PhysRevResearch.5.033207).

<div id="refer-anchor-2"></div>

[2] P. M. R. Brydon, S. Das Sarma, H.-Y. Hui, and J. D. Sau, Topological Yu-Shiba-Rusinov chain from spin-orbit coupling, [Phys. Rev. B 91, 064505 (2015)](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.91.064505).

## Citation

If you use this code or notebook in your research, please cite our paper:

```bibtex
@article{Shen2023MajoranaMagnon,
  title = {Majorana-Magnon Interactions in Topological {{Shiba}} Chains},
  author = {Shen, Pei-Xin and Perrin, Vivien and Trif, Mircea and Simon, Pascal},
  year = {2023},
  month = sep,
  journal = {Physical Review Research},
  volume = {5},
  number = {3},
  pages = {033207},
  publisher = {American Physical Society},
  doi = {10.1103/PhysRevResearch.5.033207}
}
```