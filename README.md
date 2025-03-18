# 🚀 SpaceX Falcon 9 First Stage Landing Prediction  

## **Project Description**  
This project is part of the **IBM Data Science Capstone**. The goal is to predict whether the first stage of SpaceX’s Falcon 9 rocket will successfully land after launch.  

SpaceX offers Falcon 9 launches for approximately **$62 million**, while other providers charge over **$165 million**. A significant portion of the savings comes from the **reusability of the first stage**.  

By predicting the landing success of the first stage, we can estimate the cost of a launch and help alternative companies **compete against SpaceX** in the rocket launch market.  

## **Project Structure**  
The project is organized into several folders, each containing specific components:  

### **1. Data Collection**  
📂 **Files:**  
- `jupyter-labs-spacex-data-collection-api-v2.ipynb`  
- `jupyter-labs-webscraping.ipynb`  

📄 **Description:**  
These notebooks contain code for collecting data from various sources, including APIs and web scraping. The collected data includes **launch records, payload details, and landing outcomes**.  

### **2. Exploratory Data Analysis**  
📂 **Files:**  
- `dashbord.ipynb`  
- `dataset_part_3.csv`  
- `jupyter-labs-eda-dataviz-v2.ipynb`  
- `jupyter-labs-eda-sql-coursera_sqllite.ipynb`  
- `lab-jupyter-launch-site-location-v2.ipynb`  

📄 **Description:**  
These notebooks perform **data wrangling, exploratory data analysis (EDA), and visualization**.  
Key analyses include:  
- **Landing outcomes distribution**  
- **Payload mass impact on launch success**  
- **Launch site analysis**  
- **Visualizations using Folium and Plotly**  

### **3. Model Training**  
📂 **Files:**  
- `SpaceX-Machine-Learning-Prediction-Part-5-v1.ipynb`  

📄 **Description:**  
This notebook contains code for training and evaluating **machine learning models** to predict the landing outcomes of Falcon 9’s first stage.  
Key steps:  
- Comparing various **classification models**  
- Identifying the **best-performing model**  

### **4. Report**  
📂 **Files:**  
- `ds-capstone-template-coursera.pptx`  

📄 **Description:**  
This presentation summarizes the project findings, including:  
- Visualizations  
- Model performance metrics  
- Key insights  

## **Key Findings**  

### **Landing Outcomes Analysis**  
- The most frequent outcome was **"No Attempt"**, followed by **"Failure (drone ship)"** and **"Success (ground pad)"**.  

### **Model Accuracy Comparison**  
- The **SVM (Support Vector Machine) model** achieved the highest classification accuracy, proving to be the most effective model for predicting landing success.  

### **Confusion Matrix for SVM Model**  
- The confusion matrix showed a **high number of true positives and true negatives**, indicating good prediction performance.  

### **Payload vs. Launch Outcome Analysis**  
- Scatter plots revealed **the correlation between payload mass and launch success**, showing which **payload ranges and booster versions** had the highest success rates.  

### **Launch Site Location Analysis**  
- The proximity analysis of **launch sites** provided insights into **strategic site placement and its impact on launch success rates**.  

## **Conclusion**  
✅ **Best Model:** The **SVM model** was identified as the most effective for predicting Falcon 9 landing outcomes.  
✅ **Strategic Insights:** Analyzing launch sites helped **optimize launch operations**.  
✅ **Data Preparation:** Proper **data wrangling and EDA** were crucial for building an accurate and reliable model.  

These findings provide **valuable insights for SpaceX** and other stakeholders in optimizing **future launch operations and improving mission success rates**.  
