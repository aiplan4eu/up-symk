# Integration of SymK with the Unified Planning Library

## Installation

Currently we are in the development phase and everything has to be built locally. First, build locally our version of the  [unified planning library](https://github.com/speckdavid/unified-planning) where we have registered SymK.

The following should install all necessary dependencies.
```
sudo apt-get -y install cmake g++ make python3 autoconf automake git
```

Clone and install the unified-planning library.

```
git clone git@github.com:speckdavid/unified-planning.git
pip install unified-planning/
```

Then install this package.

```
git clone git@github.com:aiplan4eu/up-symk.git
pip install up-symk/
```

## Usages
In the [notebooks folder](notebooks/), you can find an [example](https://github.com/aiplan4eu/up-symk/blob/master/notebooks/symk_usage.ipynb) of how to use the SymK planner within the unified planning library.
