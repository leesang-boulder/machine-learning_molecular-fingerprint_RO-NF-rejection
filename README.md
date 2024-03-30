# Raw and processed data

new_list_2.csv - SMILES of compounds having rejection data

compound_rejections_3.csv - raw data with membrane properties, compound properties, and operating conditions

df_fin_path_1024_1_fin.csv - processed rejection data with path-based molecular fingerprint (length = 1)

df_fin_path_32768_3_fin.csv - processed rejection data with path-based molecular fingerprint (length = 3). Not uploaded here due to the file size, but can be provided upon request.

df_fin_morgan_4096_1_fin.csv - processed rejection data with circular molecular fingerprint (radius = 1)

df_fin_morgan_16384_3_fin.csv - processed rejection data with circular molecular fingerprint (radius = 3). Not uploaded here due to the file size, but can be provided upon request.

df_fin_PubChem_new.csv - processed rejection data with PubChem structural key molecular fingerprint

df_fin_MACCS_new.csv - processed rejection data with MACCS structural key molecular fingerprint


# ML_MF_Rejection jupyter notebook scripts

Clustering - This code groups molecules in a unsupervised manner based on their molecular fingerprints

Draw_molecule - Draw molecular fragments corresponding to fingerprint feature number

MF_generation - Generate different fingerprints based on SMILES

Model_dataset_2_nested_hyperparameter - Build a XGBoost bodel

Tanimoto_similarity - Analyze the outcomes with finerprint similarity scores and rejections

calculation_CPSA - calculating molecular descriptors such as Van Der Waals Volume and Partial Surface charge
