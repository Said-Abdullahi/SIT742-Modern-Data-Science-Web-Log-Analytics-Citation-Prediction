# Modern-Data-Science-Web-Log-Analytics-Citation-Prediction

## Project Overview

This project was completed as part of SIT742 (Modern Data Science) at Deakin University. The assignment focused on two main tasks:

1. **Web Log Analytics:** Analysis of over 8 million web log entries for Hotel TULIP, a five-star hotel located at Deakin University. The goal was to uncover user access patterns and server performance using data science and machine learning techniques.
2. **Professor Citation Prediction:** Web crawling and time series analysis to collect and predict citation metrics for A/Professor Gang Li from 2003 to 2021, using ARIMA models and grid search for optimal parameter selection.

## Background

- **Web Log Analytics:** The web logs provided insights into how users accessed the hotel’s website, including peak traffic hours, server status distributions, and geographic origins of requests.
- **Citation Prediction:** The citation data for A/Professor Gang Li was collected from Google Scholar and analyzed to predict future citation trends using advanced time series models.

## Data Collection

- **Web Log Data:** Over 8 million log entries from Hotel TULIP’s web server, containing fields such as date, time, IP address, request method, URI, user agent, and server status.
- **Citation Data:** Citation counts for A/Professor Gang Li from 2003 to 2021, collected via web crawling using the `scholarly` Python library.

## Data Description

| Data Source         | Key Fields/Features                                    | Description                                      |
|---------------------|-------------------------------------------------------|--------------------------------------------------|
| Web Logs            | date, time, s-ip, cs-method, cs-uri-stem, user-agent, sc-status | HTTP requests and server responses                |
| Citation Data       | year, citation                                        | Annual citation counts for a professor            |

## Usage

### Prerequisites

- **Python 3.7+**
- **Jupyter Notebook**
- **Required Libraries:**

### Running the Project

1. **Web Log Analytics:**
- Open the Jupyter notebook in `notebooks/` for data loading, cleaning, exploratory analysis, and machine learning tasks.
- The notebook includes code for data ETL, feature selection, unsupervised learning (K-means), supervised learning (Logistic Regression, Decision Trees), and association rule mining.

2. **Citation Prediction:**
- The notebook includes code for web crawling to collect citation data.
- Time series analysis and ARIMA modeling are performed to predict future citations.
- Grid search is used to find optimal ARIMA parameters.

## Results

- **Web Log Analytics:** Insights into server usage, peak traffic hours, and user behavior. Machine learning models achieved high accuracy in predicting server status codes.
- **Citation Prediction:** ARIMA models successfully predicted citation trends, with RMSE metrics and visualizations provided for model evaluation.
