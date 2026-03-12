# PSS-LLM-Psychometrics

This repository contains the core code and prompt files for the study evaluating large language model (LLM)-derived stress-related language features as a psychometric measurement framework for repeated stress assessment.

## Repository status

This repository is currently maintained as a **private repository** and is being shared **only with editors and reviewers** for peer review purposes.

If the manuscript is accepted and published, the repository will be made **publicly available** in its final curated form.

## Overview

Most prior LLM studies in mental health have emphasized classification against questionnaire-based thresholds. In contrast, this study examines whether LLM-derived language features can function as a **measurement-oriented psychometric signal** in repeated, real-world stress assessments.

Using longitudinal language data collected in a naturalistic repeated-assessment setting, we evaluated whether LLM-extracted features demonstrate:

- repeatability across repeated extractions  
- convergent validity with conventional psycholinguistic features  
- ecological validity with daily stress measures  
- incremental value beyond conventional text-derived features  
- clinical face validity through blinded expert evaluation  

## Repository contents

This repository intentionally includes only the minimum files necessary to inspect the core analytical logic, the LLM prompting approach, the expert evaluation materials, and the derived feature-level outputs used in the study:

- `README.md` — repository overview and usage notes
- `main_analysis.py` — core code for preprocessing, feature extraction workflow, and main analyses
- `prompt.txt` — LLM prompt used for feature extraction
- `blinded_expert_evaluation_format.xlsx` — example format for the blinded expert evaluation
- `misclassified_case_analysis_format.xlsx` — example format for the expert review of the 42 misclassified cases
- `liwc_extracted_features.csv` — LIWC-derived feature outputs used in the analyses
- `llm_extracted_features_main_analysis.csv` — LLM-derived feature outputs used in the main analyses

## Data availability

The original participant-level source data, including raw text/transcript data and PSS-related data, are not publicly available due to privacy, confidentiality, and institutional restrictions.

However, to support methodological transparency, this repository includes selected derived feature-level outputs used in the study, including LIWC-derived features and the LLM-derived features used in the main analyses.

These shared files do not include raw source text, original questionnaire responses, or participant-identifiable information.

## Code availability

This repository provides the core code, prompt material, and selected derived feature-level outputs required to understand and partially reproduce the analytical workflow underlying the study.

Because the original raw text data and PSS-related source data are not included, full end-to-end reproduction from source inputs is not possible without authorized access to the underlying dataset.

## Purpose of this repository

The purpose of this repository is to provide transparency regarding:

- the core analytic workflow
- the LLM prompting approach
- the overall computational logic underlying the study

It is intended to support editorial and peer review evaluation at this stage, and public methodological transparency after publication.

## Intended use

This repository is provided for research transparency and methodological inspection only.

It is not intended for clinical use, diagnosis, treatment decisions, or deployment as a standalone mental health assessment tool.
