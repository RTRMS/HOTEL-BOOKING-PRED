# Hotel Booking Cancellation Prediction | Machine Learning

## Project Overview

This project focuses on predicting hotel booking cancellations using Machine Learning techniques.

Hotel cancellations create significant challenges for the hospitality industry, affecting revenue, room availability, and business planning.

The objective of this project is to analyze historical hotel booking data, identify patterns associated with cancellations, and build a predictive model that can help hotels make better business decisions.

## Project Objectives

- Analyze historical hotel booking data.
- Perform Exploratory Data Analysis (EDA).
- Identify important factors influencing booking cancellations.
- Clean and preprocess the dataset.
- Apply Machine Learning techniques.
- Build a predictive model to classify whether a booking will be canceled.
- Evaluate model performance.

## Repository Structure

```text
PYML/
│
├── ML_hotel_booking_Prediction.ipynb
├── ML_hotel_booking_Prediction-checkpoint.ipynb
├── hotel_bookings.csv
├── data_dictionary.txt
└── README.md
```

## Dataset

The project uses a hotel booking dataset containing historical reservation information.

The dataset includes information such as:

- Hotel type
- Lead time
- Arrival date
- Number of guests
- Number of previous cancellations
- Booking changes
- Deposit type
- Customer type
- Distribution channel
- Country
- Reservation status

**Target Variable:** `is_canceled`

- `0` – Booking was not canceled.
- `1` – Booking was canceled.

## Technologies & Tools

- Python – Programming language
- Pandas – Data manipulation and analysis
- NumPy – Numerical computations
- Matplotlib – Data visualization
- Seaborn – Statistical visualization
- Scikit-learn – Machine Learning and model evaluation
- Jupyter Notebook – Development environment

## Project Workflow

### 1. Data Collection

Loaded the hotel booking dataset and explored its structure.

### 2. Data Cleaning

- Checked for missing values.
- Identified duplicate records.
- Handled inconsistent data.
- Prepared data for analysis.

### 3. Exploratory Data Analysis (EDA)

Analyzed booking patterns and cancellation trends to understand the relationships between different variables.

### 4. Feature Engineering & Preprocessing

Prepared categorical and numerical variables for Machine Learning.

### 5. Model Building

Developed a Machine Learning classification model to predict booking cancellations.

### 6. Model Evaluation

Evaluated model performance using appropriate classification metrics.

## Business Impact

This project demonstrates how Machine Learning can help the hospitality industry:

- Identify bookings with a higher cancellation risk.
- Improve room inventory management.
- Support revenue management strategies.
- Improve reservation planning.
- Make data-driven business decisions.

## Installation & Execution

### Prerequisites

Install Python and Jupyter Notebook.

### Step 1: Clone the repository

```bash
git clone https://github.com/RTRMS/PYML.git
```

### Step 2: Navigate to the project directory

```bash
cd PYML
```

### Step 3: Install dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### Step 4: Launch Jupyter Notebook

```bash
jupyter notebook
```

### Step 5: Open the notebook

Open `ML_hotel_booking_Prediction.ipynb` and execute the cells sequentially.

## Key Learning Outcomes

- Data cleaning and preprocessing.
- Exploratory Data Analysis.
- Feature engineering.
- Classification using Machine Learning.
- Model evaluation.
- Applying Machine Learning to a real-world business problem.

## Author

**Roop Tej Rathod**

GitHub: https://github.com/RTRMS

---

If you find this project interesting, consider giving the repository a star.
