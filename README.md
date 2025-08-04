# spherimatch
[![ascl:2507.022](https://img.shields.io/badge/ascl-2507.022-blue.svg?colorB=262255)](https://ascl.net/2507.022)
[![2025ascl.soft07022H](https://img.shields.io/badge/ADS-2025ascl.soft07022H-blue.svg)](https://ui.adsabs.harvard.edu/abs/2025ascl.soft07022H/abstract)

A Python package for cross-matching and self-matching in spherical coordinates.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Example Usage](#example-usage)
- [API Reference](#api-reference)
- [Contributing](#contributing)
- [Citation](#citation)

## Introduction
`spherimatch` is a Python package designed to perform cross-matching and self-matching in spherical coordinates. This is particularly useful in fields such as astrophysics, geophysics, and any domain where objects are naturally distributed on a spherical surface.
Currently, this package only support astrophysics coordinates `(Ra, Dec)` in degrees. More units and naming convention will be supported in the future.

## Features
- Efficient computation ( $O(N\log N)$ ) of matching problems in spherical coordinates.
- Friends-of-Friends (FoF) analysis in spherical coordinates.
- Duplicate removal in spherical coordinates.
- Easy integration with existing data processing packages, such as `pandas`.

## Installation
Install `spherimatch` by:
```bash
pip install spherimatch
```
See the [installation guide](https://technic960183.github.io/spherimatch/install.html) for more details.

## Example Usage
Before you start, please check out our documentation for a
[quick start](https://technic960183.github.io/spherimatch/index.html#quickstart).

- To perform **cross-matching** between two catalogs, check this
  [cross-matching example](https://technic960183.github.io/spherimatch/tutorial/xmatch.html).
- To **cluster** the objects in a catalog with the Friends-of-Friends (FoF) algorithm, check this
  [clustering example](https://technic960183.github.io/spherimatch/tutorial/fof.html).
- To **remove duplicates** from a catalog, check this
  [duplicate removal example](https://technic960183.github.io/spherimatch/tutorial/duplicates_removal.html).

## API Reference
The full documentation and API reference can be found [here](https://technic960183.github.io/spherimatch/index.html).

## Contributing
If you find any bugs or potential issues, please report it directly to me (via Slack or E-mail), or start an [issue](https://github.com/technic960183/spherimatch/issues).

If you have any suggestions or feature requests, feel free to start an [issue](https://github.com/technic960183/spherimatch/issues).

## Citation
If you find `spherimatch` useful in your research, please consider citing it.

`spherimatch` is registered in the [Astrophysics Source Code Library (ASCL)](https://ascl.net/2507.022), and can be cited using its Bibcode: [`2025ascl.soft07022H`](https://ui.adsabs.harvard.edu/abs/2025ascl.soft07022H/abstract).

Please feel free to use your preferred citation format. For convenience, here is a BibTeX entry:
```bibtex
@software{2025ascl.soft07022H,
       author = {{Hsu}, Yuan-Ming},
        title = "{spherimatch: Cross-matching and self-matching in spherical coordinates}",
 howpublished = {Astrophysics Source Code Library, record ascl:2507.022},
         year = 2025,
        month = jul,
          eid = {ascl:2507.022},
       adsurl = {https://ui.adsabs.harvard.edu/abs/2025ascl.soft07022H},
      adsnote = {Provided by the SAO/NASA Astrophysics Data System}
}
```
You may also include a reference to the GitHub repository `https://github.com/technic960183/spherimatch` in the footnote if appropriate.

If you publish a paper that uses `spherimatch`, feel free to let me know. I would be happy to hear how this package supports your work!
