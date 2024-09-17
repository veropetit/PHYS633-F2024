# L07 and L08 Saha Equations Part 1 and Part 2

Week 4, Tuesday and Thursday

Notebook will be used on Thursday. 

## Material covered and references

We found out that to calculate the mean molecular weight precisely, we also need to know the degree of ionization of each elements. To do so, we need to do some Stat Mech. 

* We need to use first the concept of Boltzmann factor that describes the probability of finding a particle in one of its energy state. In a large ensemble of particle, the fraction of particle in a given state becomes equal to this probability
* We also need to find out the possible states for the free electron that results from the ionization. This is when we need to use the uncertainty principle. For this we find that we can put only 2 electrons (of opposite spin) in a "quantum box" of size $dVd^3p\approx h^3$.

> In the [textbooks](../CourseInformation/textbooks.md):
> 
>* For this part, I suggest looking into the undergrad Thermo/StatMech book by Schroeder (2.5, 6.7). 
>* You can also find a nice description in "Astrophysical Concepts" by Martin Harwitt, 4.11

---

Here are the steps to find the Saha equation that relates the number of atoms (for a given element) in two adjacent ionization levels:

1. Using the Boltzmann factor for each ionizations level, we can find the relation between the number of atoms with their electron in the ground state $n_0^r$ and the total number of atoms in this ionization state $n^r$.  
2. Now, we can look at the removal of single electron from an atom in its ground-state configuration to the next ionization stage also in its ground-state configuration (note: this next ionization stage has also to take into account the state (energy and multiplicity) of the ejected electron). 
3. We can combine all the equations found in 1 and 2 to get a single relation between $n^r$ and $n^{r+1}$, called the Saha equation. 

> In the [textbooks](../CourseInformation/textbooks.md):
> 
>* My favorite derivation is in the Kip 14.1
>* Leblanc 1.5
>* Hansen 3.4
>* McD Chap.7

---

We want to use the Saha equation to find the number of elements in each ionization stage of each elements present in a gas. 

With a bit of math, we can setup 3 sets of equations with three sets of unknowns.

For the case of hydrogen, we analytically solved this set of equation. We will see during next lecture what do to if we have multiple ionization stages, and multiple elements.

> In the [textbooks](../CourseInformation/textbooks.md):
> 
>* Kip 14.2

---

We will discuss briefly an issue with the partition function, which goes to infinity is we consider an infinite number of energy level. We fix this problem by invoking a maximum bound energy level, that will depend on the pressure. The physical basis of this "fix" is that for a non-isolated atom, the energy levels with very large energy will be perturbed by the presence of nearby charges (resulting in "pressure ionization" in the most extreme cases).

> In the [textbooks](../CourseInformation/textbooks.md):
> 
>* McD has a good description of pressure ionization in chap. 7.
>* Also in Kip 14.6

---

Now, we look at what these equations will look like if you have a mixture of various elements, each of which can have more than one ionization stage. I demonstrated the case of H + He. 

> In the [textbooks](../CourseInformation/textbooks.md):
> 
>* Kip 14.5 has the best description

---

We found out that if one knew $E = n_e/n_\mathrm{ion}$, the set of equation "1" through "2" is linear. Therefore we use linear algebra to solve for the ionization fractions $x$, and put them in equation "3" (charge conservation that relates $E$ with the ionization fractions $x$ and the known mass fractions $X$) to calculate the $E$ associated with our resulting ionization fractions. If the $E$ we get from equation #3 is different than the one we assumed at the start, it means that our estimate was wrong, and we can keep trying different values of $E$ until we find the right one!

> In the [textbooks](../CourseInformation/textbooks.md):
> 
>* Kip 14.4
