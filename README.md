# Pert_BDNK_Stars
Mathematica utilities for perturbation theory of viscous stars. 

We provide a package <mark>xPertGSGM</mark> that features a set of utilities to work in the Gerlach-Sengupta-Gundlach-Martín García framework for perturbation theory. 
The perturbed Einstein equations are provided as separate files in `equations/Odd_Eqs` and `equations/Even_Eqs`. 
The stress energy tensor associated to perturbations of a BDNK fluid is given in the files `equations/Odd_SET` and `equations/Even_SET`. 

All of these utilities are illustrated in the example notebooks Odd_Equations.nb and Even_Equations.nb. 
These show how to construct a frame and load the perturbed Einstein equations and the perturbed Stress Energy tensor.
Moreover they contain the step-by-step derivation of the master equations presented in the paper, as well as their full expression in coordinates.

If you find this useful and use this in your research, please cite the accompanying paper.

```
@article{Redondo-Yuste:2024vdb,
    author = "Redondo-Yuste, Jaime",
    title = "{Perturbations of relativistic dissipative stars}",
    eprint = "2411.16841",
    archivePrefix = "arXiv",
    primaryClass = "gr-qc",
    month = "11",
    year = "2024"
}
```
