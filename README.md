Thesis: Structure-based algorithms for protein-protein interactions
======

![Alt text](https://github.com/lupoglaz/thesis/blob/master/Cover/logo_UJF_vertical_multituelles.png)

## Abstract
The phenotype of every known living organism is determined mainly by the compli-
cated interactions between the proteins produced in this organism. Understanding
the orchestration of the organismal responses to the external or internal stimuli
is based on the understanding of the interactions of individual proteins and their
complexes structures. The prediction of a complex of two or more proteins is the
problem of the protein-protein docking field. Docking algorithms usually have two
major steps: exhaustive 6D rigid-body search followed by the scoring. In this work
we made contribution to both of these steps. We developed a novel algorithm for
6D exhaustive search, HermiteFit. It is based on Hermite decomposition of 3D
functions into the Hermite basis. We implemented this algorithm in the program
for fit- ting low-resolution electron density maps. We showed that it outperforms
existing algorithms in terms of time-per-point while maintaining the same output
model accuracy. We also developed a novel approach to computation of a scoring
function, which is based on simple logical arguments and avoids an ambiguous com-
putation of the reference state. We compared it to the existing scoring functions
on the widely used protein-protein docking benchmarks. Finally, we developed an
approach to include water-protein interactions into the scoring functions and val-
idated our method during the Critical Assessement of Protein Interactions round
47.
