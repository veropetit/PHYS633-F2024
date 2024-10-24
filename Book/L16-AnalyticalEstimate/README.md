# L16 Analytical Estimate

Week 9, Thursday


## Material covered and references



We started making our first approximation that the opacity doesn't depend on wavelength (called the "grey" case). From this we found some simple relations between $\tilde{J}$, $\tilde{F}$, $\tilde{S}$, and $\tilde{K}$, but we are still short one equation. 

> In the [textbooks](../CourseInformation/textbooks.md):
> 
>* Gray chap 7
>* Leblanc  4.2 (note that Leblanc uses $H = F/4\pi$)



---

* We considered the case were the optical depth is very large (called the Eddington approximation). 

* Mathematically, we decomposed the source function at a Taylor expansion, kepping only the first term because tau is very large. The other mathematical approximation we did was that instead of integrating from $\tau$ to $\infty$, we only go from $\tau$ to $\tau+\tau$, which we found a good approximation for large $\tau$. By doing a change of variable for $x$ being the "distance from" $\tau$ ($x = |\tau' -\tau|$), it enables us to combine both integral together, greatly simplifying the math. 

> In the [textbooks](../CourseInformation/textbooks.md):
> 
>* Leblanc 3.8 
