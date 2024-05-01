Two Dimensional Density of States
==================================

:date: 2023-10-10
:tags: Physics, Semiconductors
:category: Semiconductors
:title: Two Dimesnional Density of States
:author: Pushkar
:summary: Two Dimensional Density of States

Introduction
-------------

Standard semiconductor physics textbooks define work function somewhat vaguely, 
which only brings out part of the physical significance of the term.

  Work function is the difference between the Fermi level :math:`E_F` and the vacuum level :math:`E_0`, where the vacuum level is the energy state of electrons outside the material.

In this article, we will elaborate on this definition, especially some subtle points on the definition of the **vacuum level**.

Work Function of a Metal
-------------------------

Before moving to semiconductors, we will first consider a metal.
Consider an electron inside a metal at the Fermi level.
Bring this electron *just outside* the metal to *rest*.
The energy required to do so is called the work function of the metal.
The phrase *just outside* is essential.
The final position of the electron should be far enough from the metal so that
it does not experience any force due to its atomic structure.
However, it should be no farther. 
In semiconductor and surface physics, this energy is called the vacuum level.
This definition differs from the definition of *reference* vacuum potential, 
defined for an electron at *infinite* distance from the metal. 
Once the electron is brought outside, it should be at rest and possess no kinetic energy.
Also, if we bring the electron outside the metal, 
there would be some charge separation (as the metal has one less electron now), 
increasing the electrostatic potential of the system.
However, we are not including this minute change in electrostatic potential in the definition now. 
You can think of the electron brought out of the metal more in terms of a *thought experiment*,
than literally taking out the electron.

The electron outside the metal has higher energy than the electron inside the metal.
The metal would have disintegrated if it had been otherwise since an electron in a vacuum has lower energy!
The work function of solids is, therefore, always positive.

Next, let us introduce some macroscopic charges to the metal. 
Introducing macroscopic charge would change its electrostatic potential.
Metals, typically being conductors, are equipotential.
For example, potting a charge :math:`Q` on a spherical conductor of radius :math:`R` 
would increase its electrostatic potential :math:`\phi` to :math:`\frac{Q}{4\pi\epsilon_0R}`.
We know from the basic laws of electromagnetism that electrostatic potential is continuous in nature.
Therefore, if the metal is at an electrostatic potential :math:`\phi`, 
a point *just outside* the metal is also at an electrostatic potential :math:`\phi`.

We want to repeat our thought experiment for this case.
The electrostatic potential of the metal has changed by :math:`\phi`.
This will also change the Fermi level by :math:`-e\phi`. 
But because the electrostatic potential just outside the metal has also changed by :math:`\phi`, the vacuum level also shifts by :math:`-e\phi`,
effectively keeping the work function constant!
Had the vacuum level been defined as infinitely far from the metal, this would not have been the case.
Any change in the electrostatic potential of the metal does not change the electropotential at an infinitely far distance.
Hence, the work function would also change by :math:`-e\phi`.


From this picture, we can clearly understand the reason for a constant work function 
and why the vacuum level closely follows the electrostatic potential of the metal.
Many resources on semiconductor physics present these results as axioms, 
but they follow the proper definition of physical terms!
In the next article, we will take up the case of semiconductors.
