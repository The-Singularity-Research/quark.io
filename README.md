# quark.io

A graph/lattice based approach to nuclear physics with the goal of improving efficiency in nuclear fusion and fission models for clean and sustainable energy production

### Triangulations and Trivalent Graphs of Quarks

To each nuclear particle we associate harmonic oscillator in a parabolic potential well which we can make into a periodic (extended) cogwheel model by using methods in [Surface Algebras I: Dessins D'enfants, Surface Algebras, and Dessin Orders](https://arxiv.org/abs/1810.06750) and [Surface Algebras and Surface Orders II: Affine Bundles on Curves](https://arxiv.org/abs/1812.00621) to extend t'Hooft's cogwheel model of [quantum cellular automata](https://arxiv.org/abs/1405.1548) pg. 23. Think of this extended cogwheel as an infinite covering of t'Hooft's cogwheels. 

*In the continuum limit (for higher dimensional qudits) this becomes an infinite covering of the circle. A restriction to discretized Planck time may be prudent in which case the partition of the circle would either be finite if the radius is such that the planck length angle divides the circumference evenly, or it would become an irrational rotation algebra otherwise.*


##Hexagon and Triangulated Hexagon Game of Life
---

Here are some references for John Horton Conway's Game of Life on a hexagonal or triangulated hexagonal mesh. Allowing for arbitrary embeddings of triangulated hexagonal meshes into Riemann surfaces shows how we can run Conway's Game of Life on a quantum computer with quarks and gluons as qubits and qutrits if we allow for multi-color cells. Conway's game of life is Turing complete (and of course so is a quantum computer built on qubits and qutrits), so any model of computation can be emulated in this way (quantum or not), and this is in fact one Turing complete classical program running on a Turing complete quantum computer. 

1. [Triangulated Hexagon Mesh Game of Life](https://www.youtube.com/watch?v=VOQrDh6AvYQ&t=230s)

2. [Triangulated Hexagon Mesh Game of Life 2](https://www.youtube.com/watch?v=Y0CCGwl3Sw4)

3. [Multi-spectrum/color Game of Life on Hexagons](https://www.youtube.com/watch?v=eDPmUpboQNA), [see here](http://davidsiaw.github.io/hexlife/), see also [Here](https://davidsiaw.github.io/blog/2014/11/21/hexlife/) and [Here](https://davidsiaw.github.io/blog/2014/11/22/hexlife-part-2/)

4. [Hexagonal Game of Life](https://arunarjunakani.github.io/HexagonalGameOfLife/)

5. [Game of Life on a Torus](https://www.youtube.com/watch?v=lxIeaotWIks)

Turning this into a game where players are allowed to define their own rules for how colors interact with one another allows for an exponentially large game space. Perhaps for example, we could define color windows (intervals in the electromagnetic spectrum) labelled R, G, and B. Defining a cyclic relationship R-->G-->B-->R we have a way of determining what colors can interact with other colors and in what way. Perhaps R is allowed to red-shift green by some fixed or dynamic amount, Green is allowed to red-shift blue, and blue is allowed to blue shift red if we define cutoffs between the infrared and ultraviolet ends of the visible spectrum and treat this as a circle of colors rather than as a linear spectrum. This could be used to define a generalization of something similar to Go or snake with the objective of encapsulating segments of other players' snakes, red or blue shifting the segment to more desirable colors, and then moving to another snake to do the same. The game could be co-op or competative depending on the player defined rules. 

Many other rule-sets for games using this triangulated, multi-color hexagon mesh on arbitrary Riemann surfaces can be defined. Such a game would have applications in visual data representation, quantum information processing, gaming and recreational puzzles, and studying elementary particles such as quarks and gluons. Using guage group equivariant neural networks would allow for a modernized version of alphaGo, and even alphaFold and alphaStar if the data is represented properly in the multi-colored mesh (think of RGB as a 3 dimensional "feature" vector bundle on a Riemann surface, extendable to more colors than just three of course). 



