# L14 Limb Darkening

Week 7, Thursday


## Material covered and references



We applied the formal solution of RT to a semi-infinite, flat atmosphere. We found an expression for the in-going (u<0) and out-going (u>0) rays. 
In the case of the Sun, we are able to measure the emergent intensity $I(\tau = 0,u)$ as a function of $u$. This can therefore be used to constrain the source function $S(\tau)$ and hence the temperature. 

By using a simple approximation that the source function is linear with the optical depth $S(\tau)=S_0+S_1\tau$, we found that $I(\tau=0, u) = S(\tau=u)$. This implies that rays coming from the center of the Sun's projected disk ($u=1$) in the sky are brighter that the rays coming from the sides ($u=0$). This phenomenon is called Limb-Darkening.

Therefore by measuring Limb-Darknening, we can put constrains on the temperature structure at various optical depth. Furthermore, as the optical depth is a function of wavelength, the spatial location of e.g. $\tau=1$ will be different for different wavelengths. Measurements of Limb-Darkening at various wavelengths thus enables a good estimate of the temperature structure of the Sun's atmosphere.  

We worked on a notebook that made a visualization of the stellar disk (as would be viewed in the sky) for stars with various slopes for the dependence of the source function on the vertical optical depth. We then used this visualization to see the effect of limb-darkening on the measurement of a planet transit in front of the star. Of course, this as an approximation -- for example we neglected the slight change in distance due to the curved orbit of the planet, and we made a simple numerical integral over our spatial grid to get the flux that would be observed. 

Micro-Objectives:

* I can derive the expression for the emerging intensity as a function of $u$, if the source function is a linear function of $\tau$. 
* [N] I can sketch and explain the impact of limb-darkening on our view of the visible hemisphere of the sun. 
* [N] I can explain the effect of the slope of the source function on the limb-darkening. 
* [N] I can explain how the transit of a planet in front of a star modifies the total light coming from a star
* [N] I can explain how the shape of a planet transit will be impacted by a diffence in limb-darkening. 

---
