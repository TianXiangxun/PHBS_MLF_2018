# Forest Type Mapping Data Proposal

## Team members

**August Rodermans - 1701212999**

**Jason Tian- 1701213094**

**Daniel Bonfil - 1801214680**

## Motivation
The project use dataset from UCI machine learnning repository. We think the project is interesting and meaningful, because the output (forest type map) can be used to identify and/or quantify the ecosystem services (e.g. carbon storage, erosion protection) provided by the forest,which has significant effect on enviroment pretection.

## Data Source
We derived our dataset from UCI machine learnning repository.
Souce:http://archive.ics.uci.edu/ml/datasets/Forest+type+mapping

## Data Summary Statistic
This data set contains 523 samples from a remote sensing study which mapped different forest types based on their spectral characteristics
at visible-to-near infrared wavelengths, using ASTER satellite imagery. 
Here is an example of our dataset:

![](./data1.png)

The attributes information are shown as follows:

* **S：Sugi forest**
* **h: Hinoki forest**
* **d: Mixed deciduous forest**
* **o: Other non forest land**
* **b1 - b9: ASTER image bands containing spectral information in the green, red, and near infrared wavelengths for three dates (Sept. 26, 2010; March 19, 2011; May 08, 2011.)**
* **pred_minus_obs_S_b1 - pred_minus_obs_S_b9: Predicted spectral values (based on spatial interpolation) minus actual spectral values for the 's' class (b1-b9)**
* **pred_minus_obs_H_b1 - pred_minus_obs_H_b9: Predicted spectral values (based on spatial interpolation) minus actual spectral values for the 'h' class (b1-b9)**		

