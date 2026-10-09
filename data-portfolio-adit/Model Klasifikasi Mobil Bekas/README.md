# Used Car Image Classification

This project classifies used-car models from images using a ResNet34-based deep-learning workflow.

## Contents

- `TK1_Fattan_Raditya_Anggoro (4).ipynb` — data preparation, model training, and evaluation notebook.
- `Makalah Model Klasifikasi Mobil Bekas.pdf` — project paper.

## Dataset

The notebook downloads the [Iran Used Cars dataset](https://www.kaggle.com/datasets/usefashrfi/iran-used-cars-dataset) with `kagglehub`. You need a Kaggle account and credentials configured in your environment.

## Environment

The notebook was run in a GPU-enabled Colab/Kaggle-style environment. Core dependencies include:

```bash
pip install timm torch torchvision scikit-learn pandas matplotlib pillow kagglehub
```

## Reproduce

1. Open the notebook in Google Colab, Kaggle, or Jupyter with GPU support.
2. Configure Kaggle authentication if prompted.
3. Run cells in order to download the dataset, prepare images, train ResNet34, and evaluate predictions.

The included run reports a test accuracy of **75.7123%**. It was limited to three epochs because of GPU constraints; results can change with data splits, hardware, and training settings.
