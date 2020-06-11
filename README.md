hexgrid project
===============

a simulation and realtime monitor / interface to spatial structures. the structure is defined as a mesh which can be rendered and also serve as a structure to organize computing modules with spatial properties.

requirements
============

-   liblo osc
-   pyopengl
-   pygame
-   trimesh
-   numpy, scipy, ...

modules
=======

-   oscsrv
-   sensorimotor

running scripts
===============

go into the project directory

``` example
cd smp_meshgrid
```

trigrid<sub>display</sub>
-------------------------

run the GL display with

``` example
python3 scripts/trigrid_display.py --width=1600 --height=900
```

trigrid
-------

this is the model, loading a mesh and sending vertex, edge and face information to the display server

run the model with

``` example
python3 scripts/trigrid.py
```

### trigrid modes

there is a few predfined meshes (hexagon, line, ...). the model can run on its own and it can be connected with the physical hexagon using libsensorimotor

then there are a few modes that serve as simple demo and starting points for extending the activation and coupling rules.

-   threshold crossing triggered activation with lateral coupled neighbors
-   TODO: random activation and isotropic propagation
-   TODO: liquid model

