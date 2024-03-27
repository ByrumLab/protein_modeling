2D maps refer to graphical representations that display structural information in a two-dimensional format. These maps typically depict various aspects of protein structures, such as secondary structure elements (e.g., alpha helices, beta strands), residue interactions, contact maps, and other relevant features.

2D maps can provide valuable insights into the spatial arrangement of amino acids, the connectivity between different regions of the protein, and the overall topology of the structure. They are often used in conjunction with 3D models and other visualization tools to aid in the analysis and interpretation of protein structures.

Common types of 2D maps used for protein structure visualization include Ramachandran plots, contact maps, secondary structure diagrams, and sequence alignment representations. These maps help researchers and scientists better understand the complex three-dimensional architecture of proteins and identify key structural characteristics that may be important for function or interaction with other molecules.


Protein _contact maps_ are a reduced representation of protein structure, providing a quick way of visually inspecting structural features. 
Contact maps provide a simplified representation of protein structures, facilitating the visual inspection of structural features based on residue proximity within the defined distance threshold.

A contact map is a square matrix M where Mi,j=1 if the distance δij between residues i and j is below a predetermined distance threshold t or Mi,j=0 otherwise. The equation for a contact map as described can be represented as follows:

$`M(i,j) = 1 if δ(i,j) < t`$

$`M(i,j) = 0 if δ(i,j) ≥ t`$



Where:
- M(i,j) represents the element at row i and column j in the contact map matrix.
- δ(i,j) denotes the distance between residues i and j.
- t is the predetermined distance threshold.

This equation defines the binary nature of a contact map, where a value of 1 indicates that the distance between residues i and j is below the threshold t, and a value of 0 indicates that 
the distance is equal to or greater than the threshold. 
