# Numeric Scaling
- What is Numeric Scaling?  
  Numeric scaling is a preprocessing technique to transform numerical features to a common scale without distorting differences in the ranges of values.

- Why scale?  
  - Algorithms like SVM, k-NN, and neural networks are sensitive to feature scales.  
  - Features with large ranges can dominate learning, causing poor performance.  
  - Helps optimization converge faster and more stably.

- Common methods  
  - Min-Max Scaling (Normalization): Scales data to [0,1] range.  
  - Standardization (Z-score normalization): Centers data around zero mean and unit variance.  
  - Robust Scaling: Uses median and Interquartile Range (IQR) to reduce effect of outliers.

- Important points  
  - Fit scaler only on training data to avoid data leakage.  
  - Apply the same transformation to validation/test data.  
  - Consider data distribution and presence of outliers when choosing scaler.  
  - Scaling not always needed for tree-based models.

---

# Categorical Encoding
- What is Categorical Encoding?  
  Transform categorical features into numerical format for ML algorithms.

- Common methods  
  - One-hot Encoding: Create binary columns per category.  
  - Label Encoding: Assign integers to categories.  
  - Target Encoding: Replace categories with target averages.

- Important points  
  - Avoid high cardinality to prevent curse of dimensionality.  
  - Use encoding methods appropriate for algorithm and data.

---

# Text Cleaning
- What is Text Cleaning?  
  Preprocessing raw text to remove noise and inconsistencies.

- Typical steps  
  - Lowercasing  
  - Removing punctuation, special characters  
  - Removing stopwords  
  - Stemming/Lemmatization

---

# Text Vectorization
- What is Text Vectorization?  
  Convert cleaned text into numerical vectors for ML.

- Common methods  
  - Bag of Words  
  - TF-IDF  
  - Word Embeddings (Word2Vec, GloVe)

---

# Missing Values
- What are Missing Values?  
  Data entries missing or null.

- Handling methods  
  - Deletion (if few missing)  
  - Imputation (mean, median, mode)  
  - Advanced: KNN Imputation, model-based

---

# Outlier Handling
- What are Outliers?  
  Data points significantly different from others.

- Detection methods  
  - Statistical (Z-score, IQR)  
  - Visualization (boxplots)

- Handling methods  
  - Removal  
  - Transformation (log, winsorization)  
  - Robust models

---

# Date-Time Processing
- Processing temporal features for ML.

- Common operations  
  - Extracting year, month, day, weekday  
  - Creating cyclical features (sin/cos for hours)  
  - Handling time zones

---

# Feature Engineering
- Creating new features to improve model.

- Examples  
  - Aggregations  
  - Interactions  
  - Domain-specific transformations

---

# Data Splitting
- Splitting dataset into train, validation, test sets.

- Considerations  
  - Stratified splitting for classification  
  - Time series split for temporal data

---

# Data Balancing
- Handling imbalanced datasets.

- Techniques  
  - Oversampling (SMOTE)  
  - Undersampling  
  - Class weighting

---

# Basic Image Transforms
- Simple image preprocessing like resizing, cropping, flipping.

---

# Image Augmentation
- Random transformations to increase dataset diversity.

---

# Image Denoising
- Removing noise from images.

---

# Histogram Equalization
- Improving image contrast.

---

# Image Format Conversion
- Converting between image formats (e.g., PNG to JPEG).

---

# Image Folder Structure
- Organizing images for training (class folders, etc).

---

# Image Normalization
- Scaling pixel values (e.g., to [0,1] or mean=0, std=1).
