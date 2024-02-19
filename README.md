# ATR_TN93
Code accompanying the paper "A novel algebraic approach to time-reversible evolutionary models" by Marta Casanellas, Roser Homs and Angélica Torres. Preprint available [here](https://arxiv.org/abs/2309.02276).

This repository contains Macaulay2 and Julia files with the code to compute phylogenetic invariants for the Tamura-Nei 93 evolutionary model. We provide a description of the contents of each file.

**MACAULAY2 files**
- **Tripod.m2 :** Computation of the phylogenetic invariants for tripods under the TN93 model. These computations correspond to Lemma 5.1 in the manuscript.
- **Tripod_Toric.m2 :** Computation of the polynomials generating the phylogenetic ideal for a tripod, and polynomials that define the complete intersection for the phylogenetic variety coming from the tripod under the TN93 model. These computations correspond to Proposition 5.3 in the manuscript and Computations for the tripod in the Supplementary Material.
- **Quartet.m2 :**  Computations of phylogenetic invariants for quartets under the TN93 model. These computations correspond to Section 2.2 of the Supplementary Material.
- **Quartet_CI.m2 :** Computations of the polynomials defining a complete intersection of the phylogenetic variety coming for a quartet 12|34. The results correspond to Theorem 5.14 in the manuscript.

**Julia files**
- **Mixed_submatrices.jl :** In this file we check that the matrix D in the proof of Proposition 5.3 in the manuscript does not have any mixed submatrix with more rows than columns.

**Text files**
- **3leavesVanishingIdeal_FinalBasis.txt :** Printed list of results from the Tripod.m2 computations.
- **4leaves_tensor_FinalBasis.txt** and **4leaves_tensor_id_FinalBasis.txt :** Printed lists of results from the Quartet.m2 computations (the first one corresponds to the general tensor and the second one to assuming the identity matrix at the leaves).
