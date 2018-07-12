# Transient plate contraction between two simultaneous slab windows: Insights from Paleogene tectonics of the Patagonian Andes

[![CC BY 4.0][cc-by-shield]][cc-by]

by
[Guido Gianni](https://www.researchgate.net/profile/Guido_Gianni),
[Agustina Pesce](https://www.researchgate.net/profile/Agustina_Pesce),
[Santiago Soler](https://www.github.com/santis19)

This paper has been submitted for publication in Journal of Geodynamics.

## Abstract

Plate kinematic reconstructions show that the Farallon-Phoenix (Aluk) 
spreading center subducted under South America sometime between the Late 
Cretaceous and the Paleogene periods.
Geological studies have supported a ridge-trench interaction in Patagonia 
during Paleocene to Eocene times mostly based on the documentation of slab 
window magmatism and Andean arc-quiescence.
However, a revision of most recent works dealing with the Paleogene tectonic 
evolution of Central Patagonia, with emphasis in a key orogenic segment 
between 45°S to 46°30’S, highlights inconsistencies in this model.
Particularly, the existence of two discrete areas with simultaneous slab 
window-related magmatism separated by a sector with plate-wide contraction, 
along with a spatio-temporal mismatch between magmatism location and ridge 
kinematics, preclude a single ridge-trench interaction.
With the purpose to better understand this complex tectonic setting, we 
integrated this updated geological evolution into a plate kinematic model.
Finally, we propose that the oblique collision of a segmented 
Farallon-Phoenix/Aluk mid-ocean ridge would explain the latitudinally variable 
tectonomagmatic evolution of Patagonia during early Paleogene times.


## Downloading the Model

You can download a copy of all the files in this repository by cloning the 
[git](https://git-scm.com/) repository:

    git clone https://github.com/santis19/paper-plate-contraction-patagonia.git

or [download a zip archive](https://github.com/santis19/paper-plate-contraction-patagonia/archive/master.zip)

A copy of the repository is also archived at *insert DOI here*


## Dependencies

In order to being able to see and edit the model you need to download 
and install [GPlates](http://www.gplates.org/), available for Windows, Mac Os 
X and Ubuntu.

Our model was created using
[GPlates 2.0](https://sourceforge.net/projects/gplates/files/gplates/2.0/).


## The Model

To create the new plates model we have modified the one released by
[Müller et.al. (2016)](https://www.earthbyte.org/ocean-basin-evolution-and-global-scale-plate-reorganization-events-since-pangea-breakup/).

The `data` folder contains:

* `muller_et_al_2016_v1.14`: Global Plate Boundaries and 
Rotations model released by Müller et. al. (2016).

* `gianni_et_al_2018`: New plate model created in this paper.

In order to see and edit the new model we need to run GPlates and load the 
following features:

* `data/muller_et_al_2016_v1.14/Global_EarthByte_230-0Ma_GK07_AREPS.rot`: 
Müller et. al. (2016) Plates Rotations.

* `data/muller_et_al_2016_v1.14/Global_EarthByte_230-0Ma_GK07_AREPS_Coastlines.gpml`:
Müller et. al. (2016) Coastlines.

* `data/gianni_et_al_2018/Gianni_et_al_230-0Ma_PlateBoundaries.gpml`:
New Plates Boundaries Model.

By editing the Layers Drawing style you can change how the plates and the 
coastlines are shown.


## References

Müller R.D., Seton, M., Zahirovic, S., Williams, S.E., Matthews, K.J.,
Wright, N.M., Shephard, G.E., Maloney, K.T., Barnett-Moore, N., Hosseinpour,
M., Bower, D.J., Cannon, J., 2016. Ocean basin evolution and global-scale
plate reorganization events since Pangea breakup, Annual Review of Earth and
Planetary Sciences, Vol 44, 107-138.
DOI: [10.1146/annurev-earth-060115-012211](https://www.annualreviews.org/doi/10.1146/annurev-earth-060115-012211)

## License

Copyright (c) 2018 Guido Gianni, Agustina Pesce, Santiago R. Soler.

This work is licensed under a [Creative Commons Attribution 4.0 International 
License][cc-by].

[![CreativeCommons][cc-by-image]][cc-by]


[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
