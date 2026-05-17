# Electron Orbitals and Their Shapes

## 1. What an electron orbital is

An **electron orbital** is not a tiny path that an electron follows around an atomic nucleus.

An orbital is a **quantum-mechanical wavefunction**, or more precisely a mathematical function related to the probability of finding an electron in different regions of space.

In classical physics, it is tempting to imagine an atom like a miniature Solar System:

- the nucleus is like the Sun,
- electrons are like planets,
- electrons orbit in neat circular paths.

That picture is useful historically, but it is physically wrong.

In quantum mechanics, electrons do not move around the nucleus in sharply defined classical orbits. Instead, an electron bound to an atom is described by a **wavefunction**:


$$

\psi(\mathbf{r},t)

$$


For many atomic orbitals, especially in simple atoms, we often focus on the spatial part:


$$

\psi(\mathbf{r})

$$


The wavefunction itself can be positive, negative, or complex-valued. The measurable quantity is the **probability density**:


$$

|\psi(\mathbf{r})|^2

$$


This tells us the relative probability of detecting the electron near a particular point in space.

So when we draw an orbital shape, we are usually drawing a surface that encloses a high probability region, often something like 90% or 95% of the total electron probability.

An orbital is therefore best understood as a **probability cloud** produced by the rules of quantum mechanics.

---

## 2. Why electrons have orbitals instead of classical orbits

Electrons are quantum objects. They have both particle-like and wave-like behavior.

A classical orbit assumes that the electron has a definite position and a definite velocity at every instant. Quantum mechanics does not allow that level of exactness.

The **Heisenberg uncertainty principle** says:


$$

\Delta x\,\Delta p \geq \frac{\hbar}{2}

$$


where:

- $\Delta x$ is uncertainty in position,
- $\Delta p$ is uncertainty in momentum,
- $\hbar$ is the reduced Planck constant.

If an electron were confined to a perfectly known path, its position and momentum would be too precisely specified. That is not allowed.

Instead, electrons occupy quantum states. These states are solutions to the **Schrödinger equation**.

For an electron in an atom, the time-independent Schrödinger equation is:


$$

\hat{H}\psi = E\psi

$$


where:

- $\hat{H}$ is the Hamiltonian operator, representing total energy,
- $\psi$ is the wavefunction,
- $E$ is the allowed energy of that state.

Only certain wavefunctions satisfy the equation while remaining physically meaningful. Those allowed wavefunctions are the atomic orbitals.

This is why atomic energies are quantized. The electron cannot have just any energy; it can only occupy states that fit the wave-like boundary conditions around the nucleus.

---

## 3. The hydrogen atom as the simplest model

The cleanest orbital shapes come from the hydrogen atom, which has one proton and one electron.

Because hydrogen has only one electron, there are no electron-electron repulsions to complicate the problem. The electron moves in the Coulomb potential of the proton:


$$

V(r) = -\frac{1}{4\pi\epsilon_0}\frac{e^2}{r}

$$


where:

- $e$ is the elementary charge,
- $r$ is the distance from the nucleus,
- $\epsilon_0$ is the vacuum permittivity.

The Schrödinger equation for hydrogen can be solved exactly. Its solutions are called **hydrogenic orbitals**.

These orbitals are labeled using quantum numbers:


$$

n, \ell, m_\ell

$$


Each quantum number describes a different part of the orbital.

For multi-electron atoms, orbital shapes are still often described using hydrogen-like labels such as 1s, 2p, 3d, and 4f, but the actual orbitals are modified by electron-electron interactions, shielding, and effective nuclear charge.

---

## 4. The three main quantum numbers for orbital shape

Atomic orbitals are usually described by three spatial quantum numbers.

### Principal quantum number: $n$

The principal quantum number is:


$$

n = 1, 2, 3, 4, \ldots

$$


It mainly determines the orbital's energy level and overall size.

Larger $n$ generally means:

- the orbital extends farther from the nucleus,
- the electron has higher energy,
- the orbital has more radial structure,
- there may be more radial nodes.

Examples:

- $n=1$: first shell
- $n=2$: second shell
- $n=3$: third shell
- $n=4$: fourth shell

The shell number in labels such as 1s, 2p, and 3d is the value of $n$.

### Angular momentum quantum number: $\ell$

The angular momentum quantum number is:


$$

\ell = 0, 1, 2, \ldots, n-1

$$


It determines the general shape of the orbital.

The common orbital letters correspond to values of $\ell$:

| $\ell$ | Letter | General shape |
|---:|:---:|---|
| 0 | s | spherical |
| 1 | p | dumbbell-shaped |
| 2 | d | mostly clover-shaped |
| 3 | f | more complex multi-lobed shapes |

The letters come from older spectroscopy terms:

- s = sharp,
- p = principal,
- d = diffuse,
- f = fundamental.

After f, the letters continue alphabetically, skipping j:


$$

g, h, i, k, \ldots

$$


In chemistry, s, p, d, and f orbitals are the most important.

### Magnetic quantum number: $m_\ell$

