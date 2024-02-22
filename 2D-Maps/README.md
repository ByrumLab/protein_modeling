Protein contact maps are a reduced representation of protein structure, providing a quick way of visually inspecting structural features. 
Contact maps provide a simplified representation of protein structures, facilitating the visual inspection of structural features based on residue proximity within the defined distance threshold.
A contact map is a square matrix M where Mi,j=1 if the distance δij between residues i and j is below a predetermined distance threshold t or Mi,j=0 otherwise. The equation for a contact map as described can be represented as follows:

<div align=”center”> $` M(i,j) = 1 if δ(i,j) < t`$ </div>



<p align="center">
// $` M(i,j) = 0 if δ(i,j) ≥ t `$
</p>


Where:
- M(i,j) represents the element at row i and column j in the contact map matrix.
- δ(i,j) denotes the distance between residues i and j.
- t is the predetermined distance threshold.

This equation defines the binary nature of a contact map, where a value of 1 indicates that the distance between residues i and j is below the threshold t, and a value of 0 indicates that 
the distance is equal to or greater than the threshold. 
