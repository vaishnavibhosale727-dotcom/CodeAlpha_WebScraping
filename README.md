# 📚 Web Scraping & Data Visualization Project

## 📌 Project Overview
This project focuses on web scraping book data and performing data visualization using Python.

The dataset contains information about books including:
- 📖 Title
- 💰 Price
- ⭐ Rating

The data was scraped from an online books website and saved into a CSV file. 
Further analysis and visualization were performed using Python libraries.

---

## 🛠️ Technologies Used

- Python
- Pandas
- Requests
- BeautifulSoup
- Matplotlib
- Google Colab / Jupyter Notebook

---

## 📂 Project Files

- `books_all_pages1.csv` → Scraped dataset
- `webscraping.ipynb` → Python notebook containing scraping + visualization code

---

## 🔎 Steps Performed

### 1️⃣ Web Scraping
- Sent HTTP requests to website
- Parsed HTML using BeautifulSoup
- Extracted:
  - Book Title
  - Price
  - Rating
- Stored data into Pandas DataFrame
- Exported data to CSV file

### 2️⃣ Data Cleaning
- Removed currency symbol (£) from Price
- Converted Price column to float
- Converted Rating (One, Two, Three, etc.) into numeric format

### 3️⃣ Data Visualization
Created visualizations such as:
- 📊 Price Distribution
- ⭐ Rating Count Plot
- 📈 Average Price by Rating

## 📊 Sample Output

Example Data:

| Title                    |  Price       | Rating |

| A Light in the Attic     | 51.77          | 3 |
| Tipping the Velvet       | 53.74          | 1 |


## 🚀 How to Run

1. Clone the repository:
2. 2. Open `webscraping.ipynb` in Jupyter Notebook or Google Colab

3. Run all cells

---

## 🎯 Learning Outcomes

- Understanding of Web Scraping
- HTML Parsing
- Data Cleaning using Pandas
- Data Visualization
- CSV file handling
- Real-world data pipeline creation

---

## 👨‍💻 Author
Vaishnavi Bhosale
