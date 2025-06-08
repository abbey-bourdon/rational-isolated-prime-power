This repository contains code and data associated to the paper "Rational isolated j-invariants from $X_1(\ell^n)$ and $X_0(\ell^n)$" by Abbey Bourdon and Özlem Ejder (2025).

Our code requires the gl2.m file associated to the paper "l-adic images of Galois for elliptic curves over $\mathbb{Q}$" by Jeremy Rouse, Andrew V. Sutherland, and David Zureick-Brown, arXiv:2106.11141 (2021). This can be found at https://github.com/AndrewVSutherland/ell-adic-galois-images/blob/main/groups/gl2.m. We make remarks on the other files in this repository below:

*The file isolated_points_from_imaga_Gamma1.m is an abbreviated version of the algorithm of Abbey Bourdon, Sachi Hashimoto, Timo Keller, Zev Klagsbrun David Lowry-Duda, Travis Morrison, Filip Najman, Himanshu Shukla. The original article is availalbe at https://arxiv.org/abs/2311.07740. The original algorithm is available at https://github.com/davidlowryduda/isolated_points/blob/master/isolatedpoints.m.

*The file isolated_points_from_imaga_Gamma0.m is an abbreviated version of the algorithm of Meghan Lee, as in her MS thesis. The original thesis document is available at https://users.wfu.edu/bourdoam/MeghanLeeThesis.pdf. The original algorithm is available at https://github.com/meghanhlee/NonIsolated.

*The file elladicgens.txt contains all known ell-adic images of Galois for non-CM elliptic curves over $\mathbb{Q}$, as classified by Rouse/Zureick-Brown (Rs. Number Theory, 2015) and Rouse/Sutherland/Zureick-Brown (Forum Math. Sigma, 2022). These papers are available at https://arxiv.org/abs/1402.5997 & https://arxiv.org/abs/2106.11141.

*The file nonisoscript_Gamma1.magma is the script used to run isolated_points_from_imaga_Gamma1.m on all images in elladicgens.txt.

*The file nonisoscript_Gamma0.magma is the script used to run isolated_points_from_imaga_Gamma0.m on all images in elladicgens.txt.

*The file Gamma1results.out gives the output from running isolated_points_from_imaga_Gamma1.m on all images in elladicgens.txt.

*The file Gamma0results.out gives the output from running isolated_points_from_imaga_Gamma0.m on all images in elladicgens.txt.

*The file Image49.196.9.1.txt includes all computations used in the proof of Corollary 3. It employs a "ChangeLevel" function, as appearing in work of Daniels/Gonzalez-Jimenez (Math. Comp., 2020). The paper is available at https://arxiv.org/abs/1808.02887 for the paper and the code is available at http://verso.mat.uam.es/~enrique.gonzalez.jimenez/research/tables/tors6/RZB_Search.txt.
