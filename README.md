# cgem-schism

cgem-schism


## Compile and run CGEM and make basic plots
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/lisalenorelowe/cgem-schism.git/HEAD?labpath=cgem.ipynb)


## Run CGEM with different temperatures
Shows how to change an input with f90nml command.  (not finished at all...beware.)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/lisalenorelowe/cgem-schism.git/HEAD?labpath=cgem_testing.ipynb)


### Random, so I don't need to look up the command later...
f2py -c rnitrate.F90 --f77exec=/rsstu/users/l/lllowe/cgem/cgem_schism/env_f90/bin/gfortran