The magnetic quantum number is:


$$

m_\ell = -\ell, -\ell+1, \ldots, 0, \ldots, \ell-1, \ell

$$


It determines the orientation of the orbital in space.

For a given $\ell$, the number of possible orientations is:


$$

2\ell + 1

$$


So:

- s orbitals have 1 orientation,
- p orbitals have 3 orientations,
- d orbitals have 5 orientations,
- f orbitals have 7 orientations.

These orientations correspond to different orbitals within the same subshell.

---

## 5. The electron spin quantum number

A fourth quantum number describes electron spin:


$$

m_s = +\frac{1}{2} \quad \text{or} \quad -\frac{1}{2}

$$


Spin is not literally an electron spinning like a tiny ball. It is an intrinsic quantum property related to angular momentum and magnetic behavior.

Each orbital can hold at most two electrons because of the **Pauli exclusion principle**.

The Pauli exclusion principle says that no two electrons in the same atom can have the exact same set of four quantum numbers:


$$

n, \ell, m_\ell, m_s

$$


Since a single orbital has fixed $n$, $\ell$, and $m_\ell$, it can hold only two electrons, one with spin up and one with spin down.

This is why:

- an s subshell holds 2 electrons,
- a p subshell holds 6 electrons,
- a d subshell holds 10 electrons,
- an f subshell holds 14 electrons.

The formula is:


$$

\text{maximum electrons in a subshell} = 2(2\ell + 1)

$$


---

## 6. Shells, subshells, and orbitals

The words **shell**, **subshell**, and **orbital** are related but not identical.

A **shell** is defined by $n$.

A **subshell** is defined by $n$ and $\ell$.

An **orbital** is defined by $n$, $\ell$, and $m_\ell$.

For example, the 2p subshell has:


$$

n=2, \ell=1

$$


Because $\ell=1$, the possible $m_\ell$ values are:


$$

-1, 0, +1

$$


So the 2p subshell contains three orbitals.

These are commonly drawn as:

- $2p_x$,
- $2p_y$,
- $2p_z$.

Each p orbital can hold two electrons, so the full 2p subshell can hold six electrons.

---

## 7. How orbital names work

An orbital label such as **3d** contains two pieces of information.

The number tells $n$:


$$

3d \Rightarrow n = 3

$$


The letter tells $\ell$:


$$

d \Rightarrow \ell = 2

$$


So a 3d orbital belongs to:

- the third shell,
- the d subshell,
- angular momentum quantum number $\ell=2$.

The possible orbitals in the 3d subshell are five orientations:

- $3d_{xy}$,
- $3d_{xz}$,
- $3d_{yz}$,
- $3d_{x^2-y^2}$,
- $3d_{z^2}$.

Each of these can hold up to two electrons.

---

## 8. Probability density and orbital surfaces

An orbital drawing is usually not a picture of the electron itself.

Instead, it is often a surface of constant probability density or a surface enclosing a chosen percentage of the total probability.

The probability of finding the electron inside a small volume $dV$ is:


$$

dP = |\psi|^2 dV

$$


The total probability of finding the electron somewhere in all space must be 1:


$$

\int |\psi|^2 dV = 1

$$


This is called normalization.

When a textbook shows a p orbital as a dumbbell, it is not saying the electron is only on the surface of the dumbbell. It means the electron is likely to be found in the volume represented by that shape.

The electron is not confined to a hard boundary. The probability density fades gradually and extends infinitely far in principle, though it becomes extremely small far from the nucleus.

---

## 9. Phase: why orbitals have positive and negative lobes

Many orbital diagrams color lobes differently. For example, one lobe may be blue and the other red.

This usually represents the **phase** or sign of the wavefunction, not electric charge.

For example, a p orbital has two lobes with opposite wavefunction signs:


$$

\psi > 0 \quad \text{on one side}

$$


$$

\psi < 0 \quad \text{on the other side}

$$


But probability density is:


$$

|\psi|^2

$$


So both positive and negative regions correspond to positive probability.

Phase matters strongly in bonding. When orbitals overlap:

- same-phase overlap can form bonding combinations,
- opposite-phase overlap can form antibonding combinations.

This is one reason orbital signs are important even though only $|\psi|^2$ directly gives probability density.

---

## 10. Nodes

A **node** is a region where the wavefunction is zero:


$$

\psi = 0

$$


At a node, the probability density is also zero:


$$

|\psi|^2 = 0

$$


There are two main kinds of nodes:

1. **Radial nodes**
2. **Angular nodes**

The total number of nodes in a hydrogen-like orbital is:


$$

\text{total nodes} = n - 1

$$


The number of angular nodes is:


$$

\text{angular nodes} = \ell

$$


The number of radial nodes is:


$$

\text{radial nodes} = n - \ell - 1

$$


These formulas are extremely useful for understanding orbital shapes.

---

## 11. Radial nodes

A **radial node** is a spherical shell around the nucleus where the wavefunction equals zero.

At a radial node, the electron has zero probability of being found at that radius.

