# AI_MI_Intern_T11
#Breast_cancer_dataset.csv, contains the Breast Cancer Wisconsin (Diagnostic) Dataset. This dataset is widely used in machine learning for predicting whether a breast mass is malignant or benign based on digitized images of fine needle aspirates (FNA).
# **Dataset Summary**
* **Total Samples:** 569
* **Total Attributes:** 32 (ID, Diagnosis, and 30 numeric predictive features)
* **Target Variable:** `diagnosis`
* **M** = Malignant (Cancerous)
* **B** = Benign (Non-cancerous)
# **Key Features**
The features describe ten core characteristics of the cell nuclei. For each characteristic, the dataset provides the **Mean**, **Standard Error (SE)**, and **"Worst"** (mean of the three largest values), resulting in 30 total dimensions:
1. **Radius:** Mean of distances from center to points on the perimeter.
2. **Texture:** Standard deviation of gray-scale values.
3. **Perimeter:** The total distance around the nucleus.
4. **Area:** The size of the nucleus.
5. **Smoothness:** Local variation in radius lengths.
6. **Compactness:** Calculated as .
7. **Concavity:** Severity of concave portions of the contour.
8. **Concave Points:** Number of concave portions of the contour.
9. **Symmetry:** Balanced shape of the nucleus.
10. **Fractal Dimension:** Complexity of the nucleus boundary.
# **Technical Details**
* **Data Type:** All predictive features are floating-point numbers (`float64`).
* **Missing Values:** There are no missing values in the main 32 columns.
* **Typical Use Case:** Binary classification and feature importance analysis in medical diagnostics.
