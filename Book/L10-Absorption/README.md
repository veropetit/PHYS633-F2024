# L10 Absorption

Week 5, Thursday

Notebook: 10-Absorption-template.ipynb

## Material covered and references

We discussed of the relations between intensity and flux in the context of astronomical observations.

If an object can be resolved by a telescope (like for the sun), then we are measuring intensity. If propagating in empty space, the intensity does change with distance. If the light from an object is all gathered inside a single resolution element of the telescope, the object is unresolved, and we are measuring flux. Even in empty space, flux decreases with the square of the distance. 

> In the [textbooks](../CourseInformation/textbooks.md):
> 
>* Leblanc 3.3
>* Rybicki 1.2, 1.3
>* Gray Chap 5
>* Mihalas Chap 1 (in the original edition -- the new edition has quantum treatement if you are interested)

---

The goal of radiative transfer is to figure out what happens to the specific intensity as a ray of light goes through matter. 

We talked about the change in intensity due to absorption (pure absorption and/or scattering), and solved the radiative transfer equation for constant density and opacity.

Micro-objective:
- I can list the two different ways that intensity can be lost going through matter
- I can list and describe the factors that contributes to an element of absorption ($dI$)
- I can derive the equation for intensity as a function of position $I(s)$, and I can calculate and sketch it if given a functional form for the characteristics of the matter (e.g. $\rho(s)$, $\kappa(s)$, etc).



> In the [textbooks](../CourseInformation/textbooks.md):
> 
>* Leblanc 3.4 (does both emission and absorption at the same time)
>* Rybicki 1.4
>* Gray Chap.5 and 7 (be careful, the sign of dtau is ambiguous)
>* Mullan 2.3


---

The concept of optical depth -- we combine the effect of density, opacity, and spatial traveled distance into a single quantity. The optical depth $\tau$ is defined to be zero at the observer's position. 

Even though having zero optical depth at the observer might seem to add mathematical complexity for simple problems of intensity through a slab of material, it will prove to be mathematically very useful for propagation of light originating from very large optical depth. To find the emergent intensity one only needs to consider the light emitted inside of the first few optical depths from the observer, as anything emitted behind too many optical depths will be nearly completely absorbed before reaching the surface.

Micro-objectives:
- I can relate the definition of an element of optical depth ($\d\tau$) with the definition of an elements of absorption ($dI$)
- I can derive the equation for the optical depth as a function of position $\tau(s)$, and I can calculate and sketch it if given a functional form for the characteristics of the matter (e.g. $\rho(s)$, $\kappa(s)$, etc).
- I can describe why using optical depth as our “coordinate” system for RT might be advantageous. 

> In the [textbooks](../CourseInformation/textbooks.md):
> 
>* Leblanc 3.4
>* Rybicki 1.4 (be careful, in this textbook the optical depth is measured along the ray)
>* Mullan 2.4

---
Note: Chap 3. of the Leblanc has a large number of RT problems that are all good. 