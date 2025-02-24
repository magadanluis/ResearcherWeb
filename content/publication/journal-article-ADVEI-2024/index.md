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

abstract: Rotating machinery plays an essential role in various industrial processes such as manufacturing, power generation, and transportation. These machines, which include turbines, pumps, motors, compressors, and many others, are the heartbeats of numerous industries. The seamless operation of these machines is critical for the efficiency and productivity of these sectors. However, over time, these machines degrade and can suffer faults. One of the most critical components are bearings, which can suffer different types of faults. This paper presents a novel approach for bearing fault classification and diagnosis under limited data. A Monotonic Smoothed Stacked Auto Encoder~(MS2AE) is used to infer a smoothed monotonic health index from raw bearing acceleration data. The MS2AE is trained using only healthy data, so this approach can also be used with recently comisioned equipment that has not failed yet. Then, using the evolution of the health index, a first faulty point is computed, so two stages are identified in the lifespan of the rotating machinery: healthy and faulty. Correlation matrices are computed to show the relationship of the health index with time-domain and frequency-domain features in order to provide explainability and validate the health index construction process. When the health index is classified as faulty, Dynamic Time Warping is applied between healthy samples and faulty samples to extract differences. Finally, based on a 1/3-binary tree 3 level kurtogram, these differences are filtered using a bandpass filter and converted to the frequency domain, where characteristic harmonics are used to identify the type of bearing fault. The explainability provided in the health index construction process makes the system useful in certain industries where black-box AI models cannot be trusted due to strict regulations. The classification and diagnosis system achieves robustness in fault classification under different working conditions by utilizing multiple bearing fault datsets. Its ability to be trained using only healthy data and the interpretability offered, makes it suitable for recently installed rotating machinery in real industrial facilities, without requiring qualified staff.

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
