This directory contains (besides this README.txt file) two directories ( (1) coordinates_and_topology_files, (2) md_parameter_files) that contain atomic coordinates (in PDB format) of initial and final conformations, topology files, and md parameter files of all amyloid beta fibril simulations discussed in the article.

(1) coordinates_and_topology_files : This directory contains four sub directories ( (a) 5kk3 (b) 7q4b (c) 7q4m and (d) 6shs) contains initial and final coordinates of simulations and topology files. 

	(a) 5kk3 : Files are organized according to the simulations using six subdirectories as described below. 
	Following subdirectories are available inside this directory.

		5kk3_control_trial_1 - Contains topology files, initial and final coordinates of 5kk3 control trial 1 simulations.
		5kk3_control_trial_2 - Contains topology files, initial and final coordinates of 5kk3 control trial 2 simulations.
		5kk3_control_trial_3 - Contains topology files, initial and final coordinates of 5kk3 control trial 3 simulations.
		5kk3_fi10_trial_1 - Contains topology files, initial and final coordinates of 5kk3 fi10 trial 1 simulations.
		5kk3_fi10_trial_2 - Contains topology files, initial and final coordinates of 5kk3 fi10 trial 2 simulations.
		5kk3_fi10_trial_3 - Contains topology files, initial and final coordinates of 5kk3 fi10 trial 3 simulations.


	(b) 7q4b : Contains simulation files of all 7q4b simulations. Files are organized according to the simulations as described below. 
	Following subdirectories are available inside this directory.

		7q4b_control_trial_1 - Contains topology files, initial and final coordinates of 7q4b control trial 1 simulations.
		7q4b_control_trial_2 - Contains topology files, initial and final coordinates of 7q4b control trial 2 simulations.
		7q4b_control_trial_3 - Contains topology files, initial and final coordinates of 7q4b control trial 3 simulations.
		7q4b_fi10_trial_1 - Contains topology files, initial and final coordinates of 7q4b fi10 trial 1 simulations.
		7q4b_fi10_trial_2 - Contains topology files, initial and final coordinates of 7q4b fi10 trial 2 simulations.
		7q4b_fi10_trial_3 - Contains topology files, initial and final coordinates of 7q4b fi10 trial 3 simulations.


	(c) 7q4m : Contains simulation files of all 7q4m simulations. Files are organized according to the simulations as described below. 
	Following subdirectories are available inside this directory.

		7q4m_control_trial_1 - Contains topology files, initial and final coordinates of 7q4m control trial 1 simulations.
		7q4m_control_trial_2 - Contains topology files, initial and final coordinates of 7q4m control trial 2 simulations.
		7q4m_control_trial_3 - Contains topology files, initial and final coordinates of 7q4m control trial 3 simulations.
		7q4m_fi10_trial_1 - Contains topology files, initial and final coordinates of 7q4m fi10 trial 1 simulations.
		7q4m_fi10_trial_2 - Contains topology files, initial and final coordinates of 7q4m fi10 trial 2 simulations.
		7q4m_fi10_trial_3 - Contains topology files, initial and final coordinates of 7q4m fi10 trial 3 simulations.


	(d) 6shs : Contains simulation files of all 6shs simulations. Files are organized according to the simulations as described below. 
	Following subdirectories are available inside this directory.

		6shs_control_trial_1 - Contains topology files, initial and final coordinates of 6shs control trial 1 simulations.
		6shs_control_trial_2 - Contains topology files, initial and final coordinates of 6shs control trial 2 simulations.
		6shs_control_trial_3 - Contains topology files, initial and final coordinates of 6shs control trial 3 simulations.
		6shs_fi10_trial_1 - Contains topology files, initial and final coordinates of 6shs fi10 trial 1 simulations.
		6shs_fi10_trial_2 - Contains topology files, initial and final coordinates of 6shs fi10 trial 2 simulations.
		6shs_fi10_trial_3 - Contains topology files, initial and final coordinates of 6shs fi10 trial 3 simulations.

	
		Coordinates
		In each subdirectory both initial and final structures are named according to following format.

		5kk3_control_t1_initial.pdb : initial structure of control trial 1
		5kk3_control_t1_final.pdb : final structure of control trial 1

		5kk3_fi10_t1_initial.pdb : initial structure of fi10 trial 1
		5kk3_fi10_t1_final.pdb : final structure of fi10 trial 1

		

		In each of the above subdirectories, following files are available.
	
		Topology files
		topol.top		   : Topology file of the system

		topol_Protein_chain_A.itp  : Topology file of chain 1 of amyloid beta fibril
		topol_Protein_chain_B.itp  : Topology file of chain 2 of amyloid beta fibril
		topol_Protein_chain_C.itp  : Topology file of chain 3 of amyloid beta fibril
		topol_Protein_chain_D.itp  : Topology file of chain 4 of amyloid beta fibril
		topol_Protein_chain_E.itp  : Topology file of chain 5 of amyloid beta fibril
		topol_Protein_chain_F.itp  : Topology file of chain 6 of amyloid beta fibril
		topol_Protein_chain_G.itp  : Topology file of chain 7 of amyloid beta fibril
		topol_Protein_chain_H.itp  : Topology file of chain 8 of amyloid beta fibril
		topol_Protein_chain_I.itp  : Topology file of chain 9 of amyloid beta fibril
		topol_Protein_chain_J.itp  : Topology file of chain 10 of amyloid beta fibril

		posre_Protein_chain_A.itp  : Position restraint file of chain 1 of amyloid beta fibril
		posre_Protein_chain_B.itp  : Position restraint file of chain 2 of amyloid beta fibril
		posre_Protein_chain_C.itp  : Position restraint file of chain 3 of amyloid beta fibril
		posre_Protein_chain_D.itp  : Position restraint file of chain 4 of amyloid beta fibril
		posre_Protein_chain_E.itp  : Position restraint file of chain 5 of amyloid beta fibril
		posre_Protein_chain_F.itp  : Position restraint file of chain 6 of amyloid beta fibril
		posre_Protein_chain_G.itp  : Position restraint file of chain 7 of amyloid beta fibril
		posre_Protein_chain_H.itp  : Position restraint file of chain 8 of amyloid beta fibril
		posre_Protein_chain_I.itp  : Position restraint file of chain 9 of amyloid beta fibril
		posre_Protein_chain_J.itp  : Position restraint file of chain 10 of amyloid beta fibril


		Please note that following files are available only in fi10 simulations directories (not available in control simulation directories).

		topol_Protein_chain_K.itp  : Topology file of 1st fi10 peptide
		topol_Protein_chain_L.itp  : Topology file of 2nd fi10 peptide
		topol_Protein_chain_M.itp  : Topology file of 3rd fi10 peptide
		topol_Protein_chain_N.itp  : Topology file of 4th fi10 peptide
		topol_Protein_chain_O.itp  : Topology file of 5th fi10 peptide
		topol_Protein_chain_P.itp  : Topology file of 6th fi10 peptide
		topol_Protein_chain_Q.itp  : Topology file of 7th fi10 peptide
		topol_Protein_chain_R.itp  : Topology file of 8th fi10 peptide
		topol_Protein_chain_S.itp  : Topology file of 9th fi10 peptide
		topol_Protein_chain_T.itp  : Topology file of 10th fi10 peptide

		posre_Protein_chain_K.itp  : Position restraint file of 1st fi10 peptide
		posre_Protein_chain_L.itp  : Position restraint file of 2nd fi10 peptide
		posre_Protein_chain_M.itp  : Position restraint file of 3rd fi10 peptide
		posre_Protein_chain_N.itp  : Position restraint file of 4th fi10 peptide
		posre_Protein_chain_O.itp  : Position restraint file of 5th fi10 peptide
		posre_Protein_chain_P.itp  : Position restraint file of 6th fi10 peptide
		posre_Protein_chain_Q.itp  : Position restraint file of 7th fi10 peptide
		posre_Protein_chain_R.itp  : Position restraint file of 8th fi10 peptide
		posre_Protein_chain_S.itp  : Position restraint file of 9th fi10 peptide
		posre_Protein_chain_T.itp  : Position restraint file of 10th fi10 peptide
	

	
(2) md_parameter_files : MD parameter files used for energy minimization, equilibration, and production md simulation.

ions.mdp  : Parameter file for ions addition
minim.mdp : Parameter file for energy minimization
nvt.mdp   : Parameter file for NVT equilibration
npt.mdp   : Parameter file for NPT equilibration
md.mdp 	  : Parameter file for production MD run



















