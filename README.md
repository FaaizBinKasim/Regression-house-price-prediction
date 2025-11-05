🏠 House Price Prediction

This is a simple machine learning web app built using Flask. It predicts house prices based on various input features using the Boston Housing dataset.

⚙️ How It Works

1. The dataset (BostonHousing.csv) is cleaned, normalized, and trained using Random Forest Regressor in houseprice.py.
2. The trained model is saved as model.pkl.
3. app.py uses Flask to create a web interface where users can input house features.
4. The model predicts the median house price (MEDV) and displays it on the web page.

📁 Project Structure

House_price/
│
├── app.py                Flask app for prediction
├── houseprice.py         Model training script
├── model.pkl             Trained ML model
├── scaling.pkl           Saved scaler
├── BostonHousing.csv     Dataset
├── requirement.txt       Python dependencies
├── static/               CSS or JS files (if any)
└── templates/
    └── index.html        Frontend HTML page

🧠 Steps to Run

1. Install Dependencies

   pip install -r requirement.txt

2. Train the Model (optional)

   python houseprice.py

3. Run the App

   python app.py

   Then open your browser and go to:

   http://127.0.0.1:5000/

🧰 Technologies Used

* Python
* Flask
* Scikit-learn
* Pandas
* NumPy
