# production
This repository contains the configurations to run Cuizinart and CaSPAr in a production environment.

Here, the docker-compose.yaml defines the containers for nginx, cuizinart, caspar, and their databases.
nginx will route requests to `tuna.cs.uwaterloo.ca` and `tuna.cs.uwaterloo.ca/cuizinart` to the cuizinart container, and requests to `tuna.cs.uwaterloo.ca/caspar` to the caspar container.

The contents of the cuizinart and caspar containers are defined in the respective production branches in [https://github.com/gwf-uwaterloo/cuizinart].

## System setup
![Architecture](architecture.jpg)
