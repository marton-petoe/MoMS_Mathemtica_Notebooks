This repository contains supplementary material for the following 2 articles:

>[!NOTE]  
>**[1] Code Verification of Immersed Boundary Techniques using the Method of Manufactured Solutions**<br>
> M. Petö, M. Gorji, F. Duvigneau, A. Düster, D. Juhre, and S. Eisenträger<br>
> Computational Mechanics (2023)<br>
> [https://link.springer.com/article/10.1007/s00466-023-02411-x](https://link.springer.com/article/10.1007/s00466-023-02411-x)

>[!NOTE]  
>**[2] Code verification of non-linear immersed boundary simulations using the method of manufactured solutions**<br>
>M. Petö, D. Juhre, and S. Eisenträger<br>
>Computational Mechanics (2023)<br>
>[https://onlinelibrary.wiley.com/doi/10.1002/pamm.202300068](https://onlinelibrary.wiley.com/doi/10.1002/pamm.202300068)

The provided Wolfram Mathematica (12.0) notebooks contain the symbolic derivations of the manufactured solutions used in these papers. The table below summarizes which notebook is associated with which sections in Paper [1]. Paper [2] contains a single example only, for which the corresponding manufactured solution is located in the notebook `MoMS_3D_Hole_Nonlinear_Elasticity.nb`. Furthermore, in all notebooks, comments are given to locate the equations, figures, and tables in the articles the derived results correspond to. Note that a given notebook can correspond to multiple sections in the article. These notebooks are divided into different parts.

![Scheme](table.PNG)

**Usage**: In order to run the notebooks, the notebook `Utility_functions.nb` should be executed first, which defines the functions related to the computation of the stress and strain tensors, as well as the divergence operator in the different coordinate systems. Note that the execution of the mentioned notebook clears all global variables.

**Disclaimer**: The sole goal of the Mathematica scripts is to achieve a correct and understandable derivation of the manufactured solutions. Note that the scripts are not optimized for performance.

**Cite**: When using the methods or results provided in the paper and supplementary material, please cite our work accordingly.

**Further material**
Two examples from Paper [1] and a single example from Paper [2] are also discussed on the [Community page of Wolfram Research](https://community.wolfram.com/). Here, the derivation pipeline for the selected manufactured solutions can be read and understood without having installed Wolfram Mathematica on your computer. 

>[!NOTE]
>**Code verification of immersed boundary techniques using the method of manufactured solutions​**<br>
> M. Petö, M. Gorji, F. Duvigneau, A. Düster, D. Juhre and S. Eisenträger<br>
> Wolfram Community, STAFF PICKS, May 13, 2024<br>
> [https://community.wolfram.com/groups/-/m/t/3175245](https://community.wolfram.com/groups/-/m/t/3175245)
