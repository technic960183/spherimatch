# spherimatch
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
You can install `spherimatch` by cloning the codes:
```bash
git clone https://github.com/technic960183/spherimatch.git
```

pip install will be supported in the future.

Remember to set the environment variable `PYTHONPATH` (`sys.path`) to the directory where `spherimatch` is located.
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
If you find `spherimatch` useful in your research, please consider citing it. Currently, we do not plan to publish a method paper for this package in the year of 2024. However, you can still cite this repository directly.

To cite spherimatch in your publication, please use the following BibTeX entry:
```bibtex
@misc{spherimatch,
  author = {Yuan-Ming Hsu},
  title = {spherimatch: A Python package for cross-matching and self-matching in spherical coordinates.},
  year = {2024},
  howpublished = {\url{https://github.com/technic960183/spherimatch}},
  note = {Accessed: YYYY-MM}
}
```
Addtionally, you may add a reference to `https://github.com/technic960183/spherimatch` in the footnote if suitable.

If you publish a paper that uses `spherimatch`, please let me know. I would be happy to know how this package has been used in research.
