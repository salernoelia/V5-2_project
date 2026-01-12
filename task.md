# 10 Rosenzweig–MacArthur Reaction–Diffusion Model

**Description:** To understand where structural stability in predatory-prey systems originates from, in 1963 Rosenzweig and MacArthur suggested that the way in which predators and prey interact must be changed. Besides adding logistic prey growth to the classical Lotka-Volterra model, they assumed a saturating Holling type-II predation term (Holling had classified all predation interactions with prey into three functional types in the 1950s). This modification allowed for more structurally stable dynamics. Here, we analyze the spatial expansion of this model, where spatial diffusion allows predator–prey interactions to take place across heterogeneous landscapes. This model has been used to study the enrichment paradox and spatial predator–prey waves.

$$
u_t = D_u \nabla^2 u + ru \left( 1 - \frac{u}{K} \right) - \frac{\alpha u v}{1 + h u} \tag{57}
$$

$$
v_t = D_v \nabla^2 v + \beta \frac{\alpha u v}{1 + h u} - mv \tag{58}
$$

### Variables and Parameters:

* $u =$ prey density, $v =$ predator density.
* $D_u, D_v =$ diffusion coefficients.
* $r =$ prey intrinsic growth rate.
* $K =$ prey carrying capacity.
* $\alpha =$ attack rate.
* $h =$ handling time factor.
* $\beta =$ conversion efficiency.
* $m =$ predator mortality.

### Typical Parameter Values:

* $D_u \sim 0.1 \text{--} 1 \text{ m}^2/\text{d}, D_v \sim 0.05 \text{--} 0.5 \text{ m}^2/\text{d}$.
* $r \sim 0.1 \text{--} 1 \text{ d}^{-1}, K \sim 10^2 \text{--} 10^3 \text{ ind}/\text{m}^2$.
* $\alpha \sim 10^{-3} \text{--} 10^{-2} \text{ m}^2/(\text{ind d}), h \sim 0.01 \text{--} 0.1 \text{ ind}^{-1}$.
* $\beta \sim 0.1 \text{--} 0.5, m \sim 0.01 \text{--} 0.1 \text{ d}^{-1}$.

### References

* Rosenzweig and MacArthur, 1963, The American Naturalist [https://www.jstor.org/stable/2458702](https://www.jstor.org/stable/2458702)
* Grunert et al., 2021, Proceedings of the National Academy Sciences [https://doi.org/10.1073/pnas.2017463118](https://doi.org/10.1073/pnas.2017463118)
* Cantrell & Cosner (2003). *Spatial Ecology via Reaction–Diffusion Equations*. Wiley.
* Begon and Townsend (2021), *Ecology: From Individuals to Ecosystems*
