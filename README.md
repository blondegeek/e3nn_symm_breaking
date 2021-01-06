## Code Repository "Finding symmetry breaking order parameters with Euclidean Neural Networks"
This is the code respository for the following paper.
https://journals.aps.org/prresearch/abstract/10.1103/PhysRevResearch.3.L012002

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

### Citing
If you find this repository helpful for your research. Please consider citing the following:
```
@article{Smidt2021,
  doi = {10.1103/physrevresearch.3.l012002},
  url = {https://doi.org/10.1103/physrevresearch.3.l012002},
  year = {2021},
  month = jan,
  publisher = {American Physical Society ({APS})},
  volume = {3},
  number = {1},
  author = {Tess E. Smidt and Mario Geiger and Benjamin Kurt Miller},
  title = {Finding symmetry breaking order parameters with Euclidean neural networks},
  journal = {Physical Review Research}
}

@misc{e3nn_symm_breaking,
  doi = {10.5281/ZENODO.4087189},
  url = {https://zenodo.org/record/4087189},
  author = {Smidt,  Tess},
  title = {Code repository for ``Finding symmetry breaking order parameters with Euclidean neural networks''},
  publisher = {Zenodo},
  year = {2020},
  copyright = {Open Access}
}
```
