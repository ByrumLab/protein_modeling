Welcome to the Protein Modeling Tutorial Git repository! Here you will find valuable information on computational methods for Protein Structure Prediction. Below are some key methods and tools discussed in this tutorial:

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
