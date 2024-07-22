## Neurocomputational Approaches to Emotion Representation (EmoRep)

Codebase to support NIMH Grant : R01-MH124112-01

This organization is under construction.

<!--

TODO:
- Introduction
- Description of project
- Links to papers
- Description of workflow-repository mapping

-->

### Basic workflow:

1. Conduct task protocol, which involves presenting task during simulatenout acquistion of MRI and physio data : *scanner_tasks*
1. Build BIDS rawdata data structures from acquired sourcedata and NKI archive via : [build_rawdata](https://github.com/labarlab-emorep/build_rawdata)
1. Check data quality via : [func_mriqc](https://github.com/labarlab-emorep/func_mriqc)
1. Pre-process MRI data via : [func_preprocess](https://github.com/labarlab-emorep/func_preprocess)
1. Model functional MRI data via : [func_model](https://github.com/labarlab-emorep/func_model)
1. Preprocess and model archival data via : *func_archival*
1. Aggregate task and survey responses via : [make_reports](https://github.com/labarlab-emorep/make_reports)
1. Clean and classify physio data via : *physio_process*
1. Classify functional MRI data via : *classify_func*
1. Apply classification to rsFMRI data via : *classify_rest*
1. Model rsFMRI classification via : *rsfmri_hmm*

