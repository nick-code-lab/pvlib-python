# pvlib-python

<img src="docs/sphinx/source/_images/pvlib_logo_horiz.png" width="600" alt="pvlib-python logo">

<table>
<tr>
  <td>Latest Release</td>
  <td>
    <a href="https://pypi.org/project/pvlib/">
    <img src="https://img.shields.io/pypi/v/pvlib.svg" alt="latest release" />
    </a>
    <a href="https://anaconda.org/conda-forge/pvlib">
    <img src="https://anaconda.org/conda-forge/pvlib/badges/version.svg" />
    </a>
    <a href="https://anaconda.org/conda-forge/pvlib">
    <img src="https://anaconda.org/conda-forge/pvlib/badges/latest_release_date.svg" />
    </a>
</tr>
<tr>
  <td>License</td>
  <td>
    <a href="https://github.com/pvlib/pvlib-python/blob/main/LICENSE">
    <img src="https://img.shields.io/pypi/l/pvlib.svg" alt="license" />
    </a>
</td>
</tr>
<tr>
  <td>Build Status</td>
  <td>
    <a href="https://pvlib-python.readthedocs.org/en/stable/">
    <img src="https://readthedocs.org/projects/pvlib-python/badge/?version=stable" alt="documentation build status" />
    </a>
    <a href="https://github.com/pvlib/pvlib-python/actions/workflows/pytest.yml?query=branch%3Amain">
      <img src="https://github.com/pvlib/pvlib-python/actions/workflows/pytest.yml/badge.svg?branch=main" alt="GitHub Actions Testing Status" />
    </a>
    <a href="https://codecov.io/gh/pvlib/pvlib-python">
    <img src="https://codecov.io/gh/pvlib/pvlib-python/branch/main/graph/badge.svg" alt="codecov coverage" />
    </a>
  </td>
</tr>
<tr>
  <td>Benchmarks</td>
  <td>
    <a href="https://pvlib.github.io/pvlib-benchmarks/">
    <img src="https://img.shields.io/badge/benchmarks-asv-lightgrey" />
    </a>
  </td>
</tr>
<tr>
  <td>Publications</td>
  <td>
    <a href="https://doi.org/10.5281/zenodo.593284">
    <img src="https://zenodo.org/badge/DOI/10.5281/zenodo.593284.svg" alt="zenodo reference">
    </a>
    <a style="border-width:0" href="https://doi.org/10.21105/joss.05994">
    <img src="https://joss.theoj.org/papers/10.21105/joss.05994/status.svg" alt="DOI badge" >
    </a>
  </td>
</tr>
</table>

## Introduction

pvlib-python is a community-developed toolbox that provides a set of
functions and classes for simulating the performance of photovoltaic
energy systems and accomplishing related tasks. The core mission of pvlib-python is to provide open,
reliable, interoperable, and thoroughly-tested implementations of PV system models for researchers, engineers, and analysts working in the solar energy field. Our goal is to make photovoltaic modeling accessible and reproducible for everyone.

## Documentation

