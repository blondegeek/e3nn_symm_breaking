## Code Repository "Finding symmetry breaking order parameters with Euclidean Neural Networks"

### Requirements
* `torch`
* `pymatgen`
* `torch_geometric`
* `e3nn`


### Notebooks
`square_to_rectangle.ipynb`
  * Demonstrates how E(3)NNs exhibit Curie's principle and that the gradients of the network can be used to find symmetry breaking input
    
`perovskite_order_parameters_determine_irreps.ipynb`
  * Determines the irreps needed to describe octahedral distortions in perovskites in space group Pnma (62).

`perovskite_order_parameters_spacegroup_74_from_62.ipynb`
  * Recovers an intermediate structure in space group 74 from input in space group 221 and output in space group 62.

`perovskite_order_parameters_with_explicit_k.ipynb`
  * Recovers pseudovector order parameters for structure in space group 62 using explicit k-vectors.
