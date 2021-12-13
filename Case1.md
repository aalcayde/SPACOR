
## Case 1: Parallel RL load with Sinusoidal source

Given a parallel RL circuit as in Figure 1, it is supplied with any voltage giving rise to a current. Through some electric meter, you have access to both v and i. It is desired to estimate the value of R and L for every time instant, assuming that these values can change over time. Of course, Kirchhoff's first law, or KCL, is satisfied,

<img src="https://render.githubusercontent.com/render/math?math=i = i_G + i_L = G_v + \frac{1}{L}\int v = Gv +\Gamma \check{v}" width="150">

<img src="https://electrica.ual.es/spacor/images/spacorcaseone.png" width="300">

where the symbol has been used to indicate the voltage integral and, in addition, the symbol  for the inverse of the inductance. By analogy with mechanical systems, the name of compliance will be used for  (electromechanical force-current or Firestone analogy). In the above expression, it has been assumed (for simplicity) that the initial conditions are such that they give rise to null values.


Through geometric algebra, we seek a formulation that gives advanced mathematical support to the research carried out by F. De León in his paper T. Hong and F. de León, "Lissajous Curve Methods for the Identification of Nonlinear Circuits: Calculation of a Physical Consistent Reactive Power," in IEEE Transactions on Circuits and Systems I: Regular Papers , vol. 62, no. 12, pp. 2874-2885, Dec. 2015, . doi: 10.1109/TCSI.2015.2495780.

In differential geometry, it is usual to define a local coordinate system associated to each point of the curve and which evolves with the curve along its entire path. This frame is an orthogonal basis composed of the normal, tangent and binormal vector to the curve. The use of the normal and tangent vector define the concept of the osculating plane. The variation of this plane in space is what allows us to correctly estimate the parameters R and L. . For the 2D case at hand, it is sufficient to use the vector y (since it is contained in the osculating plane itself, although in 3D it will be necessary to use the normal vector since we are not sure that y is included in the osculating plane) and the tangent vector, calculated as the derivative of y. Thus, we have,

