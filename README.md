# Breast Cancer Classification

A tumor is a mass of abnormal tissue. There are two types of breast cancer tumors: those that are non-cancerous, or 'benign', and those that are cancerous, which are 'malignant'. 
A benign tumor is a tumor that does not invade its surrounding tissue or spread around the body. A malignant tumor is a tumor that may invade its surrounding tissue or spread around the body.

## 1.0 Exploratory Data Analaysis

The dataset consisted of 32 columns and the description of each column is listed below


1. id - ID number
2. diagnosis - The diagnosis of breast tissues (M = malignant, B = benign)
3. radius_mean - mean of distances from center to points on the perimeter
4. texture_mean - standard deviation of gray-scale values
5. perimeter_mean - mean size of the core tumor
6. area_mean
7. smoothness_mean - mean of local variation in radius lengths
8. compactness_mean - mean of perimeter^2 / area - 1.0
9. concavity_mean - mean of severity of concave portions of the contour
10. concave points_mean - mean for number of concave portions of the contour
11. symmetry_mean
12. fractal_dimension_mean - mean for "coastline approximation" - 1
13. radius_se - standard error for the mean of distances from center to points on the perimeter
14. texture_se - standard error for standard deviation of gray-scale values
15. perimeter_se
16. area_se
17. smoothness_se - standard error for local variation in radius lengths
18. compactness_se - standard error for perimeter^2 / area - 1.0
19. concavity_se - standard error for severity of concave portions of the contour
20. concave points_se - standard error for number of concave portions of the contour
21. symmetry_se
22. fractal_dimension_se - standard error for "coastline approximation" - 1
23. radius_worst - "worst" or largest mean value for mean of distances from center to points on the perimeter
24. texture_worst - "worst" or largest mean value for standard deviation of gray-scale values
25. perimeter_worst
26. area_worst
27. smoothness_worst - "worst" or largest mean value for local variation in radius lengths
28. compactness_worst - "worst" or largest mean value for perimeter^2 / area - 1.0
29. concavity_worst - "worst" or largest mean value for severity of concave portions of the contour
30. concave points_worst - "worst" or largest mean value for number of concave portions of the contour
31. symmetry_worst 
32. fractal_dimension_worst - "worst" or largest mean value for "coastline approximation" - 1

### 1.1 Initially the data was checked for null values and an empty column was present in the dataset. This column was removed.

### 1.2 The unique values of the dataset was analayzed and only one categorical variable was found and that is the dependant variable. (The rest of the variables are numerical)
