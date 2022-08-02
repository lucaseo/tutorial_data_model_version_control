# Weights & Biases : Basic tutorial

https://wandb.ai/

## Tutorial order

1. [dataset cleaning](https://github.com/lucaseo/tutorial_data_model_version_control/blob/main/ex_wandb/notebook/data_cleaning.ipynb)
    1. save raw dataset
    2. 1st data cleaning (basic) + versioning
    3. 2nd dats cleaning (eda) + versioning

2. [dataset split](https://github.com/lucaseo/tutorial_data_model_version_control/blob/main/ex_wandb/notebook/train_test_split.ipynb) 
   1. train/test split + versioning(splitted data)

3. model train
   1. [feature engineering + saving artifact(encoder, binarizer)](https://github.com/lucaseo/tutorial_data_model_version_control/blob/main/ex_wandb/notebook/feature_engineering.ipynb)
   2. [baseline model training + saving artifact(model)](https://github.com/lucaseo/tutorial_data_model_version_control/blob/main/ex_wandb/notebook/model_training-1.ipynb)
   3. [2nd model training + saving artifact(model)](https://github.com/lucaseo/tutorial_data_model_version_control/blob/main/ex_wandb/notebook/model_training-2.ipynb)

4. [inference](https://github.com/lucaseo/tutorial_data_model_version_control/blob/main/ex_wandb/notebook/inference.ipynb)
   1. download artifacts for production environment
   2. execute inference