# Laptop Price Predictor

Machine learning project for predicting laptop prices from hardware specifications with a Streamlit web interface.

## Features

* Predict laptop prices based on specifications
* User-friendly Streamlit web interface
* Supports different brands, RAM sizes, CPUs, GPUs, storage types, and screen resolutions
* Built using Machine Learning and deployed as a web application

## Technologies Used

* Python
* NumPy
* Pandas
* Scikit-learn
* XGBoost
* Streamlit
* Pickle

## Project Structure

laptop-price-predictor/
├── app.py
├── df.pkl
├── laptop-price-predictor.ipynb
├── laptop_data.csv
├── pipe.pkl
├── requirements.txt
├── .gitignore
└── README.md

## Installation

1. Clone the repository:
   git clone https://github.com/vaibhavvala10-commits/laptop-price-predictor.git

2. Move into the project directory:
   cd laptop-price-predictor

3. Install dependencies:
   pip install -r requirements.txt

4. Run the application:
   streamlit run app.py

## Usage

1. Select laptop specifications:

   * Brand
   * Type
   * RAM
   * Weight
   * Touchscreen
   * IPS Display
   * Screen Size
   * Screen Resolution
   * CPU
   * HDD
   * SSD
   * GPU
   * Operating System

2. Click **Predict Price** to get the estimated laptop price.

## Author

Vaibhav Vala
