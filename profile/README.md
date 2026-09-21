# MRI Lab Graz

Welcome to the GitHub organization of **MRI Lab Graz**. We build open-source tools and pipelines for neuroimaging research, with a focus on the Brain Imaging Data Structure (BIDS) standard — data conversion, quality control, connectomics, and analysis. Below is an overview of our repositories, grouped by what they do.

---

## Flagship: PRISM

**[prism-studio](https://github.com/MRI-Lab-Graz/prism-studio)** — an independent, BIDS-compatible framework and toolkit for enriching standard BIDS datasets with psychological and physiological metadata. Our most actively developed project.

---

## BIDS Conversion & Data Management
- **[BIDS_Conversion](https://github.com/MRI-Lab-Graz/BIDS_Conversion)** — DICOM/raw data to BIDS conversion.
- **[Nextflow-dcm-converter](https://github.com/MRI-Lab-Graz/Nextflow-dcm-converter)** — conversion pipeline using BIDS coiner.
- **[bids-dataset-tools](https://github.com/MRI-Lab-Graz/bids-dataset-tools)** — tools to modify an existing BIDS dataset.
- **[publicBIDS](https://github.com/MRI-Lab-Graz/publicBIDS)** — prepare a BIDS dataset for public release.
- **[datalad](https://github.com/MRI-Lab-Graz/datalad)** — DataLad implementation and HPC connection.
- **[DataLad-desktop](https://github.com/MRI-Lab-Graz/DataLad-desktop)** — stable, cross-platform DataLad version control, no GitHub Desktop dependency.

## BIDS App Runners & Quality Control
- **[bids_apps_runner](https://github.com/MRI-Lab-Graz/bids_apps_runner)** — run BIDS apps from a JSON definition file.
- **[check_bids_app](https://github.com/MRI-Lab-Graz/check_bids_app)** — check the output of several BIDS apps.
- **[bidspm](https://github.com/MRI-Lab-Graz/bidspm)** — use bidspm without MATLAB.
- **[bids-cat12-wrapper](https://github.com/MRI-Lab-Graz/bids-cat12-wrapper)** — standalone CAT12 wrapper for the terminal.
- **[bids-fastsurfer](https://github.com/MRI-Lab-Graz/bids-fastsurfer)** — scripts and notes from the FastSurfer workshop 2025 (Bonn).
- **[QualityControl](https://github.com/MRI-Lab-Graz/QualityControl)** — QA for DICOM, physio, and spectroscopy data.

## Connectomics & Analysis
- **[opticonn](https://github.com/MRI-Lab-Graz/opticonn)** — extract connectomics with DSI Studio and run statistical analysis.
- **[connectoflow](https://github.com/MRI-Lab-Graz/connectoflow)** — connectivity analysis based on denoised fMRIPrep data.
- **[dsistuido](https://github.com/MRI-Lab-Graz/dsistuido)** — command-line tools for DSI Studio.
- **[braingraph](https://github.com/MRI-Lab-Graz/braingraph)** — import and analyse brain-derived connectomics using graph theory.
- **[ModelArray](https://github.com/MRI-Lab-Graz/ModelArray)** — R tools for voxel and fixel data.
- **[flex-analysis](https://github.com/MRI-Lab-Graz/flex-analysis)** — portable, config-driven FreeSurfer/hipsta longitudinal statistical analysis pipeline.
- **[conn-tools](https://github.com/MRI-Lab-Graz/conn-tools)** — tools for the Conn toolbox.

## Study & Lab Tools
- **[survey](https://github.com/MRI-Lab-Graz/survey)** — tools for online surveys (BIDS).
- **[participant_barcode](https://github.com/MRI-Lab-Graz/participant_barcode)** — individual subject info including barcode.
- **[pyproject_installer](https://github.com/MRI-Lab-Graz/pyproject_installer)** — install a PsychoPy project from a GitHub link, with a matching venv.
- **[speech2text](https://github.com/MRI-Lab-Graz/speech2text)** — speech-to-text utilities.

## For Students
- **[master-thesis-overleaf](https://github.com/MRI-Lab-Graz/master-thesis-overleaf)** — LaTeX master's thesis template for Overleaf, Institute of Psychology Graz.

## Misc
- **[openneuro-crawler](https://github.com/MRI-Lab-Graz/openneuro-crawler)** — crawls OpenNeuro for resting-state fMRI datasets and cross-references acquisition date/location with historical weather.

---

## Contributing
We welcome contributions from the community — bug fixes, documentation, or new features. Feel free to open issues or pull requests in the relevant repository.

## Contact
Questions, feedback, or collaboration inquiries: **karl.koschutnig@uni-graz.at**, or open an issue in this repository.

---

Thank you for visiting our organization! 🌟
