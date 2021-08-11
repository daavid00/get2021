## Description
This repository contains runscripts to produce the figure in paper [A]. They
have been successfully run in Linux and Mac OS (not tested in Windows). This
implementation is based on the OPM release 2021.04. New scripts have been added/
modified in opm-material, opm-models, and opm-simulators folders, corresponding
to the 'wettability' branch. All original tests in opm-models and opm-tests from
the release 2021.04 can be run using this implementation. The folder tests
include examples of scripts to run a single simulation.

## Requirements
* [OPM](https://opm-project.org)
* [Python](https://www.python.org/downloads/)

## Python dependencies
* [numpy](https://numpy.org)
* [os](https://docs.python.org/3/library/os.html)
* [meshio](https://github.com/nschloe/meshio)
* [matplotlib](https://matplotlib.org)
* [pyvista](https://www.pyvista.org)

## Installation
* Clone all OPM modules from https://github.com/daavid00, check out the
"wettability" branch, and build all opm modules, specially 'get2021' from
opm-models (opm-simulators is not required for this simulations).

`./buildopm.bash`
* Edit line 23 of the python scripts with the full path to the 'get2021'
executable respectively.

## Running the scripts
* From the terminal, e.g., for fig2:

`python3 fig2.py`

## Paper
* [A] Landa-Marbán, D., Kumar, K., Gasda, S.E., Sandve, T.H., Kassa, A.M.
Numerical studies of long-term wettability alteration effects in co2 storage
applications. Submitted.

## Contact
David Landa-Marbán (dmar@norceresearch.no).
