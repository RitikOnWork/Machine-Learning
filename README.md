# 🚀 100 Days of Machine Learning Challenge

Welcome to my personal **100 Days of Machine Learning** learning journey! This repository serves as a structured, hands-on log of my daily progress as I build, preprocess, analyze, and train models, mastering concepts ranging from basic data ingestion to advanced machine learning pipelines.

---

## 📅 Roadmap & Progress Tracker

Below is an interactive roadmap detailing the modules completed so far. Click on the module names or notebook files to view the source code.

| Days / Module | Topic Description | Core Tools & Libraries | Source Code / Notebook |
| :--- | :--- | :--- | :--- |
| **01. Data Ingestion (CSV)** | Deep dive into importing and configuring raw tabular data with various encoding, custom indexing, separator variations, and memory-saving chunking methods. | `pandas`, CSV, TSV | 📓 [working-with-csv.ipynb](file:///e:/ML_Workbench/Machine%20Learning/1.%20Working%20with%20CSV%20Files/working-with-csv.ipynb) |
| **02. Data Ingestion (JSON & SQL)** | Handling nested JSON files, working with JSON structures, and querying relational database engines (SQL) directly into Pandas. | `pandas`, SQL, JSON | 📓 [WorkingonJsonandSql.ipynb](file:///e:/ML_Workbench/Machine%20Learning/2.%20Working%20with%20Json%20and%20Sql/WorkingonJsonandSql.ipynb) |
| **03. API Data Gathering** | Programmatically retrieving live records from web endpoints (using TMDB Movie API) and parsing the payloads into a structured dataframe. | `requests`, `pandas` | 📓 [day17.ipynb](file:///e:/ML_Workbench/Machine%20Learning/3.%20API%20To%20Dataframe/day17.ipynb) |
| **04. Web Scraping Data** | Mining and extracting structured tables from web pages (scraping AmbitionBox company listings) to build custom datasets from scratch. | `BeautifulSoup`, `requests` | 📓 [day18.ipynb](file:///e:/ML_Workbench/Machine%20Learning/4.%20Pandas-Dataframe-Using-Web-Scraping/day18.ipynb) |
| **05. Exploratory Data Analysis** | Essential descriptive statistical checklists (shape, missing values, duplicates, mathematically describing distributions, correlation maps) using the Titanic dataset. | `pandas`, `numpy` | 📓 [Understanding_Your_Data_Descriptive_Stats.ipynb](file:///e:/ML_Workbench/Machine%20Learning/5.%20Understanding%20Your%20Data%20Descriptive%20Stats/Understanding_Your_Data_Descriptive_Stats.ipynb) |
| **06. Categorical Encoding** *(In Progress)* | Feature engineering techniques to transform non-numerical categorical labels into machine-readable numbers (One-Hot, Ordinal, Label encoding). | *Upcoming Preprocessing* | 📂 [Encoding Directory](file:///e:/ML_Workbench/Machine%20Learning/Encoding) |
| **07. Feature Scaling** | Normalization & Standardization (Z-score Scaling) implementations using Scikit-Learn, with density plotting to visualize feature distribution shifts. | `scikit-learn`, `seaborn` | 📓 [Standardization.ipynb](file:///e:/ML_Workbench/Machine%20Learning/Feature_Scaling/Standardization.ipynb) |

---

## 📂 Repository Structure

Below is the directory tree of this repository:

```text
Machine Learning/
├── 📁 1. Working with CSV Files/
│   ├── 📓 working-with-csv.ipynb
│   └── 📊 [Datasets: IPL Matches, aug_train, movie_titles, zomato, test]
├── 📁 2. Working with Json and Sql/
│   ├── 📓 WorkingonJsonandSql.ipynb
│   └── 📊 train.json
├── 📁 3. API To Dataframe/
│   ├── 📓 day17.ipynb
│   └── 📊 movies.csv (TMDB API Output)
├── 📁 4. Pandas-Dataframe-Using-Web-Scraping/
│   └── 📓 day18.ipynb
├── 📁 5. Understanding Your Data Descriptive Stats/
│   ├── 📓 Understanding_Your_Data_Descriptive_Stats.ipynb
│   └── 📊 train.csv (Titanic Dataset)
├── 📁 Encoding/ [Categorical preprocessing placeholder]
├── 📁 Feature_Scaling/
│   ├── 📓 Standardization.ipynb
│   └── 📊 Social_Network_Ads.csv
└── 📄 README.md
```

---

## 🛠️ Topic Deep-Dives

### 1. [Working with CSV Files](file:///e:/ML_Workbench/Machine%20Learning/1.%20Working%20with%20CSV%20Files)
* **Objective:** Learn advanced operations with CSV and TSV files.
* **Key Operations:** Handling custom separators, naming non-header files, utilizing specific column filters, managing encoding issues, repairing bad rows, parsing custom datetime columns, and memory optimization using chunk sizes for large-scale datasets.

### 2. [Working with JSON and SQL](file:///e:/ML_Workbench/Machine%20Learning/2.%20Working%20with%20Json%20and%20Sql)
* **Objective:** Ingest data from modern web and database formats.
* **Key Operations:** Loading semi-structured JSON records, flattening hierarchical structures, and writing SQL database connectors to load records seamlessly into local DataFrames using relational query structures.

### 3. [API To Dataframe](file:///e:/ML_Workbench/Machine%20Learning/3.%20API%20To%20Dataframe)
* **Objective:** Gather programmatic web data.
* **Key Operations:** Querying endpoints using HTTP requests (`requests` library), parsing responses into dynamic dictionaries, handling pagination via custom looping, and flattening payloads into a single persistent dataset (`movies.csv`).

### 4. [Pandas-Dataframe-Using-Web-Scraping](file:///e:/ML_Workbench/Machine%20Learning/4.%20Pandas-Dataframe-Using-Web-Scraping)
* **Objective:** Extract data from HTML structures where APIs are unavailable.
* **Key Operations:** Emulating modern user-agents, navigating DOM elements using CSS class/id queries via `BeautifulSoup`, extracting text tables from AmbitionBox, and transforming scraped strings into lists to compile custom features.

### 5. [Understanding Your Data Descriptive Stats](file:///e:/ML_Workbench/Machine%20Learning/5.%20Understanding%20Your%20Data%20Descriptive%20Stats)
* **Objective:** Run a 7-step checklist to understand any new dataset mathematically.
* **Key Operations:** Analyzing dataframe dimensions (`shape`), previewing distributions (`sample`), examining columns and datatypes (`info`), checking for missing features (`isnull`), computing descriptive mathematical statistics (`describe`), checking duplicate records, and exploring cross-feature correlations (`corr`).

### 6. [Feature Scaling (Standardization)](file:///e:/ML_Workbench/Machine%20Learning/Feature_Scaling)
* **Objective:** Scale datasets to improve model convergence speed and avoid distance bias.
* **Key Operations:** Split data into Train and Test partitions (`train_test_split`), scale age and estimated salary distributions using Scikit-Learn's `StandardScaler` (Z-score normalization), and visualize pre/post-scaled distributions using KDE density plots with Seaborn.

---

## ⚙️ Tech Stack & Requirements

The notebooks are implemented using Python and standard scientific computing packages:

* **Core Libraries:** `pandas`, `numpy`
* **Web Scraping & APIs:** `requests`, `beautifulsoup4`, `lxml`
* **Machine Learning & Preprocessing:** `scikit-learn`
* **Data Visualization:** `matplotlib`, `seaborn`

### Quick Setup & Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/RitikOnWork/Machine-Learning.git
   cd Machine-Learning
   ```

2. **Create a virtual environment (optional but recommended):**
   ```bash
   python -m venv venv
   # On Windows:
   .\venv\Scripts\activate
   # On macOS/Linux:
   source venv/bin/activate
   ```

3. **Install the dependencies:**
   ```bash
   pip install pandas numpy requests beautifulsoup4 scikit-learn matplotlib seaborn lxml notebook
   ```

4. **Launch Jupyter notebook:**
   ```bash
   jupyter notebook
   ```

---

## 📈 Future Milestones
- [ ] Complete categorical feature encoding notebooks (`Encoding/` directory).
- [ ] Implement Outlier Detection and Handling.
- [ ] Implement Feature Transformation (Log, Box-Cox, Yeo-Johnson transforms).
- [ ] Build baseline Supervised Learning models (Linear Regression, Logistic Regression, Decision Trees).

*Keep learning, keep coding!* 💻🔥