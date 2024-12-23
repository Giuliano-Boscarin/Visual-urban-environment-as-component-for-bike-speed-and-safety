

# Visual Urban Environment: A Component for Bike Speed and Safety Analysis

This project leverages machine learning and explainable AI (xAI) techniques to analyze cycling dynamics in urban environments. It integrates visual and tabular data to predict cycling speeds and study safety patterns related to cycling accidents. The ultimate goal is to provide actionable insights for improving urban infrastructure and enhancing cycling safety.

---

### **Goal**
1. **Cycling Speed Prediction**: Use visual features of urban spaces (e.g., road quality and surrounding infrastructure) combined with tabular data to predict cycling speeds.
2. **Cycling Safety Analysis**: Examine and explain bike accidents using explainable AI, identifying risk factors and patterns to improve safety measures.

---

### **Methods**
1. **Image Embeddings**: Use embeddings of urban space images to train machine learning models and analyze the impact of visual elements on cycling speeds.
2. **Safety Analysis**: Combine accident data and tabular information to model and explain cycling accident risks.
3. **Explainability**: Apply xAI techniques to interpret model predictions and uncover actionable insights for urban planning.

---

### **Data Sources**
The datasets used in this project include:
1. **Visual Data**:
   - Images of Rotterdam's urban spaces.
   - Image metadata with details such as year, month, and location (`image_metadata.csv`).
   - Image embeddings representing visual features (`image_embeddings.csv`).
2. **Cycling Speed Data**:
   - Geo-dataset containing streets and corresponding bike speed data for the Netherlands (`bike_speeds.gpkg`).
3. **Traffic Accident Data**:
   - Geo-dataset with information on accidents in Rotterdam (`accident_events.geojson`).
   - Tabular data describing parties involved in the accidents (`accident_parties.csv`).

**Note**: All geographical datasets are transformed to the Dutch projection (EPSG: 28992).

---

### **Techniques Used**
1. **Data Preprocessing**:
   - Handling image and tabular data.
   - Standardizing and transforming geographical data.
2. **Machine Learning**:
   - Supervised models for predicting cycling speeds using image embeddings.
   - Models for analyzing accident data and identifying risk factors.
3. **Explainable AI**:
   - Techniques like SHAP (SHapley Additive exPlanations) to interpret model predictions and uncover patterns.
4. **Visualization**:
   - Tools like Matplotlib and Seaborn for data insights and exploratory analysis.
5. **Geo-analysis**:
   - Integration of geographical datasets for urban analysis.

