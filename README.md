# Netflix Data Analysis Using Python
## Auspify Technologies – Internship Project

### Project overview
This project analyzes the supplied Netflix dataset using Python. It follows the six tasks in the Auspify Technologies **Data Analysis Using Python Task List** PDF.

The PDF says interns must complete any 4 out of 6 tasks. This repository includes code for all six tasks for additional practice.

### Dataset
- File: `Dataset.csv`
- Rows: 8,790
- Columns: 10
- Columns: show_id, type, title, director, country, date_added, release_year, rating, duration, listed_in

The dataset contains Netflix title metadata such as content type, title, director, country, date added, release year, rating, duration and genres (`listed_in`).

### Tasks covered
1. **Netflix Data Cleaning & Preparation** – inspect missing values, normalize text, remove duplicates, standardize types and export cleaned data.
2. **Content Type Analysis Dashboard** – count Movies and TV Shows, compare proportions and visualize distribution.
3. **Country-Wise Netflix Content Analysis** – split multiple country values, calculate country counts, rank countries and compare content types.
4. **Trend Analysis by Release Year** – calculate yearly title counts, visualize trends and compare Movies with TV Shows.
5. **Content Rating & Genre Analysis** – analyze rating categories, genre counts and content-type comparisons.
6. **Netflix Business Insights Report** – calculate KPIs, create charts and export evidence-based findings.

### Tools and libraries
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

### How to run
1. Download or clone this repository.
2. Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

3. Open Jupyter Notebook:

```bash
jupyter notebook
```

4. Open `notebooks/Netflix_Data_Analysis.ipynb`.
5. Run cells from top to bottom. The notebook expects `Dataset.csv` in the project root folder.

### Project structure

```text
Netflix_Data_Analysis_Python/
├── Dataset.csv
├── notebooks/
│   └── Netflix_Data_Analysis.ipynb
├── reports/
│   └── (generated CSV reports and charts)
├── screenshots/
│   └── (add screenshots of completed tasks)
└── README.md
```

### Important analysis notes
- Missing values and placeholder text are checked separately. The notebook does not invent values for missing director, country or rating fields.
- A title can contain multiple countries or genres. Therefore country and genre counts represent title-category records, not unique global title counts.
- `release_year` is the original release year, not the date Netflix added the title. The notebook also provides an optional `date_added` trend.
- This dataset contains title metadata. It does not contain viewing hours, customer preferences, revenue or profitability, so conclusions about those topics are not supported.

### Deliverables
The notebook exports cleaned data and analysis reports into the `reports/` folder, including:
- `Netflix_KPI_Summary.csv`
- `Netflix_Business_Insights.csv`
- `Country_Wise_Content_Count.csv`
- `Genre_Wise_Content_Count.csv`
- `Release_Year_Trend.csv`
- PNG charts for the tasks

### Internship submission reminder
According to the task PDF, prepare:
- Project source code
- Screenshots of completed tasks
- GitHub repository link (if available)
- Optional project demonstration video

### Credits
Prepared as a learning project based on the Auspify Technologies Data Analysis Using Python internship task list. Review the outputs and write your own final interpretation before submission.
