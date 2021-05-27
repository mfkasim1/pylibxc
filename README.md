# PyLibXC
Github clone of libxc's repository: https://gitlab.com/libxc/libxc/
The reason I build this repository is to use Github action in building the pylibxc package and upload it to PyPI.
The URL in PyPI is: https://pypi.org/project/pylibxc2/, so you can install it conveniently by `python -m pip install pylibxc2`.
Note that although the package name is `pylibxc2`, you still need to `import pylibxc`.
I can't upload it to `pylibxc` (probably because it has been reserved although there is no release yet).

## How to update the distribution

This should be done only if the version number of `libxc` in gitlab is updated.

* Edit `setup.py` by changing `release` to `True`
* Commit the changes
* Put the tag into the commit by adding a new release.

All of those can be done from Github website, so no need to clone this repository.
