# case_IEEE123
A modified IEEE 123 bus balanced feeder in matpower case format(mpc) modified from https://github.com/LucienBobo/SOCP_OPF_Nick2017
intermediate buses are added on power lines, and closed breakers are modeled using a branch with very small impedence (1e-6~1e-7 for X and 1e-7~1e-8 for R)
The topology of the feeder is basically as in "Network partition and voltage coordination control for distribution networks with high penetration of distributed PV units",Y. Chai,
L. Guo, C. Wang, Z. Zhao, et al. https://ieeexplore.ieee.org/document/8309383
