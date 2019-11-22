# parseCrispresso
This Matlab codes allow to extract relevant data from the folders "CRISPResso_on_···" generated by CRISPResso2 software. 

Extract_data_CRISPResso_Pool_Edited_Cells.m

This code is useful for results generated by CRISPResso2 when it is run in basic model to quantify gene editing efficiency of CRISPR reagents at a given guide RNA target site in a population of edited cells. 

The code generates an excel file (.xlsx) containing for each sample (CRISPResso2 subfolder) the 'Aligned_Reads', 'Frameshift_Mutations', 'InFrame_Mutations', 'UnModified_Reads', 'Modified_reads', 'Percentage_FSmut", 'Percentage_IFmut', 'Percentage_UnMod'' and 'Mod_percentage' calculated by CRISPResso. 

Extract_data_CRISPResso_Clonal_Edited_Cells.m

This code is useful for results generated by CRISPResso2 when it is run in basic model to identify mutations in both alleles of a target gene in a clonal line resulted from a CRISPR-editing experiment. 

Apart from trata extracted by the "Extract_data_CRISPResso_Pool_Edited_Cells.m", this code includes in the excel file up to tree allele sequences and frequencies identified by CRISPResso2. Based in these data it determines the edited genotype of each clonal line analysed. It works with alleles in both, experiments in which coding sequence is provided to CRISPResso2 and in which coding sequence is not provided to CRISPResso2.

Both codes works very similar (read code explanations for more details). You must copy the code in the same path where is located a main folder containing all "CRISPResso_on_···" subfolders, open the code in a Matlab workspace, press run and finally type in the Command Window the name of your main folder.
