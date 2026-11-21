### Muhammad Ahmed Mushtaq

Doctoral candidate in Biotechnology and DAAD fellow at the Brandenburg University of Technology (BTU) Cottbus–Senftenberg, Fachgebiet Multiparameterdiagnostik.

#### Research

My doctoral research examines the alpha-hemolysin of *Escherichia coli* and its role in pathogenesis. I combine experimental microbiology (cytotoxicity assays on five cell lines, *hlyA* knockout and complementation, RT-qPCR and long-read sequencing) with computational biology. I also design and carry out the bioinformatic and biostatistical analyses of our research group, which span bacterial genomics, metagenomics and machine-learning-based functional annotation. In independent projects I apply the same principles of reproducible analysis to transcriptomic, proteomic and single-cell data from human disease cohorts.

#### Large-scale and high-performance computing

- **NHR@ZIB compute-time grant** on the national supercomputer *Lise* (Zuse Institute Berlin) for the project “Global population structure and evolution of typical and atypical enteropathogenic *E. coli* (EPEC)”. Within our research group I am responsible for the computationally intensive analyses, which I plan, run and maintain on this allocation.
- **Scalable pipelines.** On *Lise* I build and run Slurm-scheduled pipelines that extend these analyses to tens of thousands of bacterial genomes for population-structure and phylogenomic studies.
- **Data at scale.** A comparative genomics database of more than 9,000 NCBI strains for machine-learning-based functional annotation; 359,889 single cells from two independent pulmonary fibrosis cohorts; five matched data layers (transcriptome, proteome, somatic mutations, copy number and survival) for 136 pancreatic tumours and 9,254 genes.

#### Selected projects

- [PDAC-RNA-Protein-Concordance](https://github.com/AhmedI0/PDAC-RNA-Protein-Concordance): mRNA–protein agreement, molecular subtypes and survival in the CPTAC-3 pancreatic cancer cohort. Python clients for the NCI GDC REST and PDC GraphQL APIs, an SQLite sample database, R/Bioconductor statistics, and pytest and testthat suites.
- [ScRNA](https://github.com/AhmedI0/ScRNA): single-cell atlas of idiopathic pulmonary fibrosis (132,455 cells, 30 donors) with independent replication in 227,434 cells, packaged as a tested Python library with executed notebooks.

#### Publications

*Published*

1. **Mushtaq MA**, Schierack P, Yousaf M, Fatima F, Qamar T, Mohsin M, Khan MM (2026). Integrated poultry production as a reservoir of *tet*(X4) and *mcr-1.1* encoding *Escherichia coli* in Pakistan. *Microbial Genomics* 12(8). [doi:10.1099/mgen.0.001800](https://doi.org/10.1099/mgen.0.001800)
2. Khan MM, **Mushtaq MA**, Suleman M, Ahmed U, Ashraf MF, Aslam R, Mohsin M, Rödiger S, Sarwar Y, Schierack P, Ali A (2025). Fecal microbiota landscape of commercial poultry farms in Faisalabad, Pakistan: a 16S rRNA gene-based metagenomics study. *Poultry Science* 104(6), 105089. [doi:10.1016/j.psj.2025.105089](https://doi.org/10.1016/j.psj.2025.105089)
3. Abdullah S, **Mushtaq MA**, Ullah K, Hassan B, Azam M, Zahoor MA, Wang J, Xu J, Toleman MA, Mohsin M (2025). Dissemination of clinical *Escherichia coli* harboring the *mcr-1* gene in Pakistan. *Frontiers in Microbiology* 15. [doi:10.3389/fmicb.2024.1502528](https://doi.org/10.3389/fmicb.2024.1502528)
4. Khan MM, **Mushtaq MA**, Abbas N, Fatima F, Gibbon MJ, Schierack P, Mohsin M (2024). Occurrence, antimicrobial resistance and genomic features of *Klebsiella pneumoniae* from broiler chicken in Faisalabad, Pakistan. *Frontiers in Veterinary Science* 11. [doi:10.3389/fvets.2024.1433124](https://doi.org/10.3389/fvets.2024.1433124)
5. Abdullah S, Almusallam A, Li M, Mahmood MS, **Mushtaq MA**, Eltai NO, Toleman MA, Mohsin M (2023). Whole genome-based genetic insights of *bla*<sub>NDM</sub> producing clinical *E. coli* isolates in hospital settings of Pakistan. *Microbiology Spectrum* 11(5). [doi:10.1128/spectrum.00584-23](https://doi.org/10.1128/spectrum.00584-23)
6. Rafiq A, Zahra T, Ali S, Shahid A, Iqbal M, Ijaz A, **Mushtaq MA** (2021). A review on different diseases due to human gut microbiota dysbiosis. 19(1), 1–10.

*Under review*

7. Dong L, Farooq W, Zhou Y, Cui R, **Mushtaq MA**, Liu Q, Aslam HM, Wu C. CD40-overexpressed mesenchymal stem cells enhance macrophage-mediated control of *Mycobacterium tuberculosis*. Submitted to *Archives of Microbiology*.

*Conference talk:* oral presentation of the doctoral study at the 78th Annual Conference of the German Society for Hygiene and Microbiology (DGHM), Hamburg, September 2026.

#### Training and course certificates in high-performance computing and AI

- Practical: High-Performance Computing System Administration, GWDG Göttingen (19–23 October 2026)
- Getting Started with the AI Training Platform (Slurm, JupyterHPC, KISSKI), GWDG (November 2026)
- Deep Learning Bootcamp: Building and Deploying AI Models (PyTorch, TensorFlow, Gradio), GWDG (March and July 2026)
- Debugging Scientific Applications (GDB, Valgrind, Slurm, remote debugging), GWDG (May 2026)
- Quantum Computing with Simulators on HPC (JupyterHPC, containers), GWDG (April 2026)
- Supercomputing for Every Scientist (SSH, Slurm, Spack, module system), GWDG (March 2026)
- System Administration for HPC (18 hours), BioNT (October 2025)

#### Methods and tools

- **Languages:** Python, R/Bioconductor, SQL, Bash, C/OpenMP (basic)
- **Genomics and metagenomics:** SPAdes, Flye, Medaka, Bakta, MOB-suite, geNomad, PPanGGOLiN, IQ-TREE; shotgun and 16S rRNA metagenomics
- **Transcriptomics, proteomics and single-cell analysis:** Scanpy, scvi-tools, CellRank 2, LIANA+, pySCENIC, DESeq2, edgeR, limma, fgsea, GSVA
- **Statistics and machine learning:** survival analysis and Cox models, elastic net, XGBoost, PyTorch, TensorFlow
- **Infrastructure and software practice:** Linux, Slurm, Snakemake, conda/mamba, renv, Git, pytest, testthat; NHR@ZIB *Lise*
