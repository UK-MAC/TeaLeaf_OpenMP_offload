# TeaLeaf OpenMP45

This is an OpenMP offload port of Tealeaf reference for GPUs (tested on AMD and Nvidia)

## Compling

In most cases one needs to load the appropriate modules (including those for the accelerator in question).

Then for AMD/Nvidia GPUs (with the Cray compiler)

```
make clean; make COMPILER=CRAY
```

or for Nvidia GPUs (nvhpc compilers),

```
make clean; make COMPILER=PGI
```
