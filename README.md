# Mt Hay, Blue Mountains NSW, Change Detection 2019 to 2023

## Objective
To quantify the changes in land cover at Mt Hay, Blue Mountains NSW following the major bushfire in December 2019.

## Method
Sentinel 2 satellite data was obtained from Digital Earth Australia's Open Data Cube for two dates in each of November 2019 and November 2024. Each 10m×10m=100m^2 plot in the study area was represented by one pixel in the dataset. The two dates for each year were averaged to form RGB, NIR and NDVI datasets. True-colour (RGB) and NDVI images of the study area and its surrounds were plotted and reviewed. A land cover classification was developed using NDVI thresholds, from which class change matrices and a class change map were produced. 

## Usage
* Clone the repository to the [Digital Earth Australia (DEA) Sandbox](https://app.sandbox.dea.ga.gov.au/hub/login?next=%2Fhub%2F)
* Run all steps in `./nbk/data_preparation.ipynb`
* Run all steps in `./nbk/analysis.ipynb`

## Report
There is a summary report in the `./report` directory.