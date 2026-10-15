# 🚀 Startup Funding Analysis Dashboard

An interactive data analysis dashboard built with Python, Pandas, Matplotlib, and Streamlit to explore Indian startup funding trends and discover insights from investment data.

## 📌 About the Project

The startup ecosystem generates valuable data about investments, business sectors, locations, and investors. Analyzing this data can help us understand how funding is distributed and how investment activity changes over time.

**Startup Funding Analysis** is a data analytics project that transforms startup funding records into meaningful insights through data processing, statistical analysis, and interactive visualizations.

This project is part of my journey toward mastering Python, data analysis, and machine learning.

## ✨ Key Features

- 📊 **Overall Funding Analysis** — Explore key statistics such as total funding, average funding, and maximum funding.
- 📈 **Monthly Funding Trends** — Analyze changes in funding activity over time.
- 🏢 **Startup Analysis** — Explore investment records associated with individual startups.
- 💰 **Investor Analysis** — Examine investor activity and investment patterns.
- 🌍 **Sector and City Analysis** — Explore funding distribution across business sectors and locations.
- 📉 **Data Visualization** — Present insights through charts and graphical representations.
- 🖥️ **Interactive Dashboard** — Explore funding data through a Streamlit application.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Pandas | Data manipulation and analysis |
| Matplotlib | Data visualization |
| Streamlit | Interactive dashboard |
| CSV | Dataset storage |

## 📂 Project Structure

```text
Startup-Funding-Analysis/
│
├── startup_dashboard_streamlit_app.py
├── startup_cleaned.csv
├── requirements.txt
└── README.md
```

*Note: Update this structure if your actual repository contains different filenames.*

## ⚙️ Installation and Setup

Follow these steps to run the project locally.

### 1. Clone the Repository

```bash
git clone https://github.com/aashish-712/Startup-Funding-Analysis.git
```

### 2. Navigate to the Project Folder

```bash
cd Startup-Funding-Analysis
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

If you do not have a `requirements.txt` file, install the main libraries:

```bash
pip install streamlit pandas matplotlib
```

### 5. Run the Dashboard

```bash
streamlit run startup_dashboard_streamlit_app.py
```

Open the local URL displayed in your terminal to use the dashboard.

## 📊 Dataset

The project uses a CSV dataset containing Indian startup funding records.

Depending on the available columns, the dataset can support analysis of:

- Startup names
- Investment dates
- Funding amounts
- Business sectors
- Startup locations
- Investor information
- Funding rounds

The quality and completeness of these fields determine which analyses can be performed.

## 🎯 What I Learned

Through this project, I am developing practical skills in:

- Data cleaning and preprocessing
- Pandas filtering, grouping, and aggregation
- Exploratory data analysis (EDA)
- Working with dates and numerical data
- Data visualization
- Building interactive applications with Streamlit
- Organizing and documenting Python projects

## 🔮 Future Improvements

- Add more interactive filters.
- Improve dashboard design and user experience.
- Explore additional funding trends and investment patterns.
- Add more advanced statistical analysis.
- Deploy the dashboard online.
- Explore machine learning applications using startup funding data.

## 👨‍💻 Author

**Aashish Bhandari**

- GitHub: [@aashish-712](https://github.com/aashish-712)

## ⭐ Support

If you find this project interesting, consider giving the repository a star!

---

*Learning by building, analyzing data, and turning insights into interactive applications.*
