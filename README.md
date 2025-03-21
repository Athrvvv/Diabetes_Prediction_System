# Diabetes Prediction System 🩺  
**Diabetes Prediction System** is a machine learning project that uses a **Naive Bayes classification model** to predict the likelihood of diabetes based on user inputs. The system processes medical data, applies predictive analysis, and provides results via a **Flask web application**.

## Why Naive Bayes?  
**Naive Bayes** is ideal for medical predictions due to its simplicity and efficiency. It calculates the **probability of diabetes** by analyzing input features independently, ensuring quick and accurate predictions.

## Features  
- **Machine Learning Model**: Trained using Naive Bayes on medical data.  
- **Web Interface**: Flask-based UI for entering data and viewing results.  
- **Pickle Model Deployment**: Pre-trained model stored and loaded via `model.pkl`.  
- **Data Processing**: Pandas and NumPy for handling and transforming data.  

## Technologies Used  
- **Python**  
- **Flask**  
- **Scikit-learn**  
- **Pandas, NumPy**  
- **Jupyter Notebook**  

## Installation & Setup  
1. Clone the repository:  
   ```bash
   git clone https://github.com/Athrvvv/Diabetes_Prediction_System.git
   cd Diabetes_Prediction_System
   ```
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Flask app:  
   ```bash
   python app.py
   ```

## Usage  
- Open `diabetes_model.ipynb` to analyze data and retrain the model if needed.  
- Run `app.py` to launch the web application and interact with the prediction system.  
- Input relevant medical data to receive a **diabetes prediction**.  

## Dataset  
The dataset used contains **medical attributes** such as glucose levels, BMI, and insulin, which are used by the model to predict diabetes.  

## Future Enhancements  
- Add more advanced models for comparison.  
- Deploy on cloud platforms for wider accessibility.  
- Enhance UI for better user experience.  

## Contact  
For queries or suggestions, open an issue in the repository.

