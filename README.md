# 🌊 Water Quality Data Analysis

## 📌 Project Objectives
1. **Potability Water Quality**:  
   - 📈 **Goal**: Predict pH levels 1 day into the future using other features in the dataset.  
   - 🛠 **Methodology**:  
     - Regularization techniques (e.g., **LASSO**) to retain relevant features.  
     - Examination of variable collinearity to ensure robust predictions.  

2. **Agricultural Water Quality**:  
   - 🌾 **Goal**: Predict Nitrate levels 1 day into the future using other dataset features.

3. **Microbial Safety Water Quality**:  
   - 🦠 **Goal**: Predict Total Coliform levels 1 day into the future to assess microbial safety.

---

## 🗂 Dataset Overview
- **Source**: Class-recommended dataset on Water Quality.  
- **Datasets Used**:  
  - *Sample Results (narrow)*  
  - *Sample Results (physical/chemical metadata)*  
- **Merge Key**: `OrganizationIdentifier`  

📊 **Data Details**:
- The merged DataFrame contains **441 variables** related to water measurements.  
- Key features include:
  - 💧 **Alkalinity**  
  - 🧪 **Acidity**  
  - 🌱 **Carbonate/Bicarbonate Levels**  
  - 🌬️ **Carbon Dioxide (CO₂) Levels**

---

## 🔍 Research Focus
### Predictive Task:
- **Potability Water Quality**: Use last-day water quality measurements to predict the next day’s pH levels.  

---

## 🌍 Regional Focus
### Where Should Investments Be Prioritized?
Our research focuses on counties in the Bay Area, including:
- Alameda  
- Contra Costa  
- Marin  
- San Francisco  
- San Mateo  
- Santa Clara  

🏗️ **Goal**: Determine zones requiring investments in water treatment infrastructure, such as:
- 🚰 **Water Treatment Plants**  
- 🌱 **Nitrate Removal Technologies**  
- 🌊 **Drainage Systems**

For instance, if predictions show poor Nitrate quality in a specific zone of Alameda County, that zone will be prioritized for infrastructure upgrades.

---

## 📋 Methodology Summary
1. Combine datasets on water quality using `OrganizationIdentifier`.  
2. Process features to create a predictive framework for:
   - Potability (pH levels)  
   - Agricultural water quality (Nitrate levels)  
   - Microbial safety (Total Coliform levels)  
3. Apply regularization methods and evaluate collinearity to ensure robust predictions.  

---

Let us know if you'd like further details or enhancements! 🚀
