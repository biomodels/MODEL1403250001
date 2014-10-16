# MODEL1403250001: MODEL1403250001

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL1403250001.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL1403250001.git@20140916`

## Usage

Importing the model package.

`import MODEL1403250001 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes

    
    
    This is corresponding to the model of yeast glycolysis "glucose upshift" condition described in the paper "Testing Biochemistry Revisited: How In Vivo Metabolism Can Be Understood from In Vitro Enzyme Kinetics" by van Eunen et al published in Plos Comput Biol, 2012.


