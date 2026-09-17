## About

The PVDOMICS (Redefining Pulmonary Hypertension through Pulmonary Vascular Disease Phenomics) study, launched in 2014 by the NHLBI with support from the Pulmonary Hypertension Association, is a multi-center observational study that aimed to enroll 1,500 adults with pulmonary hypertension (PH), at-risk comparators, and healthy controls. The study aimed to perform comprehensive phenotyping and endophenotyping across the World Health Organization (WSPH) classified PH clinical groups 1 through 5 as well as intermediate phenotypes (including those without overt PH) in order to deconstruct the traditional classification and define new meaningful subclassifications of patients with PVD.

Enrollment for the PVDOMICS study occurred over three years, with each participant completing comprehensive clinical and multi-omic testing within six weeks. ollow-up to track survival and transplant outcomes continues annually, with current data available for up to 7 years. Sleep, medical, physical fitness, quality of life, cardiopulmonary health, biospecimen, “omic” data were collected for 461 participants at the baseline visit from 2016 to present using at- home sleep tests, physical exams, quality of life surveys, cardiopulmonary exercise testing, blood and urine collection. Clinical sleep studies done prior to study enrollment in were allowed when a PVDOMICS study protocol sleep study was not done.

## Methods

### Recruitment and eligibility

Participants presenting for Pulmonary Hypertension (PH) evaluation, heart failure, lung disease, dyspnea, or exercise intolerance were recruited from 6 clinical centers. The Pulmonary Vascular Disease (PVD) group inclusion criteria were adults over 18 referred for right heart catheterization to evaluate known or suspected PVD due to cardiac or pulmonary disease, who were able to complete all required diagnostic tests and provided informed consent. The control group consisted of healthy adults aged 18 or older with normal cardiopulmonary screening and no end organ disease, who also provided informed consent. Exclusion criteria for the PVD group were dialysis-dependent kidney disease, being deemed too ill by the clinician to complete testing, or pregnancy/nursing. For controls, exclusions were active cancer (except localized non-melanoma skin cancer) or pregnancy/nursing.

### Clinic visits

Participants underwent a clinical phenotyping protocol including pulmonary and right ventricular structure/function assessment and biospecimen collection for omic analysis. Procedures included quality of life assessment, sleep study, body compositional analysis, six-minute walk testing, transthoracic echocardiography, cardiac magnetic resonance imaging, cardiopulmonary exercise testing, pulmonary function testing, chest CT, ventilation lung scan, and right heart catheterization with provocative maneuvers. Data was collected at baseline and annual follow-up visits.

Clinical measurements taken at baseline include:

- Pulmonary function testing performed using American Thoracic Society (ATS)

- Computed tomography of the chest - Ventilation perfusion scintigraphy

- Standard 12-lead electrocardiogram performed using a digitalized electrocardiograph machine

- Comprehensive two-dimensional transthoracic echocardiography

- Standardized Cardiac MRI exam with Gadolinium-DTPA contrast agent.

- Cardiopulmonary hemodynamics examined by right heart catheterization with provocative testing and non-invasive or invasive cardiopulmonary exercise testing (iCPET).

### HSAT or PSG collection

One night of unattended home sleep apnea test data was collected in participants’ homes using the NOX-T3, Carefusion (Becton, Dickinson, Franklin Lakes, NJ) following the PVDOMICS study protocol.

If the participant had a sleep study done within one year prior to or six months after the study participation window, or had clinical sleep studies conducted during the PVDOMICS period, then it is at the discretion of the Center PI as to whether this **“alternative”** sleep study can be accepted, or if an additional PVDOMICS protocol sleep study should be performed.

The HSAT montage included the following channels:

- nasal pressure transducer 200 Hz

- respiratory inductance plethysmography 200 Hz

- oxygen saturation (Nonin & Wrist Ox model 3150 ® with Nonin Puresat ®) SpO2 3Hz, Pleth 75Hz

- electrocardiogram 200 Hz

- snoring Microphone data collected at 8 kHz

- body position at 200 Hz

### HSAT or PSG scoring

Sleep studies collected as part of the PVDOMICS core study protocol were scored using standardized methods for home sleep apnea testing and will conform to American Academy of Sleep Medicine (AASM) guidelines. The scoring event definitions are listed below:

- Epoch Interval: consecutive segments of 30 seconds.

- Apneas were defined as a drop in peak signal excursion by \>90% of the pre-event baseline using a nasal transducer and the duration of the drop is \>10 seconds in accordance with American Academy of Sleep Medicine guidelines.

- Obstructive apneas were scored if there is persistence of thoracoabdominal effort and absence of airflow.

- Central apneas were scored if there is an absence of thoracoabdominal effort and airflow.

- Hypopnea events were scored if peak signal excursion is reduced by \>30% of the pre-event baseline using nasal pressure transducer lasting for \>10 seconds and associated with \>3% oxygen desaturation.

- Periodic breathing was defined as airflow or inductance channels increasing and decreasing at least 50% from the maximum, in a cyclic waxing and waning or "sinusoidal" manner for a consecutive period of \>10 min.

Alternative sleep studies received from external laboratories may differ in study type, acquisition procedures, and respiratory event scoring criteria.

**The NSRR team recommends using metrics derived from the PVDOMICS core study protocol for analyses requiring consistent respiratory event definitions. Combined variables incorporate data from heterogeneous source studies and should be interpreted and used with caution.**

## Data de-identification

All personally identifiable information (PII) was removed from the data files by the NSRR team.

## Data overview

