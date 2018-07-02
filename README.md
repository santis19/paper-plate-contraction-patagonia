# Paper Title

[![CC BY 4.0][cc-by-shield]][cc-by]

by
Author 1,
Author 2,
etc

This paper has been submitted for publication in *Some Journal*.

## Abstract

abstract


## Downloading the Model

You can download a copy of all the files in this repository by cloning the 
[git](https://git-scm.com/) repository:

    git clone https://github.com/santis19/patagonia-gplates.git

or [download a zip archive](https://github.com/santis19/patagonia-gplates/archive/master.zip)

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

Müller R.D., Seton, M., Zahirovic, S., Williams, S.E., Matthews, K.J., Wright, N.M., Shephard, G.E., Maloney, K.T., Barnett-Moore, N., Hosseinpour, M., Bower, D.J., Cannon, J., 2016. Ocean basin evolution and global-scale plate reorganization events since Pangea breakup, Annual Review of Earth and Planetary Sciences, Vol 44, 107-138. DOI: 10.1146/annurev-earth-

## License

Copyright (c) 2018 Guido Gianni, Santiago R. Soler. Todos los derechos 
reservados.

This work is licensed under a [Creative Commons Attribution 4.0 International 
License][cc-by].

[![CreativeCommons][cc-by-image]][cc-by]


[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20SA%204.0-lightgrey.svg
