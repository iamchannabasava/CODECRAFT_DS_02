# README

## Data Cleaning and Exploratory Data Analysis (EDA) Script

This project involves performing data cleaning and exploratory data analysis (EDA) on a dataset named `age_gender.csv`. The analysis includes detecting duplicates, summarizing data, and visualizing distributions of key variables like age, gender, and ethnicity.

---

### Prerequisites

To run this script, ensure you have the following installed:

1. **Python 3.6+**
2. Required Python libraries:
   - `pandas`
   - `matplotlib`

Install the necessary libraries using:

```bash
pip install pandas matplotlib
```

---

### Dataset

The dataset used in this analysis should have the following columns:

1. **age**: The age of individuals (numeric).
2. **ethnicity**: Encoded ethnicity values (categorical).
3. **gender**: Encoded gender values (0 for male, 1 for female).
4. **img\_name**: Names of the associated image files (string).
5. **pixels**: String representation of pixel intensity values (string).

---

### Steps in the Script

1. **Load the Dataset**:

   - The script reads the dataset using Pandas.

2. **Data Cleaning**:

   - Check for duplicate rows in the dataset.
   - Summarize numerical columns for basic statistics.
   - Identify unique values in categorical columns (`ethnicity`, `gender`).

3. **Data Visualization**:

   - Visualize the distribution of `age` using a histogram.
   - Visualize the distribution of `gender` using a bar plot.
   - Visualize the distribution of `ethnicity` using a bar plot.

---

### How to Use

1. Place the `age_gender.csv` file in the same directory as the script, or update the file path in the script.

2. Run the script using the command:

```bash
python script_name.py
```

Replace `script_name.py` with the name of your Python file.

3. View the outputs:
   - A summary of the dataset printed in the console.
   - Visualizations displayed as plots for age, gender, and ethnicity distributions.

---

### Example Output

#### Console Output:

- Number of duplicate rows: 0
- Statistical summary of numerical columns (e.g., mean, min, max).
- Unique values in categorical columns.

#### Plots:

1. Age distribution as a histogram.
2. Gender distribution as a bar plot.
3. Ethnicity distribution as a bar plot.

---

### Notes

- Ensure the dataset matches the expected structure described above.
- The script does not process the `img_name` or `pixels` columns; they are ignored for this analysis.
- Modify the script as needed for additional analysis or visualization.

---

### License

This project is provided under the MIT License. You are free to use, modify, and distribute the script as needed.

---

### Author

[Channabasava Mathapati](iamchannabasava25@gmail.com)

