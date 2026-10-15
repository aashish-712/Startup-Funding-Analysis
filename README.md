# Indian Startup Funding Analysis Dashboard

A data analytics project built with Python and Streamlit to explore Indian startup funding data, analyze investment trends, and visualize funding patterns through an interactive dashboard.

## 📌 Project Overview

The **Indian Startup Funding Analysis Dashboard** transforms startup funding records into meaningful insights using data analysis and visualization.

The project uses Pandas for data manipulation, Matplotlib for charts, and Streamlit to build an interactive web application.

It is designed to explore funding amounts, startup activity, investment trends, and investor-related information in the Indian startup ecosystem.

## ✨ Features

- **Overall Funding Analysis** — View key funding metrics, including total funding, maximum funding, average funding per startup, and the number of unique startups.
- **Monthly Funding Trends** — Analyze month-on-month funding amounts and startup record counts.
- **Investor Analysis** — Explore investment records associated with selected investors.
- **Recent Investments** — View recent investment records with dates, startup names, sectors, cities, funding rounds, and amounts.
- **Investment Comparisons** — Visualize investment amounts across startups.
- **Funding Distribution** — Explore investment distribution by funding round, business sector, and city.
- **Year-on-Year Trends** — Examine changes in investment amounts over time.
- **Interactive Dashboard** — Navigate between analysis sections using Streamlit's sidebar.

## 🛠️ Technologies Used

- **Python** — Core programming language
- **Streamlit** — Interactive web application
- **Pandas** — Data cleaning, manipulation, and analysis
- **Matplotlib** — Data visualization
- **CSV** — Startup funding dataset storage

## 📂 Project Structure

```text
indian_website/
│
├── startup_dashboard_streamlit_app.py
├── startup_cleaned.csv
├── requirements.txt
├── README.md
├── helloworld.py
├── tem_df.py
└── test.py
```

## 🚀 Getting Started

Follow these steps to run the project on your local machine.

### 1. Clone the Repository

```bash
git clone https://github.com/aashish-712/indian_website.git
```

### 2. Navigate to the Project Directory

```bash
cd indian_website
```

### 3. Create a Virtual Environment (Recommended)

```bash
python -m venv venv
```

Activate the environment.

**Windows:**

```bash
venv\Scripts\activate
```

**macOS / Linux:**

```bash
source venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

### 5. Run the Application

```bash
streamlit run startup_dashboard_streamlit_app.py
```

Streamlit will provide a local URL in your terminal. Open that URL in your browser to access the dashboard.

## 📊 Dataset

The project uses `startup_cleaned.csv`, a CSV dataset containing startup funding records.

The dataset includes fields such as:

- `date` — Investment date
- `startup` — Startup name
- `vertical` — Business sector
- `subvertical` — More specific business category
- `city` — Startup location
- `investors` — Investor information
- `round` — Funding round
- `amount` — Funding amount

These fields are used to group, summarize, and visualize startup funding activity.

## 🎯 Learning Objectives

This project provides practical experience with:

- Data manipulation and aggregation using Pandas
- Working with dates and time-based data
- Grouping data and calculating summary statistics
- Creating charts with Matplotlib
- Building interactive dashboards with Streamlit
- Organizing Python projects and managing dependencies
- Turning raw data into visual insights

## 🔮 Future Improvements

- Add advanced filters for dates, sectors, cities, and funding rounds.
- Improve startup-specific analysis and comparisons.
- Add more detailed key performance indicators.
- Improve dashboard layout and chart readability.
- Deploy the application online so users can access it through a public URL.
- Add data validation and improve error handling.

## 👨‍💻 Author

**Aashish Bhandari**

GitHub: [@aashish-712](https://github.com/aashish-712)

## ⭐ Support

If you find this project useful, consider giving the repository a star on GitHub.

---

*Built as a hands-on project to practice Python, data analysis, and interactive dashboard development.*
