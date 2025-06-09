This repository contains code and data associated to the paper "Rational isolated j-invariants from $X_1(\ell^n)$ and $X_0(\ell^n)$" by Abbey Bourdon and Özlem Ejder (2025).

Our code requires the `gl2.m` file associated to the paper [*l-adic images of Galois for elliptic curves over Q*](https://arxiv.org/abs/2106.11141) by Jeremy Rouse, Andrew V. Sutherland, and David Zureick-Brown (Forum Math. Sigma, 2022). This can be found [here](https://github.com/AndrewVSutherland/ell-adic-galois-images/blob/main/groups/gl2.m). We make remarks on the other files in this repository below:

- `isolated_points_from_image_Gamma1.m` is an abbreviated version of the algorithm of Abbey Bourdon, Sachi Hashimoto, Timo Keller, Zev Klagsbrun David Lowry-Duda, Travis Morrison, Filip Najman, and Himanshu Shukla in the paper [*Towards a classification of isolated j-invariants*](https://arxiv.org/abs/2311.07740), (Math. Comp., 2025). The original algorithm is available [here](https://github.com/davidlowryduda/isolated_points/blob/master/isolatedpoints.m).

- `isolated_points_from_image_Gamma0.m` is an abbreviated version of the algorithm of Meghan Lee, as in her MS thesis [*Isolated j-invariants arising from the modular curve X_0(N)*](https://users.wfu.edu/bourdoam/MeghanLeeThesis.pdf). The original algorithm is available [here](https://github.com/meghanhlee/NonIsolated).

- `elladicgens.txt` contains all known ell-adic images of Galois for non-CM elliptic curves over $\mathbb{Q}$, as classified in [*Elliptic curves over Q and 2-adic images of Galois*](https://arxiv.org/abs/1402.5997) by Jeremy Rouse and David Zureick-Brown (Res. Number Theory, 2015) and in [*l-adic images of Galois for elliptic curves over Q*](https://arxiv.org/abs/2106.11141) Jeremy Rouse, Andrew V. Sutherland, and David Zureick-Brown  (Forum Math. Sigma, 2022).

- `nonisoscript_Gamma1.magma` is the script used to run `isolated_points_from_image_Gamma1.m` on all images in `elladicgens.txt`.

- `nonisoscript_Gamma0.magma` is the script used to run `isolated_points_from_image_Gamma0.m` on all images in `elladicgens.txt`.

- `Gamma1results.out` gives the output from running `isolated_points_from_image_Gamma1.m` on all images in `elladicgens.txt`.

- `Gamma0results.out` gives the output from running `isolated_points_from_image_Gamma0.m` on all images in `elladicgens.txt`.

- `Image49.196.9.1.txt` includes all computations used in the proof of Corollary 3. It employs a "ChangeLevel" function, as appearing in [*On the torsion of rational elliptic curves over sextic fields*](https://arxiv.org/abs/1808.02887) by Harris Daniels and Enrique González-Jiménez (Math. Comp., 2020). The paper is available at  for the paper and the code is available [here](http://verso.mat.uam.es/~enrique.gonzalez.jimenez/research/tables/tors6/RZB_Search.txt).
