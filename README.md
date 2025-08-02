# Titanic Data Science Project

A comprehensive data science project analyzing the famous Titanic dataset to predict passenger survival using machine learning techniques.

## Project Overview

This project uses the classic Titanic dataset from the Seaborn library to perform exploratory data analysis and build predictive models for passenger survival. The Titanic dataset is a popular choice for introductory data science projects as it contains rich passenger information including demographics, ticket details, and survival outcomes.

## Dataset Description

The Titanic dataset contains information about passengers aboard the RMS Titanic, including:

- **survived**: Survival status (0 = No, 1 = Yes)
- **pclass**: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- **sex**: Gender of passenger
- **age**: Age in years
- **sibsp**: Number of siblings/spouses aboard
- **parch**: Number of parents/children aboard
- **fare**: Passenger fare
- **embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)
- **class**: Passenger class (First, Second, Third)
- **who**: Person category (man, woman, child)
- **adult_male**: Boolean indicating if passenger is adult male
- **deck**: Deck level
- **embark_town**: Full name of embarkation port
- **alive**: Survival status (yes/no)
- **alone**: Boolean indicating if passenger was traveling alone

## Current Project Status

### ✅ Completed Tasks

1. **Project Initialization**
   - Created Jupyter notebook (`ai - titanic data.ipynb`)
   - Set up repository structure
   - Configured Python environment with required dependencies

2. **Dataset Loading Implementation**
   - Successfully loaded Titanic dataset from Seaborn library
   - Implemented data loading in structured notebook cells
   - Verified dataset structure with 891 rows and 15 columns

3. **Initial Data Exploration**
   - Displayed first 5 rows of dataset using `head()` method
   - Confirmed dataset integrity and structure
   - Made data available for analysis as `titanic_df` DataFrame

## Technical Setup

### Environment Configuration
- **Python Version**: 3.7.2
- **Environment**: Virtual environment (`.venv`)
- **Jupyter Kernel**: Properly configured and running

### Dependencies
- **Seaborn**: For dataset loading and statistical visualization
- **Pandas**: Automatically included with Seaborn for data manipulation
- **NumPy**: Automatically included for numerical operations

### Installation & Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/BustinJiever/Titanic_data_science_test.git
   cd Titanic_data_science_test
   ```

2. **Set up virtual environment**:
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
   ```

3. **Install dependencies**:
   ```bash
   pip install seaborn scikit-learn jupyter
   ```

4. **Launch Jupyter Notebook**:
   ```bash
   jupyter notebook
   ```

5. **Open the analysis notebook**:
   - Navigate to `ai - titanic data.ipynb`
   - Run all cells to load and explore the dataset

## Project Structure

```
Titanic_data_science_test/
├── ai - titanic data.ipynb    # Main analysis notebook
├── README.md                  # Project documentation
└── .git/                      # Git repository files
```

## Next Steps for Analysis

The project is now ready for comprehensive data science analysis. Recommended next phases include:

### Phase 1: Exploratory Data Analysis (EDA)
- [ ] Generate statistical summaries of all variables
- [ ] Analyze missing data patterns and distributions
- [ ] Create comprehensive data visualizations
- [ ] Identify correlations between variables and survival

### Phase 2: Data Preprocessing
- [ ] Handle missing values (age, deck, embarked)
- [ ] Encode categorical variables
- [ ] Feature scaling and normalization
- [ ] Create new engineered features

### Phase 3: Data Visualization
- [ ] Survival rate analysis by passenger class
- [ ] Age and gender distribution visualizations
- [ ] Fare distribution and its relationship to survival
- [ ] Embarkation port analysis
- [ ] Family size impact on survival

### Phase 4: Machine Learning Model Development
- [ ] Split data into training and testing sets
- [ ] Implement baseline models (Logistic Regression, Decision Trees)
- [ ] Advanced models (Random Forest, Gradient Boosting, SVM)
- [ ] Model evaluation and comparison
- [ ] Hyperparameter tuning

### Phase 5: Model Evaluation & Insights
- [ ] Cross-validation and performance metrics
- [ ] Feature importance analysis
- [ ] Model interpretation and insights
- [ ] Final recommendations and conclusions

## Data Science Methodology

This project follows the standard data science methodology:

1. **Business Understanding**: Predict passenger survival on the Titanic
2. **Data Understanding**: Explore the Titanic dataset structure and quality
3. **Data Preparation**: Clean and prepare data for modeling
4. **Modeling**: Build and evaluate predictive models
5. **Evaluation**: Assess model performance and select best approach
6. **Deployment**: Present findings and actionable insights

## Expected Outcomes

By the end of this project, we aim to:
- Achieve >80% accuracy in survival prediction
- Identify key factors that influenced survival rates
- Provide insights into historical patterns and social dynamics
- Demonstrate proficiency in end-to-end data science workflow

## Contributing

This project is part of a data science learning initiative. Contributions, suggestions, and improvements are welcome through pull requests and issues.

## License

This project is for educational purposes. The Titanic dataset is publicly available through the Seaborn library.

---

**Last Updated**: Current as of latest commit
**Project Status**: Foundation complete, ready for comprehensive analysis