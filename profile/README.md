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

1. Collect simultaneous fMRI and physio data during task presentation : *scanner_tasks*
1. Build BIDS rawdata data structures from acquired sourcedata and NKI archive: [build_rawdata](https://github.com/labarlab-emorep/build_rawdata)
1. Check data quality: [func_mriqc](https://github.com/labarlab-emorep/func_mriqc)
1. Pre-process MRI data: [func_preprocess](https://github.com/labarlab-emorep/func_preprocess)
1. Model functional MRI data: [func_model](https://github.com/labarlab-emorep/func_model)
1. Preprocess and model archival data: [func_archival](https://github.com/labarlab-emorep/func_archival)
1. Aggregate task and survey responses: [make_reports](https://github.com/labarlab-emorep/make_reports)
1. Clean and classify physio data: *physio_process*
1. Classify functional MRI data: *classify_func*
1. Apply classification to rsFMRI data: [classify_rest](https://github.com/labarlab-emorep/classify_rest)
1. Model rsFMRI classification: *rsfmri_hmm*

