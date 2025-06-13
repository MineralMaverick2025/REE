**codefile structure **

-Base_metal_prediction 

----CNN

input_file: cu_input.tiff

code_file: cnn_for_base_metal_prediction.ipynb

training_dataset: BM_N_BM_new.shp (location of deposit and non-deposit)

output:prediction_map_67.tif

----RF

input_file: cu_input.tiff

code_file: rf_for_bm_prediction.ipynb

training_dataset: BM_N_BM_new.shp (location of deposit and non-deposit)

output: prediction_map_rf_89.tiff


----SVM

input_file: cu_input.tiff

code_file: svm_for_bm_prediction.ipynb

training_dataset: BM_N_BM_new.shp (location of deposit and non-deposit)


----FIS

input_file:

aeromag_dist_cl1_9.tiff

buffer_5km.tiff

cet_pol_cl1_9.tiff

cet_pt_cl1_9.tiff

grav_dist_cl1_9.tiff

grav_fv_9.tiff

l_99.tiff

pca2_kriging_9.tiff

spec_k_9.tiff

spec_k_th_9.tiff

code_file: fis_code.ipynb

output: probability_map.tiff

-------------------------------------------------------------------------------------------------------------------

-Gold_prediction


----CNN

input_file: au_input.tiff

code_file: cnn_for_gold_prediction.ipynb

training_dataset: Gold_N_Gold.shp (location of deposit and non-deposit)

output: prediction_map_87.tif


----RF

input_file: au_input.tiff

code_file: rf_for_gold_prediction.ipynb

training_dataset: Gold_N_Gold.shp (location of deposit and non-deposit)

output: prediction_map_rf.tiff


----SVM

input_file: au_input.tiff

code_file: svm.ipynb

training_dataset: Gold_N_Gold.shp (location of deposit and non-deposit)


----FIS

input_file:

aeromag_dist_cl1_9.tiff

buffer_5km.tiff

cet_pol_cl1_9.tiff

cet_pt_cl1_9.tiff

grav_dist_cl1_9.tiff

grav_fv_9.tiff

l_99.tiff

pca2_kriging_9.tiff

spec_k_9.tiff

spec_k_th_9.tiff

code_file: fis_code.ipynb

output: probability_map.tiff

-----------------------------------------------------------------------------------------------------------------------

-Ree_prediction


----CNN

input_file: ree_input.tiff

code_file: cnn_for_ree_prediction.ipynb

training_dataset: REE_points.shp (location of deposit and non-deposit)

output: prediction_map_76.tif


----RF

input_file: ree_input.tiff

code_file: rf_for_ree_prediction.ipynb

training_dataset: REE_points.shp(location of deposit and non-deposit)

output: prediction_map_rf_92.tiff


----SVM

input_file: ree_input.tiff

code_file: svm_for_ree_prediction.ipynb

training_dataset: REE_points.shp (location of deposit and non-deposit)


----FIS

input_file:

buffer_5km.tiff

l_99.tiff

pca2_kriging_9.tiff

spec_k_9.tiff

spec_k_th_9.tiff

code_file: fis_code.ipynb

output: probability_map.tiff

-----------------------------------------------------------------------------------------------------------------------------

----input_for_all_commodity_algorithm

aeromag_dist_cl1_9.tiff

buffer_5km.tiff

cet_pol_cl1_9.tiff

cet_pt_cl1_9.tiff

grav_dist_cl1_9.tiff

grav_fv_9.tiff

l_99.tiff

pca2_kriging_9.tiff

spec_k_9.tiff

spec_k_th_9.tiff

au_input.tiff

cu_input.tiff

ree_input.tiff


----------------------------------------------------------------------------------------------------------------------------

https://drive.google.com/drive/folders/10XvYc0SgoPySNC54YIEf1ZtN3LyrrGG3?usp=sharing
