The results folder contains the files and figures generated by the TKSA-MC web server which are the following:

-Fig_MC_*name_of_pdb*_pH_*_T_*.jpg: figures of each simulation  for different pHs and temperature.

-Output_MC_*name_of_pdb*_pH_*_T_*.dat: Information used for algorithm obtained from the PDB file. 
There are 13 columns in this file:
1 - Name:           3 letters code used to identify the residue.
2 - Residue-index:  Residue sequence position in the PDB file.
3 - Position:       Ionizable residue index position.
4 - Atom:           Atom sequence position in the PDB file.
5 - Atom-type:      Identification of the atom assumed as the ionizable group.
6 - X:              Position X of the atom in the PDB file in nm.
7 - Y:              Position Y of the atom in the PDB file in nm.
8 - Z:              Position Z of the atom in the PDB file in nm.
9 - PKA:            Value of the reference PKA for each residue type.
10 - SASA:          Normalized Solvent-Accessible Surface Area - used the software Surface Racer© (Tsodikov, O. V. et al. (2002). J. Comput. Chem) and normalized by Lins, L. et al. (2003) Protein Sci.)
11 - Charge:        Initial charge assumed to start the algorithm.
12 - dG_Energy:     Free energy contribution of each residue in kJ/mol.
13 - Total_dG:      Electrostatic free energy contribution of all residues (Somation of column 12) in kJ/mol.

-Fig_Gqq-pH_*name_of_pdb_*.jpg: figure of Total electrostatic free energy (column 13 in the output file ) the combination of 21 different runs for different pH.
-Gqq-ph*name_of_pdb_*.dat: Total electrostatic free energy (column 13 in the output file ) the combination of 21 different runs for different pH.
-processed-*name_of_pdb_*.pdb: PDB file used by TKSA-MC web server after some format check.
