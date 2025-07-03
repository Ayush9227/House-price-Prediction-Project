🏠 House Price Prediction using Machine Learning  
This project estimates house selling prices based on factors like location, area, number of bedrooms, and more. The model is trained on a housing dataset and served using a simple Python backend.

📁 Project Structure  
bash  
Copy  
Edit  
house-price-prediction/  
│  
├── House Price Prediction Dataset.csv      # Dataset used for training  
├── house_price_prediction.ipynb            # Jupyter notebook for model building  
├── house_price_model.pkl                   # Trained ML model (Pickle file)  
├── houseprice.py                           # Python backend for predictions (Flask or Streamlit)  
├── requirements.txt                        # Python dependencies  
└── README.md                               # Project documentation  

✅ Features  
- Data cleaning and preprocessing  
- Feature engineering (encoding, handling missing values)  
- Model training and evaluation  
- Deployment-ready prediction script  
- Interactive prediction UI using Streamlit or Flask  

📊 Dataset Overview  
This dataset contains the following features:  

🏙️ Location  

📐 Area (sqft)  

🛏️ Number of Bedrooms  

🛁 Number of Bathrooms  

🏷️ Price (Target variable)  

🧠 Technologies Used  
Python (Pandas, NumPy, Scikit-learn)  

Jupyter Notebook  

Machine Learning: Linear Regression  

Model Serialization: pickle  

Web Framework: Streamlit or Flask  

⚙️ How to Run  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/Ayush9227/house-price-prediction.git  
   cd house-price-prediction  
   ```  
2. Install dependencies:  
   ```bash  
   pip install -r requirements.txt  
   ```  
3. Run the app:  
   If using Flask:  
   ```bash  
   python houseprice.py  
   ```  
   If using Streamlit:  
   ```bash  
   streamlit run houseprice.py  
   ```  
4. Make predictions:  
   Enter house features in the UI (area, location, BHK, etc.) to instantly get the predicted price.  

📈 Model Evaluation  
- Algorithm Used: Linear Regression  
- Metrics: MAE, RMSE  
- Performance: Evaluated on test split and cross-validation  

💡 Future Improvements  
- Enhance model accuracy using Random Forest or XGBoost  
- Add more features like amenities, parking, etc.  
- Deploy on platforms like Render, Heroku, or Streamlit Cloud  
🙋‍♂️ Author: Ayush Guha  
GitHub: Ayush9227  
