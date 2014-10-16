# BIOMD0000000295: Akman2008_Circadian_Clock_Model1

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000295.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000295.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000295 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
**Isoform switching facilitates period control in the Neurospora crassa circadian clock.**   
Akman OE, Locke JC, Tang S, Carré I, Millar AJ, Rand DA _Mol. Syst. Biol._
2008;Vol 4: 164 [18277380](http://www.ncbi.nlm.nih.gov/pubmed/18277380) ,  
**Abstract:**   
A striking and defining feature of circadian clocks is the small variation in
period over a physiological range of temperatures. This is referred to as
temperature compensation, although recent work has suggested that the
variation observed is a specific, adaptive control of period. Moreover, given
that many biological rate constants have a Q(10) of around 2, it is remarkable
that such clocks remain rhythmic under significant temperature changes. We
introduce a new mathematical model for the Neurospora crassa circadian network
incorporating experimental work showing that temperature alters the balance of
translation between a short and long form of the FREQUENCY (FRQ) protein. This
is used to discuss period control and functionality for the Neurospora system.
The model reproduces a broad range of key experimental data on temperature
dependence and rhythmicity, both in wild-type and mutant strains. We present a
simple mechanism utilising the presence of the FRQ isoforms (isoform
switching) by which period control could have evolved, and argue that this
regulatory structure may also increase the temperature range where the clock
is robustly rhythmic.

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html) .  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


