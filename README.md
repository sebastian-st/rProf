# rProf

Very simple python3 script to create radial profiles of *.FITS images, allowing also to produce a quick plot. The *.FITS standard was developed by NASA for storing astrophysical data.

# Requirements

- astropy
- matplotlib
- numpy

# Usage

```shell
$ chmod +x rProf
$ ./rProf file [options]
```

When not specifying any options, the code exports the data in ascii format to "profile.txt" (column format: "radius value")

(see option --help for a description of options)
