# L02 Gravity Field

Week 1, Thursday

Notebook: 02-GravityField.ipynb (see next item)

Slides shown in class: (see next items)

## Material covered and references

<font color="red">S2022: we first finished the hydro timescale from Tuesday</font>

We first discussed two mathematical concepts that will be very important in this course:

1. The number of quantities that can be determined or constrained depends on the number of equations we have.
2. In this course we will always be doing definite integrals
meaning that $\int_1^2 dF = F_2 - F_1$. When solving differential equation by integration (means taking the integral on both sides of the equation), the integral bounds need to match physically (for example, we are integrating equation from the center of the star to the surface of the star). The bounds won't necessarily
have the same value on each side of the equation. 

---

We discussed the gravity field inside of a star, and introduced out first "Differential equation" called the "continuity equation":

$$ \frac{dM_r(r)}{dr} = 4 \pi \rho(r) r^2. $$

We cannot yet solved this equation, because we have too many unknowns. We will need more physics (and associated equations). 

Micro-objectives:
- I can explain (with words and sketches) the relation between the gravitational acceleration and the enclosed mass.
- I can write the integral form of the equation for the enclosed mass ($M_r$) in term of the density $\rho(r)$.


---

But we could still explore how $M_r(r)$ and $g(r)$ would behave if we make a guess about the density vary inside of the star ($\rho(r)$). 

This allows us to practice integrating these differential equations, how to set the bounds of the integrals, and working with unit-less integral and 'scaled' quantities (i.e. using $x=r/R_\star$)

Micro-objectives:
- [Math]: I can make a change of variable to an integral to make the integrant unit-less.
- I can integrate the equation (with unit-less integrant) for the enclosed mass ($M_r$) when given a functional form for the density $\rho(r)$ and express the results in units of $M_\star$.
- I can compute the central density for a given $M_\star$ and $R_\star$ if given a functional form for $\rho(r)$.
- I can draw a sketch of $M_r/M_\star$ for a constant density and for a density that decreases with radial distance and explain the differences.

- I can compute an expression for $g(r)/g_\star$ as a function of $r$ if given a functional form for $\rho(r)$
- I can analytically find the radius at which $g(r)$ is at its maximum.
- I can draw a sketch of $g(r)/g_\star$ for a constant density and for a density that decreases with radial distance and explain the differences.

---

> In the [textbooks](../textbooks.md):
> 
> * Leblanc 5.2.2
> * McD 2.2
> * Kip 1.1
> * Hansen 1.1, 1.4 

---

