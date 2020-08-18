# High Risk mixIRT
- Metadata for the mixIRT paper on multimorbidity.
- DOI: 10.1109/JBHI.2019.2948734
- Based on the pioneering work by Katherine Prenevost: https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0206915

# Data
- Deidentified data: https://www.datahub.va.gov/dataset/ICD9-and-ICD10-Comorbid-Diagnosis-for-High-Risk-Ve/mick-4aih
- icd9.csv:  Cohort from calendar year 2014 (N1 = 937,407), for which we used International Classification of Disease Version 9 (ICD9) codes to identify comorbid conditions.
- icd10.csv: A more recent cohort selected from June 2017 to June 2018  (N2 = 979,607) for use with the newer International Classification of Disease Version 10 (ICD10) codes
# Meta Data
- mixIRTMetaData.pdf: Variable names and descriptions.
- Included are two tab delimited flat files that contain the ICD codes, descriptions and flags for chronic conditions
	Names:
		ICD9CodesAndConditions.txt: Full list of ICD9 codes, descriptions and flags of chronic conditions.
		ICD10CodesAndConditions.txt: Full list of ICD10 codes, descriptions, and flags of chronic conditions.
	Column names:
		ICD\\d+Code: The ICD Code
		ICD\\d+Description: The ICD description
		Flags: See the reference below and the mixIRTMetaData.pdf for details on the chronic conditions.

# Reference:
A. Batten, J. Thorpe, R. Piegari and A. Rosland, "A Resampling Based Grid Search Method to Improve Reliability
and Robustness of Mixture-Item Response Theory Models of Multimorbid High-Risk Patients," in IEEE Journal of
Biomedical and Health Informatics.
doi: 10.1109/JBHI.2019.2948734
Abstract: There are many statistics available to the applied statistician for assessing model fit and even more
methods for assessing internal and external validity. We detail a useful approach using a grid search technique
that balances the internal model consistency with generalizability and can be used with models that naturally
lend themselves to multiple assessment techniques. Our method relies on resampling and a simple grid search
method over 3 commonly used statistics that are simple to calculate. We apply this method in a latent traits
framework using a mixture Item Response Theory (MIXIRT) model of common chronic health conditions. Model fit
is assessed using Akaike's Information Criteria (AIC), latent class similarity is measured with the Variance
of Information (VI), and the consistency of condition complexity and prevalence across latent classes is
compared using Kendall's τ rank order statistic. From two patient cohorts at high risk for hospitalization
in 2014 and 2018, we generated 19 MIXIRT models (allowing 2-20 latent classes) on 21 common comorbid
conditions identified via healthcare encounter diagnosis codes. We ran these models on 100 bootstrap
samples of size 10% for each cohort. Among the resulting models, combined AIC and VI statistics identified
5-7 latent classes, but the rank order correlation of condition complexity revealed that only the 5 class
solutions had consistent condition complexity. The 5 class solutions were combined to produce a single
parsimonious MIXIRT solution that balanced clinical significance with model fit, cluster similarity, and
consistency of condition complexity.
keywords: {Complexity theory;Sociology;Statistics;Diseases;Solid modeling;Search methods;chronic conditions;
high-risk patients;item response theory;latent class analysis;multimorbidity},
