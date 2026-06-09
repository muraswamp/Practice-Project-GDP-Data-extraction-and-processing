# 🌍 Top 10 Largest Economies in the World - ETL Pipeline

This project is an automated script developed in **Python** that applies the **ETL (Extract, Transform, Load)** process to collect, clean, and structure macroeconomic data from the internet.

## 🎯 Project Objective
Acting in a Data Engineering scenario, the main goal of this script is to extract the list of the top 10 largest economies in the world (by nominal GDP) from a webpage, process the numerical values into a more readable scale (from millions to billions of dollars), and export the cleaned data for consumption.

## 🛠️ Technologies Used
* **Python 3**
* **Pandas**: For direct Web Scraping (`read_html`), *DataFrame* formatting, and cleaning structured data.
* **NumPy**: For algebraic manipulation and mathematical formatting (rounding decimal places).

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone [https://github.com/muraswamp/Practice-Project-GDP-Data-extraction-and-processing.git]
2. Instale as dependências:
   - pandas
   - numpy
   - lxml
3. Execute o script:
4. python ETL-project.py  

## 📊 Expected Output
When you run the script, it will generate a file named `Largest_economies.csv` and print the following table to your terminal:

```text
           Country  GDP (Billion USD)
1    United States           26854.60
2            China           19373.59
3            Japan            4409.74
4          Germany            4308.85
5            India            3736.88
6   United Kingdom            3158.94
7           France            2923.49
8            Italy            2169.74
9           Canada            2089.67
10          Brazil            2081.24
