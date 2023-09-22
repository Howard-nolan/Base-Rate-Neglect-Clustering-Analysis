# Base Rate Neglect Clustering Analysis
This repository explores the potential of altering information presentation to mitigate base rate neglect bias. The study indicates a significant reduction in base rate bias (>40%) when information presentation is altered. This git repositiory utilizes machine learning clustering models to better understand what happens to how people are impacted by base rate bias at an individual level.

## Introduction and Background
Base rate neglect is a cognitive fallacy where individuals tend to overshadow general prevalence (base rate) in favor of specific case information. This fallacy often manifests in domains like medicine and law. More about this can be found in at https://en.wikipedia.org/wiki/Base_rate_fallacy.

Professor Pellumb Reshidi from Duke University has curated a dataset underscoring that a transformation in information presentation can substantially curtail base rate neglect. This repository capitalizes on ML classification to:
1. Segment users according to their extent of base rate neglect.
2. Analyze shifts in user classifications with modifications in information presentation modalities, granting an individualized comprehension of user behavior under varying treatments.

## Approach
1. Cluster Determination: Implement the elbow method alongside the silhouette score to ascertain the ideal number of clusters.
2. Data Aggregation: Consolidate data from diverse treatments into distinct clusters.
3. Cluster Composition Analysis: Examine the variation in cluster composition across different treatments.
4. Data Classification: Classify data relative to established centroids. These centroids epitomize the accurate Bayesian probability, the naive probability, and a midpoint equidistant between them.
# Outcomes
The experimental outcomes elucidate a migration of users from categories 2 and 3 (representing erroneous estimates) to category 1 (indicating accurate estimates) when treatments, i.e., modes of information presentation, are modified. The detailed results comprise four distinct outputs:

<img width="400" alt="Screen Shot 2023-09-02 at 3 06 44 PM" src="https://github.com/Howard-nolan/Base-Rate-Neglect-Clustering-Analysis/assets/106356427/36792a3c-d069-41f9-a772-066bb7aa04e6"> <img width="400" alt="Screen Shot 2023-09-02 at 3 07 00 PM" src="https://github.com/Howard-nolan/Base-Rate-Neglect-Clustering-Analysis/assets/106356427/f9121b0f-0ae4-4e6c-b8a5-4b3b8a8bbaac">
<img width="400" alt="Screen Shot 2023-09-02 at 3 07 10 PM" src="https://github.com/Howard-nolan/Base-Rate-Neglect-Clustering-Analysis/assets/106356427/1472becd-f4ac-4eec-8ed9-1e455cdcd21d"> <img width="400" alt="Screen Shot 2023-09-02 at 3 07 17 PM" src="https://github.com/Howard-nolan/Base-Rate-Neglect-Clustering-Analysis/assets/106356427/5eb0c773-ff7d-49ce-83b3-53d0aabf95ea">
<img width="400" alt="Screen Shot 2023-09-02 at 3 07 33 PM" src="https://github.com/Howard-nolan/Base-Rate-Neglect-Clustering-Analysis/assets/106356427/d146692c-f1a0-4185-9b41-33c1862c9e4b"> <img width="400" alt="Screen Shot 2023-09-02 at 3 07 40 PM" src="https://github.com/Howard-nolan/Base-Rate-Neglect-Clustering-Analysis/assets/106356427/dfe4e50d-bfd8-440e-a56b-2ff187f94e94">
<img width="400" alt="Screen Shot 2023-09-02 at 3 07 51 PM" src="https://github.com/Howard-nolan/Base-Rate-Neglect-Clustering-Analysis/assets/106356427/719a0e23-1699-4f7b-bfed-1ae1daf6cce3"> <img width="400" alt="Screen Shot 2023-09-02 at 3 07 59 PM" src="https://github.com/Howard-nolan/Base-Rate-Neglect-Clustering-Analysis/assets/106356427/0ba89e15-35bc-42b6-b9e6-cede88eb2b63">
