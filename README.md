# MODEL1006230039: Lemon2003_Ca2Dynamics

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL1006230039.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL1006230039.git@20140916`

## Usage

Importing the model package.

`import MODEL1006230039 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
**Metabotropic receptor activation, desensitization and sequestration-I: modelling calcium and inositol 1,4,5-trisphosphate dynamics following receptor activation.**   
Lemon G, Gibson WG, Bennett MR. _J Theor Biol_ 2003 Jul 7;223(1):93-111
[12782119](http://www.ncbi.nlm.nih.gov/pubmed/12782119) ,  
**Abstract:**   
A mathematical account is given of the processes governing the time courses of
calcium ions (Ca2+), inositol 1,4,5-trisphosphate (IP(3)) and
phosphatidylinositol 4,5-bisphosphate (PIP(2)) in single cells following the
application of external agonist to metabotropic receptors. A model is
constructed that incorporates the regulation of metabotropic receptor
activity, the G-protein cascade and the Ca2+ dynamics in the cytosol. It is
subsequently used to reproduce observations on the extent of desensitization
and sequestration of the P(2)Y(2) receptor following its activation by uridine
triphosphate (UTP). The theory predicts the dependence on agonist
concentration of the change in the number of receptors in the membrane as well
as the time course of disappearance of receptors from the plasmalemma, upon
exposure to agonist. In addition, the extent of activation and desensitization
of the receptor, using the calcium transients in cells initiated by exposure
to agonist, is also predicted. Model predictions show the significance of
membrane PIP(2) depletion and resupply on the time course of IP(3) and Ca2+
levels. Results of the modelling also reveal the importance of receptor
recycling and PIP(2) resupply for maintaining Ca2+ and IP(3) levels during
sustained application of agonist.

This model was taken from the [CellML
repository](http://www.cellml.org/models) and automatically converted to SBML.  
The original model was: [ **Lemon G, Gibson WG, Bennett MR. (2003) -
version=1.0**
](http://models.cellml.org/exposure/d7c4eca1662324918761bc5b18745cd1)  
The original CellML model was created by:  
**Wei Liu**   
wliu052@aucklanduni.ac.nz  
The University of Auckland  

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not..  
  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


