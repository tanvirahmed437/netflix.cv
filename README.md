# 🎬 Netflix Titles Data Analysis

## 📌 Project Overview

This project explores a Netflix titles dataset using Python, Pandas, and Matplotlib. The goal is to understand the dataset, clean missing values, filter information, perform basic analysis, and visualize patterns in Netflix movies and TV shows.

For this project, only the first 300 rows of the dataset are used.

## 🎯 Objectives

* Load and explore the Netflix dataset.
* Understand rows, columns, and data types.
* Identify and handle missing values.
* Select specific rows and columns.
* Filter movies and TV shows based on conditions.
* Create new columns and manage indexes.
* Perform basic statistical analysis.
* Create different visualizations to understand the data.

## 🛠️ Technologies Used

* **Python** — Programming language
* **Pandas** — Data manipulation and analysis
* **Matplotlib** — Data visualization
* **Seaborn** — Heatmap visualization
* **Jupyter Notebook** — Writing and running code

## 📂 Dataset

**File:** `netflix_titles.csv`

The dataset contains information about Netflix titles, including:

* `show_id` — Unique ID of each title
* `type` — Movie or TV Show
* `title` — Name of the title
* `director` — Director's name
* `cast` — Cast members
* `country` — Country associated with the title
* `date_added` — Date the title was added to Netflix
* `release_year` — Year the title was released
* `rating` — Content rating
* `duration` — Movie duration or number of TV show seasons
* `listed_in` — Genre or category
* `description` — Short description of the title

**Note:** The analysis uses only the first 300 rows of the dataset.

## 📊 Data Analysis Performed

### 1. Data Loading and Exploration

* Loaded the CSV file using Pandas.
* Viewed the first and last rows.
* Checked the dataset shape, columns, and data types.
* Generated descriptive statistics.

### 2. Data Cleaning

* Identified missing values.
* Replaced missing values in the `director`, `country`, and `cast` columns with `"Unknown"`.
* Removed the `description` column for this analysis.

### 3. Data Manipulation

* Selected individual and multiple columns.
* Retrieved rows using `loc` and `iloc`.
* Created a new `Age` column using the formula `2026 - release_year`.
* Filtered titles released after 2018.
* Selected movies from the United States.
* Set and reset the DataFrame index.
* Explored Pandas Series operations.

### 4. Data Visualization

The project includes the following graphs:

| Visualization | Purpose                                                                                            |
| ------------- | -------------------------------------------------------------------------------------------------- |
| Histogram     | Understand the distribution of release years                                                       |
| Bar Chart     | Compare the number of movies and TV shows                                                          |
| Line Plot     | Observe release years across the first 30 titles                                                   |
| Scatter Plot  | Explore the relationship between title age and release year                                        |
| Box Plot      | Examine the spread of release years and identify potential outliers                                |
| Pie Chart     | Visualize the distribution of the top five country entries                                         |
| Area Plot     | Explore the number of titles grouped by release year                                               |
| Heatmap       | Compare movie and TV show counts across countries, or examine correlations between numeric columns |

### 5. Additional Analysis

* Counted movies and TV shows.
* Identified the most frequently listed countries.
* Found the oldest and newest release years represented in the selected data.
* Separated movies and TV shows into different DataFrames.
* Identified titles with unknown directors.

## 📈 Expected Outcomes

This project helps develop a basic understanding of:

* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* Pandas DataFrame and Series operations
* Boolean filtering and indexing
* Statistical summaries
* Data visualization
* Interpreting patterns in a real-world dataset

Actual findings depend on the contents of the dataset and the results produced when the notebook is executed.

## 🚀 How to Run the Project

1. Clone this repository:

   ```bash
   git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
   ```

2. Open the project folder:

   ```bash
   cd YOUR-REPOSITORY
   ```

3. Install the required libraries:

   ```bash
   pip install pandas matplotlib seaborn jupyter
   ```

4. Make sure `netflix_titles.csv` is in the correct project directory.

5. Open Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

6. Open your notebook and run the cells in order.

## 📁 Project Structure

```text
Netflix-Titles-Data-Analysis/
│
├── netflix_titles.csv
├── netflix_analysis.ipynb
└── README.md
```

*Replace `netflix_analysis.ipynb` with your actual notebook filename if it is different.*

## 🔮 Future Improvements

* Analyze the complete dataset instead of only 300 rows.
* Explore trends in movies and TV shows over time.
* Compare content across different countries.
* Analyze genres, ratings, and durations.
* Improve visualizations with additional insights.
* Build an interactive dashboard.

## 👨‍💻 Author

**Your Name**

GitHub: [Your GitHub Profile](https://github.com/YOUR-USERNAME)

## 📄 License

This project is intended for educational and learning purposes. Include the dataset's original source and applicable license information when distributing the dataset.