The number of radial nodes is:


$$

n - \ell - 1

$$


Examples:

### 1s orbital

For 1s:


$$

n=1, \ell=0

$$


Radial nodes:


$$

1 - 0 - 1 = 0

$$


So 1s has no radial nodes.

### 2s orbital

For 2s:


$$

n=2, \ell=0

$$


Radial nodes:


$$

2 - 0 - 1 = 1

$$


So 2s has one radial node.

This means the 2s orbital has an inner spherical region and an outer spherical region separated by a spherical node where the probability density is zero.

### 3s orbital

For 3s:


$$

n=3, \ell=0

$$


Radial nodes:


$$

3 - 0 - 1 = 2

$$


So 3s has two radial nodes.

Higher s orbitals still look spherical overall, but they contain more radial layers.

---

## 12. Angular nodes

An **angular node** is a plane, cone, or more complicated angular surface where the wavefunction equals zero.

The number of angular nodes is:


$$

\ell

$$


Examples:

### s orbitals

For s orbitals:


$$

\ell = 0

$$


So s orbitals have zero angular nodes.

That is why they are spherical.

### p orbitals

For p orbitals:


$$

\ell = 1

$$


So p orbitals have one angular node.

For a $p_z$ orbital, the angular node is the xy-plane.

The wavefunction is positive on one side of the nucleus and negative on the other side, with zero probability in the nodal plane.

### d orbitals

For d orbitals:


$$

\ell = 2

$$


So d orbitals have two angular nodes.

These nodes create the clover-like or donut-and-dumbbell shapes of d orbitals.

### f orbitals

For f orbitals:


$$

\ell = 3

$$


So f orbitals have three angular nodes.

This leads to more complex multi-lobed shapes.

---

## 13. The s orbitals

An **s orbital** has:


$$

\ell = 0

$$


This means s orbitals are spherically symmetric.

The simplest s orbital is 1s.

The 1s orbital is highest in probability density at the nucleus and decreases outward.

The 1s orbital has:

- $n=1$,
- $\ell=0$,
- zero radial nodes,
- zero angular nodes,
- a spherical shape.

The 2s orbital is also spherical, but it has one radial node.

The 3s orbital is also spherical, but it has two radial nodes.

So all s orbitals are spherical, but higher s orbitals have more internal shell-like structure.

A rough conceptual picture:

```text
1s: one spherical probability cloud

2s: inner spherical region, radial node, outer spherical region

3s: inner region, radial node, middle region, radial node, outer region
```

The radial nodes are not physical walls. They are regions where the wavefunction changes sign and the probability density passes through zero.

---

## 14. The p orbitals

A **p orbital** has:


$$

\ell = 1

$$


This means p orbitals have one angular node.

There are three p orbitals in every p subshell:

- $p_x$,
- $p_y$,
- $p_z$.

They are oriented along the x, y, and z axes.

Each p orbital has two lobes separated by a nodal plane through the nucleus.

For example:

- $p_x$ has lobes along the x-axis and a yz nodal plane,
- $p_y$ has lobes along the y-axis and an xz nodal plane,
- $p_z$ has lobes along the z-axis and an xy nodal plane.

The two lobes have opposite phase.

The probability density is zero at the nucleus for p orbitals because the angular part of the wavefunction has a node there.

The first p orbitals appear at $n=2$, because $\ell$ can only go up to $n-1$.

So there is no 1p orbital.

The lowest p orbitals are:


$$

2p_x, 2p_y, 2p_z

$$


---

## 15. The d orbitals

A **d orbital** has:


$$

\ell = 2

$$


This means d orbitals have two angular nodes.

There are five d orbitals in every d subshell:

- $d_{xy}$,
- $d_{xz}$,
- $d_{yz}$,
- $d_{x^2-y^2}$,
- $d_{z^2}$.

Four of these are usually drawn as cloverleaf shapes:

- $d_{xy}$,
- $d_{xz}$,
- $d_{yz}$,
- $d_{x^2-y^2}$.

The fifth, $d_{z^2}$, looks different. It has two lobes along the z-axis and a doughnut-like ring around the middle.

The first d orbitals occur at $n=3$, because $\ell=2$ requires:


$$

n \geq 3

$$


So there is no 1d or 2d orbital.

The lowest d orbitals are the 3d orbitals.

---

## 16. The shapes of the five d orbitals

### $d_{xy}$

The $d_{xy}$ orbital has four lobes between the x and y axes.

Its nodal planes are the xz-plane and the yz-plane.

This means the orbital has zero wavefunction wherever $x=0$ or $y=0$.

### $d_{xz}$

The $d_{xz}$ orbital has four lobes between the x and z axes.

Its nodal planes are the xy-plane and the yz-plane.

### $d_{yz}$

The $d_{yz}$ orbital has four lobes between the y and z axes.

Its nodal planes are the xy-plane and the xz-plane.

### $d_{x^2-y^2}$

The $d_{x^2-y^2}$ orbital has four lobes pointing directly along the x and y axes.

