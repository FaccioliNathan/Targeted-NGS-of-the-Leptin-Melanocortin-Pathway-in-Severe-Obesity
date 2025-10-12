_R-studio software (version 2023.03.0+386 using R version 4.2.3) was used.
The null hypothesis tested was that there was no difference between the group of patients carrying potentially pathogenic variants and non-carriers and was rejected if p < 0.05.
A contingency table was created beforehand to verify the applicability of the statistical test used._

****Annotations:****

obgen.csv is the csv file containing the raw data of every  patient.

variantpathor: logical variable, 1 = patient carrying a probable pathogenic variant, 0 = patient carrying no probable pathogenic variant

atcdf: logical variable, 1 = at least 1 first-degree relative known to be obese for this patient, 0 = no first-degree relative (mother, father, siblings) known to be obese for this patient

Obesity.before.6.years: logical variable, 1 = BMI exceeded the IOTF 30 curve before the age of 6 in the growth curve of this patient, or obesity before the age of 6 was reported in medical records for the patient, 0 = 1 is not applicable

Age of obesity onset was defined as the age at which BMI exceeded the IOTF 30 curve or if reported in medical records.
