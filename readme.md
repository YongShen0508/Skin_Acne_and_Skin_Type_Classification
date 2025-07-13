## 🧪 Final Year Project - Phase 1 (FYP1)

This repository documents the work completed in **FYP1**, which focuses on the development and evaluation of a deep learning-based skin analysis model. The objective is to accurately assess users' skin conditions using facial image inputs.

---

## ✅ Objective 1: Development and Comparison of Skin Analysis Models

### 🎯 Goal
To develop a deep learning-based skin analysis model capable of evaluating and determining users' skin conditions with high accuracy.

### 🧠 Models Evaluated
The following models were trained and tested on a labeled dataset of facial skin images:

1. **Classic Convolutional Neural Network (CNN) model**
2. **EfficientNetB0 model**
3. **ResNet50 model**
4. **YOLOv8 model**
5. **GPT assitant-based Classification model powered by GPT-4o**

### ⚙️ Methodology

- Utilized preprocessed facial images labeled with:
  - **Acne severity levels**: Level 0, Level 1, Level 2  
  - **Skin types**: Dry, Oily, Normal  
- Split the dataset into **training** , **validation** and **testing** sets  
- Applied **data augmentation techniques** (e.g., flipping, rotation, brightness adjustment) on training set  to improve model generalization
- All images will be resized to a fixed shape of (224, 224).
- Evaluated model performance using:
  - **Accuracy**
  - **Precision**
  - **Recall**
  - **Confusion Matrix**

### 📊 Results Summary

> ## Skin Acne Summary

| Model           | Training Accuracy | Validation Accuracy | Testing Accuracy |
|-----------------|-------------------|----------------------|------------------|
| CNN             | 45.3%             | 43.0%                | 36.0%            |
| EfficientNetB0  | 80.0%             | 56.0%                | 56.5%            |
| ResNet50        | 60.8%             | 56.1%                | 49.3%            |
| YOLOv8          |                 70.0%                    | 64.0%            |
| ChatGPT API     |                  --                      | 43.0%            |


### 🏆 Best Performing Model
The **YOLOv8** model achieved the highest accuracy among all tested models and was selected as the core skin analysis model for subsequent stages of the system.

### ✅ Status
Objective 1 has been successfully completed. The most accurate and reliable model has been selected to power the skin condition evaluation component.

### 🔜 What’s Next in FYP2
In **FYP2**, the focus will be on completing the system with the following objectives:

- **Objective 2: To recommend skincare products suitable for users with various skin concerns**  
  Develop a recommendation module that suggests personalized skincare products based on the skin analysis results. This ensures users receive product suggestions tailored to their specific skin conditions, improving effectiveness while minimizing potential side effects.  
  The system will utilize a Content-Based Filtering approach to identify and recommend the most suitable products.

- **Objective 3: To develop a mobile application for skin analysis and recommendation system**  
  Build a user-friendly mobile application that integrates the deep learning skin analysis model and the skincare product recommendation module. The app will provide an intuitive interface allowing users to scan their skin, receive personalized product recommendations, and track their skin improvement over time by storing past analysis results for easy comparison.


---

> **Note:** The source code and implementation details will be updated once the full program is completed.
