# ColabFavourites

My Google Colab notebooks for machine learning projects.

- Code lives here: one notebook per task, named `<Project>_<Task>.ipynb`.
- Data and trained models live in Google Drive under `MyDrive/ColabFavourites/<Project>/`.
- Released models are published as GitHub Releases tagged `<project>-model-v<N>`.

## CoffeeCare: coffee leaf disease detection (MSc research)
Detects diseases on Arabica and Robusta coffee leaves for Ugandan farmers.
Backend API: `coffeecare-backend` repository.

| Notebook | Purpose |
|---|---|
| CoffeeCare_Dataset_Builder.ipynb | Download datasets, map classes, build train/val/test splits |
| CoffeeCare_Model_Training.ipynb | Train MobileNetV3 and export TFLite (coming) |
| CoffeeCare_Model_Evaluation.ipynb | Ugandan test set, confusion matrix, per-species results (coming) |