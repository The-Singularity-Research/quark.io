# quark.io

A graph/lattice based approach to nuclear physics with the goal of improving efficiency in nuclear fusion and fission models for clean and sustainable energy production

### Triangulations and Trivalent Graphs of Quarks
For some fixed atom decompose the nucleus into quarks representing each proton and neutron of the nucleaus. To each quark associate a (black) trivalent node (with three "half-edges" attached to it). For each quark-quark interaction we create a single white bivalent node/vertex (with two half-edges attached) and glue a single half eadge of each quark in the quark-quark interaction to it. Once this is done for all quark-quark interactions in the atomic nucleaus, a bipartitie graph connecting quarks is formed called a "dessin d'enfant", i.e. a graph cellularly embedded in a compact Riemann surface. 

The bipartite graph ontained in this procedure (ignoring the white nodes for a moment) forms the geometric dual graph to a triangulation of the Riemann surface since each black node is trivalent. So, if it is preferred, triangles may be used in place of trivalent black nodes. 

To each quark we associate harmonic oscillator in a parabolic potential well which we can make into a three periodic (extended) cogwheel model by using methods in [Surface Algebras I: Dessins D'enfants, Surface Algebras, and Dessin Orders](https://arxiv.org/abs/1810.06750) and [Surface Algebras and Surface Orders II: Affine Bundles on Curves](https://arxiv.org/abs/1812.00621) to extend t'Hooft's cogwheel model of [quantum cellular automata](https://arxiv.org/abs/1405.1548) pg. 23. Think of this extended cogwheel as an infinite covering of t'Hooft's cogwheels. 

*In the continuum limit (for higher dimensional qudits) this becomes an infinite covering of the circle. A restriction to discretized Planck time may be prudent in which case the partition of the circle would either be finite if the radius is such that the planck length angle divides the circumference evenly, or it would become an irrational rotation algebra otherwise.*



