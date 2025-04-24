# TESLA-AND-GAMESTOP-ANALYSIS
# 📈 Stock and Revenue Analysis Dashboard: Tesla & GameStop

This project is a part of the final peer-graded assignment for the IBM Data Science Certificate. The goal is to extract historical stock data and revenue data for **Tesla** and **GameStop**, then visualize the data using Python, yfinance and web scraping.

## 🧠 Objectives

- Extract stock data using the `yfinance` library.
- Visualize trends using a custom plotting function.
- Build side-by-side dashboards to analyze stock vs revenue for both companies.

## 🔧 Technologies Used

- Python 3
- Pandas
- yfinance
- Jupyter Notebook

## 📊 Project Structure

### 1. Tesla Stock Data (`yfinance`)
Downloaded historical stock data for Tesla using the `yfinance.Ticker("TSLA")` object.

### 2. Tesla Revenue Data (`Web Scraping`)
Scraped Tesla revenue from a JSON data source or parsed financial tables using BeautifulSoup.

### 3. GameStop Stock Data (`yfinance`)
Fetched historical GameStop stock data using the same method as Tesla.

### 4. GameStop Revenue Data (`Web Scraping`)
Revenue was scraped from a reliable JSON source or table from financial websites.

### 5. Tesla Dashboard
A line graph of Tesla's stock price over time using `matplotlib`.

### 6. GameStop Dashboard
A line graph showing GameStop's stock trend using the same graphing function.

### 7. Submission & Notebook Sharing
All code and screenshots were saved in a Jupyter Notebook and shared for peer evaluation.

## 📷 Screenshots
Each question result is shown using screenshots in the notebook.

## 🚀 How to Run

1. Clone the repo.
2. Open `data_analysis.ipynb` in Jupyter Notebook.
3. Run the cells sequentially to reproduce the graphs and results.

```bash
git clone https://github.com/yourusername/stock-dashboard-assignment.git
cd stock-dashboard-assignment
jupyter notebook Final\ Assignment-v2.ipynb
