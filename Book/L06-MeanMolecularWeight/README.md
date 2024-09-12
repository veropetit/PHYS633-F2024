# L05 Mean molecular weight

Week 3, Thursday



## Material covered and references

Now we want to consider more realistic models where the pressure is described by e.g. the ideal gas law (we will talk about other sources of pressure later on in the course). The ideal gas pressure is a function of the concentration of free particles (which includes free electrons!). However, the equation for hydrostatic equilibrium is a function of density.

We therefore relate the concentration of free particle with the density using a quantity called the mean molecular weight ($\mu$). The mean molecular weight conceptually represents the mean mass (in units of the mass of one hydrogen atom $m_H$) per free particle. The mean molecular weight thus depends on:

* The distribution of element abundances (usually measured in mass fraction $X_i$)
* The ionization level of each element ($y_i$) -- we will see how this is highly dependent on temperature in the next class meeting

> In the [textbooks](../textbooks.md):
> 
>* Leblanc 5.6.2 
>* McD 2.5 (fully ionized only)
>* Kip 13.1

---

We defined two mean molecular weights

* $\mu_\mathrm{ion}$, which is the mean mass (in  units) per ion 
* $\mu_\mathrm{e}$, which is the mean mass (in $m_H$ units) per free electron (note, all the mass is coming from the ions -- if you have 10 hydrogen atoms, and only two of them are ionized, then you have 10 $m_H$ / 2 free electron, and $\mu_e=5$).

The mean molecular weight per free particle is then:

$$\frac{1}{\mu} = \frac{1}{\mu_\mathrm{ion}} +\frac{1}{\mu_\mathrm{e}}$$

In your notebook, we found out how to calculate the mean molecular weight given a known distribution of abundances for each element, in the completely neutral and completely ionized cases. 

> In the [textbooks](../textbooks.md):
> 
>* Leblanc 5.6.2
>* Hansen 1.4.1
 
---

In astronomy, we often refer to the abundance of elements in terms of their mass fraction. We also usually refer to the mass fraction of hydrogen by $X$, the mass fraction of helium by $Y$, and the mass fraction of everything else by $Z$ (also called the "metallicity"). In class I pointed out that we can write an approximation to calculate the mean molecular weight based on $X$, $Y$ and $Z$, instead of the complete calculation. The derivation of these formulas (and the approximations made) are in the textbooks

> In the [textbooks](../textbooks.md):
> 
>* Leblanc, equations 5.126 and 5.127
>* Kip 8.1 for abudances
 
---

Python skills:

* Practice adding scatter points to graph
* Learn about reading data text files
* Practice using a MESA stellar structre file

