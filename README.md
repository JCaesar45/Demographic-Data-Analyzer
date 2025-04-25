### 📄 `README.md`

```markdown
# Demographic Data Analyzer

This project is part of the freeCodeCamp Data Analysis with Python curriculum.  
It uses the 1994 U.S. Census dataset to perform various demographic data analyses using **Pandas**.

## 📊 Dataset

The dataset used is `adult.data.csv`, originally from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/adult).  
It contains demographic and income data for over 30,000 individuals.

## 🔍 What the Script Analyzes

The `calculate_demographic_data()` function answers the following questions:

1. How many of each race are represented?
2. What is the average age of men?
3. What percentage of people have a Bachelor's degree?
4. What percentage of people with advanced education (Bachelors, Masters, Doctorate) earn >50K?
5. What percentage without advanced education earn >50K?
6. What is the minimum number of work hours per week?
7. What percentage of people who work the minimum hours earn >50K?
8. What country has the highest percentage of rich people (>50K)?
9. What is the most common high-income occupation in India?

## 📁 Project Structure

```
.
├── adult.data.csv
├── demographic_data_analyzer.py
├── main.py
├── test_module.py
└── README.md
```

## ▶️ How to Run

Make sure you have Python installed (3.7 or higher recommended).

1. Install dependencies:
   ```bash
   pip install pandas
   ```

2. Run the main script:
   ```bash
   python main.py
   ```

3. (Optional) Run unit tests:
   ```bash
   python -m unittest test_module.py
   ```

## ✅ Requirements

- Python 3.x
- pandas

Install requirements with:
```bash
pip install -r requirements.txt
```

## 👨‍💻 Author

Developed by [Your Name Here] as part of the freeCodeCamp Data Analysis Certification.

```

---