Its nodal planes lie diagonally between the x and y axes.

This orbital is very important in transition-metal chemistry because it points directly at ligands in many square-planar and octahedral coordination environments.

### $d_{z^2}$

The $d_{z^2}$ orbital has two main lobes along the z-axis and a torus around the center.

It is sometimes written as:


$$

d_{3z^2-r^2}

$$


This notation comes from its angular mathematical form.

Although it looks different from the other d orbitals, it still has two angular nodes and belongs to the same d subshell.

---

## 17. The f orbitals

An **f orbital** has:


$$

\ell = 3

$$


This means f orbitals have three angular nodes.

There are seven f orbitals in every f subshell because:


$$

2\ell + 1 = 2(3) + 1 = 7

$$


The first f orbitals occur at $n=4$, because $\ell=3$ requires:


$$

n \geq 4

$$


So there are no 1f, 2f, or 3f orbitals.

The shapes of f orbitals are more complex than s, p, and d orbitals. They can have multiple lobes, rings, and alternating phases.

F orbitals are especially important for lanthanides and actinides.

Because f orbitals are often spatially buried beneath outer s and p orbitals, f-electron chemistry can behave differently from ordinary main-group chemistry.

---

## 18. Why orbital shapes come from angular wavefunctions

For hydrogen-like atoms, the orbital wavefunction can be separated into a radial part and an angular part:


$$

\psi_{n\ell m}(r,\theta,\phi) = R_{n\ell}(r)Y_\ell^m(\theta,\phi)

$$


where:

- $R_{n\ell}(r)$ is the radial wavefunction,
- $Y_\ell^m(\theta,\phi)$ is a spherical harmonic,
- $r$ is distance from the nucleus,
- $\theta$ and $\phi$ describe direction.

The radial part controls how the orbital changes with distance from the nucleus.

The angular part controls the shape and orientation.

This is why:

- all s orbitals are spherical,
- p orbitals have dumbbell shapes,
- d orbitals have clover-like shapes,
- f orbitals are more complex.

The angular functions are called **spherical harmonics**. They are the natural wave patterns on a sphere, similar to how sine waves are natural wave patterns on a line.

---

## 19. Radial distribution function

The probability density $|\psi|^2$ gives probability per unit volume.

But when asking how likely the electron is to be found at a certain distance from the nucleus, we need to account for the volume of a spherical shell.

A shell at radius $r$ has surface area:


$$

4\pi r^2

$$


The radial distribution function is roughly:


$$

P(r) = 4\pi r^2 |R(r)|^2

$$


This tells us the probability of finding the electron at distance $r$, regardless of direction.

This distinction is important.

For the hydrogen 1s orbital, the probability density is largest at the nucleus. However, the radial distribution function is zero at the nucleus because a sphere of radius zero has zero volume.

The most probable radius for the hydrogen 1s electron is the Bohr radius:


$$

a_0 \approx 5.29 \times 10^{-11}\ \text{m}

$$


So:

- maximum probability density for 1s is at the nucleus,
- maximum radial probability for 1s is at $a_0$.

These are not contradictions. They answer different questions.

---

## 20. The Bohr radius

The **Bohr radius** is a natural length scale for atomic orbitals:


$$

a_0 = \frac{4\pi\epsilon_0\hbar^2}{m_e e^2}

$$


Its value is approximately:


$$

a_0 \approx 0.529\ \text{Å}

$$


or:


$$

a_0 \approx 5.29 \times 10^{-11}\ \text{m}

$$


For hydrogen, the 1s orbital has its most probable radius at about one Bohr radius.

Higher orbitals extend farther outward. Roughly, the size of hydrogen-like orbitals increases with $n^2$.

For hydrogen-like ions, the effective orbital size decreases as nuclear charge increases.

A rough scaling is:


$$

\text{orbital size} \sim \frac{n^2 a_0}{Z}

$$


where $Z$ is the nuclear charge for a one-electron ion.

For multi-electron atoms, the scaling is more complicated because inner electrons shield outer electrons from the full nuclear charge.

---

## 21. Effective nuclear charge and shielding

In a multi-electron atom, an outer electron is attracted to the nucleus but repelled by other electrons.

Inner electrons partially block, or **shield**, the outer electron from the full positive charge of the nucleus.

The electron therefore experiences an **effective nuclear charge**:


$$

Z_{\text{eff}}

$$


This is less than the actual nuclear charge $Z$, especially for outer electrons.

Greater effective nuclear charge pulls orbitals closer to the nucleus and lowers their energy.

Shielding helps explain periodic trends such as:

- atomic radius,
- ionization energy,
- electron affinity,
- electronegativity.

Orbitals that penetrate closer to the nucleus feel a larger effective nuclear charge.

This is why, within a given shell, orbital energies in multi-electron atoms often follow the trend:


$$

s < p < d < f

$$


The s orbital penetrates closest to the nucleus, so it is stabilized more strongly.

---

## 22. Penetration

**Penetration** describes how much an orbital's electron density reaches close to the nucleus.

