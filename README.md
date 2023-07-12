# Template for Local Packages: Part 2
This repository contains a complementary example for how to use the [template](https://github.com/trowraic/bag-builder/tree/master) for the intended package structure. 

This file only contains a demonstration of how to import a package with the format used in [this rep](https://github.com/trowraic/bag-builder/tree/master). 

Step-By-Step:
* clone both repositories into your working directory\
`git clone git@github.com:trowraic/bag-builder.git master .`\
`git clone git@github.com:trowraic/local-install-of-package.git master .`
* in the `local-install-of-package`-directory setup and activate a virtual python environment via\
`python3 -m venv .thisvenv`\
`source .thisvenv/bin/activate`
* install the local package (+dependencies as described in the `setup.py`-file) from the respective directory\
`pip install ../bag-builder`
* run the code with\
`python3 testlocalinstall.py`
