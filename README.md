# interactor-blender-meshoptimizer

An add-on for an open-source 3D creation suite that simplifies the selected meshes to a target error with meshoptimizer.

## What it is for

It adds a decimate command to the mesh menu that reduces one or more selected meshes, with the error measured against each mesh's bounds and an option to keep border vertices in place.

## Build and run

The add-on loads meshoptimizer as a shared library from its own directory or the system library path. The `Build meshoptimizer` workflow builds that library for each desktop platform; put it beside `__init__.py` and install the directory as an add-on.

## Licence

Apache-2.0; see `LICENSE`. meshoptimizer itself is MIT.
