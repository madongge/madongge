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

- **[ProteinFlux: PTM-Conditioned Protein Dynamics](https://www.biorxiv.org/content/10.64898/2026.05.06.721822v1)** *(Third Author)*
  - *Preprint on bioRxiv (May 2026)* | Collaboration with Chi Ying Lab & Shipston Lab
  - PTM-conditioned SE(3) flow-matching architecture for generative prediction of protein conformational dynamics.
  - Contributed to model development, Invariant Point Attention (IPA) integration, flow-matching training, and multi-GPU distributed inference.

- **[Molecular dynamics descriptors for 1,079 post-translationally modified protein systems](https://www.biorxiv.org/content/10.64898/2026.08.23.746532v1)** *(Fourth Author)*
  - *Preprint on bioRxiv (Aug 2026)* | [🌐 Interactive Dataset Platform](https://kkkniengliu.github.io/dyna-mo-ptm-web/)
  - Large-scale DynaMo-PTM benchmark dataset covering 1,079 AlphaFold 3-seeded systems and 32.37 μs aggregate MD sampling.
  - Engineered the end-to-end DynaMo-phos processing pipeline, PTM-aware atom14 tokenization, RMSD quality control, and feature extraction.
 
- **[*C. elegans* Dual-Channel Fluorescence Time-Lapse Stabilizer](https://github.com/madongge/celegans-frame-stabilizer#readme)**
*Summer Research @ Lingfeng Meng Lab, ZJU–UoE (ZJE) Institute (Jun – Aug 2024)*
- **Wet-Lab & Bioimaging**: Cultured and maintained *C. elegans* strains; performed dual-channel spinning-disk confocal time-lapse fluorescence microscopy (`CSU GFP / mCherry`, 16-bit multi-frame TIFF stacks) to image neuronal soma and axonal puncta.
- **Sub-Pixel ECC Stabilization Pipeline**: Built an automated Python/OpenCV image-stabilization tool ([`frame_stabilizer`](https://github.com/madongge/celegans-frame-stabilizer#readme)) combining Gaussian local-contrast enhancement, Otsu-guided ROI segmentation, and masked Enhanced Correlation Coefficient (`cv2.findTransformECC`) sub-pixel alignment with temporal trajectory smoothing.
- **Cross-Channel Registration & Lab Deployment**: Propagated learned affine warp matrices from Channel 1 to Channel 2 to lock dual-channel neuronal fluorescence in place across 400-frame recordings, and packaged the tool as a standalone `.exe` for lab workflows.
[![C. elegans Stabilization Demo](https://raw.githubusercontent.com/madongge/celegans-frame-stabilizer/main/assets/demo_comparison.gif)](https://github.com/madongge/celegans-frame-stabilizer#readme)
>  **[Click here or on the animation above to view the full documentation & algorithmic pipeline →](https://github.com/madongge/celegans-frame-stabilizer#readme)**


- **[scRNA-foundation-benchmark](https://github.com/madongge/scRNA-foundation-benchmark)**
  - Systematic benchmark of single-cell foundation models (scGPT, scANVI, CellTypist) vs. traditional KNN baseline on 10x Genomics PBMC datasets.

- **[PTPN3-YWHAB-AlphaFold3](https://github.com/madongge/PTPN3-YWHAB-AlphaFold3)**
  - AlphaFold3 complex modeling & PyMOL biophysical interaction analysis of phosphorylation-dependent binding.

---

###  Technical Stack
`Python` • `PyTorch` • `AlphaFold3` • `AlphaFlow` • `PyMOL` • `MDAnalysis` • `ESM2` • `Scanpy` • `Git/Linux`
