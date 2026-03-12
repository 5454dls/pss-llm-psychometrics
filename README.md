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

This repository intentionally includes only the minimum files necessary to inspect the core analytical logic and LLM feature extraction approach:

- `README.md` — repository overview and usage notes
- `core_analysis.py` — core code for preprocessing, feature extraction workflow, and main analyses
- `prompt_1.txt` — first LLM prompt used for feature extraction
- `prompt_2.txt` — second LLM prompt used for feature extraction

## Data availability

The underlying participant-level data are **not publicly available** due to privacy, confidentiality, and institutional restrictions.

Accordingly, this repository does not include raw data, processed data, or any participant-identifiable information.

## Code availability

This repository provides the core code required to understand the analytical workflow and the prompt design used for LLM-based feature extraction.

Because the original data are not included, exact numerical reproduction of the study results is not possible without authorized access to the source dataset.

## Purpose of this repository

The purpose of this repository is to provide transparency regarding:

- the core analytic workflow
- the LLM prompting approach
- the overall computational logic underlying the study

It is intended to support editorial and peer review evaluation at this stage, and public methodological transparency after publication.

## Intended use

This repository is provided for research transparency and methodological inspection only.

It is not intended for clinical use, diagnosis, treatment decisions, or deployment as a standalone mental health assessment tool.
