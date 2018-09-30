About r-mbess
=============

Home: http://nd.edu/~kkelley/site/MBESS.html

Package license: GPL-2 | GPL-3

Feedstock license: BSD 3-Clause

Summary: Implements methods that useful in designing research studies and analyzing data, with  particular emphasis on methods that are developed for or used within the behavioral,  educational, and social sciences (broadly defined). That being said, many of the methods  implemented within MBESS are applicable to a wide variety of disciplines. MBESS has a  suite of functions for a variety of related topics, such as effect sizes, confidence intervals  for effect sizes (including standardized effect sizes and noncentral effect sizes), sample size planning (from the accuracy in parameter estimation [AIPE], power analytic, equivalence, and  minimum-risk point estimation perspectives), mediation analysis, various properties of  distributions, and a variety of utility functions. MBESS (pronounced 'em-bes') was originally  an acronym for 'Methods for the Behavioral, Educational, and Social Sciences,' but at this  point MBESS contains methods applicable and used in a wide variety of fields and is an  orphan acronym, in the sense that what was an acronym is now literally its name. MBESS has  greatly benefited from others, see <http://nd.edu/~kkelley/site/MBESS.html> for a detailed  list of those that have contributed and other details.



Current build status
====================

[![Linux](https://img.shields.io/circleci/project/github/conda-forge/r-mbess-feedstock/master.svg?label=Linux)](https://circleci.com/gh/conda-forge/r-mbess-feedstock)
[![OSX](https://img.shields.io/travis/conda-forge/r-mbess-feedstock/master.svg?label=macOS)](https://travis-ci.org/conda-forge/r-mbess-feedstock)
[![Windows](https://img.shields.io/appveyor/ci/conda-forge/r-mbess-feedstock/master.svg?label=Windows)](https://ci.appveyor.com/project/conda-forge/r-mbess-feedstock/branch/master)

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-r--mbess-green.svg)](https://anaconda.org/conda-forge/r-mbess) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/r-mbess.svg)](https://anaconda.org/conda-forge/r-mbess) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/r-mbess.svg)](https://anaconda.org/conda-forge/r-mbess) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/r-mbess.svg)](https://anaconda.org/conda-forge/r-mbess) |

Installing r-mbess
==================

Installing `r-mbess` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
```

Once the `conda-forge` channel has been enabled, `r-mbess` can be installed with:

```
conda install r-mbess
```

It is possible to list all of the versions of `r-mbess` available on your platform with:

```
conda search r-mbess --channel conda-forge
```


About conda-forge
=================

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[CircleCI](https://circleci.com/), [AppVeyor](https://www.appveyor.com/)
and [TravisCI](https://travis-ci.org/) it is possible to build and upload installable
packages to the [conda-forge](https://anaconda.org/conda-forge)
[Anaconda-Cloud](https://anaconda.org/) channel for Linux, Windows and OSX respectively.

To manage the continuous integration and simplify feedstock maintenance
[conda-smithy](https://github.com/conda-forge/conda-smithy) has been developed.
Using the ``conda-forge.yml`` within this repository, it is possible to re-render all of
this feedstock's supporting files (e.g. the CI configuration files) with ``conda smithy rerender``.

For more information please check the [conda-forge documentation](https://conda-forge.org/docs/).

Terminology
===========

**feedstock** - the conda recipe (raw material), supporting scripts and CI configuration.

**conda-smithy** - the tool which helps orchestrate the feedstock.
                   Its primary use is in the construction of the CI ``.yml`` files
                   and simplify the management of *many* feedstocks.

**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


Updating r-mbess-feedstock
==========================

If you would like to improve the r-mbess recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/r-mbess-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string)
   back to 0.
