---
permalink: /publications/
title: "Publications"
author_profile: true
---

Full list on [Google Scholar](https://scholar.google.com/citations?user=RPX33-EAAAAJ).

## Journal articles

**Evaluation of Classical and Deep-Learning Deformable Registration for MR to 4D-CT Contour Mapping in Liver Stereotactic Body Radiotherapy**  
**Z. Kheil**, L. Risser, E. Cohen-Jonathan Moyal, S. Ken  
*Physics and Imaging in Radiation Oncology*, 2026  
A clinical benchmark of classical and deep learning methods for mapping contours from MRI onto each breathing phase of a 4D-CT, on 170 liver SBRT patients.  
[Paper](https://doi.org/10.1016/j.phro.2026.100969)

**Incorporating Sliding and Local Rigidity Constraints in Neural-Based Image Registration**  
**Z. Kheil**, S. Ken, L. Risser  
*Scientific Reports*, 2026  
Builds physical priors into neural registration: organs that slide against each other and structures that should stay rigid, so predicted deformations stay physically plausible.  
[Preprint](https://arxiv.org/abs/2504.05444) · [Code](https://github.com/Kheil-Z/biomechanical_DLIR) · [Playground](https://huggingface.co/spaces/HocusPocus98/biomechanical-dlir-loss-playground)

**FGFR Inhibition as a New Therapeutic Strategy to Sensitize Glioblastoma Stem Cells to Tumor Treating Fields**  
P. Deshors, **Z. Kheil**, L. Ligat, V. Gouazé-Andersson, E. Cohen-Jonathan Moyal  
*Cell Death Discovery*, 2025  
Shows that FGFR inhibition with pemigatinib sensitizes glioblastoma stem cells to Tumor Treating Fields.  
[Paper](https://doi.org/10.1038/s41420-025-02542-5)

## Conference papers

**IMITATE: Image Registration with Context for Unknown Time Frame Recovery**  
**Z. Kheil**, L. Robinet, L. Risser, S. Ken  
*IEEE International Symposium on Biomedical Imaging (ISBI)*, 2025, oral presentation  
Recovers missing or corrupted breathing phases in 4D-CT with context-aware registration.  
[Paper](https://arxiv.org/abs/2505.10124) · [Code](https://github.com/Kheil-Z/IMITATE)

**DRIM: Learning Disentangled Representations from Incomplete Multimodal Healthcare Data**  
L. Robinet, A. Berjaoui, **Z. Kheil**, E. Cohen-Jonathan Moyal  
*Medical Image Computing and Computer-Assisted Intervention (MICCAI)*, 2024  
Multimodal learning across MRI, histopathology and omics that separates shared and modality-specific information, and handles missing modalities.  
[Paper](https://arxiv.org/abs/2409.17055) · [Code](https://github.com/Lucas-rbnt/DRIM)

## Code

- [**biomechanical_DLIR**](https://github.com/Kheil-Z/biomechanical_DLIR): PyTorch framework for registration with physical constraints (rigid structures, sliding interfaces, learned tissue mechanics), with an [interactive loss playground](https://huggingface.co/spaces/KZ98/biomechanical-dlir-loss-playground).
- [**IMITATE**](https://github.com/Kheil-Z/IMITATE): context-aware registration for recovering time frames in 4D-CT.
- [**DRIM**](https://github.com/Lucas-rbnt/DRIM) (co-author): disentangled multimodal learning across MRI, histopathology and omics, robust to missing modalities.
- [**Elenchus**](https://github.com/Kheil-Z/elenchus): a multiplayer LLM workspace, where a team and its AI models share one thread.
- Contributor to [**MONAI**](https://github.com/Project-MONAI/MONAI), the PyTorch framework for medical imaging.
