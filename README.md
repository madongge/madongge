# Hi, I'm Dongge Ma (马岽戈) 👋

**Bioinformatics Undergraduate Researcher** @ [Zhejiang University–University of Edinburgh Institute (ZJE)](https://zje.intl.zju.edu.cn/)  
*Prospective PhD Student (Fall 2027)*  
📧 Email: `dongge.23@intl.zju.edu.cn` | 🌐 Location: Zhejiang, China

---

###  Research Interests
- **Generative AI for Biology**: Flow Matching, SE(3) Equivariant Networks, Diffusion Models
- **Structural Bioinformatics**: Protein Dynamics, Post-Translational Modifications (PTMs), Biomolecular Ensembles
- **Physical Relaxation & Evaluation**: Bridging generative proxy objectives with real-world force-field stability

---

###  Highlighted Research & Publications

- **Controllable Flow Matching for Protein Ensembles** *(First Author)*
  - *Status: Under Second-Round Review at AAAI (Double-Blind Review)*
  - Investigated secondary-structure steering in AlphaFlow-based ensemble generators; identified the proxy gap where ~70% raw structural gains dissipate after downstream physical relaxation.
  - *Anonymized manuscript available upon private request.*

- **[ProteinFlux: PTM-Conditioned Protein Conformational Dynamics](https://github.com/Mochimo-mo/ProteinFlux)** *(Third Author)*
  - *[📄 Preprint on bioRxiv (May 2026)](https://www.biorxiv.org/content/10.64898/2026.05.06.721822v1)* | *[💻 GitHub Repository](https://github.com/Mochimo-mo/ProteinFlux)* | Collaboration with Chi Ying Lab & Shipston Lab
  - PTM-conditioned SE(3) flow-matching architecture for generative prediction of protein conformational dynamics.
  - Contributed to model development, Invariant Point Attention (IPA) integration, flow-matching training, DSSP secondary-structure extraction (1,938 proteins), and multi-GPU distributed inference.

- **[*C. elegans* Dual-Channel Fluorescence Time-Lapse Stabilizer](https://github.com/madongge/celegans-frame-stabilizer#readme)** *(Summer Research Intern)*
  - *Summer Research @ ZJE Lingfeng Meng Lab (Jun – Aug 2024)* | *[💻 GitHub Repository & README](https://github.com/madongge/celegans-frame-stabilizer#readme)*
  - Cultured and maintained *C. elegans* strains; performed dual-channel spinning-disk confocal time-lapse fluorescence microscopy (`CSU GFP / mCherry`, 16-bit multi-frame TIFF stacks) to capture neuronal soma and axonal fluorescence signals.
  - Engineered an automated Python/OpenCV stabilization tool (`frame_stabilizer`) combining Gaussian local-contrast enhancement, Otsu-based ROI segmentation, and masked sub-pixel Enhanced Correlation Coefficient (`cv2.findTransformECC`) alignment with temporal trajectory smoothing across dual channels.

  [![C. elegans Stabilization Demo](https://raw.githubusercontent.com/madongge/celegans-frame-stabilizer/main/assets/demo_comparison.gif)](https://github.com/madongge/celegans-frame-stabilizer#readme)

- **[DynaMo-PTM: Molecular Dynamics Descriptors for Modified Proteins](https://kkkniengliu.github.io/dyna-mo-ptm-web/)** *(Fourth Author)*
  - *[📄 Preprint on bioRxiv (Aug 2026)](https://www.biorxiv.org/content/10.64898/2026.08.23.746532v1)* | *[🌐 Interactive Dataset Platform](https://kkkniengliu.github.io/dyna-mo-ptm-web/)*
  - Large-scale DynaMo-PTM benchmark dataset covering 1,079 AlphaFold 3-seeded systems and 32.37 μs aggregate MD sampling.
  - Engineered the end-to-end DynaMo-phos processing pipeline, PTM-aware atom14 tokenization, RMSD quality control, and feature extraction.

---

###  Technical Stack
- **Programming & Databases**: Python, Java, SQL (MySQL), PyTorch, NumPy, pandas, scikit-learn, Biopython, OpenCV, Pillow
- **Structural Bioinformatics & MD**: PyMOL, AlphaFold 3, DSSP, MDAnalysis, GROMACS / H5 Trajectory Processing, ESM2
- **Single-Cell & Sequence Analysis**: Scanpy, scvi-tools, CellTypist, scGPT, scANVI
- **Bioimaging & Wet-Lab**: *C. elegans* Husbandry, Spinning-Disk Confocal Fluorescence Microscopy, Fiji/ImageJ, Sub-Pixel Image Registration
- **Development Tools**: Git, GitHub, MySQL, Linux, Jupyter Notebook