Full documentation can be found at [pvlib-python ReadTheDocs](https://pvlib-python.readthedocs.io/en/stable/),
including a comprehensive [Frequently Asked Questions](https://pvlib-python.readthedocs.io/en/stable/user_guide/faq.html) page.

## Installation

pvlib-python releases may be installed using the `pip` and `conda` tools:

```bash
# Using pip
pip install pvlib

# Using conda
conda install -c conda-forge pvlib
```

Please see the [Installation page](https://pvlib-python.readthedocs.io/en/stable/user_guide/installation.html) of the documentation for complete instructions.


## Contributing

We welcome your help to make pvlib-python an even better tool! Whether you're fixing bugs, adding new features, improving documentation, or sharing examples, your contributions are valuable to our community.

Please see the [Contributing page](https://pvlib-python.readthedocs.io/en/stable/contributing/index.html) for more on how you can contribute. We welcome contributions of all kinds, including:

- Code improvements and bug fixes
- Documentation enhancements
- New models and features
- Example notebooks and tutorials
- Testing improvements

The long-term success of pvlib-python depends on substantial community support and involvement.

## Citing

Many of the contributors to pvlib-python work in institutions where
citation metrics are used in performance or career evaluations. If you
use pvlib-python in a published work, please cite:

### Recommended citation for the pvlib-python project

  Anderson, K., Hansen, C., Holmgren, W., Jensen, A., Mikofski, M., and Driesse, A.
  "pvlib-python: 2023 project update."
  Journal of Open Source Software, 8(92), 5994, (2023).
  [https://doi.org/10.21105/joss.05994](https://doi.org/10.21105/joss.05994)

### Recommended citation for pvlib iotools

  Jensen, A., Anderson, K., Holmgren, W., Mikofski, M., Hansen, C., Boeman, L., Loonen, R.
  "pvlib iotools — Open-source Python functions for seamless access to solar irradiance data."
  Solar Energy, 266, 112092, (2023).
  [https://doi.org/10.1016/j.solener.2023.112092](https://doi.org/10.1016/j.solener.2023.112092)

### Historical citation for pvlib-python

  Holmgren, W., Hansen, C., and Mikofski, M.
  "pvlib-python: a python package for modeling solar energy systems."
  Journal of Open Source Software, 3(29), 884, (2018).
  [https://doi.org/10.21105/joss.00884](https://doi.org/10.21105/joss.00884)

If you use pvlib-python in a commercial or publicly-available application, please
consider displaying one of the "powered by pvlib" logos shown below:

<img src="docs/sphinx/source/_images/pvlib_powered_logo_vert.png" width="300" alt="Powered by pvlib vertical logo">&nbsp;&nbsp;&nbsp;<img src="docs/sphinx/source/_images/pvlib_powered_logo_horiz.png" width="300" alt="Powered by pvlib horizontal logo">

## Getting Support

pvlib usage questions can be asked on
[Stack Overflow](https://stackoverflow.com) and should be tagged with
the [pvlib](https://stackoverflow.com/questions/tagged/pvlib) tag.

The [pvlib-python google group](https://groups.google.com/forum/#!forum/pvlib-python)
is used for discussing various topics of interest to the pvlib-python
community. We also make new version announcements on the google group.

If you suspect that you may have discovered a bug, would like to
suggest an enhancement, or propose a new feature for pvlib, please create an issue on our
[GitHub issues page](https://github.com/pvlib/pvlib-python/issues). When creating an issue:

- For bugs: Include a minimal code example that reproduces the problem
- For enhancements: Describe the desired functionality and why it would be valuable
- For new features: Outline the feature and its potential use cases

Be sure to include relevant details that will help maintainers understand and address your request.

## License

pvlib-python is released under the BSD 3-clause license, a permissive open source license that allows for commercial and private use with limited restrictions. See the [LICENSE file](https://github.com/pvlib/pvlib-python/blob/main/LICENSE) for complete details.

## History and Acknowledgement

pvlib-python began in 2013 as a Python translation of the [PVLIB for Matlab](https://github.com/sandialabs/MATLAB_PV_LIB)
toolbox developed by Sandia National Laboratories. pvlib-python has grown substantially since then.
Today it contains code contributions from over a hundred individuals worldwide
and is maintained by a core group of PV modelers from a variety of institutions.

pvlib has been supported directly and indirectly by DOE, NumFOCUS, and
Google Summer of Code funding, university research projects,
companies that allow their employees to contribute, and from personal time.

## NumFOCUS

pvlib-python is a [NumFOCUS Affiliated Project](https://numfocus.org/sponsored-projects/affiliated-projects).

[![NumFOCUS Affiliated Projects](https://i0.wp.com/numfocus.org/wp-content/uploads/2019/06/AffiliatedProject.png)](https://numfocus.org/sponsored-projects/affiliated-projects)