For the same principal shell $n$, penetration generally follows:


$$

s > p > d > f

$$


This means an ns electron can spend more time close to the nucleus than an np, nd, or nf electron in the same shell.

Because s orbitals have no angular nodes, they can have nonzero probability density at the nucleus.

P, d, and f orbitals have angular nodes that force their probability density to zero at the nucleus.

Greater penetration means the electron feels more nuclear attraction and is lower in energy.

This is why 2s is usually lower in energy than 2p in multi-electron atoms, even though they are degenerate in the ideal hydrogen atom.

---

## 23. Degeneracy

Orbitals are **degenerate** when they have the same energy.

In the hydrogen atom, energy depends only on $n$:


$$

E_n = -\frac{13.6\ \text{eV}}{n^2}

$$


So in hydrogen:

- 2s and 2p have the same energy,
- 3s, 3p, and 3d have the same energy,
- 4s, 4p, 4d, and 4f have the same energy.

This degeneracy happens because hydrogen has only one electron and a simple Coulomb potential.

In multi-electron atoms, electron-electron interactions break this degeneracy.

As a result, subshell energies depend on both $n$ and $\ell$.

For example, in many atoms:


$$

2s < 2p

$$


and:


$$

3s < 3p < 3d

$$


Energy ordering in real atoms can become complicated, especially for transition metals and heavier elements.

---

## 24. Orbital filling and electron configuration

Electrons fill orbitals according to several rules.

### Aufbau principle

Electrons generally fill lower-energy orbitals before higher-energy orbitals.

A common approximate filling order is:

```text
1s
2s
2p
3s
3p
4s
3d
4p
5s
4d
5p
6s
4f
5d
6p
7s
5f
6d
7p
```

This order is useful, but it has exceptions.

### Pauli exclusion principle

Each orbital can hold at most two electrons, and they must have opposite spins.

### Hund's rule

When electrons occupy orbitals of equal energy, they usually fill them singly first with parallel spins before pairing.

For example, a p subshell has three orbitals. Three electrons in a p subshell usually occupy separate p orbitals before any one p orbital gets a second electron.

This reduces electron-electron repulsion and produces more stable configurations.

---

## 25. Why 4s fills before 3d but can ionize first

A common confusing point is the relationship between 4s and 3d orbitals.

In many neutral atoms, the 4s orbital fills before the 3d orbital.

However, when transition metals form cations, 4s electrons are often removed before 3d electrons.

This happens because orbital energies are not fixed independent boxes. They change depending on the atom's electron configuration and ionization state.

Before the 3d subshell is populated, 4s can be slightly lower in energy. After 3d electrons are present, the 3d orbitals become more stabilized relative to 4s.

So the simple filling order is a useful guide, not a universal law.

---

## 26. Orbital size and energy

Orbitals with larger $n$ generally extend farther from the nucleus.

For hydrogen-like atoms, energy is determined by:


$$

E_n = -\frac{13.6\ \text{eV}}{n^2}

$$


Higher $n$ means less negative energy, so the electron is less tightly bound.

For example:


$$

E_1 = -13.6\ \text{eV}

$$


$$

E_2 = -3.4\ \text{eV}

$$


$$

E_3 = -1.51\ \text{eV}

$$


As $n$ increases, the electron is farther from the nucleus on average and easier to remove.

In multi-electron atoms, the energy depends on both $n$ and $\ell$, as well as electron-electron repulsions.

---

## 27. Why orbitals have different shapes

Orbital shapes come from standing wave patterns in three dimensions.

A bound electron behaves like a wave confined by the attractive electric field of the nucleus.

Only certain wave patterns fit the atom's boundary conditions. These patterns have different numbers and arrangements of nodes.

The s orbital is the simplest spherical standing wave.

P orbitals are the next angular pattern, with one angular node.

D orbitals are more complex, with two angular nodes.

F orbitals are more complex still, with three angular nodes.

The more angular nodes an orbital has, the more complicated its shape becomes.

This is similar to vibration modes on a drumhead or a sphere:

- the lowest mode is simple,
- higher modes have more nodal lines,
- more nodes mean more complex patterns.

Orbitals are three-dimensional quantum standing waves around the nucleus.

---

## 28. Orbitals are not electron trajectories

The word “orbital” can be misleading because it sounds like “orbit.”

An electron in a p orbital is not moving along a dumbbell-shaped path.

An electron in a d orbital is not traveling around four clover leaves.

The orbital shape describes where the electron is likely to be detected, not the route it takes.

Between measurements, the electron is described by its wavefunction. It does not have a classical path in the same sense that a planet does.

This is one of the major conceptual breaks between classical physics and quantum mechanics.

---

## 29. Measurement and probability

Before measurement, quantum mechanics describes the electron using a wavefunction.

When a position measurement is made, the electron is detected at a specific location.

Repeated measurements on identically prepared atoms build up the orbital probability distribution.

This means an orbital is not observed by watching one electron trace a path. It is inferred from the statistical pattern of many measurements or from effects such as spectra, bonding, and scattering.

