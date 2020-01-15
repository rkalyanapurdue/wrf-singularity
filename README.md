# Singularity container recpies for WRF

Use the recipe file Singularity to build WRF using the GNU compilers

## Important Notes

1. The build assumes that source code for HDF, HDF5, NETCDF-C, NETCDF-Fortran, WRF and WPS 
have been downloaded. 
2. This build uses OpenMPI 4.0.1. The OpenMPI version on the nodes where this container is 
run needs to match that inside the container.
