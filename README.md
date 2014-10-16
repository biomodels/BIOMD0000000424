# BIOMD0000000424: Faratian2009_PTENrole_TrastuzumabResistance

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000424.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000424.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000424 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


Faratian2009 - Role of PTEN in Trastuzumab resistance

This model is described in the article:

[Systems biology reveals new strategies for personalizing cancer medicine and
confirms the role of PTEN in resistance to
trastuzumab.](http://identifiers.org/pubmed/19638581)

Faratian D, Goltsov A, Lebedeva G, Sorokin A, Moodie S, Mullen P, Kay C, Um
IH, Langdon S, Goryanin I, Harrison DJ.

Cancer Res. 2009 Aug; 69(16): 6713-6720

Abstract:

Resistance to targeted cancer therapies such as trastuzumab is a frequent
clinical problem not solely because of insufficient expression of HER2
receptor but also because of the overriding activation states of cell
signaling pathways. Systems biology approaches lend themselves to rapid in
silico testing of factors, which may confer resistance to targeted therapies.
Inthis study, we aimed to develop a new kinetic model that could be
interrogated to predict resistance to receptor tyrosine kinase (RTK) inhibitor
therapies and directly test predictions in vitro and in clinical samples. The
new mathematical model included RTK inhibitor antibody binding, HER2/HER3
dimerization and inhibition, AKT/mitogen-activated protein kinase cross-talk,
and the regulatory properties of PTEN. The model was parameterized using
quantitative phosphoprotein expression data from cancer cell lines using
reverse-phase protein microarrays. Quantitative PTEN protein expression was
found to be the key determinant of resistance to anti-HER2 therapy in silico,
which was predictive of unseen experiments in vitro using the PTEN inhibitor
bp(V). When measured in cancer cell lines, PTEN expression predicts
sensitivity to anti-HER2 therapy; furthermore, this quantitative measurement
is more predictive of response (relative risk, 3.0; 95% confidence interval,
1.6-5.5; P < 0.0001) than other pathway components taken in isolation and when
tested by multivariate analysis in a cohort of 122 breast cancers treated with
trastuzumab. For the first time, a systems biology approach has successfully
been used to stratify patients for personalized therapy in cancer and is
further compelling evidence that PTEN, appropriately measured in the clinical
setting, refines clinical decision making in patients treated with anti-HER2
therapies.

This model is hosted on [BioModels Database](http://www.ebi.ac.uk/biomodels/)
and identified by:
[BIOMD0000000424](http://identifiers.org/biomodels.db/BIOMD0000000424).

To cite BioModels Database, please use: [BioModels Database: An enhanced,
curated and annotated resource for published quantitative kinetic
models](http://identifiers.org/pubmed/20587024).

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.


