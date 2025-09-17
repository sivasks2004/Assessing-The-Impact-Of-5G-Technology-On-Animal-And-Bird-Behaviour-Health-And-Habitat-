# 🛰️ Assessing the Impact of 5G Technology on Animal and Bird Behaviour, Health and Habitat

## 📌 Project Overview
The rapid deployment of **5G technology**, with its **high-frequency electromagnetic radiation (EMR)**, has raised concerns about its potential effects on **wildlife ecosystems**.  
This project investigates the **physiological, behavioural, and ecological impacts** of 5G radiation on a wide range of animal species — including **mammals, birds, insects, and aquatic life**.

Our approach integrates:
- **Real-time ecological data collection**
- **Machine Learning models** for predictive analysis
- **Comparative evaluation** of classification algorithms

The goal is to **predict disruptions in animal behaviour, mortality risk, and habitat fragmentation**, ultimately guiding **policy makers, environmental agencies, and telecom providers** towards sustainable 5G deployment.

---

## 👥 Team & Mentor
- **Mentor:** Mr. S. B. Kartikeyan (Assistant Professor, Dept. of Computer Applications, Kongu Engineering College)
- **Team Members:**
  - D. Rubitha [24MCR083]  
  - K. Siva [24MCR101]  
  - B. Thirisurya [24MCR117]   

---

## 🎯 Objectives
1. Assess the **impact of 5G EMR** on animal health, behaviour, and habitat.  
2. Identify **species most vulnerable** to EMR exposure.  
3. Develop **predictive ML models** for ecological disruption assessment.  
4. Provide **data-driven insights** to balance technological growth with conservation.  

---

## 📚 Literature Review
- Studies reveal **biological effects of EMR** on insects, birds, mammals, and aquatic life.  
- Observed impacts include:
  - **Oxidative stress**  
  - **Reproductive issues**  
  - **Navigation and migration disruptions**  
  - **Reduced biodiversity and habitat fragmentation**  
- Lack of **standardized testing protocols** and **long-term ecological data** motivates this project.  

---

## 🛠️ Methodology

### 🔹 1. Data Collection
- Environmental monitoring systems & ecological databases  
- IoT-based **sensor networks**, **satellite imagery**, and **drone surveillance**  
- Species-specific features: migration routes, reproductive cycles, feeding behaviour, nesting patterns, proximity to 5G towers  
- Field expert reports & conservation biologist insights  

### 🔹 2. Data Preprocessing
- Cleaning and normalization of heterogeneous datasets  
- Handling missing values using **imputation techniques**  
- Encoding categorical variables (species type, habitat type)  
- Scaling numerical features (distance from tower, sightings, temperature)  

### 🔹 3. Feature Selection
- **Boruta, Mutual Information, and K-Best** methods  
- Key features: **nest abandonment, disoriented migration, mortality rate, habitat type**  
- Reduces dimensionality while improving interpretability  

### 🔹 4. Data Splitting & Balancing
- **Train-test split** (80:20 / 70:30)  
- **SMOTE** (Synthetic Minority Oversampling Technique) to handle class imbalance  
- Ensures fair learning across affected vs. unaffected species  

### 🔹 5. Model Training
- **Support Vector Machine (SVM):** Maximizes class separation margin.  
- **Gradient Boosting:** Iteratively corrects errors, improves accuracy.  
- **CatBoost:** Handles categorical features efficiently, avoids preprocessing complexity.  
- **Random Forest:** Ensemble of decision trees, improves robustness.  

### 🔹 6. Model Evaluation
- **Metrics used:** Accuracy, Precision, Recall, F1-Score, ROC-AUC  
- **Visualization:** Performance charts (per species, per algorithm)  

### 🔹 7. Final Prediction
- Deploy best-performing model (**CatBoost with 99.06% accuracy**)  
- Predicts disruption in behaviour, habitat fragmentation, and ecological risk zones  

---

## 📊 Results
| Algorithm              | Accuracy  | Precision | Recall | F1-Score |
|------------------------|-----------|-----------|--------|----------|
| CatBoost               | **99.06%** | 1.00      | 1.00   | 1.00     |
| Gradient Boosting      | 98.31%    | 0.98      | 0.98   | 0.98     |
| Random Forest          | 96.81%    | 0.97      | 0.96   | 0.96     |
| Support Vector Machine | 92.50%    | 0.92      | 0.91   | 0.91     |

✅ **Key Observation:** CatBoost outperformed other models, showing strongest prediction accuracy and reliability in identifying species impacted by 5G EMR.

---

## 🔮 Future Scope
- Implement **LSTM & Transformer models** for temporal behaviour prediction.  
- Expand dataset to include **global ecological diversity**.  
- Use **Generative Adversarial Networks (GANs)** to simulate rare case data.  
- Develop **cloud-based collaborative platforms** for real-time wildlife monitoring.  

---

## 🌍 Impact
This research emphasizes the **need for balance** between **technological advancement** and **ecological preservation**.  
By integrating **machine learning with environmental science**, we contribute towards **sustainable 5G deployment strategies**.

---

## 📝 Conclusion
This project demonstrates that **5G electromagnetic radiation has measurable ecological impacts**, particularly on species sensitive to electromagnetic cues.  
By applying **advanced ML algorithms**, we achieved high prediction accuracy, with **CatBoost emerging as the most reliable model**.  
Our findings stress the importance of **balancing technological advancement with biodiversity conservation**, ensuring that 5G deployment strategies are **environmentally responsible** and **sustainable**.

---

## 📑 References
Key references include:
- International Journal of Innovative Research in Science, Engineering and Technology (IJIRSET)  
- Environmental Health (2022) – DOI: 10.1186/s12940-022-00900-9  
- EKLIPSE Project Report (2018) on EMR & wildlife  
- Cindy L. Russell – 5G Public Health and Environmental Implications  
- Multiple peer-reviewed studies on birds, insects, mammals, and aquatic ecosystems under EMF exposure  

