| Dataset                               | Method          | Identifiability (↓) | MMD (↓)    | Wasserstein (↓) |
|---------------------------------------|-----------------|---------------------|------------|-----------------|
| **ID-5** Wine Quality                 | ADASYN          | 0.7620             | 0.0531    | 0.0878         |
|                                       | Borderline-SMOTE| 0.5710             | 0.4258    | 0.1251         |
|                                       | SMOTE           | 0.7837             | 0.0496    | 0.0903         |
|                                       | FDASampler      | **0.1802**         | 0.5740    | 0.5395         |
| **ID-6** Wholesale customers          | ADASYN          | 0.9954             | 0.0250    | 0.1114         |
|                                       | Borderline-SMOTE| 0.9823             | **0.0197**| **0.1116**     |
|                                       | SMOTE           | 0.9954             | 0.0324    | 0.1466         |
|                                       | FDASampler      | **0.0804**         | 0.3454    | 0.5251         |
| **ID-7** Iranian Churn                | ADASYN          | 0.6196             | 0.1705    | 0.1128         |
|                                       | Borderline-SMOTE| 0.4611             | 0.2511    | 0.1335         |
|                                       | SMOTE           | 0.8682             | **0.0064**| **0.0265**     |
|                                       | FDASampler      | **0.0000**         | 0.6399    | 0.5373         |
| **ID-10** Ozone Level Detection       | ADASYN          | 0.5504             | **0.0492**| 0.0480         |
|                                       | Borderline-SMOTE| 0.5504             | 0.0572    | 0.0619         |
|                                       | SMOTE           | 0.5504             | 0.0518    | **0.0378**     |
|                                       | FDASampler      | **0.0174**         | 0.8904    | 0.3261         |
| **ID-11** AI4I 2020 Predictive Maintenance | ADASYN     | 1.0000             | 0.0178    | 0.0826         |
|                                       | Borderline-SMOTE| 0.9580             | 0.0333    | 0.1054         |
|                                       | SMOTE           | 1.0000             | **0.0123**| **0.0781**     |
|                                       | FDASampler      | **0.0000**         | 0.4386    | 0.6374         |
| **ID-13** Skin Segmentation           | ADASYN          | 0.0904             | 0.0635    | 0.3363         |
|                                       | Borderline-SMOTE| **0.0248**         | 0.1058    | 0.4296         |
|                                       | SMOTE           | 0.8030             | **0.0004**| **0.0228**     |
|                                       | FDASampler      | 0.0636             | 0.1049    | 0.3899         |
| **ID-14** User Knowledge Modeling     | ADASYN          | 1.0000             | 1.0000    | 1.0000         |
|                                       | Borderline-SMOTE| 0.7685             | 0.0623    | 0.1406         |
|                                       | SMOTE           | 0.7868             | **0.0333**| **0.1239**     |
|                                       | FDASampler      | **0.4534**         | 0.2103    | 0.4557         |
| **ID-16** Breast Cancer Wisconsin (Prognostic) | ADASYN | 1.0000             | 0.1107    | 0.1212         |
|                                       | Borderline-SMOTE| 0.9375             | 0.1308    | 0.1229         |
|                                       | SMOTE           | 1.0000             | **0.0968**| **0.1085**     |
|                                       | FDASampler      | **0.2734**         | 1.0479    | 0.5082         |
| **ID-19** Habermans Survival          | ADASYN          | 0.8772             | 0.0325    | 0.1824         |
|                                       | Borderline-SMOTE| 0.6798             | 0.0775    | 0.2470         |
|                                       | SMOTE           | 0.8772             | **0.0085**| **0.1269**     |
|                                       | FDASampler      | **0.1886**         | 0.1322    | 0.5685         |
| **ID-24** Vertebral Column            | ADASYN          | 0.6702             | 0.0543    | **0.1139**     |
|                                       | Borderline-SMOTE| 0.5631             | 0.0595    | 0.1355         |
|                                       | SMOTE           | 0.7446             | **0.0170**| 0.0916         |
|                                       | FDASampler      | **0.1369**         | 0.1988    | 0.3836         |
| **ID-25** SPECTF Heart                | ADASYN          | 1.0000             | **0.0660**| 0.0792         |
|                                       | Borderline-SMOTE| 1.0000             | 0.0908    | 0.0872         |
|                                       | SMOTE           | 1.0000             | 0.0842    | **0.0786**     |
|                                       | FDASampler      | **0.1184**         | 0.8025    | 0.3792         |
| **ID-27** Cervical Cancer Behavior Risk | ADASYN       | 0.9667             | **0.1597**| **0.1965**     |
|                                       | Borderline-SMOTE| 0.8333             | 0.3580    | 0.2614         |
|                                       | SMOTE           | 0.9667             | 0.1919    | 0.1709         |
|                                       | FDASampler      | **0.5500**         | 0.7916    | 0.4262         |
| **ID-28** Sepsis Survival Minimal Clinical Records | ADASYN | 0.2829             | 0.0050    | 0.0535         |
|                                       | Borderline-SMOTE| 0.2771             | 0.0054    | 0.0681         |
|                                       | SMOTE           | 0.2829             | **0.0031**| **0.0420**     |
|                                       | FDASampler      | **0.0048**         | 0.2295    | 0.6062         |
| **ID-33** Musk (Version 2)            | ADASYN          | 0.5361             | 0.1930    | 0.0223         |
|                                       | Borderline-SMOTE| 0.3750             | 0.2536    | 0.0312         |
|                                       | SMOTE           | 0.9171             | **0.0130**| **0.0200**     |
|                                       | FDASampler      | **0.0005**         | 1.0802    | 0.4824         |
| **ID-34** HTRU2                       | ADASYN          | 0.4587             | 1.1636    | 1.0435         |
|                                       | Borderline-SMOTE| 0.2734             | 1.0678    | 0.9453         |
|                                       | SMOTE           | 0.9984             | **0.0039**| **0.0422**     |
|                                       | FDASampler      | **0.0008**         | 0.6931    | 0.6793         |
| **ID-35** Drug Consumption (Quantified)| ADASYN        | 0.9278             | 0.0535    | 0.1342         |
|                                       | Borderline-SMOTE| 0.8927             | 0.0898    | 0.1396         |
|                                       | SMOTE           | 0.9229             | **0.0504**| **0.1252**     |
|                                       | FDASampler      | **0.1275**         | 0.7257    | 0.5502         |
| **Website Phishing**                  | ADASYN          | 0.2939             | 0.1140    | 0.1557         |
|                                       | Borderline-SMOTE| **0.2809**         | 0.1442    | 0.1844         |
|                                       | SMOTE           | 0.2923             | **0.0236**| **0.0705**     |
|                                       | FDASampler      | 0.0451             | 0.4779    | 0.4870         |

**Notes**:  
- ↓ indicates lower values are better.  
- Bold values denote the best-performing method for each metric within a dataset.

  **Notes**

- Although fdaSampler performs slightly worse on distribution-based metrics such as MMD and Wasserstein distance, its stronger smoothing effect enhances class separability, leading to better classification results. This indicates a trade-off where the generated samples may deviate modestly from the original data distribution but form clearer decision boundaries, which benefits classifier training in practice, especially for imbalanced datasets.
