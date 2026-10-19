# StudentPerformancePrediction-ML
# Student Performance Prediction Using Machine Learning

## 📌 About the Project

Student Performance Prediction Using Machine Learning is a Python-based project that analyzes student academic data to identify performance patterns and classify students into different performance categories. The project uses data analysis, visualization, and machine learning classification techniques to explore the factors associated with student academic performance.

The system works with a CSV dataset containing student-related information, including demographic details, academic characteristics, classroom participation, learning activities, and student absence records. Data visualization techniques are used to understand the distribution of student performance across different categories and identify relationships between numerical variables.

The project implements multiple machine learning classifiers and compares their classification performance using evaluation metrics. It also includes an interactive, menu-driven visualization interface and an option to test individual inputs to obtain predictions from the trained models.

## 🎯 Objectives

- Analyze student academic data to understand performance patterns.
- Visualize student performance across different academic and demographic categories.
- Explore relationships between numerical features using a correlation heatmap.
- Implement and compare multiple machine learning classification algorithms.
- Evaluate model predictions using classification reports and accuracy scores.
- Demonstrate how machine learning can support the analysis of educational data.

## ⚙️ Key Features

- **Data Analysis:** Processes student information from a CSV dataset.
- **Correlation Heatmap:** Visualizes correlations between numerical variables.
- **Interactive Visualizations:** Generates graphs showing student performance by semester, gender, nationality, grade, section, topic, stage, and absence days.
- **Multiple ML Models:** Implements Decision Tree, Random Forest, Perceptron, Logistic Regression, and Multi-Layer Perceptron (MLP) classifiers.
- **Model Evaluation:** Displays classification reports and accuracy scores to help compare model performance.
- **Prediction Interface:** Accepts user input through the terminal and generates predictions using the trained classifiers.

## 🧠 Machine Learning Algorithms

The project uses the following classification algorithms:

1. **Decision Tree Classifier** – Classifies student performance using decision-based rules.
2. **Random Forest Classifier** – Uses an ensemble of decision trees to make predictions.
3. **Perceptron** – Applies a linear classification approach.
4. **Logistic Regression** – Estimates class membership using a linear classification model.
5. **Multi-Layer Perceptron (MLP)** – Uses a neural network-based classification approach.

The models are evaluated using classification reports and accuracy measurements. Their actual performance depends on the dataset, preprocessing, feature selection, and training configuration.

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Data Processing:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn
- **Dataset Format:** CSV

## 📂 Project Structure

```text
StudentPerformancePrediction-ML/
├── AI-Data.csv
├── Project.py
├── requirements.txt
├── README.md
└── .gitignore
```

## 🚀 Installation and Setup

### Prerequisites

Install Python and Git on your computer before proceeding.

### Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/Student-Performance-Prediction-ML.git
```

Replace `YOUR-USERNAME` with your GitHub username and use your actual repository name.

### Step 2: Navigate to the Project Folder

```bash
cd Student-Performance-Prediction-ML
```

### Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 4: Run the Project

```bash
python Project.py
```

Ensure that `AI-Data.csv` is located in the same directory as `Project.py`.

## 📊 Expected Output

When executed, the project provides:

- A correlation heatmap of numerical dataset features.
- A menu to generate student performance distribution graphs.
- Classification reports for the implemented machine learning models.
- Accuracy scores for model evaluation.
- An optional terminal-based input interface for generating predictions.

## 🔮 Applications

This project demonstrates how machine learning can be applied to educational data analysis, student performance classification, academic pattern exploration, and educational data mining.

It serves as an academic learning project for understanding data preprocessing, visualization, classification algorithms, and model evaluation.

## ⚠️ Limitations

The predictions depend on the quality and representativeness of the dataset. The current implementation uses a fixed subset of selected features, and its reported accuracy should not be interpreted as proof of general performance on unseen student populations. Further improvements could include more robust preprocessing, stratified train-test splitting, cross-validation, hyperparameter tuning, and a more user-friendly interface.

## 👩‍💻 Project Purpose

This project was developed to explore the practical application of Python and machine learning techniques in educational data analysis and student performance prediction.

**Note:** The project provides experimental predictions for learning and analysis purposes and should not be used as the sole basis for important educational decisions.
