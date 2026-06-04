# E-commerce Data Analysis & Executive Storytelling

## Overview

This project analyzes an E-commerce dataset through three main stages:

1. **Data Cleaning & Preprocessing**
2. **Exploratory Data Analysis (EDA)**
3. **Executive Data Storytelling**

The project transforms raw sales data into meaningful business insights and recommendations.

---

## Project Structure

```text
Ecommerce-Data-Analysis/
│
├── Untitled-1.ipynb
│   └── Data Cleaning & Feature Engineering
│
├── full_eda_notebook.ipynb
│   └── Exploratory Data Analysis (EDA)
│
├── executive_storytelling_notebook.ipynb
│   └── Business Storytelling & Recommendations
│
├── cleaned_ecommerce_data.csv
│   └── Cleaned Dataset
│
├── requirements.txt
│
└── README.md
```

---

## Dataset Features

The dataset includes:

- Product Information
- Quantity
- Unit Price
- Payment Method
- Order Status
- Coupon Code
- Referral Source
- Total Price
- Date Features

---

## Stage 1 — Data Cleaning

Performed preprocessing tasks including:

- Removing irrelevant columns
- Handling missing values
- Replacing missing coupon codes with `NoCoupon`
- Feature engineering from dates:
  - Month
  - DayOfWeek
  - IsWeekend
- Duplicate checking

---

## Stage 2 — Exploratory Data Analysis (EDA)

The EDA explored:

### Customer Behavior
- Purchase patterns
- Cart size analysis

### Product Analysis
- Best-selling products

### Payment Analysis
- Customer payment preferences

### Coupon Analysis
- Coupon effectiveness

### Referral Source Analysis
- Marketing performance

### Time Analysis
- Weekday vs Weekend spending

---

## Stage 3 — Executive Storytelling

The final notebook converts insights into **business recommendations** using an executive presentation style.

### Key Findings

- Product demand is balanced
- Online payment is slightly preferred
- High cancellation and return rate observed
- `FREESHIP` generated the highest average order value
- Facebook customers spend more
- Larger carts increase spending

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Ecommerce-Data-Analysis.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook:

```bash
jupyter notebook
```

---

## Author

**Nourhan Sayed**  
Faculty of Computers and Artificial Intelligence  
Fayoum University
