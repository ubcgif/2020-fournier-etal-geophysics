# Sparse magnetic vector inversion in spherical coordinates

_Dominique Fournier, Lindsey J. Heagy and Douglas W. Oldenburg_

https://doi.org/10.1190/geo2019-0244.1

![thumbnail](./paper/thumbnail.png)

## Summary

Magnetic vector inversion has received considerable attention over recent years for processing magnetic field data that are affected by remanent magnetization. However, the magnetization models obtained with current inversion algorithms are generally too smooth to be easily interpreted geologically. To address this, we review the magnetic vector inversion formulated in a spherical coordinate system. We tackle convergence issues posed by the non-linear transformation from Cartesian to spherical coordinates by using an iterative sensitivity weighting approach and a scaling of the spherical parameters. The spherical formulation allows us to impose sparsity assumptions on the magnitude and direction of magnetization independently and, as a result, the inversion recovers simpler and more coherent magnetization orientations. The numerical implementation of our algorithm on large-scale problems is facilitated by discretizing the forward problem using tiled Octree meshes. All of our results are generated using the open-source SimPEG software. We demonstrate the enhanced capabilities of our algorithm on a large airborne magnetic survey collected over the Kevitsa Ni-Cu-PGE deposit. The recovered magnetization direction inside the intrusive and in the host stratigraphy is consistent with laboratory measurements and provides evidence for tectonic deformation.


## Citation

Dominique Fournier, Lindsey J. Heagy, Douglas W. Oldenburg; Sparse magnetic vector inversion in spherical coordinates. Geophysics 2020;; 85 (3): J33–J49. doi: https://doi.org/10.1190/geo2019-0244.1

```
@article{fournier_inversion_2020,
    author = {Fournier, Dominique and Heagy, Lindsey J. and Oldenburg, Douglas W.},
    title = "{Sparse magnetic vector inversion in spherical coordinates}",
    journal = {Geophysics},
    volume = {85},
    number = {3},
    pages = {J33-J49},
    year = {2020},
    month = {03},
    issn = {0016-8033},
    doi = {10.1190/geo2019-0244.1},
    url = {https://doi.org/10.1190/geo2019-0244.1},
}

```