The wavefunction gives probabilities, not certainties.

For an electron in an orbital, there are regions of high probability and regions of low or zero probability.

---

## 30. The 1s orbital in detail

The hydrogen 1s orbital is the simplest atomic orbital.

It has:

- $n=1$,
- $\ell=0$,
- $m_\ell=0$,
- spherical symmetry,
- no nodes.

Its wavefunction has the form:


$$

\psi_{1s}(r) = \frac{1}{\sqrt{\pi a_0^3}}e^{-r/a_0}

$$


The probability density is:


$$

|\psi_{1s}(r)|^2 = \frac{1}{\pi a_0^3}e^{-2r/a_0}

$$


This probability density is largest at the nucleus and decreases exponentially outward.

However, the radial probability distribution is:


$$

P(r) = 4\pi r^2 |\psi_{1s}(r)|^2

$$


This is largest at:


$$

r = a_0

$$


So for hydrogen 1s:

- highest density point: nucleus,
- most probable radius: one Bohr radius.

This is a subtle but important distinction.

---

## 31. The 2s orbital in detail

The 2s orbital has:

- $n=2$,
- $\ell=0$,
- one radial node,
- no angular nodes,
- spherical symmetry.

Because it is an s orbital, it is spherical.

But unlike 1s, the 2s orbital has a spherical radial node.

Inside the node, the wavefunction has one sign. Outside the node, it has the opposite sign.

The probability density is zero at the radial node because the wavefunction passes through zero there.

The 2s orbital therefore has an inner region and an outer region.

In multi-electron atoms, the inner penetration of the 2s orbital makes it lower in energy than 2p.

---

## 32. The 2p orbitals in detail

The 2p orbitals have:

- $n=2$,
- $\ell=1$,
- no radial nodes,
- one angular node.

There are three 2p orbitals:

- $2p_x$,
- $2p_y$,
- $2p_z$.

Each has two lobes with opposite phase.

For $2p_z$, the angular part is related to:


$$

\cos\theta

$$


This produces a positive lobe on one side of the xy-plane and a negative lobe on the other side.

At the xy-plane:


$$

\theta = 90^\circ

$$


$$

\cos\theta = 0

$$


So the xy-plane is a nodal plane.

The 2p orbitals are important in covalent bonding, especially in elements such as carbon, nitrogen, and oxygen.

---

## 33. Orbital overlap and chemical bonds

Chemical bonds form when atomic orbitals overlap and electrons occupy molecular orbitals.

When two atoms approach, their atomic orbitals combine to form molecular orbitals.

A simple example is two hydrogen 1s orbitals combining.

They can combine constructively:


$$

\psi_{\text{bonding}} = \psi_A + \psi_B

$$


or destructively:


$$

\psi_{\text{antibonding}} = \psi_A - \psi_B

$$


The bonding combination increases electron density between the nuclei, lowering energy.

The antibonding combination has a node between the nuclei, raising energy.

This gives two molecular orbitals:

- a lower-energy bonding orbital,
- a higher-energy antibonding orbital.

Bond formation depends heavily on orbital shape, phase, symmetry, and overlap.

---

## 34. Sigma and pi bonds

Orbital shapes explain different types of covalent bonds.

### Sigma bonds

A **sigma bond** forms from head-on orbital overlap along the internuclear axis.

Examples:

- s-s overlap,
- s-p overlap,
- p-p head-on overlap,
- hybrid orbital overlap.

Sigma bonds have electron density concentrated along the line connecting the nuclei.

They are usually the first bond formed between two atoms.

### Pi bonds

A **pi bond** forms from side-by-side overlap of p orbitals.

Pi bonds have electron density above and below the internuclear axis.

A double bond usually consists of:

- one sigma bond,
- one pi bond.

A triple bond usually consists of:

- one sigma bond,
- two pi bonds.

The existence of pi bonds depends on the shape and orientation of p orbitals.

---

## 35. Hybrid orbitals

Hybrid orbitals are combinations of atomic orbitals on the same atom.

They are especially useful in chemistry for describing molecular geometry.

Hybridization does not mean orbitals physically mix like liquids. It is a mathematical recombination of orbitals to create new orbitals better aligned with bonding directions.

Common hybridizations include:

| Hybridization | Orbitals mixed | Number of hybrids | Geometry | Approximate angle |
|---|---|---:|---|---:|
| sp | 1 s + 1 p | 2 | linear | 180° |
| sp² | 1 s + 2 p | 3 | trigonal planar | 120° |
| sp³ | 1 s + 3 p | 4 | tetrahedral | 109.5° |
| sp³d | 1 s + 3 p + 1 d | 5 | trigonal bipyramidal | 90°/120° |
| sp³d² | 1 s + 3 p + 2 d | 6 | octahedral | 90° |

Hybrid orbitals help explain why carbon can form four equivalent-looking bonds in methane even though its valence atomic orbitals include one 2s and three 2p orbitals.

---

## 36. sp hybrid orbitals

