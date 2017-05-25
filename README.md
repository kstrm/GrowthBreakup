# GrowthBreakup

The primary contents of the repository is a Jupyter notebook that explores the growth, $A$, and breakup, $B$, rate terms in the Winterwerp (1998) model:

$$ \frac{d(d_f)}{dt}=A-B$$

where, $d_f$ is the floc size. $A$ and $B$ are defined by:

$$A=k_{a}^{'}\frac{{d_{p}}^{n_{f}-3}}{n_{f}\rho _{s}}GCd_{f}^{4-n_{f}} = K_{A}GCd_{f}^{4-n_{f}}$$

and

$$B=k_{b}^{'}\frac{{d_{p}}^{-p}}{n_{f}}\left ( \frac{\mu }{F_{y}} \right )^{q}G^{q+1}\left ( d_{f}-d_{p} \right )^{p}d_{f}^{2q+1} = K_{B}G^{q+1}\left ( d_{f}-d_{p} \right )^{p}d_{f}^{2q+1}$$

Here, $G$ is the turbulent shear rate, $C$ is the suspended sediment concentration, $d_p$ is the primary particle size, $n_f$ is the fractal dimension of the flocs, $k_{a}^{'}$ is the collision efficiency coefficient that accounts for the fact that not all collisions result in aggregation. $k_{a}^{'}$ is an empirical coefficient that needs to be calibrated for each suspension of mud. $k_{b}^{'}$ is the breakup coefficient, and $p$ and $q$ are empirical coefficients. In the model, $F_{y}$ and $k_{b}^{'}$ are functions of the physiochemical properties of the sediment and water that need to be empirically determined. Winterwerp suggested a reasonable value of $F_{y} = 10^{-10}$ N for estuarine flocs, and $p=3-n_{f}$ and $q$ to be 0.5, respectively.

** References **

Winterwerp, J. C. (1998). A simple model for turbulence induced flocculation of cohesive sediment. Journal of Hydraulic Research, 36(3):309–326.
