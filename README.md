# ZO-FO-Gap

This repository contains the code files used in the paper titled "From Cursed to Competitive: Closing the ZO–FO Gap via Input-to-State Stability".

Link to the paper: "https://arxiv.org/pdf/2604.25372".

In this project, we show that Gaussian zeroth-order (ZO) versions of gradient descent, heavy ball and Nesterov’s accelerated gradient can be viewed as their first-order (FO) counterparts with bounded perturbations. Using input-to-state stability, we prove that they converge at the same rate as the FO methods, with no extra dimension dependence in the iteration count, to a neighbourhood of the FO fixed point whose size is controlled by the smoothing parameter, step size and number of sampled directions.

This repository contains two Python notebook files:

"ZO_nodim.ipynb" includes the implementations of the experiments presented in Section 4.1 and Appendix E.1.

"ZO_nodim_NN.ipynb" includes the implementations of the experiments presented in Section 4.2 and Appendix E.2.