In sp hybridization, one s orbital and one p orbital combine to make two sp hybrid orbitals.

These two hybrids point in opposite directions.

The geometry is linear:


$$

180^\circ

$$


Examples include atoms in molecules such as:

- carbon dioxide, $\text{CO}_2$,
- acetylene, $\text{C}_2\text{H}_2$.

An sp-hybridized carbon has two unhybridized p orbitals remaining. These can form pi bonds.

This is why acetylene has a carbon-carbon triple bond:

- one sigma bond from sp-sp overlap,
- two pi bonds from p-p overlap.

---

## 37. sp² hybrid orbitals

In sp² hybridization, one s orbital and two p orbitals combine to form three sp² hybrid orbitals.

These orbitals lie in one plane and point 120° apart.

The geometry is trigonal planar.

A common example is ethene, $\text{C}_2\text{H}_4$.

Each carbon in ethene is sp² hybridized.

The carbon-carbon double bond consists of:

- one sigma bond from sp²-sp² overlap,
- one pi bond from side-by-side overlap of unhybridized p orbitals.

The pi bond restricts rotation around the double bond because rotating would reduce p-orbital overlap.

---

## 38. sp³ hybrid orbitals

In sp³ hybridization, one s orbital and three p orbitals combine to form four sp³ hybrid orbitals.

These point toward the corners of a tetrahedron.

The ideal bond angle is:


$$

109.5^\circ

$$


A classic example is methane, $\text{CH}_4$.

Carbon forms four equivalent sigma bonds with hydrogen.

The tetrahedral arrangement minimizes electron-pair repulsion and maximizes separation between bonding regions.

Sp³ hybridization is also used to describe:

- single-bonded carbon atoms in alkanes,
- nitrogen in amines,
- oxygen in water.

However, lone pairs can compress bond angles, as in water and ammonia.

---

## 39. Lone pairs and orbital shape

Lone pairs occupy orbitals too.

In simple VSEPR-style models, lone pairs repel bonding pairs more strongly than bonding pairs repel each other.

For example, water has two O-H bonds and two lone pairs on oxygen.

A simple electron-domain model gives oxygen roughly sp³ electron geometry, but the molecular shape is bent.

The H-O-H bond angle is about 104.5°, smaller than the ideal tetrahedral angle of 109.5°.

Ammonia has three N-H bonds and one lone pair.

Its electron geometry is roughly tetrahedral, but its molecular shape is trigonal pyramidal.

The H-N-H bond angle is about 107°.

Orbital shape, lone-pair repulsion, and molecular geometry are deeply connected.

---

## 40. Molecular orbitals versus atomic orbitals

Atomic orbitals describe electrons in atoms.

Molecular orbitals describe electrons spread over entire molecules.

In molecular orbital theory, electrons are not assigned to a single bond between two atoms. Instead, they occupy orbitals that can extend over multiple nuclei.

A molecular orbital is often written as a linear combination of atomic orbitals:


$$

\psi_{MO} = c_1\psi_1 + c_2\psi_2 + c_3\psi_3 + \cdots

$$


where the coefficients determine how much each atomic orbital contributes.

Molecular orbital theory explains phenomena that simple Lewis structures struggle with, such as:

- the paramagnetism of oxygen,
- delocalized pi systems,
- aromaticity,
- metal-ligand bonding,
- electronic spectra.

Orbital shapes matter because only orbitals with compatible symmetry and energy can overlap effectively.

---

## 41. Delocalized orbitals

Some electrons are not localized between just two atoms.

In molecules with conjugated pi systems, p orbitals overlap across several atoms.

This creates delocalized molecular orbitals.

A classic example is benzene, $\text{C}_6\text{H}_6$.

Each carbon has an unhybridized p orbital. These p orbitals overlap around the ring to create delocalized pi orbitals above and below the plane of the molecule.

The electrons are spread over the ring rather than locked into alternating single and double bonds.

This delocalization stabilizes benzene and is central to aromaticity.

Orbital shape and symmetry explain why benzene is unusually stable.

---

## 42. Orbitals and spectra

Atomic orbitals are connected to spectra because electrons can transition between quantized energy levels.

When an electron absorbs a photon, it can move to a higher-energy state:


$$

\Delta E = h\nu

$$


When it falls to a lower-energy state, it emits a photon with energy:


$$

E_{\text{photon}} = h\nu

$$


The frequency of light is:


$$

\nu = \frac{\Delta E}{h}

$$


This is why atoms emit and absorb specific wavelengths of light.

Orbital energy differences produce spectral lines.

The hydrogen emission spectrum was one of the key clues that electrons in atoms occupy quantized states.

---

## 43. Selection rules

Not every transition between orbitals is equally likely.

Quantum mechanics imposes **selection rules**.

For many electric dipole transitions in atoms, an important rule is:


$$

\Delta \ell = \pm 1

$$


This means transitions such as s to p or p to d are allowed, while s to s transitions are forbidden or much weaker under simple electric dipole rules.

