
## Case 1: Parallel RL load with Sinusoidal source

Given a parallel RL circuit as in Figure 1, it is supplied with any voltage giving rise to a current. Through some electric meter, you have access to both v and i. It is desired to estimate the value of **R** and **L** for every time instant, assuming that these values can change over time. Of course, Kirchhoff's first law, or KCL, is satisfied,

<p align="center"><img src="https://render.githubusercontent.com/render/math?math=i = i_G + i_L = G_v + \frac{1}{L}\int v = Gv +\Gamma \check{v}" width="300"></p>

where the symbol has been used to indicate the voltage integral and, in addition, the symbol <img src="https://render.githubusercontent.com/render/math?math=\Gamma"> for the inverse of the inductance. By analogy with mechanical systems, the name of compliance will be used for <img src="https://render.githubusercontent.com/render/math?math=\Gamma"> (electromechanical force-current or Firestone analogy). In the above expression, it has been assumed (for simplicity) that the initial conditions are such that they give rise to null values.


<p align="center"><img src="https://electrica.ual.es/spacor/images/spacorcaseone.png" width="300"></p>

Through geometric algebra, we seek a formulation that gives advanced mathematical support to the research carried out by F. De León in his paper T. Hong and F. de León, "Lissajous Curve Methods for the Identification of Nonlinear Circuits: Calculation of a Physical Consistent Reactive Power," in IEEE Transactions on Circuits and Systems I: Regular Papers , vol. 62, no. 12, pp. 2874-2885, Dec. 2015, . doi: 10.1109/TCSI.2015.2495780.

In differential geometry, it is usual to define a local coordinate system associated to each point of the curve and which evolves with the curve along its entire path. This frame is an orthogonal basis composed of the normal, tangent and binormal vector to the curve. The use of the normal and tangent vector define the concept of the osculating plane. The variation of this plane in space is what allows us to correctly estimate the parameters R and L. . For the 2D case at hand, it is sufficient to use the vector y (since it is contained in the osculating plane itself, although in 3D it will be necessary to use the normal vector since we are not sure that y is included in the osculating plane) and the tangent vector, calculated as the derivative of y. Thus, we have,

<p align="center"><img src="https://render.githubusercontent.com/render/math?math=y = v\sigma_1 + \check{v}\sigma_2 + i \sigma_3"></p>
<p align="center"><img src="https://render.githubusercontent.com/render/math?math=y' = v'\sigma_1 + v\sigma_2 + i' \sigma_3"></p>
and proceed to calculate the oscillating plane,
<p align="center"><img src="https://render.githubusercontent.com/render/math?math=K_{osc} = y \wedge y' = (v^2 - \check{v}v')\sigma_{12} + (\check{v}i`-iv)\sigma_{23} + (iv'-vi')\sigma_{31}  width="25%"></p>

Following the reasoning of finding the ratio between  and , as well as  and  the value of  and  is now,
