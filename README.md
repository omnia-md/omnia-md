Omnia
=====

Omnia is a consortium of open-source software for computational biophysics
and chemistry.

Installation
============

To install, you just need a working python / conda installation (see http://docs.continuum.io/anaconda/install.html) and the following commands:


```
conda config --add channels http://conda.binstar.org/omnia
conda install omnia
```

This will add our omnia binstar channel to your conda repositories and then install the omnia metapackage (https://github.com/omnia-md/conda-recipes/blob/master/omnia/meta.yaml), which current includes OpenMM, MSMBuilder, MDTraj, and PDBFixer.

Note: currently only python2.7 on OSX / Linux are supported, but python3.4 will be supported in the coming months.  However, individual components of omnia (such as openmm) may be available for your platform.  You can install the components individually via the following commands:

```
conda config --add channels http://conda.binstar.org/omnia
conda install openmm
```
