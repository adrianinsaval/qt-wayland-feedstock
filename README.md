About qt-wayland-feedstock
==========================

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/qt-wayland-feedstock/blob/main/LICENSE.txt)

Home: http://qt-project.org

Package license: LGPL-3.0-only

Summary: QtWayland module

Development: https://github.com/qt/qtwayland/tree/5.15

Documentation: https://wiki.qt.io/QtWayland

The QtWayland module consists of two parts.

Wayland platform plugin --
    Enables Qt applications to be run as Wayland clients.

QtWaylandCompositor API --
    Enables the creation of Wayland compositors using Qt and QtQuick.


Current build status
====================


<table>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-qt--wayland-green.svg)](https://anaconda.org/freecad/qt-wayland) | [![Conda Downloads](https://img.shields.io/conda/dn/freecad/qt-wayland.svg)](https://anaconda.org/freecad/qt-wayland) | [![Conda Version](https://img.shields.io/conda/vn/freecad/qt-wayland.svg)](https://anaconda.org/freecad/qt-wayland) | [![Conda Platforms](https://img.shields.io/conda/pn/freecad/qt-wayland.svg)](https://anaconda.org/freecad/qt-wayland) |

Installing qt-wayland
=====================

Installing `qt-wayland` from the `freecad` channel can be achieved by adding `freecad` to your channels with:

```
conda config --add channels freecad
conda config --set channel_priority strict
```

Once the `freecad` channel has been enabled, `qt-wayland` can be installed with `conda`:

```
conda install qt-wayland
```

or with `mamba`:

```
mamba install qt-wayland
```

It is possible to list all of the versions of `qt-wayland` available on your platform with `conda`:

```
conda search qt-wayland --channel freecad
```

or with `mamba`:

```
mamba search qt-wayland --channel freecad
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search qt-wayland --channel freecad

# List packages depending on `qt-wayland`:
mamba repoquery whoneeds qt-wayland --channel freecad

# List dependencies of `qt-wayland`:
mamba repoquery depends qt-wayland --channel freecad
```




Updating qt-wayland-feedstock
=============================

If you would like to improve the qt-wayland recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`freecad` channel, whereupon the built conda packages will be available for
everybody to install and use from the `freecad` channel.
Note that all branches in the conda-forge/qt-wayland-feedstock are
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

* [@conda-forge/qt-main](https://github.com/orgs/conda-forge/teams/qt-main/)
* [@hmaarrfk](https://github.com/hmaarrfk/)

