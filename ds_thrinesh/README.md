# Trader Behavior vs Market Sentiment Analysis

## Project Links

🔗 Google Colab:
https://colab.research.google.com/drive/1J2aDgIVH_8-TtCQHSeTpiAXqV2fltO__?usp=sharing

🔗 GitHub Repository:
https://github.com/thrinesh07/bitcoin-sentiment-trader-analysis.git

🔗 Final Report (PDF):
https://drive.google.com/file/d/16ShdOMCVOnA7FLfDzvbPy_9cL8wD094b/view?usp=sharing


## Candidate Name:
Thrinesh Yerra

## Role Applied For:
Junior Data Scientist – Trader Behavior Insights

## Objective:
The goal of this project is to analyze how Bitcoin market sentiment (Fear vs Greed)
impacts trader behavior and performance. By combining historical trading data from
Hyperliquid with the Fear & Greed Index, I aimed to uncover meaningful behavioral
patterns that can help in building smarter and more data-driven trading strategies.

## Datasets Used

1. Historical Trader Data (Hyperliquid)
   - Includes: Account, Coin, Side, Closed PnL, Size USD, Timestamp, etc.

2. Bitcoin Market Sentiment Data (Fear & Greed Index)
   - Includes: Date, Classification (Fear / Greed)

## Tools & Technologies Used

- Python
- Google Colab
- Pandas
- Matplotlib
- Seaborn

## Methodology

1. Imported both datasets into Google Colab
2. Cleaned and formatted date/time columns
3. Simplified sentiment into Fear and Greed categories
4. Merged both datasets using the Date column
5. Segregated data based on sentiment
6. Performed analysis on:
   - Profitability (Closed PnL)
   - Total trading volume (Size USD)
   - Trade behavior (Buy vs Sell)
   - Best trading hours
   - Most profitable coins
7. Generated charts and a final report

## Key Insights

- Market sentiment strongly impacts trading behavior
- Greed periods tend to show higher volume and aggressive trading
- Certain coins perform significantly better during specific sentiment conditions
- Specific hours of the day are more profitable for trading
- Trade direction (Buy/Sell) also impacts total profitability

## Files Included

- notebook_1.ipynb (Main Google Colab notebook)
- csv_files/ (Processed data files)
- outputs/ (Visualizations)
- ds_report.pdf (Final report)
- README.md (This file)

## How to Run

1. Open `notebook_1.ipynb` in Google Colab
2. Upload both CSV files
3. Run all cells from top to bottom
4. All required output files will be generated automatically

Prepared by: Thrinesh Yerra



