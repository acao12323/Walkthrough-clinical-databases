# WALKTHROUGH ON ICU CLINICAL DATABASES

eICU Use Case

The primary objective of this work is to develop a predictive model that estimates the number of ventilation days for a patient newly admitted to the ICU. This model will utilize sociodemographic, anthropometric, and clinical data derived from the APACHE Score. The APACHE Score is calculated for ICU patients to assess their risk of mortality.
## Data
Data

For this project, we downloaded the following tables from version 2.0.1 of the eICU project:

1. apacheApsVar
2. apachePatientResult
3. patient

We obtained the eICU demo dataset (a lightweight version of eICU) from [PhysioNet](https://physionet.org/content/eicu-crd-demo/2.0.1/#files-panel)

Detailed descriptions of the table contents can be found on [GitHub](https://github.com/MIT-LCP/eicu-code/tree/master/website/content/eicutables)
