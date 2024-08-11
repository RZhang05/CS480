# CS480

## Sources

Notebooks adapted from https://www.kaggle.com/code/hdjojo/modified-planttraits2024-eda-training and https://www.kaggle.com/code/markwijkhuizen/planttraits2024-eda-training-pub. Fine-tuned model from the same source.

## Reproducibility

1. We need to generate a fine-tuned image model. The finetuning notebook is for this purpose but note that the produced model only achieves 0.32 public score. To achieve the 0.52 on the leaderboard, use the fine-tuned image model given in the link above instead which has a 0.44 public score.
2. Now we can add the tabular data using the proj notebook. This is very similar to the finetuning notebook, but combines the image model with a tabular model. If using the fine-tuned model from the link above this will give the 0.52. Using the model from the finetuning notebook will give 0.33. 
