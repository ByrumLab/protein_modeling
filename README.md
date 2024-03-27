Welcome to the Protein Modeling Tutorial Git repository! Here you will find valuable information on computational methods for Protein Structure Prediction. 

Traditionally, proteins were studied individually by identifying and cloning their coding sequences into expression vectors for biochemical experiments or structural analysis. However, with advancements in sequencing technology in the early 1980s, the focus shifted towards studying entire sets of proteins within organisms. The RCSB Protein Data Bank (PDB) serves as a valuable resource for biological macromolecular structures, offering tools to understand the relationship between sequence, structure, and function.

When encountering a protein structure model for the first time, the complexity of thousands or even hundreds of thousands of atoms may seem overwhelming. To simplify this, a hierarchical description of protein structure is commonly used, consisting of primary, secondary, tertiary, and quaternary levels. Additionally, super secondary structures and domains are included between the secondary and tertiary levels to provide a more detailed organization of protein structures. This hierarchical approach aids in deciphering patterns within protein structures and understanding their functional significance.

As of February 7, 2006, the RCSB/PDB contained 35,026 structures, with 33,429 being proteins, including those in complexes with nucleic acids while the updated data is shown in figure 1 below. 
![Alt text](https://github.com/kalyanidhusia/protein_modeling/blob/main/Figure_1.png)



Below are some key methods and tools discussed in this tutorial:

## Computational Methods for Protein Structure Prediction

1. **Homology or Comparative Modeling**
- Approximates the 3D structure of a target protein using an empirical 3D template structure with >30% sequence identity.

2. **Fold Recognition or Threading Methods**
- Evaluates how well the amino acid sequence of a protein fits into known 3D protein structures using inter-residue potentials of mean force or statistical parameters.

3. **Ab Initio Methods (Modeller, I-tessar)**
- Utilizes knowledge-based information to predict 3D structures of protein sequences without using template structures. Successful cases are typically observed in small proteins with length below 100 residues.

4. **Ab Initio Methods without Knowledge-based Information (AlphaFold2)**
- AlphaFold2, developed by DeepMind, is a machine-learning based model that won the championship in the 14th Critical Assessment of Structure Prediction (CASP14). It represents a significant advance in protein structure prediction.

## Model Validation

- Every homology model contains errors due to factors such as % sequence identity between reference and model. It is essential to validate the correctness of the overall fold/structure, errors in localized regions, and stereochemical parameters.

## Protein Related Conda Tools

### Checklist:
- [x] Install Cath tools: `conda install bioconda::cath-tools`
- [x] Install ProDy for protein structure, dynamics, and sequence analysis: `conda install prody` or `mamba install prody`
- [x] Install Mustang for structural alignment of multiple protein structures: `conda install bioconda::mustang`
- [ ] _will add more_

For more detailed information and resources, please refer to the provided notebooks and documentation. 
Happy modeling!
