# Salary Estimation App

A **Streamlit web application** for predicting customer salaries using a pre-trained TensorFlow model based on the Churn Modelling Dataset.

## Features
- Predicts salary based on customer details.
- Interactive and user-friendly interface.
- Scalable preprocessing pipeline with encoders and scalers.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Anaspro72/salary-estimation-app.git
   cd salary-estimation-app
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Add model and preprocessing files to the root:
   - `model.h5`
   - `onehot_encoder_geo.pkl`
   - `gender_encoder.pkl`
   - `scaler.pkl
   - `app.py
   - `main.ipynb
     

4. Run the app:
   ```bash
   streamlit run app.py
   ```

## Inputs
- **Geography**: Select country (e.g., France, Germany).
- **Gender**: Male or Female.
- **Age**: 20–100 years.
- **Balance**: Account balance.
- **Credit Score**: Customer credit score.
- **Tenure**: Years with the bank.
- **Products**: Number of products used.
- **Has Credit Card**: Yes/No.
- **Is Active Member**: Yes/No.
- **Exited**: Yes/No.

## Output
- Displays the estimated salary based on user inputs.


## License
Licensed under the MIT License.
