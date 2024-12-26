# imdb-distilbert
This project employs parameter-efficient fine- tuning, LoRA (low-rank adaptation), on a pre- trained DistilBERT to compare with a fully- trained DistilBERT and Logistic Regression model for the purpose of sentiment classification of IMDb movie reviews.

Achieved 92% best test accuracy on IMDb sentiment classification using LoRA and AdaLoRA fine-tuning on HuggingFace’s DistilBERT, trained in 20 minutes on a T4 Colab GPU with 17k samples; hyperparameters optimized with Optuna
