About hklpy2_solvers-feedstock
==============================

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/hklpy2_solvers-feedstock/blob/main/LICENSE.txt)

Home: https://github.com/prjemian/hklpy2_solvers

Package license: LicenseRef-UChicago-Argonne-LLC-License

Summary: Solvers for the hklpy2 diffractometer control package.

Development: https://github.com/prjemian/hklpy2_solvers

Documentation: https://prjemian.github.io/hklpy2_solvers/

# hklpy2_solvers

[![Release](https://img.shields.io/github/v/release/prjemian/hklpy2_solvers)](https://github.com/prjemian/hklpy2_solvers/releases)
[![Tag](https://img.shields.io/github/v/tag/prjemian/hklpy2_solvers)](https://github.com/prjemian/hklpy2_solvers/tags)
[![PyPi](https://img.shields.io/pypi/v/hklpy2_solvers.svg)](https://pypi.python.org/pypi/hklpy2_solvers)
[![Conda Package](https://img.shields.io/badge/package-hklpy2_solvers-green.svg)](https://anaconda.org/channels/conda-forge/packages/hklpy2_solvers/overview)
[![Conda Version](https://anaconda.org/conda-forge/hklpy2_solvers/badges/version.svg)](https://anaconda.org/channels/conda-forge/packages/hklpy2_solvers/overview)
[![Conda Downloads](https://anaconda.org/conda-forge/hklpy2_solvers/badges/downloads.svg)](https://anaconda.org/channels/conda-forge/packages/hklpy2_solvers/overview)
[![Conda Platforms](https://anaconda.org/conda-forge/hklpy2_solvers/badges/platforms.svg)](https://anaconda.org/channels/conda-forge/packages/hklpy2_solvers/overview)
[![Coverage Status](https://coveralls.io/repos/github/prjemian/hklpy2_solvers/badge.svg?branch=main)](https://coveralls.io/github/prjemian/hklpy2_solvers?branch=main)
[![Documentation](https://img.shields.io/badge/docs-blue)](https://prjemian.github.io/hklpy2_solvers/latest/)
[![Ask DeepWiki](https://deepwiki.com/badge.svg)](https://deepwiki.com/prjemian/hklpy2_solvers)
[![License: ANL](https://img.shields.io/badge/license-ANL-brightgreen)](LICENSE)

Solvers for the [hklpy2](https://github.com/prjemian/hklpy2) package.

<table>
    <tr>
        <td>
            <b>Solvers</b>
            <p>
                <a href="https://prjemian.github.io/hklpy2_solvers/latest/geometries.html">Geometries</a>
                · <a href="https://prjemian.github.io/hklpy2_solvers/latest/guide_ad_hoc.html">ad_hoc</a>
                · <a href="https://prjemian.github.io/hklpy2_solvers/latest/guide_diffcalc.html">diffcalc</a>
            </p>
        </td>
        <td>
            <b>User Guide</b>
            <p>
                <a href="https://prjemian.github.io/hklpy2_solvers/latest/guides.html">Guides</a>
                · <a href="https://prjemian.github.io/hklpy2_solvers/latest/install.html">Installation</a>
                · <a href="https://prjemian.github.io/hklpy2_solvers/latest/api/hklpy2_solvers/">API</a>
                · <a href="https://prjemian.github.io/hklpy2_solvers">documentation</a>
                · <a href="https://github.com/prjemian/hklpy2_solvers">source</a>
                · <a href="https://prjemian.github.io/hklpy2_solvers/latest/release_notes.html">Releases</a>
                · <a href="https://prjemian.github.io/hklpy2_solvers/latest/license.html">License</a>
                · <a href="https://prjemian.github.io/hklpy2_solvers/latest/genindex.html">Index</a>
            </p>
        </td>
    </tr>
</table>

Current build status
====================


<table><tr>
    <td>All platforms:</td>
    <td>
      <a href="https://github.com/conda-forge/hklpy2_solvers-feedstock/actions/workflows/conda-build.yml">
        <img src="https://github.com/conda-forge/hklpy2_solvers-feedstock/actions/workflows/conda-build.yml/badge.svg?event=push&branch=main">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-hklpy2__solvers-green.svg)](https://anaconda.org/conda-forge/hklpy2_solvers) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/hklpy2_solvers.svg)](https://anaconda.org/conda-forge/hklpy2_solvers) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/hklpy2_solvers.svg)](https://anaconda.org/conda-forge/hklpy2_solvers) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/hklpy2_solvers.svg)](https://anaconda.org/conda-forge/hklpy2_solvers) |

Installing hklpy2_solvers
=========================

Installing `hklpy2_solvers` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
conda config --set channel_priority strict
```

How to use
----------

<details>
<summary>With conda</summary>

```
conda install hklpy2_solvers
```

</details>

<details>
<summary>With mamba</summary>

```
mamba install hklpy2_solvers
```

</details>

<details>
<summary>With pixi</summary>

```
# for adding to your local project
pixi add hklpy2_solvers
# for installing globally
pixi global install hklpy2_solvers
```

</details>

Search package versions
-----------------------

It is possible to list all of the versions of `hklpy2_solvers` available on your platform:

<details>
<summary>With conda</summary>

```
conda search hklpy2_solvers --channel conda-forge
```

</details>

<details>
<summary>With mamba</summary>

```
mamba search hklpy2_solvers --channel conda-forge
```

</details>

<details>
<summary>With pixi</summary>

```
pixi search hklpy2_solvers --channel conda-forge
```

</details>

<details>
<summary>With mamba repoquery, which may provide more information</summary>

```
# Search all versions available on your platform:
mamba repoquery search hklpy2_solvers --channel conda-forge

# List packages depending on `hklpy2_solvers`:
mamba repoquery whoneeds hklpy2_solvers --channel conda-forge

# List dependencies of `hklpy2_solvers`:
mamba repoquery depends hklpy2_solvers --channel conda-forge
```

</details>


About conda-forge
=================

[![Powered by
NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](https://numfocus.org)

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[Azure](https://azure.microsoft.com/en-us/services/devops/), [GitHub](https://github.com/),
[CircleCI](https://circleci.com/), [AppVeyor](https://www.appveyor.com/),
[Drone](https://cloud.drone.io/welcome), and [TravisCI](https://travis-ci.com/)
it is possible to build and upload installable packages to the
[conda-forge](https://anaconda.org/conda-forge) [anaconda.org](https://anaconda.org/)
channel for Linux, Windows and OSX respectively.

To manage the continuous integration and simplify feedstock maintenance,
[conda-smithy](https://github.com/conda-forge/conda-smithy) has been developed.
Using the ``conda-forge.yml`` within this repository, it is possible to re-render all of
this feedstock's supporting files (e.g. the CI configuration files) with ``conda smithy rerender``.

For more information, please check the [conda-forge documentation](https://conda-forge.org/docs/).

Terminology
===========

**feedstock** - the conda recipe (raw material), supporting scripts and CI configuration.

**conda-smithy** - the tool which helps orchestrate the feedstock.
                   Its primary use is in the construction of the CI ``.yml`` files
                   and simplify the management of *many* feedstocks.

**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


Updating hklpy2_solvers-feedstock
=================================

If you would like to improve the hklpy2_solvers recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/hklpy2_solvers-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks, and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@prjemian](https://github.com/prjemian/)

