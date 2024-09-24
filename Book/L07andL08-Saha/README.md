# L07 and L08 Saha Equations Part 1 and Part 2

Week 4, Tuesday and Thursday

Notebook will be used on Thursday. 

## Material covered and references

We found out that to calculate the mean molecular weight precisely, we also need to know the degree of ionization of each elements. To do so, we need to do some Stat Mech. 

In the text below, I will use an analogy to illustrate the whole concept. 
1. Atoms are like building, where the floors corresponds to the various energy levels that the electrons can occupy. For each "floor", there are a certain number of apartemnts that the electrons can occupy: this corresponds to the multiplicity of the energy levels (for example, only 2 electrons could fit in the ground state of a neutral hydrogen atoms, 8 could fit in the first excited energy level, etc.)
2. Different ions (neutral H, neutral helium, helium+, neutral carbon, carbon+, etc) will have different types of buildings. The floors (energy levels) and the number of apartments (multiplicity of the levels) will be different, but known. 
4. The "ground state" is the electron confguration with the least energy. In our analogy, it means that all of the electrons occupy the lowest possible energy levels, or in other words they all occupy apartments in their atom building that are the closest possible to the basement. 
3. Ultimatly, we want to know how many building of each type (He+, He0, etc etc) that we have in our gas -- no matter on which floors the electrons in that building live. 

* We need to use first the concept of Boltzmann factor that describes the probability of finding a particle in one of its energy state. In a large ensemble of particle, the fraction of particle in a given state becomes equal to this probability
* We also need to find out the possible states for the free electron that results from the ionization. This is when we need to use the uncertainty principle. For this we find that we can put only 2 electrons (of opposite spin) in a "quantum box" of size $dVd^3p\approx h^3$.

> In the [textbooks](../CourseInformation/textbooks.md):
> 
>* For this part, I suggest looking into the undergrad Thermo/StatMech book by Schroeder (2.5, 6.7). 
>* You can also find a nice description in "Astrophysical Concepts" by Martin Harwitt, 4.11

---

Here are the steps to find the Saha equation that relates the number of atoms (so building of a given type) (for a given element) in two adjacent ionization levels:

1. Using the Boltzmann factor for each type of building (ionization level), we can find the relation between the number of buildings (atoms) with their electron tenants in the basement (ground state $n_0^r$) and the total number building of that type (atoms in this ionization state $n^r$).  
We did this by building a formula (using the easier case of hydrogen as an example) that said that the total number of buildings was equal to number of buildings with their (sole electron) tenant living in the basement, plus the number of building for with their electron tenant living on the first floor, plus the number of buildign with their electron tenant living on the second floor, etc. 

2. Now, we can look at the removal of single electron from an atom in its ground-state configuration to the next ionization stage also in its ground-state configuration (note: this next ionization stage has also to take into account the state (energy and multiplicity) of the ejected electron). In our analogy, the expression we found was the relation between the number of atom building of type e.g. He0 with all of the electron living in the basement and the number of atom buildings of type He+ will all of the electron living in the basement. 

3. We can combine all the equations found in 1 and 2 to get a single relation between $n^r$ and $n^{r+1}$, called the Saha equation. In our analogy using He0 and He+ as an example, Part 1 gave us an equation that gives us the total number of buildings of type He0 if we know the number of buildings of type He0 for which the electron tenants live in the basement, and a similar equation for the buildings of type He+. We replaced in the equation in part 2, et voila!

Micro-objectives:
* I can explain the notation we use for representing the ionization and excitation state of an atom
* I can relate the ionization fraction ($y_i$) of one element with the concentration fractions.
* I can explain why the StatMech expression for the ionization reaction contains the multiplicity of the free electron.
* In the expression for $\frac{n_{r+1}}{n_r}P_e$, I can explain the meaning of all the terms (and where they came from in the derivation). 

> In the [textbooks](../CourseInformation/textbooks.md):
> 
>* My favorite derivation is in the Kip 14.1
>* Leblanc 1.5
>* Hansen 3.4
>* McD Chap.7

---

We want to use the Saha equations to find the number of elements in each ionization stage of each elements present in a gas. 

With a bit of math, we can setup 3 sets of equations with three sets of unknowns.

For the case of hydrogen, we analytically solved this set of equation. We will see during next lecture what do to if we have multiple ionization stages, and multiple elements.

Micro-objectives:
* I can explain the various conditions that will favor/disfavor high ionization

> In the [textbooks](../CourseInformation/textbooks.md):
> 
>* Kip 14.2

---

We will discuss briefly an issue with the partition function, which goes to infinity is we consider an infinite number of energy level. We fix this problem by invoking a maximum bound energy level, that will depend on the pressure. The physical basis of this "fix" is that for a non-isolated atom, the energy levels with very large energy will be perturbed by the presence of nearby charges (resulting in "pressure ionization" in the most extreme cases).

Micro-objectives:
* I can explain why we need to truncate the partition functions (conceptually, and numerically)

> In the [textbooks](../CourseInformation/textbooks.md):
> 
>* McD has a good description of pressure ionization in chap. 7.
>* Also in Kip 14.6

---

Now, we look at what these equations will look like if you have a mixture of various elements, each of which can have more than one ionization stage. I demonstrated the case of H + He. 

We found out that if one knew $E = n_e/n_\mathrm{ion}$, the set of equation "1" through "2" is linear. Therefore we use linear algebra to solve for the ionization fractions $x$, and put them in equation "3" (charge conservation that relates $E$ with the ionization fractions $x$ and the known mass fractions $X$) to calculate the $E$ associated with our resulting ionization fractions. If the $E$ we get from equation #3 is different than the one we assumed at the start, it means that our estimate was wrong, and we can keep trying different values of $E$ until we find the right one!

Micro-objectives:

* I can explain the meaning of $E$ and its minimum and maximum expected value for hydrogen only and for a mixture of hydrogen and helium. 
* I can apply the iterative method to solve for the ionization fractions in a mixture of hydrogen and helium.

> In the [textbooks](../CourseInformation/textbooks.md):
> 
>* Kip 14.5 has the best description
