---
title: "Robust prediction of remaining useful lifetime of bearings using deep learning"
authors:
- L. Magadán
- J. C. Granda
- F. J. Suárez
date: "2023-12-16T00:00:00Z"
doi: "https://doi.org/10.1016/j.engappai.2023.107690"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-12-16T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Engineering Applications of Artificial Intelligence*"
publication_short: "EAAI"

abstract: Predicting the remaining useful lifetime (RUL) of bearings in electric motors is crucial to reduce repair costs in industrial maintenance. With the technological advances of Industry 4.0, physical models for prognostics and RUL prediction have been replaced by data-driven models that require no expert feature extraction. Instead, the model itself learns which features are important. However, these models are normally trained and tested on the same dataset, i.e. under the same operating conditions. This limits the application of a model to other operating conditions unless the model is fine-tuned with data corresponding to those conditions. This paper proposes a novel robust health prognostics technique that detects inner-race bearing failures and predicts the RUL of electric motor bearings under various motor conditions without model retraining or fine-tuning. The model combines time and frequency-domain vibration signal analyses to extract features, a stacked variational denoising autoencoder (SVDAE) to fuse these features and build a Health Indicator and a bidirectional long short-term memory (BiLSTM) neural network to predict the remaining useful lifetime of the bearings. The proposed model is trained with a dataset, validated with another dataset and finally tested with seven additional datasets corresponding to vibrations gathered from different motors and operating conditions. The results are more robust and accurate than those of the literature, the robustness of the prediction with different motor and operating conditions is proven, and there is no need to retrain or fine-tune the model, making the proposed model suitable for recently installed equipment.

tags: [Health prognostics, RUL prediction, Feature fusion, Stacked variational denoising autoencoder, Bidirectional long short-term memory]
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.sciencedirect.com/science/article/pii/S0952197623018742

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: [PN2]

---
