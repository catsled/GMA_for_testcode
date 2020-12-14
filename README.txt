# Discriminative Feature Learning for Visible-Infrared Person Re-Identification via Grayscale Modality Augmentation (GMA)
pytorch test code for Cross-Modality Person-Identification on SYSU-MM01 dataset and RegDB dataset.


### 1. Prepare the datasets.
- (1) SYSU-MM01 dataset. Download this dataset and put it under the directory 'dataset/SYSU-MM01/'
- (2) RegDB dataset. Download this dataset and put it under the directory 'dataset/RegDB/'

### 2. Use our trained model.
 - ` --  Our trained models are available at 'https://pan.baidu.com/s/13g_7qA4hoeKB0EyfuOXuKw' and the extraction code is 'oxu2'.

### 3. Testing.
 - ` -- Test a model on SYSU-MM01 or RegDB dataset by 'python test.py'
 - ` -- dataset `: which dataset "sysu" or "regdb"
 - ` -- mode `: "all" or "indoor" all search or indoor search (only for sysu dataset).
 - ` -- model_path `: choose the trained model you want to test. ('model_path = checkpoint_path + 'RegDB_Thermal-Visible.t'')
