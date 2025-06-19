About py-plumed-metatomic-feedstock
===================================

Feedstock license: [BSD-3-Clause](https://github.com/metatensor/py-plumed-metatomic-feedstock/blob/main/LICENSE.txt)

Home: http://www.plumed.org/

Package license: LGPL-3.0

Summary: Python wrappers for plumed library

Development: https://github.com/plumed/plumed2

Documentation: https://www.plumed.org/doc

PLUMED is an open source library for free energy calculations in
molecular systems which works together with some of the most
popular molecular dynamics engines.


Current build status
====================


<table>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-py--plumed--metatomic-green.svg)](https://anaconda.org/metatensor/py-plumed-metatomic) | [![Conda Downloads](https://img.shields.io/conda/dn/metatensor/py-plumed-metatomic.svg)](https://anaconda.org/metatensor/py-plumed-metatomic) | [![Conda Version](https://img.shields.io/conda/vn/metatensor/py-plumed-metatomic.svg)](https://anaconda.org/metatensor/py-plumed-metatomic) | [![Conda Platforms](https://img.shields.io/conda/pn/metatensor/py-plumed-metatomic.svg)](https://anaconda.org/metatensor/py-plumed-metatomic) |

Installing py-plumed-metatomic
==============================

Installing `py-plumed-metatomic` from the `metatensor` channel can be achieved by adding `metatensor` to your channels with:

```
conda config --add channels metatensor
conda config --set channel_priority strict
```

Once the `metatensor` channel has been enabled, `py-plumed-metatomic` can be installed with `conda`:

```
conda install py-plumed-metatomic
```

or with `mamba`:

```
mamba install py-plumed-metatomic
```

It is possible to list all of the versions of `py-plumed-metatomic` available on your platform with `conda`:

```
conda search py-plumed-metatomic --channel metatensor
```

or with `mamba`:

```
mamba search py-plumed-metatomic --channel metatensor
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search py-plumed-metatomic --channel metatensor

# List packages depending on `py-plumed-metatomic`:
mamba repoquery whoneeds py-plumed-metatomic --channel metatensor

# List dependencies of `py-plumed-metatomic`:
mamba repoquery depends py-plumed-metatomic --channel metatensor
```




Updating py-plumed-metatomic-feedstock
======================================

If you would like to improve the py-plumed-metatomic recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`metatensor` channel, whereupon the built conda packages will be available for
everybody to install and use from the `metatensor` channel.
Note that all branches in the metatensor/py-plumed-metatomic-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@GiovanniBussi](https://github.com/GiovanniBussi/)

