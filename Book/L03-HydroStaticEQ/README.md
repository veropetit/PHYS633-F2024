# L03 HydroStatic equilibrium

Week 2, Tuesday

Notebook: 03-HydroStaticEQ-template.ipynb (see next item)

Slides shown in class: (see next item)


## Material covered and references

The derivation of the hydrostatic equilibrium equation (through jellyfish physics). 
We still don't have enough equations to solve for the structure of a star (we need to know $M_r(r)$, $\rho(r)$, and $P(r)$, but we only have two equations).

Micro-objectives:
- With words and sketches, I can describe the balances of forces that keeps a small piece in the interior of a star in hydrostatic equilibrium.
- I can transform this balance of forces in terms of density, pressure, and gravitational acceleration to find the differential equation for hydrostatic equilibrium. 
- I can demonstrate (with text and math) that the equations of continuity and hydrostatic equilibrium alone are not enough to solve for the structure of a star. 

> In the [textbooks](../textbooks.md):
> 
> * Leblanc 2.2
> * McD 2.3
> * Kip 2.1
> * Hansen 1.1

---

Before moving on to adding more physics, we first look at what the pressure $P(r)$ would look like if we 
made a guess about what the density looks like inside of a star (in other words, if we guessed a function for $\rho(r)$).

We do this to practice solving differential equations using integration and bournady condition. 
It is important here to realize that the pressure should be null at the "surface" of the star, not at the center.
***(Remember to pay attention to your integral bounds!!)***

As a "what-if?": The Leblanc textbook uses the central pressure as the boundary
condition instead of the surface pressure in the example 5.1 if you are curious. 
This means that on the left side of the integral form of the equation, you will get $P(r)-P_o$. 

Micro-objective:
- I can write the integral form of the hydrostatic equilibrium equation for $P(r)$
- With sketch and words, I can explain the boundary conditions for the integral form of the hydrostatic equation.
- I can integrate the hydrostatic equilibrium equation to find $P(r)/P_c$ as a function of $r$ if given a functional form for $\rho(r)$.
- I can compute the central pressure for a given $M_\star$ and $R_\star$ if given a functional form for $\rho(r)$.
- I can evaluate the quality of our approximation for our guessed functional form for $\rho(r)$ (i.e. constant or radially decreasing density). I can formulate an hypothesis on how we could change our functional form to be closer to reality. 

> In the [textbooks](../textbooks.md):
> 
> * same as above
 
---

Python skills:

* Practice adding curves to graphs, and add legends.
* Learn more about the Astropy Constants and Units packages

## Supplemental problems suggestions:

* Hanson Prob. 1.3 and Leblanc Prob. 5.1 ask some further questions
about the decreasing density model.

* Leblanc Prob. 2.1 asks for $P(r)$ for an atmosphere (pay attention to your boundaries)