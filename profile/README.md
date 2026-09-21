# MRI Lab Graz

Welcome to the GitHub organization of **MRI Lab Graz**. We build open-source tools and pipelines for neuroimaging research, with a focus on the Brain Imaging Data Structure (BIDS) standard — data conversion, quality control, connectomics, and analysis. Below is an overview of our repositories, grouped by what they do.

---

## <img src="prism_logo.png" height="28" valign="middle" alt=""> Flagship: PRISM

**[prism-studio](https://github.com/MRI-Lab-Graz/prism-studio)** ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) — an independent, BIDS-compatible framework and toolkit for enriching standard BIDS datasets with psychological and physiological metadata. Our most actively developed project.

---

## 🔄 BIDS Conversion & Data Management
- **[BIDS_Conversion](https://github.com/MRI-Lab-Graz/BIDS_Conversion)** ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) — DICOM/raw data to BIDS conversion.
- **[Nextflow-dcm-converter](https://github.com/MRI-Lab-Graz/Nextflow-dcm-converter)** ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) — conversion pipeline using BIDS coiner.
- **[bids-dataset-tools](https://github.com/MRI-Lab-Graz/bids-dataset-tools)** ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) — tools to modify an existing BIDS dataset.
- **[publicBIDS](https://github.com/MRI-Lab-Graz/publicBIDS)** ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) — prepare a BIDS dataset for public release.
- **[datalad](https://github.com/MRI-Lab-Graz/datalad)** ![Shell](https://img.shields.io/badge/-Shell-89E051?logo=gnubash&logoColor=black) — DataLad implementation and HPC connection.
- **[DataLad-desktop](https://github.com/MRI-Lab-Graz/DataLad-desktop)** ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript&logoColor=black) — stable, cross-platform DataLad version control, no GitHub Desktop dependency.

## ✅ BIDS App Runners & Quality Control
- **[bids_apps_runner](https://github.com/MRI-Lab-Graz/bids_apps_runner)** ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) — run BIDS apps from a JSON definition file.
- **[check_bids_app](https://github.com/MRI-Lab-Graz/check_bids_app)** ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) — check the output of several BIDS apps.
- **[bidspm](https://github.com/MRI-Lab-Graz/bidspm)** ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) — use bidspm without MATLAB.
- **[bids-cat12-wrapper](https://github.com/MRI-Lab-Graz/bids-cat12-wrapper)** ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) — standalone CAT12 wrapper for the terminal.
- **[bids-fastsurfer](https://github.com/MRI-Lab-Graz/bids-fastsurfer)** ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) — scripts and notes from the FastSurfer workshop 2025 (Bonn).
- **[QualityControl](https://github.com/MRI-Lab-Graz/QualityControl)** ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) — QA for DICOM, physio, and spectroscopy data.

## 🧠 Connectomics & Analysis
- **[opticonn](https://github.com/MRI-Lab-Graz/opticonn)** ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) — extract connectomics with DSI Studio and run statistical analysis.
- **[connectoflow](https://github.com/MRI-Lab-Graz/connectoflow)** ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) — connectivity analysis based on denoised fMRIPrep data.
- **[dsistuido](https://github.com/MRI-Lab-Graz/dsistuido)** ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) — command-line tools for DSI Studio.
- **[braingraph](https://github.com/MRI-Lab-Graz/braingraph)** ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) — import and analyse brain-derived connectomics using graph theory.
- **[ModelArray](https://github.com/MRI-Lab-Graz/ModelArray)** ![Shell](https://img.shields.io/badge/-Shell-89E051?logo=gnubash&logoColor=black) — R tools for voxel and fixel data.
- **[flex-analysis](https://github.com/MRI-Lab-Graz/flex-analysis)** ![R](https://img.shields.io/badge/-R-276DC3?logo=r&logoColor=white) — portable, config-driven FreeSurfer/hipsta longitudinal statistical analysis pipeline.
- **[conn-tools](https://github.com/MRI-Lab-Graz/conn-tools)** ![MATLAB](https://img.shields.io/badge/-MATLAB-0076A8?logo=mathworks&logoColor=white) — tools for the Conn toolbox.

## 🧪 Study & Lab Tools
- **[survey](https://github.com/MRI-Lab-Graz/survey)** ![HTML](https://img.shields.io/badge/-HTML-E34F26?logo=html5&logoColor=white) — tools for online surveys (BIDS).
- **[participant_barcode](https://github.com/MRI-Lab-Graz/participant_barcode)** ![TeX](https://img.shields.io/badge/-TeX-008080?logo=latex&logoColor=white) — individual subject info including barcode.
- **[pyproject_installer](https://github.com/MRI-Lab-Graz/pyproject_installer)** ![Shell](https://img.shields.io/badge/-Shell-89E051?logo=gnubash&logoColor=black) — install a PsychoPy project from a GitHub link, with a matching venv.
- **[speech2text](https://github.com/MRI-Lab-Graz/speech2text)** ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) — speech-to-text utilities.

## 🎓 For Students
- **[master-thesis-overleaf](https://github.com/MRI-Lab-Graz/master-thesis-overleaf)** ![TeX](https://img.shields.io/badge/-TeX-008080?logo=latex&logoColor=white) — LaTeX master's thesis template for Overleaf, Institute of Psychology Graz.

## 🗂️ Misc
- **[openneuro-crawler](https://github.com/MRI-Lab-Graz/openneuro-crawler)** ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) — crawls OpenNeuro for resting-state fMRI datasets and cross-references acquisition date/location with historical weather.

---

## Contributing
We welcome contributions from the community — bug fixes, documentation, or new features. Feel free to open issues or pull requests in the relevant repository.

## Contact
Questions, feedback, or collaboration inquiries: **karl.koschutnig@uni-graz.at**, or open an issue in this repository.

---

Thank you for visiting our organization! 🌟
