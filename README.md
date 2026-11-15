# Data Analytics Case Studies

Portfolio case studies covering the full analysis workflow: cleaning raw data, exploring it with SQL, preparing it for visualization in Tableau, and running a correlation analysis in Python.

## Projects

### 1. COVID-19 Analysis (SQL → Tableau)

Exploration of global COVID-19 data on cases, deaths and vaccinations.

| File | What it does |
|---|---|
| `Portofolio_Project Data_Exploration_SQLQuery.sql` | Explores the data: infection and death rates by country and continent, and vaccination progress over time |
| `Portofolio_Project_Tableau_SQLQuery.sql` | Queries that shape the data into tables for the Tableau dashboard |

**Dashboard:** [COVID-19 Dashboard on Tableau Public](https://public.tableau.com/app/profile/chris1868/viz/CovidDashboard_16219986910350/Dashboard1)

**SQL techniques used:** joins, aggregate functions, `GROUP BY`, CTEs, temp tables, window functions, views and data-type conversions. *(Edit this list to match what you actually used.)*

**Key findings:** *(Add 2–3 bullet points, e.g. which countries had the highest infection rate relative to population.)*

### 2. Data Cleaning in SQL

| File | What it does |
|---|---|
| `Data_Cleaning_Project SQLQuery3.sql` | Cleans a raw dataset: standardizing date formats, filling missing values, splitting columns, removing duplicates and dropping unused columns |

"Nashville housing data"

### 3. Movie Correlation Analysis (Python)

| File | What it does |
|---|---|
| `Movie Correlation Project.ipynb` | Explores which factors correlate with a movie's gross revenue, such as budget, votes and score |

**Tools:** pandas, NumPy, Matplotlib and Seaborn 

**Key finding:** *(e.g. "Budget and votes had the strongest correlation with gross revenue.")*

## Tools

SQL (Microsoft SQL Server) · Tableau · Python (Jupyter, pandas)

## How to use

1. Clone the repo: `git clone https://github.com/Christos005/Data_Analytics_Case_Studies.git`
2. **SQL:** load the dataset into a database, then open the `.sql` files in SQL Server Management Studio (or another SQL client) and run them in order: cleaning, then exploration, then the Tableau queries.
3. **Python:** `pip install pandas numpy matplotlib seaborn notebook`, then open the `.ipynb` file in Jupyter.

---
**Author:** Christos Georgoudis · [GitHub](https://github.com/Christos005)
