# L04 and L05 Polytropes

Week 2, Thursday and Week 3 Tuesday



## Material covered and references

Derivation of the Lane-Emden equation

So far, we only have two equations for stellar structure: mass continuity, and hydrostatic equilibrium. However, we have 3 unknowns: $M_r(r)$, $P(r)$, and $\rho(r)$. 

We need to find a relation between two of these quantities. The ideal gas law is a relation between $P$ and $\rho$ (called an "equation of state", but it introduced another unknown $T(r)$. To find $T(r)$ we will have to talk about energy transport (later on).  

Micro-objective: 
* I can explain why we need to introduce an “equation of state” to be able to solve the structure of a star. 
* I can explain why using the “ideal gas law” is not the final solution, and how using a “polytropic” equation of state can be used right now as an approximation. 
---

But for know, we can use some useful *polytropic equation of state* where the pressure only depends on the density to a certain power such that 

$$P(r) = K\rho(r)^{\frac{n+1}{n}}$$


**The first step** is to set ourselves up to be able to solve this equation (we will solve for the density). This means:

1. Combine the hydrostatic equilibrium equation and the continuity equation to eliminate $M_r$. 

2. We assume that our solution for the density will have this form: 

$$\rho(r)=\rho_o\theta(r)^n,$$

where theta is a unit-less function that describes the variation of the density as a function of radius. 

3. We can then transform our equations of structure into the well-known Lane-Emden differential equation for polytropes, the solution of which gives $\theta(\epsilon)$, where $\epsilon$ is unit-less and related to $r$.

Micro-objectives: 
* I can identify all of the terms in the polytropic equation of state. 
* I can explain the meaning of the terms in our solution 'shape'.
* I can explain where the $\alpha$ constant we use to normalize the radial coordinate $r$ comes from. 

> In the [textbooks](../textbooks.md):
> 
>* The best one in my opinion is in the Leblanc: Sec 5.4, until eq. 5.93
>* But you can also look in McDo: Chap 9 until eq 9.10, or Hanson Sec. 7.2.1 until eq. 7.26
>* Kip has the derivation in Chap 19 until eq 19.10, but uses a nomenclature different than the other books ($w(z)$ instead of $\theta(\epsilon)$)

---

**The second step** is to analyze the solution, so that we can go from our mathematical $\theta(\epsilon)$ back to $\rho(r)$. 

1. Once we obtain the solution for $\theta(\epsilon)$ for a certain n index, we can use it to determine characteristics of the polytrope. We can find the value of $\epsilon$ at the surface: it is the value of $\epsilon$ where $\theta$ (and therefore the density!) is null! We called this location $\epsilon_1$.

2. From this, we found that we are able to then transform $\theta(\epsilon)$ into $rho/\rho_o$ versus $r/R\star$. We compared this with the real value of $rho/\rho_o$ inside of our Sun. 

Micro-objectives: 
* In a graph of $\theta(\epsilon)$ versus $\epsilon$, I can identify the center and surface of a star. 
* I can transform a graph of $\theta(\epsilon)$ versus $\epsilon$ into a graph of $\rho/\rho_o$ versus $r/R_\star$.

> In the [textbooks](../textbooks.md):
> 
>* Hanson has the best description of the properties of polytropes. 
>
>Table 7.1 also gives values for epsilon_1 and theta'(epsilon_1) for various n.
 
---

**The third and final step** was to go back to $\rho(r)$ (and also $P(r)$ and $M_r(r)$) in real units. 

We found 3 equations that relate $M_\star$, $R_\star$, $P_o$, $\rho_o$, and $K$. As we only have 3 independent equations, this means we if define two of these quantities, we can find the other 3.


For example, you can make equations for $P_o$, $\rho_o$, and $K$ that only depends on $M_\star$ and $R_\star$. 

Another example would be for stars with degenerate matter (we'll talk about this later in the course). In this case $K$ is known from statistical mechanics -- therefore if we pick the mass of the star, the radius, central pressure, and central density are all known. 

Micro-objectives:
* I can explain how the expressions for $R_\star$, $P_o$, and $M_\star$ create a system of 3 equations and 5 unknowns. 
* I can use polytropic models to compare with the Sun’s density profile shape and central density value. 

> In the [textbooks](../textbooks.md):
> 
>Same as above
 
---

Python skills:

* Practice adding curves to graph, and use the astropy units and constant packages
* Learn about functions
* Learn about loops

## Supplemental problems suggestions:

* Leblanc ex. 5.4 shows that a n=0 polytrope represent the constant density case.
* Leblanc Prob. 5.10 