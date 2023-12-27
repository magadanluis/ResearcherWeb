---
title: "Early Fault Classification in Rotating Machinery With Limited Data Using TabPFN"
authors:
- L. Magadán
- J. Roldán-Gómez
- J. C. Granda
- F. J. Suárez
date: "2023-11-14T00:00:00Z"
doi: "https://doi.org/10.1109/JSEN.2023.33311002"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-11-14T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Sensors Journal*"

abstract: Intelligent fault detection and classification is a cornerstone of prognostic and health management of rotating machinery (RM) research. Correctly classifying and predicting RM faults not only increases productivity in industrial plants but also reduces maintenance costs. The datasets from real facilities needed to train fault classifiers often have few samples due to the expense of provoking faults in real scenarios to obtain data. This article proposes the use of the tabular prior-data fit network (TabPFN) model for the classification of faults in RM. TabPFN is a model which has been pretrained with a large amount of synthetic data with many causal relationships. This allows the model to perform Bayesian inference on the data used for training. The advantages of this model are its ability to be trained with limited data without generating overfitting problems and its high speed (if a graphics processing unit (GPU) is available). To compare its performance with traditional algorithms for tabular classification such as XGboost and random forest, three public datasets were used. Results show that TabPFN performs more accurately than algorithms with limited data, so it is suitable to be deployed in real scenarios when the amount of data available from the monitored RM is limited.

tags: [Fault classification, IIoT, predictive maintenance, rotating machinery (RM), tabular prior-data fit network (TabPFN)]
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/abstract/document/10318062

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: [PN2]

---