### Covariate/phenotype datasets (CSV)

The [covariate dataset files](:files_path:/datasets) contain 714 rows each first column (alt_pid) is the unique PVDOMICS subject identifier that can be linked with PSG signal filenames.

The dataset columns are described in the accompanying data dictionary files. The **variables** data dictionary file includes folder names (id), labels (display names), descriptions, and other metadata. Categorical variables also include an associated “domain” (e.g., 1=male, 2=female), which are described in the **domains** data dictionary file.

The history of the covariate datasets and data dictionary files have been tracked on GitHub (<https://github.com/nsrr/pvdomics-data-dictionary>).

The harmonized-dataset contains many of the most frequently used demographic and sleep variables. These variables were curated by the NSRR team to allow ready inter-operability with other NSRR datasets.

The NSRR-harmonized sleep variables are derived only from participants who completed the PVDOMICS core protocol sleep studies, which used standardized equipment and clearly defined respiratory event scoring criteria.

|  |  |
|------------------------------------|------------------------------------|
| **Variable** | **Label** |
| [nsrr_age](:variables_path:/nsrr_age) | Subject age |
| [nsrr_sex](:variables_path:/nsrr_sex) | Subject sex |
| [nsrr_race](:variables_path:/nsrr_race) | Subject ethnicity |
| [nsrr_ethnicity](:variables_path:/nsrr_ethnicity) | Subject race |
| [nsrr_bmi](:variables_path:/nsrr_bmi) | Body mass index (BMI) |
| [nsrr_rei_hp3n](:variables_path:/nsrr_rei_hp3n) | Respiratory Event Index: (Apneas or hypopneas with \>= 3% oxygen desaturation)/hour of estimated sleep |
| [nsrr_current_smoker](:variables_path:/nsrr_current_smoker) | Currently smoking cigarettes |
| [nsrr_odi_dsge3](:variables_path:/nsrr_odi_dsge3) | Oxygen Desaturation Index (3%) |
| [nsrr_odi_dsge4](:variables_path:/nsrr_odi_dsge4) | Oxygen Desaturation Index (4%) |

### HSAT signal file

Raw polysomnography data are available for 703 subjects[JM1.1]. Each recording has a signal file (.EDF) and two versions of the event scoring andand epoch staging annotations (.XML). 1. EDF - Signal files in the European Data Format exported from Compumedics Profusion. 2. XML (Profusion) - Annotation files exported from Compumedics Profusion. 3. XML (NSRR) - Annotation files processed in the EDF Editor and Translator tool. NSRR XML files can be overlaid onto EDF signal files using the EDF Viewer tool. For more information about the XML translation (mapping) process, review the files available on the EDF Editor and Translator Releases page.

## Access and usage restrictions

The PVDOMICS dataset is only available for non-commercial use.

## Citation and acknowledgements

When using this dataset, users must cite the following publications:

> [Zhang GQ, Cui L, Mueller R, Tao S, Kim M, Rueschman M, Mariani S, Mobley D, Redline S. The National Sleep Research Resource: towards a sleep data commons. J Am Med Inform Assoc. 2018 Oct 1;25(10):1351-1358. doi: 10.1093/jamia/ocy064. PMID: 29860441; PMCID: PMC6188513.](https://pubmed.ncbi.nlm.nih.gov/29860441/)

> [Hemnes AR, Beck GJ, Newman JH, Abidov A, Aldred MA, Barnard J, Berman Rosenzweig E, Borlaug BA, Chung WK, Comhair SAA, Erzurum SC, Frantz RP, Gray MP, Grunig G, Hassoun PM, Hill NS, Horn EM, Hu B, Lempel JK, Maron BA, Mathai SC, Olman MA, Rischard FP, Systrom DM, Tang WHW, Waxman AB, Xiao L, Yuan JX, Leopold JA; PVDOMICS Study Group. PVDOMICS: A Multi-Center Study to Improve Understanding of Pulmonary Vascular Disease Through Phenomics. Circ Res. 2017 Oct 27;121(10):1136-1139. doi: 10.1161/CIRCRESAHA.117.311737. PMID: 29074534; PMCID: PMC5685561.](https://pubmed.ncbi.nlm.nih.gov/29074534/)

> [Hemnes AR, Leopold JA, Radeva MK, Beck GJ, et al and the PVDOMICS Study Group. Clinical characteristics and transplant-free survival across the spectrum of pulmonary vascular disease. Journal of the American College of Cardiology. 2022;80(7), 697-718. PMID: 35953136; PubMed Central PMCID: PMC9897285](https://pmc.ncbi.nlm.nih.gov/articles/PMC9897285/)

Users must include the following text in any Acknowledgements section:

> The PVDOMICS study recieved grants U01 HL125218, U01 HL125205, U01 HL125212, U01 HL125208, U01 HL125175, U01 HL125215, U01 HL125177, and was supported by the Pulmonary Hypertension Association.1

> The National Sleep Research Resource was supported by the U.S. National Institutes of Health, National Heart Lung and Blood Institute (R24 HL114473, 75N92019R002).

## References

- PVDOMICS on the National Sleep Research Resource (NSRR): <http://sleepdata.org/datasets/pvdomics>
- PVDOMICS on NSRR GitHub Data Dictionary: <https://github.com/nsrr/pvdomics-data-dictionary>
- PVDOMICS on ClinicalTrials.gov: <https://clinicaltrials.gov/study/NCT02980887>
- PVDOMICS sleep study reference article:<https://pmc.ncbi.nlm.nih.gov/articles/PMC11060475/> 