back to the [list of hypotheses](https://github.com/wds4/tribal-tapestry/blob/main/essays/bookJustification/hypotheses/README.md)

The Object Hypothesis
=====

Constraint nodes are decomposed into properties in a manner designed to facilitate and maximize horizontal integration of the graph.

-----

<div>
  <span style="display:inline-block" >
    <img
      align="top"
      width="45%"
      src="../../images/aPropertyTree.png"
    />
  </span>
  
  <span style="display:inline-block" >
    <img
      align="top"
      width="45%"
      src="../../images/enumeration.png"
    />
  </span>
</div>
Fig A. Decomposition of a constraint (purple square) into a tree of properties (orange diamonds). The "breed" property on the right is only allowed to have two values: Sheep Dog and Irish Setter, because those are the only two Dog Breeds that exist in the local database. We introduce a fourth edge type, the enumeration edge (blue arrow) to achieve horizontal integration of the concepts of Dog Breed and Dog.

<span style="display:inline-block" >
  <img
    width="100%"
    src="../../images/aConceptGraph.png"
  />
</span>
Fig. X. Vertical and horizontal integration of 3 concepts.

- Dog Breed and Irish Setter are connected vertically by the *path termination* edge (red arrow).
- Dog and Irish Setter are connected vertically by the *path propagation* edge (grey arrow).
- Dog Breed and Dog are connected horizontally by the enumeration arror (blue arrow).
  
