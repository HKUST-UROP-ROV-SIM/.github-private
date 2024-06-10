# HKUST-UROP-ROV-SIM
[Introduction](#introduction)
[How to use?](#how_to_use)
  - [Build the Dockerfile](#build_the_dockerfile)
  - [Remove original colcon_ws](#remove_original_colcon_ws)
  - [Clone colcon_ws from this organization](#clone_colcon_ws_from_this_organization)
  - [Save a running container](#save_a_running_container)  

# Introduction  
This documentation introduces how to use the [Orca4](https://github.com/clydemcqueen/orca4)  
# [How to use?](#how_to_use)
[Build the Dockerfile](#build_the_dockerfile)
1. ```cd orca4/docker```
2. Run ```./build.sh```
3. After finishing building, run ```./run.sh```
4. Remove original colcon_ws and clone the [colcon_ws](#https://github.com/HKUST-UROP-ROV-SIM/colcon_ws)
5. Clone all the sub-modules ```git submodule update --init --recursive```

