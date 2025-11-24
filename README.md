# Autism Therapy Progress Predictor
This model help us to keep a track of a autism patient for thier betterment and multiple medical purpose.

## Table of content
- [Features](#Features)
- [

## Getting Started
## 1. Features

### 1. Predicts Therapy Progress.
  * Model predicts how an autistic individual’s therapy is progressing based on given features.

###  2. Uses Two ML Algorithms
   * Linear Regression (baseline model)
   * Random Forest Regressor (advanced model)

### 3. Handles Categorical Data Automatically
   * The model converts labels like Autism_Diagnosis into numbers using Label Encoding

### 4. Learns Patterns From Realistic Data
   *  dataset contains 1000 realistic autism therapy records with features like:
      * Age
	  * Gender
	  * Symptom severity
	  * Family involvement
	  * Autism diagnosis
	  * Therapy hours
	  * etc.

### 5. Splits Data Into Train/Test Sets
  * Uses train_test_split to avoid overfitting and evaluate performance properly.

### 6. Generates Predictions for New Patients
  * Once trained, it can predict therapy progress for any new data entered.

### 7. Error Calculation & Model Scoring
  * Model uses:
	  * Mean Squared Error (MSE)
	  *	R² Score

### 8. Visualization Support
  * Created a scatter plot showing: Actual therapy progress vs Predicted therapy progress

### 9. Compares Two Models Head-to-Head
  * Project creates a table showing performance differences between:
    * Linear Regression
	 * Random Forest Regressor

### 10. Works on Real-World Social Problem
  * Helps identify therapy improvements in autistic individuals and assists:
	  * Parents
	  * Therapists
	  *	Clinics
	  *	Mental health researchers
##
## Technologies/tools used
  ### 1. Programming Language
  #### Python 3
  * Used for data processing, model building, visualization, and evaluation.

### 2. Libraries / Frameworks
#### Machine Learning
##### Scikit-Learn (sklearn) Used for:
  * Linear Regression
  * Random Forest Regressor
  * Train–test split
  * Label Encoding
  *	Evaluation metrics (MSE, R²)

#### 3.Data Handling
##### Pandas Used for:
  * Loading dataset
  * Cleaning
  * Feature selection
  * DataFrame operations
          
#### 4. Data Visualization
##### Matplotlib Used to create:
  * Scatter plot (Actual vs Predicted)

#### 5. Development Environment
##### Google Colab / Jupyter Notebook
  * Used to write and execute all Python code. 

#### 6. Tools for Documentation
##### Microsoft PowerPoint
  * For presentation (PPT).
##### Microsoft Word
  * For project documentation.
##### GitHub
  * For project hosting, version control, and code sharing.
    
#### 7. Model Building Tools
##### Linear Regression Model
  * Baseline predictive model.
##### Random Forest Regressor
  * Advanced ensemble model for better accuracy.   

#### 8. Supporting Tools 
##### LabelEncoder (Sklearn)
  * Converts categorical text/manual labels into numerical form.
##### Train-Test Split
  * For splitting data into training and testing sets.
##### Diagramming Tools
  * for system architecture & workflow

##
## 3. Steps to install & run the project
### 1. Download python3 on your system 
### 2. download lavi.py file
### 3. Run it and you are good to go...!

##
## 4. Instructions for Testing the Model
### Run the program 
### Read the FEATURE DISCRIPTION 
### Enter values and see the results

## Screenshots
<img width="846" height="823" alt="Screenshot 2025-11-24 at 10 41 45 PM" src="https://github.com/user-attachments/assets/6523fd73-ff42-49d5-8bc5-e653cbf5a220" />

<img width="846" height="823" alt="Screenshot 2025-11-24 at 10 42 07 PM" src="https://github.com/user-attachments/assets/c499ceb4-20e5-487c-b100-10d019c0f64f" />


