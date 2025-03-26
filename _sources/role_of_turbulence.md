# The importance of turbulence in the ocean

The ocean maintains steady state stratification. 

Without turbulent mixing, the ocean would not be stratified. But how is this stratification maintained? 

```{figure} images/woce.png
:name: fig-woce
:width: 100%
:align: center

WOCE, Section P16, Neutral Density
```

Taking the continuity equation for 1D flow in a steady ocean:

$$
\cancel{u \frac{\partial b}{\partial x}} + \cancel{v \frac{\partial b}{\partial y}} + w \frac{\partial b}{\partial z} \approx \frac{\partial }{\partial z}(K_z \frac{\partial b}{\partial z}),
$$

some diffusion of heat is required to balance the vertical transport of water upwards. 

Walter Munk {cite}`munk_abyssal_1966` took a vertical profile of temperature to 4000 m and, by fitting an exponential curve $f(z,K_z,w)$ to an observed buoyancy profile, deduced the eddy diffusivity, $K_z$, required to maintain the observed stratification ~ 10$^{-4}$ m$^2$s$^{-1}$. This number has since been observed in parts of the ocean, but is known to vary. 

```{figure} images/munk_tprofile.png
:name: fig-munk
:width: 50%
:align: center

Potential temperature and salinity as function of depth (km). Fig 1 of Walter Munks Abyssal Recipes (1966).
```

We know that a characteristic of turbulence is that it is dissipative. This means that turbulence requires an energy supply. 

How much energy is required to maintain Munk's predicted eddy diffusivity in the deep ocean?

If:

$$
E = \rho K_z N^2 A h ,
$$

where $\rho = 1000$  kgm$^3$ is a characteristic density, $K_z = $10$^{-4}$ $m^2s^{-1}$ is eddy diffusivity, $N^2 = 10^{-5}$ s$^{-2}$ is stratification, $A = 3.6 x 10^14$  m$^2$, is the surface area of the ocean below 1000 m and $h = 4800 $   m, the thickness of the ocean below 1000 m. 

$$
E \approx 1.7 \times 10^{12} \ \mathrm{W} = \mathbf{1.7} \ \mathrm{TW}
$$

Where does this energy come from?

```{figure} images/energy_sources.png
:name: fig-energy
:width: 100%
:align: center

Budget of energy flux to the deep ocean. Adapted and updated from {cite}`munk_abyssal_1998`.
```