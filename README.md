# StockVision

## Inventory Prediction model based on season in fashion store.

## Dataset Link
- **Kaggle Dataset**: https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-small/data


## Model Overview
This model helps fashion stores make informed decisions about the inventory count required for a particular article type across various seasons.

### **Workflow**
1. **Article-Season Prediction Model**:
   - Predicts the most likely season for a given article type.
2. **Inventory Count Prediction Model**:
   - Uses the predicted season as an input along with other features to estimate the required inventory count.

### **Inputs and Targets for Inventory Prediction Model**
#### **Input Features:**
- **Gender**
- **Season** (Predicted from Article-Season Model)
- **Brand**
- **Article Type** (e.g., Shirts, Jeans, etc.)
- **Output of Article-Season Prediction Model**

#### **Target Variable:**
- **Inventory Count**

### **Execution Steps**
Run the following Python code to:
- Load the trained models
- Enter inputs interactively
- Predict the required inventory count
