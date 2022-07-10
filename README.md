About numkit
============

Home: https://github.com/Becksteinlab/numkit

Package license: BSD-3-Clause

Feedstock license: [BSD-3-Clause](https://github.com/deepmd-kit-recipes/numkit-feedstock/blob/master/LICENSE.txt)

Summary: numerical first aid kit

Development: https://github.com/Becksteinlab/numkit

Documentation: https://pythonhosted.org/numkit/

Current build status
====================


<table><tr><td>All platforms:</td>
    <td>
      <a href="https://dev.azure.com/deepmd-kit-recipes/feedstock-builds/_build/latest?definitionId=&branchName=master">
        <img src="https://dev.azure.com/deepmd-kit-recipes/feedstock-builds/_apis/build/status/numkit-feedstock?branchName=master">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-numkit-green.svg)](https://anaconda.org/deepmodeling/numkit) | [![Conda Downloads](https://img.shields.io/conda/dn/deepmodeling/numkit.svg)](https://anaconda.org/deepmodeling/numkit) | [![Conda Version](https://img.shields.io/conda/vn/deepmodeling/numkit.svg)](https://anaconda.org/deepmodeling/numkit) | [![Conda Platforms](https://img.shields.io/conda/pn/deepmodeling/numkit.svg)](https://anaconda.org/deepmodeling/numkit) |

Installing numkit
=================

Installing `numkit` from the `deepmodeling` channel can be achieved by adding `deepmodeling` to your channels with:

```
conda config --add channels deepmodeling
conda config --set channel_priority strict
```

Once the `deepmodeling` channel has been enabled, `numkit` can be installed with `conda`:

```
conda install numkit
```

or with `mamba`:

```
mamba install numkit
```

It is possible to list all of the versions of `numkit` available on your platform with `conda`:

```
conda search numkit --channel deepmodeling
```

or with `mamba`:

```
mamba search numkit --channel deepmodeling
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search numkit --channel deepmodeling

# List packages depending on `numkit`:
mamba repoquery whoneeds numkit --channel deepmodeling

# List dependencies of `numkit`:
mamba repoquery depends numkit --channel deepmodeling
```




Updating numkit-feedstock
=========================

If you would like to improve the numkit recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`deepmodeling` channel, whereupon the built conda packages will be available for
everybody to install and use from the `deepmodeling` channel.
Note that all branches in the deepmd-kit-recipes/numkit-feedstock are
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

* [@felix5572](https://github.com/felix5572/)

