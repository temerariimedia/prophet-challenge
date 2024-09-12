# prophet-challenge
# Mercado Libre Search Traffic & Stock Price Analysis

This project analyzes the relationship between **Mercado Libre's search traffic** and **stock price movements**. The main goal is to determine whether trends in search traffic can help predict stock price changes, and if there are any consistent patterns or spikes in search activity that align with financial events.

## Table of Contents
- [Overview](#overview)
- [Project Structure](#project-structure)
- [Analysis Steps](#analysis-steps)
- [Technologies Used](#technologies-used)
- [How to Use This Project](#how-to-use-this-project)
- [Results and Findings](#results-and-findings)
- [Conclusion](#conclusion)

## Overview
This project includes a step-by-step analysis of Mercado Libre's search traffic data alongside stock price trends. By using time-series analysis and the **Prophet model**, we aim to forecast search trends and relate them to stock price volatility and returns.

## Project Structure

```bash
mercado-libre-analysis/
│
├── data/
│   └── google_hourly_search_trends.csv      # Search trends data
│   └── stock_price_data.csv                 # Stock price data
│
├── notebooks/
│   └── mercado_libre_analysis.ipynb         # Jupyter notebook containing the full analysis
│
├── README.md                                # This README file
│
└── environment.yml                          # Environment file for dependency management
