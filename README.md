# SPACOR Space Vectors for Parameter Identification of Non-Linear Circuits

It proposes a systematic method for the identification of the load circuit parameters (say the R, L, and C elements) based only on the information of the instantaneous volt age and current measured at the point of common coupling (pcc). **Geometric Algebra (GA)** and concepts of differential geometry are used to produce a rigorous mathematical framework. The identification is formulated as a multidimensional geometrical problem that is solved conveniently by means of GA. Once the passive elements of the load have been identified, the active and reactive powers can be computed from first electromagnetic principles (Maxwell Equations). The theory is general and is verified with linear and nonlinear circuits. The paper shows single-phase circuits but the theory can be extended to three phase circuits. The method is easy to program and has shown to be very robust for all tested cases. Because of its generality, the method presented will find applications beyond electric circuits.
https://electrica.ual.es/spacor

## EXAMPLES
### Case 1: Parallel RL load with Sinusoidal source
Given a parallel RL circuit as in Figure 1, it is supplied with any voltage giving rise to a current. Through some electric meter, you have access to both v and i. It is desired to estimate the value of R and L for every time instant, assuming that these values can change over time. Of course, Kirchhoff's first law, or KCL, is satisfied,
 