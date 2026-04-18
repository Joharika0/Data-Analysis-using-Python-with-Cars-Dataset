# 🚗 Car Data Analysis using Python & Pandas

A hands-on data analysis project built in Python using a real-world Cars dataset. This project covers core data wrangling and analysis techniques including data cleaning, filtering, transformation, and exploration using the Pandas library.

---

## 📌 Project Overview

This project demonstrates practical data analysis skills applied to a Cars dataset. It walks through a series of structured tasks — from cleaning raw data to extracting meaningful insights — making it a great reference for anyone learning data analysis with Python.

---

## 🗂️ Dataset

- **File:** `Cars Data1.csv`
- **Domain:** Automobile
- **Key Columns:** `Make`, `Origin`, `Weight`, `MPG_City`, and more

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core programming language |
| Pandas | Data manipulation & analysis |
| Google Colab | Development environment |

---

## 📋 Tasks Covered

### 1. 🔍 Data Cleaning — Handling Null Values
- Identified all null/missing values in the dataset
- Filled missing **numeric** columns with their respective **column mean**
- Filled missing **categorical** columns with the **mode** (most frequent value)

### 2. 📊 Value Counts — Exploring Car Makes
- Explored all unique car `Make` entries in the dataset
- Counted the occurrences of each `Make` to understand brand distribution

### 3. 🌍 Filtering — Asia & Europe Origins
- Filtered the dataset to display only records where the car's `Origin` is **Asia** or **Europe**

### 4. ✂️ Removing Unwanted Records
- Removed all records where `Weight` exceeded **4000**, cleaning the dataset for focused analysis

### 5. ⚙️ Column Transformation — Applying Functions
- Increased all values in the `MPG_City` column by **3** using a lambda function

---

## 🚀 Getting Started

### Option 1: Run on Google Colab *(Recommended)*
1. Open the `.ipynb` file directly in [Google Colab](https://colab.research.google.com/)
2. Upload the `Cars Data1.csv` file when prompted
3. Run all cells sequentially

### Option 2: Run Locally
```bash
# Clone the repository
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

# Install dependencies
pip install pandas

# Launch Jupyter Notebook
jupyter notebook Data_Analysis_Project_using_Python_2.ipynb
```

> **Note:** If running locally, replace the Google Colab file upload block with:
> ```python
> car = pd.read_csv("Cars Data1.csv")
> ```

---

## 📁 Repository Structure

```
📦 Data-Analysis-using-Python-with-Cars-Dataset
 ┣ 📓 Data_Analysis_Project_using_Python_2.ipynb   # Main notebook
 ┣ 📄 2. Cars Data1.csv                                # Dataset
 ┗ 📄 README.md                                     # Project documentation
```

---

## 💡 Key Learnings

- Handling missing data with `fillna()` using mean and mode strategies
- Using `value_counts()` for categorical column exploration
- Filtering rows with `isin()` and Boolean masks
- Removing outliers or unwanted data using conditional filtering
- Applying transformations to columns using `apply()` and lambda functions

---

## 🙌 Acknowledgements

This project was completed as part of a Python Data Analysis learning exercise using a publicly available Cars dataset.

---

## 📬 Contact

Feel free to connect or raise an issue if you have suggestions or questions!
