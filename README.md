# SMNonLinearResponse
Wolfram code used in "Strong Nonlinear Response of Strange Metals".

Repository includes Wolfram files that were used to perform numeric calculations in Section III and Section IV of Supplemental Information to arXiv:2403.00062

Files Collision_Integral_SM.nb Collision_Integral_FL.nb, Collision_Integral_SM.mx Collision_Integral_FL.mx are used to find the coefficient A in Eqs. 107-109 in Section III of Supplemental Information.

The Collision_Integral_SM.nb computes the A coefficient for the critical case - Eq. 108. The Collision_Integral_FL.nb computes the coefficient in the Fermi liquid regime - Eq. 109. Files Collision_Integral_SM.mx Collision_Integral_FL.mx are the corresponding data files for a computationally heavy step in the evaluation of the collision integral. The files are evaluated for the set of parameters reported in the file.

Files Results.nb, wGamma_0_plots.nb, and No_Gamma0_figs.nb were used in Section IV of Supplemental Information.

Results.nb generates results for nonzero Gamma_0; specifically, TG1al1 array are the results for Gamma_0=1 (results of evaluation are saved in the same .nb). wGamma_0_plots.nb uses TG1al1 as an input to produce plots in the supplementary. No_Gamma0_figs.nb generates data and plots for Gamma_0=0, with the evaluation results saved in the same file.
