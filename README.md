# COSI-150B-FinalProject

## Author: Tingwei Liu     tingweiliu@brandeis.edu

## This is a project implement FFM and FwFM based on Recbole Library.
Recbole Offical: https://github.com/RUCAIBox/RecBole


## How to run
### 1. Download the dataset
Follow the link from the Recbole library and download processed Criteo Dataset
https://drive.google.com/drive/folders/1LUAplt4mgB6LhLTGND6x0hrnRC_T9OpN

### 2. Clone this repository, put your download dataset into /Recbole/dataset folder

### 3.use command
(base) root % python run_recbole.py --model=FFM --dataset=criteo --config_files=test.yaml
for FFM model

(base) root % python run_recbole.py --model=FwFM --dataset=criteo --config_files=test.yaml
for FwFM model

