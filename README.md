# protein_modeling

#Introduction to protein structures



#Protein structure prediction

*	Homology or Comparative Modeling

Comparative ("homology") modeling approximates the 3D structure of a target protein for which only the sequence is available, provided an empirical 3D "template" structure is available with >30% sequence identity.

*	Fold Recognition or threading Methods

In fold recognition by threading one takes the amino acid sequence of a protein and evaluates how well it fits into one of the known three-dimensional (3D) protein structures. The quality of sequence-structure fit is typically evaluated using inter-residue potentials of mean force or other statistical parameters.

*	Ab initio methods that utilize knowledge-based information

Despite significant effort, we still have very limited ability to fold proteins by ab initio approaches, i.e. to predict 3D structures of protein sequences without using template structures from other experimentally solved proteins. Successful cases have been witnessed only on small proteins with length below 100 residues, and with a root mean squared deviation (RMSD) typically above 2.5 Å. The difficulty of ab initio protein structure prediction is twofold. First, we lack decent force fields to accurately describe the atomic interactions which can be used to guide the protein folding simulations. 
Apparently, force fields with an incorrectly located global minimum will undoubtedly misfold the target proteins. Although the physics-based atomic force fields can provide a reasonable description of protein atomic interactions in many aspects, the implementation requests atomic-level representation which is often too slow to fold a protein structure from scratch. The knowledge-based potentials, which are often in reduced forms and derived from statistical regularities of structures in the Protein Data Bank (PDB), have shown power in both protein fold recognition and structure assembly simulations, where appropriate selections of reference states and structural features are proven to be of critical importance.

*	Ab initio methods without the aid of knowledge-based information

This is where Alphafold2 comes into play.

