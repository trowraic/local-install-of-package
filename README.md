# Template for Local Packages: Part 2
This repository contains a complementary example for how to use the [template](https://github.com/trowraic/bag-builder/tree/master) for the intended package structure. 

This file only contains a demonstration of how to import a package with the format used in [this rep](https://github.com/trowraic/bag-builder/tree/master). 

Step-By-Step:
* clone both repositories into your working directory\
`git clone git@github.com:trowraic/bag-builder.git -b master`\
`git clone git@github.com:trowraic/local-install-of-package.git -b master`
* in the `local-install-of-package`-directory setup and activate a virtual python environment via\
`python3 -m venv .thisvenv`\
`source .thisvenv/bin/activate`
* install the local package (+ dependencies as described in the `setup.py`-file) from the respective directory\
`pip install ../bag-builder`
* run the code with\
`python3 testlocalinstall.py`

As an alternative to the local installation of this package, the package can also be installed by using the syntax\
`pip install git+<Link to repository>`\
i.e. here\
`pip install git+https://github.com/trowraic/bag-builder.git`

