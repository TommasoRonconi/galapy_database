# GalaPy database

This repository contains files used for running the GalaPy library (available at [this URL](https://github.com/TommasoRonconi/galapy), or from the Python Package Index, PyPI).

## Directory structure

Files are divided per category:

- Cosmologies:
  * Planck 2015
  * Planck 2018
  * WMAP7
  * WMAP9
- filters (data downloaded from [SVO - Filter Profile Service](http://svo2.cab.inta-csic.es/theory/fps/))
- SSP:
  * PARSEC22
  * [Bruzual&Charlot, 2003](https://doi.org/10.1046/j.1365-8711.2003.06897.x)
- AGN\_templates:
  * [Fritz et al., 2006](https://doi.org/10.1111/j.1365-2966.2006.09866.x)
- IGM:
  * [Inoue et al. 2014](https://doi.org/10.1093/mnras/stu936)
- images

## Download

**PREFERRED DOWNLOAD STRATEGY** is through the dedicated functions and entry-points of the GalaPy library.

Otherwise the user can clone this repository and add its location permanently to the database search path:

``` bash
$ git clone https://github.com/TommasoRonconi/galapy_database.git
```

## Change History

- **v0.2.1** (09/02/24) added references to authors of data/models
- **v0.2.0** (28/12/23) new naming convention for SSP tables
- **v0.1.2** (24/10/23) patch solving the bumps in SSP tables
- **v0.1.0** (31/05/23) first upload and release, mainly for testing the download functionalities in GalaPy.
