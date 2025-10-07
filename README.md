# Water Quality Prediction System🌊💧
**Overview**

The Water Quality Prediction System is an intelligent application designed to predict the quality of water based on various chemical and physical parameters. Using machine learning techniques, the system classifies water as safe or unsafe for consumption, helping authorities, industries, and communities ensure water safety.

**Features**

Predict Water Quality: Classifies water as safe or unsafe using machine learning models.
Data-Driven Insights: Analyzes important water parameters such as pH, turbidity, hardness, etc.
Interactive Interface: Allows users to input water parameters and receive instant predictions
Visualization: Provides graphs and charts for data analysis and trends.
Scalable: Can be extended to include real-time sensor data.

**Technologies Used**

Programming Language: Python
Libraries/Frameworks:
pandas, numpy → Data manipulation
scikit-learn → Machine Learning models
matplotlib, seaborn → Data visualization
Flask/Streamlit → Web interface (if applicable)
Database: CSV / SQL (for storing water quality data)

**Installation**

```Clone the repository:
git clone https://github.com/yourusername/water-quality-prediction.git
```

```Navigate to the project folder:
cd water-quality-prediction
```
```Install required dependencies:
pip install -r requirements.txt
```
```Run the application:
streamlit run app.py

```

**Usage**
Open the application in your browser.
Input the water parameters: pH, Hardness, Solids, Chloramines, Sulfate, Conductivity, Organic Carbon, Trihalomethanes, Turbidity, etc.
Click Predict to see the water quality result.
Optionally, visualize trends and insights from historical data.

**Dataset**

The system uses a dataset containing water quality parameters and quality labels.

Example dataset columns:

pH, Hardness, Solids, Chloramines, Sulfate, Conductivity, Organic_carbon, Trihalomethanes, Turbidity, Quality
You can find the dataset in the data/ folder.
Machine Learning Models
Logistic Regression
Random Forest Classifier
Support Vector Machine (SVM)
You can train your model with your dataset or use the pre-trained model provided.

```Folder Structure
water-quality-prediction/
│
├── data/                # Dataset files
├── models/              # Trained ML models
├── app.py               # Main application script
├── requirements.txt     # Dependencies
├── README.md            # Project documentation
└── utils.py             # Helper functions
```
Contributing

Fork the repository.
Create your feature branch: git checkout -b feature-name
Commit your changes: git commit -m "Add new feature"
Push to the branch: git push origin feature-name
Open a pull request.

License

This project is licensed under the MIT License.

**Contact**
Developer: Siddharth Bajaj

Email:siddharthbajaj24@gmail.com

LinkedIn/GitHub:github.com/siddharthcode-24

**Water Quality Prediction**

This project aims to predict multiple water quality parameters using machine learning techniques, specifically MultiOutputRegressor wrapped around a RandomForestRegressor. It was developed as part of a one-month AICTE Virtual Internship sponsored by Shell in June 2025.
<br>

**Overview**

Access to clean water is a critical global concern. Accurate prediction of various water quality metrics can help in early detection of pollution and ensure timely intervention.
In this project, we:
Collected and preprocessed real-world water quality datasets
Used supervised machine learning for multi-target regression
Built a pipeline using MultiOutputRegressor with RandomForestRegressor
Evaluated the model using appropriate regression metrics.
<br>
**Technologies Used**

Python 3.12
Pandas, NumPy – Data handling
Scikit-learn – Machine learning model and evaluation
Matplotlib, Seaborn – Data visualization
Jupyter Notebook – Interactive experimentation
<br>

**Predicted Water Quality Parameters**

The model predicts multiple water quality parameters such as:
NH4
BOD5 (BSK5)
Colloids
O2, NO3, NO2, SO4, PO4 and
CL
<br>

**Model Performance**

The model was evaluated using:

R² Score
Mean Squared Error (MSE)
Performance was acceptable across all parameters
<br>

**Model link:**

 https://drive.google.com/file/d/1dnr2C6i7SuxRg_FEJ6gVSThgCavLtXa6/view?usp=drive_link
<br>
**Internship Details**
```
Internship Type: AICTE Virtual Internship - Edunet Foundation
Sponsor: Shell
Duration: June 2025 (1 month)
Focus Area: Machine Learning in Environmental Monitoring
