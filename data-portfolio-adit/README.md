# Data Science & Analytics Portfolio

Hi, I’m **Fattan Raditya Anggoro**. This repository collects selected work in business analytics, time-series forecasting, computer vision, and digital image processing.

The projects are presented with their original reports, notebooks, and implementation files. Where a dataset is not included, the documentation explains how to obtain or supply it.

## Featured projects

| Project | Focus | Tools | Evidence |
| --- | --- | --- | --- |
| [Kimia Farma Business Analytics](#kimia-farma-business-analytics) | Sales-performance analysis and dashboarding | BigQuery, Looker Studio | Dashboard, report, presentation |
| [LQ45 Stock Index Forecasting](#lq45-stock-index-forecasting) | Irregular time-series forecasting with GRU-ODE | Python, TensorFlow, pandas | Reproducible Python implementation and thesis |
| [Used Car Image Classification](#used-car-image-classification) | Used-car model classification with ResNet34 | Python, PyTorch, timm | Notebook and project report |
| [Digital Image Processing](#digital-image-processing) | Frequency-domain image filtering | Python, Jupyter | Hands-on notebook |
| [Stress-Level Classification](#stress-level-classification) | Neural-network classification project | Artificial neural networks | Project paper |

---

## Kimia Farma Business Analytics

**Goal:** analyse Kimia Farma’s 2020–2023 sales data and communicate performance insights through an interactive dashboard.

**What’s included**

- [Dashboard preview](./Performance_Analysis_Kimia_Farma_2020-2023%20(2)_page-0001.jpg)
- [Final report](./FinalTask_KimiaFarma_BDA_Fattan%20Raditya%20Anggoro.pdf)
- [Presentation](https://docs.google.com/presentation/d/1AwqSGjQDMiKQM-grN4EsM7Yn-e9llZ9L/edit?usp=sharing)
- [Interactive Looker Studio dashboard](https://lookerstudio.google.com/reporting/86b99192-7652-4e59-97ae-014f0432d1fc)

![Kimia Farma performance dashboard preview](./Performance_Analysis_Kimia_Farma_2020-2023%20(2)_page-0001.jpg)

---

## LQ45 Stock Index Forecasting

**Goal:** forecast five-minute LQ45 closing prices from irregular high-frequency observations using a custom GRU-ODE network.

The implementation evaluates Euler and RK4 numerical solvers across a hyperparameter grid, using a chronological train/validation/test split to avoid temporal leakage.

- [Project README](./Stock%20Index%20Forecasting/readme.md)
- [Python implementation](./Stock%20Index%20Forecasting/Stock%20Price%20Forecasting%20_%20Irregular%20Time%20Series.py)
- [Thesis](./Stock%20Index%20Forecasting/Skripsi%20Adit%20Rev1.pdf)

---

## Used Car Image Classification

**Goal:** classify used-car models from images using a ResNet34-based deep-learning workflow.

The notebook loads the public Iran Used Cars dataset through Kaggle, prepares image transformations, trains the model, and reports test accuracy.

- [Project README](./Model%20Klasifikasi%20Mobil%20Bekas/README.md)
- [Notebook](./Model%20Klasifikasi%20Mobil%20Bekas/TK1_Fattan_Raditya_Anggoro%20(4).ipynb)
- [Project paper](./Model%20Klasifikasi%20Mobil%20Bekas/Makalah%20Model%20Klasifikasi%20Mobil%20Bekas.pdf)

---

## Digital Image Processing

**Goal:** implement and explore frequency-domain filtering techniques based on *Digital Image Processing* by Gonzalez and Woods.

- [Project README](./Digital%20Image%20Processing%20Hands-on%20Code/README.md)
- [Notebook](./Digital%20Image%20Processing%20Hands-on%20Code/Filtering_in_the_Frequency_Domain_Kelompok_3_TK1_Citra_Digital.ipynb)

---

## Stress-Level Classification

**Goal:** model stress levels from job characteristics, mental-health awareness, and health-history features.

- [Project documentation](./Project%20Sains%20Data%20ANN/README.md)
- [Project paper](./Project%20Sains%20Data%20ANN/Makalah%20Sains%20Data%20(1).pdf)

## Repository structure

```text
.
├── FinalTask_KimiaFarma_BDA_Fattan Raditya Anggoro.pdf
├── Performance_Analysis_Kimia_Farma_2020-2023 (2)_page-0001.jpg
├── Stock Index Forecasting/
├── Model Klasifikasi Mobil Bekas/
├── Digital Image Processing Hands-on Code/
└── Project Sains Data ANN/
```

## Notes

- This repository is intended for portfolio and educational use.
- Reports may contain data, methods, and results in Indonesian.
- External dashboards and presentation links are maintained by their providers and may require access permissions.
