# Data Sources

Source data are not redistributed. All inputs are available to approved
researchers through the access routes listed below.

---

## 1. PPMI — Primary analysis

**Access:** Free registration and data use agreement at
[ppmi-info.org](https://www.ppmi-info.org)
(RRID: SCR_006431).

**Data vintage:** Last accessed via the PPMI portal on February 14, 2026.
Longitudinal data collected between July 7, 2010 and January 1, 2026.

### Required variables

**Demographics and genotyping.** Age at onset, sex, self-reported race
and ethnicity, melanoma history, baseline medication status, deep brain
stimulation treatment status, α-synuclein seed amplification assay (SAA)
result, and years since original diagnosis. *MC1R* variant calls (R163Q/P,
V60L, V92M/L, R151S/G/C, R160W, D294N/H, D84E, R142H) with penetrance
class (R vs r) and zygosity. Monogenic status for *LRRK2*, *GBA*, *SNCA*,
*PRKN*, *PINK1*, *PARK7*, and *VPS35* used for cohort definition and
exclusions.

**Motor outcomes (primary).** MDS-UPDRS Part III summary scores in
OFF-medication and ON-medication states. Item-level Part III scores for
subscore derivation: bradykinesia (items 3.4–3.8, 3.9, 3.14), rigidity
(3.3a–e), tremor (3.15–3.18), axial (3.9–3.13), and orofacial
(3.1–3.2). Levodopa equivalent daily dosage (LEDD) at each visit.

**Secondary outcomes.** MDS-UPDRS Parts I, II, and IV. Montreal Cognitive
Assessment (MoCA). DAT-SPECT striatal binding ratios (caudate and
putamen). SCOPA-AUT, Geriatric Depression Scale (Short Version), and
Epworth Sleepiness Scale.

**CSF biomarkers.** Baseline concentrations of total tau, phospho-tau,
amyloid-β, α-synuclein, neurofilament light chain (NfL), and GFAP.
SAA kinetic measures: time to threshold, time to 50% threshold,
fluorescence maximum, and area under the curve.

**Prodromal cohort.** Phenoconversion dates and status (PD, DLB, MSA)
for time-to-event analysis via Fine-Gray proportional
subdistribution hazards model, with DLB or MSA phenoconversion as
competing events.

**Population stratification.** Genetic principal components (PC1–10)
and European-ancestry flag derived from LD-pruned common biallelic
variants, used for sensitivity analyses.

### Genotyping

*MC1R* and monogenic variant calls derived from PPMI whole genome
sequencing (Genetics Core, Illumina, GATK Best Practices).

---

## 2. Replication cohorts — GP2 and clinical trial data

**Access:** Application for research access at
[gp2.org](https://gp2.org). Data last accessed March 11, 2026.

Three null clinical trials are used as replication cohorts. The agents
used in SURE-PD phase 2, SURE-PD3, and STEADY-PD III did not
demonstrate disease modification. In each, visits after initiation of
levodopa or dopamine agonist therapy are excluded.

### Required variables (per trial)

Longitudinal MDS-UPDRS III (summary and item-level for subscores),
medication status (levodopa, dopamine agonist, MAO-B inhibitor, and
LEDD), treatment arm assignment, demographics (age at onset, sex, race),
and *MC1R*/*LRRK2*/*GBA* carrier flags.

### SURE-PD3 (N=226; 167 *MC1R* LoF carriers, 59 non-carriers)

Genotyped by GP2 whole genome sequencing. Administered MDS-UPDRS III.

### SURE-PD phase 2 (N=74; 34 *MC1R* LoF carriers, 40 non-carriers)

Genotyped via the GP2 NeuroBooster Array with BEAGLE imputation against
the GP2 release 10 reference panel. V60L and rarer variants fell below
the imputation reliability threshold and are not called. Administered
original UPDRS III, converted to MDS-UPDRS III via Hoehn & Yahr
stage-specific calibration.

### STEADY-PD III (N=287; 209 *MC1R* LoF carriers, 78 non-carriers)

Genotyped by GP2 whole genome sequencing. Administered original UPDRS
III, converted to MDS-UPDRS III via Hoehn & Yahr stage-specific
calibration.
