# MFJK1_Segmentation_MHDs (created 04/12/2023)
Repository contains pre-clinical MHD (ITK) images and segmentation labels for tibia of 32 mice used in the MRI study of myelofobrosis model described in:  Kushwaha, et al. Tomography 2023, 9(2), 589-602

Each data folder is labeled with the animal ID and include "Zipped" dataset for all 
available scan dates (listed in "MFJK1_seg_data_info" spreadsheet) containing source 
"MToff" MHDs utilized for segmentation and the folders with available MHD segmentations
(labeled as described in the publication):

"EA1" -- manual expert annotator 1; "EA2" -- manual expert annotator 2;
"TS" -- attention UNet for full training set; "TS1" -- attention UNet for 
"Split1" training set; "TS2" -- attention UNet for "Split2" training set;
"TSM" -- attention UNet for single-mouse training;
(Note that EA2 annotations were NOT perfromed for animals in the Training set.)

The repository also includes a "MFJK1_seg_data_info" spreadsheet with data 
summary and animal assignments to the Training, Testing, and Validation subsets,
and "MFJK1_tibia_seg_vol_RepeatabilityAnalysi" with tibia volume repeatability 
analysis for test-retest scans. 
