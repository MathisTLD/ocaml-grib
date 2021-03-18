## ocaml-grib - OCaml bindings to the ECMWF's GRIB API and NCEP's g2clib

[GRIB API][gribapi] and [g2clib][] are a libraries for reading and writing
GRIB edition 1 and 2, commonly used for meteorological data.

These OCaml bindings are distributed under the MIT license.

[gribapi]: https://software.ecmwf.int/wiki/display/GRIB/Home
[g2clib]: http://www.nco.ncep.noaa.gov/pmb/codes/GRIB2/

## Usage

install with `make install`

## Requirements

we use oasis here to generate setup.ml, configure, Makefile

```bash
opam install oasis
```

- pcre.h

```bash
brew install pcre
```

- grib_api.h

```bash
brew install eccodes
```
