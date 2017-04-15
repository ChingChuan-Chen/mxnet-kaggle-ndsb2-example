## Step by step

0. Download data from [Kaggle-NDSB-II](https://www.kaggle.com/c/second-annual-data-science-bowl/data)
1. Put `sample_submission_validate.csv.zip`, `train.csv.zip`, `train.zip` and `validate.zip` in project folder.
2. Run `processing.R` to pack `dcm` files into csv file with 30 x 64 x 64 resized image per line.
3. Run `train.R` to generate `submission.csv`.
