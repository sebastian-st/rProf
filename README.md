# rProf (beta / testing)

Very simple python3 script to create radial profiles of *.FITS images, allowing also to produce a quick plot. The *.FITS standard was developed by NASA for storing astrophysical data.

Currently available features:
- Compute mean (or median) in radial bins of a given width Δr
- If wished, it computes also the standard deviation
- Allows to specify custom center coordinates (x,y) in which the profile is computed

![Example](http://sebastian.stapelberg.de/documents/rprof.jpg "Example")

# Requirements

- astropy
- matplotlib
- numpy

# Usage

```shell
$ chmod +x rProf
$ ./rProf file [options]
```

When not specifying any options, the code exports the data in ascii format to "profile.txt" (column format: "radius value"). With option "-s", the result is shown in a plot.
