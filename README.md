# mpi-python-examples

This repository a series of MPI Python examples.

### Requirements

1. An installation of MPI implementation
2. Install Python dev
3. Install mpi4py

#### An installation of MPI implementation

Example installation of MPI 

```
sudo apt-get install openmpi-bin openmpi-common openssh-client openssh-server libopenmpi-dev
```

#### Install Python dev

Install Python dev, which installs the correct Python header files.
```
sudo apt-get install python-dev # for python2.x instances.
sudo apt-get install python3-dev # for python 3.x instances.
```

#### Install mpi4py
```
sudo env MPICC=/usr/bin/mpicc pip install mpi4py
```
