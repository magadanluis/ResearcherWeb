---
title: "Explainable and interpretable bearing fault classification and diagnosis under limited data"
authors:
- L. Magadán
- C. Ruíz-Cárcel
- J. C. Granda
- F. J. Suárez
- A. Starr
date: "2024-11-05T00:00:00Z"
doi: "https://doi.org/10.1016/j.aei.2024.102909"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-11-05T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Advanced Engineering Informatics*"
publication_short: "ADVEI"

abstract: Remaining useful lifetime (RUL) predictions of electric motors are of vital importance in the maintenance and reduction of repair costs. Thanks to technological advances associated with Industry 4.0, physical models used for prediction and prognostics have been replaced by data-driven models that do not require specialized staff for feature selection, as the model itself learns what features are important. However, these models are usually trained and tested with the same datasets. That makes it difficult to reuse models with different datasets, so they should be retrained with data from the specific motor being analyzed. This paper presents a novel and robust health prognostics technique that predicts the remaining useful lifetime of the bearings of electric motors under different motor conditions (shaft frequency, load, type of bearing) without retraining or fine-tuning the model used. The model integrates the frequency-domain signal analysis and a stacked autoencoder (SAE) with a bidirectional long short-term memory (BiLSTM) neural network. The proposed model is trained with the IMS-bearing dataset and is then tested with IMS, FEMTO, and XJTU-SY datasets without retraining it, providing accurate results in all of them, and proving its robustness with different electric motors and work conditions.

tags: [Industry 4.0, Fault diagnosis, Fault classification, Rotating machinery, Dynamic time warping, Stacked autoencoder, Explainable AI]
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://link.springer.com/article/10.1007/s11036-022-02017-2

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: [PN2]

---
