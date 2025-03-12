# Heart Disease Risk Prediction

This repository contains a Streamlit-based web application that predicts the risk of heart disease using a machine learning model.

## Features
- User-friendly web interface built with Streamlit
- Accepts user input for age, blood pressure, smoking habits, physical activity, diabetes levels, and alcohol consumption
- Uses a trained machine learning model to predict heart disease risk
- Displays results with warnings for high-risk cases

## Installation

### Prerequisites
- Python 3.x
- pip
- Git

### Steps
1. Clone this repository:
   ```sh
   git clone https://github.com/yourusername/heart-disease-prediction.git
   cd heart-disease-prediction
   ```
2. Create a virtual environment (optional but recommended):
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Running the App
1. Ensure you have the trained model and scaler files (`heart_model1.sav`, `heart_scalerf1.sav`) in the project directory.
2. Run the Streamlit app:
   ```sh
   streamlit run app.py
   ```
3. Open the link displayed in the terminal to access the app in your browser.

## File Structure
```
heart-disease-prediction/
│── app.py               # Main application script
│── heart_model1.sav     # Trained machine learning model
│── heart_scalerf1.sav   # Scaler for preprocessing inputs
│── requirements.txt     # Python dependencies
│── README.md            # Project documentation
```

## Technologies Used
- **Python**
- **Streamlit** (for UI)
- **scikit-learn** (for machine learning model)
- **Pandas & NumPy** (for data handling)
- **Pillow** (for image handling)

## Contributing
Feel free to open an issue or submit a pull request if you find any improvements or bugs.

## License
This project is open-source and available under the [MIT License](LICENSE).

