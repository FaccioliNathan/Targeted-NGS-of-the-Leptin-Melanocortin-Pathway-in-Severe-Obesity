_R-studio software (version 2023.03.0+386 using R version 4.2.3) was used._

_The null hypothesis tested was that there was no difference between the group of patients carrying potentially pathogenic variants and non-carriers and was rejected if p < 0.05._

_A contingency table was created beforehand to verify the applicability of the statistical test used (using the table function, with the deparse.level=2 and useNA="always" display options for easier reading)._



****Annotations:****



ob is dataset the in which the csv file obgen.csv containing the raw data of every individual was uploaded.
obadu is a subset of the data containing the data of only the adults patients.

variantpathor: logical variable, 1 = individual carrying at least 1 probable pathogenic variant; 0 = individual carrying no probable pathogenic variant.

atcdf: logical variable, 1 = at least 1 first-degree relative (mother, father, siblings) known to be obese for the individual; 0 = no first-degree relative known to be obese for the individual.

Obesity.before.6.years: logical variable, 1 = BMI exceeded the IOTF 30 curve before the age of 6 in the growth curve of the individual, or without growth curve available obesity before the age of 6 was reported in medical records for the patient; 0 = BMI exceeded the IOTF 30 curve after the age of 6 in the growth curve of the individual, and without growth curve available obesity before the age of 6 was not reported in medical records for the individual.

Eating.behavior.disorder: logical variable, 1 = at least 1 eating behavioral disorder was reported for the individual: severe hyperphagia, impulsivity, intolerance to frustration, obsessions or active food-seeking strategies; 0 = no eating behavioral disorder was reported for the individual.

tbendoc: logical variable, 1 = at least 1 central endocrine disorder requiring replacement therapy was reported for the individual: somatotropic, thyrotropic, corticotropic, gonadotropic deficiencies or central diabetes insipidus; 0 = no central endocrine disorder was reported for the individual.

Gonadotropic.deficiency: logical variable, 1 = gonadotropic deficiency requiring replacement therapy was reported for the individual; 0 = no gonadotropic deficiency was reported for the individual.

tnd: logical variable, 1 = at least 1 neurodevelopmental disorder was reported for the individual: intellectual development disorder, psychomotor delay, autism spectrum disorder or specific learning disorders; 0 = no neurodevelopmental disorder was reported for the individual.

malfo: logical variable, 1 = at least 1 malformative feature was reported for the individual: organ malformations, dysmorphic syndrome or spinal static disorders; 0 = no malformative feature was reported for the individual.

compl: logical variable, 1 = at least 1 obesity-related comorbidity was diagnosed for the individual: arterial hypertension, type 2 diabetes, obstructive sleep apnea, hepatic steatosis or insulin resistance; 0 = no obesity-related comorbidity was diagnosed for the individual.

Type.2.diabetes: logical variable, 1 = type 2 diabetes was diagnosed for the individual; 0 = type 2 diabetes was not diagnosed for the individual.

Hypertension: logical variable, 1 = arterial hypertension was diagnosed for the individual; 0 = arterial hypertension was not diagnosed for the individual.

Obstructive.sleep.apnea: logical variable, 1 = obstructive sleep apnea was diagnosed for the individual; 0 = obstructive sleep apnea was not diagnosed for the individual.

NAFLD: logical variable, 1 = hepatic steatosis was diagnosed for the individual; 0 = hepatic steatosis was not diagnosed for the individual.