Selection rules come from the symmetry of the orbitals and the interaction between light and matter.

They help explain why some spectral lines are strong and others are weak or absent.

---

## 44. Orbitals in magnetic fields

The magnetic quantum number $m_\ell$ is called “magnetic” because orbital orientations respond to magnetic fields.

In the absence of external fields, orbitals in the same subshell are often degenerate.

For example, the three p orbitals can have the same energy.

A magnetic field can split these energy levels. This is called the **Zeeman effect**.

The splitting occurs because different orbital angular momentum orientations interact differently with the magnetic field.

This provides experimental evidence that angular momentum and orbital orientation are quantized.

---

## 45. Spin-orbit coupling

Electron spin can interact with orbital angular momentum.

This is called **spin-orbit coupling**.

From the electron's perspective, motion around the nucleus creates an effective magnetic field. The electron's spin magnetic moment interacts with this field.

Spin-orbit coupling is especially strong in heavy atoms because their inner electrons move at high speeds near highly charged nuclei.

Spin-orbit effects help explain:

- fine structure in atomic spectra,
- heavy-element chemistry,
- splitting of electronic energy levels,
- some properties of transition metals and lanthanides.

This means the simple orbital picture is often refined by including relativistic effects.

---

## 46. Real orbitals versus complex orbitals

The mathematical hydrogen solutions often use complex spherical harmonics:


$$

Y_\ell^m(\theta,\phi)

$$


Some of these functions are complex-valued.

Textbook orbitals such as $p_x$, $p_y$, and $p_z$ are usually real combinations of complex spherical harmonics.

For example, real p orbitals can be constructed from combinations of $m_\ell = -1, 0, +1$ states.

This is why there can be more than one equally valid way to represent orbitals.

The physical probability density must be real, but the wavefunction itself can be complex.

Complex orbitals are often more natural when discussing angular momentum. Real orbitals are often more intuitive for chemistry and bonding.

---

## 47. Common misconceptions

### Misconception 1: Electrons orbit the nucleus like planets

Electrons in atoms are not tiny planets moving in fixed paths.

They are quantum objects described by wavefunctions.

### Misconception 2: Orbital surfaces are hard boundaries

An orbital drawing does not show a hard edge.

Electron probability extends beyond the drawn shape.

The surface usually encloses a chosen percentage of probability.

### Misconception 3: Different lobe colors mean positive and negative charge

Different colors usually mean opposite wavefunction phase, not opposite electric charge.

The electron always has negative charge.

### Misconception 4: The electron is smeared-out matter

The wavefunction is not simply a literal smeared electron substance.

It is a probability amplitude used to calculate measurement probabilities.

### Misconception 5: Hybrid orbitals are always physically real objects

Hybrid orbitals are useful mathematical constructs.

They describe bonding geometry well in many cases, but molecular orbital theory gives a more complete picture.

### Misconception 6: Orbitals are always occupied

An orbital is an allowed quantum state whether or not an electron occupies it.

Empty orbitals can still matter in bonding, excitation, and reactivity.

---

## 48. Summary of orbital types

| Orbital type | $\ell$ | Number per subshell | Max electrons | General shape | Angular nodes |
|---|---:|---:|---:|---|---:|
| s | 0 | 1 | 2 | sphere | 0 |
| p | 1 | 3 | 6 | dumbbell | 1 |
| d | 2 | 5 | 10 | clover / donut-dumbbell | 2 |
| f | 3 | 7 | 14 | complex multi-lobed | 3 |

The number of orbitals in a subshell is:


$$

2\ell + 1

$$


The maximum number of electrons in a subshell is:


$$

2(2\ell + 1)

$$


The total number of nodes is:


$$

n - 1

$$


The number of radial nodes is:


$$

n - \ell - 1

$$


The number of angular nodes is:


$$

\ell

$$


---

## 49. A useful mental model

A good way to think about orbitals is this:

An electron in an atom behaves like a standing wave around the nucleus.

Only certain wave patterns are allowed.

Each allowed pattern has:

- a size,
- an energy,
- a shape,
- an orientation,
- a number of nodes,
- a phase structure.

The orbital is the mathematical description of that wave pattern.

The square of the wavefunction gives the probability density for detecting the electron.

The shapes we draw are visual summaries of those probability distributions.

---

## 50. The core picture

Electron orbitals are quantum states, not classical paths.

Their shapes come from solutions to the Schrödinger equation.

The principal quantum number $n$ mainly controls size and energy.

The angular momentum quantum number $\ell$ controls shape.

The magnetic quantum number $m_\ell$ controls orientation.

The spin quantum number $m_s$ controls electron spin state.

S orbitals are spherical.

P orbitals are dumbbell-shaped.

D orbitals are mostly clover-shaped, with one donut-and-dumbbell case.

F orbitals are more complex multi-lobed shapes.

Nodes are regions where the probability of finding the electron is zero.

Orbital phases determine how orbitals combine in chemical bonding.

The entire orbital model is one of the central bridges between quantum physics and chemistry.
