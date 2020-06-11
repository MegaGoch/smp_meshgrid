
# Table of Contents

1.  [hexgrid project](#org3aaecd4)
2.  [requirements](#orgcf6795b)
3.  [running scripts](#orgf9e5a45)
    1.  [trigrid\\<sub>display</sub>](#org152f65c)
    2.  [trigrid](#orgfdc4787)
        1.  [trigrid modes](#org9f67a08)
4.  [modules](#orgb84bb46)



<a id="org3aaecd4"></a>

# hexgrid project

a simulation and realtime monitor / interface to spatial
structures. the structure is defined as a mesh which can be rendered
and also serve as a structure to organize computing modules with
spatial properties.


<a id="orgcf6795b"></a>

# requirements

-   pygame
-   pyopengl
-   numpy, scipy - can also be installed with distribution tools
-   pyliblo - python wrapper for liblo OSC library
-   trimesh, meshpy - mesh libraries

    pip3 install pygame pyopengl numpy scipy pyliblo trimesh pyzmq joblib meshpy


<a id="orgf9e5a45"></a>

# running scripts

to run the demo go into the project directory

    cd smp_meshgrid


<a id="org152f65c"></a>

## trigrid\\<sub>display</sub>

then start the GL display with

    python3 scripts/trigrid_display.py --width=1600 --height=900


<a id="orgfdc4787"></a>

## trigrid

this contains the model, and when running loads a mesh and sends
vertex, edge and face information derived from model states to the
display server. run it with

    python3 scripts/trigrid.py


<a id="org9f67a08"></a>

### trigrid modes

there is a few predfined meshes (hexagon, line, &#x2026;). the model can
run on its own and it can be connected with the physical hexagon using
libsensorimotor

then there are a few modes that serve as simple demo and starting
points for extending the activation and coupling rules.

-   threshold crossing triggered activation with lateral coupled neighbors
-   TODO: random activation and isotropic propagation
-   TODO: liquid model


<a id="orgb84bb46"></a>

# modules

-   oscsrv
-   sensorimotor

