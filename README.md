# ICML 2026 · AI x Biomedical Papers

> A curated collection of **315 papers** from ICML 2026 at the intersection of AI and biomedicine.


[![Papers](https://img.shields.io/badge/papers-315-22d3ee?style=flat-square)](papers.json)
[![Spotlights](https://img.shields.io/badge/spotlights-27-f59e0b?style=flat-square)](#)
[![Categories](https://img.shields.io/badge/categories-10-818cf8?style=flat-square)](#contents)
[![License](https://img.shields.io/badge/license-CC0-34d399?style=flat-square)](LICENSE)

Machine-readable data: [`papers.json`](papers.json) — 315 papers with titles, authors, abstracts, keywords, PDF and code links.

---

## Contents

- [Protein Design & Structure](#protein-design--structure) (47)
- [Drug Discovery & Molecular Design](#drug-discovery--molecular-design) (45)
- [Genomics & Sequence Biology](#genomics--sequence-biology) (30)
- [Single-Cell & Spatial Omics](#single-cell--spatial-omics) (14)
- [Clinical AI & Healthcare](#clinical-ai--healthcare) (88)
- [Medical Imaging](#medical-imaging) (26)
- [Neuroscience & Brain](#neuroscience--brain) (53)
- [Immunology & Microbiology](#immunology--microbiology) (2)
- [Oncology](#oncology) (1)
- [Structural Biology & MD Simulation](#structural-biology--md-simulation) (9)

---

## Protein Design & Structure

> Protein structure prediction, binder design, inverse folding, and protein language models.

### Chamaileon: Cross-Context Binder Design with Contextualized Modeling and Mixed Sampling 🌟 **Spotlight**
*Hengyuan Cao, Shizhuo Cheng, Mingxuan Liu, Weicheng Huang*

> The rapid evolution of generative models has unlocked new potentials in protein binder design, a pivotal task in structural biology, by facilitating end-to-end generation via joint sequence-structure modeling or hallucin...

**Keywords:** cross-context binder design, in-context generation, mixed sampling, diffusion model

[PDF](https://openreview.net/pdf/ccbe9db5da89566c2659746f3bc6ffe601c41d8b.pdf) · [Code](https://github.com/caohengyuan/Chamaileon) · [OpenReview](https://openreview.net/forum?id=JAQ9bm0Rp4)

---

### FIDIA: Function-Informed Sequence Design via Inference-Aligned Policy Optimization 🌟 **Spotlight**
*Minghan Li, Fengji Li, Yilin Tao, Yue Deng*

> Computational protein design typically employs a sequential workflow of structure generation followed by sequence (re)design. While structure generators can be explicitly conditioned on functional objectives, inverse fol...

**Keywords:** Protein Inverse Folding; Best-of-N Inference Alignment; Gradient Estimation

[PDF](https://openreview.net/pdf/05d621a378fd331663d4dc6ed294f523cba7ba66.pdf) · [Code](https://github.com/deng-ai-lab/FIDIA-code) · [OpenReview](https://openreview.net/forum?id=pvbJsa0ia0)

---

### FLIP2: Expanding Protein Fitness Landscape Benchmarks for Real-World Machine Learning Applications 🌟 **Spotlight**
*Kieran Didi, Sarah Alamdari, Alex Xijie Lu, Bruce James Wittmann et al.*

> Machine learning methods that predict protein fitness from sequence remain sensitive to changes in data distributions, limiting generalization across common conditions encountered in protein engineering. Practically, pro...

**Keywords:** protein engineering, machine learning, protein language models, benchmarks

[PDF](https://openreview.net/pdf/2df19db58cdcfb66484b40d86c6a8230e18b60ca.pdf) · [OpenReview](https://openreview.net/forum?id=Ue8aOgz9T9)

---

### Protein Autoregressive Modeling via Multiscale Structure Generation 🌟 **Spotlight**
*Yanru Qu, Cheng-Yen Hsieh, Zaixiang Zheng, Ge Liu*

> We present protein autoregressive modeling (PAR), the first multi-scale autoregressive framework for protein backbone generation via coarse-to-fine next-scale prediction. Using the hierarchical nature of proteins, PAR ge...

**Keywords:** Protein backbone generation, Multi-scale autoregressive modeling, Zero-shot generalization

[PDF](https://openreview.net/pdf/ac6410d483ab6418490d0f3ece5b3dbd895dd8bd.pdf) · [Code](https://par-protein.github.io/) · [OpenReview](https://openreview.net/forum?id=08tW615mgI)

---

### Protein Fold Classification at Scale: Benchmarking and Pretraining 🌟 **Spotlight**
*Dexiong Chen, Andrei Manolache, Mathias Niepert, Karsten Borgwardt*

> Classifying protein topology is essential for deciphering biological function, but progress is held back by the lack of large-scale benchmarks that avoid duplicates and by models that do not scale well. We introduce TEDB...

**Keywords:** protein fold classification, benchmarking, protein representation learning, masked autoencoders

[PDF](https://openreview.net/pdf/d1a6173984d1a6f0efc6b2876f6835a2d0784d63.pdf) · [Code](https://github.com/BorgwardtLab/TEDBench) · [OpenReview](https://openreview.net/forum?id=jPKqiaPTEd)

---

### TD3B: Transition-Directed Discrete Diffusion for Allosteric Binder Generation 🌟 **Spotlight**
*Hanqun Cao, Aastha Pal, Sophia Tang, Yinuo Zhang*

> Protein function is often controlled by ligands that bias the direction of state transitions, such as agonists and antagonists, rather than stabilizing a single conformation. This is especially important for clinically r...

**Keywords:** Generative modeling, discrete diffusion, molecular design, protein-ligand interactions

[PDF](https://openreview.net/pdf/de97db8e2505a6b7de1f387c3a9ab3332cf6ccf3.pdf) · [Code](https://huggingface.co/ChatterjeeLab/TD3B) · [OpenReview](https://openreview.net/forum?id=RNuC8Nj6rD)

---

### Towards Sub-Second Molecular Docking as a Structural Primitive: A Quantized Consistency Diffusion Framework 🌟 **Spotlight**
*Kexin Zhang, Weichen Qin, Yue Teng, Jiale Yu et al.*

> Agent-centered scientific discovery is turning scientific models into always-on computational infrastructure. In this paradigm, AI agents coordinate tools, interpret feedback, and drive high-frequency research loops, req...

**Keywords:** Molecular Docking, Diffusion Models, Consistency Regularization, Quantized Residual Learning

[PDF](https://openreview.net/pdf/0bea51c5e68808ee6259901d37c39361bb3a5e4b.pdf) · [Code](https://github.com/KexinZhangResearch/PhysDock) · [OpenReview](https://openreview.net/forum?id=NyPHOtsJfE)

---

### BioDynaSpec: Harmonic-Guided Spatio-Spectral Autoregressive Diffusion for Protein Dynamics Generation
*Mujie Lin, Yutian Liu, Yudi Guo, Yanzhen Hou et al.*

> Generating long-horizon molecular dynamics (MD) is difficult due to error accumulation in time-domain autoregressive models, which causes drift, and fixed step-size constraints on temporal resolution. We propose **BioDyn...

**Keywords:** Protein Dynamics, Molecular Dynamics Generation, Generative Models, Local Near-Equilibrium Dynamics

[PDF](https://openreview.net/pdf/cbc54a4ef6d77da0fbd886ac0f56439bc3cef1a3.pdf) · [Code](https://github.com/Linmj-Judy/BioDynaSpec.git) · [OpenReview](https://openreview.net/forum?id=TwMRZPkn4e)

---

### CalPro: Prior-Aware Evidential Conformal Prediction with Structure-Aware Sensitivity Bounds for Protein Structures
*Ibne Farabi Shihab, Sanjeda Akter, Anuj Sharma*

> Deep protein structure predictors such as AlphaFold provide confidence estimates (e.g., pLDDT) that are not calibrated and degrade under distribution shifts across experimental modalities, temporal changes, and disordere...

**Keywords:** conformal prediction, uncertainty quantification, evidential deep learning, Normal–Inverse-Gamma

[PDF](https://openreview.net/pdf/d6a0cc76579267577c45f956686cbbbc8be8286f.pdf) · [OpenReview](https://openreview.net/forum?id=3LRWjJTp0Y)

---

### Co-Generative De Novo Functional Protein Design
*Xinrui Chen, Yizhen Luo, Siqi Fan, Zaiqing Nie*

> *De novo* functional protein design aims to generate protein sequences that realize specified biochemical functions without relying on evolutionary templates, enabling broad applications in biotechnology and medicine. Ex...

**Keywords:** function, protein design, co-generation

[PDF](https://openreview.net/pdf/a3bbcbc9d1c42825c5d4908c429fe78c8b3df4d0.pdf) · [Code](https://github.com/PharMolix/OpenBioMed) · [OpenReview](https://openreview.net/forum?id=O4BmkfXv1f)

---

### Conditionally Site-Independent Neural Evolution of Antibody Sequences
*Stephen Zhewen Lu, Aakarsh Vermani, Kohei Sanno, Jiarui Lu*

> Common deep learning approaches for antibody engineering focus on modeling the marginal distribution of sequences. By treating sequences as independent samples, however, these methods overlook affinity maturation as a ri...

**Keywords:** antibody evolution, substitution models, neural Markov chain, classifier guidance

[PDF](https://openreview.net/pdf/296aab2258ea05d3ba255240cba1c65df5ecc03a.pdf) · [Code](https://github.com/thematrixmaster/cosine) · [OpenReview](https://openreview.net/forum?id=DcyK4f7ZyU)

---

### Cross-Chirality Generalization by Axial Vectors for Hetero-Chiral Protein-Peptide Interaction Design
*Ziyi Yang, Zitong Tian, Yinjun Jia, Tianyi Zhang et al.*

> D-peptide binders targeting L-proteins have promising therapeutic potential. Despite rapid advances in machine learning-based target-conditioned peptide design, generating D-peptide binders remains largely unexplored. In...

**Keywords:** Equivariance, GNN, Peptide design, Mirror-image binders

[PDF](https://openreview.net/pdf/4850f70d81dd9c85f4923e11cb5634ec10a25a9c.pdf) · [Code](https://github.com/YZY010418/PepMirror) · [OpenReview](https://openreview.net/forum?id=mAusAlRZ0a)

---

### Demystifying Multimodal Biomolecular Co-design With Intrinsic Geodesic Coupling
*Keyue Qiu, Xintong Wang, Zhilong Zhang, Hao Zhou*

> Biomolecules such as proteins and small-molecule ligands play a central role in biological systems, arising from the tight interplay between sequence and three-dimensional structure. Recent generative models for biomolec...

**Keywords:** multi-modality, structure-based drug design, protein design

[PDF](https://openreview.net/pdf/2756f3bd78251b352c0b7b16878fad53763ef051.pdf) · [OpenReview](https://openreview.net/forum?id=SSoOP9ia5t)

---

### Discrete Diffusion with Physical Mass Constraints for \emph{De Novo} Peptide Sequencing
*An Zeyu, Wanyu Lin*

> $\textit{De novo}$ peptide sequencing is a pivotal technique that directly reconstructs amino acid sequences from tandem mass spectrometry (MS/MS) data; it enables the identification of novel proteins and variants absent...

**Keywords:** De Novo Peptide Sequencing, Discrete Diffusion, Precursor Mass, Spectral Fragment Ion

[PDF](https://openreview.net/pdf/f6cedd01df5376f5e377865e8c01963abe9dc1ad.pdf) · [OpenReview](https://openreview.net/forum?id=tIG4D44jn9)

---

### Enhancing Protein-Protein Interaction Prediction with Hierarchical Motif-based Multimodal Protein Embedding
*Zaifei YANG, Samuel Ping-Man Choi, James Kwok*

> Protein-protein interactions (PPIs) are essential for many biological processes. However, existing PPI prediction approaches suffer from two major limitations: they overlook the hierarchical organization of proteins, par...

**Keywords:** Protein-Protein Interaction, Hierarchical Representation Learning, Multi-modality Fusion, Graph Neural Networks

[PDF](https://openreview.net/pdf/ee18aca8e69bb144c0f5cb7da40439050ef9a675.pdf) · [Code](https://github.com/yzf-code/MMM-PPI) · [OpenReview](https://openreview.net/forum?id=goPaAYr1J3)

---

### EpiCoCo: De Novo Epitope Generation via MHC-Context Co-Modeling and Contrastive Affinity Guidance
*Haoyang Luan, Gufeng Yu, Letian Chen, Zhenran Xiao*

> The *de novo* generation of high-affinity epitopes tailored to specific major histocompatibility complex (MHC) proteins is a pivotal challenge in computational immunotherapy. However, current methods struggle to effectiv...

**Keywords:** Immunotherapeutics, Peptide Design, Structure-Sequence Co-design

[PDF](https://openreview.net/pdf/a58f1d65071b8376ea0d95fd97ef34ad906017b7.pdf) · [Code](https://github.com/StevenLuan904/EpiCoCo) · [OpenReview](https://openreview.net/forum?id=qwtCnzt5B8)

---

### Explicit representation of germline and non-germline residues improves antibody language modeling
*Jeonghyeon Kim, Nathaniel Blalock, Ameya Kulkarni, Kensuke Nakamura*

> Antibodies originate from germline templates and are diversified by somatic hypermutation, producing sequences in which conserved germline residues scaffold structure while rare non-germline (NGL) substitutions refine an...

**Keywords:** Antibody Language Model, Disentangled Representaion Learning, Somatic Hypermutation, Controllable Protein Design

[PDF](https://openreview.net/pdf/c5495241d903f82eef38ab0ecfa2d41f6a2013a5.pdf) · [Code](https://github.com/RomeroLab/PRISM) · [OpenReview](https://openreview.net/forum?id=INxIx5piFC)

---

### Flexible Kernels for Protein Property Prediction
*Martin Jankowiak, Yerdos Ordabayev, Rudraksh Tuwani, Henry Neil Ward*

> Despite its importance to applications in protein design, predicting protein properties like binding affinity and thermostability from sparse experimental data remains a significant challenge. Accordingly, we introduce a...

**Keywords:** protein property prediction, gaussian processes, sequence kernels, protein foundation models

[PDF](https://openreview.net/pdf/90d4443d9450bec7d40b467917b15976e048df80.pdf) · [Code](https://github.com/generatebio/lock_gp) · [OpenReview](https://openreview.net/forum?id=uOSa4bbPDj)

---

### FlexiFlow: decomposable flow matching for generation of flexible molecular ensemble
*Riccardo Tedoldi, Ola Engkvist, Patrick Bryant, Hossein Azizpour*

> Sampling useful three-dimensional molecular structures along with their most favorable conformations is a key challenge in drug discovery. Current state-of-the-art 3D de-novo molecular design generative models are limite...

**Keywords:** de novo molecular generation, flow matching, drug discovery

[PDF](https://openreview.net/pdf/12f6d43bbcc6eb2797381f0bdc45da15785fa4bf.pdf) · [OpenReview](https://openreview.net/forum?id=iL4Uo9HeXc)

---

### GenUnfold: Rapidly Predict Protein Mechanical Unfolding Trajectory via a Physics-Guided Diffusion Model
*Yiyuan Zhang, Cailong Hua, VINITENDRA SINGH, Joseph M. Muretta*

> Many fundamental biological processes are governed by mechanical forces, with proteins acting as the key molecular mediators. Elucidating how protein unfolding responds to force is critical for understanding the mechano-...

**Keywords:** Diffusion Model, Protein Unfolding, Physics-guided

[PDF](https://openreview.net/pdf/33b230e5d72baa331b05b9c3fd2b9ee360a16c72.pdf) · [Code](https://github.com/SalapakaLab-SIMBioSys/Gen_Unfold) · [OpenReview](https://openreview.net/forum?id=wutI1P0dsB)

---

### Geometric Pocket-Centric Protein Encoding for Polypharmacology-Guided Multi-Target Drug Design
*Haoran liu, Xiaoli Lin, Jing Hu, Yu Zou*

> Polypharmacology provides a powerful strategy for treating complex diseases, but identifying molecules that simultaneously satisfy coupled constraints across multiple biological targets remains difficult. Existing method...

**Keywords:** drug design, Protein representation, Topology encoding

[PDF](https://openreview.net/pdf/bca4039e6d3cc3ed7d994e4c34234ba2a734f6c7.pdf) · [OpenReview](https://openreview.net/forum?id=DuaA7vJGF6)

---

### Immuno-VLM: Immunizing Large Vision-Language Models via Generative Semantic Antibodies for Open-World Trustworthiness
*Xiang Fang, Wanlong Fang, Wei Ji*

> Large Vision-Language Models have achieved unprecedented success in zero-shot recognition by aligning visual features with broad semantic concepts. However, this semantic abstraction creates a critical vulnerability in o...

**Keywords:** Immuno-VLM

[PDF](https://openreview.net/pdf/975b34792e31a93737adca74c79ed8f0b9ce5d46.pdf) · [OpenReview](https://openreview.net/forum?id=ZeZi4SerW0)

---

### Inference-time optimization for experiment-grounded protein ensemble generation
*Sai Advaith Maddipatla, Anar Rzayev, Marco Pegoraro, Martin Pacesa*

> Protein function relies on dynamic conformational ensembles, yet current generative models like AlphaFold3 (AF3) often fail to produce ensembles that match experimental data. Recent experiment-guided generators attempt t...

**Keywords:** protein generative models, alphafold, inference-time optimization, experiment-grounded ensemble generation

[PDF](https://openreview.net/pdf/4e8875a02d94cfa3f32871b4e7687e7b9b2de527.pdf) · [OpenReview](https://openreview.net/forum?id=kbhIfLokFn)

---

### Learning Protein Structure-Function Relationships through Knowledge-guided Representation Decomposition
*Mingqing Wang, Zhiwei Nie, ATHANASIOS V. VASILAKOS, Yonghong He*

> Proteins encode diverse functions within complex three-dimensional structures, yet most deep learning representations remain highly entangled, obscuring the biophysical signals that underlie function. Here we introduce P...

**Keywords:** disentangled representation learning, protein structural modeling, knowledge enhancement, mechanistic interpretability

[PDF](https://openreview.net/pdf/4d5a0f9bbfdc1d3b768075c57908a03b9a9219f6.pdf) · [Code](https://github.com/AI-HPC-Research-Team/ProtDiS) · [OpenReview](https://openreview.net/forum?id=OM0C7jyV0p)

---

### Learning the Interaction Prior for Protein-Protein Interaction Prediction: A Model-Agnostic Approach
*Ziqi Gao, Chenyi Zi, Zijing Liu, Ziqiao Meng*

> Protein-protein interactions (PPIs) are fundamental to cellular function, disease mechanisms, and drug discovery. Current learning-based PPI predictors focus on learning powerful protein representations but neglect desig...

**Keywords:** protein-protein interaction prediction, graph prompt learning, graph representation learning

[PDF](https://openreview.net/pdf/fab25cf56f5ff1d704ccc10327da6ef4d55935ef.pdf) · [OpenReview](https://openreview.net/forum?id=p7PPMKTPJp)

---

### LipoPU: Pocket-level Prediction of Lipid-Protein Interactions via Positive-Unlabeled Learning
*Yuxing Wang, Wenyi Zhang, Yilong Zou, Jing Huang*

> Computational identification of lipid-binding proteins is critical for both fundamental research and therapeutic development. Existing models are typically trained in a fully supervised manner, treating unlabeled samples...

**Keywords:** Lipid-protein interactions, Lipid-binding site prediction, Protein pockets, Positive-unlabeled (PU) learning

[PDF](https://openreview.net/pdf/e8219623d675da5b4182b9dcd6d3a9efec6ff210.pdf) · [Code](https://github.com/JingHuangLab/LipoPU) · [OpenReview](https://openreview.net/forum?id=1AyRuF9ULp)

---

### MacroGuide: Topological Guidance for Macrocycle Generation
*Alicja Maksymiuk, Alexandre Duplessis, Michael M. Bronstein, Alexander Tong*

> Macrocycles are ring-shaped molecules that offer a promising alternative to small-molecule drugs due to their enhanced selectivity and binding affinity against difficult targets. Despite their chemical value, they remain...

**Keywords:** Macrocycles, Topological Data Analysis, Molecule generation, Persistent Homology

[PDF](https://openreview.net/pdf/3f45f7471ba518542d39325b8193387183f9f125.pdf) · [Code](https://github.com/ala1705/MacroGuide) · [OpenReview](https://openreview.net/forum?id=Cdi2lBTm3M)

---

### MuCO: Generative Peptide Cyclization Empowered by Multi-stage Conformation Optimization
*Yitian Wang, Fanmeng Wang, Angxiao Yue, Wentao Guo*

> Modeling peptide cyclization is critical for the virtual screening of candidate peptides with desirable physical and pharmaceutical properties.   This task is challenging because a cyclic peptide often exhibits diverse, ...

**Keywords:** Cyclic Peptides, Multi-Scale Generative Modeling, All-Atom Protein Modeling

[PDF](https://openreview.net/pdf/acdf670ba08a1149cc91071ca6e3a6cc402da25b.pdf) · [Code](https://github.com/mianqiu00/MuCO) · [OpenReview](https://openreview.net/forum?id=6l8bvRoJZN)

---

### MutAtlas: A PDB-Wide Energy-Guided Atlas of Protein Mutation Effects
*Ruihan Guo, Chaoran Cheng, Zhanghan Ni, Neil He*

> Protein mutation effect prediction is fundamental to protein engineering and disease variant interpretation, yet experimentally measured mutation data remain accurate but extremely sparse. To provide scalable supplementa...

**Keywords:** Computational Structural Biology, Protein Engineering, Protein Mutation Effects, Energy-based Data Augmentation

[PDF](https://openreview.net/pdf/dda0012104c4de22796db5f44f23c498a8407ae8.pdf) · [Code](https://github.com/guoruihan/MutAtlas) · [OpenReview](https://openreview.net/forum?id=ZcVSBTJj2m)

---

### Nested birth-death processes are competitive with neural networks as time-dependent models of protein evolution
*Annabel Large, Ian Holmes*

> Most statistical phylogenetics analyses use simple continuous-time finite-state Markov models of point substitution to describe molecular evolution. These models enforce unrealistic assumptions like keeping sequence leng...

**Keywords:** biology, protein evolution, protein sequence embeddings, protein modeling

[PDF](https://openreview.net/pdf/cdcf370d3a910921a0dc116e827840f4df2c382d.pdf) · [Code](https://github.com/AnnabelLarge/protein_evolution_icml_2026) · [OpenReview](https://openreview.net/forum?id=qs9lQluekx)

---

### PDAgent: An LLM-Driven Autonomous Agent Framework Towards *In Silico* Protein Design via Directed Mutation
*Song Ouyang, Zhijie Dong, Yong Luo, Kehua Su*

> Computational protein design holds immense promise across diverse domains, but existing approaches face significant challenges: traditional physics-based methods require substantial domain expertise, while emerging deep ...

**Keywords:** AI for Science, Protein Design, Large Language Model, Agent

[PDF](https://openreview.net/pdf/7fcac72762c58bed2e4facda99f1f8154efd14a1.pdf) · [Code](https://github.com/Gift-OYS/PDAgent) · [OpenReview](https://openreview.net/forum?id=TwTvDVj6cH)

---

### PDFBench: A Benchmark for De Novo Protein Design from Function
*Jiahao Kuang, Nuowei Liu, Changzhi Sun, Jie Wang*

> Function-guided protein design is a crucial task with significant applications in drug discovery and enzyme engineering. However, the field lacks a unified and comprehensive evaluation framework. Current models are asses...

**Keywords:** De novo Protein Design, Protein Language Model, Evaluation Metric, Benchmark

[PDF](https://openreview.net/pdf/846ea864815b94b6940781f4ac965df2c3eecd27.pdf) · [Code](https://github.com/PDFBench/PDFBench) · [OpenReview](https://openreview.net/forum?id=Z6dCaMpiqV)

---

### PepCompass: Navigating Peptide Embedding Spaces Using Riemannian Geometry
*Marcin Możejko, Adam Bielecki, Jurand Prądzyński, Hyun-Su Lee et al.*

> Antimicrobial peptide discovery is challenged by the astronomical size of peptide space and the relative scarcity   of active peptides. While generative models provide latent maps of this space, they typically ignore dec...

**Keywords:** union of manifolds, peptide optimization, riemannian geometry, geodesics

[PDF](https://openreview.net/pdf/3a9067f690a666b7b86be4b45532798456931572.pdf) · [Code](https://github.com/szczurek-lab/pep-compass) · [OpenReview](https://openreview.net/forum?id=HENUU9VR8F)

---

### Preference-based Antibody Expression Ranking: Scaling with Large-scale Weak Supervision
*Josh Qixuan Sun, Morteza Babaie, Wenyang hou, Mark Crowley*

> Antibody expression ranking is a critical task in antibody design, yet its modelling is severely hindered by the scarcity of labeled experimental data. To address this, we propose a unified preference-based learning fram...

**Keywords:** antibody, expressibility, preference learning

[PDF](https://openreview.net/pdf/2890fa0b796dacbca4d375bd8d61296bbde78c01.pdf) · [OpenReview](https://openreview.net/forum?id=mrZiCCb3zv)

---

### ProMiSE: Protein Multi-State Evaluation Benchmark in Biological Contexts
*Bonjae Ku, Seeun Kim, Yubeen Kim, Hahnbeom Park*

> Proteins are inherently dynamic, with biological functions often emerging from transitions between multiple conformational states. While recent breakthroughs have largely addressed the static structure prediction problem...

**Keywords:** Multi-state Proteins, Benchmarks, Protein Structure Prediction

[PDF](https://openreview.net/pdf/c7d2578688f05fbe5165ab58fec34b5367bf24b5.pdf) · [Code](https://github.com/seoklab/promise-bench) · [OpenReview](https://openreview.net/forum?id=5ZN3tiSetW)

---

### ProtDBench: A Unified Benchmark of Protein Binder Design and Evaluation
*Cong Liu, Milong Ren, Jiaqi Guan, Chengyue Gong*

> Recent advances in $\textit{de novo}$ protein binder design have enabled increasing experimental validation, yet reported $\textit{in silico}$ metrics remain difficult to interpret or compare across studies due to non-st...

**Keywords:** AI4Science, Protein Design, Benchmarks

[PDF](https://openreview.net/pdf/768f34a1cfe3db0fa098afd33e9b57c887a3cb04.pdf) · [Code](https://github.com/congliuUvA/ProtDBench) · [OpenReview](https://openreview.net/forum?id=bWLfplRNzt)

---

### Protein Circuit Tracing via Cross-layer Transcoders
*Darin Tsui, Kunal Talreja, Daniel Saeedi, Amirali Aghazadeh*

> Protein language models (pLMs) have emerged as powerful predictors of protein structure and function. However, the computational circuits underlying their predictions remain poorly understood. Recent mechanistic interpre...

**Keywords:** Cross-layer transcoders, Circuit discovery, Protein language models, Mechanistic interpreability

[PDF](https://openreview.net/pdf/00501873eee46b7628fabdf8f6a24e029400c3c0.pdf) · [Code](https://github.com/amirgroup-codes/ProtoMech) · [OpenReview](https://openreview.net/forum?id=Ki0eWT1sFS)

---

### Protein Design with Agent Rosetta: A Case Study for Specialized Scientific Agents
*Jacopo Teneggi, SM Bargeen Alam Turzo, Tanya Marwah, Alberto Bietti*

> Large language models (LLMs) are capable of emulating reasoning and using tools, creating opportunities for autonomous agents that execute complex scientific tasks. Protein design provides a natural testbed: although mac...

**Keywords:** llm agents, ai for science, protein design, rosetta macromolecular modeling suite

[PDF](https://openreview.net/pdf/d7b676e9ae6ab5c8342eb2245e4960d13c490843.pdf) · [Code](https://github.com/PolymathicAI/agent-rosetta) · [OpenReview](https://openreview.net/forum?id=M78xLFN7EJ)

---

### Protein Language Model Embeddings Improve Generalization of Implicit Transfer Operators
*Panagiotis Antoniadis, Beatrice Pavesi, Simon Olsson, Ole Winther*

> Molecular dynamics (MD) is a central computational tool in physics, chemistry, and biology, enabling quantitative prediction of experimental observables as expectations over high-dimensional molecular distributions such ...

**Keywords:** GenMD, Implicit Transfer Operators, Molecular Dynamics

[PDF](https://openreview.net/pdf/77557cbd0b518de143e2d0cd734ec478e619eccc.pdf) · [Code](https://github.com/PanosAntoniadis/platito) · [OpenReview](https://openreview.net/forum?id=gRzdGEtn3T)

---

### Proteo-R1: Reasoning Foundation Models for De Novo Protein Design
*Fang Wu, Weihao Xuan, Heli Qi, Hanqun Cao et al.*

> Deep learning in de novo protein design has achieved atomic-level fidelity. However, existing models remain largely non-deliberative: they directly synthesize molecular geometries without explicitly reasoning about which...

**Keywords:** Biology Foundation Models, Drug Discovery, LLM Reasoning

[PDF](https://openreview.net/pdf/9815120833db763480ef223ce93d940379af449d.pdf) · [Code](https://proteor1.github.io) · [OpenReview](https://openreview.net/forum?id=dDowWwInhz)

---

### scChord: A Probabilistic Manifold Rectification Framework for RNA-to-Protein Translation
*Jiawei Zhang, Kangjun Jin, Shuai Xiao, Jiachen Yang*

> Measuring single-cell protein abundance is essential for resolving biological mechanisms and disease progression with high resolution. However, due to the high costs and antibody throughput limitations of current proteom...

**Keywords:** Single-cell Multi-omics; Protein Abundance Prediction; Flow Matching

[PDF](https://openreview.net/pdf/69af658177ba9acd4acfcad5498a556891f8c1ce.pdf) · [Code](https://github.com/Jave-Zhang/scChord) · [OpenReview](https://openreview.net/forum?id=jCKbsTW9m8)

---

### SP-Mind: An Autonomous Reasoning Agent for Spatial Proteomics Analysis
*YuCheng Yuan, Yuanfeng Ji, Zhongxiao Li, Ruijiang Li*

> Spatial proteomics enables single-cell-resolution characterization of protein expression within tissue architecture, playing a critical role in understanding tumor microenvironments and guiding precision medicine. Howeve...

**Keywords:** Agents, Computational Biology, LLMs, Healthcare

[PDF](https://openreview.net/pdf/03fce82630fa742cb8e6864f72ed8c57ef5a35ca.pdf) · [OpenReview](https://openreview.net/forum?id=UJcB3XrffF)

---

### STRIDE: Post-Training LLMs to Reason and Refine Bio-Sequences via Edit Trajectories
*Daiheng Zhang, Shiyang Zhang, Sizhuang He, Yangtian Zhang*

> Discrete biological sequence optimization often requires goal-directed, parser-valid edits to an existing protein or molecule. Diffusion models support iterative refinement but do not   expose a controllable discrete-edi...

**Keywords:** Large Language Models, Post-Training, Biological Sequence Optimization, Protein and Molecule Design

[PDF](https://openreview.net/pdf/801048d8eb380e907f595164e41e8434863dfd68.pdf) · [OpenReview](https://openreview.net/forum?id=g9J8AyE0xy)

---

### SwitchCraft: A Programmatic Framework for Designing State-Switching Proteins
*Bowen Jing, Mihir Bafna, Anisha Parsan, Heyuan Michael Ni*

> Multistate mechanisms underlie many of the complex functions observed in natural proteins. The ability to rationally design multistate proteins would have transformative implications for many areas of biotechnology, yet ...

**Keywords:** protein design, function, multistate, proteins

[PDF](https://openreview.net/pdf/e185b7c17873b7b06ad547d9a09d125e91c1a6e8.pdf) · [Code](https://github.com/bjing2016/switchcraft) · [OpenReview](https://openreview.net/forum?id=YtqaHnqv8c)

---

### TadA-Bench: A Million-Variant Benchmark for Future-Round Discovery Toward Agentic Protein Engineering
*Jin Gao, Juntu Zhao, Zirui Zeng, Jiaqi Shen*

> AI for scientific discovery is entering an agentic era, where protein-engineering systems are expected to prioritize future wet-lab experiments rather than merely fit static measurements. We introduce TadA-Bench, a milli...

**Keywords:** Benchmark, Agentic Discovery, AI for Science, Protein Engineering

[PDF](https://openreview.net/pdf/dcfdb4d8b492f3586be1294bba7739a002d24ebc.pdf) · [Code](https://github.com/shiyegao/TadABench-1M) · [OpenReview](https://openreview.net/forum?id=KMwrxaoAW4)

---

### TerraBind: Fast and Accurate Binding Affinity Prediction through Coarse Structural Representations
*Matteo Rossi, Ryan Pederson, Miles Wang-Henderson, Ben Kaufman et al.*

> We present TerraBind, a foundation model for protein-ligand structure and binding affinity prediction that achieves 26$\times$ faster inference than state-of-the-art methods while improving affinity prediction accuracy b...

**Keywords:** binding affinity prediction, protein-ligand structure prediction, drug discovery, virtual screening

[PDF](https://openreview.net/pdf/33a8cc098f63fecd7890e26864dc2ee3d055973e.pdf) · [OpenReview](https://openreview.net/forum?id=xlevHY3oJO)

---

### Towards A Generative Protein Evolution Machine with DPLM-Evo
*Xinyou Wang, Liang Hong, Jiasheng Ye, Zaixiang Zheng*

> Proteins are shaped by gradual evolution under biophysical and functional constraints. Protein language models learn rich evolutionary constraints from large-scale sequences, and discrete diffusion-based protein language...

**Keywords:** evolutionary discrete diffusion model, protein sequence generation, protein sequence evolutionary modeling

[PDF](https://openreview.net/pdf/1104c1cafb04149eeb539a2384e04be4e8e68acd.pdf) · [OpenReview](https://openreview.net/forum?id=hcFVDmmb0J)

---

## Drug Discovery & Molecular Design

> Small molecule generation, ADMET prediction, molecular docking, and drug-target interaction.

### A Call to Lagrangian Action: Learning Population Mechanics from Temporal Snapshots 🌟 **Spotlight**
*Vincent Guan, Lazar Atanackovic, Kirill Neklyudov*

> The population dynamics of molecules, cells, and organisms are governed by a number of unknown internal and external forces. In the last decade, population dynamics have predominately been modeled with Wasserstein gradie...

**Keywords:** Population dynamics, trajectory inference, single-cell, gradient flows

[PDF](https://openreview.net/pdf/f862d11a2e5c0350797966f10c9ec180adbea432.pdf) · [Code](https://github.com/guanton/WLM) · [OpenReview](https://openreview.net/forum?id=MjPv4kRu3H)

---

### DeCoDe: Decoupling Binding Position and Molecular Conformation in 3D Ligand Diffusion for Structure-Based Drug Design 🌟 **Spotlight**
*Julong Yang, Wen Huang, Junhui Chen, Jian Peng*

> Recent advances in diffusion models show promise for Structure-Based Drug Design (SBDD), which aims to generate 3D ligand molecules that bind tightly to specific protein targets.  This involves jointly optimizing the lig...

**Keywords:** Diffusion Models, Structure-Based Drug Design, Molecule Generation

[PDF](https://openreview.net/pdf/874e1478e3ed547e2d8f392d382d519eb3bf5d2f.pdf) · [OpenReview](https://openreview.net/forum?id=lywUbYpYfG)

---

### Excited Pfaffians: Generalized Neural Wave Functions Across Structure and State 🌟 **Spotlight**
*Nicholas Gao, Till Grutschus, Frank Noe, Stephan Günnemann*

> Neural-network wave functions in Variational Monte Carlo (VMC) have achieved great success in accurately representing both ground and excited states. However, achieving sufficient numerical accuracy in state overlaps req...

**Keywords:** Machine Learning for Science, Computational Physics, Computational Chemistry, Quantum Chemistry

[PDF](https://openreview.net/pdf/c12bca29f6d8b008109d838e433100752c7a3a7a.pdf) · [Code](https://github.com/n-gao/neural-pfaffian) · [OpenReview](https://openreview.net/forum?id=meEsugjXjv)

---

### From Feasible to Practical: Pareto-Optimal Synthesis Planning 🌟 **Spotlight**
*Friedrich Hastedt, Dongda Zhang, Antonio Del rio chanona*

> Current computer-aided synthesis planning (CASP) methods often treat retrosynthesis as solved once a single feasible route is identified, focusing primarily on convergence or shortest-path metrics. This view is misaligne...

**Keywords:** Retrosynthesis planning, Multi-objective optimization, Pareto optimality, A* search

[PDF](https://openreview.net/pdf/df0836570920b3395b2f27cee809f05d3b98c588.pdf) · [OpenReview](https://openreview.net/forum?id=qpPf5mI1qn)

---

### Learning Hamiltonian Flow Maps: Mean Flow Consistency for Large-Timestep Molecular Dynamics 🌟 **Spotlight**
*Winfried Ripken, Michael Plainer, Gregor Lied, Thorben Frank*

> Simulating the long-time evolution of Hamiltonian systems is limited by the small timesteps required for stable numerical integration. To overcome this constraint, we introduce a framework to learn *Hamiltonian Flow Maps...

**Keywords:** Hamiltonian Mechanics, Molecular Dynamics, Integration, Flow Maps

[PDF](https://openreview.net/pdf/8e988cf8eadf0a1a7ecb17d79e8d332df2fe7459.pdf) · [Code](https://ml4molsim.github.io/hamiltonian-flow-maps/) · [OpenReview](https://openreview.net/forum?id=EBSn23DLwB)

---

### $\texttt{FlashSchNet}$: Fast and Accurate Coarse-Grained Neural Network Molecular Dynamics
*Pingzhi Li, Hongxuan Li, Zirui Liu, Xingcheng Lin*

> Graph neural network (GNN) potentials such as SchNet improve the accuracy and transferability of molecular dynamics (MD) simulation by learning many-body interactions, but remain slower than classical force fields due to...

**Keywords:** molecular dynamics simulation; algorithm-system co-design; graph neural network

[PDF](https://openreview.net/pdf/83e9e88ee99ffbf3375b9319c908fe037690d433.pdf) · [Code](https://github.com/unites-lab/flash-molecular-dynamics) · [OpenReview](https://openreview.net/forum?id=bu6M0Bo6PO)

---

### A recipe for scalable attention-based ML potentials: unlocking long-range accuracy with all-to-all node attention
*Eric Qu, Brandon M. Wood, Aditi S. Krishnapriyan, Zachary Ward Ulissi*

> Machine-learning interatomic potentials (MLIPs) have advanced rapidly, with many top models relying on strong physics-based inductive bias. However, as models scale to larger systems like biomolecules and electrolytes, t...

**Keywords:** Machine Learning Interatomic Potential, AI for Science, AI for Chemistry

[PDF](https://openreview.net/pdf/c13ce27b7da4e0be65e55200c362d17399a22f56.pdf) · [Code](https://github.com/facebookresearch/fairchem) · [OpenReview](https://openreview.net/forum?id=oZg9YF9dkz)

---

### APEX: Approximate-but-exhaustive search for ultra-large combinatorial synthesis libraries
*Aryan Pedawi, Jordi Silvestre-Ryan, Bradley Worley, Darren J. Hsu*

> Make-on-demand combinatorial synthesis libraries (CSLs) like Enamine REAL have significantly enabled drug discovery efforts. However, their large size presents a challenge for virtual screening, where the goal is to iden...

**Keywords:** virtual screening, drug discovery, neural information retrieval

[PDF](https://openreview.net/pdf/16a5440d3ac93197529b4642aa4d966d1080048b.pdf) · [Code](https://github.com/NumerionLabs/apex) · [OpenReview](https://openreview.net/forum?id=5lIJrDCQll)

---

### Constrained Flow Optimization via Sequential Fine-Tuning for Molecular Design
*Sven Gutjahr, Riccardo De Santi, Luca Schaufelberger, Kjell Jorner*

> Adapting generative foundation models, in particular diffusion and flow models, to optimize given reward functions (e.g., binding affinity) while satisfying constraints (e.g., molecular synthesizability) is fundamental f...

**Keywords:** flow models, diffusion models, constrained generation, generative optimization

[PDF](https://openreview.net/pdf/53b8d1185e9922e29a234550eb0edde11f3253fc.pdf) · [Code](https://github.com/svenlg/constrained-flow-optimization) · [OpenReview](https://openreview.net/forum?id=KBpIlcUIx1)

---

### Contrastive Geometric Learning Unlocks Unified Structure- and Ligand-Based Drug Design
*Lisa Schneckenreiter, Sohvi Luukkonen, Lukas Friedrich, Daniel Kuhn*

> Structure-based and ligand-based computational drug design have traditionally relied on disjoint data sources and modeling assumptions, limiting their joint use at scale. In this work, we introduce **Con**trastive **G**e...

**Keywords:** contrastive learning, geometric deep learning, protein-ligand interaction, structure-based drug design

[PDF](https://openreview.net/pdf/58c4e97551cda2938c84995f337ce3837bb67ba0.pdf) · [Code](https://github.com/ml-jku/conglude) · [OpenReview](https://openreview.net/forum?id=XJaXdi5R21)

---

### Controllable Molecule Generation via Sparse Representation Editing: An Interpretability-Driven Perspective
*Zhuoran Li, Xu Sun, Chang Wen Chen, Wanyu Lin*

> Controllable molecule generation is crucial for diverse scientific applications, such as drug discovery and materials design. While large language models (LLMs) show great promise, their dense and entangled representatio...

**Keywords:** Controllable Molecule Generation, Interpretability

[PDF](https://openreview.net/pdf/3798c11b52c39d6d37fb1fd73e1fb3461e4cc589.pdf) · [OpenReview](https://openreview.net/forum?id=ryO12fv5bJ)

---

### Coupled Cluster con MoLe: Molecular Orbital Learning for Neural Wavefunctions
*Luca Thiede, Abdulrahman Aldossary, Andreas Burger, Jorge A. Campos-Gonzalez-Angulo et al.*

> Density functional theory (DFT) is the most widely used method for calculating molecular properties; however, its accuracy is often insufficient for quantitative predictions. Coupled cluster (CC) theory is the most succe...

**Keywords:** Coupled Cluster, Molecules, Molecular orbitals, Equivariant neural networks

[PDF](https://openreview.net/pdf/f37428215c781e2ecb7d904b2598275c2014ecd8.pdf) · [OpenReview](https://openreview.net/forum?id=i5QhkUCzJh)

---

### Credible Information Subset Decomposition: An End-to-End Multi-fidelity Learning Model by Modeling Label Information
*Sihan Wang, Wenjie Du, Yang Wang*

> In the AI4Chemistry scenario, utilizing heterogeneous data at different fidelity levels is a common and core issue. High-fidelity data is accurate but scarce, while low-fidelity data is abundant but biased. Traditional m...

**Keywords:** AI4Chemistry, Multi-Fidelity Learning

[PDF](https://openreview.net/pdf/b5de0bb9743c3a653104c40f13f81c0a7a3c0039.pdf) · [Code](https://github.com/SihanWang123/Credible-Infor-subset) · [OpenReview](https://openreview.net/forum?id=puaCoeJXn5)

---

### Deep Scientific Reasoning under Physical Constraints: Structure-Aware Spectrum Prediction
*Yingheng Wang, Tao Yu, Shufeng Kong, Francesco Ricci*

> Structured scientific spectra encode rich physical information while obeying hard constraints, such as conservation laws and characteristic spectral geometry. Accurate prediction of these spectra is central to materials ...

**Keywords:** scientific reasoning, physical constraint, spectrum prediction

[PDF](https://openreview.net/pdf/7076b2983a773f2f41a0f53fda381930d7d2c576.pdf) · [OpenReview](https://openreview.net/forum?id=LTrBRkduRt)

---

### Derivative Informed Learning of Exchange-Correlation Functionals
*Eike Eberhard, Luca Thiede, Abdulrahman Aldossary, Andreas Burger*

> Machine-learned (ML) XC functionals aim to replace human-designed density functional approximations by learning directly from reference data, but they still do not consistently outperform traditional $\mathcal{O}(N^4)$-s...

**Keywords:** DFT, KS-DFT, TD-DFT, AI4Science

[PDF](https://openreview.net/pdf/8997ef6cb4e6cabe0526d0dce359956020ffb6b8.pdf) · [OpenReview](https://openreview.net/forum?id=qijM0kpqPC)

---

### DISSOLVR: An Interpretable and Fast Framework for Aqueous and Organic Solubility Prediction
*Vansh Ramani, Har Ashish Arora, Dhairya Kuchhal, Sayan Ranu*

> High-fidelity solubility prediction is fundamental to pharmaceutical development and environmental partitioning, where accurate modeling must couple molecular structure with thermodynamic behavior across diverse chemical...

**Keywords:** Solubility, Machine Learning

[PDF](https://openreview.net/pdf/1592cea191e6e0d99256141dc34d95e4f125a845.pdf) · [Code](https://github.com/VanshRamani/Dissolvr) · [OpenReview](https://openreview.net/forum?id=TwptiGypFR)

---

### Efficient and Safe Molecular Assembly via Reinforcement Learning and Constraint Solving
*Stefan Pranger, Bernhard Ramsauer, Oliver T. Hofmann, Bettina Könighofer*

> Scanning tunneling microscopy (STM) enables precise manipulation of individual atoms and molecules, offering a pathway to constructing nanoscale assemblies with rich quantum mechanical behavior. Despite its potential, ST...

**Keywords:** Reinforcement Learning, Planning&Scheduling, Molecular Manipulation, Nanostructure Formation

[PDF](https://openreview.net/pdf/91d0ba75cd700d4f7bdb388d496b986cef38b8a8.pdf) · [OpenReview](https://openreview.net/forum?id=XcQ5ud9HdX)

---

### EvoEGF-Mol: Evolving Exponential Geodesic Flow for Structure-based Drug Design
*Yaowei Jin, Junjie Wang, Cheng Cao, Penglei Wang*

> Structure-Based Drug Design (SBDD) aims to discover bioactive ligands. Conventional approaches construct probability paths separately in Euclidean and probabilistic spaces for continuous atomic coordinates and discrete c...

**Keywords:** structure-based drug design, deep generative models, exponential geodesics

[PDF](https://openreview.net/pdf/cb2b91e2d6238f737f72b297d2465973f94867d1.pdf) · [Code](https://github.com/BLEACH366/EvoEGF-Mol) · [OpenReview](https://openreview.net/forum?id=bOlF0eLPXa)

---

### FRIGID: Scaling Diffusion-Based Molecular Generation from Mass Spectra at Training and Inference Time
*Montgomery Bohde, Hongxuan Liu, Mrunali Manjrekar, Magdalena Lederbauer*

> Tandem mass spectrometry is prominent in scientific discovery workflows for identifying unknown small molecules, yet high-throughput structural elucidation remains challenging. While recent autoregressive and graph diffu...

**Keywords:** Mass Spectra, AI4Science, Generative Modeling, Diffusion Language Models

[PDF](https://openreview.net/pdf/7dfb127e7aa2caab6e028150104d066b5dc04851.pdf) · [Code](https://github.com/coleygroup/FRIGID) · [OpenReview](https://openreview.net/forum?id=wTgx7b2D9r)

---

### From Holo Pockets to Electron Density: GPT-style Drug Design with Density
*Jiahao Chen, Letian Gao, Yanhao Zhu, Wenbiao zhou*

> Recent advances in generative modeling have enabled significant progress in structure-based drug design (SBDD). Existing methods typically condition molecule generation on empty binding pockets from holo complexes, overl...

**Keywords:** Electron Density, Holo Complex, Drug Design

[PDF](https://openreview.net/pdf/e9d355f91b1fa3d9bf82e4ff9f73764a6dc254e5.pdf) · [Code](https://github.com/JiahaoChen1/EDMolGPT) · [OpenReview](https://openreview.net/forum?id=oaMuJPfDUS)

---

### From Human Labels to Literature: Semi-Supervised Learning of NMR Chemical Shifts at Scale
*Yongqi Jin, Yecheng Wang, Jun-jie Wang, Rong Zhu*

> Accurate prediction of nuclear magnetic resonance (NMR) chemical shifts is fundamental to spectral analysis and molecular structure elucidation, yet existing machine learning methods rely on limited, labor-intensive atom...

**Keywords:** Computational chemistry, Data-centric machine learning, Semi-supervised learning

[PDF](https://openreview.net/pdf/d4af4ab627df002218886bb68a8509d44503177c.pdf) · [Code](https://github.com/YongqiJin/NMRNetplusplus) · [OpenReview](https://openreview.net/forum?id=TDXx4EKHZ1)

---

### Geometric Embedding Alignment via Curvature Matching in Transfer Learning
*Sung Moon Ko, Jaewan Lee, Sumin Lee, Soorin Yim*

> Geometrical interpretations of deep learning models offer insightful perspectives into their underlying mathematical structures. In this work, we introduce a novel approach that leverages differential geometry, particula...

**Keywords:** Geometrical Deeplearning, Transfer Learning, Molecular Property Prediction

[PDF](https://openreview.net/pdf/0139cd12f4b776a182c847b15d438f5a05e96bc7.pdf) · [OpenReview](https://openreview.net/forum?id=MrFOCA1U5P)

---

### JanusPipe: Efficient Pipeline Parallel Training for Machine Learning Interatomic Potentials
*Hongyu Wang, Weijian Liu, Hongtao Xu, Yan Wang*

> Discovering atom-level phenomena requires molecular dynamics (MD) simulations with ab initio accuracy.  Machine learning interatomic potentials (MLIPs) enable stable, high-accuracy MD simulations, and their models exhibi...

**Keywords:** Pipeline parallelism, Machine learning interatomic potentials (MLIPs), Double-backward training, Distributed training

[PDF](https://openreview.net/pdf/e5832bebcc47a022ca105ff11fa2155526ae7ddd.pdf) · [Code](https://github.com/HPC-AI-Team/JanusMLIP) · [OpenReview](https://openreview.net/forum?id=TxWbgnFYCr)

---

### Large-Scale Molecular Dynamics Simulations: Direct Interatomic Modeling with Dilated Message Passing
*Haokai Hong, Wanyu Lin, KC Tan*

> Large-scale molecular dynamics simulations are essential in understanding chemical and biological processes, necessitating the accurate and efficient modeling of interatomic interactions. Existing learning-based methods ...

**Keywords:** Molecular Dynamics, Graph Neural Network, Machien Learning Force Field

[PDF](https://openreview.net/pdf/3384ba51ae715d7f3d6d94e80211f318b6c63312.pdf) · [Code](https://github.com/WanyuGroup/ICML2026-DKMP) · [OpenReview](https://openreview.net/forum?id=cNplXlpf7r)

---

### LeakGFN: Robust Molecular Generation in Generative Flow Networks via Flow Decomposition
*Hwanhee Kim, Seungyeon Choi, Sanghyun Park*

> Generative Flow Networks (GFlowNets) have emerged as a powerful framework for molecular generation, sampling diverse candidates proportionally to a reward function. However, the vast chemical space necessitates truncatin...

**Keywords:** Generative Flow Networks, Molecular Generation, Drug Discovery

[PDF](https://openreview.net/pdf/d902631f781d4cef4bfdf52781843f8e93d7800f.pdf) · [Code](https://github.com/HwanheeKim813/LeakGFN.git) · [OpenReview](https://openreview.net/forum?id=aS5zkIyzpG)

---

### Learning Compressed Shape-Aware Molecular Representations for Virtual Screening
*Robin Winter, Julian Cremer, Djork-Arné Clevert*

> Virtual screening of billion-scale molecular libraries based on 3D shape similarity remains computationally prohibitive, requiring expensive conformational sampling and alignment, as done by established tools like *ROCS*...

**Keywords:** Contrastive Learning, Representation Learning, Chemistry, Shape

[PDF](https://openreview.net/pdf/d73f7968fdf4280552d4d362061881c3b032a52c.pdf) · [Code](https://github.com/pfizer-opensource/SAND) · [OpenReview](https://openreview.net/forum?id=pB6WAdnRDR)

---

### MAST: Motif-Augmented Diffusion with Search Tree for Spectroscopic Molecular Structure Elucidation
*Chenghao Jia, Mengdi Liu, Hong Chang, Shiguang Shan*

> Elucidating molecular structures from spectra is a foundational problem in chemical and materials characterization, yet remains challenging due to spectral ambiguity and the vast molecular space. Although recent diffusio...

**Keywords:** Spectroscopy, Molecular Structure Elucidation, Diffusion Models

[PDF](https://openreview.net/pdf/b34c222f64f00a0df7ae00a9c88a759fc5d75af4.pdf) · [Code](https://github.com/Jia040223/MAST) · [OpenReview](https://openreview.net/forum?id=IVbMO5hnyv)

---

### Order Matters in Retrosynthesis: Structure-aware Generation via Reaction-Center-Guided Discrete Flow Matching
*Chenguang Wang, Zihan Zhou, LEI BAI, Tianshu Yu*

> Template-free retrosynthesis methods treat the task as black-box sequence generation, limiting learning efficiency, while semi-template approaches rely on rigid reaction libraries that constrain generalization. We addres...

**Keywords:** retrosynthesis, discrete flow matching, generative models

[PDF](https://openreview.net/pdf/5e825a35a51a4d1819bea28ca22b81ed0d5e7e86.pdf) · [OpenReview](https://openreview.net/forum?id=xeH37plPS3)

---

### Physics-Informed Pre-training on Efficient Electron-Density Images for Organic Material Property Prediction
*Zhixiang Cheng, Hongxin Xiang, Mingquan Liu, Tengfei Ma et al.*

> Precise property prediction of organic materials is pivotal for next-generation electronic and energy devices. In density functional theory (DFT), the electron density (ED) serves as the fundamental determinant of materi...

**Keywords:** Electronic Density Image, Physics-Informed Pre-training, Organic Material Property Prediction, Density Functional Theory

[PDF](https://openreview.net/pdf/0d544a89b7cbaf8e3604dde47c169cd1b0d1d88c.pdf) · [OpenReview](https://openreview.net/forum?id=IBDryWLx87)

---

### Reading the Cell, Designing the Cure: Perturbation-Conditioned Molecular Diffusion for Function-Oriented Drug Design
*ZIYU XU, zijian zhang, Liang Wang, Zhiyuan Liu*

> When reliable target structures are unavailable at scale or phenotypes arise from dysregulated pathways, transcriptomic perturbations provide a system-level functional readout for drug action. In this work, we formalize ...

**Keywords:** Transcriptome-Guided Drug Design, Single-Cell Transcriptomics, Molecular Generation, Graph Diffusion Models

[PDF](https://openreview.net/pdf/efd29788b8e64965072f802e394699c7cf247bdd.pdf) · [Code](https://github.com/EdwardCurry/CURE_TBDD) · [OpenReview](https://openreview.net/forum?id=7pinsbGVLt)

---

### ReCoG: Relational and Compact Context Graph Learning for Few-shot Molecular Property Prediction
*Zeyu Wang, Xin Zheng, Yao Lu, Shanqing Yu*

> Few-shot molecular property prediction (FSMPP) is essential in drug discovery and materials design, where high-quality labeled data are often scarce and expensive to obtain. Despite the promising performance of existing ...

**Keywords:** Few-shot learning, Molecular property prediction, Few-shot molecular property prediction

[PDF](https://openreview.net/pdf/82bf1cb428a634777152d945ff8c68372814f74e.pdf) · [Code](https://github.com/Vencent-Won/ReCoG-main) · [OpenReview](https://openreview.net/forum?id=lmhLWnIVOk)

---

### Retro-Expert: Collaborative Reasoning for Interpretable Retrosynthesis
*Xinyi Li, Sai Wang, Yutian Lin, Yu Wu*

> Retrosynthesis prediction aims to infer the reactant molecules based on a given product molecule, which is a fundamental task in chemical synthesis. However, existing methods rely on a static pattern-matching paradigm, w...

**Keywords:** Retrosynthesis, Large Language Models, Reinforcement Learning

[PDF](https://openreview.net/pdf/0e82cb0248d8d78db5f46dd69263ba3158aab912.pdf) · [OpenReview](https://openreview.net/forum?id=CPrSz9pqv7)

---

### RetrOrchestrator: A Multi-Step Retrosynthesis Agent Dynamically Orchestrating Single-Step Transition Models
*Liao Chang, Luotian Yuan, Yiping Ke, Ying Wei*

> Multi-step retrosynthesis planning is a fundamental challenge in organic chemistry, defined by its enormous search space. Existing methods typically formulate it as a Markov Decision Process (MDP) with a fixed choice of ...

**Keywords:** retrosynthesis planning, multistep retrosynthesis, tool-calling agent, tool-integrated reinforcement learning

[PDF](https://openreview.net/pdf/9f59c0c795bd9e6f63f13f81105657ed3f818066.pdf) · [Code](https://github.com/ScottLiao920/verl-retro-agent) · [OpenReview](https://openreview.net/forum?id=p6gN6f8pdy)

---

### Scaling the Prior: Size-Consistent Geometric Diffusion for 3D Molecular Generation
*Wenhan Gao, Jingxiang Qu, Yi Liu*

> Diffusion models typically operate in fixed-dimensional metric spaces, whereas 3D geometric molecular data vary in dimensionality because molecules differ in size (number of atoms). A common adaptation in diffusion model...

**Keywords:** 3D Molecular Generation, Geometric Diffusion

[PDF](https://openreview.net/pdf/0d4628ad0ca287ce1f0c0438590c7164fedb28d4.pdf) · [Code](https://github.com/wenhangao21/ICML26-StP) · [OpenReview](https://openreview.net/forum?id=5aH5eYIAFQ)

---

### Speculative Sampling For Faster Molecular Dynamics
*Arthur Kosmala, Stephan Günnemann, Meng Gao, Brandon M. Wood*

> Molecular dynamics (MD) is a key tool for simulating the dynamical behavior of atomic systems. However, MD is inherently serial, which makes it difficult to increase single-system throughput with concurrent compute. To a...

**Keywords:** molecular dynamics, speculative sampling, speculative decoding, chemistry

[PDF](https://openreview.net/pdf/6f52393261bfe8909f72e654ef6ac184428cbd19.pdf) · [Code](https://github.com/facebookresearch/LSD) · [OpenReview](https://openreview.net/forum?id=I3SK0WFmD0)

---

### Steering Large Language Models through the DMTA Cycle: Structure-Based Drug Design via Knowledge-Driven Bi-Level Thompson Sampling
*Xuanning Hu, Hao Tuo, Jinglong Ji, Anchen Li*

> Structure-based drug design (SBDD) can be effectively realized through an iterative refinement via the Design-Make-Test-Analyze (DMTA) cycle, which is a common workflow used by human experts. However, most conventional d...

**Keywords:** Structure-based Drug Design, Large Language Models, Muti-Armd Bandit, Thompson Sampling

[PDF](https://openreview.net/pdf/ec7e0aa80a15fb5f5578f5dc859777cf5ce461f8.pdf) · [Code](https://github.com/hxnhxn/K-BTS) · [OpenReview](https://openreview.net/forum?id=yqF2ubqiCn)

---

### STFlow: Data-Coupled Flow Matching for Geometric Trajectory Simulation
*Kiet Bennema ten Brinke, Koen Minartz, Vlado Menkovski*

> Simulating trajectories of dynamical systems is a fundamental problem in a wide range of fields such as molecular dynamics, biochemistry, and pedestrian dynamics. Machine learning has become an invaluable tool for scalin...

**Keywords:** Generative modeling, Trajectory simulation, flow matching, n-body dynamics

[PDF](https://openreview.net/pdf/284f024c6ac4c2f9754ea5fbbc7c02f5389c743d.pdf) · [Code](https://github.com/MrKietho/STFlow) · [OpenReview](https://openreview.net/forum?id=Wiwfiew7Y4)

---

### SynLaD: Latent Diffusion for Generating Synthesizable Molecules Conditioned on 3D Pharmacophore Profiles
*Miruna Cretu, John Bradshaw, Patricia Suriana, Saeed Saremi et al.*

> We present SynLaD, a latent diffusion framework for small-molecule generation that unifies ligand-based drug design objectives (what to make) with synthetic accessibility (how to make it). Current models typically optimi...

**Keywords:** generative model, pharmacophores, flow matching, synthesizability

[PDF](https://openreview.net/pdf/bfcadf3aee0acfb402db821f075bd7b41949ee36.pdf) · [OpenReview](https://openreview.net/forum?id=xn9Jxl54r3)

---

### Target-Aware Bandit Allocation for Scalable Surrogate Optimization in Chemical Space
*Mohammad Haddadnia, Yuvan Chali, Abhilash Jayaraj, Constance Kraay*

> Identifying high-utility candidates from massive discrete spaces under expensive evaluations is a recurring challenge across the sciences, with structure-based drug discovery as a prominent example. While surrogate-based...

**Keywords:** Surrogate Optimization, Bandit, Bayesian Optimization, Discrete Space

[PDF](https://openreview.net/pdf/c8eb6a1cb4ffd99e4138e183b63159c836012506.pdf) · [OpenReview](https://openreview.net/forum?id=5WwoJ2W0nL)

---

### Teaching Molecular Dynamics to a Non-Autoregressive Ionic Transport Predictor
*Jiyeon Kim, Byungju Lee, Won-Yong Shin*

> Unlike most static material properties widely studied in the machine learning literature, ionic transport properties are inherently dynamic, making their fast and accurate prediction from static atomic structures challen...

**Keywords:** Molecular dynamics, Material science, Chemistry, Non-autoregressive learning

[PDF](https://openreview.net/pdf/05d0318f2f279d6975c6f3d6e5d84da859bb6b0f.pdf) · [Code](https://github.com/jykim-git/MD) · [OpenReview](https://openreview.net/forum?id=JJ3KlnhGJJ)

---

### Towards Diverse Scientific Hypothesis Search with Large Language Models
*Haorui Wang, Parshin Shojaee, Kazem Meidani, Kunyang Sun et al.*

> Large language models (LLMs) are on the rise for accelerating scientific discovery, most recently in advanced tasks such as generating valid scientific hypotheses. Yet in many discovery settings, the goal is not to ident...

**Keywords:** Large Language Models, Evolutionary Algorithm, AI for Science

[PDF](https://openreview.net/pdf/7a43b19e09080aa6b0ccb241103f4c39570f48ad.pdf) · [OpenReview](https://openreview.net/forum?id=5LwZAeK5PE)

---

### Towards Docking-oriented De Novo Ligand Design via Gradient Inversion
*Zekai Chen, Xunkai Li, Sirui Zhang, Henan Sun et al.*

> De novo ligand design is a fundamental task that seeks to generate protein or molecule candidates that can effectively dock with protein receptors and achieve strong binding affinity entirely from scratch.      It holds ...

**Keywords:** Receptor-Ligand Docking, De Novo Ligand Design, Inversion Framework

[PDF](https://openreview.net/pdf/e17df958a16dc87b34f8f25846c4f86275067d73.pdf) · [OpenReview](https://openreview.net/forum?id=0VEeF91Fm6)

---

### TSMGen: Target-Specific Molecule Generation via Higher-Order Structural Dependencies and Context-Aware Bidirectional Fusion
*Yaoyu Chen, Xiaoli Lin, Ziyi Gong, Jun Pang*

> Efficiently designing high-quality molecules targeting disease-relevant targets is a critical challenge. Most existing methods can capture pairwise amino acid relations, neglecting the higher-order relations among multip...

**Keywords:** Drug Discovery, Hypergraph, Feature Fusion

[PDF](https://openreview.net/pdf/2aa3ac51684ce5c4a1ae0d3bf7160f869bf6eff6.pdf) · [OpenReview](https://openreview.net/forum?id=T5eEBKqIT3)

---

### VecMol: Vector-Field Representations for 3D Molecule Generation
*Yuchen Hua, Xingang Peng, Jianzhu Ma, Muhan Zhang*

> Generative modeling of three-dimensional (3D) molecules is a fundamental yet challenging problem in drug discovery and materials science. Existing approaches typically represent molecules as 3D graphs and co-generate dis...

**Keywords:** Neural fields, 3D molecular generation, Diffusion models, Equivariant neural networks

[PDF](https://openreview.net/pdf/7fcb7531a93fa7c37898c6bae6525b2dadfa066f.pdf) · [Code](https://github. com/MuLabPKU/VecMol) · [OpenReview](https://openreview.net/forum?id=4K87H0eSqu)

---

### When Single Answer Is Not Enough: Rethinking Single-Step Retrosynthesis Benchmarks for LLMs
*Bogdan Zagribelnyy, Ivan Ilin, Maksim Kuznetsov, Nikita Bondarev et al.*

> Recent progress has expanded the use of large language models (LLMs) in drug discovery, including synthesis planning. However, objective evaluation of retrosynthesis performance remains limited. Existing benchmarks and m...

**Keywords:** retrosynthesis, single-step retrosynthesis, LLM benchmark, dataset

[PDF](https://openreview.net/pdf/66040cb2d03f23ec653a9b54ea4166383de2db7a.pdf) · [Code](https://github.com/insilicomedicine/ChemCensor) · [OpenReview](https://openreview.net/forum?id=ABhGgV7pov)

---

## Genomics & Sequence Biology

> DNA/RNA foundation models, variant effect prediction, gene regulation, and genome analysis.

### dnaHNet: A Scalable and Hierarchical Foundation Model for Genomic Sequence Learning 🌟 **Spotlight**
*Arnav Shah, Junzhe Li, Parsa Idehpour, Adibvafa Fallahpour et al.*

> Genomic foundation models have the potential to decode DNA syntax, yet face a fundamental tradeoff. Standard subword tokenizers fragment biologically meaningful motifs such as codons and regulatory elements, while nucleo...

**Keywords:** Genomic foundation models, Scaling laws, Variant effect prediction, Gene Essentiality

[PDF](https://openreview.net/pdf/94fb39f222dfafa3b71b864788363860db6e6733.pdf) · [OpenReview](https://openreview.net/forum?id=6pN2KNCspk)

---

### Training Diffusion Language Models for Black-Box Optimization 🌟 **Spotlight**
*Zipeng Sun, Can Chen, Ye Yuan, Haolun Wu*

> We study offline black-box optimization (BBO), aiming to discover improved designs from an offline dataset of designs and labels, a problem common in robotics, DNA, and materials science with limited labeled samples. Whi...

**Keywords:** Diffusion Large Language Models, Offline Black-Box Optimization

[PDF](https://openreview.net/pdf/48fc901b617722391ad5d7ed6f63d18eac939140.pdf) · [Code](https://github.com/zpointS/DiBO) · [OpenReview](https://openreview.net/forum?id=Z7wI0sor6i)

---

### Adaptive DNA Sequence Modeling via Synergistic Plasticity Units
*Binghao Liu, Wenzheng Zhao, Zhijie Zheng, Fei Gu*

> Effective DNA modeling demands the integration of complex patterns such as local motifs, long-range dependencies, and periodic signals. Yet, architectures like CNNs, Transformers, and SSMs are hindered by static or time-...

**Keywords:** synergistic plasticity unit; DNA sequence modeling; foundation model; biological analysis

[PDF](https://openreview.net/pdf/66afcbc7ba6397e93cd78f63569f8c9dbf23a66a.pdf) · [OpenReview](https://openreview.net/forum?id=coNswqxIlk)

---

### Beyond Independent Genes: Learning Module-Inductive Representations for Single-Cell Gene Perturbation Prediction
*Jiafa Ruan, Ruijie Quan, Xu Liyang, Zongxin Yang*

> Predicting transcriptional responses to genetic perturbations is a central problem in functional genomics.  In practice, perturbation responses are rarely gene-independent but instead manifest as coordinated, program-lev...

**Keywords:** Single Cell ; Gene Perturbation

[PDF](https://openreview.net/pdf/5ddd173df6e8db1c4528d0dfe740ea452ff437d7.pdf) · [Code](https://github.com/ttruan2426-dot/scBIG) · [OpenReview](https://openreview.net/forum?id=onuLk72nRw)

---

### Bimodal masked language modeling for bulk RNA-seq and DNA methylation representation learning
*Maxence Gélard, Hakim Benkirane, Thomas Pierrot, Guillaume Richard*

> Oncologists are increasingly relying on multiple modalities to model the complexity of diseases. Within this landscape, transcriptomic and epigenetic data have proven to be particularly instrumental and play an increasin...

**Keywords:** Multimodal Learning, Representation learning, bulk RNA-seq, DNA methylation

[PDF](https://openreview.net/pdf/e609d923c272148a78208d7f5fbed5cc20f96286.pdf) · [Code](https://github.com/instadeepai/multiomics-open-research) · [OpenReview](https://openreview.net/forum?id=fi4gh4Syka)

---

### BIOARC: Discovering Optimal Neural Architectures for Biological Foundation Models
*Yi Fang, Haoran Xu, Jiaxin Han, Sirui Ding*

> Foundation models have revolutionized AI, yet biological applications often repurpose general architectures without accounting for the intrinsic structural and functional properties of distinct modalities, such as genomi...

**Keywords:** Neural Architecture Search, Foundation Models, DNA, Biology

[PDF](https://openreview.net/pdf/f7eeb8865d37a759db4f50b048f40663f1fc3236.pdf) · [OpenReview](https://openreview.net/forum?id=9yts8LUZiA)

---

### CocoRNA: Collective RNA Design with Cooperative Multi-agent Reinforcement Learning
*Tianmeng Hu, Biao Luo, Ke Li*

> Designing RNA sequences that reliably fold into specific secondary structures is essential for understanding their biological functions but remains a challenging computational problem. We propose CocoRNA, a cooperative m...

**Keywords:** Multi-agent, reinforcement learning, RNA inverse design

[PDF](https://openreview.net/pdf/e2dd5f73eb264ea52b7af811f95035b8cf23e20e.pdf) · [OpenReview](https://openreview.net/forum?id=ES14qDqVB4)

---

### DNACHUNKER: Learnable Tokenization for DNA Language Models
*Taewon Kim, Jihwan Shin, Hyomin Kim, Youngmok Jung*

> DNA language models are increasingly used to represent genomic sequence, yet their effectiveness depends critically on how raw nucleotides are converted into model inputs. Unlike natural language, DNA offers no canonical...

**Keywords:** Genomics, Machine Learning, Deep Learning, DNA Language Modeling

[PDF](https://openreview.net/pdf/994706061f9e25a6edfd657d772da1a1844e8f20.pdf) · [OpenReview](https://openreview.net/forum?id=1DxD3SBid1)

---

### FLAG: Foundation model representation with Latent diffusion Alignment via Graph for spatial gene expression prediction
*Qi Si, Penglei Wang, Yushuai Wu, Yifeng Jiao*

> Predicting spatial gene expression from routine H\&E enables large-scale molecular profiling, yet current models treat this as isolated pointwise tasks, thereby overlooking essential biological structures like gene coord...

**Keywords:** Spatial transcriptomics prediction; Whole-slide histopathology (H&E); Diffusion models; Graph neural networks; Gene Foundation Representation alignment

[PDF](https://openreview.net/pdf/f5a1052a91be4f7d3e1bc8267d8ec32a3a250e26.pdf) · [Code](https://github.com/darkflash03/FLAG) · [OpenReview](https://openreview.net/forum?id=yY7rywRtlI)

---

### Flow-Based Density Ratio Estimation for Intractable Distributions with Applications in Genomics
*Egor Antipov, Alessandro Palma, Lorenzo Consoli, Stephan Günnemann*

> Estimating density ratios between pairs of intractable data distributions is a core problem in probabilistic modeling, enabling principled comparisons of sample likelihoods under different data-generating processes acros...

**Keywords:** Density ratio estimation, flow matching, conditional distributions, single-cell analysis

[PDF](https://openreview.net/pdf/001707bbd8d37d3829e2d90520e0edc8edf48836.pdf) · [Code](https://github.com/theislab/scRatio) · [OpenReview](https://openreview.net/forum?id=5zbPdMNcl9)

---

### GenCircuit-RL: Reinforcement Learning from Hierarchical Verification for Genetic Circuit Design
*Noah Flynn*

> Designing genetic circuits, which are biological systems capable of programmed behaviors within living cells, remains a laborious, expert-driven process despite decades of progress in synthetic biology. We introduce GenC...

**Keywords:** Reinforcement Learning, Genetic Circuit Design, Code Generation, Synthetic Biology

[PDF](https://openreview.net/pdf/8d765207264ec4da61a5e7b51d3087e112200da9.pdf) · [OpenReview](https://openreview.net/forum?id=mvhRVG89Nn)

---

### GENEB: Why Genomic Models Are Hard to Compare
*Daria Ledneva, Mikhail Nuridinov, Denis Kuznetsov*

> Progress in genomic foundation models is difficult to assess due to fragmented benchmarks, incompatible evaluation protocols, and task-specific reporting. As a result, claims of superiority or generality across models ar...

**Keywords:** Genomic model evaluation, Benchmark inconsistency, Representation learning, Model generality

[PDF](https://openreview.net/pdf/2086b598f3df26b5cf83eb41a70f4c69015500f8.pdf) · [Code](https://github.com/deeppavlov/GENEB) · [OpenReview](https://openreview.net/forum?id=uZerXmyozE)

---

### HEXST: Hexagonal Shifted-Window Transformer for Spatial Transcriptomics Gene Expression Prediction
*Keunho Byeon, Jin Tae Kwak*

> Spatial transcriptomics offers spatially resolved gene expression profiling within tissue sections, but its cost and limited throughput hinder large-scale deployment. To extend this capability to routine practice, recent...

**Keywords:** Spatial Transcriptomics, Gene Expression Prediction, Histopathology Image Analysis, Geometry-aware Attention

[PDF](https://openreview.net/pdf/5dc4d1857773943bf6cb973d4bb34bcd42a1821c.pdf) · [Code](https://github.com/QuIIL/HEXST) · [OpenReview](https://openreview.net/forum?id=UwPbsFk2Dh)

---

### High-Dimensional Sensitivity Analysis for Genomic Studies: An Adversarial Framework for Learning Worst-Case Latent Confounders
*Yifan Lin, Kevin Z. Lin*

> High-dimensional genomics studies are frequently confounded by unmeasured biological processes that obscure disease-specific signals. While existing workflows can estimate these latent confounders, they fail to quantify ...

**Keywords:** Sensitivity analysis, Unmeasured Confounders, Generative Adversarial Networks, Latent Variable Modeling

[PDF](https://openreview.net/pdf/27ecbb392aaa5bf1c94844d2c0a255cee2173085.pdf) · [Code](https://github.com/yifanlinz/AD_sensitivity_ICML) · [OpenReview](https://openreview.net/forum?id=Pt4aUwYJCu)

---

### HiST: A Hierarchical Sparse Transformer for Cross-Modal Spatial Transcriptomics Modeling
*Weiyi Wu, Xinwen Xu, Xingjian Diao, Siting Li*

> Spatial transcriptomics (ST) links gene expression with tissue morphology but remains expensive and low-throughput, motivating surrogates that infer expression from routine histology. Whole-slide H&E-to-ST inference pair...

**Keywords:** Spatial Transcriptomics, Spatial Omics, Multi-modal learning

[PDF](https://openreview.net/pdf/3b2f22609e0f2ab870ed9d71584462f8c54d2ea4.pdf) · [OpenReview](https://openreview.net/forum?id=ptbzlHzmEv)

---

### InfoGlobe: Local-and-Global Information-Preserving Statistical Manifold Learning for Single-Cell Transcriptomics
*Cheng Wang, Jinpu Cai, Chongxiao Mao, Yuxuan Wang et al.*

> Geometry-preserving dimension reduction is critical for single-cell transcriptomics, where low-dimensional distances should reflect biological divergence between cell types along the transcriptomic manifold. Due to inade...

**Keywords:** scRNA-seq, Fisher-Rao, information geometry, representation learning

[PDF](https://openreview.net/pdf/7fdb21586b88f400c4f7782f430d06acf8b23261.pdf) · [Code](https://github.com/gift-novellab/InfoGlobe) · [OpenReview](https://openreview.net/forum?id=LMrsqvShfy)

---

### Interpretable Neural ODEs for Gene Regulatory Network Discovery under Perturbations
*Zaikang Lin, Sei Chang, Aaron Zweig, Minseo Kang*

> Modern high-throughput biological datasets containing thousands of perturbations enable large-scale discovery of causal graphs that represent regulatory interactions between genes. Differentiable causal graphical models ...

**Keywords:** gene regulatory network, dynamical systems, single-cell RNA-sequencing, Neural ODE

[PDF](https://openreview.net/pdf/c038481e54edbdea3e4964c473be5297d5afb56d.pdf) · [Code](https://github.com/daklab/PerturbODE) · [OpenReview](https://openreview.net/forum?id=nG9bsQq2N6)

---

### Interpreting Genomic Language Models using Sparse Autoencoders
*Akira A Nair, Jaehyun Joo, Jonghyun Lee, Lina Takemaru et al.*

> Genomic language models (gLMs) achieve strong performance across genomic prediction tasks, but their internal biological representations remain poorly understood. Sparse autoencoders (SAEs) have emerged as an interpretab...

**Keywords:** Genomic Language Models, Evo2, Interpretability, Genomics

[PDF](https://openreview.net/pdf/8164085b8e72e6ba9f2ef1d61a50078df3218ca1.pdf) · [Code](https://github.com/akira-nair/glm-sae-interpretability) · [OpenReview](https://openreview.net/forum?id=boBP35BB2U)

---

### LDARNet: DNA Adaptive Representation Network with Learnable Tokenization for Genomic Modeling
*Daria Ledneva, Denis Kuznetsov*

> Genomic foundation models increasingly adopt large language model architectures, yet almost universally rely on fixed tokenization schemes such as $k$-mers, BPE, or single nucleotides, which impose arbitrary sequence bou...

**Keywords:** Genomic sequence modeling, Learnable tokenization, Hierarchical representations, Masked language modeling

[PDF](https://openreview.net/pdf/845dec8e6408151bd9236d0eec872620dd27ef86.pdf) · [Code](https://github.com/darlednik/ICML-LDARNet) · [OpenReview](https://openreview.net/forum?id=v4hQnJn6aN)

---

### Learning Adaptive Perturbation-Conditioned Contexts for Robust Transcriptional Response Prediction
*Yinhua Piao, Hyomin Kim, Seonghwan Kim, Yunhak Oh et al.*

> Predicting high-dimensional transcriptional responses to genetic perturbations is challenging because signals are sparse and experimental noise is severe. Existing methods often suffer from mean collapse, achieving high ...

**Keywords:** Genetic Perturbation Prediction, Biological Mechanistic Interpretability, Adaptive Learning

[PDF](https://openreview.net/pdf/becaf1b2205773e8bf2494a1cd75952f53d83eb6.pdf) · [Code](https://github.com/qkrdmsghk/AdaPert) · [OpenReview](https://openreview.net/forum?id=aJVkQAd7tv)

---

### Learning Adaptive Topology with FiLM-Guided Distillation for Tertiary Structure-Based RNA Design
*Zixun Zhang, Yuncheng Jiang, Yuzhe Zhou, Jiayou Zheng*

> Tertiary structure-based RNA design aims to generate RNA sequences that can fold into desired 3D structures, but remains a challenging problem due to the scarcity of annotated data, structural noise, and the intrinsic co...

**Keywords:** Adaptive Topology Learning, FiLM-Guided Distillation, tertiary structure-based RNA design

[PDF](https://openreview.net/pdf/f65b9b0117d304d9ebc085833b07788e6e4de73b.pdf) · [OpenReview](https://openreview.net/forum?id=68GUslfGLY)

---

### MoLF: Mixture-of-Latent-Flow for Pan-Cancer Spatial Gene Expression Prediction from Histology
*Susu Hu, Stefanie Speidel*

> Inferring spatial transcriptomics (ST) from histology enables scalable histogenomic profiling, yet current methods are largely restricted to single-tissue models. This fragmentation fails to leverage biological principle...

**Keywords:** Spatial transcriptomics, generative modelling, flow matching, histopathology

[PDF](https://openreview.net/pdf/b32ff4edadd3fd921f2890cf1c725acd27272ea2.pdf) · [Code](https://github.com/susuhu/MoLF) · [OpenReview](https://openreview.net/forum?id=SNRYGh6n69)

---

### Predicting evolutionary rate as a pretraining task improves genome language model representations
*Micaela Elisa Consens, Kevin K Yang, James Brian Hall, Ashley Mae Conard*

> Genome language models (gLM) have the potential to further understanding of regulatory genomics without requiring labeled data. Most gLMs are pretrained using sequence reconstruction tasks inspired by natural language pr...

**Keywords:** Genome Language Models, Genomics, Self-Supervised Learning, Evolutionary Biology

[PDF](https://openreview.net/pdf/54bb29afb064fd5c675a523ba273ca51222ee08d.pdf) · [Code](https://github.com/microsoft/gamba) · [OpenReview](https://openreview.net/forum?id=FOIP4Blm4F)

---

### Rethinking Genomic Modeling Through Optical Character Recognition
*Hongxin Xiang, Pengsen Ma, Yunkang Cao, Di Yu*

> Recent genomic foundation models largely adopt large language model architectures that treat DNA as a one-dimensional token sequence. However, exhaustive sequential reading is structurally misaligned with sparse and disc...

**Keywords:** DNA representation learning, long-context modeling, DNA vision-language foundation models, DNA document understanding

[PDF](https://openreview.net/pdf/d019da08c49877dac33dff0410b6eea4440bcc80.pdf) · [Code](https://github.com/HongxinXiang/OpticalDNA) · [OpenReview](https://openreview.net/forum?id=nggzekChuU)

---

### RiboSphere: Learning Unified and Efficient Representations of RNA Structures
*Zhou Zhang, Hanqun Cao, Cheng Tan, Fang Wu*

> Accurate RNA structure modeling remains difficult because RNA backbones are highly flexible, non-canonical interactions are prevalent, and experimentally determined 3D structures are comparatively scarce. We introduce Ri...

**Keywords:** RNA Structure Representation, RNA Design, RNA-ligand Binding, RNA Inverse Folding

[PDF](https://openreview.net/pdf/35d715f9046643667cd35ec0a55b3af895c024c4.pdf) · [OpenReview](https://openreview.net/forum?id=BaHOWWzl5B)

---

### RNA-FM: Flow-Matching Generative Model for Genome-wide RNA-Seq Prediction
*Yaxuan Song, Jianan Fan, Tianyi Wang, Qiuyue Hu*

> Histopathology whole-slide images (WSIs) are routinely acquired in clinical practice and contain rich tissue morphology but lack direct molecular architecture and functional programs defining pathological states, whereas...

**Keywords:** Genome-wide Bulk RNA-seq Prediction, Flow-Matching Generative Model, Whole-slide Image

[PDF](https://openreview.net/pdf/b9050fc03b1184497996ed41c97899de71c1b238.pdf) · [Code](https://github.com/YXSong000/RNA-FM) · [OpenReview](https://openreview.net/forum?id=v5dquZIEUt)

---

### Scalable Single-Cell Gene Expression Generation with Latent Diffusion Models
*Giovanni Palla, Sudarshan Babu, Payam Dibaeinia, James D Pearce*

> Computational modeling of single-cell gene expression is crucial for understanding cellular processes, but generating realistic expression profiles remains a major challenge. This difficulty arises from the count nature ...

**Keywords:** latent diffusion models, transformers, tokenized latent space, scRNA-seq

[PDF](https://openreview.net/pdf/86ba29aafb9ac3b6caa7ae8a802438307e12d2ee.pdf) · [Code](https://github.com/czi-ai/scldm) · [OpenReview](https://openreview.net/forum?id=IRwg87oeJo)

---

### SpaEF: Spatially Resolved Transcriptomics Data Element-Wise Denoising Framework Powered by Large Models
*Zekuan Shang, Xiaosong Han, Liupu Wang, Wei Du et al.*

> For denoising Spatially Resolved Transcriptomics (SRT)  data, existing methods often construct spot and gene graphs to model inter-spot and inter-gene relationships, respectively. However, these methods often introduce s...

**Keywords:** Spatially Resolved Transcriptomics Data Denoising, Graph Autoencoder, Large Model

[PDF](https://openreview.net/pdf/2da8bdeff9438991ce3286bc2718138b3aec77d9.pdf) · [Code](https://github.com/Zekuan-Shang/SpaEF) · [OpenReview](https://openreview.net/forum?id=QO1uZg4fj4)

---

### Towards Universal Gene Regulatory Network Inference: Unlocking Generalizable Regulatory Knowledge in Single-cell Foundation Models
*Jiaxin Qi, Hang Li, Yan Cui, Yuhua Zheng*

> Gene Regulatory Network (GRN) inference is essential for understanding complex cellular mechanisms, rendered tractable through single-cell transcriptomic data. With the emergence of single-cell Foundation Models (scFMs),...

**Keywords:** Gene Regulatory Network, AI for Science, Single-Cell Foundation Models, Single-Cell Transcriptomics

[PDF](https://openreview.net/pdf/d8664abb1090b7667398230211434c8df08b94dc.pdf) · [Code](https://github.com/simpleshinobu/UGRN) · [OpenReview](https://openreview.net/forum?id=dilKIGbrZu)

---

### WFR-MFM: One-Step Inference for Dynamic Unbalanced Optimal Transport
*Xinyu Wang, Ruoyu Wang, Qiangwei Peng, Peijie Zhou*

> Reconstructing dynamical evolution from limited observations is a fundamental challenge in single-cell biology, where dynamic unbalanced optimal transport (OT) provides a principled framework for modeling coupled transpo...

**Keywords:** flow matching, one-step inference, unbalanced optimal transport, Wasserstein–Fisher–Rao

[PDF](https://openreview.net/pdf/30a1528413fb3975b0f6d9d10c7a6d318283ec4f.pdf) · [OpenReview](https://openreview.net/forum?id=yVGbbB3ERW)

---

## Single-Cell & Spatial Omics

> scRNA-seq analysis, cell type annotation, spatial transcriptomics, and multi-omics integration.

### AutoMat: Physics-Guided Agentic Reasoning for Solving Ill-Posed Inverse Microscopy Problems
*Yaotian Yang, Yiwen Tang, Yizhe Chen, Xiao Chen et al.*

> Reconstructing atomistic crystal structures from a single noisy STEM projection is an ill-posed inverse problem: multiple lattices can explain similar contrast, and purely feed-forward models cannot verify physical valid...

**Keywords:** AI for Science, Electron Microscopy, Crystal Structure Reconstruction, Inverse Problems

[PDF](https://openreview.net/pdf/9e60968218f4c885b14223424c4ec05aec6a4e96.pdf) · [Code](https://github.com/yyt-2378/AutoMat) · [OpenReview](https://openreview.net/forum?id=TLroFiKilA)

---

### Beyond Accuracy: Latent Perturbations for Cognitive-Aware Diagnosis
*Yuting Yan, Yinghao Fu, Wendi Ren, Haozhou Gao*

> Diagnosing rare diseases remains a persistent challenge, often hindered by cognitive anchoring: once clinicians settle on a common diagnosis, they often discount alternative explanations, including rare conditions. To ad...

**Keywords:** Counterfactual Reasoning, Rare Disease Diagnosis, Autoencoder

[PDF](https://openreview.net/pdf/af2563cc2336dbafbf91b6ea683e0e6f6eb2fb68.pdf) · [OpenReview](https://openreview.net/forum?id=rEzGzILnVC)

---

### Beyond Continuity: Simulation-free Reconstruction of Discrete Branching Dynamics from Single-cell Snapshots
*Junda Ying, Yuxuan Wang, Bowen Yang, Peijie Zhou*

> Inferring cellular trajectories from destructive snapshots is complicated by the challenges of stochasticity and non-conservative mass dynamics such as cell proliferation and apoptosis. Existing unbalanced Optimal Transp...

**Keywords:** single-cell dynamics, trajectory inference, unbalanced Schrödinger bridge

[PDF](https://openreview.net/pdf/08547660f43ba7c30c8f9e80b3b51f73caa9a2e9.pdf) · [Code](https://github.com/Sirin6/USB) · [OpenReview](https://openreview.net/forum?id=IABjbJlinz)

---

### Bipartite Graph Attention-based Clustering for Large-scale scRNA-seq Data
*Zhuomin Liang, Liang Bai, Xian Yang*

> scRNA-seq clustering is a critical task for analyzing single-cell RNA sequencing (scRNA-seq) data, as it groups cells with similar gene expression profiles. Transformers, as powerful foundational models, have been applie...

**Keywords:** Clustering, graph learning, graph transformer, scRNA-seq data clustering

[PDF](https://openreview.net/pdf/484937fe30899da9221ef72d3753aba0613377bc.pdf) · [OpenReview](https://openreview.net/forum?id=EVnMERXEvC)

---

### Leveraging Lineage Barcodes as Natural Augmentations for Contrastive Learning of Cell Fate in scRNA-seq Data
*Shizhao Joshua Yang, Yixin Wang, Kevin Z. Lin*

> Deciphering how cells commit to future fates is essential for developing precision therapeutics that can reprogram stem cells or modulate immune functions. However, isolating these fate-determining signals in single-cell...

**Keywords:** Single-cell RNA-sequencing data, Contrastive Learning, Lineage Barcoded Single-cell data, Semi-supervised learning

[PDF](https://openreview.net/pdf/9ac53adbde3fe75a73dce9529f48bb9031dfe2c9.pdf) · [Code](https://github.com/SZ-yang/Lineage_aware_ContraLearn) · [OpenReview](https://openreview.net/forum?id=wqS6MURCFQ)

---

### Mitigating Gradient Pathology in PINNs through Aligned Constraint
*Yichen Luo, Peiyu Zhu, Dongxiao Hu, Jia Wang*

> While Physics-Informed Neural Networks (PINNs) are powerful for solving Partial Differential Equations (PDEs), their training is often paralyzed by gradient pathology. The gradients from the PDE residuals and boundary co...

**Keywords:** PINNs, AI4PDE, Gradient Pathology, Loss Landscape

[PDF](https://openreview.net/pdf/458b9ecdad23e41513a6f2894a380b53a754d27b.pdf) · [Code](https://github.com/YichenLuo-0/CAML) · [OpenReview](https://openreview.net/forum?id=Fisw2kc7EY)

---

### Modeling Temporal scRNA-seq Data with Latent Gaussian Process and Optimal Transport
*Mehmet Yigit Balik, Harri Lähdesmäki*

> Single-cell RNA sequencing provides insights into gene expression at single-cell resolution, yet inferring temporal processes from these static snapshot measurements remains a fundamental challenge. Current approaches ut...

**Keywords:** Latent heteroscedastic gaussian processes, Generative modeling, Single-cell rna sequencing, Optimal transport

[PDF](https://openreview.net/pdf/16b122ce302da69bb6c9849402ee4740c51ad2be.pdf) · [Code](https://github.com/YigitBalik/LGP-OT) · [OpenReview](https://openreview.net/forum?id=8RE5i7g4uB)

---

### Needles in the Haystack: Addressing Signal Dilution Improves scRNA-seq Perturbation Response Modeling and Evaluation
*Gabriel Mateo Mejia, Henry E Miller, Francis J.A. Leblanc, BO WANG*

> Recent benchmarks reveal that single-cell perturbation response models are often outperformed by simply predicting the dataset mean. Through large-scale *in silico* simulations, together with analyses of two real-world p...

**Keywords:** Virtual Cell, Foundation Model, Genetic Perturbation

[PDF](https://openreview.net/pdf/0e4005f03edf9ce55b7be957f083dbcf1e19888e.pdf) · [Code](https://github.com/shiftbioscience/Needles-In-The-Haystack) · [OpenReview](https://openreview.net/forum?id=XsrXLPxBJw)

---

### PerturbDiff: Functional Diffusion for Single-Cell Perturbation Modeling
*Xinyu Yuan, Xixian Liu, Ya Shi Zhang, Zuobai Zhang*

> Building _Virtual Cells_ that can accurately simulate cellular responses to perturbations is a long-standing goal in systems biology. A fundamental challenge is that high-throughput  single-cell sequencing is destructive...

**Keywords:** Single-Cell Perturbation Prediction; Functional Diffusion over Cell Distributions

[PDF](https://openreview.net/pdf/0ee67fb55320a5b0151aeb80a7565a846486226e.pdf) · [Code](https://github.com/DeepGraphLearning/PerturbDiff) · [OpenReview](https://openreview.net/forum?id=yBAqonxCdp)

---

### scCBGM: Single-Cell Editing via Concept Bottlenecks
*Alma Andersson, Aya Abdelsalam Ismail, Edward De Brouwer, Doron Haviv et al.*

> Understanding cellular phenotypes and how they respond to perturbations is critical for disease biology and therapeutic design. Single-cell RNA sequencing enables characterization at cellular resolution, yet the combinat...

**Keywords:** single-cell RNA-seq, counterfactual generation, editing, concept bottleneck models

[PDF](https://openreview.net/pdf/f9bbe8d507a99f605b5e6830d730e0c86d2540d1.pdf) · [Code](https://github.com/almaan/scCBGM) · [OpenReview](https://openreview.net/forum?id=cVDeFGyb5z)

---

### scDataset: Scalable Data Loading for Deep Learning on Large-Scale Single-Cell Omics
*Davide D'Ascenzo, Sebastiano Cultrera di Montesano*

> Training deep learning models on single-cell datasets with hundreds of millions of cells requires loading data from disk, as these datasets exceed available memory. While random sampling provides the data diversity neede...

**Keywords:** bioinformatics, single-cell omics, deep learning, large scale learning and big data

[PDF](https://openreview.net/pdf/cd012bee72707413915d4b62953452731128a115.pdf) · [Code](https://github.com/scDataset/scDataset) · [OpenReview](https://openreview.net/forum?id=NiqWdmrxwn)

---

### scDEBART: Predicting in silico Single-Cell Perturbation Responses via Large-Scale Differential Expression Learning
*Jieun Sung, Wankyu Kim*

> Single-cell foundation models trained on millions of cells can learn gene expression patterns across diverse contexts. However, for predicting genetic perturbation effects they often underperform simple regression models...

**Keywords:** single-cell RNA-seq, perturbation prediction, Perturb-seq, foundation model

[PDF](https://openreview.net/pdf/1361dc3f2b1c26ec2f689868b7efde2cb28688dc.pdf) · [Code](https://github.com/Jieun-Sung/scDEBART) · [OpenReview](https://openreview.net/forum?id=pJyidZg93y)

---

### ScDiVa: Masked Discrete Diffusion for Joint Modeling of Single-Cell Identity and Expression
*Mingxuan Wang, Gaoyang Jiang, ZiJia Ren, Cheng Chen*

> Single-cell RNA-seq profiles are high-dimensional, sparse, and unordered, causing autoregressive generation to impose an artificial ordering bias and suffer from error accumulation. To address this, we propose scDiVa, a ...

**Keywords:** discrete diffusion models, masked generative modeling, non-autoregressive sequence modeling, ordering-bias-aware representation learning

[PDF](https://openreview.net/pdf/07c160942f2ef1857e580dc24f89f5413e0ae4a7.pdf) · [Code](https: //github.com/wangmingxuan666/ScDiVa) · [OpenReview](https://openreview.net/forum?id=Sm7NhztxlA)

---

### What Makes a Representation Good for Single-Cell Perturbation Prediction?
*Wenkang Jiang, Yuhang Liu, Yichao Cai, Erdun Gao*

> Single-cell perturbation modeling is fundamental for understanding and predicting cellular responses to genetic perturbations. However, existing approaches, from causal representation learning to foundation models, often...

**Keywords:** Causal representation learning, single cell perturbation

[PDF](https://openreview.net/pdf/87c4564ac98f6dc7a0f98c0582d84b95a17b175e.pdf) · [OpenReview](https://openreview.net/forum?id=5cLRC1hrTP)

---

## Clinical AI & Healthcare

> Clinical decision support, EHR analysis, medical NLP, and AI-assisted diagnostics.

### ClinTutor-R1: Advancing Scalable and Robust One-to-Many Alignment in Clinical Socratic Education 🌟 **Spotlight**
*Zhitao He, Haolin Yang, Zeyu Qin, Yi R. Fung*

> While Large Language Models (LLMs) have achieved remarkable success in dyadic (one-on-one) instruction, they face significant challenges in One-to-Many alignment, such as clinical ward rounds, where an instructor must si...

**Keywords:** Alignment, fairness, safety, privacy

[PDF](https://openreview.net/pdf/1fd9a40f76b5b6ad7a4bb9313b437256e98e7f91.pdf) · [OpenReview](https://openreview.net/forum?id=15Gs65kvHS)

---

### HypoSpace: A Diagnostic Benchmark for Set-Valued Hypothesis Generation under Underdetermination and Sublinear Coverage Bounds 🌟 **Spotlight**
*Tingting Chen, Beibei Lin, Zifeng Yuan, Qiran Zou*

> Many scientific problems are underdetermined: multiple distinct hypotheses are equally consistent with the same observations. In such settings, effective inference requires not only producing valid explanations, but also...

**Keywords:** Underdetermination, Set-Value Generation, Hypothesis, Diagnosis for creativity; Scientific discovery

[PDF](https://openreview.net/pdf/8c90d225c0f557bfdfdc09f7c267b63a63f63208.pdf) · [Code](https://github.com/CTT-Pavilion/_HypoSpace) · [OpenReview](https://openreview.net/forum?id=QpjtK65JHO)

---

### Listening Through the Noise: Cauchy-Driven Diffusion Bridges for Robust Gastrointestinal Auscultation and Clinical Benchmarking 🌟 **Spotlight**
*Dian Ding, Liren Dong, Yu Lu, Juntao Zhou*

> Gastrointestinal (GI) motility assessment via bowel sounds (BS) offers a non-invasive alternative to resource-intensive clinical standards. However, the diagnostic utility of BS is often compromised by its spectral overl...

**Keywords:** Bowel Sound Analysis, Biomedical Signal Processing

[PDF](https://openreview.net/pdf/46de54ec91f982dbfb85eb8a537f070601e61945.pdf) · [OpenReview](https://openreview.net/forum?id=EYAfw6czcC)

---

### Seizure-Semiology-Suite($S^3$): A Clinically Multimodal Dataset, Benchmark, and Models for Seizure Semiology Understanding 🌟 **Spotlight**
*Lina Zhang, Tonmoy Monsoor, Peizheng Li, Jiarui Cui et al.*

> While Multimodal Large Language Models (MLLMs) have demonstrated remarkable proficiency in general video understanding, their capacity to interpret involuntary, and spatio-temporally evolving pathologic motor behaviors s...

**Keywords:** MLLMs, Seizure Semiology, Benchmark, Medical AI

[PDF](https://openreview.net/pdf/fc4bf14e856bfe908f29c245a23251c19f6a0b32.pdf) · [Code](https://github.com/LinaZhangUCLA/SeizureSemiologySuite) · [OpenReview](https://openreview.net/forum?id=MyorUlHKVc)

---

### SleepLM: Natural-Language Intelligence for Human Sleep 🌟 **Spotlight**
*Zongzhe Xu, Zitao Shuai, Eideen Mozaffari, Ravi Shankar Aysola*

> We present SleepLM, a family of sleep-language foundation models that enable human sleep alignment, interpretation, and interaction with natural language. Despite the critical role of sleep, learning-based sleep analysis...

**Keywords:** sleep physiology; foundation model; language model; large language model; multimodal language model; AI for healthcare

[PDF](https://openreview.net/pdf/90c64569af71d54fb00ab4ce0c9a885ef93ff660.pdf) · [Code](https://github.com/yang-ai-lab/SleepLM) · [OpenReview](https://openreview.net/forum?id=9wpwfSJCp9)

---

### SurvDiff: A Diffusion Model for Generating Synthetic Data in Survival Analysis 🌟 **Spotlight**
*Marie Brockschmidt, Maresa Schröder, Stefan Feuerriegel*

> Survival analysis is a cornerstone of clinical research by modeling time-to-event outcomes such as metastasis, disease relapse, or patient death. Unlike standard tabular data, survival data often come with incomplete eve...

**Keywords:** Survival Analysis, Diffusion Models

[PDF](https://openreview.net/pdf/944a1b5bbb02346a61f1a9381d5896e63f58fadf.pdf) · [OpenReview](https://openreview.net/forum?id=boeY2syj2r)

---

### A Geometric Lens on Physics-Aligned Data Compression
*Aleix Segui Ugalde, Wesley Armour*

> In AI for Science, physics-informed losses are increasingly used to train learned compressors for scientific data, but their rate--distortion implications remain poorly understood. At fixed bitrate, these objectives ofte...

**Keywords:** AI for Science, Neural Compression, Physics-Informed Machine Learning, Rate-Distortion Theory

[PDF](https://openreview.net/pdf/affefb771dd0b582642010be6c89df8d24fb173c.pdf) · [OpenReview](https://openreview.net/forum?id=QEEwlgt8PI)

---

### A Regime-Aware Trajectory Prediction Framework for 1000+ Systems Biology Models
*Heng Rao, Jason Zipeng Zhang, Yu Gu, Zhenghao Liu et al.*

> Predicting long-horizon trajectories of biological dynamical systems remains challenging due to substantial system heterogeneity.  Most existing machine learning approaches are system-specific, requiring retraining for e...

**Keywords:** Biological Dynamics, Regime-Aware, Flow Matching

[PDF](https://openreview.net/pdf/fa4d05867326f6a01641b726bb8f4b53e67b87cb.pdf) · [Code](https://github.com/hengrao02/RegimeFlow) · [OpenReview](https://openreview.net/forum?id=sI3UUkXJxs)

---

### Agentic Framework for Epidemiological Modeling
*Rituparna Datta, Zihan Guan, Baltazar Espinoza, Yiqi Su*

> Epidemic modeling is essential for public health planning, yet traditional approaches rely on fixed model classes that require manual redesign as pathogens, policies, and scenario assumptions evolve. We introduce EpiAgen...

**Keywords:** agentic systems, epidemiological modeling, mechanistic-ML models, public health

[PDF](https://openreview.net/pdf/9287291d4f9e4f71f25f609eee7107641e3bd50f.pdf) · [OpenReview](https://openreview.net/forum?id=ujYdUdqWpm)

---

### Asymmetric Contrastive Objectives for Efficient Phenotypic Screening
*Luke Nightingale, Joseph Tuersley, Scott Warchal, Andrea Cairoli et al.*

> Phenotypic screening experiments produce many microscope images of cells under diverse perturbations, with biologically significant responses often subtle or difficult to identify visually. A central challenge is to extr...

**Keywords:** high content screening, image clustering, cell microscopy, drug discovery

[PDF](https://openreview.net/pdf/be61adbb2d24b4db0fee51e6eb72a69d0b1512a7.pdf) · [OpenReview](https://openreview.net/forum?id=oQSqJfJUvJ)

---

### Automatic Construction of Clinical Scoring Systems with LLM Agents
*Silas Ruhrberg Estévez, Christopher Chiu, Mihaela van der Schaar*

> Modern clinical practice relies on evidence-based guidelines implemented as compact scoring systems composed of a small number of interpretable decision rules. While machine-learning models achieve strong performance, ma...

**Keywords:** LLM agents, Large language models (LLMs), Clinical Guidelines, Clinical decision support

[PDF](https://openreview.net/pdf/a90b1ad86513794dfd331d11509075dc3d881f16.pdf) · [Code](https://github.com/Sr933/agentscore-official) · [OpenReview](https://openreview.net/forum?id=fFUI2PGaNG)

---

### Benchmarking the Scientific Mind: A Pathology-Derived Biomedical VQA Benchmark for Complex Scientific Reasoning
*Ziyu Zhao, Yiyang Liu, Yajiao Wang, Xiaotao Wang et al.*

> Despite progress of Multimodal Large Language Models (MLLMs) in biomedical visual question answering (VQA), existing benchmarks provide limited assessment of their scientific reasoning capabilities. Most datasets adopt s...

**Keywords:** Biomedical VQA, Multi-image Reasoning, Evaluation Methodology

[PDF](https://openreview.net/pdf/1adb191b5af8ef5a80bc0f74ffe73ab59cb673e9.pdf) · [Code](https://github.com/UniverseOfUniverse/SORBE.git) · [OpenReview](https://openreview.net/forum?id=Pj1Z7dWm4v)

---

### BioAgent Bench: An AI Agent Evaluation Suite for Bioinformatics
*Dionizije Fa, Marko Čuljak, Bruno Pandža, Mateo Čupić*

> We introduce BioAgent Bench, an evaluation suite designed for measuring the performance and robustness of AI agents in common bioinformatics tasks. The suite consists of manually curated end-to-end tasks (e.g., RNA-seq, ...

**Keywords:** agents, bioinformatics, benchmark, evaluation suite

[PDF](https://openreview.net/pdf/ed2cc15d6a6b5968c22c4303a190d340412216d5.pdf) · [Code](https://github.com/bioagent-bench) · [OpenReview](https://openreview.net/forum?id=2iFauBXg7Y)

---

### BioProBench: A Corpus and Benchmark for Biological Protocol Reasoning in Autonomous Science
*Yuyang Liu, Liuzhenghao Lv, Xiancheng Zhang, Jingya Wang*

> The realization of autonomous scientific experimentation is currently limited by LLMs' struggle to grasp the strict procedural logic and accuracy required by biological protocols. To address this fundamental challenge, w...

**Keywords:** Biological Protocol, Dataset and Benchmark, LLMs

[PDF](https://openreview.net/pdf/e7221e90baf870d8c036cd34c7d5a8d325ee1587.pdf) · [OpenReview](https://openreview.net/forum?id=8EZamwNqld)

---

### Bridging Dynamics and Data: A Unified Diffusion Framework for Mechanistically-Informed Epidemic Forecasting
*Guanghui Min, Tianhao Huang, Ke Wan, Qi R. Wang*

> Reliable epidemic forecasting is critical for public health decision-making yet remains challenging due to data sparsity and the non-stationary nature of disease dynamics. While recent hybrid models attempt to integrate ...

**Keywords:** epidemic forecasting, spatiotemporal forecasting, hybrid models

[PDF](https://openreview.net/pdf/1455baf8c80c0f6aedcc58841a3d7d67850d91b4.pdf) · [OpenReview](https://openreview.net/forum?id=AY7L7acRtD)

---

### CellBRIDGE: Learning Cellular Trajectories via Interaction-Aware Alignment
*Silas Ruhrberg Estévez, Nicolas Huynh, Tennison Liu, Roderik M. Kortlever*

> Inferring dynamics from population snapshots is a fundamental challenge in machine learning and biology. In scRNA-sequencing (scRNA-seq), destructive measurements preclude direct tracking of individual cells across time,...

**Keywords:** Cell Dynamics, Cell-Cell Interaction, RNA sequencing, Single-cell data

[PDF](https://openreview.net/pdf/887aeca6724901e89d85f6b834a19a0915bbc3b1.pdf) · [Code](https://github.com/nicolashuynh/cellbridge) · [OpenReview](https://openreview.net/forum?id=W9EgZALquo)

---

### CLINIC : Evaluating Multilingual Trustworthiness in Language Models for Healthcare
*Akash Ghosh, Srivarshinee Sridhar, Raghav Kaushik Ravi, Muhsin Muhsin*

> Integrating language models (LMs) in healthcare systems holds great promise for improving medical workflows and decision-making. However, a critical barrier to their global adoption is the lack of reliable evaluation of ...

**Keywords:** Multilingual, Trustworthiness, Language Models

[PDF](https://openreview.net/pdf/7f1f42a40dd036d70d745a8ca7f959c14bb0f9b8.pdf) · [Code](https://github.com/AikyamLab/clinic?tab=readme-ov-file) · [OpenReview](https://openreview.net/forum?id=bMsBArF8MT)

---

### DC-W2S: Dual-Consensus Weak-to-Strong Training for Reliable Process Reward Modeling in Biological Reasoning
*Chi-Min Chan, Ehsan Hajiramezanali, Xiner Li, Edward De Brouwer et al.*

> In scientific reasoning tasks, the veracity of the reasoning process is as critical as the final outcome. While Process Reward Models (PRMs) offer a solution to the coarse-grained supervision problems inherent in Outcome...

**Keywords:** Weak-to-Strong Generalization, Process Reward Modeling, Biological Reasoning

[PDF](https://openreview.net/pdf/584323b14bd609b57712b6c64c1b0248831950b8.pdf) · [Code](https://github.com/chanchimin/DC-W2S) · [OpenReview](https://openreview.net/forum?id=Lh3Hico2Pe)

---

### Deep Learning for BioImaging: What Are We Really Learning?
*Ivan Svatko, Maxime Sanchez, Ihab Bendidi, Gilles Cottrell*

> Representation learning has driven major advances in natural image analysis by enabling models to acquire high-level semantic features. In microscopy imaging, however, it remains unclear what current representation learn...

**Keywords:** Microscopy Imaging, Representation Learning, Benchmarking, Bioimaging

[PDF](https://openreview.net/pdf/47f2de2c5364d8f803a4aa6ec6afaee860324610.pdf) · [OpenReview](https://openreview.net/forum?id=ZgJlDylia4)

---

### Deliberate Evolution:  Agentic Reasoning for Sample-Efficient Symbolic Regression with LLMs
*Xinyu Pang, Zhanke Zhou, Xuan Li, Fangrui Lv*

> Symbolic regression (SR) discovers compact mathematical expressions from data, yet recent LLM-based evolutionary methods remain sample-inefficient because they rely mainly on scalar feedback such as MSE. We identify a co...

**Keywords:** Symbolic Regression, Large Language Model

[PDF](https://openreview.net/pdf/6b858c5ab779100cea6f8bb72c53da9d5ec04bea.pdf) · [Code](https://github.com/Xinyu-Pang/Deliberate-Evolution) · [OpenReview](https://openreview.net/forum?id=5JUrQ67tYL)

---

### Discontinuous Galerkin Neural Operator for Pathology Defocus Deblurring
*Shaoqing Duan, Haofei Song, Xintian Mao, Qingli Li*

> Defocus deblurring in pathological microscopy remains challenging due to the spatially varying and locally discontinuous nature of optical blur induced by a position-dependent integral imaging process.   Existing deep le...

**Keywords:** Defocus Deblurring, Pathology

[PDF](https://openreview.net/pdf/17cf2c6f128fc8ffee74194777d258c19dc2bed6.pdf) · [Code](https://github.com/DeepMed-Lab-ECNU/Single-Image-Deblur) · [OpenReview](https://openreview.net/forum?id=Og7FKaRBQA)

---

### Disease-Centric Vision-Language Pretraining with Hybrid Visual Encoding for 3D Computed Tomography
*Bowen Shi, Weiwei Cao, Ruifeng Yuan, Wanxing Chang*

> Vision–language pre-training (VLP) holds great promise for general-purpose medical AI by leveraging radiology reports as rich textual supervision, yet existing methods struggle with 3D CT imaging due to inefficient visua...

**Keywords:** Vision–language pre-training, disease-level contrastive learning, 3D CT

[PDF](https://openreview.net/pdf/54ef78f031b170bbd53d904507938d124ab1a2c8.pdf) · [OpenReview](https://openreview.net/forum?id=LcSPuepCDU)

---

### DIYHealth Suite: Dataset, Model, and Benchmark for Health Management at Home
*Changshuo Liu, Wu Junran, Zhongle Xie, Wenqiao Zhang et al.*

> Generative AI is reshaping healthcare, yet most existing advances rely on hospital-grade devices, which limits their accessibility and potential for health management outside clinical settings. With the proliferation of ...

**Keywords:** Large Language Model, Large Vision Language Model, Healthcare, Diagnosis-It-Yourself

[PDF](https://openreview.net/pdf/a2b5cd159d1332d9a904a5ea3858e39f032f2355.pdf) · [OpenReview](https://openreview.net/forum?id=xbAWn0w9kq)

---

### DSENet: A Novel Dual-Stream Enhancement Network for Multi-Scale Non-Stationary Time Series Forecasting
*Yuhan Wang, Yuanyuan Zou, Jie Cheng, Bin Dai*

> Accurately capturing local variations in long series has always been  one of the most challenging problems in time-series forecasting especially in medical signals, where local variations often indicate pathological even...

**Keywords:** Dual-Stream Enhancement, Time-Series Forecasting, Blood Glucose, Local Variations

[PDF](https://openreview.net/pdf/30275d27783f17cc663c99b69edcda8804fddcc9.pdf) · [OpenReview](https://openreview.net/forum?id=jAJJfsEwtd)

---

### Dynamic Decision Learning: Test-Time Evolution for Abnormality Grounding in Rare Diseases
*Jun Li, Mingxuan Liu, Jiazhen Pan, Che Liu*

> Clinical abnormality grounding for rare diseases is often hindered by data scarcity, rendering supervised fine-tuning infeasible and single-pass inference highly unstable. Thus, we propose Dynamic Decision Learning (DDL)...

**Keywords:** clinical abnormality grounding, rare diseases, large vision-language models, Dynamic Decision Learning

[PDF](https://openreview.net/pdf/da6acc76d9e4b7d756b7832eafaad9686f7ca1a7.pdf) · [Code](https://github.com/compai-lab/2026-ICML-DDL) · [OpenReview](https://openreview.net/forum?id=YcccAbXbVK)

---

### ECG-R1: Protocol-Guided and Modality-Agnostic MLLM for Reliable ECG Interpretation
*Jiarui Jin, Haoyu Wang, Xingliang Wu, Xiaocheng Fang et al.*

> Electrocardiography (ECG) serves as an indispensable diagnostic tool in clinical practice, yet existing multimodal large language models (MLLMs) remain unreliable for ECG interpretation, often producing plausible but cli...

**Keywords:** ECG, MLLM, ECG interpretation, reinforcement learning

[PDF](https://openreview.net/pdf/0bd5e5e528bcf4df511aa1cca492d8b030aa1da2.pdf) · [Code](https://github.com/PKUDigitalHealth/ECG-R1) · [OpenReview](https://openreview.net/forum?id=dcLjhvVU47)

---

### EEG-FM-Bench: A Comprehensive Benchmark for the Systematic Evaluation and Diagnostic Analyses of EEG Foundation Models
*Wei Xiong, Jiangtong Li, Jie Li, Kun Zhu*

> Electroencephalography foundation models (EEG-FMs) have advanced brain signal analysis, but the lack of standardized evaluation benchmarks impedes model comparison and scientific progress.  Current evaluations rely on in...

**Keywords:** EEG Foundation Model, Benchmark on EEG, Brain-Computer Interface

[PDF](https://openreview.net/pdf/80bcf3ef6f22ed255810802098014ff763d8deb9.pdf) · [Code](https://github.com/xw1216/EEG-FM-Bench) · [OpenReview](https://openreview.net/forum?id=vGeNaFHdET)

---

### Effects of Structural Reward Shaping on Biophysical Properties in RL-Trained Plasmid Generators
*McClain Thiel, Angus G. Cunningham, Chris P Barnes*

> We compare the efficacy and distributional effects of supervised fine-tuning (SFT) and reinforcement learning (RL) post-training for PlasmidGPT, a foundation model for whole-plasmid generation, using Group Relative Polic...

**Keywords:** GRPO, Reinforcement Learning, DNA, DNA-LM

[PDF](https://openreview.net/pdf/992e428cd0c9eca3a14ebde12b25222fb0c09c02.pdf) · [OpenReview](https://openreview.net/forum?id=uiMxVE16m3)

---

### Evidential Reasoning Advances Interpretable Real-World Disease Screening
*Chenyu Lian, Hong-Yu Zhou, Jing Qin*

> Disease screening is critical for early detection and timely intervention in clinical practice. However, most current screening models for medical images suffer from limited interpretability and suboptimal performance. T...

**Keywords:** Interpretable, Disease Screening, Evidence-based

[PDF](https://openreview.net/pdf/24e90b27bdbaa8bc7cd2f851674ee8477277586b.pdf) · [Code](https://github.com/DopamineLcy/EviScreen) · [OpenReview](https://openreview.net/forum?id=FCVPVqRLDJ)

---

### Expert-guided Clinical Text Augmentation via Query-Based Model Collaboration
*Dongkyu Cho, Miao Zhang, Gregory D Lyng, Rumi Chunara*

> Data augmentation is a widely used strategy to improve model robustness and generalization by enriching training datasets with synthetic examples. While large language models (LLMs) have demonstrated strong generative ca...

**Keywords:** Data augmentation, Large language models, Healthcare

[PDF](https://openreview.net/pdf/8c8d3e6b75de35b33981c1570d7fddead2736bc6.pdf) · [OpenReview](https://openreview.net/forum?id=AuPb9MEDdq)

---

### Exploring Accurate and Transparent Domain Adaptation in Predictive Healthcare via Concept-Grounded Orthogonal Inference
*Pengfei Hu, Chang Lu, Feifan Liu, Yue Ning*

> Deep learning models for clinical event prediction on electronic health records (EHR) often suffer performance degradation when deployed under different data distributions.  While domain adaptation (DA) methods can mitig...

**Keywords:** Domain Adaptation, Clinical Prediction, Transparency, Sparse Autoencoder

[PDF](https://openreview.net/pdf/5c8ab9e38823df6b3a58a5c396975a5c2249e12b.pdf) · [OpenReview](https://openreview.net/forum?id=KidQq3EaOe)

---

### FlowCloud: Learning Continuous Spatiotemporal Dynamics from Unpaired Sparse Point Cloud Snapshots
*Yinbo Liu, Keyang Ye, Wenshan Sun, Handi Gao*

> Reconstructing unified continuous dynamics from sparse, non-contiguous, and unpaired point cloud snapshots remains a fundamental challenge in spatiotemporal analysis for computer vision and developmental biology. Existin...

**Keywords:** Point Cloud Dynamics; Optimal Transport; Neural Ordinary Equations; Spatial Transcriptomics

[PDF](https://openreview.net/pdf/1538ab583c7c031a2297b85a75e6d77c2ed1cc0e.pdf) · [Code](https://github.com/yinboliu-git/FlowCloud) · [OpenReview](https://openreview.net/forum?id=lf2kkzspMA)

---

### From Conflict to Consensus: Boosting Medical Reasoning via Multi-Round Agentic RAG
*Wenhao Wu, Zhentao Tang, Yafu Li, Shixiong Kai*

> Large Language Models (LLMs) exhibit high reasoning capacity in medical question-answering, but their tendency to produce hallucinations and outdated knowledge poses critical risks in healthcare fields. While Retrieval-A...

**Keywords:** Medical reasoning, Agentic reasoning, Retrieval-augmented generation, Large language models

[PDF](https://openreview.net/pdf/6c8230cfef1039c228ec607a36ddaecb911891ad.pdf) · [Code](https://github.com/NJU-RL/MA-RAG) · [OpenReview](https://openreview.net/forum?id=S7lpdz7NAW)

---

### From Knowledge to Inference: Formalizing Specialized Public Health Reasoning on GlobalHealthAtlas
*Zhaokun Yan, Shan Xu, Wuzheng Dong, Zhaohan Liu et al.*

> Public health reasoning requires population level inference grounded in scientific evidence, expert consensus, and safety constraints. However, it remains underexplored as a structured machine learning problem with limit...

**Keywords:** Public Health, Domain-Aligned Evaluation, Multilingual Dataset, Consensus Alignment

[PDF](https://openreview.net/pdf/983264832db44b3c5eadba6b5d2dbd409bc491c6.pdf) · [Code](https://github.com/Jan8217/GlobalHealthAtlas) · [OpenReview](https://openreview.net/forum?id=02Nq73lCe6)

---

### From Token to Token Pair: Efficient Prompt Compression for Large Language Models in Clinical Prediction
*Mingcheng Zhu, Zhiyao Luo, Yu Liu, Tingting Zhu*

> By processing electronic health records (EHRs) as natural language sequences, large language models (LLMs) have shown potential in clinical prediction tasks such as mortality prediction and phenotyping. However, longitud...

**Keywords:** Clinical prediction, Prompt compression, Medical tokenization, Electronic health records

[PDF](https://openreview.net/pdf/65645f4babbd2bb22cce2ab1b40a995ac8370759.pdf) · [Code](https://github.com/JasonZuu/MedTPE) · [OpenReview](https://openreview.net/forum?id=SRGpmDQjJM)

---

### FunCQNet: A Functional Censored Quantile Neural Network for Predicting Long-Term Post-Transplant Kidney Survival
*Jiaqi Men, Hua Liu, Yiming Tang, Jinhong You*

> Accurate survival prediction in kidney transplantation is critical yet challenging due to the complex interplay between functional biomarkers and patient characteristics under censoring. To address this, we propose a fun...

**Keywords:** Functional data analysis, Functional quantile regression, Survival analysis, Kidney transplant

[PDF](https://openreview.net/pdf/f0bf0babbfff31464250fc93726138cc9b2f63a9.pdf) · [Code](https://github.com/Yiming-Tang/FunCQNet) · [OpenReview](https://openreview.net/forum?id=wNL0qGb2MN)

---

### GLEAN: Guideline-Grounded Evidence Accumulation for High-Stakes Agent Verification
*Yichi Zhang, Nabeel Seedat, Yinpeng Dong, Peng Cui*

> As LLM-powered agents have been used for high-stakes decision-making, such as clinical diagnosis, it becomes critical to develop reliable verification of their decisions to facilitate trustworthy deployment. Yet, existin...

**Keywords:** verification, healthcare, agent

[PDF](https://openreview.net/pdf/70f90e5b1d330ce5ee601761d428b8d61a04c862.pdf) · [OpenReview](https://openreview.net/forum?id=FP23eFYhAy)

---

### HDTree: Generative Modeling of Cellular Hierarchies for Robust Lineage Inference
*Zelin Zang, WenZhe Li, Yongjie Xu, Chang Yu*

> In single-cell research, tracing and analyzing high-throughput single-cell differentiation trajectories is crucial for understanding biological processes. Key to this is the robust modeling of hierarchical structures tha...

**Keywords:** Cell, AI4S, Hierarchical Representation, AI for science

[PDF](https://openreview.net/pdf/3a600580dc1124d5f5931343eb5b4cde995622cc.pdf) · [Code](https://github.com/zangzelin/code_HDTree_icml) · [OpenReview](https://openreview.net/forum?id=mURSJDd7hU)

---

### HEARTS: Benchmarking LLM Reasoning on Health Time Series
*Sirui Li, Shuhan Xiao, Mihir Joshi, Ahmed Metwally*

> The rise of large language models (LLMs) has shifted time series analysis from narrow analytics to general-purpose reasoning. Yet, existing benchmarks cover only a small set of health time series modalities and tasks, fa...

**Keywords:** LLM Reasoning, Time Series Analysis, AI for Healthcare

[PDF](https://openreview.net/pdf/94f02dc2f73566b4ce5f556099cc85037b35654e.pdf) · [Code](https://yang-ai-lab.github.io/HEARTS/) · [OpenReview](https://openreview.net/forum?id=qj4EnIvNU4)

---

### How (Not) to Hybridize Neural and Mechanistic Models for Epidemiological Forecasting
*Yiqi Su, Ray Lee, Jiaming Cui, Naren Ramakrishnan*

> Epidemiological forecasting from surveillance data is a hard problem and hybridizing mechanistic compartmental models with neural models is a natural direction. The mechanistic structure helps keep trajectories epidemiol...

**Keywords:** Neural ODEs, Mechanistic model, Data decomposition, Epidemiological modeling

[PDF](https://openreview.net/pdf/9bc60b409d8b72180b9ebeb449e5b38095a3ea16.pdf) · [Code](https://github.com/yiqisu/EpiNode.git) · [OpenReview](https://openreview.net/forum?id=otBTuq5AKB)

---

### How Should Transformers Encode Numeric Values in Electronic Health Records?
*Maria Elkjær Montgomery, Christian Igel, Mikkel Fruelund Odgaard, Martin Sillesen*

> How do we encode numeric values in transformer-based sequence processing, particularly in electronic health record (EHR) data? We systematically compare discrete, continuous, and hybrid value encoding strategies using sy...

**Keywords:** numeric value representation, transformer models, electronic health records, representation learning

[PDF](https://openreview.net/pdf/09c27a6364174159b7adc19e21f245e2400437dd.pdf) · [Code](https://github.com/Montgomeryyyy/BONSAI_values/tree/main) · [OpenReview](https://openreview.net/forum?id=YzlscRoNUj)

---

### HVR-Met: A Hypothesis-Verification-Replanning Agentic System for Extreme Weather Diagnosis
*Shuo Tang, Jiadong Zhang, Gengxian Zhou, Qizhao Jin et al.*

> While deep learning-based weather forecasting paradigms have made significant strides, addressing extreme weather diagnostics remains a formidable challenge. This gap exists primarily because the diagnostic process deman...

**Keywords:** ERA5, Extreme Weather Diagnosis

[PDF](https://openreview.net/pdf/651b7be5f53e5485ad59005ae8e51b5538207d0d.pdf) · [OpenReview](https://openreview.net/forum?id=tb2aPbeg86)

---

### iLoRA: Bayesian Low-Rank Adaptation with Latent Interaction Graphs for Microbiome Diagnosis
*Yang Song, Yixuan Zhang, Lingfa Meng, Tongyuan Hu*

> Parameter-efficient adaptation has made LLMs practical for domain prediction, but standard LoRA still relies on a static low-rank update and does not expose the latent interactions that often drive scientific labels. We ...

**Keywords:** Bayesian Low-Rank Adaptation; Graph-Conditioned LoRA; Parameter-Efficient Fine-Tuning; Latent Interaction Graphs; Microbiome Diagnosis; Uncertainty Quantification

[PDF](https://openreview.net/pdf/0820bd95008a7c690c48ebc7c774e72c62adf582.pdf) · [Code](https://github.com/GoodGoodMaul/iLoRA) · [OpenReview](https://openreview.net/forum?id=7FF8g7hCre)

---

### InfiMed-ORBIT: Aligning LLMs on Open-Ended Complex Tasks via Rubric-Based Incremental Training
*Pengkai Wang, Pengwei Liu, Qi Zuo, Zhijie Sang*

> Reinforcement learning (RL) has powered many recent breakthroughs in large language models (LLMs), especially for tasks where rewards can be computed automatically, such as code generation. However, it is less effective ...

**Keywords:** LLM, post-training, medicine

[PDF](https://openreview.net/pdf/8dcad95ebb18a8e6d034de86514025d8124a3b38.pdf) · [OpenReview](https://openreview.net/forum?id=z2vVeIscEd)

---

### Influence-Guided Symbolic Regression: Scientific Discovery via LLM-Driven Equation Search with Granular Feedback
*Evgeny Saveliev, Samuel Holt, Nabeel Seedat, David L. Bentley*

> Large Language Models (LLMs) offer a promising avenue for scientific discovery, yet their application to symbolic regression is often constrained by inefficient search strategies and coarse feedback signals. Current meth...

**Keywords:** Symbolic Regression, Equation Discovery, AI for Science, Scientific Discovery

[PDF](https://openreview.net/pdf/954ce510d1a5902db51e49c098151be23811c8df.pdf) · [Code](https://github.com/DrShushen/IGSR) · [OpenReview](https://openreview.net/forum?id=ujiUua1gGV)

---

### Interpretability Driven Evolutionary Approach for the Design of Biological Sequences
*Akash Pandey, Wei Chen, Sinan Keten*

> Designing biological sequences such as proteins and DNA for desired properties is challenging due to vast search spaces and limited wet lab evaluation budgets. Current evolutionary approaches ignore sequential dependenci...

**Keywords:** Biological Sequence Design, Active learning, Evolutionary Approach, Explainable AI

[PDF](https://openreview.net/pdf/2361d5541e8d766a19635318944e46e64e3a0f88.pdf) · [Code](https://github.com/pandeyakash23/IDEAS.git) · [OpenReview](https://openreview.net/forum?id=gaq60U4jvU)

---

### Learning Fingerprints for Medical Time Series with Redundancy-Constrained Information Maximization
*Huayu Li, ZhengXiao He, Xiwen Chen, Jingjing Wang*

> Learning meaningful representations from medical time series (MedTS), such as ECG or EEG signals, is a critical challenge. These signals are often high-dimensional, variable-length, and rife with noise. Existing self-sup...

**Keywords:** Medical Time Series, Representation learning, Healthcare

[PDF](https://openreview.net/pdf/9f7f62158f7d4f03054d24359b0bcc47ed8fa84f.pdf) · [OpenReview](https://openreview.net/forum?id=lrRBHFIgaK)

---

### Learning Treatment Allocations with Risk Control Under Partial Identifiability
*Sofia Ek, Dave Zachariah*

> Learning beneficial treatment allocations for a patient population is an important problem in precision medicine. For such allocations, a certain proportion of treated patients may not receive any benefit. This proportio...

**Keywords:** precision medicine, off-policy learning, treatment allocation, partial identification

[PDF](https://openreview.net/pdf/928768f8775b3b3a0815383778b033de1c02a78b.pdf) · [Code](https://github.com/sofiaek/treatment-risk-control/) · [OpenReview](https://openreview.net/forum?id=9kWVQtpvJi)

---

### LLM-Guided Diagnostic Evidence Alignment for Medical Vision–Language Pretraining under Limited Pairing
*Huimin Yan, Liang Bai, Xian Yang, Long Chen*

> Most existing CLIP-style medical vision--language pretraining methods rely on global or local alignment with substantial paired data. However, global alignment is easily dominated by non-diagnostic information, while loc...

**Keywords:** Medical Vision-Language Pretraining, Multimodal Learning, Diagnostic Evidence Alignment

[PDF](https://openreview.net/pdf/4df9f9d536e4d395497bc2a9f8709779941dbe05.pdf) · [OpenReview](https://openreview.net/forum?id=AftqpgG6Ja)

---

### M-IDoL: Information Decomposition for Modality-Specific and Diverse Representation Learning in Medical Foundation Model
*Yihang Liu, Longzhen Yang, Jiaxiong Yang, Ying Wen*

> Medical foundation models (MFMs) aim to learn universal representations from multimodal medical images that can generalize effectively to diverse downstream clinical tasks. However, most existing MFMs suffer from informa...

**Keywords:** Medical Image Analysis, Self-supervised Learning, Medical Foundation Model, Contrastive Learning

[PDF](https://openreview.net/pdf/508d5ccbdbfc6f924151c529fe60066b14a73134.pdf) · [OpenReview](https://openreview.net/forum?id=pn5lQVm3DH)

---

### Marrying Generative Model of Healthcare Events with Digital Twin of Social Determinants of Health for Disease Reasoning
*Ziquan Wei, Tingting Dan, Guorong Wu*

> Despite the central role of sensor-derived measurements such as imaging traits and plasma biomarkers in biomedical research and clinical practice, existing generative models for disease prediction largely depend on event...

**Keywords:** Disease reasoning, Longitudinal EHR, Functional Connectivity, Multi-organ

[PDF](https://openreview.net/pdf/d831dc201066880cfcebb565565bb35f8330a20e.pdf) · [Code](https://github.com/Chrisa142857/DiffDT) · [OpenReview](https://openreview.net/forum?id=9GKURFWGeh)

---

### Med-Scout: Curing MLLMs' Geometric Blindness in Medical Perception via Geometry-Aware RL Post-Training
*Anglin Liu, Ruichao Chen, Yi Lu, Hongxia Xu*

> Despite recent Multimodal Large Language Models (MLLMs)' linguistic prowess in medical diagnosis, we find even state-of-the-art MLLMs suffer from a critical perceptual deficit: **geometric blindness**. This failure to gr...

**Keywords:** Multimodal Large Language Model, Geometric Blindness, Medical Visual Question Answering

[PDF](https://openreview.net/pdf/1aadb632e1fd0cbfe922731e6e33f42419f0f7f6.pdf) · [Code](https://github.com/HKUSTGZ-ML4Health-Lab/Med-Scout) · [OpenReview](https://openreview.net/forum?id=iTkQLqa1Ha)

---

### MEDA: Medical-Oriented Activation Editing for Hallucination Mitigation in Medical Large Vision-Language Model
*Tianbo Wang, Yuqing Ma, Lingyan Meng, Zhange Zhang et al.*

> Medical Large Vision-Language Models (Med-LVLMs) suffer from severe hallucinations, posing critical safety risks in clinical deployment. Editing LVLM activations has shown promise for mitigating hallucination with minima...

**Keywords:** Medical Large Vision-Language Model, Hallucination, Activation Editing, Medical Expertise

[PDF](https://openreview.net/pdf/ce958c1302ea818026f3cf7da9ea56db7903f792.pdf) · [OpenReview](https://openreview.net/forum?id=VzZxoRiU3G)

---

### MedCoG: Maximizing LLM Inference Density in Medical Reasoning via Meta-Cognitive Regulation
*Yu Zhao, Hao Guan, Yongcheng Jing, Ying Zhang*

> Large Language Models (LLMs) have shown strong potential in complex medical reasoning yet face diminishing gains under inference scaling laws. While existing studies augment LLMs with various knowledge types, it remains ...

**Keywords:** Medical Reasoning, Large Language Models, Medical Agent, Knowledge Graph

[PDF](https://openreview.net/pdf/8fa86e7e7711086862e70bbd6d51f2c81d800098.pdf) · [OpenReview](https://openreview.net/forum?id=tQCMbay712)

---

### MedMosaic: A Challenging Large Scale Benchmark of Diverse Medical Audio
*Harshit Rajgarhia, Shuubham Ojha, Asif Shaik, Akhil Pothanapalli*

> Medical audio data is difficult to collect due to privacy regulations and high annotation costs arising from domain expertise. Thus, existing benchmarks tend to underrepresent complex medical audio scenarios. To address ...

**Keywords:** Audio Reasoning, Multimodal Reasoning, Prompt Engineering, Benchmarking

[PDF](https://openreview.net/pdf/29ba059400dd936d7bd1c40657e56d160a5e1669.pdf) · [OpenReview](https://openreview.net/forum?id=OMdQJQwp26)

---

### MedREK: Retrieval-Based Editing for Medical LLMs with Key-Aware Prompts
*Shujun Xia, Haokun Lin, Yichen Wu, Yinan Zhou et al.*

> Large Language Models (LLMs) hold great promise for healthcare applications, but fast-changing medical knowledge can quickly make their outputs outdated or inaccurate, limiting use in high-stakes settings. Model editing ...

**Keywords:** Clinical/Healthcare Application, Knowledge Editing, Model Editing

[PDF](https://openreview.net/pdf/0cd769cd5001e54a300fdbf8d9754ba5f41856b2.pdf) · [Code](https://github.com/mylittleriver/MedREK) · [OpenReview](https://openreview.net/forum?id=XFHjS8kw6X)

---

### MedScope: Incentivizing "Think with Videos" for Clinical Reasoning via Coarse-to-Fine Tool Calling
*Wenjie Li, Yujie Zhang, Haoran Sun, Xingqi He et al.*

> Long-form clinical videos are central to visual evidence-based decision-making, with growing importance for applications such as surgical robotics and related settings. However, current multimodal large language models t...

**Keywords:** Large Vision-Language Models (LVLMs), Medical Video Reasoning, Visual Chain-of-Thought, Agentic Reinforcement Learning

[PDF](https://openreview.net/pdf/cc2670e548f2c505e2e242362db01eb9879ffea4.pdf) · [Code](https://github.com/SII-WenjieLisjtu/MedScope) · [OpenReview](https://openreview.net/forum?id=OOyPj8hdiM)

---

### MedSIGHT: Towards Grounded Visual Comprehension in Medical Large Vision-Language Models
*Aofei Chang, Le Huang, Alex James Boyd, Parminder Bhatia*

> Medical large vision-language models (Med-LVLMs) have recently achieved remarkable progress in vision–language comprehension and medical image segmentation. However, existing models still struggle to unify these two capa...

**Keywords:** Medical Large Vision-Language Models, Medical Visual Grounding

[PDF](https://openreview.net/pdf/bfa274e8408889a5c511f9faeca143cea8a30f52.pdf) · [Code](https://github.com/Aofei-Chang/MedSIGHT) · [OpenReview](https://openreview.net/forum?id=a7mORMEWYX)

---

### Modeling Attributional Style at Scale: A Dataset and Analysis for Psychological Attribution Assessment and Reframing
*Qiang Zhou, Hanzhen Zhu, Pan Wang, Rui Tu et al.*

> According to the reformulated Learned Helplessness theory, repeated exposure to uncontrollable negative events can foster a depressogenic attributional style—increasing susceptibility to depression yet remaining a tracta...

**Keywords:** Psychological Attribution

[PDF](https://openreview.net/pdf/1baa17c0ec27ea8fc0fb7488775b26f19a2f66c5.pdf) · [Code](https://github.com/qzhou711/ASTD) · [OpenReview](https://openreview.net/forum?id=qgyEEb6wkh)

---

### Modeling Long-Tail Relations in the Operating Room via In-Context Multimodal Learning
*Boqiang Xu, Wei Zhang, Ding Ma, Jian Liang*

> Operating room (OR) scene graph generation (SGG) enables holistic modeling of OR domains by encoding interactions among medical staff, tools, and equipment as triplet-based structured scene graphs. Although existing OR S...

**Keywords:** Operating Room, Scene Graph, MLLM, In-contex Learning

[PDF](https://openreview.net/pdf/1988296e478dc7f257148eea328b9e46c9257d28.pdf) · [OpenReview](https://openreview.net/forum?id=gkR8wS8OXs)

---

### MoRGen: Mixture-of-Resolutions Generative Forecasting for Irregularly Sampled Medical Time-Series Data
*Nassim Oufattole, Matthew B.A. McDermott, Collin Stultz*

> Autoregressive generative models for irregularly sampled clinical time-series data are increasingly used for zero-shot risk forecasting. Prior work typically adopts a single fine-grained discretization of time, where tok...

**Keywords:** ehr, foundation model, long context, clinical prediction making

[PDF](https://openreview.net/pdf/f4fceded86d8b4ef33516f42e57b4ede96474281.pdf) · [Code](https://github.com/Oufattole/morgen) · [OpenReview](https://openreview.net/forum?id=Hvqkdu4Luv)

---

### Near-Optimal Dynamic Matching via Coarsening with Application to Heart Transplantation
*Itai Zilberstein, Ioannis Anagnostides, Zachary W. Sollie, Arman Kilic*

> Online matching has been a mainstay in domains such as Internet advertising and organ allocation, but practical algorithms often lack strong theoretical guarantees. We take an important step toward addressing this by dev...

**Keywords:** Online matching, heart transplant allocation, clustering

[PDF](https://openreview.net/pdf/0db01764fd770afd955ad000a7a8295bf0235464.pdf) · [OpenReview](https://openreview.net/forum?id=HQTsYta4XX)

---

### No Data? No Problem: Robust Vision-Tabular Learning with Missing Values
*Marta Hasny, Laura Alexandra Daza, Keno Bressem, Maxime Di Folco*

> Large-scale medical biobanks provide imaging data complemented by extensive tabular information, such as clinical measurements or demographics. However, this abundance of tabular attributes does not reflect real-world da...

**Keywords:** Multimodal, Vision-tabular Learning, Missing Data

[PDF](https://openreview.net/pdf/576946fa2507d538cc6e4808ca5ae97859640eda.pdf) · [Code](https://github.com/marteczkah/RoVTL) · [OpenReview](https://openreview.net/forum?id=guBK9kwmEL)

---

### Optimizing Inference-Time Compute for Medical Reasoning via Uncertainty Quantification
*Shaohao Rui, Kaitao Chen, Weijie Ma, Xiaosong Wang*

> Extended Chain-of-Thought (CoT) reasoning has significantly bolstered the capabilities of medical large language models (LLMs). However, current models exhibit static computational expenditure, applying lengthy reasoning...

**Keywords:** Chain of Thought, Inference Efficiency, Medical QA

[PDF](https://openreview.net/pdf/c0db46cb76a4fadf97a195164b05a8538a1fa7e2.pdf) · [Code](https://github.com/shaohao011/AdaThinkMed) · [OpenReview](https://openreview.net/forum?id=zlJehQJATy)

---

### OSF: On Pre-training and Scaling of Sleep Foundation Models
*Zitao Shuai, Zongzhe Xu, David Yang, Wei Wang*

> Polysomnography (PSG) provides the gold standard for sleep assessment but suffers from substantial heterogeneity across recording devices and cohorts. There have been growing efforts to build general-purpose foundation m...

**Keywords:** Healthcare, Foundation Model, Physiological Signal, AI for Healthcare

[PDF](https://openreview.net/pdf/c7a46099be8cc0e334f6cbf4082a6a6e74cde3fb.pdf) · [Code](https://github.com/yang-ai-lab/OSF-Open-Sleep-FM) · [OpenReview](https://openreview.net/forum?id=rlVGCyjqnt)

---

### PathwayLLM: Explainable Clinical Trajectory Modeling with Structured Pathways for Sepsis Prediction
*Zhengqiu Yu, Yueping Ding, Xiangrong Liu*

> Patient-level sepsis prediction requires models that track clinical deterioration over time and integrate heterogeneous structured evidence from electronic health records. We present PathwayLLM, a trajectory-based framew...

**Keywords:** Sepsis prediction, Clinical trajectory modeling, Electronic health records, Large language models

[PDF](https://openreview.net/pdf/332b8086024ec5fc16abadd70b4c9eec768198a8.pdf) · [OpenReview](https://openreview.net/forum?id=oB7gZX7MKP)

---

### PPI Candidate Ranking: Large-Scale Evaluation of a Domain Knowledge–Guided Pipeline
*Maria Emilia Russo, Federico Di Valerio, Alessia Borghini, Alessio Ragno*

> Computational approaches have become central to Protein–Protein Interaction (PPI) research, complementing experimental techniques that remain costly and incomplete. While modern deep learning methods capture diverse biol...

**Keywords:** protein protein interaction, computational biology, explainable ai, protein language models

[PDF](https://openreview.net/pdf/5a3378425026d2f0ecf1bcb15c1d5d07adc1c81e.pdf) · [OpenReview](https://openreview.net/forum?id=JRsQDPWFCC)

---

### Process Reward Agents for Steering Knowledge-Intensive Reasoning
*Jiwoong Sohn, Tomasz Sternal, Kenneth Styppa, Torsten Hoefler*

> Reasoning in knowledge-intensive domains remains challenging as intermediate steps are often not locally verifiable: unlike math or code, evaluating step correctness may require synthesizing clues across large external k...

**Keywords:** process reward model (PRM); language model agents; medical reasoning; question answering; retrieval-augmented generation (RAG); beam search; test-time scaling

[PDF](https://openreview.net/pdf/a7d75427f622f372ee2f4172fa8ffe807ff87946.pdf) · [Code](https://process-reward-agents.github.io/) · [OpenReview](https://openreview.net/forum?id=3moDc5lpBC)

---

### Quantifying the Generalization Gap in Seizure Detection: A Large-Scale Empirical Benchmark via the SzCORE Challenge
*Jonathan Dan, Amirhossein Shahbazinia, Christodoulos Kechris, David Atienza*

> Reliable automatic seizure detection from long-term electroencephalogram recordings (EEG) remains an unsolved challenge, as current models often fail to generalize across patients or clinical settings. Manual EEG review ...

**Keywords:** Seizure Detection, Generalization, Benchmarking, Electroencephalography

[PDF](https://openreview.net/pdf/6fa7b9e53efd47fc24ce03d83dbbdfc116c5d92b.pdf) · [Code](https://github.com/esl-epfl/szcore) · [OpenReview](https://openreview.net/forum?id=3vhn9kVVY5)

---

### RECTOR: Masked Region-Channel-Temporal Modeling for Affective and Cognitive Representation Learning
*Jinhan Liu, Mahsa Shoaran*

> Affective and cognitive disorders manifest as distributed, time-varying brain network dynamics across regions, channels, and time, challenging robust representation learning from EEG/sEEG for clinical diagnosis. We propo...

**Keywords:** self-supervised learning, self-attention, brain topology, masked modeling

[PDF](https://openreview.net/pdf/26b24f589f90424a684b17ef6d1b8d728cb4381c.pdf) · [OpenReview](https://openreview.net/forum?id=7GSLP4hqUO)

---

### Regulating Anatomy-Aware Rewards via Trajectory-Integral Feedback for Volumetric Computed Tomography Analysis
*Tianwei Lin, Zhongwei Qiu, Jie Cao, Jiang Liu et al.*

> Medical vision-language models (VLMs) have rapidly advanced as general-purpose multimodal assistants, yet their deployment in 3D Computed Tomography (CT) analysis remains constrained by a persistent mismatch between opti...

**Keywords:** 3D CT, Medical VLM, GRPO

[PDF](https://openreview.net/pdf/a9600070f7ad0d6ba7d32cc50c9324879fa5d086.pdf) · [Code](https://github.com/ZJU4HealthCare/TIF-GRPO) · [OpenReview](https://openreview.net/forum?id=6YVSHa3g4b)

---

### Reinforcement Learning for Tool-Calling Agents in Fast Healthcare Interoperability Resources (FHIR)
*Marius Knorr, Robert Müller, Jan Peter Bremer, Nils Schweingruber*

> Fast Healthcare Interoperability Resources (FHIR) is the dominant standard for interoperable exchange of healthcare data. In FHIR, electronic health records form a directed graph of resources. Answering clinically meanin...

**Keywords:** FHIR, Agentic Retrieval, GRPO, QA

[PDF](https://openreview.net/pdf/bd05a8c09d5fdcdaa68c9960b7206311f97e1367.pdf) · [OpenReview](https://openreview.net/forum?id=Ep6EcExLIY)

---

### Residual-Guided Multi-Resolution Refinement of Foundation Models: A Case Study in Drought Forecasting
*Wentao Gao, Jiuyong Li, Lin Liu, Thuc Duy Le*

> Regional climate prediction presents unique challenges for time series foundation models, which typically process temporal patterns through single-pass inference. Expert climatologists, in contrast, employ multi-scale te...

**Keywords:** Drought Prediction, Time series foundation models, Inference

[PDF](https://openreview.net/pdf/4b77fea231253090286bbcc67c9af6240cf18d68.pdf) · [Code](https://github.com/Wentao-Gao/RGMR_implementation) · [OpenReview](https://openreview.net/forum?id=ERCbhCrHo3)

---

### Salus: Strategic Diagnostic Testing for Complex Diagnosis via Multi-Agent Reinforcement Learning
*Shuohao Gao, Xuanzhong Chen, Lingxiao Luo, Zilin Ding*

> Diagnosing complex diseases is inherently a sequential and iterative medical investigation process, in which a clinician strategically requests multiple rounds of diagnostic tests to differentiate among similar diseases ...

**Keywords:** Sequential Decision Making, Reinforcement Learning, Large Language Models, Multi-Agent Systems

[PDF](https://openreview.net/pdf/538b51a0e48a08ce527cede5ea456d969d21e289.pdf) · [Code](https://github.com/ShuohaoGao/ICML-Salus) · [OpenReview](https://openreview.net/forum?id=KPsrOYaU79)

---

### SGERA: Stein-Guided ECG-Report Alignment for ECG Representation Learning
*Jian Chen, Yipeng Du, Wenhao Yuan, Shuai Wang*

> Electrocardiogram (ECG) representation learning via ECG-report alignment is often hindered by the inherent structural and statistical divergence between signals and natural language. Existing methods struggle to bridge t...

**Keywords:** ECG Representation Learning, Multi-modal learning, Zero-shot classification

[PDF](https://openreview.net/pdf/671a7f3c93376b1f45f8ffa4658c9f93eb338a29.pdf) · [Code](https://github.com/cccccj-03/SGERA/tree/main) · [OpenReview](https://openreview.net/forum?id=iEtOxzAs51)

---

### Small Agent Group is the Future of Digital Health
*Yuqiao Meng, Luoxi Tang, Dazheng Zhang, Rafael Brens*

> The rapid adoption of large language models (LLMs) in digital health has been driven by a "scaling-first" philosophy, i.e., the assumption that clinical intelligence increases with model size and data. However, real-worl...

**Keywords:** Clinical Reasoning, Large Language Models, Multi-Agent Systems

[PDF](https://openreview.net/pdf/d08fc18ae5ebcef4fb8d6fe051650cf5170b7b99.pdf) · [Code](https://github.com/mengyuqiao/SAG) · [OpenReview](https://openreview.net/forum?id=ALVnRcngPb)

---

### SPATIA: Multimodal Generation and Prediction of Spatial Cell Phenotypes
*Zhenglun Kong, Mufan Qiu, John Boesen, xiang lin*

> Understanding how cellular morphology, gene expression, and spatial context jointly shape tissue function is a central challenge in biology. Image-based spatial transcriptomics technologies now provide high-resolution me...

**Keywords:** Spatial transcriptomics, Multimodal Model, Spatially conditioned morphology generation

[PDF](https://openreview.net/pdf/6df30389ec5230663a3ec26c469b76e419fb5a42.pdf) · [OpenReview](https://openreview.net/forum?id=8As2E4z9qt)

---

### Spherical Procrustes Alignment for Reliable Medical Audio Diagnosis
*Ying Wang, Guoheng Huang, Chan-Tong Lam, Xiaochen Yuan*

> Reliable medical audio diagnosis requires models that are both accurate and honest about their uncertainty. However, fine-tuned models on small, imbalanced datasets often become overconfident due to norm bias, where pred...

**Keywords:** Medical audio diagnosis, Trustworthy AI, Confidence calibration, Data scarcity

[PDF](https://openreview.net/pdf/3fedc1753b8389837b369d806c6128201867291e.pdf) · [Code](https://github.com/wangying1586/SPA) · [OpenReview](https://openreview.net/forum?id=czRY4Qj153)

---

### SPR-RAFT: Parameter-Efficient Regression-Aware Fine-Tuning for Biomedical LLM Regression
*Yuanlin Yang, Chenhui Li, Xuhao Guo, Anqi Zhang*

> Biomedical regression tasks require predicting continuous targets from heterogeneous and unstructured evidence. While Large Language Models (LLMs) provide a robust interface for reasoning over mixed modalities, they are ...

**Keywords:** large language models, fine-tuning, soft prompt

[PDF](https://openreview.net/pdf/ef5371d1827e0373f204ddb5fc93a58becfcae1d.pdf) · [OpenReview](https://openreview.net/forum?id=U4z7qklYvw)

---

### Stabilizing In-Context Multi-Source Domain Adaptation for Biomedical Images Through Controls
*Ana Sanchez-Fernandez, Thomas Pinetz, Werner Zellinger, Günter Klambauer*

> Biomedical imaging data presents enormous potential for deep learning models to predict invaluable properties, such as diseases and drug effects. However, unavoidable alterations of the technical conditions cause *batch ...

**Keywords:** biological imaging, domain adaptation, test-time adaptation, meta-learning

[PDF](https://openreview.net/pdf/b4b2e61d04167a4b975db9468b1341d2041ac4a2.pdf) · [Code](https://github.com/ml-jku/cs-arm-bn/) · [OpenReview](https://openreview.net/forum?id=oUGeAcxuz5)

---

### Structured Multi-modal Graph Disentanglement for Psychiatric Diagnosis
*Hongyu Shi, Kaizhong Zheng, Wensheng Zhai, Shuai Jiang*

> Multi-modal neuroimaging-based psychiatric diagnosis must integrate cross-modal agreement with modality-specific complementarity, yet in real multi-site cohorts these signals are frequently entangled with site- and cohor...

**Keywords:** Graph neural networks, Representation disentanglement, Psychiatric diagnosis

[PDF](https://openreview.net/pdf/5cff07ce72569d34e74e15f60c71999899ef72df.pdf) · [OpenReview](https://openreview.net/forum?id=cX3r7kAqr1)

---

### STT-LLM: Structural-Temporal Tokenization for Adapting LLMs to Longitudinal Clinical Profiles
*Maxx Richard Rahman, Mostafa Hammouda, Wolfgang Maass*

> Large Language Models have shown strong generalization across natural language tasks but remain underexplored for longitudinal clinical profiles. In sports anti-doping, biological profiles are analyzed to support early d...

**Keywords:** LLM Tokenization, Longitudinal Clinical Profiles, Structural-Temporal Embedding, Sequence Prediction

[PDF](https://openreview.net/pdf/3932e06aaa356ed20d2d024747dad492eb99b18a.pdf) · [OpenReview](https://openreview.net/forum?id=oLtn3L43Ej)

---

### SynerMedGen: Synergizing Medical Multimodal Understanding with Generation via Task Alignment
*Weiren zhao, DONG Yi, Cheng Chen*

> Unifying multimodal understanding and generation is a compelling frontier that is beginning to emerge in the medical field. However, the limited existing unified medical models typically treat understanding and generatio...

**Keywords:** Medical Multi-Modal Image Synthesis; Multi-Modal Uderstanding and Generation; Medical Large Vision-Language Models

[PDF](https://openreview.net/pdf/b7d66c05a1eb185ba7cff5460d466d303250202c.pdf) · [Code](https://github.com/piooip/SynerMedGen) · [OpenReview](https://openreview.net/forum?id=Tyv61ZKb9s)

---

### Time-Conditioned Foreseeing: An EHR-Specific Foundation Model for Irregular Dynamics and Calendrical Time
*Bong Gyun Kang, Junyong Ahn, Hyeongrok Han, Sungroh Yoon*

> Electronic Health Records (EHRs) possess unique characteristics distinct from natural language, yet existing EHR foundation models often rely on suboptimal NLP-based approaches. We propose a pretraining method tailored t...

**Keywords:** Electronic Health Record, Temporal modeling, Generative pre-training, Irregularly sampled timestamps

[PDF](https://openreview.net/pdf/86216bfeed28703e5e97f96edb45fea5d0ecb332.pdf) · [Code](https://github.com/Pusheen-cat/TCF_PFM) · [OpenReview](https://openreview.net/forum?id=IalpB5Mzaz)

---

### Token-Sparse Medical Multimodal Reasoning via Dual-Stream Reinforcement Learning
*Kaitao Chen, Weiqian Zhao, Jiamin Wu, Qihao Zheng et al.*

> Vision-language models (VLMs) combining reinforcement learning (RL) ignite remarkable progress in multimodal reasoning, yet still struggle with medical images, which typically exhibit extremely sparse visual evidence to ...

**Keywords:** medical vision-language models, medical reasoning

[PDF](https://openreview.net/pdf/f8c38849662308b07b247bd16b0b43914f3b2e17.pdf) · [OpenReview](https://openreview.net/forum?id=elrnTLDiT3)

---

### Tri-Scale Neural ODEs for Continuous Multi-Omics Disease Modeling
*Shohaib Shaffiey, Massimiliano Pierobon*

> The fields of AI-based disease fingerprinting, drug discovery and repurposing are currently among the emerging frontiers of machine learning applied to medicine. One major challenge is to obtain robust $\textit{in-silico...

**Keywords:** Neural Ordinary Differential Equations, Tri-Scale Neural ODE, Multi-Scale Modeling, Multi-Omics

[PDF](https://openreview.net/pdf/39923d80c8a692d2e267e5e42c5f40ad88b8eb60.pdf) · [OpenReview](https://openreview.net/forum?id=PsjSZaunzO)

---

### UniMedVL: Unifying Medical Multimodal Understanding and Generation through Observation-Knowledge-Analysis
*Junzhi Ning, Wei Li, Cheng Tang, Jiashi Lin et al.*

> Medical workflows routinely combine reading images with producing visual and textual outputs, making both image understanding and generation central to medical AI. Most existing systems, however, address these abilities ...

**Keywords:** Multimodal Learning, Medical AI, Vision-Language Model, Unified Framework

[PDF](https://openreview.net/pdf/9c4b2a81fd5043023f8f018f975530e6569a7d7a.pdf) · [Code](https://github.com/uni-medical/UniMedVL) · [OpenReview](https://openreview.net/forum?id=7UR3rNXMz9)

---

### Unlocking Cross-Modal Biosignal Synthesis: A Temporally-Aware VAE-Diffusion Model
*Chenyang Xu, Dezhen Wang, Hao Wang*

> Synthesizing authentic phonocardiograms (PCG) from ubiquitous electrocardiograms (ECG) is a critical task for accessible cardiac monitoring. Existing generative models, however, struggle to capture the heart's complex el...

**Keywords:** Machine Learning, Biosignal Synthesis, VAE, Diffusion Models

[PDF](https://openreview.net/pdf/7d4562c5b583662019a57f8607043ce8c9e9eacc.pdf) · [OpenReview](https://openreview.net/forum?id=aComqAqP6j)

---

## Medical Imaging

> Radiology AI, pathology, segmentation, and imaging foundation models.

### Are We Overconfident in Models and Results for Semi-Supervised 3D Medical Image Segmentation?
*Jun Li, Ziwei Qin*

> Semi-supervised learning has become a dominant paradigm for reducing annotation costs. However, we argue that the current progress is clouded by a twofold overconfidence problem. Algorithmically, mainstream pseudo-labeli...

**Keywords:** Semi-Supervised Learning, Medical Image Segmentation, Proto Learning, Over-confidence Mitigation

[PDF](https://openreview.net/pdf/2bd73ee38a4fd11c1536a59b154275f526dc00bc.pdf) · [OpenReview](https://openreview.net/forum?id=bGxMpQsIuN)

---

### Beyond Instance-Level Self-Supervision in 3D Multi-Modal Medical Imaging
*Tan Pan, Shuhao Mei, Yixuan Sun, Kaiyu Guo et al.*

> Self-supervised pre-training methods in medical imaging typically treat each individual as an isolated instance, learning representations through augmentation-based objectives or masked reconstruction. They often do not ...

**Keywords:** medical image analysis, self-supervised learning, 3D medical imaging

[PDF](https://openreview.net/pdf/ed2540d02e3e0dba6228ee5f2c1734c695f4a00f.pdf) · [Code](https://github.com/Ashespt/TACO) · [OpenReview](https://openreview.net/forum?id=Vtps0ZUlgv)

---

### Cello: A Universal Cell-wise Feature Aggregation framework for  Reliable  Pathology Images Analysis
*Hengrui Lou, Weihan Li, Jiazhen Yang, Lingxiang Jia et al.*

> Computational pathology has made progress in diagnosis and prognosis prediction from whole slide images (WSIs), yet pipelines still rely on patch-level feature extraction and aggregation, departing from the cell-centric ...

**Keywords:** Cell-wise Feature Aggregation, Reliable Diagnosis, Computer Vision, Computational Pathology

[PDF](https://openreview.net/pdf/0fac7f88f69a8fee60081cbee4e3d07d13b48f75.pdf) · [Code](https://github.com/HengruiLou/Cello) · [OpenReview](https://openreview.net/forum?id=2qc3SXdpns)

---

### Cross-Subject Modeling for Widefield Calcium Imaging via Atlas-Aligned Spatiotemporal Tokenization
*Mohammad Hosseini, Eray Erturk, Saba Hashemi, Maryam M. Shanechi*

> Large-scale, multi-subject widefield calcium imaging provides unprecedented access to brain-wide cortical dynamics. However, the high dimensionality, complex spatiotemporal structure, and substantial task-irrelevant acti...

**Keywords:** Widefield calcium imaging, Cross-Subject modeling, Neural decoding, Tokenization

[PDF](https://openreview.net/pdf/7c117b10aacc786eb551444ecec9c51e092ee43d.pdf) · [Code](https://github.com/ShanechiLab/WiCAT) · [OpenReview](https://openreview.net/forum?id=pZq2RMptsQ)

---

### DPsurv: Dual-Prototype Evidential Fusion for Uncertainty-Aware and Interpretable Whole Slide Image Survival Prediction
*Yucheng Xing, Ling Huang, Jingying Ma, Ruping Hong et al.*

> Whole-slide images (WSIs) are widely used for cancer survival analysis because of their comprehensive histopathological information at both cellular and tissue levels, enabling quantitative, large-scale, and prognostical...

**Keywords:** Survival Analysis, Evidence Theory, Whole Slide Image, Uncertainty Quantification

[PDF](https://openreview.net/pdf/f7ff576288af888c2a3bba3875bf2bf56b896168.pdf) · [Code](https://github.com/YuchengXing99/DPsurv) · [OpenReview](https://openreview.net/forum?id=RKqL4GYXz3)

---

### EpiTwin: Spatiotemporal Graph Transformers for Epileptic sEEG Signal Reconstruction
*Jingbo Yang, Yunfeng Zhao, Chao Qiu, Yulin Sun*

> Stereotactic electroencephalography (sEEG) provides temporally precise intracranial recordings but is inherently constrained by sparse and irregular spatial sampling due to clinical limitations on electrode implantation....

**Keywords:** Stereotactic EEG, Neural signal reconstruction, Graph neural networks, Transformers

[PDF](https://openreview.net/pdf/787ac839010f9b81bf0c1fbf9188fffdfa530b8a.pdf) · [OpenReview](https://openreview.net/forum?id=wmyNZRBBKv)

---

### FACT: Fuzzy Alignment with Comorbidity Topology for Reliable Multi-Label Medical Image Diagnosis
*Yingyu Chen, Yongqiang Huang, Yang Qin, Ziyuan Yang*

> In clinical practice, patients often present with multiple co-occurring diseases, yet most existing Multi-Label-Diagnosis (MLD) methods treat diagnosis as a rigid discriminative partitioning task, implicitly assuming tha...

**Keywords:** Multi-label Diagnosis, Medical Image Analysis, Fuzzy Set Theory

[PDF](https://openreview.net/pdf/55bedb9ae52d8db157a4db466e911d89c3d6c6e4.pdf) · [Code](https://github.com/yyuChen9/FACT) · [OpenReview](https://openreview.net/forum?id=T5u3haVBgi)

---

### Federated Distillation for Whole Slide Image via Gaussian-Mixture Feature Alignment and Curriculum Integration
*Luru Jing, Cong Cong, Yanyuan Chen, Yongzhi Cao*

> Federated learning (FL) offers a promising framework for collaborative digital pathology by enabling model training across institutions. However, real-world deployments face heterogeneity arising from diverse multiple in...

**Keywords:** Federated Learning; Whole Slide Image Classification; Dataset Distillation

[PDF](https://openreview.net/pdf/e08241aa7c926c2531c67f321bbca9d6db37b3ed.pdf) · [Code](https://github.com/HuahuaCodes/FedHD-ICML2026) · [OpenReview](https://openreview.net/forum?id=GPyay3ZTrk)

---

### FlowPET: Physics-Informed Symplectic Flow Matching for Low-Count PET Reconstruction
*Zheng Zhang, Hao Tang, Yingying Hu, zhanli hu*

> Low-count Positron Emission Tomography (PET) reconstruction is severely hindered by the dissipative nature of prevailing generative models, where the inherent phase-space contraction leads to the numerical extinction (``...

**Keywords:** Medical Imaging, Positron Emission Tomography, Low-Count PET  Reconstruction

[PDF](https://openreview.net/pdf/21c4ee52ea200f85c6dd87015d8acad88571bc7a.pdf) · [OpenReview](https://openreview.net/forum?id=LnNbhU8IcR)

---

### Foundation VAE for CT Reconstruction, Augmentation, and Generation
*Qi Chen, Shuhan Ding, Yu Gu, Nan Liu*

> Variational autoencoders (VAEs) compress high resolution CT volumes into compact latents while preserving clinically relevant structure. However, training CT-specific VAEs from scratch or heavily fine-tuning them incurs ...

**Keywords:** CT Generation, CT Augmentation, CT Reconstruction, Foundation VAE

[PDF](https://openreview.net/pdf/c7fa1e0151f8b0946a175adc3d653b1ae628adfc.pdf) · [Code](https://github.com/qic999/Foundation-VAE) · [OpenReview](https://openreview.net/forum?id=f51haqkwRQ)

---

### Geometrically Constrained Stenosis Editing in Coronary Angiography via Entropic Optimal Transport
*Jialin Li, Zhuo Zhang, Cao Yue, Guipeng Lan*

> The scarcity of high-quality imaging data for coronary angiography (CAG) stenosis limits the clinical translation of automated stenosis detection. Synthetic stenosis data provides a practical avenue to augment training s...

**Keywords:** Medical image editing, Synthetic data generation, Stenosis detection, Coronary Angiography

[PDF](https://openreview.net/pdf/9ae656376203a8445512ed693ca0a26e3234fd99.pdf) · [Code](https://github.com/LiJialin001/OT-Bridge-Editor) · [OpenReview](https://openreview.net/forum?id=hZ0xrfUenD)

---

### Image-to-Brain Signal Generation for Visual Prosthesis with CLIP Guided Multimodal Diffusion Models
*Ganxi Xu, Zhao-Rong Lai, Yuting Tang, Yonghao Song*

> Visual prostheses hold great promise for restoring vision in blind individuals. While researchers have successfully utilized M/EEG signals to evoke visual perceptions during the brain decoding stage of visual prostheses,...

**Keywords:** Image-to-brain, visual prosthesis, M/EEG, diffusion transformer

[PDF](https://openreview.net/pdf/f81a9571fb3394d9a30bbd8c1d087017396b4f5f.pdf) · [OpenReview](https://openreview.net/forum?id=iPTCYxloni)

---

### Med-SegLens: Latent-Level Model Diffing for Interpretable Medical Image Segmentation
*Salma J. Ahmed, Emad Mohammed, Azam Asilian Bidgoli*

> Modern segmentation models achieve strong predictive performance but remain largely opaque, limiting our ability to diagnose failures, understand dataset shift, or intervene in a principled manner. We introduce $\textbf{...

**Keywords:** Model Diffing, Model Interpretability, Medical Image Segmentation, Dataset Shift

[PDF](https://openreview.net/pdf/443a61ca5d23ea0581d2b766afeb9f56dbc60580.pdf) · [Code](https://github.com/Salma-Jamal/Med-SegLens) · [OpenReview](https://openreview.net/forum?id=vaRFU0xKQa)

---

### MedCRP-CL: Continual Medical Image Segmentation via Bayesian Nonparametric Semantic Modality Discovery
*Ziyuan Gao*

> Medical image segmentation faces a fundamental challenge in continual learning: data arrives sequentially from heterogeneous sources, yet effective continual learning requires discovering which tasks share sufficient str...

**Keywords:** Bayesian Methods, Continual Learning, Medical Vision-Language Models

[PDF](https://openreview.net/pdf/5b28cc1d59507e3c19282b562dbc4817321b6dc5.pdf) · [Code](https://github.com/zygao930/MedCRP-CL) · [OpenReview](https://openreview.net/forum?id=v0DWbfP3b9)

---

### MolAlign3D: Enhancing Fixed-Dimensional E(3)-Equivariant Latent Space for High-Fidelity 3D Molecular Reconstruction and Editing
*Zitao Chen, Jiatong Ji, Yinjun Jia, Wei-Ying Ma*

> Recent advances in 3D molecular modeling have achieved high-fidelity structural synthesis, yet these models often lack an explicit and manipulable representation space. To address this, MolFLAE introduced a fixed-dimensi...

**Keywords:** Drug Design, Deep Learninng, Molecule Generation, Molecule Editing

[PDF](https://openreview.net/pdf/c833e17e2460624782535caed7d5bc128274e58c.pdf) · [OpenReview](https://openreview.net/forum?id=2USw3I5GiJ)

---

### On Revisiting Entropy for Identifying Mislabeled Images
*Chunlei Li, Zixuan Zheng, Yilei Shi, Guanglu Dong*

> Mislabeled samples in training datasets severely degrade the performance of deep networks, as overparameterized models tend to memorize erroneous labels. We address this challenge by proposing a novel approach for mislab...

**Keywords:** mislabeled data detection, signed entropy integral, contrastive language-image pretraining (CLIP)

[PDF](https://openreview.net/pdf/3e9b7b7bdc371d348638e9e530d14f01ee588a49.pdf) · [OpenReview](https://openreview.net/forum?id=BUxrIaf7Zc)

---

### Ophiuchus: Incentivizing Tool-augmented ''Think with Images'' for Joint Medical Segmentation, Understanding and Reasoning
*Yankai Jiang, Yujie Zhang, Peng Zhang, Wenjie Li*

> Recent medical MLLMs have made significant progress in generating step by step textual reasoning chains. However, they still struggle with complex clinical tasks that necessitate dynamic and iterative focusing on fine-gr...

**Keywords:** Medical MLLM, Medical Agent, Agentic RL

[PDF](https://openreview.net/pdf/7734e618cbf88421cfd116392ce0b24c599df296.pdf) · [Code](https://github.com/SII-zyj/Ophiuchus) · [OpenReview](https://openreview.net/forum?id=coJqVkqb03)

---

### ORBIT: A Prognostic World Model for Ocular Reasoning Based on Imagined Trajectories
*Jiangtao Yan, Yanlin Qu, Yansheng Qiu, Shujian Gao et al.*

> The longitudinal management of blinding fundus diseases constitutes a Partially Observable Markov Decision Process (POMDP) necessitating a critical precision-risk trade-off between intervention and over-treatment, as tru...

**Keywords:** World Models, Medical AI, Causal Inference, Weak Supervision

[PDF](https://openreview.net/pdf/47f1525428541fe9a2538c757317dc796bb584a7.pdf) · [OpenReview](https://openreview.net/forum?id=pd6GY2x8FG)

---

### Physiology-Aware Masked Cross-Modal Reconstruction for Biosignal Representation Learning
*Hao Zhou, Simon A. Lee, Cyrus Tanade, Keum San Chun et al.*

> Biosignals acquired from different locations on the body often provide temporally ordered views of the same underlying physiological process. However, most existing self-supervised learning methods treat these signals as...

**Keywords:** Health Applications, Self-supervised Learning, Biosignal Representation Learning, Wearables

[PDF](https://openreview.net/pdf/2b6abafb6dd234b40edc5ab5ef680b8714212215.pdf) · [Code](https://github.com/hzhou3/xMAE) · [OpenReview](https://openreview.net/forum?id=NxbSbkLNMc)

---

### Plug-and-Play Diffusion Meets ADMM: Dual-Variable Coupling for Robust Medical Image Reconstruction
*Chenhe Du, Xuanyu Tian, Qing Wu, Muyu Liu*

> Plug-and-Play diffusion prior (PnPDP) frameworks have emerged as a powerful paradigm for solving imaging inverse problems by treating pretrained generative models as modular priors. However, we identify a critical flaw i...

**Keywords:** diffusion model, inverse problem, plug-and-play, CT

[PDF](https://openreview.net/pdf/e1039de319f1723a79f31dd2f60ef47e97302882.pdf) · [Code](https://github.com/duchenhe/DC-PnPDP) · [OpenReview](https://openreview.net/forum?id=jEBkuuETjr)

---

### Reference-Free Meta-Learning for Generalized Implicit Neural Representation in Efficient MRI Reconstruction
*Haonan Zhang, Qing Wu, Xuanyu Tian, Bowen Li*

> Implicit Neural Representation (INR) has emerged as a powerful paradigm for continuous MRI reconstruction. However, standard self-supervised INR requires time-consuming optimization from scratch for each scan, hindering ...

**Keywords:** meta-learning. implicit neural representation. MRI reconstruction, reference-free

[PDF](https://openreview.net/pdf/c872dd0b83b4db488e51a1d6f3f504bb02105768.pdf) · [OpenReview](https://openreview.net/forum?id=jPVGiAUlNa)

---

### Rethinking Federated Prompt Learning for Medical Images: From Textual Tuning to Visual Manifold Anchoring
*Yipan Wei, Wenke Huang, Yapeng Li, He Li*

> Federated Prompt Learning (FPL) adapts Vision-Language Models to privacy-sensitive medical imaging, typically via a textual tuning paradigm that assumes the frozen visual encoder provides a discriminative feature geometr...

**Keywords:** Federated Learning, Prompt Learning, Vision-Language Models, Medical Image Analysis

[PDF](https://openreview.net/pdf/235823c6d304c183cc3ef95cbdc40250ed433653.pdf) · [Code](https://github.com/YipanWei/FedMAP) · [OpenReview](https://openreview.net/forum?id=3LymHCdeRd)

---

### Scaling Vision Transformers for Functional MRI with Flat Maps
*Connor Lane, Mihir Tripathy, Leema Krishna Murali, Ratna Sagari Grandhi et al.*

> We study the problem of training self-supervised foundation models for functional MRI. Our main contributions are: (1) we introduce a new model family (CortexMAE) trained using the masked autoencoder framework on 2.1K ho...

**Keywords:** self-supervised learning, foundation models, neuroscience, functional MRI

[PDF](https://openreview.net/pdf/b7dd9148b91a71badecf7d6072ff6fe908aa0e6d.pdf) · [Code](https://github.com/MedARC-AI/CortexMAE) · [OpenReview](https://openreview.net/forum?id=s8cdRWLTCc)

---

### The Double Dilemma in Multi-Task Radiology Report Generation: A Gradient Dynamics Analysis and Solution
*Erjian Zhang, Yatong Hao, Liejun Wang, Zhiqing Guo*

> While multi-task learning based automatic radiology report generation (RRG) is widely adopted to ensure clinical consistency, most focus on architectural designs yet remain limited to coarse linear scalarization strategi...

**Keywords:** Radiology Report Generation, Gradient Dynamics, Multi-Task Optimization, Medical Image Analysis

[PDF](https://openreview.net/pdf/5cfe601d3ea51995ff159ac76dfe869831f3e8bc.pdf) · [Code](https://github.com/vpsg-research/CAME-Grad) · [OpenReview](https://openreview.net/forum?id=T7y2wavrFM)

---

### Thinking in Scales: Accelerating Gigapixel Pathology Image Analysis via  Adaptive Continuous Reasoning
*Jiusong Ge, Yingkang Zhan, Wenjie Zhao, Di Zhang et al.*

> Traditional whole slide image (WSI) analysis methods typically rely on the multiple instance learning (MIL) paradigm, which extracts patch-level features at high magnification and aggregates them for slide-level predicti...

**Keywords:** Computational Pathology, Whole Slide Image Analysis, Efficient Inference

[PDF](https://openreview.net/pdf/f0a644528105d8a40c15a51e8120eaae340a2f2e.pdf) · [OpenReview](https://openreview.net/forum?id=LgFmen6sHP)

---

### Transitive Representation Learning Enhances Histopathology Annotation
*Moritz Schaefer, Zoe Piran, Nils Philipp Walter, Animesh Awasthi*

> The characterization of histopathology with AI promises to assist clinical decision-making, but it is currently limited due to coarse-grained annotations that miss cellular identities. To overcome this gap, we bridge his...

**Keywords:** Multimodal Learning, Contrastive Learning, Computational Biology, Computational Histopathology

[PDF](https://openreview.net/pdf/5633e8d66627583698d6fffa502376d7f9347d92.pdf) · [Code](https://github.com/zinagoodlab/spatialwhisperer) · [OpenReview](https://openreview.net/forum?id=Ze7U293Zw4)

---

## Neuroscience & Brain

> Neural decoding, brain imaging, BCI, and computational neuroscience.

### Learning Biophysical Models of Large-Scale Multineuronal Data To Enable Precise Neurostimulation 🌟 **Spotlight**
*Amrith Lotlikar, Ian Christopher Tanoh, Praful K. Vasireddy, Andrew Lanpouthakoun et al.*

> Multi-compartment Hodgkin–Huxley (HH) models provide a principled framework for predicting neural dynamics and responses to electrical stimulation. However, fitting HH biophysical parameters typically requires intracellu...

**Keywords:** simulation based inference, retina, neuroscience, neuroengineering

[PDF](https://openreview.net/pdf/f6ef892f96486d0a05a990b48b62bae9941de6fe.pdf) · [OpenReview](https://openreview.net/forum?id=4hoiRJsmpp)

---

### Linguistic Properties and Model Scale in Brain Encoding: From Small to Compressed Language Models 🌟 **Spotlight**
*SUBBA REDDY OOTA, Vijay Rowtula, Satya Sai Srinath Namburi GNVV, Khushbu Pahwa*

> Recent work has shown that scaling large language models (LLMs) improves their alignment with human brain activity, yet it remains unclear what drives these gains or which representational properties are responsible. Alt...

**Keywords:** brain encoding, fMRI, light weight language models, larger language models

[PDF](https://openreview.net/pdf/64bd9fcefecf680e1c2fe56567845a2a152d04a5.pdf) · [OpenReview](https://openreview.net/forum?id=WK1NvxRMsL)

---

### Mind-Omni: A Unified Multi-Task Framework for Brain-Vision-Language Modeling via Discrete Diffusion 🌟 **Spotlight**
*Yizhuo Lu, Changde Du, Qingyu Shi, Hang Chen*

> Modeling the interplay between external stimuli and internal neural representations is a pivotal research area for Brain-Computer Interfaces (BCIs). A major limitation of prior work is the prevailing paradigm of speciali...

**Keywords:** Neural signal modeling, unified multitask framework, discrete diffusion

[PDF](https://openreview.net/pdf/426378cbae09e997b188c2f3750124b7608a9421.pdf) · [Code](https://github.com/ReedOnePeck/Mind-Omni) · [OpenReview](https://openreview.net/forum?id=3gCdh3u2GK)

---

### NeuronCtrl: Geometry-Aware Safe Closed-Loop Generative Control for Neuronal Microenvironment Dynamics 🌟 **Spotlight**
*Haowei Xu, Yixin Chen, Wanyi Fu, Hongbin Han*

> Neuromodulation can be viewed as closed-loop control of high-dimensional spatiotemporal fields on irregular 3D morphologies, coupling membrane electrophysiology with ionic reaction--diffusion. This view supports high-rat...

**Keywords:** Neuromodulation, computational neuroscience, closed-loop control, biophysical simulation

[PDF](https://openreview.net/pdf/58dd8f56e9b6470f4ea8fce237ac8effa6f09ffa.pdf) · [OpenReview](https://openreview.net/forum?id=ZK3h2ENA67)

---

### PhenoBrain: Phenotype-Conditioned Long-Range Communication for Multi-Modal Brain Network Analysis 🌟 **Spotlight**
*Lingyuan Meng, KE LIANG, Hao Li, Meng Liu*

> Multi-modal brain network analysis aims to predict neuropsychiatric status from functional connectomes with heterogeneous phenotypes. However, most existing methods treat phenotypes as auxiliary features and perform late...

**Keywords:** multi-modal graph learning, brain network analysis

[PDF](https://openreview.net/pdf/ef493e72e5eb7e06a04e0c00cb8121db26dfe86c.pdf) · [OpenReview](https://openreview.net/forum?id=9NqKL9QQ4a)

---

### Real-World Unsupervised Models Generalize to Predict Brain Responses to Out-of-Distribution Stimuli 🌟 **Spotlight**
*Chenggang Chen, Zhiyu Yang, Xiaoqin Wang*

> Deep neural networks currently provide the leading quantitative models of neural responses in sensory systems. However, these networks remain implausible as models of sensory development, largely because they rely on sup...

**Keywords:** Computational Neuroscience, NeuroAI, Unsupervised Learning, Speech

[PDF](https://openreview.net/pdf/e05963b790e4684a11cc983020653225a6c36194.pdf) · [Code](https://github.com/ccg1988/ICML2026) · [OpenReview](https://openreview.net/forum?id=H1HHss5Zj4)

---

### A hitchhiker's guide to Poisson gradient estimation
*Michael Ibrahim, Hanqi Zhao, Eli Zachary Sennesh, Zhi Li*

> Poisson-distributed latent variable models are widely used in computational neuroscience, but differentiating through discrete stochastic samples remains challenging. Two approaches address this: *Exponential Arrival Tim...

**Keywords:** Poisson, Latent Variable Models, Reparameterization, Variational Auto-Encoder

[PDF](https://openreview.net/pdf/d5351f3965ddd781783ac879b814a35af073b350.pdf) · [Code](https://github.com/hadivafaii/PoissonGradientEstimation) · [OpenReview](https://openreview.net/forum?id=T4Ibp5vLpE)

---

### Abstraction Induces the Brain Alignment of Language and Speech Models
*Emily Cheng, Aditya R. Vaidya, Richard Antonello*

> Research has repeatedly demonstrated that intermediate hidden states extracted from large language models and speech audio models predict measured brain response to natural language stimuli. Yet, very little is known abo...

**Keywords:** encoding models, neuroai

[PDF](https://openreview.net/pdf/b1497ff5dc33b44e5565b73d45121bf8ae903bb0.pdf) · [OpenReview](https://openreview.net/forum?id=n5Ds4qbtjM)

---

### Adaptive Coding Emerges in Stabilized Supralinear Networks Trained with Local Plasticity
*Haoyu Albert Wang, Wei P Dai, Jialun Ma, Jiawei Zhang et al.*

> Lateral connections (LCs) are ubiquitous in the cortical circuits. While DL architectures have rich intralayer interactions to support feature selectivity and contextual modulation, explicit excitatory and inhibitory (E-...

**Keywords:** recurrent connection, lateral connection, sparse coding, population coding

[PDF](https://openreview.net/pdf/d9b85b08cc9632b11eb6f55a6e5de2dd712f1de9.pdf) · [OpenReview](https://openreview.net/forum?id=fPX6A4us61)

---

### ADHD Disease Detection Based on Short- and Long-Term Brain Function Encoding and Memory Graph Network
*Dongxun Jiang, Borui Jia, Yuxuan Wang, Dongdong Zhang*

> Graph-based attention deficit hyperactivity disorder (ADHD) detection methods have been extensively studied, but comparatively less attention has been paid to short-term brain functional reorganization. In this paper, we...

**Keywords:** Attention-Deficit/Hyperactivity Disorder, Long- and Short-Term Series, Graph Network, Brain Disease Detection

[PDF](https://openreview.net/pdf/5d709c43daa9cb279032d46063a5afef8a26a10a.pdf) · [OpenReview](https://openreview.net/forum?id=IaZmw8c9U4)

---

### Alignment between Brains and AI: Evidence for Convergent Evolution across Modalities, Scales and Training Trajectories
*Guobin Shen, Dongcheng Zhao, Yiting Dong, Qian Zhang*

> Artificial and biological systems may converge on similar computational strategies despite different architectures and learning mechanisms—a form of convergent evolution. We test this at scale by comparing internal repre...

**Keywords:** Brain Alignment, Large Language Models, NeuroAI, Representation Alignment

[PDF](https://openreview.net/pdf/26077e52c97298c7d40dcce68e0074800c48ce27.pdf) · [Code](https://github.com/FloyedShen/BrainAlign) · [OpenReview](https://openreview.net/forum?id=XrRqY9QOSa)

---

### Bio-Vision-Inspired Spiking Neural Networks for Object Detection with Event Cameras
*Dongyang Ma, Zhengyu Ma, Yifan Huang, Chenlin Zhou*

> Retina-like event cameras and brain-inspired Spiking Neural Networks (SNNs)  demonstrate exceptional energy efficiency through bio-inspired sensing and computation.  While SNNs are naturally well-suited to the asynchrono...

**Keywords:** Bio-Vision-Inspired, Brain-inspired, Event cameras, Spiking Neural Networks

[PDF](https://openreview.net/pdf/d04a3c25d48544e04f0c2d8e68d9e646b7d254b6.pdf) · [OpenReview](https://openreview.net/forum?id=MoQiswth2n)

---

### BIT-LLM: Brain Instruction Tuned LLM with persistent Cross-Attention for fMRI-to-Text Decoding
*Sunghwan Lee, Jihun Kim, Chae Lynn Kim, Ji Yun Park*

> Decoding fMRI into natural language is challenging because strong, pre-trained language priors can dominate autoregressive generation, obscuring whether a model truly utilizes neural evidence. We introduce BIT-LLM, which...

**Keywords:** Neuroscience, fMRI, Reinforcement Learning, Large Language Model

[PDF](https://openreview.net/pdf/8d421f21521afa6a237682c4b6e634277d334e04.pdf) · [OpenReview](https://openreview.net/forum?id=HZhlRnJOHq)

---

### BrainJanus: A Unified Model for Understanding and Generation across Brain, Vision, and Language
*Haitao Wu, Qirui Zhang, Zhouheng Yao, Shangquan Sun et al.*

> Modeling the bidirectional correspondence between external sensory stimuli and internal neural activity has emerged as a critical frontier in neuroscience. However, existing approaches predominantly treat brain encoding ...

**Keywords:** BCI, Brain Decoding, Brain Encoding

[PDF](https://openreview.net/pdf/d0a7245e4c5c2c2d5f4558a2ce9a2ef184f6bdf5.pdf) · [Code](https://github.com/HaitaoWuTJU/BrainJanus) · [OpenReview](https://openreview.net/forum?id=nJxailqsUW)

---

### CalM: A Self-Supervised Foundation Model for Population Dynamics in Calcium Imaging Data
*Xinhong Xu, Yimeng Zhang, Qichen Qian, Yuanlong Zhang*

> Recent work suggests that large-scale, multi-animal modeling can significantly improve neural recording analysis. However, for functional calcium traces, existing approaches remain task-specific, limiting transfer across...

**Keywords:** Neural foundation model, Neuronal Calcium trace, Self-supervised learning, Pretrain fine-tuning

[PDF](https://openreview.net/pdf/6f8d7dec4d3843818d7f925da70a48b630d45073.pdf) · [Code](https://github.com/TSuXinH/CalM) · [OpenReview](https://openreview.net/forum?id=S4pUDRolZd)

---

### Credit Assignment via Neural Manifold Noise Correlation
*Byungwoo Kang, Maceo Richards, Bernardo L. Sabatini*

> Credit assignment, the process of determining how changes in individual neurons and synapses influence a network’s output, is central to learning in brains and machines. Noise correlation-based methods, which estimate gr...

**Keywords:** biological plausible learning rules; computational neuroscience

[PDF](https://openreview.net/pdf/623feba148057be937a8aab3de0ad36946faf5ec.pdf) · [OpenReview](https://openreview.net/forum?id=RyxUQr2l4k)

---

### Dynamic Compression Flows for Neuroscience Data
*Ganchao Wei, Daniela F De Albuquerque, Miles Martinez, Shiyang Pan*

> While neuroscience experiments have repeatedly demonstrated the involvement of large populations of neurons in even simple behaviors, these studies have just as often reported that the collective dynamics of neural activ...

**Keywords:** Flow-matching, Neuroscience, Time Series, Latent Dynamics

[PDF](https://openreview.net/pdf/a72456d6a263eacfa1f56aadbe1755bd20e8802e.pdf) · [Code](https://github.com/dannyfa/Velocity_Flow_Matching/tree/cleaned) · [OpenReview](https://openreview.net/forum?id=Y86LpaxXz4)

---

### Dynamics and Representation Structure of Local Approximations to Gradient-Based Learning in Linear Recurrent Neural Networks
*Ezekiel Williams, Alexandre Payeur, Guillaume Lajoie*

> Biological and neuromorphic recurrent neural networks (RNNs) are subject to spatial and temporal locality constraints on the information that can plausibly be used during learning. A common strategy to satisfy these cons...

**Keywords:** learning dynamics, recurrent neural networks, plasticity, deep learning theory

[PDF](https://openreview.net/pdf/a431d397cb892b68e4249564f3f351cc94a96e81.pdf) · [Code](https://gitlab.com/zek3r/icml-2026) · [OpenReview](https://openreview.net/forum?id=wB4zHbCJJg)

---

### EEG-Based Multimodal Learning via Hyperbolic Mixture-of-Curvature Experts
*Runhe Zhou, Shanglin Li, Guanxiang Huang, Xinliang Zhou*

> Electroencephalography (EEG)-based multimodal learning integrates brain signals with complementary modalities to improve mental state assessment, providing great clinical potential. The effectiveness of such paradigms la...

**Keywords:** Electroencephalography, hyperbolic geometry, multimodal learning, neurotechnology

[PDF](https://openreview.net/pdf/ea752240194f22a799321a61fe59d0f28350fdf2.pdf) · [Code](https://github.com/zhourunhe/EEG-MoCE) · [OpenReview](https://openreview.net/forum?id=VSn4wLFd2p)

---

### EmBrace: A Collective Knowledge Fusion Framework Toward Unified EEG Foundation Models
*Ziyu Jia, Junyi Lin, Pu Wan, Jinxin Pi et al.*

> Electroencephalography (EEG) foundation models (EFMs) have achieved strong performance across a wide range of downstream EEG tasks via pretraining and fine-tuning. Through empirical analysis, we observe that (i) no singl...

**Keywords:** EEG, Foundation Model, Knowledge Fusion

[PDF](https://openreview.net/pdf/a1d66506a9ff2a7833c7a5d974c1a48b9a356393.pdf) · [Code](https://github.com/NeoAxiomN/EmBrace) · [OpenReview](https://openreview.net/forum?id=BJ5rYj8O8W)

---

### Fine-grained Analysis of Brain-LLM Alignment through Input Attribution
*Michela Proietti, Roberto Capobianco, Mariya Toneva*

> Understanding the alignment between large language models (LLMs) and human brain activity can reveal computational principles underlying language processing. This work describes a pipeline to apply attribution methods to...

**Keywords:** Brain alignment, Brain-LLM aligment, Input attribution, Next word prediction

[PDF](https://openreview.net/pdf/67e2f8af6c767a89c19a0cd9326998db4649c0e2.pdf) · [Code](https://github.com/bridge-ai-neuro/Brain-LLM-Alignment-Attribution) · [OpenReview](https://openreview.net/forum?id=BbxYfjeT5b)

---

### FOVI: A biologically-inspired foveated interface for deep vision models
*Nicholas Blauch, George A. Alvarez, Talia Konkle*

> Human vision is foveated, with variable resolution peaking at the center of a large field of view; this reflects an efficient trade-off for active sensing, allowing eye-movements to bring different parts of the world int...

**Keywords:** Foveation, biological inspiration, efficiency, computer vision

[PDF](https://openreview.net/pdf/d667ebd0939bb0fcdfd197b91b03fccfe1632dff.pdf) · [Code](https://github.com/nblauch/fovi) · [OpenReview](https://openreview.net/forum?id=pPfyQujFgG)

---

### From Representation to Action: A Unified Laplacian Framework for Spatial Representation and Path Planning
*Junfeng Zuo, Yuhang He, Wenhao Zhang, Fang Fang*

> Navigation in complex environments relies on internal spatial representations that guide action. While the brain employs a diverse repertoire of spatial tuning cells—including grid, place, and head-direction cells—a norm...

**Keywords:** Spatial Cognition, Path Planning, Laplacian Operator, Potential-based Navigation

[PDF](https://openreview.net/pdf/a38f2e61a1249f9b81fe01efb17f207d631862fc.pdf) · [OpenReview](https://openreview.net/forum?id=JnROrhQsyJ)

---

### Geometry-Guided Generative Representation for Functional Brain Graphs
*Subati Abulikemu, Tiago Azevedo, Michail Mamalakis, John Suckling*

> In network neuroscience, functional brain systems are often characterized using separate yet related graph-theoretic or spectral descriptors, overlooking how these properties covary and partially overlap across individua...

**Keywords:** Graph Representation Learning, Graph Transformer, fMRI, Functional Connectivity

[PDF](https://openreview.net/pdf/300a33da978ec59997300cf3a3c03fa945863bad.pdf) · [Code](https://github.com/SubatA20/geometry-guided-brain-graph-AE) · [OpenReview](https://openreview.net/forum?id=ieUVj77Hsz)

---

### Harnessing Spectrum Video for Subject-Level Few-Shot and Cross-Montage EEG Generalization
*Wei Wang, Fang He, Yifan Li, Wanying Qu*

> Existing EEG models are limited by electrode heterogeneity and rigid "channel-first" architectures that treat sensors as independent features. We propose Brain Signal Rendering (BSR), which reinterprets EEG as a physical...

**Keywords:** EEG, Brain-Computer Interface

[PDF](https://openreview.net/pdf/7a479015e0343277f4642527062f8c58588e34f4.pdf) · [OpenReview](https://openreview.net/forum?id=iCjSoADDPs)

---

### How do Humans Process AI-generated Hallucination Contents: a Neuroimaging Study
*Shuqi Zhu, Yi Zhong, Ziyi Ye, Bangde Du*

> While AI-generated hallucinations pose considerable risks, the underlying cognitive mechanisms by which humans can successfully recognize or be misled by these hallucinations remain unclear. To address this problem, this...

**Keywords:** hallucinations, brain signals, neuroscience, multimodal large language model

[PDF](https://openreview.net/pdf/c9f227918e1196b656cf29eddec5dd84d6295f44.pdf) · [OpenReview](https://openreview.net/forum?id=4S92fyThbQ)

---

### Identifying Connectivity Distributions from Neural Dynamics Using Flows
*Timothy Doyeon Kim, Ulises Pereira Obilinovic, Yiliu Wang, Eric Todd SheaBrown*

> Connectivity structure shapes neural computation, but inferring this structure from population recordings is degenerate: multiple connectivity structures can generate identical dynamics. Recent work uses low-rank recurre...

**Keywords:** computational neuroscience, low-rank recurrent neural networks, identifiability, interpretability

[PDF](https://openreview.net/pdf/cce5b104c23ec377684d9b178a2337322f58cdee.pdf) · [OpenReview](https://openreview.net/forum?id=AuiUlu3OmT)

---

### KAST-BAR: Knowledge-Anchored Semantically-Dynamic Topology Brain Autoregressive Modeling for Universal Neural Interpretation
*Haoning Wang, Wenchao Yang, Shuai Shen, Yang Li*

> While EEG foundation models have shown significant potential in universal neural decoding across tasks, their advancement remains constrained by the inadequacy modeling of *complex spatiotemporal topology*, as well as th...

**Keywords:** Electroencephalogram, brain autoregressive modeling, self-supervised learning, brain-computer interfaces

[PDF](https://openreview.net/pdf/007369c349d8375f649f19dc264fba83c9d92fe8.pdf) · [OpenReview](https://openreview.net/forum?id=Ee4j4zMir5)

---

### Learning Dynamic Stability Landscapes in Synchronization Networks
*Christian Nauck, Junyou Zhu, Michael Lindner, Frank Hellmann*

> The robustness of synchronization is typically characterized by scalar, per-node stability indices whose dependence on topology is studied via network science or graph neural networks (GNNs). We propose a novel upstream ...

**Keywords:** graph neural networks, Kuramoto oscillators, dynamical systems, basin stabilty

[PDF](https://openreview.net/pdf/b669ee079609d7ece61b5043a7fcb09ac43d28b1.pdf) · [Code](https://github.com/PIK-ICoNe/paper-companion_predicting-snbs-landscapes) · [OpenReview](https://openreview.net/forum?id=HCb1fg6Y8M)

---

### Learning Multi-Scale Hypergraph for High-Order Brain Connectivity Analysis
*Jaeyoon Sim, Soojin Hwang, Seunghun Baek, Guorong Wu*

> Understanding complex interactions between brain regions is critical for early neurodegenerative disease classification such as Alzheimer’s Disease (AD) and Parkinson’s Disease (PD). While graph-based models are widely u...

**Keywords:** Neurodegenerative Disease, Brain Network Analysis, High-Order Graph Learning

[PDF](https://openreview.net/pdf/0bf9b192177caf67c2c3c0e48f5be8290b98945b.pdf) · [OpenReview](https://openreview.net/forum?id=j5vTJrpoeL)

---

### LERD: Latent Event-Relational Dynamics for Neurodegenerative Classification
*Yicheng Feng, Hairong Chen, Ziyu Jia, Samir Bhatt*

> Alzheimer’s disease (AD) alters brain electrophysiology and disrupts multichannel EEG dynamics, making accurate and clinically useful EEG-based diagnosis increasingly important for screening and disease monitoring. Howev...

**Keywords:** Bayesian dynamical systems; latent event inference; EEG; Alzheimer’s disease; event-relational graphs; interpretable machine learning

[PDF](https://openreview.net/pdf/61f280243524d4254a13147ad5393a571663d7de.pdf) · [OpenReview](https://openreview.net/forum?id=B5DAV1EA8Z)

---

### Let EEG Models Learn EEG
*Yifan Wang, Yijia Ma, Wen Li, Chenyu You*

> High-fidelity EEG generation is critical for alleviating data scarcity and addressing privacy constraints in large-scale neural modeling. Despite recent progress, most existing approaches formulate EEG generation via dis...

**Keywords:** EEG generation

[PDF](https://openreview.net/pdf/a27d5ad89bf86c7b8d0fc2530ec52ddfd9adae9d.pdf) · [OpenReview](https://openreview.net/forum?id=TP8OuKKmsf)

---

### MEG-XL: Data-Efficient Brain-to-Text via Long-Context Pre-Training
*Dulhan Jayalath, Oiwi Parker Jones*

> Clinical brain-to-text interfaces are designed for paralysed patients who cannot provide extensive training recordings. Pre-training improves data-efficient generalisation by learning statistical priors across subjects, ...

**Keywords:** brain-computer interfaces, speech decoding, self-supervised learning

[PDF](https://openreview.net/pdf/e4c0407dac6d92faca863a0400ab8ea4f5e55408.pdf) · [Code](https://github.com/neural-processing-lab/MEG-XL) · [OpenReview](https://openreview.net/forum?id=cefix4VmhS)

---

### Mind the State: Towards Unified, Context-Aware EEG-to-fMRI Synthesis
*Yamin Li, Shiyu Wang, Chang Li, Ange Lou et al.*

> Functional magnetic resonance imaging (fMRI) provides dynamic measurements of human brain activity at high spatial resolution and depth, but its use is constrained by high cost, limited accessibility, and strict acquisit...

**Keywords:** EEG, fMRI, EEG-to-fMRI synthesis

[PDF](https://openreview.net/pdf/51c260705917c53931e52f3d6228720ce859770e.pdf) · [OpenReview](https://openreview.net/forum?id=Kw1Z8gOTvk)

---

### Multi-Integration of Labels Across Categories for Component Identification in Multi-trial Time Series
*Noga Mudrik, Yuxi Chen, Gal Mishne, Adam Shabti Charles*

> Many fields collect large-scale temporal data through repeated measurements (`trials’), where each trial is labeled with a set of metadata variables spanning several categories. For example, a trial in a neuroscience stu...

**Keywords:** multi-trial data, multi-label analysis, component identification, matrix factorization

[PDF](https://openreview.net/pdf/bbcf0f2bbe0b4c3482dd2bae9a8774ae2f9ccc3e.pdf) · [Code](https://github.com/NogaMudrik/MILCCI) · [OpenReview](https://openreview.net/forum?id=3LA6VvtC22)

---

### Multimodal Scaling Laws for Task & Data-Optimized Models of Visual Cortex
*Abdulkadir Gokce, Yingtian Tang, Martin Schrimpf*

> Task-optimized neural networks are the leading in-silico models of sensory cortex, yet the field lacks a unified understanding of which modeling choices drive improved brain alignment. Prior NeuroAI work is fragmented ac...

**Keywords:** NeuroAI, scaling laws, computational neuroscience, brain alignment

[PDF](https://openreview.net/pdf/9f64f02234454460ff0af7966baf9e451733c51b.pdf) · [Code](https://github.com/epflneuroailab/multimodal-brain-scaling) · [OpenReview](https://openreview.net/forum?id=OQ6jQHJPTT)

---

### NeurIPS: Neuro-anatomical Inductive Priors for Sphere-based Brain Decoding
*Sijin Yu, Zijiao Chen, Zhenyu Yang, Zihao Tan et al.*

> Current fMRI decoders face a performance-fidelity trade-off where efficient ID encoders outperform geometrically faithful surface-based models. We argue this is partly driven by inefficient surface tokenization and the f...

**Keywords:** Brain Decoding, MoE, Spherical Convolutions

[PDF](https://openreview.net/pdf/55dff9bcd050fbfbeccaf4d27c6325073bbfe34f.pdf) · [Code](https://github.com/SCUT-Xinlab/NeurIPS) · [OpenReview](https://openreview.net/forum?id=gXTtBRI1yj)

---

### NeuroCLUS: A Foundation Model with Functional Clustering for Intracranial Neural Decoding
*Hui Zheng, Haiteng Wang*

> Foundation models for intracranial neural recordings aim to learn generalizable representations from large-scale unlabeled data. However, existing approaches rely on suboptimal tokenization schemes -- treating individual...

**Keywords:** iEEG, neural decoding, channel cluster, foundation model

[PDF](https://openreview.net/pdf/9d418bbd5551f57401efb1ba8f497687a0e33525.pdf) · [OpenReview](https://openreview.net/forum?id=pFweJM4Uw8)

---

### Omni-fMRI: A Universal Atlas-Free fMRI Foundation Model
*Mo Wang, Wenhao Ye, Junfeng Xia, Junxiang Zhang et al.*

> Self-supervised fMRI foundation models have shown promising transfer performance, yet most rely on predefined region-level parcellations that discard fine-grained voxel information and introduce atlas-dependent biases. W...

**Keywords:** fMRI, foundation model, voxel-level, atlas-free

[PDF](https://openreview.net/pdf/d264d438c664191e0215eef5b9b2ca30150660ba.pdf) · [OpenReview](https://openreview.net/forum?id=Rc8th2rXXe)

---

### On the Infinite Width and Depth Limits of Predictive Coding Networks
*Francesco Innocenti, El Mehdi Achour, Rafal Bogacz*

> Predictive coding (PC) is a biologically plausible alternative to standard backpropagation (BP) that minimises an energy function with respect to network activities before updating weights. Recent work has improved the t...

**Keywords:** predictive coding, backpropagation, local learning, infinite width

[PDF](https://openreview.net/pdf/faf19675c4e33c5ef6f4300c5961317bb711a336.pdf) · [Code](https://github.com/thebuckleylab/jpc/tree/main/experiments/limits_paper) · [OpenReview](https://openreview.net/forum?id=ADUGteohC7)

---

### On the Spectral Unreachability of Brain Graph Learning
*Jiaming Zhuo, Shuai Zhai, Ziyi Ma, Kun Fu et al.*

> Brain network classification is pivotal for diagnosing neurological disorders, yet identifying interpretable functional biomarkers fundamentally relies on precise parcellation. Unfortunately, conventional deep graph enco...

**Keywords:** Graph Neural Networks, Graph Transformers, Brain Network

[PDF](https://openreview.net/pdf/aa0ae6b4a8709fef8b55f89ae71b067547c19098.pdf) · [OpenReview](https://openreview.net/forum?id=n3ilFhSRIx)

---

### PATCHCODE: Discrete Latent Predictive Learning for EEG Foundation Model
*KIEREN YU, Ziyang LIU, Chang Huang, Kaishun Wu*

> EEG foundation models aim to learn transferable representations, yet EEG recordings are dominated by high-frequency noise and large cross-subject variability. Existing pretraining strategies such as masked autoencoding o...

**Keywords:** EEG;Foundation Model;JEPA;BCI

[PDF](https://openreview.net/pdf/da1db2af1fb17b9b75f284a3b9d2ffe9f19e5f35.pdf) · [Code](https://github.com/kierenyyu/Patchcode) · [OpenReview](https://openreview.net/forum?id=NWcZ5vualM)

---

### PCRNet: Phase-aware Complex Refinement Network for EEG-based Auditory Attention Decoding
*Xiran Chen, Xiaoke Yang, Jian Zhou, Zhao Lv*

> Auditory attention decoding (AAD) based on Electroencephalography (EEG) aims to identify the attended speaker in multi-speaker environments. However, existing methods typically overlook the crucial phase information of E...

**Keywords:** EEG, Auditory Attention Detection, Brain-Computer Interface, Deep Learning

[PDF](https://openreview.net/pdf/a7e7895f3a0e532a3ecb4ee5cd0cf84dbeefd93d.pdf) · [Code](https://github.com/SunshineGreeny/PCRNet) · [OpenReview](https://openreview.net/forum?id=89MeH5Ax8r)

---

### Physiology as Language: Translating Respiration to EEG during Sleep
*Kaiwen Zha, Chao Li, Hao He, Peng Cao et al.*

> This paper introduces a novel cross-physiology translation task: synthesizing sleep electroencephalography (EEG) from respiration signals. To address the significant complexity gap between the two modalities, we propose ...

**Keywords:** Cross-Physiology Translation, Sleep EEG Synthesis

[PDF](https://openreview.net/pdf/65ebc36f253e9fad659b3141faa817db81eea9e6.pdf) · [OpenReview](https://openreview.net/forum?id=ceErPsyO38)

---

### ROAMM: A Benchmark Dataset for Multimodal Human Attention Decoding and EEG-to-Text Modeling During Naturalistic Reading
*Haorui Sun, Ardyn Vivienne Olszko, Niharika Singh, David C. Jangraw*

> We present Reading Observed At Mindless Moments (ROAMM), a multimodal dataset comprising 50 hours of simultaneous EEG and eye-tracking recordings collected during naturalistic multi-page reading from 44 participants. ROA...

**Keywords:** benchmark dataset, EEG, eye-tracking, mind-wandering

[PDF](https://openreview.net/pdf/ada458fb948b8a9ba69f454949f412d6cb1ebbe7.pdf) · [OpenReview](https://openreview.net/forum?id=zqLPdt09fE)

---

### See the Emotion: A Facial Emoji Proxy Modeling for EEG Emotion Recognition
*Jingjing Hu, Dan Guo, Haofan Cheng, Zeng ying*

> Despite the high accuracy of EEG-based emotion recognition, existing models remain opaque "black boxes", lacking semantic grounding between abstract neural features and human-interpretable states. In this paper, we refra...

**Keywords:** EEG-based Emotion Recognition; Facial Emoji Proxy Modeling; interpretable EEG-based emotion decoding

[PDF](https://openreview.net/pdf/590b84e713e8b5339dc9f215b01d26f5560ec0a4.pdf) · [OpenReview](https://openreview.net/forum?id=AdTBZw18aH)

---

### SI-IGCL: Subject Invariance-aware Inverse Graph Contrastive Learning for Psychiatric Disorder Identification
*Jiayu Lu, Yujin Wang, Xiaofeng Liu, Dandan Li*

> Functional brain network analysis plays an important role in understanding and diagnosing psychiatric disorders. However, current methods struggle with subject variations, impairing the model’s generalization ability to ...

**Keywords:** brain network, psychiatric disorder classification, contrastive learning

[PDF](https://openreview.net/pdf/477ee290d419c7a99a3a6b8743ec8ceb35d749d2.pdf) · [OpenReview](https://openreview.net/forum?id=ZoYQxFtDVM)

---

### Spik4lite: Refactoring Neuromorphic Sparsity for Efficient Spiking Neural Networks on Commodity Edge Devices
*Yongzhi She, Qihua Zhou, Yuhao Wang, Yaodong Huang*

> Recently, the spiking neural networks (SNNs) have shown great promise in enhancing AI task performance by utilizing the brain-inspired and energy-efficient computational paradigm via the binary (0/1) spikes. Modern SNNs,...

**Keywords:** Spiking Neural Network, Edge Intelligence

[PDF](https://openreview.net/pdf/b2695c2d9782d84af09e7d5865b5f20b8a2660c2.pdf) · [Code](https://github.com/yongzhishe/Spik4lite) · [OpenReview](https://openreview.net/forum?id=WRP7d18h9t)

---

### Structure Abstraction and Generalization in a Hippocampal-Entorhinal Inspired World Model
*Tianqiu Zhang, Muyang Lyu, Xiao Liu, Si Wu*

> Humans abstract experiences into structured representations to facilitate pattern inference and knowledge transfer. While the hippocampal-entorhinal (HPC-MEC) circuit is known to represent both spatial and conceptual spa...

**Keywords:** structure abstraction, brain-inspired AI, hippocampal-entorhinal coupling, world model

[PDF](https://openreview.net/pdf/9f1f805b9f6c66b338094e85433e74e0d47c4987.pdf) · [Code](https://github.com/senngadaisuki/hpc-mec-worldmodel) · [OpenReview](https://openreview.net/forum?id=AYXgo5FjYz)

---

### Torus Graphs for Large Scale Neural Phase Analysis
*Jack Goffinet, Casey Hanks, David Carlson*

> Oscillatory neural signals such as electroencephalography (EEG) and local field potentials (LFPs) show phase relationships that coordinate communication across brain regions. Modern recordings capture hundreds of channel...

**Keywords:** torus graphs, score matching, circular statistics

[PDF](https://openreview.net/pdf/f7e2eb1399c939df6d90ec4d5999286254db5001.pdf) · [Code](https://github.com/jackgoffinet/torus-graphs) · [OpenReview](https://openreview.net/forum?id=kq22pSSKwA)

---

### Ubiquity of Emergent Hebbian Dynamics in Regularized Learning
*David Aaron Koplow, Tomaso Poggio, Liu Ziyin*

> Hebbian and anti-Hebbian plasticity are widely observed in the brain and are classically modeled as mechanistic, local homosynaptic rules stabilized by homeostatic constraints. This raises an identifiability question: do...

**Keywords:** Hebbian Learning, Neuroscience, Regularization

[PDF](https://openreview.net/pdf/87c4ad80a8e7b5dc2b5f8682ba71e3389a2d9cd2.pdf) · [OpenReview](https://openreview.net/forum?id=fSRmJOzMA1)

---

### Uncovering Latent Communication Patterns in Brain Networks via Adaptive Flow Routing
*Tianhao Huang, Guanghui Min, Zhenyu Lei, Aiying Zhang*

> Unraveling how macroscopic cognitive phenotypes emerge from microscopic neuronal connectivity remains one of the core pursuits of neuroscience. To this end, researchers typically leverage multi-modal information from str...

**Keywords:** Neuroscience, Graph Neural Networks, Brain Network, Brain Disease Diagnosis

[PDF](https://openreview.net/pdf/e553936bad6e2876166104f5620d8b67592b49cc.pdf) · [OpenReview](https://openreview.net/forum?id=clFn9vQ8cK)

---

### ViEEG: Hierarchical Visual Neural Representation for EEG Brain Decoding
*Minxu Liu, Donghai Guan, Chuhang Zheng, Chunwei Tian*

> Understanding and decoding brain activity into visual representations is a fundamental challenge at the intersection of neuroscience and artificial intelligence. While electroencephalogram (EEG) visual decoding has shown...

**Keywords:** Brain-Computer Interfaces, Electroencephalogram, Neural Representation Learning, Cross-modal Alignment

[PDF](https://openreview.net/pdf/6cc1ca714b70889700eadd325b51f651d9b8c40a.pdf) · [Code](https://github.com/LauMason/ViEEG) · [OpenReview](https://openreview.net/forum?id=DkK7GUr8n3)

---

## Immunology & Microbiology

> Immune response modeling, antibody design, and microbial genomics.

### Constrained hybrid modelling to predict microbial dynamics and organic matter turnover in soil systems
*Paul Collart, Juergen Gall, Andrea Schnepf, Holger Pagel*

> Soil microorganisms control organic matter cycling and largely determine how soil systems can cope with and mitigate climate change and environmental threats. Representing microbial dynamics in process-based soil models ...

**Keywords:** Hybrid modelling, Soil science, Carbon cycling

[PDF](https://openreview.net/pdf/fb6990b947b2ee949eb050563f59f3a8f62f8d86.pdf) · [Code](https://jugit.fz-juelich.de/p.collart/hysomi_publication/) · [OpenReview](https://openreview.net/forum?id=UR1yz4AMYj)

---

### DecoderTCR: Compositional Pretraining and Entropy-Guided Decoding for TCR-pMHC Interactions
*Boqiao Lai, Melissa Englund, Ramit Bharanikumar, Isabel Nocedal*

> Modeling recognition between T-cell receptors (TCRs) and peptide-MHC (pMHC) complexes is a fundamental challenge in computational immunology, constrained by sparse paired interaction data relative to abundant unpaired se...

**Keywords:** Protein Language Models, Immunology, Continual Pre-training, Non-Autoregressive Decoding

[PDF](https://openreview.net/pdf/a61ccc1b469c7c29f9dc33219434efe86ef6a728.pdf) · [OpenReview](https://openreview.net/forum?id=yzes8qBM70)

---

## Oncology

> Cancer genomics, tumor microenvironment, and oncology AI.

### TwinWeaver: An LLM-Based Foundation Model Framework for Pan-Cancer Digital Twins
*Nikita Makarov, Maria Bordukova, Lena Voith von Voithenberg, Estrella Pivel-Villanueva et al.*

> Precision oncology requires forecasting clinical events and trajectories, yet modeling sparse, multi-modal clinical time series remains a critical challenge. We introduce TwinWeaver, an open-source framework that seriali...

**Keywords:** electronic health records, EHR, real-world data, large language models

[PDF](https://openreview.net/pdf/65b4696d6b6281f8f30792939f0ec6630123ae98.pdf) · [Code](https://github.com/MendenLab/TwinWeaver/) · [OpenReview](https://openreview.net/forum?id=oWqRhYpJb6)

---

## Structural Biology & MD Simulation

> Molecular dynamics, protein-ligand interactions, and structural bioinformatics.

### Autoregressive Boltzmann Generators 🌟 **Spotlight**
*Danyal Rehman, Charlie B. Tan, Yoshua Bengio, Joey Bose*

> Efficient sampling of molecular systems at thermodynamic equilibrium is a hallmark challenge in statistical physics. This challenge has driven the development of Boltzmann Generators (BGs), which allow rapid generation o...

**Keywords:** Boltzmann Generators, AI for Science, Molecules, Peptides

[PDF](https://openreview.net/pdf/1e84b2847bc0607ee39a974ea16724fde61c6e0b.pdf) · [OpenReview](https://openreview.net/forum?id=75AYDsndHP)

---

### CARD: Coarse-to-fine Autoregressive Modeling with Radix-based Decomposition for Transferable Free Energy Estimation
*Ziyang Yu, Yi He, Wenbing Huang, Wen Yan*

> Estimating free energy differences quantifies thermodynamic preferences in molecular interactions, which is central to chemistry and drug discovery. Despite fruitful progress, existing methods still face key limitations:...

**Keywords:** exact free energy estimation, coarse-to-fine modeling, radix-based decomposition, autoregressive model

[PDF](https://openreview.net/pdf/dc049f424e5cee2b9ed2de8dba6c29411bb6375a.pdf) · [Code](https://github.com/bytedance/CARD) · [OpenReview](https://openreview.net/forum?id=Kdc1UvnMKk)

---

### Coarse-Grained Boltzmann Generators
*Weilong Chen, Bojun Zhao, Jan Eckwert, Julija Zavadlav*

> Sampling equilibrium molecular configurations from the Boltzmann distribution is a longstanding challenge. Boltzmann Generators (BGs) address this by combining exact-likelihood generative models with importance sampling,...

**Keywords:** Boltzmann Generators, Molecular Dynamics, Coarse-Graining, Machine Learning Potentials

[PDF](https://openreview.net/pdf/73077e4d48e3bc92940d05d02634d4a58f5efb5b.pdf) · [Code](https://github.com/tummfm/cg-bg) · [OpenReview](https://openreview.net/forum?id=EsB46shM3U)

---

### Efficient Prediction of SO(3)-Equivariant Hamiltonian Matrices via SO(2) Local Frames
*Haiyang Yu, Yuchao Lin, Xuan Zhang, Xiaofeng Qian*

> We consider the task of predicting Hamiltonian matrices to accelerate electronic structure calculations, which plays an important role in physics, chemistry, and materials science. Motivated by the inherent relationship ...

**Keywords:** Density Functional Theory; AI for Science; Electronic Structure

[PDF](https://openreview.net/pdf/790f4bbe88e0d89dbdeff6664d654c0ee0b66bfa.pdf) · [Code](https://github.com/divelab/AIRS/) · [OpenReview](https://openreview.net/forum?id=f9i6VLHT5v)

---

### Elign: Equivariant Diffusion Model Alignment from Foundational Machine Learned Force Fields
*Yunyang Li, Lin Huang, Luojia Xia, Wenhe Zhang*

> Generative models for 3D molecular conformations must respect Euclidean symmetries and concentrate probability mass on thermodynamically favorable, mechanically stable structures. However, E(3)-equivariant diffusion mode...

**Keywords:** Machine learning force field, equivariant diffusion model

[PDF](https://openreview.net/pdf/758041a25e99aaad6fc1d3c8456098d9cb15ae43.pdf) · [Code](https://github. com/gersteinlab/elign) · [OpenReview](https://openreview.net/forum?id=7u1EZZcwqX)

---

### From Evaluation to Design: Using Potential Energy Surface Smoothness Metrics to Guide ML Interatomic Potential Architectures
*Ryan Liu, Eric Qu, Tobias Kreiman, Samuel M Blau*

> Machine Learning Interatomic Potentials (MLIPs) sometimes fail to reproduce the physical smoothness of the quantum potential energy surface (PES), leading to erroneous behavior in downstream simulations that standard ene...

**Keywords:** Machine Learning Interatomic Potential, Physical Soundness, Potential Energy Surface, Smoothness

[PDF](https://openreview.net/pdf/362bd43872cd2ff549cbded8dbf252e49ca6320c.pdf) · [Code](https://github.com/ryanliu30/bsct.git) · [OpenReview](https://openreview.net/forum?id=554mOD1mDp)

---

### GFFMERGE: Efficient Merging of Graph Neural Force Fields and Beyond
*Parth Verma, Parv Pratap Singh, Vipul Garg, Ishita Thakre*

> Graph Neural Networks (GNNs) have revolutionized Neural Force Fields for atomistic simulations, achieving near-quantum accuracy at reduced cost, yet adapting these models to new chemical systems requires expensive retrai...

**Keywords:** Graph Neural Networks, Force Fields, Model Merging, Foundation Models

[PDF](https://openreview.net/pdf/f7ea3dea5bbe2248258b244d0dcbabf2d057b14f.pdf) · [Code](https://github.com/idea-iitd/GFFMerge) · [OpenReview](https://openreview.net/forum?id=4L8bHiw2Jm)

---

### MOES-Pred: Molecular Structural Representation Learning by  Adaptive Energy-Sentinel Vibration for Generalized Property Prediction
*Zhiran Hou, Tinghuai Ma, Huan Rong, Li Jia*

> Predicting molecular properties from three-dimensional structures is fundamentally hindered by limited labeled data. While researchers have adapted self-supervised pre-training techniques from computer vision and natural...

**Keywords:** Self-supervised Learning, Denoising Pre-training, Adaptive Energy-Sentinel, Molecular Property Prediction

[PDF](https://openreview.net/pdf/8dbcc1436039d1497380a4bdbc3c423a96a79e03.pdf) · [OpenReview](https://openreview.net/forum?id=uHxt1ZRPLJ)

---

### Smooth Dynamic Cutoffs for Machine Learning Interatomic Potentials
*Kevin Han, Haolin Cong, Bowen Deng, Amir Barati Farimani*

> Machine learning interatomic potentials (MLIPs) have proven to be wildly useful for molecular dynamics simulations, powering countless drug and materials discovery applications. However, MLIPs face two primary bottleneck...

**Keywords:** machine learning interatomic potential, atomistic simulation, large scale molecular dynamics

[PDF](https://openreview.net/pdf/2fdbbd6b2a4b418bbead8fae1931b219fcf3f9de.pdf) · [Code](https://github.com/AegisIK/smooth-dynamic-cutoff) · [OpenReview](https://openreview.net/forum?id=BCVB3TFpk5)

---

## Data

All papers in [`papers.json`](papers.json):

| Field | Description |
|-------|-------------|
| `id` | OpenReview paper ID |
| `title` | Title |
| `authors` | Authors list |
| `abstract` | Abstract |
| `tags` | Category tags |
| `keywords` | Keywords |
| `spotlight` | Whether it is a Spotlight paper |
| `pdf` | PDF link |
| `code` | Code repository |
| `forum` | OpenReview forum link |

---

*Curated by [BioTender](https://www.biotender.online)*