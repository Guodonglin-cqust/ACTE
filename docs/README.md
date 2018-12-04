# ACTE - Anisotropic Coefficients of Thermal Expansion

This program contains an efficient algorithm for the calculation of the anisotropic coefficients of thermal expansion.  User input is minimal for the standard calculation and the script itself is adaptable to any supercomputing infrastructure. 

## Getting Started

A copy of this program can be obtained, with this readme file, from Github. After downloading, the user should modify the supercomputer requirements and point the script to the vasp and tdep executables.  

A more detailed description of what is needed to run this script is found in the user manual.  See [USER_MANUAL.pdf](USER_MANUAL.pdf) for additional details.

### Prerequisites

This program requires python version 3.0+.  Additionally, this program requires several numpy packages:

* numpy
* subprocess
* matplotlib 
* mendeleev 


Each of these can be installed from the python depository using `pip install`.

### Installing

Installation is easy! 

You only need to place this program into the root folder where the calculations take place.


## Deployment

Before using this program it is important that the program, and systems running this program, be set up.

This requires:

1. Structured file and folder system
   - This folder system is outlined using `python ACTE.py --help`
2. VASP
   - VASP should be downloaded, installed, and the VASP executable linked in the program.
3. TDEP
   - TDEP should be downloaded, installed, and the TDEP bin folder needs to be linked.


## Contributing

There are currently no contributors to this program. However, if anyone would like to make changes to the code please send an email to the author, Nicholas Pike.  Changes and suggestions are more than welcome.

## Versioning

0.0 - Initial production version of the program

## Authors

* **Nicholas Pike** - *Initial work* - Please email (Nicholas.pike at smn.uio.no) if you have questions, comments, or ideas.


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

