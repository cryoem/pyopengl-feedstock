About pyopengl-feedstock
========================

Feedstock license: [BSD-3-Clause](https://github.com/cryoem/eman-feedstock/blob/main/LICENSE.txt)

Home: http://pyopengl.sourceforge.net

Package license: LicenseRef-pyopengl

Summary: Standard OpenGL bindings for Python

Development: https://github.com/mcfletch/pyopengl

Documentation: http://pyopengl.sourceforge.net/documentation/index.html

Current build status
====================


<table><tr>
    <td>All platforms:</td>
    <td>
      <img src="https://img.shields.io/badge/noarch-disabled-lightgrey.svg" alt="noarch disabled">
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-pyopengl-green.svg)](https://anaconda.org/cryoem/pyopengl) | [![Conda Downloads](https://img.shields.io/conda/dn/cryoem/pyopengl.svg)](https://anaconda.org/cryoem/pyopengl) | [![Conda Version](https://img.shields.io/conda/vn/cryoem/pyopengl.svg)](https://anaconda.org/cryoem/pyopengl) | [![Conda Platforms](https://img.shields.io/conda/pn/cryoem/pyopengl.svg)](https://anaconda.org/cryoem/pyopengl) |

Installing pyopengl
===================

Installing `pyopengl` from the `cryoem` channel can be achieved by adding `cryoem` to your channels with:

```
conda config --add channels cryoem
conda config --set channel_priority strict
```

Once the `cryoem` channel has been enabled, `pyopengl` can be installed with `conda`:

```
conda install pyopengl
```

or with `mamba`:

```
mamba install pyopengl
```

It is possible to list all of the versions of `pyopengl` available on your platform with `conda`:

```
conda search pyopengl --channel cryoem
```

or with `mamba`:

```
mamba search pyopengl --channel cryoem
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search pyopengl --channel cryoem

# List packages depending on `pyopengl`:
mamba repoquery whoneeds pyopengl --channel cryoem

# List dependencies of `pyopengl`:
mamba repoquery depends pyopengl --channel cryoem
```




Updating pyopengl-feedstock
===========================

If you would like to improve the pyopengl recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`cryoem` channel, whereupon the built conda packages will be available for
everybody to install and use from the `cryoem` channel.
Note that all branches in the cryoem/pyopengl-feedstock are
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

* [@almarklein](https://github.com/almarklein/)
* [@mcfletch](https://github.com/mcfletch/)
* [@tadeu](https://github.com/tadeu/)

