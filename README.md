# ADOpy <img src="https://adopy.github.io/logo/adopy-logo.svg" align="right" width="300px">

[![PyPI](https://img.shields.io/pypi/v/adopy.svg?color=green)](https://pypi.org/project/adopy/)
[![Project Status: Active – The project has reached a stable, usable state and is being actively developed.](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active)
[![Travis CI](https://travis-ci.org/adopy/adopy.svg?branch=develop)](https://travis-ci.org/adopy/adopy)
[![CodeCov](https://codecov.io/gh/adopy/adopy/branch/develop/graph/badge.svg?token=jFnJgnVV1k)](https://codecov.io/gh/adopy/adopy)

**ADOpy** is a Python implementation of Adaptive Design Optimization (ADO; Myung, Cavagnaro, & Pitt, 2013), which computes optimal designs dynamically in an experiment. Its modular structure permit easy integration into existing experimentation code.

ADOpy supports Python 3.6 or above and relies on NumPy, SciPy, and Pandas.

### Features

- **Grid-based computation of optimal designs using only three classes**: `adopy.Task`, `adopy.Model`, and `adopy.Engine`.
- **Easily customizable for your own tasks and models**
- **Pre-implemented Task and Model classes including**:
  - Psychometric function estimation for 2AFC tasks (`adopy.tasks.psi`)
  - Delay discounting task (`adopy.tasks.ddt`)
  - Choice under risk and ambiguity task (`adopy.tasks.cra`)
- **Example code for experiments using PsychoPy** ([link][example-code])

[example-code]: https://github.com/adopy/adopy/tree/master/examples

### Installation

```bash
# Install from PyPI
pip install adopy

# Install from Github (developmental version)
pip install git+https://github.com/adopy/adopy.git@develop
```

### Resources

- [**Getting started**](https://adopy.org/getting-started.html)
- [**Documentation**](https://adopy.org)
- [**Bug reports**](https://github.com/adopy/adopy/issues)

## Citation

If you use ADOpy, please cite this package along with the specific version.
It greatly encourages contributors to continue supporting ADOpy.

> Yang, J., Pitt, M. A., Ahn, W., & Myung, J. I. (2020).
> ADOpy: A Python Package for Adaptive Design Optimization.
> _Behavior Research Methods_, 1--24.
> https://doi.org/10.3758/s13428-020-01386-4

## References
- Myung, J. I., Cavagnaro, D. R., and Pitt, M. A. (2013).
  A tutorial on adaptive design optimization.
  *Journal of Mathematical Psychology, 57*, 53–67.

