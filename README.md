# BIOMD0000000191: Model_1

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000191.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000191.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000191 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


SBML creators: Armando Reyes-Palomares * , Raul Montañez *, Carlos Rodriguez-
Caso +, Francisca Sanchez-Jimenez * , Miguel A. Medina *

* ProCel Group, Department of Molecular Biology and Biochemistry, Faculty of Sciences, Campus de Teatinos, University of Malaga and CIBER de Enfermedades Raras (CIBER-ER). + Complex Systems Lab (ICREA-UPF), Barcelona Biomedical Research Park (PRBB-GRIB).

http://asp.uma.es

In silico analysis of arginine catabolism as a source of nitric oxide or
polyamines in endothelial cells.  
Montañez, R et al.: Amino Acids. 2008 Feb;34(2):223-9.  
The model reproduces the dynamical behavior of the arginine catabolism and
transport in relation to the nitric oxide production. In this model there are
some additions and corrections to the publication. All perturbations and
analysis have produced results very close to the published experiments. The
model was successfully tested on CoPaSi v.4.4 (build 26).

Erratum: parameters values modificated respect to the publication to reach the
steady-state:

Kmodc=90 µM (60 µM in the paper)

Kiornhat (is equivalent to the parameter Kmefflhat Eq ) = 360 µM (380 µM in
the paper)

  

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not.

  

To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


