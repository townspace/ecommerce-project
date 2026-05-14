# 🛒 Ecommerce Project

A Python-based **Exploratory Data Analysis (EDA)** project using pandas to analyse ecommerce purchase data. This project dives into customer transaction records to uncover purchasing patterns, demographic insights, and behavioural trends.

---

## 📌 Overview

Using a dataset of ecommerce purchases, this project applies pandas operations and data exploration techniques to answer real business questions — such as who is buying, what they are buying, and how they are paying. It is a practical exercise in data wrangling and analysis using Python.

---

## 📁 Repository Structure

```
ecommerce-project/
│
├── Ecommerce Purchases Exercise.ipynb   # Main notebook with full analysis
└── README.md                            # Project documentation
```

---

## 📊 Dataset

The dataset contains ecommerce purchase records with the following types of fields:

| Field | Description |
|-------|-------------|
| `Address` | Customer's address |
| `Lot` | Lot identifier |
| `AM or PM` | Time of purchase (morning or afternoon) |
| `Browser Info` | Browser used to make the purchase |
| `Company` | Customer's company |
| `Credit Card` | Credit card number used |
| `CC Exp Date` | Credit card expiry date |
| `CC Security Code` | Card security code |
| `CC Provider` | Credit card provider (Visa, Mastercard, etc.) |
| `Email` | Customer's email address |
| `Job` | Customer's job title |
| `IP Address` | Customer's IP address |
| `Language` | Browser/preferred language |
| `Purchase Price` | Price of the purchase |

---

## 🧪 What's Inside the Notebook

- **Data Loading** — Reading the dataset into a pandas DataFrame
- **Basic Exploration** — Inspecting shape, data types, and null values
- **Aggregations & Filtering** — Answering specific questions using pandas methods like `.value_counts()`, `.groupby()`, `.loc[]`, and `.apply()`
- **Purchase Price Analysis** — Finding highest, lowest, and average purchase prices
- **Language & Browser Breakdown** — Which languages and browsers are most common
- **Job & Company Insights** — Most common job titles and companies among customers
- **Credit Card Analysis** — Top CC providers and identifying soon-to-expire cards
- **Time-based Analysis** — Comparing AM vs PM purchase behaviour
- **Email Domain Extraction** — Parsing and analysing customer email providers

---

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- Jupyter Notebook or JupyterLab

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/townspace/ecommerce-project.git
   cd ecommerce-project
   ```

2. Install dependencies:
   ```bash
   pip install numpy pandas jupyter
   ```

3. Launch the notebook:
   ```bash
   jupyter notebook "Ecommerce Purchases Exercise.ipynb"
   ```

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core programming language |
| Jupyter Notebook | Interactive development environment |
| pandas | Data manipulation, filtering, and aggregation |
| NumPy | Numerical operations |

---

## 💡 Key Skills Demonstrated

- DataFrame creation and inspection
- Filtering and conditional selection with `.loc[]` and boolean masks
- String operations and `.apply()` for feature extraction
- Aggregation with `.groupby()` and `.value_counts()`
- Working with real-world messy data fields (emails, IPs, credit cards)

---

## 📬 Contact

Created by [@townspace](https://github.com/townspace) — feel free to raise an issue or get in touch!
